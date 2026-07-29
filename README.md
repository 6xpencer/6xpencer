<a name="top"></a>

<div align="center">

<a href="https://github.com/spencerscott">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=30&duration=2600&pause=900&color=A78BFA&center=true&vCenter=true&width=780&height=90&lines=Spencer+Scott;Full-Stack+%26+Mobile+Developer;Flutter+%C2%B7+On-Device+AI+%C2%B7+Offline-First;Models+that+run+on+the+phone%2C+not+the+cloud" alt="Spencer Scott, Full-Stack and Mobile Developer" />
</a>

<br/>

<a href="https://github.com/spencerscott"><img src="https://komarev.com/ghpvc/?username=spencerscott&color=a78bfa&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile views" /></a>
<a href="https://github.com/spencerscott?tab=followers"><img src="https://img.shields.io/github/followers/spencerscott?color=fbbf24&style=for-the-badge&label=FOLLOWERS&labelColor=1c1b22" alt="Followers" /></a>
<a href="https://github.com/spencerscott?tab=repositories"><img src="https://img.shields.io/github/stars/spencerscott?color=a78bfa&style=for-the-badge&label=STARS&labelColor=1c1b22" alt="Stars" /></a>
<a href="mailto:you@example.com"><img src="https://img.shields.io/badge/OPEN%20TO-COLLABORATION-6d28d9?style=for-the-badge&labelColor=1c1b22" alt="Open to collaboration" /></a>

<br/><br/>

