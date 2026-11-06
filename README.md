<div align="center">

# 🚀 Awesome AI Agent Engineering

### 從「收藏熱門 Repo」到「打造能正式交付的 AI Agent 系統」

**A curated, practical, Traditional Chinese guide to AI Agents, Coding Agents, Skills, MCP, RAG, Computer Use, Evaluation & Enterprise AI.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Language](https://img.shields.io/badge/Language-繁體中文-0f766e)](#)
[![Focus](https://img.shields.io/badge/Focus-Engineering%20%26%20Production-2563eb)](#)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-f59e0b)](#貢獻指南)

[📜 舊版首頁與歷史索引](./README_ARCHIVE_2026-07-26.md) · [📁 每日追蹤歷史檔案](./)

**不是另一份只有連結的 Awesome List。** 這份指南回答三個問題：**這工具解決什麼問題？什麼時候該用？如何驗證真的有用？**

[⚡ 先看精選](#-編輯精選從這裡開始) · [🧭 選型指南](#-30-秒選型指南) · [🗺️ 技術地圖](#-ai-agent-技術地圖) · [📚 Repo 全索引](#-repo-全索引) · [🛠️ 實戰專案](#-從收藏到實作五個-project-blueprints) · [🤝 貢獻](#-貢獻指南)

</div>

> [!IMPORTANT]
> **資料整理日：2026-11-06。** 本清單整理自歷次 GitHub AI Agent 追蹤紀錄，已去除重複項目，並依用途重新編排。它是**編輯精選與選型指南**，不是 GitHub 官方 Trending 排行，也不宣稱列出的專案都在當日熱門榜。開源專案變動很快，請以連結中的官方 README、版本、授權與安全公告為準。為避免誤導，**不放入無法持續維護的即時 Star 數及成長率**。

## ✨ 為什麼值得收藏？

- **按問題找工具**：從「我要做多 Agent」、「我要讓 Agent 操作網頁」到「如何防止越權」，皆可直接找到候選方案。
- **區分工具層次**：Framework、Harness、Runtime、Orchestrator、Skill、MCP、Memory、Evaluation，不再混為一談。
- **關注正式部署**：權限、審核、追蹤、隔離、成本、可靠性與 ROI，不只看 Demo。
- **提供實戰專案**：給出架構組合、測試方法及驗收指標，而不是只說「值得學習」。
- **繁體中文、保留英文專有名詞**：適合台灣工程師、AI 架構師、顧問與技術 PM。

---

## 📑 目錄

- [🏆 編輯精選：從這裡開始](#-編輯精選從這裡開始)
- [🧭 30 秒選型指南](#-30-秒選型指南)
- [🗺️ AI Agent 技術地圖](#-ai-agent-技術地圖)
- [📚 Repo 全索引](#-repo-全索引)
  - [01. Agent Frameworks 與 Orchestration](#01-agent-frameworks-與-orchestration)
  - [02. Coding Agents 與開發工作台](#02-coding-agents-與開發工作台)
  - [03. Skills、Prompt Workflow 與規格驅動開發](#03-skillsprompt-workflow-與規格驅動開發)
  - [04. Browser Automation 與 Computer Use](#04-browser-automation-與-computer-use)
  - [05. Memory、Context Engineering 與 RAG](#05-memorycontext-engineering-與-rag)
  - [06. Evaluation、Security 與 Governance](#06-evaluationsecurity-與-governance)
  - [07. Enterprise Integration、Data 與 Infrastructure](#07-enterprise-integrationdata-與-infrastructure)
  - [08. AI 商業應用與多模態產品](#08-ai-商業應用與多模態產品)
  - [09. 學習資源與研究](#09-學習資源與研究)
- [⚔️ 常見選型對決](#️-常見選型對決)
- [🛠️ 從收藏到實作：五個 Project Blueprints](#️-從收藏到實作五個-project-blueprints)
- [🗓️ 30 天學習路線](#️-30-天學習路線)
- [📏 企業級 Agent 驗收框架](#-企業級-agent-驗收框架)
- [📊 SWOT](#-swot這份資源庫的價值與限制)
- [🔎 收錄標準與資料可信度](#-收錄標準與資料可信度)
- [🤝 貢獻指南](#-貢獻指南)
- [📖 核心參考資料](#-核心參考資料)

---

## 🏆 編輯精選：從這裡開始

> **推薦理由基於技術學習與應用場景，不代表 Star 排名，也不保證符合正式環境要求。**

| 你想解決的問題 | 優先研究 | 為什麼值得看 | 第一個可驗證成果 |
|---|---|---|---|
| 搭建完整 Agent Harness | [Deep Agents](https://github.com/langchain-ai/deepagents) | 工具、檔案系統、任務規劃與 Subagent 的可組合設計 | 完成具有工具呼叫與人工審查的 Agent |
| 多個 Agent 協調工作 | [Paperclip](https://github.com/paperclipai/paperclip) | 從任務、角色、預算到審批的組織化管理 | 多 Agent 不重複領取任務 |
| 改善 Coding Agent 開發品質 | [Superpowers](https://github.com/obra/superpowers) | 規格、TDD、Worktree、Code Review 的工程流程 | 與原生 Agent 做同題 A/B Test |
| 將 Skills 系統化 | [Anthropic Skills](https://github.com/anthropics/skills) | Skill 格式、範例與能力封裝模式 | 做出一個可重用的 `SKILL.md` |
| Agent 操作網頁 | [agent-browser](https://github.com/vercel-labs/agent-browser) | 結構化頁面觀察與瀏覽器操作 CLI | 完成三種網站操作任務 |
| Agent 操作桌面軟體 | [Agent Desktop](https://github.com/vercel-labs/agent-desktop) | 作業系統 Accessibility API 與可定位的 UI 元素 | 在隔離環境完成桌面工作流 |
| Agent 跨 Session 記住進度 | [Claude-Mem](https://github.com/thedotmack/claude-mem) | 開發活動記錄與記憶檢索 | 第二次 Session 少做多少重複工作 |
| 長期知識與反思 | [Hindsight](https://github.com/vectorize-io/hindsight) | Retain / Recall / Reflect 模式 | 測量跨任務記憶的品質 |
| Agent 程式碼安全審查 | [Cloudflare Security Audit Skill](https://github.com/cloudflare/security-audit-skill) | 漏洞尋找與獨立驗證的分工 | 可重現、具證據的稽核結果 |
| Agent 行為測試 | [Agent Lightning](https://github.com/microsoft/agent-lightning) | Agent 軌跡蒐集與訓練研究 | 建立任務 Reward 與評估集 |
| 企業資料語意層 | [NVIDIA Auto-Ontology](https://github.com/NVIDIA/auto-ontology) | 商業術語、資料關係與 Text-to-SQL 治理 | 檢查 Agent 能否正確判斷資料不足 |
| AI Agent 成本與權限治理 | [Nasiko](https://github.com/Nasiko-Labs/nasiko) | Model Routing、Agent Control 與觀測性方向 | 每項任務可追蹤成本與工具使用 |

**只選三個入門？** 建議先用 **Deep Agents → Superpowers → agent-browser**，分別建立 Agent 基礎、工程交付流程，以及能驗收的工具執行能力。

---

## 🧭 30 秒選型指南

| 你的真實需求 | 第一個要查的專案 | 也值得比較 | 避免的誤區 |
|---|---|---|---|
| 用 Python 建立可以呼叫工具的 Agent | [Deep Agents](https://github.com/langchain-ai/deepagents) | [LangGraph](https://github.com/langchain-ai/langgraph) | 不要把所有流程都包成自由循環的 Agent |
| 任務流程有固定分支、人工核准與狀態恢復 | [LangGraph](https://github.com/langchain-ai/langgraph) | [Deep Agents](https://github.com/langchain-ai/deepagents) | 不要只靠 Prompt 保證狀態一致 |
| 多個 Coding Agents 平行開發 | [Worktrunk](https://github.com/max-sixty/worktrunk) | [Orca](https://github.com/stablyai/orca) | Worktree 不會隔離資料庫、Port 與外部服務 |
| 跨多個 Session 持續開發 | [Beads](https://github.com/gastownhall/beads) | [Claude-Mem](https://github.com/thedotmack/claude-mem) | Memory ≠ Task Tracking |
| Agent 研究網站並取得資料 | [Scrapling](https://github.com/D4Vinci/Scrapling) | [agent-browser](https://github.com/vercel-labs/agent-browser) | 不代表能合法或穩定取得所有網站 |
| 在沒有 API 的桌面系統完成操作 | [Agent Desktop](https://github.com/vercel-labs/agent-desktop) | [Mika](https://github.com/wangzan101/Mika)（Android） | 不要在正式帳號直接測試高權限操作 |
| 企業知識庫問答 | [WeKnora](https://github.com/Tencent/WeKnora) | [Hindsight](https://github.com/vectorize-io/hindsight) | 檢索到文件不等於答案必然正確 |
| 企業 SQL 問答 | [Auto-Ontology](https://github.com/NVIDIA/auto-ontology) | [WeKnora](https://github.com/Tencent/WeKnora) | Schema 不是商業指標定義 |
| Agent 上線前評估 | [iFixAi](https://github.com/ifixai-ai/iFixAi) | [Agent Lightning](https://github.com/microsoft/agent-lightning) | 不要把模型當裁判的評分視為最終事實 |
| 私有模型與推論最佳化 | [FreeToken](https://github.com/FlashML-org/FreeToken) | [colibri](https://github.com/JustVugg/colibri) | 能載入模型 ≠ 可接受的推論速度 |
| AI 影片與產品動畫 | [HyperFrames](https://github.com/heygen-com/hyperframes) | [OpenMontage](https://github.com/calesthio/OpenMontage) | 自動製作仍需素材授權及 QA |
| 社群內容生產與排程 | [Postiz](https://github.com/gitroomhq/postiz-app) | [last30days-skill](https://github.com/mvanhorn/last30days-skill) | Trending 不等於經過時序驗證的爆文 |

---

## 🗺️ AI Agent 技術地圖

```text
                           ┌─────────────────────────────┐
                           │         Business Goal       │
                           │       需求 / KPI / ROI       │
                           └──────────────┬──────────────┘
                                          │
                           ┌──────────────▼──────────────┐
                           │   Agent Orchestration       │
                           │  LangGraph / Deep Agents    │
                           └──────────────┬──────────────┘
                                          │
             ┌────────────────────────────┼───────────────────────────┐
             │                            │                           │
      ┌──────▼──────┐              ┌──────▼──────┐             ┌──────▼──────┐
      │ Skills / SOP│              │ Tools / MCP │             │Memory / RAG │
      │ Superpowers │              │ Browser     │             │ Hindsight   │
      │ Anthropic   │              │ Desktop/API │             │ Claude-Mem  │
      └──────┬──────┘              └──────┬──────┘             └──────┬──────┘
             │                            │                           │
             └────────────────────────────┼───────────────────────────┘
                                          │
                           ┌──────────────▼──────────────┐
                           │  Execution / Sandbox / CI   │
                           │ Worktree / Docker / Floci   │
                           └──────────────┬──────────────┘
                                          │
                           ┌──────────────▼──────────────┐
                           │ Evaluation / Governance     │
                           │ Security / Trace / Approval │
                           └──────────────┬──────────────┘
                                          │
                           ┌──────────────▼──────────────┐
                           │      Accepted Outcome       │
                           │ Quality · Cost · Reliability│
                           └─────────────────────────────┘
```

### 先分清楚六個常被混用的概念

| 名詞 | 白話定義 | 典型關注點 |
|---|---|---|
| **Framework** | 建立 Agent 互動、狀態與流程的函式庫 | Graph、State、Tool Calls |
| **Harness / Runtime** | 讓 Agent 真正工作的一整套執行環境 | Tool Loop、Filesystem、Context、Sandbox |
| **Orchestrator** | 協調不同 Agent、任務與依賴 | Dispatch、Retry、Queue、Approval |
| **Skill** | 可重複使用的工作指引與資源 | `SKILL.md`、Scripts、References |
| **MCP / Tool** | 提供 Agent 可呼叫的外部能力 | API、Browser、Desktop、Permissions |
| **Evaluation / Governance** | 驗證成果並控制風險 | Accuracy、Policy、Audit、Cost |

> [!TIP]
> **不要預設 Multi-Agent 一定更好。** 如果任務能清楚拆成固定步驟，先考慮 Deterministic Workflow；只有需要多個獨立專業判斷、平行探索或分工審查時，再考慮 Subagents / Agent Teams。

---

## 📚 Repo 全索引

**閱讀方式：** `⭐ 推薦起點` 表示編輯特別推薦先研究，**不是**官方徽章；`🧪 實驗研究` 表示建議先在隔離環境驗證。所有專案均需自行確認授權、相容性及目前維護狀態。

### 01. Agent Frameworks 與 Orchestration

| Repo | 適合研究什麼 | 何時優先考慮 |
|---|---|---|
| [LangGraph](https://github.com/langchain-ai/langgraph) ⭐ | 有狀態的 Graph、分支、循環與持續工作流程 | 企業工作流程、人工核准、復原 |
| [Deep Agents](https://github.com/langchain-ai/deepagents) ⭐ | 具有規劃、工具、Subagents 的 Agent Harness | 想快速建立完整 Agent |
| [AgentScope Java 2.0](https://github.com/agentscope-ai/agentscope-java) | 分散式 Agent、工具核准、Sandbox、Session 恢復 | Java 企業 Agent 與長時間任務；需自行驗證正式部署 |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | 軟體開發 Agent 平台與執行環境 | Coding Agent 平台、隔離執行 |
| [Paperclip](https://github.com/paperclipai/paperclip) ⭐ | AI Agent 的組織、任務、預算與批准 | 多 Agent 持續運作管理 |
| [Orkas](https://github.com/Orkas-AI/Orkas) | 桌面型專業 Agent 分工與交付 | 多角色桌面工作台 |
| [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) 🧪 | Plugin-first Agent Runtime 設計 | 研究 Harness 可擴充架構 |
| [dsh-superagent Prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) 🧪 | GitHub 事件觸發、任務授權與長時間執行 | Proactive / Event-driven Agents |
| [Claude Code Game Studios](https://github.com/Donchitos/Claude-Code-Game-Studios) | 多角色 Agent 階層與工作規則 | 學習 Agent Team 組織設計 |
| [RocketRide](https://github.com/rocketride-org/rocketride-server) | 視覺化 AI Pipeline 與可攜式工作流程 | Pipeline 設計、非工程師共同審查 |
| [Parlant](https://github.com/emcie-co/parlant) | 對話式 Agent 的業務規則與客戶互動 | 客服、對話合規、規則化回應 |

### 02. Coding Agents 與開發工作台

| Repo | 適合研究什麼 | 何時優先考慮 |
|---|---|---|
| [T3 Code](https://github.com/pingdotgg/t3code) ⭐ | 遠端管理多種 Coding Agent 工作階段 | 手機、桌面及遠端開發 |
| [Worktrunk](https://github.com/max-sixty/worktrunk) ⭐ | Git Worktree 建立、切換、整合 | 多個 Agent 平行改程式 |
| [Orca](https://github.com/stablyai/orca) | 平行 Coding Agents、結果比較與審查 | 同題多模型、多種實作比較 |
| [Beads](https://github.com/gastownhall/beads) ⭐ | 持續任務、相依關係及工作狀態 | 跨 Session、長期工程任務 |
| [ThinkRail](https://github.com/JetBrains/thinkrail) | Agentic IDE 與 Living Specifications | 規格驅動、IDE 整合 |
| [Codync](https://github.com/leepokai/Codync) | 行動裝置遠端操作及協作 Coding Agents | Chat-based Agent Teams |
| [OpenMausBot](https://github.com/milind-soni/OpenMausBot) | 聊天式本機 Agent 工作台 | 個人助理、Computer Use |
| [OpenIDEA](https://github.com/l0ng-ai/openidea) | Rust 原生 IDE 與開發工具架構 | 研究 Native Tooling 與 IDE |
| [Craft Anything](https://github.com/storytold/craft-anything) 🧪 | 研究既有軟體的可觀察行為並比較重建成果 | 具合法授權的舊系統翻新 |

### 03. Skills、Prompt Workflow 與規格驅動開發

| Repo | 適合研究什麼 | 何時優先考慮 |
|---|---|---|
| [Anthropic Skills](https://github.com/anthropics/skills) ⭐ | Agent Skills 範例、`SKILL.md` 與資源封裝 | 學習建立可重用 Skill |
| [Superpowers](https://github.com/obra/superpowers) ⭐ | 需求探索、TDD、計畫、審查流程 | 提升 Coding Agent 交付品質 |
| [OpenSpec](https://github.com/Fission-AI/OpenSpec) ⭐ | 需求變更的提案、規格、設計、任務與歸檔 | 既有專案需求治理、跨 Session 交付 |
| [gstack](https://github.com/garrytan/gstack) ⭐ | 產品探索、架構、Code Review、QA、Release 的 Skills | Coding Agent 端到端交付；Codex 支援仍標示實驗性 |
| [GitHub Spec Kit](https://github.com/github/spec-kit) | 可組合的規格驅動開發、Bug Fix 與評估流程 | 團隊標準化開發流程及品質關卡 |
| [Everything Claude Code / ECC](https://github.com/affaan-m/ECC) ⭐ | Agents、Skills、Hooks、Rules 組合 | 研究 Harness Configuration |
| [Matt Pocock Skills](https://github.com/mattpocock/skills) | 需求訪談、規格、Ticket、實作與 Review | 工程化 Skill Workflow |
| [Google Elephant Goldfish Model](https://github.com/google/elephant-goldfish-model) | 完整上下文設計、獨立上下文審查 | 規格品質與交叉驗證 |
| [Vercel Skills CLI](https://github.com/vercel-labs/skills) ⭐ | Skills 搜尋、安裝、更新與管理 | 統一 Skills 管理流程 |
| [jakubkrehel/skills](https://github.com/jakubkrehel/skills) | UI Accessibility、Layout、State Testing | 前端品質與邊界測試 |
| [Unslop](https://github.com/heydamir/unslop) | 既有 UI 的設計檢查與改善 | AI 產生介面的視覺精修 |
| [Taste Skill](https://github.com/Leonxlnx/taste-skill) | Art Direction 與前端視覺品質流程 | 介面設計方向與 Browser QA |
| [Claude SEO](https://github.com/AgriciDaniel/claude-seo) | SEO/GEO 與內容檢查 Skills | 搜尋行銷內容工作流 |

### 04. Browser Automation 與 Computer Use

| Repo | 適合研究什麼 | 何時優先考慮 |
|---|---|---|
| [agent-browser](https://github.com/vercel-labs/agent-browser) ⭐ | 結構化頁面 Snapshot 與操作 CLI | Browser Agent 開發 |
| [Lightpanda](https://github.com/lightpanda-io/browser) ⭐ | 輕量化 Browser Engine 與自動化 | 瀏覽器執行效能研究 |
| [Agent Desktop](https://github.com/vercel-labs/agent-desktop) ⭐ | Accessibility API 與桌面操作 | 無 API 的桌面工作流 |
| [Scrapling](https://github.com/D4Vinci/Scrapling) ⭐ | Python 爬取、解析、資料取得 | 公開網頁資料蒐集 |
| [Agent Reach](https://github.com/Panniantong/Agent-Reach) | 跨平台內容讀取工具 | Research Agent 的資料來源層 |
| [Mika](https://github.com/wangzan101/Mika) 🧪 | Android App 控制與行動 Agent | 行動裝置工作自動化 |
| [AI Goofish Monitor](https://github.com/Usagi-org/ai-goofish-monitor) | 定期蒐集、AI 分析與通知系統 | 研究監控產品架構 |

> [!CAUTION]
> 網頁讀取與自動化工具**不代表**可以任意存取受保護內容。請遵守目標服務的使用條款、授權、隱私規定與合理速率限制，並避免繞過存取控制。

### 05. Memory、Context Engineering 與 RAG

| Repo | 適合研究什麼 | 何時優先考慮 |
|---|---|---|
| [Claude-Mem](https://github.com/thedotmack/claude-mem) ⭐ | Session 工作紀錄、持續記憶與檢索 | Coding Agent 重複工作太多 |
| [Hindsight](https://github.com/vectorize-io/hindsight) ⭐ | 長期記憶、回想與反思 | 跨任務經驗累積 |
| [Context Mode](https://github.com/mksglu/context-mode) ⭐ | 工具輸出裁切、索引與 Context 控制 | 大量工具輸出消耗 Tokens |
| [XERJ](https://github.com/xerj-org/xerj) | 本機搜尋、程式碼/文件索引、MCP | Repo 與文件檢索 |
| [WeKnora](https://github.com/Tencent/WeKnora) | 知識庫問答與 RAG 應用 | 企業文件知識服務 |
| [OpenViking](https://github.com/volcengine/OpenViking) | Agent Context / Memory 組織 | 分層上下文管理研究 |
| [Code-Graph-RAG](https://github.com/vitali87/code-graph-rag) | 程式碼知識圖譜與 RAG | 跨檔案程式結構理解 |

### 06. Evaluation、Security 與 Governance

| Repo | 適合研究什麼 | 何時優先考慮 |
|---|---|---|
| [Cloudflare Security Audit Skill](https://github.com/cloudflare/security-audit-skill) ⭐ | 安全審查、候選漏洞驗證、證據整理 | Coding Agent Code Security |
| [iFixAi](https://github.com/ifixai-ai/iFixAi) ⭐ | Agent 行為、越權、政策及對抗測試 | Agent 上線前驗收 |
| [Agent Lightning](https://github.com/microsoft/agent-lightning) ⭐ | Agent Rollout 蒐集與強化學習 | 進階 Agent Training / Evaluation |
| [Microsoft TokenEconomizer](https://github.com/microsoft/TokenEconomizer) ⭐ | Micro-skills、Tool Pruning、Failure-loop Intervention | Coding Agent 成本 A/B Test；作者成效須自行重現 |
| [NVIDIA Auto-Ontology](https://github.com/NVIDIA/auto-ontology) ⭐ | 商業語意層與 Text-to-SQL 評估 | 企業資料問答可信度 |
| [Nasiko](https://github.com/Nasiko-Labs/nasiko) 🧪 | Agent 身分、模型路由、成本與工具管控 | Agent Control Plane |
| [AiSOC](https://github.com/beenuar/AiSOC) 🧪 | AI 輔助安全事件調查與審查 | Security Operations |

### 07. Enterprise Integration、Data 與 Infrastructure

| Repo | 適合研究什麼 | 何時優先考慮 |
|---|---|---|
| [Spotify Portal AI Plugins](https://github.com/spotify/portal-ai-plugins) ⭐ | 內部服務目錄、受控操作、開發者平台整合 | Enterprise Tool Gateway |
| [NetBird](https://github.com/netbirdio/netbird) | Zero Trust 網路與安全存取 | Agent 連接內部服務 |
| [Floci](https://github.com/floci-io/floci) ⭐ | 本機 AWS 服務模擬 | Cloud Agent PoC 整合測試 |
| [FreeToken](https://github.com/FlashML-org/FreeToken) | MoE 模型推論、CPU/GPU 協同執行 | 私有 LLM 推論研究 |
| [colibri](https://github.com/JustVugg/colibri) | 大型 MoE 模型的分層記憶體推論 | 受限硬體的模型服務 |
| [World Monitor](https://github.com/koala73/worldmonitor) | 多來源情報儀表板與 AI 分析 | Enterprise Intelligence |

### 08. AI 商業應用與多模態產品

| Repo | 適合研究什麼 | 何時優先考慮 |
|---|---|---|
| [Postiz](https://github.com/gitroomhq/postiz-app) ⭐ | 社群內容排程、管理與分析 | Content Operations |
| [last30days-skill](https://github.com/mvanhorn/last30days-skill) ⭐ | 近期話題研究與跨來源觀察 | Trend Discovery |
| [Horizon](https://github.com/Thysrael/Horizon) | 多來源情報蒐集、評分、去重、雙語摘要及定期發布 | 技術情報雷達與研究自動化；注意資料時效 |
| [HyperFrames](https://github.com/heygen-com/hyperframes) ⭐ | HTML/CSS 程式化影片生成 | 教學、品牌與資料動畫 |
| [OpenMontage](https://github.com/calesthio/OpenMontage) | AI 影片製作 Pipeline | 多階段影片產製 |
| [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar) | 可重用影片風格與 Creative Skills | Agentic Filmmaking |
| [SolidCraft](https://github.com/tangency-labs/solidcraft) ⭐ | 參數化 CAD 與 MCP | 製造業工程軟體 Agent |
| [Archify](https://github.com/tt-a1i/archify) ⭐ | 系統架構圖、規格與程式碼證據 | 架構提案與審查 |
| [Doop](https://github.com/kgoedecke/doop) | 人類與 Agent 共用設計 Canvas | UI 設計交付與核准 |
| [Hex](https://github.com/anomalyco/hex) | 本機優先語音輸入與轉錄 | Voice-first Agent 介面 |

### 09. 學習資源與研究

| Repo / 資源 | 核心內容 | 推薦對象 |
|---|---|---|
| [AI Engineering from Scratch](https://github.com/rohitg00/ai-engineering-from-scratch) ⭐ | AI / RAG / Agent / Security / Evaluation 分階段學習 | 系統化補強基礎 |
| [AI Engineering Hub](https://github.com/patchy631/ai-engineering-hub) ⭐ | Agentic RAG、MCP、多模態範例專案 | 喜歡從程式學習的人 |
| [Agent Skills 規格](https://agentskills.io/) | Skills 格式與可攜性 | Skill 作者 |
| [MCP 官方文件](https://modelcontextprotocol.io/) | Tool / Context 協定與架構 | MCP Tool 開發者 |
| [SWE-bench](https://www.swebench.com/) | 真實程式修復任務的評估方向 | Coding Agent 評估者 |
| [LangGraph 官方文件](https://docs.langchain.com/oss/python/langgraph/overview) | Graph、Persistence、Human-in-the-loop | Python Agent 工程師 |

---

## ⚔️ 常見選型對決

| 比較 | A 擅長 | B 擅長 | 建議怎麼選 |
|---|---|---|---|
| **Deep Agents vs LangGraph** | 快速建立可用 Harness | 精細設計狀態及流程 | 流程固定且具核准節點，優先 LangGraph |
| **Superpowers vs ECC** | 一套一致的開發方法 | 大量可選 Skills / Hooks | 先用 Superpowers 建基準，再挑選 ECC 元件 |
| **OpenSpec vs Spec Kit** | 輕量化變更規格、既有專案 | 可擴充的開發流程與品質關卡 | 需求變更治理先試 OpenSpec；流程標準化先試 Spec Kit |
| **Worktrunk vs Orca** | CLI 與 Worktree 管理 | 多 Agent 操作 UI | 重 CLI 選 Worktrunk；重可視化選 Orca |
| **Claude-Mem vs Beads** | 保留歷史與發現 | 管理任務與依賴 | 兩者互補，不是直接替代 |
| **Hindsight vs Context Mode** | 長期記憶、反思 | 減少當次 Context 汙染 | 依「跨 Session」或「當次資料量」區分 |
| **Scrapling vs agent-browser** | 資料擷取與解析 | 頁面操作及互動 | 批次擷取先評估 Scrapling；工作流操作先評估 agent-browser |
| **Agent Desktop vs agent-browser** | 原生桌面軟體 | 網頁介面 | 取決於目標應用是 OS UI 還是 Browser |
| **Lightpanda vs Chromium** | 輕量瀏覽器與效率研究 | 廣泛網站相容性 | 先用相同網站集合做相容性及成本基準測試 |
| **Paperclip vs Orkas** | 任務、組織、成本治理 | 專業 Agent 的桌面工作體驗 | 多人持續營運重治理；個人探索重工作台 |
| **Auto-Ontology vs 一般 Text-to-SQL** | 商業定義與語意層 | 直接由 Schema 產生查詢 | 指標定義複雜的企業應先建語意層 |

---

## 🛠️ 從收藏到實作：五個 Project Blueprints

> 每個題目都設計為**可驗收的 PoC**。以下為建議整合，不代表所列專案已提供現成的一鍵串接。

### Project A｜WorkshopFlow：企業內訓報名與候補 App

**工具組合：** LangGraph / Deep Agents + Superpowers + Worktrunk + Pytest

**需求：** HR 建課、員工報名、滿額候補、取消自動遞補、不得重複報名、同時搶最後一席不得超收。

**設計重點：** 把名額一致性寫成資料庫 Transaction / Constraint，不靠 Agent Prompt 保證；Agent 只負責設計、實作與測試。

**驗收：** 併發測試下不超收、候補順序正確、重複報名被拒絕、所有功能測試通過。

### Project B｜Enterprise Research Agent：企業技術情報系統

**工具組合：** Scrapling + Agent Reach + LangGraph + Hindsight

**流程：** Source Discovery → Authorized Collection → Timestamped Snapshot → Deduplication → Analysis → Evidence Review。

**驗收：** 每個結論可追溯來源 URL、擷取時間、原始快照；區分**觀測事實**與**推論**；不能把當前互動量誤當增長率。

### Project C｜Agent Governance Lab：AI Agent 上線前驗收

**工具組合：** iFixAi + Cloudflare Security Audit Skill + 自製 Policy Tests

**流程：** 定義角色及規則 → 正常/惡意測試案例 → 執行 Agent → 獨立驗證 → 人工核准。

**驗收：** 未授權操作為零、重要違規場景可被偵測、安全發現具可重現證據；紀錄每個 Case 的模型成本與人工修正時間。

### Project D｜Legacy ERP Computer Use：無 API 內部系統自動化

**工具組合：** Agent Desktop + agent-browser + Human Approval

**流程：** Observe UI → Resolve Element → Execute Restricted Action → Verify Outcome → Audit Log。

**驗收：** 30 個模擬任務的完成率、錯誤操作率、介面變動後恢復率；不得操作真實付款或其他高風險功能。

### Project E｜Research-to-Video：技術研究自動生成解說影片

**工具組合：** Research Agent + HyperFrames + FFmpeg / FFprobe

**流程：** Source Verification → Script → Storyboard → Visual Assets → Render → Fact & Media QA。

**驗收：** 影片長度、字幕正確率、來源引用、渲染成功率、素材授權與每支合格影片成本。

---

## 🗓️ 30 天學習路線

| 週次 | 學習主題 | 推薦 Repo | 本週可交付成果 |
|---|---|---|---|
| **Week 1** | Agent 基礎、Tool Calls、狀態機 | LangGraph、Deep Agents | 具工具呼叫與可重試的單一 Agent |
| **Week 2** | Coding Agents、Skills、TDD | Superpowers、Anthropic Skills、Worktrunk | 以規格與測試完成 5 個工程任務 |
| **Week 3** | Browser、RAG、Memory | agent-browser、Scrapling、Hindsight | 可追溯資料來源的 Research Agent |
| **Week 4** | Evaluation、Security、Governance | iFixAi、Cloudflare Skill、Auto-Ontology | 具有 Evaluation Report 的企業 PoC |

### 下一步：挑戰進階主題

- **Agent Teams / Dynamic Workflows：** Paperclip、Orkas、LangGraph。
- **Computer Use：** Agent Desktop、Mika、Lightpanda。
- **Enterprise Data Agent：** NVIDIA Auto-Ontology、WeKnora。
- **Agent Training：** Microsoft Agent Lightning。
- **On-premise Inference：** FreeToken、colibri。

---

## 📏 企業級 Agent 驗收框架

別只報告「Agent 成功執行了」。真正的交付應量測以下指標：

| 構面 | 指標 | 衡量方法 |
|---|---|---|
| **功能** | Task Success Rate | 通過獨立驗收案例數 / 總案例數 |
| **品質** | Specification Compliance | 人工與自動化測試檢查需求覆蓋 |
| **可靠性** | Recovery Success Rate | 中斷或重試後正確恢復的比例 |
| **安全** | Unauthorized Action Rate | 不符合授權的實際操作 / 所有敏感操作 |
| **可追溯性** | Evidence Coverage | 有來源、Trace 或操作證據的結果比例 |
| **效率** | End-to-end Latency | 從輸入到合格結果的實際耗時 |
| **成本** | Cost per Accepted Task |（模型 + 工具 + Infra + 人工審核成本）/ 合格任務數 |
| **商業價值** | ROI |（可歸因效益 − 導入與營運成本）/ 導入與營運成本 |

**最低實驗紀律：** 使用相同模型、相同題目、相同資料、相同驗收集；重複多次；記錄失敗案例；區分「作者自述」、「自己重現」、「外部獨立測試」。

### 不可忽略的四條企業安全原則

1. **Prompt 不是授權系統**：資料庫、API 和工具端必須實施真正的 Permission Check。
2. **Sandbox 不是可選項**：不信任的程式與外部內容應在受限環境執行。
3. **Human-in-the-loop 應放在高風險 Action 前**：例如付款、刪除、對外發信、修改生產設定。
4. **記憶、Trace、Logs 也是敏感資料**：必須規範收集、遮罩、保留期限和刪除方式。

---

## 📊 SWOT：這份資源庫的價值與限制

| | 分析 |
|---|---|
| **Strengths 優勢** | 台灣繁體中文、實務導向、按問題選型、強調驗收與企業治理，而非只堆積連結。 |
| **Weaknesses 弱點** | Repo 變動快速；部分小型專案成熟度不足；跨專案整合不等於官方支援。 |
| **Opportunities 機會** | 可發展成台灣 AI Agent 工程師的共同知識庫、Benchmark、架構模板與社群共同評測。 |
| **Threats 威脅** | Star 數灌水或短期熱度、維護中止、授權變化、安全漏洞、過度宣傳的效能或產品能力。 |

**編輯策略：** 更重視「解決真實問題、可重現、可驗證、持續維護」，而不是單純追求熱門數量。

---

## 🔎 收錄標準與資料可信度

### 收錄條件

- 有可查詢的**官方 Repository** 或具體官方文件。
- 能清楚描述一項工程用途，而不是只提供宣傳口號。
- 能辨識適用場景、主要限制，以及至少一個可驗收的實作方向。
- 必須區分 Framework、應用產品、Skill、CLI、Infrastructure、Benchmark。
- 不收錄明顯侵犯隱私、未經授權的存取流程或惡意用途。

### 資料可信度標記（建議未來每次 PR 附上）

| 標記 | 意義 |
|---|---|
| `official-docs` | 功能來自專案官方 README / Documentation |
| `reproduced` | 已在記錄的環境實測成功 |
| `independent-eval` | 有第三方可檢查的評估 |
| `experimental` | 原型、Beta、或尚未完成正式環境驗證 |
| `needs-review` | 授權、維護、功能或連結有待重新核查 |

> **Stars 僅能作為探索訊號，不應作為唯一推薦依據。** 本清單刻意不凍結 Star 排名與效能數值。若未來新增 Trending 自動更新，請保留**觀測時間、統計視窗、資料來源**，區分每日／每週增加量與累積 Stars。

### 維護建議

- **每日**：搜集候選 Trending，不自動把所有熱門項目加入精選。
- **每週**：人工確認候選 Repo 是否有實際工程價值，去重並更新分類。
- **每月**：檢查連結、授權、Release、最近維護、已知安全風險。
- **每季**：重新執行 Benchmark，移除過期或不再推薦的項目。

---

## 🤝 貢獻指南

歡迎提交 PR 補充真正值得學習的 AI Agent Repository。

### 新增 Repo 的 PR 範本

```md
### Repository Name
- GitHub: https://github.com/owner/repository
- Category: Agent Framework / Skills / Browser / Memory / Evaluation / ...
- One-liner: 一句話說明它解決什麼問題
- Best for: 真正適合的使用場景
- Not for: 不適合的使用情境
- Evidence: 官方文件、範例、Benchmark 連結
- Limitations: 已知限制、資安或授權注意事項
- Verified on: YYYY-MM-DD
- Test idea: 一個可以客觀驗收的 PoC
```

### PR 審核規則

1. **先搜尋是否重複**，同一 Repository 只收錄一次，必要時跨分類引用。
2. **附官方連結**，避免使用不明第三方介紹作為唯一證據。
3. **不可捏造 Star 數、效能或正式部署案例**。
4. **不要把提案架構描述成官方現有整合**。
5. **避免無依據的「最強」、「100% 準確」、「全面取代」等說法**。
6. **重大安全疑慮需明確標註**，不以「開源」作為安全保證。

### 可以協助的方向

- 新 Repo 推薦與連結校對
- Python / LangGraph 實作範例
- Agent Evaluations 與 Benchmark 重現
- 企業導入案例（附公開、可查證來源）
- 將單一大 README 拆成分類子頁面
- 英文版本與繁體中文術語校對

---

## 📖 核心參考資料

以下提供概念、協定、原始實作與評估的官方入門連結：

- [GitHub Trending](https://github.com/trending) — GitHub 趨勢探索入口。
- [Anthropic Agent Skills](https://github.com/anthropics/skills) — Skills 範例與封裝方式。
- [Agent Skills Specification](https://agentskills.io/) — Skills 規格。
- [Model Context Protocol](https://modelcontextprotocol.io/) — MCP 官方文件。
- [LangGraph Documentation](https://docs.langchain.com/oss/python/langgraph/overview) — Agent 工作流程與狀態管理。
- [Microsoft Agent Lightning](https://github.com/microsoft/agent-lightning) — Agent Training 與評估研究。
- [SWE-bench](https://www.swebench.com/) — 真實軟體工程任務評估。

---

<div align="center">

### ⭐ Stop collecting Agents. Start engineering outcomes.

**真正優秀的 AI Agent 系統，不只會完成任務，還必須能被驗證、追蹤、控制與持續改善。**

如果這份指南對你有幫助，可以在自己的 GitHub Repository 按下 **Star**，並透過 PR 分享可重現的實作經驗。

**Made for builders who care about quality, reliability, and real-world impact.**

</div>