<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KadonWills/kadonwills/main/assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/KadonWills/kadonwills/main/assets/header-light.svg">
  <img alt="Kadon Wills — Software Engineer & Tech Entrepreneur" src="https://raw.githubusercontent.com/KadonWills/kadonwills/main/assets/header-dark.svg" width="100%">
</picture>

<br>

<a href="https://kapolbrondon.com"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&pause=1400&color=3838F0&center=true&vCenter=true&width=740&height=42&lines=Models+extract+and+explain.+Deterministic+code+decides.;Shipping+AI+products+out+of+Douala%2C+Cameroon.;7%2B+years+%C2%B7+10%2B+startup+products+%C2%B7+5+markets." alt="What I do"></a>

<br>

<a href="https://kapolbrondon.com"><img src="https://img.shields.io/badge/Portfolio-kapolbrondon.com-3838F0?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0B0B10" alt="Portfolio"></a>
<a href="https://www.linkedin.com/in/kadon"><img src="https://img.shields.io/badge/LinkedIn-in%2Fkadon-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0B0B10" alt="LinkedIn"></a>
<a href="mailto:kapolw@gmail.com"><img src="https://img.shields.io/badge/Email-kapolw%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0B0B10" alt="Email"></a>
<br>
<a href="https://x.com/kadonwills1"><img src="https://img.shields.io/badge/X-%40kadonwills1-000000?style=for-the-badge&logo=x&logoColor=white&labelColor=0B0B10" alt="X"></a>
<a href="https://dev.to/kadonwills"><img src="https://img.shields.io/badge/Dev.to-kadonwills-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white&labelColor=0B0B10" alt="Dev.to"></a>
<a href="https://stackoverflow.com/users/11230859/kadon"><img src="https://img.shields.io/badge/Stack_Overflow-11230859-F58025?style=for-the-badge&logo=stackoverflow&logoColor=white&labelColor=0B0B10" alt="Stack Overflow"></a>

</div>

---

> **Technology should fundamentally improve how we live and work, not add noise.**

<div align="center">

<img src="https://img.shields.io/badge/Years-7%2B-D4FF3F?style=flat-square&labelColor=0B0B10" alt="7+ years">
<img src="https://img.shields.io/badge/Startup_products-10%2B-D4FF3F?style=flat-square&labelColor=0B0B10" alt="10+ startup products">
<img src="https://img.shields.io/badge/Markets-5-D4FF3F?style=flat-square&labelColor=0B0B10" alt="5 markets">
<img src="https://img.shields.io/badge/Time_zones_led-3-D4FF3F?style=flat-square&labelColor=0B0B10" alt="3 time zones">
<img src="https://img.shields.io/badge/Base-Douala,_CM_·_WAT-3838F0?style=flat-square&labelColor=0B0B10" alt="Douala, Cameroon">
<img src="https://komarev.com/ghpvc/?username=kadonwills&label=Views&color=3838F0&style=flat-square" alt="Profile views">

</div>

## 👋 The 30-second version

I'm **Brondon Wills** — most people call me **Kadon**. Software engineer, and founder of **[Dinovix Ltd.](https://www.dinovix.com)**

The hardest part of building the future isn't writing the code — it's aligning technical velocity with a modern business mindset to create products that actually scale. Over seven years I've helped startups and SMEs across **Cameroon, the US, Switzerland, Germany and the UK** turn intricate problems into web and mobile products: fintech ledgers, high-traffic commerce, design systems, and corporate systems nobody is allowed to break.

These days I mostly build **AI products where the model is a component, not the architecture** — and I ship them end to end, from the Firestore rules to the pricing page.

<br>

## 🚀 Shipping now

> These are commercial products, so most of the source is private. **Links go to the live product, not the repo.**

<table>
<tr>
<td width="50%" valign="top">

### 🛰 [Fursa](https://www.fursa.space)
**The path, verified.**

Matches a real profile against official immigration rules and ranks the routes actually open to it — every figure sourced, dated, and priced in the applicant's own currency.

`Next.js 16` `Firebase Vector` `MCP` `EN / FR`

**The hard part:** eligibility is computed in tested, auditable code — never by a model. `unknown` is a first-class verdict that never degrades into `fail`. Import boundaries around the pure core are enforced in CI, not in code review.

`106 programmes` · `33 origin countries` · `31 test suites`

</td>
<td width="50%" valign="top">

### ✍️ [ProPost AI](https://www.propost-ai.online)
**One post a day, in your voice, approved by you.**

Drafts a LinkedIn post daily in the user's own tone, schedules it against their own analytics, and publishes nothing without an explicit approval step.

`Auth.js v5` `AI Gateway` `Firestore` `LinkedIn OAuth`

**The hard part:** two-stage OAuth with AES-256-GCM token encryption at rest, and a plan-gated model picker that re-validates **server-side** — so a client can never force a tier it hasn't paid for.

