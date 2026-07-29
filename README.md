<a name="top"></a>

<div align="center">

<!-- Live typing header. No local asset, so it renders on every clone and fork. -->
<a href="https://github.com/spencerscott">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=30&duration=2600&pause=900&color=A78BFA&center=true&vCenter=true&width=780&height=90&lines=Spencer+Scott;Full-Stack+%26+Mobile+Developer;Flutter+%C2%B7+On-Device+AI+%C2%B7+Offline-First;Models+that+run+on+the+phone%2C+not+the+cloud" alt="Spencer Scott â€” Full-Stack & Mobile Developer" />
</a>

<br/>

<a href="https://github.com/spencerscott"><img src="https://komarev.com/ghpvc/?username=spencerscott&color=a78bfa&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile views" /></a>
<a href="https://github.com/spencerscott?tab=followers"><img src="https://img.shields.io/github/followers/spencerscott?color=fbbf24&style=for-the-badge&label=FOLLOWERS&labelColor=1c1b22" alt="Followers" /></a>
<a href="https://github.com/spencerscott?tab=repositories"><img src="https://img.shields.io/github/stars/spencerscott?color=a78bfa&style=for-the-badge&label=STARS&labelColor=1c1b22" alt="Stars" /></a>
<a href="mailto:you@example.com"><img src="https://img.shields.io/badge/OPEN%20TO-COLLABORATION-6d28d9?style=for-the-badge&labelColor=1c1b22" alt="Open to collaboration" /></a>

<br/><br/>

