<h1 align="center">Lin Junrong · 林均融</h1>

<p align="center">
  Building AI infrastructure at <a href="https://www.agora.io">Agora</a> · Full-stack partner at <a href="https://dimension-studio.vercel.app">Dimension Studio</a><br>
  <sub>聲網 Agora AI 基礎建設 · 次元創意全端合夥人 · 台灣</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-AI%20Infra%20%C2%B7%20Full--stack-1f2937?style=flat-square" alt="Focus">
  <img src="https://img.shields.io/badge/Stack-Next.js%20%C2%B7%20Python%20%C2%B7%20K8s-1f2937?style=flat-square" alt="Stack">
  <img src="https://img.shields.io/badge/Based%20in-Taiwan-1f2937?style=flat-square" alt="Taiwan">
</p>

---

### About · 關於我

我是林均融，來自台灣，國立中興大學資訊管理學系。

我做的事很單純：**把中小企業跑在 Excel、LINE 群組和紙本上的流程，變成真正能用的系統。** 通常一個人從頭做到尾 —— 談需求、寫規格、設計資料庫、寫後端、刻前端、部署上線，然後承擔最沒人想碰的那一段：上線之後把它維持活著。

過去兩年我交付了 6 套正在運作的系統。有給食品品牌做的多租戶投稿編審平台，超過 100 位投稿者在上面走完整條編輯流程；有給 B2B 經銷商做的名單開發 SaaS，每週自動爬四個招募平台、去重、寄開發信；也有給連鎖運動場館做的 43 條路由營運系統，會員、排課、四種金流、電子發票、稽核日誌全包。這些案子讓我學到一件事：**寫出功能只是開始，真正難的是上線之後六個月它還沒壞。** 所以我會把備份、監控、還原腳本、資料庫的 row-level security 當成交付的一部分，而不是「之後再說」。