`365 drafts/user/year` · `0 posts published unapproved`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📡 [Busidea Radar](https://busidea-radar.vercel.app)
**Opportunity research, on a schedule.**

Researches four business opportunities across three markets, dedupes against the last 90 days, and emails a digest with conviction scores and buyer personas.

`Claude web search` `Vercel Blob` `NDJSON streaming`

**The hard part:** cost-aware two-stage dedup — a free keyword fingerprint settles the obvious pairs, and only genuinely borderline ones escalate to a single *batched* LLM verdict.

`~$0.85 per run` · `tracked per model on the dashboard`

</td>
<td width="50%" valign="top">

### 🛵 Delivr &nbsp;<sub>`pre-launch`</sub>
**One engine. Delivery, rides and parcels.**

A single *Job* primitive — a driver moved through a sequence of stops — powering three verticals and four role-based portals on one logistics core.

`Multi-tenant` `Geohash dispatch` `Firestore rules`

**The hard part:** `companyId` isolation is enforced in the security rules *and* re-checked server-side on every route. One service layer feeds both the cookie-session web API and the bearer-token mobile API, so tenancy can't drift between them.

`52 route handlers` · `19 test suites`

</td>
</tr>
</table>

**Also in flight**

| | What it does | The interesting bit | Status |
|---|---|---|---|
| **MBOKAM** | Turns a Cameroonian merchant's WhatsApp number into a real shop | Four-layer multi-tenancy down to **Postgres RLS**; custom ESLint rules that ban the admin client outside `lib/db/*` | Pre-launch |
| **Baobab** | A family tree in 3D that relatives claim and extend themselves | `react-three-fiber` kinship + layout engine; living people private by default; invites are Admin-SDK-only | Early |
| **Job Hunter** | 15 scored roles in your inbox at 08:00, each with a written intro | ~150 ATS endpoints across 6 providers, and a "remote lie detector" that reads work-authorisation locks instead of trusting the word *Remote* | Private beta |
| **sysprobe** | What's eating your CPU, disk and battery — right now | Rust workspace: one shared core, two front-ends (CLI + Tauri v2). Trashes, never deletes | Tool |

<br>

## 🏛 How I build

The same shape shows up in almost everything above. The single rule it's organised around:

> ### Models extract and explain. Deterministic code decides.

```mermaid
%%{init: {'theme':'base','themeVariables':{'fontFamily':'ui-sans-serif, system-ui, sans-serif','fontSize':'14px','lineColor':'#8B8B9A','primaryColor':'#3838F0','primaryTextColor':'#FFFFFF','primaryBorderColor':'#6366F1','secondaryColor':'#6366F1','tertiaryColor':'#1F2937','edgeLabelBackground':'#1F2937','textColor':'#F5F5F7'}}}%%
flowchart LR
    U(["User"]) --> E["Edge<br/>locale · session · tenant"]
    E --> S["Server Actions<br/>+ Route Handlers"]
    S --> C[["Deterministic core<br/>pure · no I/O · no model"]]
    C --> V["Verdict<br/>pass · fail · unknown"]
    S -. "extract · explain" .-> L["Model layer<br/>AI Gateway"]
    L -. "schema-checked" .-> S
    S --> D[("Firestore / Postgres<br/>tenancy in the rules")]
    K["Cron + agents"] --> S

    classDef core fill:#D4FF3F,stroke:#7A9B00,color:#0B0B10,stroke-width:2px
    classDef model fill:#6366F1,stroke:#4F46E5,color:#FFFFFF
    classDef data fill:#1F2937,stroke:#3838F0,color:#F5F5F7
    class C,V core
    class L model
    class D data
```

A model is allowed to read a government PDF and tell me what it says. It is never allowed to decide whether you qualify. That boundary is what makes the output auditable — and it's why the core of these products is a pure, fully-tested module that imports nothing but a schema library and a date library.

<br>

## 📐 Four things I've stopped arguing about

- **Scope is the real architecture decision.** Most "architecture problems" are unbounded scope wearing a costume.
- **Regulated work sets the floor.** Once you've shipped in fintech and public sector, that becomes the baseline everywhere else.
- **Components are a contract.** A design system nobody documents is just a folder.
- **Empathetic technical leadership.** Leading remote teams across three time zones taught me async clarity beats synchronous heroics — written decisions, visible reasoning, no ambient context.

<br>

## 🧰 Stack

*Tools chosen for the job, not the résumé.*

<div align="center">
<!-- Commas below are %2C-encoded on purpose: a raw comma inside srcset is a
     candidate separator, so the browser would request only the first icon. -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts%2Cnextjs%2Creact%2Ctailwind%2Cnodejs%2Cjava%2Cspring%2Cflutter%2Cdart%2Cfirebase%2Cpostgres%2Cdocker%2Crust%2Cvercel%2Cgit%2Cfigma&theme=dark&perline=8">
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=ts%2Cnextjs%2Creact%2Ctailwind%2Cnodejs%2Cjava%2Cspring%2Cflutter%2Cdart%2Cfirebase%2Cpostgres%2Cdocker%2Crust%2Cvercel%2Cgit%2Cfigma&theme=light&perline=8">
  <img alt="TypeScript, Next.js, React, Tailwind, Node.js, Java, Spring, Flutter, Dart, Firebase, PostgreSQL, Docker, Rust, Vercel, Git, Figma" src="https://skillicons.dev/icons?i=ts%2Cnextjs%2Creact%2Ctailwind%2Cnodejs%2Cjava%2Cspring%2Cflutter%2Cdart%2Cfirebase%2Cpostgres%2Cdocker%2Crust%2Cvercel%2Cgit%2Cfigma&theme=dark&perline=8" width="620">
</picture>
</div>

<details>
<summary><b>The full inventory</b></summary>

<br>

| Layer | | |
|---|---|---|
| **Languages** | *Daily drivers* | Java · JavaScript (ES6) · TypeScript · Dart · SQL |
| **Backend** | *Where the rules live* | Spring Boot · Spring Cloud · Spring Security · Spring REST · Microservices · Laravel · Node.js |
| **Frontend** | *Product surface* | React · Next.js · Redux · Inertia · Tailwind CSS · MUI · Ant Design · Styled Components · Motion |
| **Mobile** | *Cross-platform* | Flutter · Dart |
| **Data** | *Persistence* | PostgreSQL · MySQL · Oracle · Firebase · Strapi |
| **AI** | *Model layer* | Vercel AI SDK · AI Gateway · Anthropic SDK · MCP · structured output with schema validation |
| **Tooling** | *How the work ships* | Git · Docker · GitHub Actions · Maven · Webpack · Swagger · Storybook · Chromatic · Cloudflare · Stripe · Figma · Agile |

</details>

<br>

## 📊 Public footprint

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=KadonWills&theme=github_dark">
  <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=KadonWills&theme=default">
  <img alt="Top languages by repository" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=KadonWills&theme=github_dark" height="200">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=KadonWills&theme=github_dark">
  <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=KadonWills&theme=default">
  <img alt="Top languages by commit" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=KadonWills&theme=github_dark" height="200">
</picture>

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KadonWills/kadonwills/output/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/KadonWills/kadonwills/output/snake.svg">
  <img alt="Contribution graph" src="https://raw.githubusercontent.com/KadonWills/kadonwills/output/snake.svg" width="100%">
</picture>

<sub><b>Read this chart with an asterisk.</b> The products above live in private repos, so the public slice skews toward older, open work — it's a floor, not a ceiling.</sub>

</div>

<br>

## 🌍 Selected client work

Client names are under NDA, so here are the outcomes instead.

| Domain | What it was | Outcome |
|---|---|---|
| **Fintech** | Rebuilt a payments backend that was losing customers to slow, unreliable transaction handling | **−30%** response times · **−40%** downtime · 100% client satisfaction |
| **Public sector** | End-to-end automated federal tax return platform, compliance logic isolated from presentation | **99%** calculation accuracy · **−25%** processing time |
| **Design systems** | Atomic component library, Figma handoff through to documented, visually-tested release | Visual regressions in production eliminated · full documentation coverage |
| **SaaS** | Digitised shift management that previously ran on paper and messaging apps | Delivered in a single quarter |

<br>

## 🎓 Beyond the code

- **Certified** — Meta Front-End Developer (2024) · Google Africa Developer Training (2021)
- **Studied** — BSc Computer Science, Software Engineering — African Institute of Computer Science, Cameroon
- **Give back** — Co-founder, Bio Foundation · Contributor, Open Source Cameroon · Mentor, Code4Africa
- **Speak** — French and English (bilingual) · Chinese and Russian (basics)

<br>

---

<div align="center">

## 🤝 Let's build something

**Open to select engagements** — fractional CTO, MVP sprints, product-lifecycle consulting, and technical due diligence.<br>
I reply within two working days.

<a href="mailto:kapolw@gmail.com"><img src="https://img.shields.io/badge/Start_a_conversation-kapolw%40gmail.com-3838F0?style=for-the-badge&logo=minutemailer&logoColor=white&labelColor=0B0B10" alt="Email me"></a>
<a href="https://kapolbrondon.com"><img src="https://img.shields.io/badge/See_the_case_studies-kapolbrondon.com-D4FF3F?style=for-the-badge&logo=readdotcv&logoColor=0B0B10&labelColor=0B0B10" alt="Portfolio"></a>

<br><br>

<a href="https://www.buymeacoffee.com/kadon"><img src="https://img.shields.io/badge/Buy_me_a_coffee-FFDD00?style=flat-square&logo=buymeacoffee&logoColor=0B0B10&labelColor=FFDD00" alt="Buy me a coffee"></a>

<br><br>

***"Great code, like great art, leaves an indelible mark on the world."***

</div>
