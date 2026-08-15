<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/aukcraft/.github/main/profile/aukcraft-logo-dark.svg" />
  <img src="https://raw.githubusercontent.com/aukcraft/.github/main/profile/aukcraft-logo.svg" alt="aukcraft logo" width="96" />
</picture>

# aukcraft

**auk** —— 海雀，敏捷精准的猎手。**craft** —— 工艺，对手艺的敬畏。

一个小而精的开源团队，以模块化思维构建可复用的基础设施——配以刻意轻量的技术栈。
A small open-source team building modular, reusable infrastructure — with a deliberately lightweight stack.

![当前焦点](https://img.shields.io/badge/当前焦点-Peregrine-14B8A6?style=flat-square)
![最新发布](https://img.shields.io/badge/最新发布-v0.x-6B7280?style=flat-square)
![Rust](https://img.shields.io/badge/Rust-1E2A38?style=flat-square&logo=rust&logoColor=white)
![开源协议](https://img.shields.io/badge/协议-MIT-2E8B57?style=flat-square)

</div>

---

## 我们是谁 / Who We Are

aukcraft 是一个小而精的开源团队，执着于系统架构与工程流程。我们相信：AI 改变了代码的生产方式，但架构思维与工程素养依然是人的核心竞争力。我们构建的每个模块都独立、可测试、可复用——今天的内部组件，就是明天的开源 crate。

> We don't chase perfect lines of code. We chase clear system boundaries, extensible architecture, and efficient engineering process.

---

## 工程哲学 / Engineering Philosophy

| 原则 | 含义 |
|---|---|
| **规范驱动开发 / Spec-Driven Development** | 先写规格，再写代码——规格是团队与 AI 协作的单一事实来源。 |
| **模块化即战略 / Modularity as strategy** | 每个组件独立、可测试、可复用——今天的内部模块，明天就是开源 crate。 |
| **流程即产品 / Process is product** | CI/CD、代码审查、发布策略与文档，与最终代码同等重要。 |
| **性能是底线 / Performance as baseline** | 每一帧都有预算；性能不是事后优化，而是设计之初的约束。 |

---

## 当前项目：Peregrine / Current Project

**一个可编程的桌面视觉覆盖层系统**——最初为解决 3D 眩晕而生，其核心是通用的视觉锚点引擎。
A programmable desktop visual overlay system — a general-purpose visual anchor engine at its core.

**架构亮点 / Architecture highlights：**

- **四层可编程架构** — Elements → Materials（Rhai 脚本）→ Layers → Profiles
- **热重载配置** — 外部编辑即时生效，原子写入永不损坏
- **用户可编程** — drop-in `.rhai` 材质脚本，自动生成交互 UI
- **高性能覆盖层** — Rust + winit + softbuffer，透明置顶、跟随目标窗口

**技术栈：** Rust · Tauri 2.x · React · TypeScript · Tailwind CSS · Rhai
**平台：** Windows（x86 / x64 / ARM64），macOS & Linux 规划中。**协议：** MIT

[查看项目 / View Project](https://github.com/eeymoo/peregrine) · [下载最新版 / Download](https://github.com/eeymoo/peregrine/releases) · [贡献指南 / Contributing](https://github.com/eeymoo/peregrine/blob/main/CONTRIBUTING.md)

---

## 工作流程 / Workflow

```
规格  SDD     — 规格驱动开发：先写规格，再写代码
测试  TDD     — 测试驱动开发：红、绿、重构
审查  Review  — 每一处变更都要过设计与代码评审
集成  CI/CD   — 自动化构建、测试与发布，流程说了算
沉淀  Docs    — 决策留痕，规格归档，知识不流失
```

**流程不是束缚——流程是让速度可持续的东西。**
Process isn't overhead. Process is how speed stays sustainable.

---

## 未来方向 / What's Next

- **更多桌面工具** — 基于 Peregrine 可视化引擎，延伸出不同场景的覆盖层工具。
- **开发者基础设施** — 将 Peregrine 中验证过的模块化组件（配置系统、热重载、跨平台路径抽象）抽离为独立开源的 Rust crate。
- **跨平台运行时** — 让基于 Tauri + Rust 的桌面应用开发更高效、更标准化。关注我们的路线图 / Follow our roadmap.

---

## 加入我们 / Join Us

我们在寻找同样敬畏手艺的人 / We're looking for people who care about the craft：

- **SDD 工程师** — 规格驱动开发：把规格与意图变成可运行的系统
- **Skills 工程师** — 把 prompt 与工作流沉淀为可复用的技能，从能力到产品
- **产品设计** — 设计更符合用户直觉的产品
- **UI/UX 设计师** — 界面与交互设计，关注细节与视觉克制

**参与方式：** 提交 Issue、发起 Pull Request，或邮件联系 **dev@aukcraft.org** 进行技术讨论与架构咨询。
Open an Issue, send a PR, or write to dev@aukcraft.org.

---

<div align="center">

**hello@aukcraft.org** — 通用咨询 · **dev@aukcraft.org** — 技术讨论 · **security@aukcraft.org** — 安全漏洞报告

[github.com/aukcraft](https://github.com/aukcraft) · [aukcraft.org](https://aukcraft.org) · [English Version](README.md)

© 2026 aukcraft. Crafted with precision.

</div>
