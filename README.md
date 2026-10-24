<!--
  OasisViridis / Profile README
  Visual direction: Viridian Workbench
  Palette: viridian green + GitHub-native light/dark canvas
  Works without JavaScript, custom CSS, or GitHub Actions.
  Image sources: capsule-render, readme-typing-svg, shields.io, github-readme-stats.
-->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&amp;color=0:0D1117,55:164B34,100:247B54&amp;height=215&amp;section=header&amp;text=OASISVIRIDIS&amp;fontSize=46&amp;fontColor=F0FFF4&amp;fontAlignY=37&amp;desc=Yifan%20Liang%20-%20AI%20Agent%20Tooling&amp;descSize=16&amp;descAlignY=60" />
    <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&amp;color=0:F6FFF8,55:D9F6E4,100:9CDBB5&amp;height=215&amp;section=header&amp;text=OASISVIRIDIS&amp;fontSize=46&amp;fontColor=174D32&amp;fontAlignY=37&amp;desc=Yifan%20Liang%20-%20AI%20Agent%20Tooling&amp;descSize=16&amp;descAlignY=60" />
    <img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:F6FFF8,55:D9F6E4,100:9CDBB5&amp;height=215&amp;section=header&amp;text=OASISVIRIDIS&amp;fontSize=46&amp;fontColor=174D32&amp;fontAlignY=37&amp;desc=Yifan%20Liang%20-%20AI%20Agent%20Tooling&amp;descSize=16&amp;descAlignY=60" width="100%" alt="OasisViridis — Yifan Liang, AI Agent Tooling" />
  </picture>
</div>

<h2 align="center">做 AI Agent 的工具，也做它工作时的界面。</h2>
<p align="center"><em>Tools for AI agents, and the interfaces they work in.</em></p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com/?font=Fira+Code&amp;size=17&amp;duration=2700&amp;pause=1100&amp;color=56D48A&amp;center=true&amp;vCenter=true&amp;width=450&amp;height=40&amp;lines=Agent+tooling;Local-first+desktop+software;Python+%2B+TypeScript+on+Windows" />
    <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com/?font=Fira+Code&amp;size=17&amp;duration=2700&amp;pause=1100&amp;color=17683D&amp;center=true&amp;vCenter=true&amp;width=450&amp;height=40&amp;lines=Agent+tooling;Local-first+desktop+software;Python+%2B+TypeScript+on+Windows" />
    <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&amp;size=17&amp;duration=2700&amp;pause=1100&amp;color=17683D&amp;center=true&amp;vCenter=true&amp;width=450&amp;height=40&amp;lines=Agent+tooling;Local-first+desktop+software;Python+%2B+TypeScript+on+Windows" width="450" alt="Agent tooling · Local-first desktop software · Python and TypeScript on Windows" />
  </picture>
</p>

<p align="center">
  <img alt="Focus: Agent tooling" src="https://img.shields.io/badge/FOCUS-Agent%20tooling-247B54?style=for-the-badge&amp;labelColor=193B2B" />
  <img alt="Craft: Desktop interfaces" src="https://img.shields.io/badge/CRAFT-Desktop%20interfaces-247B54?style=for-the-badge&amp;labelColor=193B2B" />
  <img alt="Approach: Local-first" src="https://img.shields.io/badge/APPROACH-Local--first-247B54?style=for-the-badge&amp;labelColor=193B2B" />
</p>

---

## 01 / 当前主线 · Building now

两个相互补充的方向：**让 Agent 的交付过程更可验证，让它的工作过程更可见。**

### [`TheMasterplan`](https://github.com/OasisViridis/TheMasterplan) · 交付协议

**Python · GitHub + Jujutsu**

面向 GitHub 与 Jujutsu 的轻量 AI 辅助交付协议。重点不是把流程做复杂，而是把三个边界说清楚：**最小上下文、可验证交付、明确的人类决策边界**。

`less context` → `verifiable delivery` → `human decision`

### [`Pioneer`](https://github.com/OasisViridis/Pioneer) · Agent 桌面工作台

**Electron · TypeScript · 毕业设计**

模块化 Agent 桌面工作台，围绕本地项目海报墙、多标签会话与可停靠面板组织工作空间。目标是让 Agent 的**工具调用与文件改动直接呈现在界面上**，而不是藏在对话背后。