2026 年 7 月我加入**聲網 Agora**，在 [TEN Framework](https://github.com/TEN-framework/ten-framework) 團隊做 AI 基礎建設 —— Kubernetes、GPU 可觀測性、即時對話式 AI 的串流延遲。從「一個人扛完整條產品線」換到「大規模基礎建設的一個環節」，是完全不同的思考尺度，我還在學。

我相信工具應該替人做無聊的事。這個頁面上的每一個開源專案，都是因為同一件事我手動做了三次、做到不想再做，才寫出來的。

---

I'm Lin Junrong, from Taiwan, studying Management Information Systems at National Chung Hsing University.

What I do is simple: **I turn the workflows that small businesses run on spreadsheets, chat groups, and paper into software that actually works.** Usually alone, usually end to end — requirements, spec, database, backend, frontend, deployment, and then the part nobody wants: keeping it alive after launch.

Over the past two years I've shipped six systems that are still running. A multi-tenant editorial platform for a food brand, where 100+ contributors move through a full submission and review pipeline. A lead-generation SaaS for a B2B distributor that crawls four recruiting platforms weekly, deduplicates, and sends cold email under quota control. A 43-route operations system for a multi-location sports facility — membership, scheduling, four payment gateways, e-invoicing, audit logging. These taught me one thing: **shipping the feature is the easy half. The hard half is that it still works six months later.** So backups, monitoring, restore scripts, and row-level security are part of what I deliver, not something to get to later.

In July 2026 I joined **Agora**, working on AI infrastructure with the [TEN Framework](https://github.com/TEN-framework/ten-framework) team — Kubernetes, GPU observability, and latency in real-time conversational AI. Going from carrying an entire product line alone to owning one piece of large-scale infrastructure is a completely different scale of thinking, and I'm still learning it.

I think tools should do the boring things for you. Every open source project on this page exists because I did the same thing by hand three times and got tired of it.

---

### Open Source · 開源專案

Tools I built for my own work, cleaned up and released.
以下是我為自己的工作流做的工具，整理後開源。

#### 🧰 接案工作流自動化工具組 · Freelance Workflow Automation
**[`freelance-agent-skills`](https://github.com/noron12234/freelance-agent-skills)** · 11 skills · 7,800 行

把接案裡「不是在寫程式」的那 60% 自動化 —— 寫提案書、把會議錄音變成規格、套用客戶改稿、產使用說明書、上線後自動盯 bug。
<sub>11 Claude Code skills automating the non-coding 60% of solo consulting — proposals, meeting-to-spec, client revisions, manuals, post-launch monitoring.</sub>

#### 🔍 「我剛剛做到哪？」Session 找回工具 · Session Finder
**[`wwi`](https://github.com/noron12234/wwi)** · Python · 1,200 行

開了五個終端機視窗之後，忘記哪個 session 有你要的東西。這個工具把所有專案的所有 session 建索引、自動摘要、一句話告訴你那次做了什麼，然後在正確的目錄下幫你重開。
<sub>Browse, search, summarize and resume Claude Code sessions across every project and terminal window.</sub>

#### 💾 自動備份工具組 · Automated Backup Kit
**[`backup-kit`](https://github.com/noron12234/backup-kit)** · Shell / YAML · 1,100 行

客戶系統上線後，資料誰在備份？這套用 GitHub Actions 當排程器，把 Supabase / Fly.io / Insforge 的資料每天備到 GitHub + Backblaze B2 兩層，月費約 $0.50，而且附**測過的還原腳本**。
<sub>Two-tier backup for managed-platform apps — GitHub Actions + Backblaze B2, ~$0.50/month, with tested restore scripts.</sub>

#### 📎 下載來源擷取器 · Download Source Capture
**[`dl-capture`](https://github.com/noron12234/dl-capture)** · Python · macOS

下載一個檔案後，想告訴別人「檔案在這、來源網址在這」，得開 Finder 複製路徑再翻瀏覽器歷史。這個工具自動把兩者一起丟進剪貼簿。
<sub>Automatically put a download's file path *and* its source URL on your clipboard.</sub>

---

### Client Work · 接案作品

I don't name clients directly. A few are recognizable from the live links — those are shipped, public products.

我不主動點名客戶。少數幾個可以從線上連結認出來 —— 那些本來就是已經公開上線的產品。細節可以當面聊。

| Project · 專案 | Stack | Live |
|---|---|---|
| **Multi-tenant editorial platform**<br><sub>Contributor submissions, tag-based editorial pipeline, template-driven email, monthly publication. 100+ contributors.</sub><br><sub>多租戶投稿編輯平台 —— 投稿流程、標籤化編審管線、模板化寄信、月刊發行，超過 100 位投稿者</sub> | Next 16 · Supabase · PostHog · R2 | [↗](https://calendar101-2027.vercel.app) |
| **Real-time analytics dashboard**<br><sub>SSR metrics for the platform above — live submission counts, editorial funnel, contributor cohorts.</sub><br><sub>上述平台的即時數據儀表板 —— SSR 渲染、投稿即時計數、編審漏斗、投稿者分群</sub> | Next 16 · SSR · Supabase | [↗](https://calendar-pulse-sigma.vercel.app) |
| **Studio landing site**<br><sub>Typography-led layout, before/after case studies, motion hero.</sub><br><sub>字體主導的版面、before/after 案例對比、動態主視覺</sub> | Next 16 · Tailwind v4 | [↗](https://dimension-studio.vercel.app) |
| **Lead-scraping SaaS**<br><sub>Crawls four recruiting platforms weekly, dedupes, tags companies, sends bulk cold email under quota control. In production.</sub><br><sub>每週爬四個招募平台、去重、依福利標記公司、配額控管下寄送開發信，已上線運作中</sub> | Python · Streamlit · Playwright · Fly.io · Docker | private |
| **Venue operations platform**<br><sub>43 routes. Membership, class scheduling, 4 payment gateways, cron lifecycle jobs, e-invoice, audit log, GA4 / Meta / LINE tagging.</sub><br><sub>43 條路由 —— 會員、課程排程、4 種金流、cron 生命週期任務、電子發票、稽核日誌、GA4 / Meta / LINE 埋碼</sub> | Next 14 · Supabase | under NDA |
| **Internal PM dashboard**<br><sub>Case pipeline, payment logs, deliverables, engineer assignment. Shared with partner engineers.</sub><br><sub>案件進度、收款紀錄、交付項、工程師指派，與合作工程師共用</sub> | Next · Insforge | private |

More detail → **[github.com/noron12234/works](https://github.com/noron12234/works)**

---

### How I work · 工作方式

- **Solo, end to end.** Spec through deployment through maintenance. No handoffs to lose things in.
- **Ship, then harden.** Get it in front of real users, then close the gaps that actually matter.
- **Automate the boring parts.** Every repo above exists because I did the same thing manually three times.

> - **一個人做完整條線** —— 規格到部署到維運，中間沒有交接可以掉東西
> - **先上線再收斂** —— 讓真實使用者先碰到，再補真正重要的洞
> - **無聊的事自動化** —— 上面每個 repo 都是因為同一件事我手動做了三次

---

### Stack · 技術棧

**Frontend** — Next.js · React · TypeScript · Tailwind
**Backend** — Python · Node · PostgreSQL · Supabase · SQLite
**Infra** — Kubernetes · Docker · Fly.io · Vercel · GitHub Actions
**Tooling** — Playwright · Streamlit · PostHog · Claude Code

---

### Contact · 聯絡

**noron12334@gmail.com** · Taiwan
National Chung Hsing University, Management Information Systems · 國立中興大學 資訊管理學系