**[About](#about) | [Principles](#principles) | [Stack](#stack) | [Architecture](#architecture) | [Work](#work) | [Performance](#performance) | [Analytics](#analytics) | [Contact](#contact)**

</div>

---

## About

I build software across the full stack: **React** and **TypeScript** on the front end, **Flutter** for mobile, **Java** and **Python** for backend services, and **SQL** underneath it all.

My focus is on-device intelligence: pushing machine learning to the edge so applications respond instantly, work without connectivity, and keep user data on the device. No round-trips. No privacy tradeoffs. No excuses about signal.

```yaml
identity:
  name: Spencer Scott
  role: Full-Stack and Mobile Developer
  focus:
    - Flutter
    - On-Device AI
    - Offline-First Architecture
  building: Ingredient-to-Recipe
  principle: Ship fast. Respect privacy. Sweat the details.
```

<table>
<tr>
<td width="50%" valign="top">

**What I reach for first**

Flutter for anything with a screen and a user. One codebase, native feel on both platforms, and a render pipeline predictable enough to hit a frame budget on purpose.

</td>
<td width="50%" valign="top">

**What I avoid**

Server calls in the hot path. Client state that only makes sense when a request succeeds. Any architecture where "you must be online" is part of the user experience.

</td>
</tr>
</table>

---

## Principles

> **Great applications are not just built. They are felt.**
> Every interaction should be instant, every screen should feel alive, and every byte should respect the person holding the device.

| Principle | In practice |
|:--|:--|
| **Mobile-first** | One codebase with a native feel on every platform. |
| **On-device AI** | Models run locally. Private by architecture, not by policy. |
| **Offline-first** | The network is an enhancement, never a dependency. |
| **Built to last** | Clean architecture over expedient hacks. |
| **Measured, not guessed** | Frame time, cold start, and bundle size tracked in CI. |
| **Boring where it counts** | Novel in the product, conservative in the plumbing. |

---

## Stack

<details open>
<summary><b>Languages</b></summary>
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
<summary><b>Frameworks and platforms</b></summary>
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
<summary><b>AI, data, testing, and delivery</b></summary>
<br/>

![TensorFlow Lite](https://img.shields.io/badge/TensorFlow%20Lite-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

</details>

---

## Architecture

Offline-first is not a cache. The local database is the source of truth, and the server is a peer that syncs when reachable.

```mermaid
flowchart TB
    UI["UI Layer: reads local state"]
    LOCAL["Local Store: SQLite source of truth"]
    QUEUE["Mutation Queue: durable, ordered, idempotent"]
    SYNC["Sync Engine: backoff, dedupe, resolve"]
    REMOTE["Remote: optional peer"]

    UI -->|write intent| LOCAL
    LOCAL -->|optimistic commit| UI
    LOCAL --> QUEUE
    QUEUE --> SYNC
    SYNC <-->|when reachable| REMOTE
    SYNC -->|reconciled state| LOCAL

    style UI fill:#6d28d9,stroke:#a78bfa,color:#ffffff
    style LOCAL fill:#4c1d95,stroke:#a78bfa,color:#ffffff
    style SYNC fill:#b45309,stroke:#fbbf24,color:#ffffff
    style REMOTE fill:#3f3f46,stroke:#a1a1aa,color:#ffffff
```

---

## Work

### Ingredient-to-Recipe

An offline-first Flutter application that identifies ingredients from a single photo and generates recipe suggestions entirely on-device. No server, no account, no connection required.

| Metric | Target | Why it matters |
|:--|:--:|:--|
| Inference latency | `< 400 ms` | Recognition should feel like a camera shutter. |
| End-to-end result | `< 1 s` | Photo to ranked recipes without a loading state. |
| Network calls | `0` | No telemetry, latency variance, or request cost. |
| Model footprint | `~12 MB` | The whole inference pipeline fits in the app bundle. |

**What was hard:** the first model was 94 MB and took 2.3 seconds on a mid-range Android device. Getting to 12 MB and 380 ms cost four points of top-1 accuracy, but recipe ranking tolerates a wrong guess better than a two-second wait. Pick the metric the user actually feels.

| Project | Description | Stack |
|:--|:--|:--|
| **Sync Engine** | Durable mutation queue with retries, backoff, ordering, and conflict policies. | Dart, SQLite, Drift |
| **Frame Budget CI** | GitHub Action that fails builds when p99 frame time regresses. | Dart, Actions, Python |
| **Model Shrink Toolkit** | Distillation, pruning, and INT8 export with accuracy reporting. | Python, PyTorch, ONNX |

---

## Performance

| Budget | Threshold | Enforced by |
|:--|:--:|:--|
| Cold start, p95 | `< 1.8 s` | Physical-device integration test |
| Frame build time, p99 | `< 16 ms` | Timeline parser |
| Jank frames per session | `< 0.5%` | Device test harness |
| Release bundle size | `< 40 MB` | Size diff on every pull request |
| Peak memory during inference | `< 220 MB` | Profiled device test |

---

## Analytics

The previous analytics section showed broken images because it depended on generated files that had not been published yet. This version uses live, cached Shields endpoints, so the section is useful immediately and does not render empty boxes.

<div align="center">

### Profile snapshot

<a href="https://github.com/spencerscott?tab=overview"><img src="https://img.shields.io/github/followers/spencerscott?style=for-the-badge&label=followers&color=a78bfa&labelColor=1c1b22" alt="Followers" /></a>
<a href="https://github.com/spencerscott?tab=repositories"><img src="https://img.shields.io/github/repositories/spencerscott?style=for-the-badge&label=repositories&color=6d28d9&labelColor=1c1b22" alt="Public repositories" /></a>
<a href="https://github.com/spencerscott?tab=stars"><img src="https://img.shields.io/github/stars/spencerscott?style=for-the-badge&label=stars&color=fbbf24&labelColor=1c1b22" alt="Stars" /></a>
<a href="https://github.com/spencerscott"><img src="https://img.shields.io/github/commit-activity/y/spencerscott/spencerscott?style=for-the-badge&label=commits%20this%20year&color=7c3aed&labelColor=1c1b22" alt="Commits this year" /></a>

</div>

### Repository health

| Repository | Activity | Last commit | Language | Size |
|:--|:--|:--|:--|:--|
| [Ingredient-to-Recipe](https://github.com/spencerscott/ingredient-to-recipe) | ![Commits](https://img.shields.io/github/commit-activity/y/spencerscott/ingredient-to-recipe?style=flat-square&label=commits&color=6d28d9) | ![Last commit](https://img.shields.io/github/last-commit/spencerscott/ingredient-to-recipe?style=flat-square&label=%20&color=a78bfa) | ![Language](https://img.shields.io/github/languages/top/spencerscott/ingredient-to-recipe?style=flat-square&label=%20&color=b45309) | ![Size](https://img.shields.io/github/repo-size/spencerscott/ingredient-to-recipe?style=flat-square&label=%20&color=fbbf24) |
| [Sync Engine](https://github.com/spencerscott/sync-engine) | ![Commits](https://img.shields.io/github/commit-activity/y/spencerscott/sync-engine?style=flat-square&label=commits&color=6d28d9) | ![Last commit](https://img.shields.io/github/last-commit/spencerscott/sync-engine?style=flat-square&label=%20&color=a78bfa) | ![Language](https://img.shields.io/github/languages/top/spencerscott/sync-engine?style=flat-square&label=%20&color=b45309) | ![Size](https://img.shields.io/github/repo-size/spencerscott/sync-engine?style=flat-square&label=%20&color=fbbf24) |
| [Frame Budget CI](https://github.com/spencerscott/frame-budget-ci) | ![Commits](https://img.shields.io/github/commit-activity/y/spencerscott/frame-budget-ci?style=flat-square&label=commits&color=6d28d9) | ![Last commit](https://img.shields.io/github/last-commit/spencerscott/frame-budget-ci?style=flat-square&label=%20&color=a78bfa) | ![Language](https://img.shields.io/github/languages/top/spencerscott/frame-budget-ci?style=flat-square&label=%20&color=b45309) | ![Size](https://img.shields.io/github/repo-size/spencerscott/frame-budget-ci?style=flat-square&label=%20&color=fbbf24) |

### What the numbers mean

| Signal | Useful for | Limitation |
|:--|:--|:--|
| Followers and stars | Audience and project interest | Not a quality score. |
| Commit activity | Recent momentum | Squash merges compress many commits. |
| Top language | Repository identity | It does not show architecture or quality. |
| Last commit | Maintenance signal | A quiet project may simply be finished. |
| Repository size | Rough project scale | Assets and generated files can distort it. |

No fake green squares, no broken generated SVGs, no shared GitHub token pool. Just live links and numbers that render.

---

## Contact

Open to collaboration on mobile, on-device AI, and offline-first products. Best way in: a short note about what you are building and where it hurts.

<div align="center">

<a href="mailto:you@example.com"><img src="https://img.shields.io/badge/Email-f59e0b?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://linkedin.com/in/yourhandle"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://yoursite.com"><img src="https://img.shields.io/badge/Portfolio-6d28d9?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
<a href="https://github.com/spencerscott?tab=repositories"><img src="https://img.shields.io/badge/Repositories-1c1b22?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>

<br/><br/>

**Thanks for stopping by.**

<br/>

*[Back to top](#top)*

</div>
