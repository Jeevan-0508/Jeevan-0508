<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b0f14,45:0ea5e9,100:38bdf8&height=210&section=header&text=Jeevan&fontSize=68&fontColor=e2e8f0&fontAlignY=33&desc=Risk%20Operations%20%E2%80%A2%20AI%20Governance%20%E2%80%A2%20Automation&descSize=17&descAlignY=53&animation=fadeIn" width="100%" alt="" />

<a href="https://jeevan-0508.github.io">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=3400&pause=800&color=38BDF8&center=true&vCenter=true&width=820&height=48&lines=Risk+Manager+%40+Amazon+Transportation;I+hunt+Supply+chain+fraud+across+EU+%26+NA+regions;Then+I+open-source+the+methodology;EU+AI+Act+%C2%B7+GDPR+%C2%B7+ISO+42001+%C2%B7+NIST+AI+RMF" alt="" />
</a>

<br/>

<a href="https://jeevan-0508.github.io"><img src="https://img.shields.io/badge/%F0%9F%8C%90_Portfolio-jeevan--0508.github.io-38bdf8?style=for-the-badge&labelColor=0b0f14" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/jeevan-siddhabhaktula-6927041a2/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0b0f14" alt="LinkedIn" /></a>
<a href="mailto:jeevansiddhabhaktula@gmail.com"><img src="https://img.shields.io/badge/Email-Say_hello-e2e8f0?style=for-the-badge&logo=gmail&logoColor=e2e8f0&labelColor=0b0f14" alt="Email" /></a>
<img src="https://komarev.com/ghpvc/?username=Jeevan-0508&style=for-the-badge&color=38bdf8&labelColor=0b0f14&label=Visitors" alt="" />

</div>

---

<div align="center">

### ⚡ Here's what I do

</div>

<table>
<tr>
<td width="50%" valign="top">

#### 🚚 Catch freight fraud
Missing trailers, cargo theft, identity fraud, internal collusion — across **EU and NA lanes** for Amazon Transportation. Then I write down the method so other teams can use it.

</td>
<td width="50%" valign="top">

#### ⚖️ Make regulation usable
EU AI Act, GDPR, ISO/IEC 42001, NIST AI RMF — turned into tools a team can act on in an **afternoon** instead of a quarter.

</td>
</tr>
</table>

<div align="center">

*Everything below runs client-side or offline. No uploads, no server, no telemetry, **zero dependencies**.*

</div>

---

<div align="center">

### 🧬 How the pieces connect

</div>

```mermaid
flowchart LR
    A["🔍 Carrier fraud investigations<br/>Amazon Transportation"]
    B["📖 freight-fraud-taxonomy<br/>12 patterns · 77 indicators"]
    C["🗺️ freight-risk-atlas<br/>control-coverage scoring"]
    D["📡 FOMO<br/>EU risk news monitor"]
    E["📜 EU AI Act · GDPR<br/>ISO 42001 · NIST AI RMF"]
    F["🇪🇺 eu-ai-act-scanner"]
    G["🔒 gdpr-compliance-scanner"]
    H["🎛️ ai-governance-control-room<br/>4 frameworks · 56 reqs · 29 controls"]

    A --> B --> C
    A --> D
    E --> F --> H
    E --> G --> H

    classDef freight fill:#0b2b3a,stroke:#38bdf8,stroke-width:2px,color:#e2e8f0
    classDef gov fill:#1e1b4b,stroke:#818cf8,stroke-width:2px,color:#e2e8f0
    classDef src fill:#111823,stroke:#5b6b82,stroke-width:1px,color:#8b9bb4
    class A,B,C,D freight
    class F,G,H gov
    class E src
```

---

<div align="center">

### 🚚 Freight &amp; carrier fraud

</div>

<table>
<tr><td width="30%" valign="top">