**[About](#-about) Â· [Principles](#-engineering-principles) Â· [Stack](#-technical-stack) Â· [Architecture](#-how-i-build-offline-first) Â· [Focus](#-current-focus) Â· [Work](#-selected-work) Â· [Performance](#-performance-as-a-feature) Â· [Timeline](#-timeline) Â· [Analytics](#-github-analytics) Â· [Writing](#-writing--notes) Â· [Working With Me](#-working-with-me) Â· [Contact](#-contact)**

</div>

---

## ðŸ§­ About

I build software across the full stack: **React** and **TypeScript** on the front end, **Flutter** for mobile, **Java** and **Python** for backend services, **SQL** underneath it all.

My focus is on-device intelligence: pushing machine learning to the edge so applications respond instantly, work without connectivity, and never ship user data off the device. No round-trips. No privacy tradeoffs. No excuses about signal.

Most apps treat the network as the floor they stand on. I treat it as a bonus. That single inversion changes everything downstream: how state is stored, how conflicts resolve, where inference runs, and what happens on a train through a tunnel. It is harder to build and dramatically better to use.

```yaml
identity:
  name: "Spencer Scott"
  role: "Full-Stack & Mobile Developer"
  focus: ["Flutter", "On-Device AI", "Offline-First Architecture"]
  building: "Ingredient-to-Recipe â€” AI recipe generation, fully offline"
  principle: "Ship fast. Respect privacy. Sweat the details."
  currently_learning: ["Rust for mobile FFI", "WebGPU inference", "CRDT internals"]
  open_to: ["Collaboration", "Contract work", "Code review swaps"]
```

<table>
<tr>
<td width="50%" valign="top">

**What I reach for first**

Flutter for anything with a screen and a user. It gets one codebase to a native feel on both platforms, and the render pipeline is predictable enough to hit a frame budget on purpose.

</td>
<td width="50%" valign="top">

**What I avoid**

Server calls in the hot path. Client state that only makes sense when a request succeeds. Any architecture where "you must be online" is a sentence the user ever reads.

</td>
</tr>
</table>

---

## ðŸŒ  Engineering Principles

> **Great applications aren't just built. They're felt.**
> Every interaction should be instant, every screen should feel alive, and every byte should respect the person holding the device.

|    | Principle | In Practice |
|:--:|:--|:--|
| ðŸ“± | **Mobile-First** | One codebase, native feel on every platform. Flutter done properly. |
| ðŸ§  | **On-Device AI** | Models that run locally. Private by architecture, not by policy. |
| âš¡ | **Offline-First** | The network is an enhancement, never a dependency. |
| ðŸ—ï¸ | **Built to Last** | Clean architecture and maintainable systems over expedient hacks. |
| ðŸ“ | **Measured, Not Guessed** | Frame time, cold start, and bundle size tracked in CI like tests. |
| ðŸ” | **Boring Where It Counts** | Novel in the product, conservative in the plumbing. |

**The uncomfortable version of each:** mobile-first means desktop gets fewer features. On-device AI means smaller models and real accuracy tradeoffs. Offline-first means writing conflict resolution nobody thanks you for. Built to last means shipping slower in week one to ship faster in month six. Every principle costs something. These are the ones worth paying for.

---

## ðŸ§° Technical Stack

<details open>
<summary><b>ðŸ’» Languages</b></summary>
<br/>

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

</details>

<details open>
<summary><b>âš›ï¸ Frameworks & Platforms</b></summary>
<br/>

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

</details>

<details>
<summary><b>ðŸ§  AI & On-Device Intelligence</b></summary>
<br/>

![TensorFlow Lite](https://img.shields.io/badge/TensorFlow%20Lite-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![On-Device AI](https://img.shields.io/badge/On--Device%20AI-6d28d9?style=for-the-badge)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-6d28d9?style=for-the-badge)
![Quantization](https://img.shields.io/badge/Model%20Quantization-6d28d9?style=for-the-badge)
![Offline-First](https://img.shields.io/badge/Offline--First-f59e0b?style=for-the-badge)

**Techniques I actually use:** post-training INT8 quantization, quantization-aware training when accuracy drops past tolerance, knowledge distillation to shrink teacher models, operator fusion, NNAPI and Core ML delegate routing with a CPU fallback that never crashes.

</details>

<details>
<summary><b>ðŸ—„ï¸ Data & Persistence</b></summary>
<br/>

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Drift](https://img.shields.io/badge/Drift-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Isar](https://img.shields.io/badge/Isar-6d28d9?style=for-the-badge)

</details>

<details>
<summary><b>ðŸ§ª Testing & Quality</b></summary>
<br/>

![Flutter Test](https://img.shields.io/badge/Flutter%20Test-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Patrol](https://img.shields.io/badge/Patrol-6d28d9?style=for-the-badge)
![JUnit](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

Golden tests for anything visual, integration tests on real devices for anything that touches the camera or the model, unit tests for the sync layer where the bugs are subtle and expensive.

</details>

<details>
<summary><b>ðŸ› ï¸ Tooling & Delivery</b></summary>
<br/>

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Fastlane](https://img.shields.io/badge/Fastlane-00F200?style=for-the-badge&logo=fastlane&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</details>

---

## ðŸ—ï¸ How I Build Offline-First

Offline-first is not a cache. A cache is what you add when the network fails. Offline-first means the local database is the source of truth and the server is a peer you sync with when it happens to be reachable.

```mermaid
flowchart TB
    UI["ðŸ–¼ï¸ UI Layer<br/><sub>reads only from local state</sub>"]
    LOCAL["ðŸ—ƒï¸ Local Store<br/><sub>SQLite Â· source of truth</sub>"]
    QUEUE["ðŸ“¤ Mutation Queue<br/><sub>durable Â· ordered Â· idempotent</sub>"]
    SYNC["ðŸ”„ Sync Engine<br/><sub>backoff Â· dedupe Â· resolve</sub>"]
    REMOTE["â˜ï¸ Remote<br/><sub>optional peer</sub>"]

    UI -->|"write intent"| LOCAL
    LOCAL -->|"optimistic commit"| UI
    LOCAL --> QUEUE
    QUEUE --> SYNC
    SYNC <-->|"when reachable"| REMOTE
    SYNC -->|"reconciled state"| LOCAL

    style UI fill:#6d28d9,stroke:#a78bfa,color:#ffffff
    style LOCAL fill:#4c1d95,stroke:#a78bfa,color:#ffffff
    style SYNC fill:#b45309,stroke:#fbbf24,color:#ffffff
    style REMOTE fill:#3f3f46,stroke:#a1a1aa,color:#ffffff
```

The interesting part is not the diagram, it's the rules that make it hold up:

| Rule | Reason |
|:--|:--|
| Every mutation carries a client-generated ID | Retries become safe. The server can dedupe without guessing. |
| The queue is durable, not in-memory | An app killed mid-sync resumes instead of losing the write. |
| Conflicts resolve by policy, not by accident | Last-write-wins where it's fine, merge where it isn't, prompt where it matters. |
| The UI never awaits the network | Optimistic commit locally, reconcile after. Latency stops being visible. |
| Sync is a state machine, not a boolean | `idle Â· pending Â· syncing Â· degraded Â· failed` each render differently. |

```dart
/// Writes land locally first, then drain to the server when it's reachable.
/// The UI is never blocked on a socket.
Future<void> save(Recipe recipe) async {
  final op = Mutation.upsert(
    entity: recipe,
    clientId: const Uuid().v4(),   // makes retries idempotent
    at: clock.now(),
  );

  await _db.transaction(() async {
    await _db.recipes.upsert(recipe);  // optimistic, instant
    await _queue.enqueue(op);          // durable across process death
  });

  _sync.nudge();                       // fire and forget, never awaited
}
```

---

## ðŸ”­ Current Focus

- **On-device machine learning** Â· quantized vision models running in real time on mid-range hardware, not just flagships
- **Offline-first Flutter** Â· conflict-free local persistence and sync that survives a dead connection and a killed process
- **Performance engineering** Â· frame budgets, cold-start times, and memory profiles treated as first-class requirements
- **Model compression** Â· distillation and pruning to get useful accuracy under a 15 MB bundle ceiling
- **Rust FFI for mobile** Â· moving the hottest preprocessing loops out of Dart where the numbers justify it

---

## ðŸ“¸ Selected Work

### ðŸ¥• Ingredient-to-Recipe

An offline-first Flutter application that identifies ingredients from a single photo and generates recipe suggestions entirely on-device. No server, no account, no connection required.

```mermaid
flowchart LR
    A["ðŸ“· Capture"] --> B["ðŸ” Preprocess<br/><sub>resize Â· normalize</sub>"]
    B --> C["ðŸ§  Quantized CNN<br/><sub>TFLite Â· INT8</sub>"]
    C --> D["ðŸ¥• Ingredient set"]
    D --> E["ðŸ½ï¸ Rank recipes<br/><sub>local index</sub>"]
    E --> F["âœ¨ Results"]

    style A fill:#6d28d9,stroke:#a78bfa,color:#ffffff
    style C fill:#6d28d9,stroke:#a78bfa,color:#ffffff
    style E fill:#b45309,stroke:#fbbf24,color:#ffffff
    style F fill:#b45309,stroke:#fbbf24,color:#ffffff
```

| Metric | Target | Why it matters |
|:--|:--:|:--|
| Inference latency | `< 400 ms` | Recognition should feel like a camera shutter, not a request |
| End-to-end result | `< 1 s` | Photo to ranked recipes without a loading state |
| Network calls | `0` | Zero telemetry, zero latency variance, zero cost per request |
| Model footprint | `~12 MB` | INT8 quantization keeps the whole pipeline in the app bundle |

**Stack** Â· `Flutter` `Dart` `TensorFlow Lite` `Computer Vision` `Offline-First`

> **Engineering note:** the full inference pipeline ships inside the app bundle. Nothing leaves the device, so privacy is a property of the architecture rather than a promise in a policy.

**What was hard:** the first model was 94 MB and took 2.3 seconds on a mid-range Android device. Getting to 12 MB and 380 ms cost four points of top-1 accuracy, which turned out not to matter because ranking recipes tolerates a wrong guess far better than a two-second wait does. The lesson generalizes: pick the metric the user actually feels.

<br/>

### ðŸ—‚ï¸ Other Things I've Built

<table>
<tr>
<td valign="top" width="33%">

**Sync Engine (library)**

A reusable durable mutation queue for Flutter apps. Handles ordering, retries, exponential backoff, and pluggable conflict policies.

`Dart` Â· `SQLite` Â· `Drift`

</td>
<td valign="top" width="33%">

**Frame Budget CI**

A GitHub Action that runs Flutter integration tests on device, parses the timeline, and fails the build when p99 frame time regresses.

`Dart` Â· `Actions` Â· `Python`

</td>
<td valign="top" width="33%">

**Model Shrink Toolkit**

Scripts that take a PyTorch checkpoint through distillation, pruning, and INT8 export, reporting the accuracy cost of each step.

`Python` Â· `PyTorch` Â· `ONNX`

</td>
</tr>
</table>

---

## ðŸ“ˆ Performance as a Feature

Performance stops regressing the moment it becomes a failing test instead of a good intention. These are enforced in CI, not aspirational:

| Budget | Threshold | Enforced by |
|:--|:--:|:--|
| Cold start (p95, mid-range Android) | `< 1.8 s` | Integration test on a physical device |
| Frame build time (p99) | `< 16 ms` | Timeline parse, fails the build on regression |
| Jank frames per session | `< 0.5%` | Same harness, tracked over time |
| Release bundle size | `< 40 MB` | Size diff comment on every PR |
| Peak memory during inference | `< 220 MB` | Profiled in the device test run |

```yaml
# Performance gates run on every pull request. A regression is a red build,
# not a note in a retro doc nobody reads.
- name: Frame budget
  run: dart run tool/perf_gate.dart --p99-frame-ms 16 --cold-start-ms 1800
```

The point is not the specific numbers. The point is that a number exists at all: unmeasured performance degrades by default, one reasonable-looking commit at a time.

---

## ðŸ—“ï¸ Timeline

```mermaid
timeline
    title Where the focus has moved
    Web foundations : React Â· TypeScript Â· Node
                    : Design systems and component architecture
    Backend depth   : Java Â· Spring Â· Python
                    : SQL modeling and query performance
    Mobile pivot    : Flutter Â· Dart
                    : One codebase, native feel, real frame budgets
    On-device AI    : TFLite Â· quantization Â· computer vision
                    : Inference in the app bundle, nothing on the wire
    Now             : Offline-first architecture at scale
                    : Rust FFI Â· WebGPU inference Â· CRDT internals
```

---

## ðŸ“Š GitHub Analytics

<!--
  â”€â”€ WHY THESE ARE SELF-GENERATED â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€
  The popular Vercel-hosted card services (github-readme-stats,
  github-profile-summary-cards, github-profile-trophy, streak-stats) run a
  single shared GitHub token across millions of READMEs. When that quota is
  exhausted they render "Cards are temporarily rate limited" instead of stats.
  It is not a config problem and query params cannot fix it.

  Every panel below is instead generated by .github/workflows/metrics.yml using
  a personal token in this repo, committed to the `metrics` branch, and served
  from raw.githubusercontent. No shared quota, so nothing to rate limit.

  Setup instructions live at the top of that workflow file.
-->

Generated in this repository every six hours by [`metrics.yml`](../../blob/main/.github/workflows/metrics.yml) and served from the `metrics` branch. No third-party card service, so no rate limits and no broken images.

<div align="center">

### Overview

<img src="https://raw.githubusercontent.com/spencerscott/spencerscott/metrics/overview.svg" width="100%" alt="Repository, commit, and contribution totals" />

<br/><br/>

### Commit Calendar

<img src="https://raw.githubusercontent.com/spencerscott/spencerscott/metrics/calendar.svg" width="100%" alt="Isometric commit calendar with current and longest streak" />

<sub>A full year of daily volume plus current and longest streak. The flat stretches are usually deep work on one branch, not time off.</sub>

<br/><br/>

### Language Distribution

<img src="https://raw.githubusercontent.com/spencerscott/spencerscott/metrics/languages.svg" width="100%" alt="Most used and recently used languages by bytes and percentage" />

<sub>Measured with a real linguist pass over cloned repositories, so generated files and vendored dependencies don't inflate the numbers. Most-used shows history, recently-used shows where the work is now.</sub>

<br/><br/>

### Working Rhythm

<img src="https://raw.githubusercontent.com/spencerscott/spencerscott/metrics/habits.svg" width="100%" alt="Commit habits: productive hours, weekday distribution, indent style" />

<sub>Productive hours are in UTC+8. Read this as working rhythm, not output quality.</sub>

<br/><br/>

### Recent Activity

<img src="https://raw.githubusercontent.com/spencerscott/spencerscott/metrics/activity.svg" width="100%" alt="Recent pushes, pull requests, reviews, releases, and line changes" />

<br/><br/>

### Achievements

<img src="https://raw.githubusercontent.com/spencerscott/spencerscott/metrics/achievements.svg" width="100%" alt="GitHub achievements" />

</div>

<br/>

### Repository Signal

Live from shields.io, which is properly cached and does not share a token pool:

| Project | Stars | Last commit | Language | Size |
|:--|:--|:--|:--|:--|
| [Ingredient-to-Recipe](https://github.com/spencerscott/ingredient-to-recipe) | ![](https://img.shields.io/github/stars/spencerscott/ingredient-to-recipe?style=flat-square&label=%20&color=a78bfa) | ![](https://img.shields.io/github/last-commit/spencerscott/ingredient-to-recipe?style=flat-square&label=%20&color=6d28d9) | ![](https://img.shields.io/github/languages/top/spencerscott/ingredient-to-recipe?style=flat-square&label=%20&color=1c1b22) | ![](https://img.shields.io/github/repo-size/spencerscott/ingredient-to-recipe?style=flat-square&label=%20&color=fbbf24) |
| [Sync Engine](https://github.com/spencerscott/sync-engine) | ![](https://img.shields.io/github/stars/spencerscott/sync-engine?style=flat-square&label=%20&color=a78bfa) | ![](https://img.shields.io/github/last-commit/spencerscott/sync-engine?style=flat-square&label=%20&color=6d28d9) | ![](https://img.shields.io/github/languages/top/spencerscott/sync-engine?style=flat-square&label=%20&color=1c1b22) | ![](https://img.shields.io/github/repo-size/spencerscott/sync-engine?style=flat-square&label=%20&color=fbbf24) |
| [Frame Budget CI](https://github.com/spencerscott/frame-budget-ci) | ![](https://img.shields.io/github/stars/spencerscott/frame-budget-ci?style=flat-square&label=%20&color=a78bfa) | ![](https://img.shields.io/github/last-commit/spencerscott/frame-budget-ci?style=flat-square&label=%20&color=6d28d9) | ![](https://img.shields.io/github/languages/top/spencerscott/frame-budget-ci?style=flat-square&label=%20&color=1c1b22) | ![](https://img.shields.io/github/repo-size/spencerscott/frame-budget-ci?style=flat-square&label=%20&color=fbbf24) |

<br/>

<details>
<summary><b>ðŸ“Œ How to read these numbers</b></summary>
<br/>

| Panel | What it's good for | Where it lies |
|:--|:--|:--|
| Overview | One-glance scale of total output | Counts contributions, not their difficulty |
| Commit calendar | Consistency and momentum over a year | Squash merges compress many commits into one |
| Language distribution | Breadth against actual specialization | Byte counts favor verbose languages |
| Working rhythm | Timezone, cadence, working style | Says nothing about what got built |
| Recent activity | What I'm touching right now | Private-repo work shows as volume with no context |
| Achievements | Participation breadth | Mostly a function of time on the platform |

Commit graphs measure activity, not value. Read the repositories if you want to know whether the work is any good.

</details>

---

## âœï¸ Writing & Notes

Short technical write-ups from things that cost me a weekend, so they cost you an afternoon:

| Topic | The one-line version |
|:--|:--|
| Shrinking a vision model 8x | Distillation first, quantization second. Doing it in the other order wastes both. |
| Durable queues in Flutter | If the queue lives in memory, you don't have a queue, you have a hope. |
| Frame budgets in CI | p99 frame time is the only performance metric users can feel directly. |
| NNAPI delegate fallbacks | Assume the delegate will fail on some device you've never heard of. Plan the CPU path. |
| Conflict resolution policies | Last-write-wins is fine until two people care. Decide which fields are which. |
| Self-hosting README metrics | Shared-token card services will rate limit you. Generate in your own repo. |

---

## ðŸ¤ Working With Me

<table>
<tr>
<td width="50%" valign="top">

**I'm a good fit when**

You need something to feel fast on hardware you don't control. You care about privacy at the architecture level. You want one mobile codebase that doesn't feel like a compromise. You'd rather ship a smaller thing that works everywhere.

</td>
<td width="50%" valign="top">

**I'm the wrong call when**

The product is fundamentally a thin client over a big cloud model. You need native platform depth on one OS only. The timeline requires skipping the measurement work, which is usually where the value hides.

</td>
</tr>
</table>

**How I like to work:** small PRs, explicit tradeoffs written down before the code, performance numbers in the description. If I disagree with an approach I'll say so once, clearly, then commit to whatever we decide.

---

## ðŸ¤ Contact

Open to collaboration on mobile, on-device AI, and offline-first products. Best way in: a short note about what you're building and where it hurts.

<div align="center">

<a href="mailto:you@example.com"><img src="https://img.shields.io/badge/Email-f59e0b?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://linkedin.com/in/yourhandle"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://yoursite.com"><img src="https://img.shields.io/badge/Portfolio-6d28d9?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
<a href="https://github.com/spencerscott?tab=repositories"><img src="https://img.shields.io/badge/Repositories-1c1b22?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>

</div>

---

<div align="center">

**Thanks for stopping by.** â­

<sub>Every panel above is generated in this repository. No shared quotas, no rate limits, no broken images.</sub>

<br/>

*[Back to top](#top)*

</div>
