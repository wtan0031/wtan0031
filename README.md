<h1 align="center">Wei Liang Tan</h1>

<p align="center">
  <strong>iOS Engineer · Fintech &amp; Consumer Mobile · Building with agents</strong><br/>
  Kuala Lumpur, Malaysia 🇲🇾
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white" alt="Swift"/>
  <img src="https://img.shields.io/badge/SwiftUI-0071E3?style=flat&logo=swift&logoColor=white" alt="SwiftUI"/>
  <img src="https://img.shields.io/badge/UIKit-2396F3?style=flat&logo=apple&logoColor=white" alt="UIKit"/>
  <img src="https://img.shields.io/badge/Kotlin_Multiplatform-7F52FF?style=flat&logo=kotlin&logoColor=white" alt="Kotlin Multiplatform"/>
  <img src="https://img.shields.io/badge/Xcode-147EFB?style=flat&logo=xcode&logoColor=white" alt="Xcode"/>
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=claude&logoColor=white" alt="Claude Code"/>
</p>

---

I build and ship **production iOS apps** — the kind that handle real money and real users. Most of my day-to-day work lives in private company repos, so this profile is a snapshot of how I work and what I've shipped rather than a wall of stars.

- 🏦 **Currently** — Software Engineer, Mobile (iOS) at **Definitiv** (part of **The Access Group**). Sole iOS engineer on two production apps for a payroll platform serving Australia and New Zealand, and co-building its Kotlin Multiplatform rewrite — **135 merged PRs across three apps in year one**
- 🚀 **Previously** — Software Engineer, Mobile (iOS) at **GX Bank** — one of the first two iOS engineers at one of Malaysia's first digital banks; owned the payments stack, which has processed **RM 1B+** since launch
- 🧩 **I care about** — correctness, clean release process, and code that the next engineer can read. Fintech taught me that "it works on my machine" isn't good enough.
- 📱 **Focus** — SwiftUI · UIKit · MVVM · SwiftData · StoreKit · Kotlin Multiplatform · app architecture, testing, and App Store delivery

### How I work

- **Ship deliberately.** Feature specs, acceptance criteria, and a release checklist before code — not after.
- **Test what matters.** Unit and UI tests around the logic that would actually hurt users if it broke.
- **Leave a trail.** Clear PRs, documented decisions, and code reviewed like someone's money depends on it — because it usually does.

### 🤖 How I build with agents

A year ago I wrote every line by hand. Today agents are my default tool, and I run a [personal library of agent skills](https://github.com/wtan0031/agent-skills) — release notes, feature docs, scaffolding — tailored to how I ship. That's what lets one engineer keep three apps moving.

The rule I hold myself to: **"it ran" is not "it worked."** For anything an agent generates, I define the check that proves it's correct *before* generating, and run it every time. Agents write a lot of my code; the judgement about what ships is still mine.

### 📊 Agent-assisted delivery, by the numbers
<sub>30 Jun – 19 Oct 2026 · from git history and local agent logs ([ccusage](https://github.com/ryoppippi/ccusage))</sub>

| | |
|---|---|
| **Shipped** | **1,960+ commits · 680+ merged PRs** across 11 personal repos |
| **Tooling** | **38 custom agent skills** for review, auditing, release and SwiftUI checks — some open-sourced in [agent-skills](https://github.com/wtan0031/agent-skills) |
| **Agent usage** | **6.2B+ tokens measured** with ccusage |
| **Verification** | Agent changes go through tests and a review step — 27 unit-test files guard the maths in one unattended pipeline |

- **Parallel, isolated work.** Independent tasks run as separate agent sessions, each in its own git worktree and ending in its own PR.
- **Agents read; rules decide.** My scheduled pipelines run agents unsupervised, so every number comes from unit-tested code, and a tool deny-list blocks any write to an external account.
- **Usage is a budget.** I measure usage with ccusage and my own [`/token-report`](https://github.com/wtan0031/agent-skills/tree/main/skills/token-report), and treat tokens as a cost, not a free resource.

### 🔨 Selected work

**[CrucibleCraft](https://cruciblecraft.com)** — my indie iOS studio. *"Software forged to last"* — every app ships only after rigorous testing. No VC, no growth hacks, no shortcuts.

- **[Bayarsama](https://cruciblecraft.com/bayarsama/)** — bill-splitting app, **live on the App Store**. Splits any bill item by item, auto-calculates taxes and service charges across 13 currencies, and shares each person's share via WhatsApp or PDF. Built solo from zero to release in about five months: 131 merged PRs, SwiftUI + SwiftData, StoreKit 2 subscriptions with regional pricing and graceful downgrade.
- More in the crucible 🔥

**At work** *(private repos)*

- **Kotlin Multiplatform rewrite** — end-to-end feature slices (Timesheets with manager approvals, Announcements, Annual Statements, Settings with biometrics), each with domain layer, UI, unit + E2E tests and docs. My first time writing Kotlin.
- **Legacy modernisation** — fixed 20+ production crashes in a 15-year-old codebase, moved it to Swift Package Manager and modern dependencies, and tightened its security along the way.

### Tech I reach for

`Swift` · `SwiftUI` · `UIKit` · `SwiftData` / `Core Data` · `Combine` · `async/await` · `StoreKit 2` · `Kotlin Multiplatform` · `Compose Multiplatform` · `Firebase` · `XCTest` / `Swift Testing` · `Fastlane` · `Git` · Python for tooling

**Agents:** `Claude Code` · `Codex` · `Copilot` · `Gemini`

### 📫 Reach me

- ✉️ **wtan0031@gmail.com**
- 💼 [LinkedIn](https://www.linkedin.com/in/wei-liang-tan-67aa29122/)
- 🌐 [cruciblecraft.com](https://cruciblecraft.com)

<p align="center"><sub>Always happy to talk iOS, Kotlin Multiplatform, or building with agents.</sub></p>