**[freight-fraud-taxonomy](https://github.com/Jeevan-0508/freight-fraud-taxonomy)**

<img src="https://img.shields.io/github/stars/Jeevan-0508/freight-fraud-taxonomy?style=flat-square&color=38bdf8&labelColor=0b0f14" alt="" />
<img src="https://img.shields.io/badge/CC_BY_4.0-open-38bdf8?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

An open reference taxonomy of freight and carrier fraud — **12 patterns**, **77 detection indicators**, **137 countermeasures** split preventive / detective / responsive, plus **31 false-positive tests** so the indicators don't fire on legitimate carriers. Sourced to 11 public references.

</td></tr>

<tr><td width="30%" valign="top">

**[freight-risk-atlas](https://github.com/Jeevan-0508/freight-risk-atlas)**

<a href="https://jeevan-0508.github.io/freight-risk-atlas/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-38bdf8?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/tests-86_passing-22c55e?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

A carrier risk **assessment** engine — scores how well controls cover three stages: pre-award, in transit, post-event. It measures coverage, not probability of fraud, and says so. Ships an interactive detection timeline and a fraud-pattern relationship network.

</td></tr>

<tr><td width="30%" valign="top">

**[FOMO](https://github.com/Jeevan-0508/FOMO)**

<a href="https://jeevan-0508.github.io/FOMO/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-38bdf8?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/refresh-every_6h-38bdf8?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

A logistics and supply-chain risk news monitor for the German/EU market. English **and** German sources, categorised by risk type, re-scanned automatically every six hours by a GitHub Action.

</td></tr>

<tr><td width="30%" valign="top">

**[fraud-watch](https://github.com/Jeevan-0508/fraud-watch)**

<a href="https://jeevan-0508.github.io/fraud-watch/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-38bdf8?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/MIT-open-38bdf8?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

A living freight-fraud investigation simulator. A freight network runs itself — trucks, drivers, trailers and carriers over a real topology — and the analyst sees only what was *recorded*. What actually happened is held in the simulation and is structurally unreachable from every analyst-facing surface, so the exercise cannot be gamed by reading the answer.

</td></tr>

<tr><td width="30%" valign="top">

**[shrink-signal](https://github.com/Jeevan-0508/shrink-signal)**

<a href="https://jeevan-0508.github.io/shrink-signal/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-38bdf8?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/sources-Eurostat_%2B_BKA-38bdf8?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

A loss-prevention reading of European police-recorded crime: **8 Eurostat offence categories**, **41 countries**, 2008–2024 — plus a German **BKA** panel that reaches 2025, carries a shoplifting category Eurostat has no code for, and breaks down to all **16 Bundesländer**. The reasons it might be wrong are printed above the charts, not in a footnote.

</td></tr>

<tr><td width="30%" valign="top">

**[one-more-shift](https://github.com/Jeevan-0508/one-more-shift)**

<a href="https://jeevan-0508.github.io/one-more-shift/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-38bdf8?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/tests-24_passing-22c55e?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

A tiny farewell arcade game built on the taxonomy above: flag or clear **108 real cards** — 77 genuine risk indicators, 31 genuine innocent explanations — against a 60-second clock that tightens its pace in the last third. Best score persists locally. No invented data, no backend.

</td></tr>
</table>

<div align="center">

### ⚖️ AI governance &amp; compliance

</div>

<table>
<tr><td width="30%" valign="top">

**[ai-governance-control-room](https://github.com/Jeevan-0508/ai-governance-control-room)**

<a href="https://jeevan-0508.github.io/ai-governance-control-room/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-818cf8?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/frameworks-4-818cf8?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

An operator console for AI governance. **4 frameworks** mapped to **56 requirements** and **29 controls**, with **84 evidence artefacts** — so for any one control you can see everything it satisfies at once. 8 controls span three or more frameworks.

</td></tr>

<tr><td width="30%" valign="top">

**[eu-ai-act-scanner](https://github.com/Jeevan-0508/eu-ai-act-scanner)**

<a href="https://jeevan-0508.github.io/eu-ai-act-scanner"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-818cf8?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/PWA-offline-818cf8?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

Classify an AI system against **Regulation (EU) 2024/1689** in about ten minutes. **14 risk-qualifier questions**, each mapped to a specific article with an "explain why" panel → **22 requirements across 5 risk tiers** → compliance score, ISO 42001 + NIST AI RMF crosswalks, exportable report.

</td></tr>

<tr><td width="30%" valign="top">

**[gdpr-compliance-scanner](https://github.com/Jeevan-0508/gdpr-compliance-scanner)**

<a href="https://jeevan-0508.github.io/gdpr-compliance-scanner/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-818cf8?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/data-never_uploaded-22c55e?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

Drop in a CSV / Excel / JSON file, get an instant GDPR exposure report: which columns hold personal data, how sensitive, what to do about it. **35 field-name rules + 9 value-regex detectors**, risk score out of 100. Parsing happens in your browser — the file never leaves your machine.

</td></tr>

<tr><td width="30%" valign="top">

**[reg-search](https://github.com/Jeevan-0508/reg-search)**

<a href="https://jeevan-0508.github.io/reg-search/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-818cf8?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/tests-11_passing-22c55e?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

Natural-language search over the Control Room's 56 cited requirements, ranked with a **BM25 implementation written from scratch** — no embeddings, no external model, no API key. Shows exactly which query terms earned a result its rank.

</td></tr>

<tr><td width="30%" valign="top">

**[dora-compliance-scanner](https://github.com/Jeevan-0508/dora-compliance-scanner)**

<a href="https://jeevan-0508.github.io/dora-compliance-scanner/docs/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-818cf8?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/requirements-19-818cf8?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

Self-assessment coverage against **Regulation (EU) 2022/2554 (DORA)** — **19 cited requirements** across the ICT risk-management, incident-reporting, resilience-testing and third-party pillars. Answer, score, export; the citation for every requirement travels with it.

</td></tr>

<tr><td width="30%" valign="top">

**[POLICY//AUDIT](https://github.com/Jeevan-0508/policy-audit)**

<a href="https://jeevan-0508.github.io/policy-audit/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-818cf8?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/tests-12_passing-22c55e?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

The evidence side of governance: feed it a document corpus (policy, architecture, code) and it finds where regulation → control → documented policy → actual implementation diverges, with every finding traced back to the source text. Doesn’t replace a control room — feeds one.

</td></tr>
</table>

---

<div align="center">

### 🧪 Risk tooling &amp; multi-agent systems

</div>

<table>
<tr><td width="30%" valign="top">

**[risk-swarm](https://github.com/Jeevan-0508/risk-swarm)**

<a href="https://jeevan-0508.github.io/risk-swarm/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-a78bfa?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/tests-815_passing-22c55e?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

Seven named agents investigate a real repository together — one maps it, one stress-tests it, one audits the others. **815 tests across 60 files, 30 of them adversarial attacks** (16 guard-layer + 14 council-layer) against the agents themselves, because an investigator you cannot attack is one you cannot trust.

</td></tr>

<tr><td width="30%" valign="top">

**[shadow-network](https://github.com/Jeevan-0508/shadow-network)**

<a href="https://jeevan-0508.github.io/shadow-network/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-a78bfa?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/tests-80_passing-22c55e?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

A persistent synthetic freight-carrier economy that ticks forward one real day at a time via an unattended GitHub Action, while a BYOK AI council investigates flagged incidents from a redacted case brief that never carries the sim's own ground truth. A public leaderboard tracks the council's win rate against fraud it never gets to see labelled.

</td></tr>

<tr><td width="30%" valign="top">

**[risk-os](https://github.com/Jeevan-0508/risk-os)**

<a href="https://jeevan-0508.github.io/risk-os/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-a78bfa?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/MIT-open-a78bfa?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

An operational risk register that runs entirely in the browser — register, scoring, treatment plans and review cycles, with import/export so the data stays yours. No account, no server, no telemetry.

</td></tr>

<tr><td width="30%" valign="top">

**[RISK//REPLAY](https://github.com/Jeevan-0508/risk-replay)**

<a href="https://jeevan-0508.github.io/risk-replay/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-a78bfa?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/tests-102_passing-22c55e?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

AI decision forensics: replay a model’s past decision deterministically, mutate one input, and see exactly how the outcome and its governance score would have changed — a counterfactual you can inspect, not just an accuracy number.

</td></tr>

<tr><td width="30%" valign="top">

**[RISK//RING](https://github.com/Jeevan-0508/risk-ring)**

<img src="https://img.shields.io/badge/tests-10_passing-22c55e?style=flat-square&labelColor=0b0f14" alt="" />
<img src="https://img.shields.io/badge/data-simulated%2C_labelled-a78bfa?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

A trained fraud classifier evaluated against ground truth from a simulator built to have some (structuring, layering, collusion rings), not a downloaded 99.8%-legitimate CSV. Honest metrics, SHAP explainability, graph-based collusion-ring detection.

</td></tr>

<tr><td width="30%" valign="top">

**[FORECAST//LEDGER](https://github.com/Jeevan-0508/Forecast-Ledger)**

<img src="https://img.shields.io/badge/tests-59_passing-22c55e?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

Seals a forecast before the outcome exists, grades it once reality arrives, and refuses to forecast when the history can’t support the evaluation protocol. Real Eurostat data, rolling-origin backtest, MASE, no hindsight.

</td></tr>
</table>

<div align="center">

### 🌌 Science, built to be explored

</div>

<table>
<tr><td width="30%" valign="top">

**[scale-of-everything](https://github.com/Jeevan-0508/scale-of-everything)**

<a href="https://jeevan-0508.github.io/scale-of-everything/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-22d3ee?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/three.js-in--browser_AI-22d3ee?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

An interactive zoom through **ten scales of the universe**, from one planet surface to the edge of the observable universe — then two steps further, into territory explicitly labelled *not measured*. Two AI models run in your browser: one searches by meaning, one talks.

</td></tr>

<tr><td width="30%" valign="top">

**[quantum-galaxy](https://github.com/Jeevan-0508/quantum-galaxy)**

<a href="https://jeevan-0508.github.io/quantum-galaxy/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-22d3ee?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/concepts-20-22d3ee?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

An interactive 3D galaxy for quantum physics: **20 concepts** orbit as planets across **5 themed solar systems** around a central black hole. Ask a question in plain language and an in-browser AI flies you to the concept that answers it.

</td></tr>
</table>

<div align="center">

### 🎮 Interactive engineering

</div>

<table>
<tr><td width="30%" valign="top">

**[NIGHTFALL // ZERO](https://github.com/Jeevan-0508/nightfall-zero)**

<a href="https://jeevan-0508.github.io/nightfall-zero/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-f472b6?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/tests-330_passing-22c55e?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

A browser survival-shooter with a deterministic engine underneath the spectacle: waves, weapons, bosses, maps and loadouts, built in autonomous phased sessions with a real test suite over the pure engine/AI/collision logic.

</td></tr>

<tr><td width="30%" valign="top">

**[HAKAI // WORLD](https://github.com/Jeevan-0508/hakai_world)**

<a href="https://jeevan-0508.github.io/hakai_world/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-f472b6?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/tests-135%2F137_passing-eab308?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

An explorable 2.5D living world built from the [HAKAI Protocol](https://github.com/Jeevan-0508/hakai-protocol-v2) universe — same creatures and lore, walked into instead of clicked through. Two known test failures are named in the README, not hidden.

</td></tr>

<tr><td width="30%" valign="top">

**[RULESHIFT](https://github.com/Jeevan-0508/ruleshift)**

<a href="https://jeevan-0508.github.io/ruleshift/"><img src="https://img.shields.io/badge/%E2%96%B6_live-demo-f472b6?style=flat-square&labelColor=0b0f14" alt="live" /></a>
<img src="https://img.shields.io/badge/tests-27_passing-22c55e?style=flat-square&labelColor=0b0f14" alt="" />

</td><td valign="top">

A puzzle game where the rules are never quite what they seem — every generated level is BFS-verified solvable before it’s shown, so a level that looks unfair is provably not.

</td></tr>
</table>

---

<div align="center">

### 📊 What this looks like at work

**Risk Manager · Amazon Transportation · ROC / TIO / RCMT**

</div>

<div align="center">

| | |
|:--|--:|
| Model-driven fraud prevention impact | **&gt;$15M** |
| Reduction in EU/NA carrier-audit false positives | **~40%** |
| Loss-forecasting engine accuracy | **~95%** |
| Risk reporting automated, manual → generated | **~90%** |
| Monthly audit events monitored | **80K+** |
| Investigators working off the RCMT wiki + SOPs I wrote | **20+** |

</div>

<div align="center">

<sub>I apply <b>DMAIC</b> to risk problems: find the risk → analyse the data behind it → automate the manual step out of it → measure whether it actually moved.</sub>

</div>

---

<div align="center">

### 🛠️ Stack

**Build**

<img src="https://skillicons.dev/icons?i=python&theme=dark" width="48" height="48" title="Python" alt="Python" />
<img src="https://skillicons.dev/icons?i=js&theme=dark" width="48" height="48" title="JavaScript" alt="JavaScript" />
<img src="https://skillicons.dev/icons?i=html&theme=dark" width="48" height="48" title="HTML5" alt="HTML5" />
<img src="https://skillicons.dev/icons?i=css&theme=dark" width="48" height="48" title="CSS3" alt="CSS3" />
<img src="https://skillicons.dev/icons?i=flask&theme=dark" width="48" height="48" title="Flask" alt="Flask" />
<img src="https://skillicons.dev/icons?i=aws&theme=dark" width="48" height="48" title="AWS" alt="AWS" />
<img src="https://skillicons.dev/icons?i=git&theme=dark" width="48" height="48" title="Git" alt="Git" />
<img src="https://skillicons.dev/icons?i=githubactions&theme=dark" width="48" height="48" title="GitHub Actions" alt="GitHub Actions" />
<img src="https://skillicons.dev/icons?i=mysql&theme=dark" width="48" height="48" title="MySQL" alt="MySQL" />
<img src="https://skillicons.dev/icons?i=bash&theme=dark" width="48" height="48" title="Bash" alt="Bash" />
<img src="https://skillicons.dev/icons?i=powershell&theme=dark" width="48" height="48" title="PowerShell" alt="PowerShell" />
<img src="https://skillicons.dev/icons?i=markdown&theme=dark" width="48" height="48" title="Markdown" alt="Markdown" />

<sub><i>hover any icon for its name</i></sub>

**Risk &amp; fraud**

<img src="https://img.shields.io/badge/Fraud_Detection-38bdf8?style=for-the-badge&labelColor=0b0f14" alt="Fraud Detection" />
<img src="https://img.shields.io/badge/Carrier_Vetting-38bdf8?style=for-the-badge&labelColor=0b0f14" alt="Carrier Vetting" />
<img src="https://img.shields.io/badge/Cargo_Theft_Investigation-38bdf8?style=for-the-badge&labelColor=0b0f14" alt="Cargo Theft Investigation" />
<img src="https://img.shields.io/badge/Identity_Fraud-38bdf8?style=for-the-badge&labelColor=0b0f14" alt="Identity Fraud" />
<img src="https://img.shields.io/badge/Anomaly_Detection-38bdf8?style=for-the-badge&labelColor=0b0f14" alt="Anomaly Detection" />
<img src="https://img.shields.io/badge/Supply_Chain_Security-38bdf8?style=for-the-badge&labelColor=0b0f14" alt="Supply Chain Security" />

**Governance &amp; standards**

<img src="https://img.shields.io/badge/EU_AI_Act-818cf8?style=for-the-badge&labelColor=0b0f14&logo=europeanunion&logoColor=818cf8" alt="EU AI Act" />
<img src="https://img.shields.io/badge/GDPR-818cf8?style=for-the-badge&labelColor=0b0f14" alt="GDPR" />
<img src="https://img.shields.io/badge/ISO%2FIEC_42001-818cf8?style=for-the-badge&labelColor=0b0f14" alt="ISO/IEC 42001" />
<img src="https://img.shields.io/badge/NIST_AI_RMF-818cf8?style=for-the-badge&labelColor=0b0f14" alt="NIST AI RMF" />
<img src="https://img.shields.io/badge/ISO_28000-818cf8?style=for-the-badge&labelColor=0b0f14" alt="ISO 28000" />
<img src="https://img.shields.io/badge/ISO_9001-818cf8?style=for-the-badge&labelColor=0b0f14" alt="ISO 9001" />

**Data &amp; method**

<img src="https://img.shields.io/badge/pandas-8b9bb4?style=for-the-badge&labelColor=0b0f14&logo=pandas&logoColor=8b9bb4" alt="pandas" />
<img src="https://img.shields.io/badge/SQL-8b9bb4?style=for-the-badge&labelColor=0b0f14&logo=mysql&logoColor=8b9bb4" alt="SQL" />
<img src="https://img.shields.io/badge/Power_BI-8b9bb4?style=for-the-badge&labelColor=0b0f14" alt="Power BI" />
<img src="https://img.shields.io/badge/Lean_Six_Sigma_%2F_DMAIC-8b9bb4?style=for-the-badge&labelColor=0b0f14" alt="Lean Six Sigma / DMAIC" />
<img src="https://img.shields.io/badge/Forecasting-8b9bb4?style=for-the-badge&labelColor=0b0f14" alt="Forecasting" />


</div>

<div align="center">

`AWS Lambda` `Amazon Bedrock` `Amazon Connect` `Amazon Lex` `Regulation (EU) 2024/1689`

</div>

<details>
<summary><b>🏆 Certifications</b></summary>
<br/>

- ☁️ **AWS Certified Solutions Architect**
- 📊 **Lean Six Sigma Black Belt** &amp; **Green Belt**
- 🔐 **ISO 28000** Supply Chain Security · **ISO 9001** Internal Auditor
- 🛡️ **Cybersecurity Foundations** · **Power BI / Data Analytics** · **Risk Management**

</details>

<details>
<summary><b>🧰 Other things I've built</b></summary>
<br/>

- **[All-in-one-desk](https://github.com/Jeevan-0508/All-in-one-desk)** — offline-first Python productivity suite: document conversion, OCR, KPI calculators, email and flowchart generators. Flask · Tesseract · LibreOffice · PyInstaller.
- **[hakai-protocol-v2](https://github.com/Jeevan-0508/hakai-protocol-v2)** — a real-life RPG for habits: quests, XP, gear, bosses, streaks. Zero dependencies, offline save system. **[Live](https://jeevan-0508.github.io/hakai-protocol-v2)**
- **[a-conversation-with-existence](https://github.com/Jeevan-0508/a-conversation-with-existence)** — a book I wrote.
- **[mind-galaxy](https://github.com/Jeevan-0508/mind-galaxy)** — the book's 18 chapters, laid out as an explorable 3D galaxy instead of a table of contents.

</details>

<details>
<summary><b>🌱 What I'm working toward</b></summary>
<br/>

- Deepening the **EU AI Act / ISO 42001 / NIST AI RMF** intersection beyond what the tools already encode
- Applying **anomaly detection** to carrier fraud patterns
- Moving into **AI governance / risk roles in the EU market**

</details>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Jeevan-0508/Jeevan-0508/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Jeevan-0508/Jeevan-0508/output/snake-light.svg" />
  <img src="https://raw.githubusercontent.com/Jeevan-0508/Jeevan-0508/output/snake-dark.svg" width="100%" alt="My contribution graph, being eaten" />
</picture>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Jeevan-0508&theme=dark&background=0b0f14&border=1e293b&stroke=1e293b&ring=38bdf8&fire=38bdf8&currStreakLabel=38bdf8&sideLabels=8b9bb4&dates=5b6b82&currStreakNum=e2e8f0&sideNums=e2e8f0&hide_border=false" alt="" />

<br/><br/>

<img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FJeevan-0508&query=%24.public_repos&label=Public%20Repos&color=38bdf8&labelColor=0b0f14&style=for-the-badge" alt="" />
<img src="https://img.shields.io/github/followers/Jeevan-0508?style=for-the-badge&color=38bdf8&labelColor=0b0f14&label=Followers" alt="" />

</div>

---

<div align="center">

### 📫 Let's talk

Open to **AI governance**, **risk management** and **automation** roles.

<a href="https://jeevan-0508.github.io"><img src="https://img.shields.io/badge/%F0%9F%8C%90-Portfolio-38bdf8?style=for-the-badge&labelColor=0b0f14" alt="" /></a>
<a href="https://www.linkedin.com/in/jeevan-siddhabhaktula-6927041a2/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0b0f14" alt="" /></a>
<a href="mailto:jeevansiddhabhaktula@gmail.com"><img src="https://img.shields.io/badge/Gmail-e2e8f0?style=for-the-badge&logo=gmail&logoColor=e2e8f0&labelColor=0b0f14" alt="" /></a>

<br/>

<sub>⭐ If any of these are useful to you, a star helps.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38bdf8,55:0ea5e9,100:0b0f14&height=120&section=footer" width="100%" alt="" />

</div>
