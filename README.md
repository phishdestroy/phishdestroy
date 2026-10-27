<picture>
  <source media="(max-width: 600px)" srcset="assets/hero-video-mobile.webp">
  <img src="assets/hero-video.webp" width="100%" alt="PhishDestroy — We don’t just block. We burn it all down.">
</picture>

<p align="center"><img src="assets/typing.svg" width="760" alt="We don’t just block. We burn it all down. Scorched earth for phishing infrastructure. Neutralize. Erase. Repeat. Your domain is evidence now. Every restart costs you more."></p>

<p align="center">
  <a href="https://phishdestroy.io/"><img src="assets/button-website.svg" height="34" alt="Website"></a>
  <a href="https://phishdestroy.io/live/"><img src="assets/button-monitor.svg" height="34" alt="Live monitor"></a>
  <a href="https://github.com/phishdestroy/destroylist"><img src="assets/button-feeds.svg" height="34" alt="Threat feeds"></a>
  <a href="https://api.destroy.tools/"><img src="assets/button-api.svg" height="34" alt="Public API — free, no key"></a>
  <a href="https://t.me/PhishDestroy_bot"><img src="assets/button-report.svg" height="34" alt="Report a threat"></a>
  <a href="https://phishdestroy.io/appeals/"><img src="assets/button-appeals.svg" height="34" alt="Appeal a listing — 24-hour maximum"></a>
  <a href="mailto:github@phishdestroy.io"><img src="assets/button-email.svg" height="34" alt="Email github@phishdestroy.io"></a>
</p>

## Scorched earth for phishing infrastructure.

If you build phishing sites, drain wallets, or knowingly push scam “offers,” we want your operation to fail. Domains flagged. Providers holding the evidence. Every restart costing you more.

We started after watching scam domains survive for years through hundreds of complaints. Cheap to launch, years of victims, no consequences. We're here to wreck that deal. We scan, archive, report and follow up, and keep it all public, so a dead link or a fresh domain doesn't wipe the record.

<picture>
  <source media="(max-width: 600px)" srcset="assets/workflow-mobile.svg">
  <img src="assets/workflow.svg" width="100%" alt="Scan, archive, report, follow up — the work we can do ourselves">
</picture>

<details>
<summary><strong>How we hunt</strong></summary>

A domain is a starting point. We follow the certificates, infrastructure, code and money around it.

- **Certificate Transparency (CT) logs:** watch certificate records for new domains, related hostnames and recurring naming patterns.
- **Passive DNS:** trace historical IP addresses, nameservers and DNS changes to follow infrastructure as it moves.
- **Hosting & ASN correlation:** compare network ranges, hosting providers and registration history to map related infrastructure.
- **YARA & phishing-kit fingerprints:** match recurring code and artifacts across captured pages, phishing kits and malware samples.
- **On-chain transaction analysis:** follow wallet addresses and transaction flows to investigate reported theft, drainer activity and connections between cases.
- **Malware reverse engineering:** inspect scripts, APKs and malware samples to understand their behavior and extract indicators for further investigation.

</details>

<details>
<summary><strong>Five years online, hundreds of complaints</strong></summary>

Registrars say they don't allow scams. Hosts say the same. Yet some of these sites steal for years. So what happened to the complaints?

Often the report didn't show the scam. Cloaking served scanners a harmless page, so we showed what the victim sees: screenshots, archives, even video. Every scam that survives has a reason. We find it, fill the gap in the evidence, report again and log the response.

Scams are against everyone's rules. When the evidence arrives, that should mean something.

</details>

<details>
<summary><strong>A dead website can take the evidence with it</strong></summary>

We've investigated operations where every site was already gone: no scan, no archive, nothing showing what the domain did. A dead link proves nothing.

So we capture while there's something to capture. Months later an investigator or regulator may need exactly that page. That's also why the database is on GitHub: what we found, when we reported it, and where we might be wrong, all public.

</details>

<details>
<summary><strong>Who gets the credit?</strong></summary>

We don't have a “delete” button. When a registrar suspends a domain, that's their call. When another researcher cracks a case, that's their work. We don't need the score.

We want scammers losing time and money. Domains that once ran for years now get replaced in days or hours. That's the whole field's work, and we're part of it.

PhishDestroy is unpaid and non-commercial. No money, no obligations, nothing to gain from any particular ban or verdict.

</details>

<details>
<summary><strong>The hostility is deliberate</strong></summary>

No sympathy for phishing crews, drainer operators, or “affiliates” sending victims into scams. Whatever you call it, you're helping steal.

A scam losing its domain, its traffic or its cash-out route is exactly what we're working for.

But hacked sites are victims too, and our data can be wrong. That's why it's public and why appeals exist. Listed by mistake? We fix it and say sorry.

</details>

<p align="center"><img src="assets/divider.svg" width="100%" alt=""></p>


## <a name="open-data"></a>Public data. Use it.

Check a domain, download the public list, or follow the evidence in a domain report. Free API. No key.

