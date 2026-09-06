<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b0f14,45:0ea5e9,100:38bdf8&height=210&section=header&text=Jeevan&fontSize=68&fontColor=e2e8f0&fontAlignY=33&desc=Risk%20Operations%20%E2%80%A2%20AI%20Governance%20%E2%80%A2%20Automation&descSize=17&descAlignY=53&animation=fadeIn" width="100%" alt="" />

<a href="https://jeevan-0508.github.io">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=3400&pause=800&color=38BDF8&center=true&vCenter=true&width=820&height=48&lines=Risk+Manager+%40+Amazon+Transportation;I+hunt+carrier+fraud+across+EU+%26+NA+lanes;Then+I+open-source+the+methodology;EU+AI+Act+%C2%B7+GDPR+%C2%B7+ISO+42001+%C2%B7+NIST+AI+RMF" alt="" />
</a>

<br/>

<a href="https://jeevan-0508.github.io"><img src="https://img.shields.io/badge/%F0%9F%8C%90_Portfolio-jeevan--0508.github.io-38bdf8?style=for-the-badge&labelColor=0b0f14" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/jeevan-siddhabhaktula-6927041a2/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0b0f14" alt="LinkedIn" /></a>
<a href="mailto:jeevansiddhabhaktula@gmail.com"><img src="https://img.shields.io/badge/Email-Say_hello-e2e8f0?style=for-the-badge&logo=gmail&logoColor=e2e8f0&labelColor=0b0f14" alt="Email" /></a>
<img src="https://komarev.com/ghpvc/?username=Jeevan-0508&style=for-the-badge&color=38bdf8&labelColor=0b0f14&label=Visitors" alt="" />

</div>

---

<div align="center">

### ⚡ I do two things

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

<img src="https://skillicons.dev/icons?i=python,js,html,css,flask,aws,git,githubactions,mysql,bash,powershell,markdown&theme=dark&perline=12" alt="" />

</div>

<div align="center">

`AWS Lambda` `Bedrock` `Connect` `Lex` `SQL` `Power BI` `GitHub Actions` `Pandas`

`EU AI Act (Reg. 2024/1689)` `GDPR` `ISO/IEC 42001` `NIST AI RMF` `ISO 28000` `Lean Six Sigma / DMAIC`

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
