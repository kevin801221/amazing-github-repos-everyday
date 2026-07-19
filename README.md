<div align="center">

# 🔥 Amazing GitHub Repos Everyday

### 每天 5 分鐘，追蹤正在爆紅的 AI / LLM / Agent 開源專案

[![Daily Update](https://img.shields.io/badge/更新頻率-每日-brightgreen?style=for-the-badge)](./ai-repos-2026-07-18.md)
[![Focus](https://img.shields.io/badge/聚焦-AI%20%2F%20LLM%20%2F%20Agent-blue?style=for-the-badge)](https://github.com/topics/ai)
[![Latest](https://img.shields.io/badge/最新報告-2026--07--18-orange?style=for-the-badge)](./ai-repos-2026-07-18.md)

**跨日去重整理：同一個 GitHub repo 只在主索引保留一次，完整日報仍保留原始排序。**

[⭐ 推薦研究](#-推薦研究) · [📌 去重總索引](#-去重總索引) · [📅 歷史報告](#-歷史報告) · [🧭 趨勢雷達](#-趨勢雷達) · [🎯 整理規則](#-整理規則)

</div>

---

## ⭐ 推薦研究

> 以下依可落地性、技術延展性與學習價值排序；不是依 star 數量排名。

| 優先度 | Repo | 適合研究的情境 | 推薦原因 |
|:---:|:---|:---|:---|
| 1 | [modiqo/skillspec](https://github.com/modiqo/skillspec) | 想把 Agent skills 導入團隊或產品 | 它把 skills 從提示詞集合提升為可規格化、可測試、可驗證的工程資產，直接處理可維護性與風險診斷。 |
| 2 | [Sahir619/fable-method](https://github.com/Sahir619/fable-method) | 想建立可重複使用的 Agent 工作流程 | 將 think／act 流程與評測綁在一起，重點是讓流程能跨模型複用並持續驗證，而不只是追逐單一模型。 |
| 3 | [deer-flow/llm-space](https://github.com/deer-flow/llm-space) | 正在開發或除錯 Agent | 能檢視 harness 的執行步驟、重播失敗案例與評估效能；這正是 Agent 從 demo 走向可靠系統時最需要的能力。 |
| 4 | [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) | 想研究 coding agent 的長期記憶 | 把 codebase 索引為可持久查詢的知識，適合拆解 MCP、程式碼檢索與 context 管理的架構取捨。 |
| 5 | [elder-plinius/T3MP3ST](https://github.com/elder-plinius/T3MP3ST) | 想建立 Agent 安全測試能力 | 多代理紅隊演練提供具體的攻擊面與測試流程，可用來設計自己的安全評估；應只在隔離、授權環境研究。 |
| 6 | [HUANGCHIHHUNGLeo/claude-real-video](https://github.com/HUANGCHIHHUNGLeo/claude-real-video) | 想做多模態產品或影片理解 | 將場景切分、去重影格與逐字稿結合，提供比單純丟影片給模型更可控的本地分析管線。 |
| 7 | [William-Lu-stack/Flawless](https://github.com/William-Lu-stack/Flawless) | 維運 Kubernetes 或雲端平台 | 把 AI Agent 用在 SRE／AgenticOps；若你的工作重心是基礎設施，這個項目的優先度可提升到前 3。 |

### 一般情況的股市研究首選

| 推薦 | Repo | 為什麼適合一般情況 | 使用前要知道 |
|:---:|:---|:---|:---|
| **首選** | [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) | 支援台股、A 股、港股、美股、日股、韓股與 ETF；整合多市場資料、新聞、報告與自動推送，並提供 GitHub Actions 的低門檻定時部署，適合先建立自己的自選股研究與每日復盤流程。 | 需要設定 LLM 與資料來源；免費資料源可能受限流或波動影響。所有分析、評分與回測都只適合輔助研究，不構成買賣建議，仍需自行驗證資料與風險。 |

> 若只研究 A 股、且需要更深入的選股、監控與回測，再看 [shy3130/tickflow-stock-panel](https://github.com/shy3130/tickflow-stock-panel)；它更偏量化工作台，設定與使用門檻也較高。

---

## 📌 去重總索引

> 更新至：**2026-07-18** · 已整合 **13 份報告** · 共 **34 個不重複 repo**<br>
> 星數採各 repo 在報告中最後一次出現的觀測值；「首次收錄」代表第一次進入本專案日報的日期。

| 首次收錄 | 最後觀測 | Repo | ⭐ 最新觀測 | 一句話看懂 |
|:---|:---|:---|---:|:---|
| 2026-07-18 | 2026-07-18 | [HUANGCHIHHUNGLeo/claude-real-video](https://github.com/HUANGCHIHHUNGLeo/claude-real-video) | 1,712 | 讓 Claude 或其他 LLM 以場景感知、去重影格與逐字稿理解影片的本地工具。 |
| 2026-07-18 | 2026-07-18 | [deer-flow/llm-space](https://github.com/deer-flow/llm-space) | 986 | 桌面 agent 原型工具，可檢視 harness 步驟、重播失敗案例並評估效能。 |
| 2026-07-17 | 2026-07-17 | [William-Lu-stack/Flawless](https://github.com/William-Lu-stack/Flawless) | 691 | 面向 Kubernetes 與雲端基礎設施的 AI SRE（AgenticOps）自動化工具。 |
| 2026-07-15 | 2026-07-18 | [AlephAITech/WorkBuddyGuide](https://github.com/AlephAITech/WorkBuddyGuide) | 1,048 | WorkBuddy 的開源實戰指南，彙整工作流、Skills、MCP、自動化與多代理範例。 |
| 2026-07-15 | 2026-07-18 | [Sahir619/fable-method](https://github.com/Sahir619/fable-method) | 1,643 | 將 Claude Fable 5 工作方法整理成可供不同模型使用的 think／act 技能集與評測。 |
| 2026-07-14 | 2026-07-17 | [SmileLikeYe/agent-chief](https://github.com/SmileLikeYe/agent-chief) | 780 | local-first 的注意力守門層，將 agent、警報與資訊流整合成單一可信介面。 |
| 2026-07-11 | 2026-07-11 | [modiqo/cliare](https://github.com/modiqo/cliare) | 712 | CLI「代理就緒度」量測工具，評估命令列工具對 AI agent 的友善程度。 |
| 2026-07-10 | 2026-07-16 | [uzairansaruzi/hermex](https://github.com/uzairansaruzi/hermex) | 779 | Hermes agent 的原生 iPhone App，讓個人 AI 代理可在行動裝置使用。 |
| 2026-07-10 | 2026-07-18 | [simonlin1212/Vibe-Research](https://github.com/simonlin1212/Vibe-Research) | 880 | 個人投資研究 Agent，涵蓋 A 股／美股／港股的復盤、資訊雷達與持倉研究。 |
| 2026-07-09 | 2026-07-09 | [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) | 53,263 | 讓 AI 代理透過 CLI 搜尋並讀取 Twitter、Reddit、YouTube、GitHub 等平台內容。 |
| 2026-07-09 | 2026-07-09 | [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | 35,672 | 開源的 agentic 影片製作系統，把 AI 編碼助手變成多工具製片工作室。 |
| 2026-07-09 | 2026-07-09 | [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) | 55,908 | LLM 驅動的多市場股票分析系統，整合行情、新聞、看板與自動推播。 |
| 2026-07-09 | 2026-07-09 | [JCodesMore/ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template) | 26,823 | 搭配 AI 編碼代理快速複製網站，產出可用的專案骨架。 |
| 2026-07-09 | 2026-07-09 | [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) | 28,627 | 高效能程式碼理解 MCP，將 codebase 建成持久化知識圖譜。 |
| 2026-07-09 | 2026-07-09 | [phuryn/pm-skills](https://github.com/phuryn/pm-skills) | 23,063 | 產品經理用的 agent 技能、指令與外掛市集，覆蓋策略到成長流程。 |
| 2026-07-09 | 2026-07-09 | [stablyai/orca](https://github.com/stablyai/orca) | 14,241 | 專為同時操控多個並行代理而生的 ADE。 |
| 2026-07-09 | 2026-07-09 | [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) | 12,506 | NVIDIA 開源的 AI agent skills 安全掃描器，偵測漏洞與惡意樣態。 |
| 2026-07-09 | 2026-07-09 | [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | 13,792 | 免費 AI gateway，以單一端點串接多家模型供應商並節省 token。 |
| 2026-07-08 | 2026-07-18 | [synthetic-sciences/openscience](https://github.com/synthetic-sciences/openscience) | 2,546 | 面向科學研究的 AI workbench，加速實驗設計、資料分析與研究流程。 |
| 2026-07-08 | 2026-07-11 | [eli-labz/Third-Eye](https://github.com/eli-labz/Third-Eye) | 934 | 生產級 OSINT 平台，提供多情報領域的即時態勢感知。 |
| 2026-07-08 | 2026-07-18 | [modiqo/skillspec](https://github.com/modiqo/skillspec) | 979 | 讓 agent 技能可依循、可測試、可驗證的規格與診斷工具。 |
| 2026-07-06 | 2026-07-18 | [elder-plinius/T3MP3ST](https://github.com/elder-plinius/T3MP3ST) | 4,897 | 多代理紅隊演練平台，用於自動化滲透與攻擊性資安測試。 |
| 2026-07-06 | 2026-07-06 | [alchaincyf/fanbox](https://github.com/alchaincyf/fanbox) | 887 | 「vibe coding」駕駛艙，集中檔案、終端機與每次改動檢視。 |
| 2026-07-05 | 2026-07-18 | [jmerelnyc/Talos](https://github.com/jmerelnyc/Talos) | 990 | Talos 網路 GPU 工作節點客戶端，承接推論任務並回報運行時間。 |
| 2026-07-05 | 2026-07-18 | [sums001/Windows-Copilot-API](https://github.com/sums001/Windows-Copilot-API) | 1,133 | 將 Windows Copilot 逆向封裝成 OpenAI-compatible API；使用前需留意合規。 |
| 2026-07-03 | 2026-07-11 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 80,355 | 用 YAGNI 約束 AI coding agent，主張少寫程式碼、避免過度工程。 |
| 2026-07-03 | 2026-07-08 | [XiaomiMiMo/MiMo-Code](https://github.com/XiaomiMiMo/MiMo-Code) | 11,590 | 小米開源的程式碼代理專案，主打模型與 agent 共同演化。 |
| 2026-07-03 | 2026-07-10 | [omnigent-ai/omnigent](https://github.com/omnigent-ai/omnigent) | 6,930 | 統一調度 Claude Code、Codex、Cursor 等多種代理的 meta-harness。 |
| 2026-07-03 | 2026-07-06 | [cobusgreyling/loop-engineering](https://github.com/cobusgreyling/loop-engineering) | 5,943 | loop engineering 模式、範本與 CLI，設計能持續提示 AI agent 的系統。 |
| 2026-07-03 | 2026-07-17 | [shy3130/tickflow-stock-panel](https://github.com/shy3130/tickflow-stock-panel) | 2,220 | LLM 驅動的 A 股選股、監控與回測量化工作台。 |
| 2026-07-03 | 2026-07-10 | [TestSprite/testsprite-cli](https://github.com/TestSprite/testsprite-cli) | 2,272 | 在終端機執行 AI 驅動自動化測試的 TestSprite 官方 CLI。 |
| 2026-07-03 | 2026-07-13 | [benchflow-ai/awesome-evals](https://github.com/benchflow-ai/awesome-evals) | 708 | 建構與評測 AI agent 的精選論文、工具、演講與 benchmark 清單。 |
| 2026-07-03 | 2026-07-14 | [raiyanyahya/recall](https://github.com/raiyanyahya/recall) | 708 | Claude Code 持久記憶工具，local-first 並用摘要節省 token。 |
| 2026-07-03 | 2026-07-06 | [tigicion/dao-code](https://github.com/tigicion/dao-code) | 1,604 | DeepSeek-V4 取向的終端機 coding agent，支援 1M context、MCP 與 Hooks。 |

---

## 📅 歷史報告

| 日期 | 原始收錄數 | 去重新增 | 完整報告 |
|:---|---:|---:|:---|
| **2026-07-18** | 10 | 2 | [查看 →](./ai-repos-2026-07-18.md) |
| 2026-07-17 | 10 | 1 | [查看 →](./ai-repos-2026-07-17.md) |
| 2026-07-16 | 10 | 0 | [查看 →](./ai-repos-2026-07-16.md) |
| 2026-07-15 | 10 | 2 | [查看 →](./ai-repos-2026-07-15.md) |
| 2026-07-14 | 10 | 1 | [查看 →](./ai-repos-2026-07-14.md) |
| 2026-07-13 | 10 | 0 | [查看 →](./ai-repos-2026-07-13.md) |
| 2026-07-11 | 10 | 1 | [查看 →](./ai-repos-2026-07-11.md) |
| 2026-07-10 | 10 | 2 | [查看 →](./ai-repos-2026-07-10.md) |
| **2026-07-09** | 9 | 9 | [查看 →](./ai-repos-2026-07-09.md) |
| 2026-07-08 | 8 | 3 | [查看 →](./ai-repos-2026-07-08.md) |
| 2026-07-06 | 9 | 2 | [查看 →](./ai-repos-2026-07-06.md) |
| 2026-07-05 | 9 | 2 | [查看 →](./ai-repos-2026-07-05.md) |
| 2026-07-03 | 9 | 9 | [查看 →](./ai-repos-2026-07-03.md) |

---

## 🧭 趨勢雷達

| 趨勢 | 觀察 |
|:---|:---|
| **Agentic 內容製作** | 影片生成、網站複製、研究工作台開始把「多工具代理流程」產品化。 |
| **程式碼記憶與 MCP** | codebase 索引、持久記憶、技能規格正在成為 AI coding agent 的基礎設施。 |
| **Agent skills 安全** | 技能市集與技能掃描同時升溫，代表 agent 擴充能力開始需要安全邊界。 |
| **AI 資安與 OSINT** | 紅隊演練、自動化情報分析與社群資料讀取工具快速增加。 |
| **多代理編排** | meta-harness、ADE、gateway 持續出現，開發者想在同一層抽換與協調不同代理。 |
| **Agent 可用性延伸** | 原生行動端代理與 CLI agent-ready 評測工具出現，焦點從代理能力延伸到跨裝置使用與工具相容性。 |
| **Agent 工作流資產化** | 實戰指南與可攜式技能集把工作流程、Skills、MCP 與評測包裝成可複用的開源資產。 |
| **多模態與 Agent 可觀測性** | 本地影片理解與 agent 執行重播工具開始出現，讓多模態輸入與失敗分析更容易進入日常開發流程。 |

---

## 🎯 整理規則

```text
去重鍵     → GitHub owner/repo URL
主索引     → 同一 repo 只保留一次，使用最後一次觀測到的星數與描述
日期欄位   → 首次收錄 = 第一次進入日報；最後觀測 = 最近一次出現在日報
歷史報告   → 保留原始每日排序與當日資料，方便回看當天榜單脈絡
```

**資料口徑提醒**

- 2026-07-03、2026-07-05、2026-07-06、2026-07-08、2026-07-10、2026-07-11、2026-07-13 至 2026-07-18 報告主要鎖定近 30 天內建立的 AI / LLM / Agent 專案。
- 2026-07-09 報告改以 GitHub Trending monthly 與專案頁觀測「本月爆紅」專案，因此部分專案建立時間早於 30 天窗口。
- 星數、建立日期與描述皆以各日報中的觀測資料為準，GitHub 即時數值可能已不同。

---

<div align="center">

## ⭐ 覺得有用？Star 一下，明天繼續追

**每天更新 · 零廣告 · 只推真正有動能的 repo**

[![Star this repo](https://img.shields.io/github/stars/kevinluo/amazing-github-repos-everyday?style=social&label=Star)](https://github.com/kevinluo/amazing-github-repos-everyday)

</div>
