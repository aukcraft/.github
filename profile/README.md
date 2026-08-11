<div align="center">

<img src="https://raw.githubusercontent.com/aukcraft/.github/main/profile/aukcraft-logo.svg" alt="aukcraft logo" width="96" />

# aukcraft

**auk** — the seabird, an agile and precise hunter. **craft** — reverence for the craft itself.

A small open-source team building modular, reusable infrastructure — with a deliberately lightweight stack.
一个小而精的开源团队，以模块化思维构建可复用的基础设施——配以刻意轻量的技术栈。

![Current Focus](https://img.shields.io/badge/Current_Focus-Peregrine-14B8A6?style=flat-square)
![Latest Release](https://img.shields.io/badge/Latest_Release-v0.x-6B7280?style=flat-square)
![Rust](https://img.shields.io/badge/Rust-1E2A38?style=flat-square&logo=rust&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-2E8B57?style=flat-square)

</div>

---

## Who We Are / 我们是谁

aukcraft is a small open-source team obsessed with system architecture and engineering process. We believe that in the age of AI, the way code is produced has changed — but architectural thinking and engineering discipline remain human core competencies. Every module we build is designed to be independent, testable, and reusable: today's internal component is tomorrow's open-source crate.

> 我们专注系统架构与工程流程。不追求每一行代码都完美，而追求清晰的系统边界、可扩展的底层架构与高效的开发流程。

---

## Engineering Philosophy / 工程哲学

| Principle | What It Means |
|---|---|
| **Architecture over code / 架构优先于代码** | We invest the most effort at the design stage; code is the execution of architecture, not a substitute for it. |
| **Modularity as strategy / 模块化即战略** | Every component is independent, testable, and reusable — today's internal module is tomorrow's open-source crate. |
| **Process is product / 流程即产品** | CI/CD, code review, release strategy, and documentation are as important as the final code. |
| **Cross-platform by default / 跨平台是默认** | A lightweight native stack; every platform, first-class. |
| **Clarity over perfection / 清晰重于完美** | We optimize for clear system boundaries and extensible foundations, not flawless lines. |

---

## Current Project: Peregrine / 当前项目

**A programmable desktop visual overlay system** — originally built to solve 3D motion sickness for players, at its core it is a general-purpose visual anchor engine.
一个可编程的桌面视觉覆盖层系统，其核心是通用的视觉锚点引擎。

**Architecture highlights / 架构亮点：**

- **Four-layer programmable architecture** — Elements → Materials (Rhai scripts) → Layers → Profiles，四层可编程架构
- **Hot-reloadable configuration** — external edits take effect instantly; atomic writes never corrupt，热重载配置，原子写入
- **User-programmable** — drop-in `.rhai` material scripts with auto-generated interactive UI，用户可编程
- **High-performance overlay** — Rust + winit + softbuffer, transparent, always-on-top, follows target windows

**Stack:** Rust · Tauri 2.x · React · TypeScript · Tailwind CSS · Rhai
**Platform:** Windows (x86 / x64 / ARM64); macOS & Linux planned. **License:** MIT

[View Project / 查看项目](https://github.com/eeymoo/peregrine) · [Download Latest / 下载最新版](https://github.com/eeymoo/peregrine/releases) · [Contributing / 贡献指南](https://github.com/eeymoo/peregrine/blob/main/CONTRIBUTING.md)

---

## Technical Foundation / 技术底座

```
Language    Rust                  — systems programming, performance, safety
Desktop     Tauri 2.x             — lightweight cross-platform desktop runtime
Frontend    React + TypeScript    — precise, typed UI engineering
Styling     Tailwind CSS          — constrained, consistent design tokens
Scripting   Rhai                  — user-facing programmability, embedded in Rust
```

---

## What's Next / 未来方向

- **More desktop tools** — new overlay tools for different scenarios, built on Peregrine's visual engine. 基于 Peregrine 可视化引擎延伸更多桌面工具。
- **Developer infrastructure** — extracting battle-tested modules (config system, hot reload, cross-platform path abstraction) into standalone open-source Rust crates. 将验证过的模块化组件抽离为独立开源 crate。
- **Cross-platform runtime** — making Tauri + Rust desktop development more efficient and standardized. Follow our roadmap as it unfolds. 跨平台运行时标准化——关注我们的路线图。

---

## Join Us / 加入我们

We're looking for contributors who care about the craft / 我们在寻找同样敬畏手艺的你：

- **Rust developers** — systems programming, performance optimization, cross-platform abstraction
- **Frontend engineers** — React / TypeScript, developer experience, UI precision
- **Designers** — tool-product design, interaction detail, visual restraint
- **Testing / QA** — automation, CI, release pipelines

**How to contribute:** open an Issue, send a Pull Request, or write to **dev@aukcraft.org** for technical discussion and architecture consulting.
参与方式：提交 Issue / PR，或邮件联系 dev@aukcraft.org。

---

<div align="center">

**hello@aukcraft.org** — general & community · **dev@aukcraft.org** — technical · **security@aukcraft.org** — vulnerability reports

[github.com/aukcraft](https://github.com/aukcraft) · [aukcraft.org](https://aukcraft.org) · [中文版本](README.zh-CN.md)

© 2026 aukcraft. Crafted with precision.

</div>
