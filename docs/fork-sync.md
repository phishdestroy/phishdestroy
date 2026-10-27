# Fork synchronization

Each configured public fork checks its upstream default branch every 12 hours.
Schedules are staggered across the day; GitHub Actions may delay scheduled jobs.
Manual runs are available under **Actions → Sync upstream (12 hours)**.

The reusable workflow is pinned to a commit in this repository. It uses only the
calling repository's built-in `GITHUB_TOKEN`; no personal token or shared secret
is stored. It merges shallow snapshots without running code from the fork.

- Fork commits and independent changes are preserved. Conflicts fail the job
  without updating the branch. Pushes are never forced.
- Existing fork workflows are preserved. Upstream workflows are not imported
  or executed by synchronization.
- `.github/fork-sync-state.json` records the last successful upstream snapshot.
  A monthly state refresh keeps quiet forks from reaching GitHub's 60-day
  scheduled-workflow inactivity limit.
- Archived/disabled repositories and upstreams are skipped.
- Each fork follows its actual GitHub parent. The separate `openphish` fork
  provides the current OpenPhish feed. TweetFeed and Hagezi have audited initial recovery
  snapshots because their upstream histories were rewritten.
- The `DO-NOT-USE-xmrwallet-com` investigation remains outside automatic sync.

Review failures in the workflow job summary. A missing common ancestor is only
recoverable from the recorded upstream snapshot; unknown histories are never
silently replaced. Future forks need the same caller workflow installed.