`project wall` → `tabbed sessions` → `dockable workspace` → `observable actions`

## 02 / 延伸探索 · Along the way

### [`dsh-persona-hazel`](https://github.com/OasisViridis/dsh-persona-hazel) · 人格卡与召回

**Python · DeepSeek Harness**

把公开素材中提炼出的说话方式整理为静态人格卡与召回片段，封装成 DeepSeek Harness 插件。关注人格表达如何以**可组织、可调用**的形式进入 Agent 工具链。

### [`Supersonic`](https://github.com/OasisViridis/Supersonic) · 多屏协同 HMI

**React · FastAPI · WebSocket**

智能座舱多屏协同原型：通过 WebSocket 广播同一份状态快照，让多个界面基于一致状态协同展示。**2026 年 8 月基线冻结**；也是毕业设计的前期探索之一。

### [`IdlerDream`](https://github.com/OasisViridis/IdlerDream) · 工作区观察仪表盘

**Windows · Local-first · 只读**

观察多个工作区与运行中的 Agent 进程的本地只读仪表盘。**2026 年 8 月停止开发，未正式发布**；保留为一次围绕本地可观测性的探索。

<details>
  <summary><strong>更多项目 / More repositories</strong></summary>

- [`dsh-manqu-pet`](https://github.com/OasisViridis/dsh-manqu-pet) — DeepSeek Harness Web GUI 的桌面宠物。
- [`BagItUp`](https://github.com/OasisViridis/BagItUp) — 为文稿采集视频素材，并完成校验与归档。
- [`linshe-marketplace-miniapp`](https://github.com/OasisViridis/linshe-marketplace-miniapp) — 校园二手交易小程序，课程作业。

</details>

---

## 03 / 工具箱 · The stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-215B40?style=flat-square&amp;logo=python&amp;logoColor=FFFFFF" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-215B40?style=flat-square&amp;logo=typescript&amp;logoColor=FFFFFF" />
  <img alt="Electron" src="https://img.shields.io/badge/Electron-215B40?style=flat-square&amp;logo=electron&amp;logoColor=FFFFFF" />
  <img alt="React" src="https://img.shields.io/badge/React-215B40?style=flat-square&amp;logo=react&amp;logoColor=FFFFFF" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-215B40?style=flat-square&amp;logo=fastapi&amp;logoColor=FFFFFF" />
  <img alt="Git" src="https://img.shields.io/badge/Git-215B40?style=flat-square&amp;logo=git&amp;logoColor=FFFFFF" />
  <img alt="Jujutsu" src="https://img.shields.io/badge/Jujutsu-215B40?style=flat-square&amp;logoColor=FFFFFF" />
</p>

**语言** · Python / TypeScript / JavaScript / PowerShell  
**界面与服务** · Electron / React / Vite / FastAPI  
**开发环境与版本控制** · Windows / Git / Jujutsu

---

## 04 / GitHub · In the open

<p align="center">
  <a href="https://github.com/OasisViridis?tab=repositories" aria-label="查看 OasisViridis 的 GitHub 仓库">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=OasisViridis&amp;show_icons=true&amp;hide_rank=true&amp;theme=github_dark&amp;title_color=56D48A&amp;icon_color=56D48A&amp;hide_border=true&amp;bg_color=0D1117" />
      <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=OasisViridis&amp;show_icons=true&amp;hide_rank=true&amp;theme=default&amp;title_color=17683D&amp;icon_color=238636&amp;hide_border=true&amp;bg_color=FFFFFF" />
      <img src="https://github-readme-stats.vercel.app/api?username=OasisViridis&amp;show_icons=true&amp;hide_rank=true&amp;theme=default&amp;title_color=17683D&amp;icon_color=238636&amp;hide_border=true&amp;bg_color=FFFFFF" width="470" alt="OasisViridis GitHub public activity statistics" />
    </picture>
  </a>
</p>

<p align="center"><sub>统计由公开 GitHub 数据动态生成；项目内容以上方仓库为准。</sub></p>

<p align="center">
  <strong>Tools for the work. Interfaces for the human.</strong>
</p>
