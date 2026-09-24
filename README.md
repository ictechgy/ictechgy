<div align="center">

<h1>Hi, I'm Coden 👋</h1>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=5B8DEF&center=true&vCenter=true&width=460&lines=iOS+Developer;Developer+Tools+Builder;Building+with+AI" alt="Typing SVG" />

<p>🔍 I like digging deep and sharing what I learn &nbsp;·&nbsp; 🤖 These days I build together with AI</p>

<a href="mailto:ictechgy@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Gmail" /></a>
<img src="https://komarev.com/ghpvc/?username=ictechgy&style=flat-square&color=5B8DEF&label=Profile+Views" alt="Profile Views" />

</div>

<br/>

## 👀 About Me

- 🧩 I build **iOS apps** and enjoy going deep on modularization and architecture
- 🛠️ When I need a tool, I **build it myself** — from developer CLIs to full products
- 🤖 I prototype fast **with AI** and turn ideas into shipped software
- ✍️ I like to **write down and share** what I learn along the way

<br/>

## 🧰 Tech Stack

<div align="center">

**Language & IDE**

![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white)

**UI**

![SwiftUI](https://img.shields.io/badge/SwiftUI-0055FF?style=flat-square&logo=swift&logoColor=white)
![UIKit](https://img.shields.io/badge/UIKit-2396F3?style=flat-square&logo=apple&logoColor=white)
![AutoLayout](https://img.shields.io/badge/AutoLayout-4B5563?style=flat-square)

**Concurrency**

![Swift Concurrency](https://img.shields.io/badge/Swift_Concurrency-F05138?style=flat-square&logo=swift&logoColor=white)
![Combine](https://img.shields.io/badge/Combine-4B5563?style=flat-square)
![GCD](https://img.shields.io/badge/DispatchQueue-4B5563?style=flat-square)

**Architecture**

![Modularization](https://img.shields.io/badge/Modularization-4B5563?style=flat-square)
![SPM](https://img.shields.io/badge/SPM-F05138?style=flat-square&logo=swift&logoColor=white)
![Needle](https://img.shields.io/badge/Needle_DI-4B5563?style=flat-square)
![Coordinator](https://img.shields.io/badge/Coordinator-4B5563?style=flat-square)

**Web Bridge**

![WebKit](https://img.shields.io/badge/WebKit-4B5563?style=flat-square)
![WKWebView](https://img.shields.io/badge/WKWebView_Messaging-4B5563?style=flat-square)

**Collaboration**

![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=slack&logoColor=white)

</div>

<br/>

## 🚀 Projects & Products

> Things I designed, built, and shipped on my own.

### 🛠️ Developer Tools (Open Source)

> Static analysis tools that turn codebases — and database schemas — into a **queryable dependency graph** — dead code, cycles, impact analysis, layering rules, and architecture metrics as queries over one graph.

<div align="center">
<img src="graph-family.png" alt="The *graph tool family bird mascots gathered around a dependency graph" width="720" />
</div>

| Tool | Platform | Description |
| :--- | :--- | :--- |
| [**cartograph**](https://github.com/ictechgy/cartograph) | ![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white) | Queryable dependency graph for Swift / iOS codebases, built on IndexStoreDB |
| [**kartograph**](https://github.com/ictechgy/kartograph) | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) | Explainable dependency graphs and dead-code analysis for Kotlin / Android |
| [**gartograph**](https://github.com/ictechgy/gartograph) | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) | Queryable dependency graph for Go codebases — cycles, dead code, and layer rules as queries |
| [**rustograph**](https://github.com/ictechgy/rustograph) | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) | Queryable dependency graph for Rust / Cargo workspaces — cycles, dead code, and impact analysis as queries |
| [**schemagraph**](https://github.com/ictechgy/schemagraph) | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) | Dependency graphs for databases — catalogs and SQL bodies in, impact analysis, cycle detection, and architecture rules out |

<details>
<summary><b>Dart / Flutter & cross-language graphs</b> &nbsp;·&nbsp; <sub>dartograph + isthmus — the Dart/Flutter engine and the joiner that links graphs across language boundaries, click to expand</sub></summary>

<br/>

| Tool | Platform | Description |
| :--- | :--- | :--- |
| [**dartograph**](https://github.com/ictechgy/dartograph) | ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) | Evidence-backed dependency graph analysis for Dart / Flutter codebases |
| [**isthmus**](https://github.com/ictechgy/isthmus) | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | Joins the graphs above across language boundaries — Flutter `MethodChannel`/Pigeon (Dart ↔ Swift/Kotlin) and React Native bridge calls that per-language tools miss, plus a `persistence` domain joining Go code to DB schemas via gartograph + schemagraph facts |

</details>

<details>
<summary><b>More tools</b> &nbsp;·&nbsp; <sub>12 more — for AI coding agents, iOS engineering, and data tooling, click to expand</sub></summary>

<br/>

**🤖 For AI coding agents** — deterministic, local, no LLM in the loop

| Tool | Platform | Description |
| :--- | :--- | :--- |
| [**joinery**](https://github.com/ictechgy/joinery) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | The linker for agent skill stacks — extracts each skill's implicit CLI / MCP / client-feature dependencies, dry-fits them against your machine, locks and compiles per-agent configs |
| [**riskgate**](https://github.com/ictechgy/riskgate) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | One YAML policy that decides what your coding agent may do — allow, prompt, or deny every tool call, portable across agent CLIs, zero dependencies |
| [**yield-audit**](https://github.com/ictechgy/yield-audit) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Outcome accounting for AI coding agents: what survived, what it cost, what was wasted — includes an AI rework-rate lens for phantom productivity |
| [**epitaph**](https://github.com/ictechgy/epitaph) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | A repo-scoped ledger of rejected agent attempts — structured tombstones for rolled-back patches, consulted before the next agent retries the same path |
| [**agent2perfetto**](https://github.com/ictechgy/agent2perfetto) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Converts Claude Code session logs into Perfetto trace JSON — view agent sessions as timelines, tool slices, and context / cost counters |
| [**packet-ask**](https://github.com/ictechgy/packet-ask) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Sends only a scrubbed packet — never the raw repo — to personal coding-subscription subagents for review and second opinions |
| [**relay-continuity**](https://github.com/ictechgy/relay-continuity) | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) | Local, privacy-first continuity for AI-assisted work — evidence-backed resume context without storing code, chats, or telemetry |
| [**understatus**](https://github.com/ictechgy/understatus) | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) | A calm macOS statusline addon for Claude Code — live CPU, memory, battery, disk, network & AI-session info, with selectable themes |

**📱 For iOS engineering**

| Tool | Platform | Description |
| :--- | :--- | :--- |
| [**locus**](https://github.com/ictechgy/locus) | ![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white) | Where every UI element lives in source — a static traceability map from iOS accessibility elements to Swift code; CLI + MCP server |
| [**strictmigrate**](https://github.com/ictechgy/strictmigrate) | ![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white) | Delegates a Swift 6 strict-concurrency migration to agents — the compiler is the judge, a journal is the single source of truth; spans the KMP boundary |
| [**coroner**](https://github.com/ictechgy/coroner) | ![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white) | Local post-mortem triage for iOS telemetry (.ips + MetricKit) — symbolicate, cluster, version-journal, and expose it to coding agents over MCP |

**🗄️ For data & infra**

| Tool | Platform | Description |
| :--- | :--- | :--- |
| [**vecdiff**](https://github.com/ictechgy/vecdiff) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Diffs two embedding-index snapshots for vector-DB migrations and index audits — local, numpy-only, CI-gateable |

</details>

### 🤖 AI Agent Infrastructure

> Tools for running AI coding agents safely and smoothly — sandboxing, policy gates, account switching, and shared knowledge.

| Tool | Platform | Description |
| :--- | :--- | :--- |
| [**agentbelt**](https://github.com/ictechgy/agentbelt) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Runs AI coding agents on macOS confined to one project directory — Seatbelt-enforced, kernel-tested |
| [**exitzero**](https://github.com/ictechgy/exitzero) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Offline policy and verification gates for AI-assisted coding teams |
| [**multi-account-tool**](https://github.com/ictechgy/multi-account-tool) | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | Switches between multiple AI CLI accounts (Claude Code, Codex, Gemini/Antigravity) from one TUI — Keychain-backed with automatic rollback |
| [**knowledger**](https://github.com/ictechgy/knowledger) | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | Domain-scoped knowledge agreements for KBs, LLM wikis, and AI workflows — with a Hyperledger Fabric adapter |

### 🖥️ macOS Apps

> Native macOS apps, built together with AI. Distributed at [coden.kr](https://coden.kr).

| App | Description |
| :--- | :--- |
| [**Storage Medic**](https://coden.kr/products/storage-medic/) | Find and clean up what's eating your disk space |
| [**Nits**](https://coden.kr/products/nits/) | Fine-tune display brightness and color temperature |

### 🌐 Web & Mobile Services

<details>
<summary><b>Side projects I've shipped</b> &nbsp;·&nbsp; <sub>click to expand</sub></summary>

<br/>

| Service | Description |
| :--- | :--- |
| [**PickMeJobs**](https://www.pickmejobs.kr) | Job postings, aggregated in one place |
| [**Oneul Buffet**](https://oneulbuffet.com) | Map of buffets and company cafeterias |
| [**EVCar**](https://evcar.dev) | EV charging station map |
| [**PyeonDeal**](https://pyeondeal.com) | Convenience store deals and promotions |
| [**PolicyHanun**](https://policyhanun.kr) | Government policies at a glance |
| [**Hansan**](https://hansan.app) | Real-time crowd density map of Seoul |
| [**Mosquito Index Map**](https://mosquito-index-map.ictechgy.workers.dev) | Map of mosquito and pest activity |
| [**Observed**](https://observed.live) | Real-time status monitoring for AI tools and infrastructure |

</details>

<br/>

## 📊 GitHub Stats

<div align="center">

<img src="github-metrics.svg" alt="Metrics — stats, languages, and commit calendar" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ictechgy&hide_border=true&ring=5B8DEF&fire=5B8DEF&currStreakLabel=5B8DEF" alt="Streak" />

</div>

<br/>

## 📮 Contact

<div align="center">

<a href="mailto:ictechgy@gmail.com"><img src="https://img.shields.io/badge/ictechgy@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>

<br/><br/>

<sub>Thanks for stopping by! Feel free to reach out by email 😊</sub>

</div>

<!-- profile readme: @ictechgy -->