<p align="center">
  <a href="https://api.destroy.tools/"><img src="assets/button-data-api.svg" height="34" alt="Public API documentation — no key required"></a>
  <a href="https://raw.githubusercontent.com/phishdestroy/destroylist/main/list.json"><img src="assets/button-data-list.svg" height="34" alt="Download the public domain list as JSON"></a>
  <a href="https://phishdestroy.io/dataset"><img src="assets/button-data-dataset.svg" height="34" alt="Explore the research dataset and download formats"></a>
  <a href="https://phishdestroy.io/domain/"><img src="assets/button-data-reports.svg" height="34" alt="Search public domain reports and evidence"></a>
</p>


Connect AI tools through [MCP](https://api.destroy.tools/#mcp): `https://api.destroy.tools/mcp`.

## Already in motion

<picture>
  <source media="(max-width: 600px)" srcset="assets/roadmap-mobile.svg">
  <img src="assets/roadmap.svg" width="100%" alt="Running: collect, publish, scan and report. Growing: IOCs, fingerprints and evidence. Underway: Gemini has used our findings; API and MCP provide live checks.">
</picture>

**Next:** broader coverage and more AI systems checking the evidence before recommending a site.

<details>
<summary><strong>AI should spot the scam before it recommends it</strong></summary>

We've seen AI recommend scam sites. One was [xmrwallet[.]com](https://github.com/phishdestroy/DO-NOT-USE-xmrwallet-com), a wallet scam running since 2016. A decade online, and a model still sent people there.

So we're building records AI can use: IOCs, fingerprints, recurring patterns, scans, archives, and how each scam works. A new domain shouldn't make the same operation unrecognizable.

The goal: a model checks before it recommends, and warns the person before they connect a wallet, paste a seed phrase or send money. Our API and MCP already provide live checks.

</details>

<p align="center"><img src="assets/divider.svg" width="100%" alt=""></p>

## Public feeds & investigations

Our scans, reports and investigation files are here.

<p align="center">
  <a href="https://github.com/phishdestroy/destroylist"><img src="https://my-readme-stats-wine.vercel.app/api/pin/?username=phishdestroy&amp;repo=destroylist&amp;theme=dark&amp;hide_border=true" width="400" alt="destroylist: description, language, stars and forks"></a>
  <a href="https://github.com/phishdestroy/DestroyScammers"><img src="https://my-readme-stats-wine.vercel.app/api/pin/?username=phishdestroy&amp;repo=DestroyScammers&amp;theme=dark&amp;hide_border=true" width="400" alt="DestroyScammers: description, language, stars and forks"></a>
</p>

<p align="center">
  <a href="https://github.com/phishdestroy/Operation-Takedown"><img src="https://my-readme-stats-wine.vercel.app/api/pin/?username=phishdestroy&amp;repo=Operation-Takedown&amp;theme=dark&amp;hide_border=true" width="400" alt="Operation-Takedown: description, language, stars and forks"></a>
  <a href="https://github.com/phishdestroy/ScamIntelLogs"><img src="https://my-readme-stats-wine.vercel.app/api/pin/?username=phishdestroy&amp;repo=ScamIntelLogs&amp;theme=dark&amp;hide_border=true" width="400" alt="ScamIntelLogs: description, language, stars and forks"></a>
</p>

<p align="center">
  <a href="https://github.com/phishdestroy/shortdot-evidence"><img src="https://my-readme-stats-wine.vercel.app/api/pin/?username=phishdestroy&amp;repo=shortdot-evidence&amp;theme=dark&amp;hide_border=true" width="400" alt="shortdot-evidence: description, language, stars and forks"></a>
  <a href="https://github.com/phishdestroy/nicenic-evidence"><img src="https://my-readme-stats-wine.vercel.app/api/pin/?username=phishdestroy&amp;repo=nicenic-evidence&amp;theme=dark&amp;hide_border=true" width="400" alt="nicenic-evidence: description, language, stars and forks"></a>
</p>

<p align="center">
  <a href="https://github.com/phishdestroy/namesilo-evidence"><img src="https://my-readme-stats-wine.vercel.app/api/pin/?username=phishdestroy&amp;repo=namesilo-evidence&amp;theme=dark&amp;hide_border=true" width="400" alt="namesilo-evidence: description, language, stars and forks"></a>
  <a href="https://github.com/phishdestroy/trustname-evidence"><img src="https://my-readme-stats-wine.vercel.app/api/pin/?username=phishdestroy&amp;repo=trustname-evidence&amp;theme=dark&amp;hide_border=true" width="400" alt="trustname-evidence: description, language, stars and forks"></a>
</p>

### <a name="evidence"></a>Investigation dashboards

<p align="center">
<a href="https://phishdestroy.github.io/namesilo-evidence/#analytics"><img src="assets/button-analytics-namesilo.svg" height="34" alt="namesilo analytics"></a>
<a href="https://phishdestroy.github.io/nicenic-evidence/#analytics"><img src="assets/button-analytics-nicenic.svg" height="34" alt="nicenic analytics"></a>
<a href="https://phishdestroy.github.io/shortdot-evidence/#analytics"><img src="assets/button-analytics-shortdot.svg" height="34" alt="shortdot analytics"></a>
<a href="https://phishdestroy.github.io/trustname-evidence/#analytics"><img src="assets/button-analytics-trustname.svg" height="34" alt="trustname analytics"></a>
</p>

<p align="center"><img src="assets/divider.svg" width="100%" alt=""></p>


## <a name="appeals"></a>If we get it wrong

Wrongly listed? [Tell us.](https://phishdestroy.io/appeals/) No account, no proof of ownership, just the domain and a few words. Clear cases are approved automatically within minutes. If a human needs to look, the public report is hidden during review.

**Every appeal gets 24 hours, max.** No decision by then means it's approved automatically, and the domain is removed from the site, GitHub and the database.

**[Appeal a listing](https://phishdestroy.io/appeals/)** · [Choose an issue template](https://github.com/phishdestroy/destroylist/issues/new/choose)

<p align="center"><img src="assets/divider.svg" width="100%" alt=""></p>

## A little less serious

<p align="center"><a href="https://github.com/phishdestroy?tab=overview"><img src="https://raw.githubusercontent.com/phishdestroy/phishdestroy/refs/heads/output/github-contribution-grid-snake-dark.svg" width="880" alt="Animated snake eating our GitHub contribution grid"></a></p>

<details>
<summary><strong>GitHub activity, statistics & trophies</strong></summary>

### <a name="stats"></a>Statistics & Activity

<p align="center">
  <a href="https://stats.hyo.dev/stats/phishdestroy"><img src="https://stats.hyo.dev/api/github-stats-advanced?login=phishdestroy" width="700" alt="PhishDestroy GitHub overview from stats.hyo.dev"></a>
</p>

<p align="center">
  <a href="https://stats.hyo.dev/stats/phishdestroy"><img src="https://stats.hyo.dev/api/github-trophies?login=phishdestroy" width="700" alt="PhishDestroy trophy card from stats.hyo.dev"></a>
</p>

<p align="center">
  <img src="https://my-readme-stats-wine.vercel.app/api?username=phishdestroy&amp;show_icons=true&amp;theme=dark&amp;hide_border=true&amp;card_width=437&amp;line_height=24" width="348" alt="PhishDestroy GitHub statistics">
  <img src="https://my-readme-stats-wine.vercel.app/api/top-langs/?username=phishdestroy&amp;layout=compact&amp;theme=dark&amp;hide_border=true&amp;card_width=437&amp;langs_count=8" width="348" alt="Most used languages">
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=phishdestroy&amp;theme=dark&amp;hide_border=true" width="700" alt="PhishDestroy GitHub contribution streak">
</p>

<p align="center">
  <img src="https://github-trophies.vercel.app/?username=phishdestroy&amp;theme=onedark&amp;no-frame=true&amp;margin-w=15" width="700" alt="PhishDestroy GitHub trophies">
</p>

<p align="center">
  <a href="https://github.com/phishdestroy?tab=overview">View GitHub contribution activity</a>
</p>

<p align="center">
  <img src="https://ghchart.rshah.org/58a6ff/phishdestroy" width="700" alt="GitHub contribution calendar">
</p>

<details>
<summary><strong>More stats</strong></summary>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=phishdestroy&amp;theme=github_dark" width="700" alt="GitHub profile and contribution history">
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=phishdestroy&amp;theme=github_dark" width="348" alt="Top languages by repository">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=phishdestroy&amp;theme=github_dark" width="348" alt="Top languages by commit">
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=phishdestroy&amp;theme=github_dark" width="348" alt="GitHub activity totals">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=phishdestroy&amp;theme=github_dark&amp;utcOffset=3" width="348" alt="Commits by hour, UTC+3">
</p>

</details>

</details>


<p align="center"><img src="assets/footer-wave.svg" width="100%" alt=""></p>


<p align="center">
  <strong>We don’t just block. We burn it all down.</strong><br>
  <sub>Independent, non-commercial work since 2019.</sub><br>
  <sub><a href="mailto:github@phishdestroy.io">github@phishdestroy.io</a></sub>
</p>
<p align="center">
  <a href="https://phishdestroy.io/"><img src="assets/button-website.svg" height="34" alt="Website"></a>
  <a href="https://phishdestroy.io/live/"><img src="assets/button-monitor.svg" height="34" alt="Live monitor"></a>
  <a href="https://github.com/phishdestroy/destroylist"><img src="assets/button-feeds.svg" height="34" alt="Threat feeds"></a>
  <a href="https://api.destroy.tools/"><img src="assets/button-api.svg" height="34" alt="Public API — free, no key"></a>
  <a href="https://t.me/PhishDestroy_bot"><img src="assets/button-report.svg" height="34" alt="Report a threat"></a>
  <a href="https://phishdestroy.io/appeals/"><img src="assets/button-appeals.svg" height="34" alt="Appeal a listing — 24-hour maximum"></a>
  <a href="mailto:github@phishdestroy.io"><img src="assets/button-email.svg" height="34" alt="Email github@phishdestroy.io"></a>
</p>

