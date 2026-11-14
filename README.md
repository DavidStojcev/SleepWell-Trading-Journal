# 📊 SleepWell Trading Journal

> **Trade with clarity, manage risk systematically, and sleep like a baby at night.**
>
> A private, 100% client-side trading journal and execution analytics suite for disciplined equity, futures, forex, and crypto traders.

### 🔗 [**Live Demo → https://sleepwell.journal-apps.workers.dev/**](https://sleepwell.journal-apps.workers.dev/)

> [!NOTE]
> 🚧 **Work in progress.** Features and UI are evolving quickly.
> 🔒 **Source code is private.** This repository is a showcase only: screenshots, feature overview, and the live link.

![SleepWell Trading Journal Dashboard](docs/assets/dashboard.jpg)

---

## 💡 Why SleepWell?

1. **100% data privacy (zero backend)**: Trades, notes, and P&L live in your browser's **IndexedDB**. Nothing is sent to any server. Verify it anytime with the built-in **Privacy Audit**.
2. **Psychology meets metrics**: Quantitative stats are paired with pre/post-market journaling, a **Strategy Playbook**, and **Ghost Mode** to find and fix behavioural leaks.
3. **Risk-adjusted analytics**: R-multiples, drawdown, expectancy, profit factor, and time-of-day edge, with no spreadsheet formulas.

---

## ✨ Key Features

| Feature | Description |
| :--- | :--- |
| **📈 Portfolio Dashboard** | Equity curve, win rate, profit factor, net P&L, drawdown, and expectancy over custom time windows. |
| **👻 Ghost Mode** | Overlays your real equity curve with a "clean" curve that removes rule-breaking trades, showing what indiscipline cost you. |
| **📘 Strategy Playbook** | Define setups with rule checklists and pin your best trades as benchmarks. |
| **🧠 Local Insights** | On-device engine that flags tilt, time-of-day leaks, and position-size skew. No cloud calls. |
| **🕸️ Journal Health Radar** | 5-axis score for logging completeness, prep, review, plan adherence, and R:R adherence. |
| **🔍 Global Filter Bar** | Slice everything by date, symbol, setup, tag, side, and account. |
| **📅 Heatmap Calendar** | Daily P&L with session notes and trade details. |
| **⚖️ Risk & Execution Engine** | FIFO matching, multi-fill pairing, planned vs. realized R:R, fees and slippage. |
| **🎨 Theme Engine** | Dark and light themes: Ocean Night, Obsidian OLED, Evergreen, Starlight Festival, Ocean Breeze, Paper, Cloud, Pelican Town. |
| **📝 Markdown Journal** | Pre- and post-market templates with mindset prompts and execution audits. |
| **📸 Trade Cards** | Paste screenshots from the clipboard and export shareable trade cards. |
| **📥 CSV / Excel Import** | Presets for IBKR, Schwab, Thinkorswim, TradingView, MetaTrader, Robinhood, TradeStation, and generic files. |
| **🛡️ Privacy Audit & Backups** | Proof of zero outbound traffic, plus one-click JSON backup and restore. |

---

## 🔄 Workflow

```
[1. Playbook] ─► [2. Pre-Market Prep] ─► [3. Log / Import Trades]
                                                   │
[5. Insights & Ghost Mode] ◄─ [4. Post-Market Review] ◄┘
```

1. **Playbook**: define setups and pre-trade rules.
2. **Pre-market**: review conditions and complete the mindset checklist.
3. **Log trades**: manual entry with planned stop/target, or bulk import from your broker.
4. **Review**: tag setups and mistakes, check R-multiples, complete the post-market debrief.
5. **Analyze**: use Ghost Mode, Local Insights, and the Health Radar to find your edge and your leaks.

---

## 🛠️ Tech Stack

- **UI**: React 19 + Vite
- **Routing**: React Router v7
- **Charts**: Recharts
- **Storage**: Client-side IndexedDB (no backend)
- **Parsing**: PapaParse (CSV), SheetJS (Excel)
- **Images**: html-to-image
- **Testing**: Vitest (170+ tests) and Playwright (E2E)
- **Hosting**: Cloudflare (free tier), auto-deployed from a private GitHub repository

---

## 🔒 Data Privacy & Backups

Because everything runs in your browser's IndexedDB, **your data never leaves your device**.

- **Privacy Audit**: Settings → Privacy Audit confirms no external requests.
- **Backups**: use **Export backup** regularly. Clearing site data can erase IndexedDB.
- **Moving devices**: export a backup, then use **Import trades → Restore Backup** on the new device.

---

## 📬 Contact

Questions or feedback? Open an issue on this repository.
