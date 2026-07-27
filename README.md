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

### About · 關於

I build production systems for small and mid-sized businesses — usually alone, usually end to end. Spec, database, backend, frontend, deploy, and the part nobody wants: keeping it alive after launch.

Right now I work on AI infrastructure at **Agora**, on the [TEN Framework](https://github.com/TEN-framework/ten-framework) team — Kubernetes, GPU observability, and real-time conversational AI. Alongside that I run client engagements through **Dimension Studio**, mostly turning spreadsheet-driven workflows into actual software.

> 我幫中小企業做上線用的系統，通常一個人從規格、資料庫、後端、前端、部署一路做到底，包含最沒人想碰的那段 —— 上線之後把它維持活著。
>
> 目前在**聲網 Agora** 的 [TEN Framework](https://github.com/TEN-framework/ten-framework) 團隊做 AI 基礎建設，主要是 Kubernetes、GPU 可觀測性、即時對話式 AI。同時透過**次元創意**接案，多半是把跑在 Excel 上的流程變成真正的系統。

---

### Open Source · 開源專案

Tools I built for my own work, cleaned up and released.
以下是我為自己的工作流做的工具，整理後開源。

| Repo | English | 繁體中文 |
|---|---|---|
| **[freelance-agent-skills](https://github.com/noron12234/freelance-agent-skills)** | 11 Claude Code skills automating the non-coding 60% of solo consulting — proposals, meeting-to-spec, launch analytics, post-launch monitoring | 11 個 Claude Code skill，自動化接案中「不是寫程式」的那 60% —— 提案書、會議轉規格、上線埋碼、上線後監控 |
| **[wwi](https://github.com/noron12234/wwi)** | Browse, search, summarize and resume Claude Code sessions across every project and terminal window | 跨專案、跨終端機視窗瀏覽／搜尋／摘要／續接 Claude Code session |
| **[backup-kit](https://github.com/noron12234/backup-kit)** | Two-tier backup for Supabase / Fly.io / Insforge apps — GitHub Actions + Backblaze B2, ~$0.50/month, with tested restore scripts | Supabase / Fly.io / Insforge 專案的雙層自動備份 —— GitHub Actions + Backblaze B2，月費約 $0.50，附可用的還原腳本 |
| **[dl-capture](https://github.com/noron12234/dl-capture)** | macOS: put a download's file path *and* its source URL on the clipboard, automatically | macOS：自動把下載檔案的「路徑 + 來源網址」一起丟進剪貼簿 |

---

### Client Work · 接案作品

Client names withheld. Happy to walk through any of these in detail.
客戶名稱保留，細節可以當面聊。

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
