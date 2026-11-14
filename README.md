<div align="center">

# SleepWell Trading Journal

**Trade with clarity. Manage risk systematically. Sleep like a baby.**

A private, 100% client-side trading journal and execution analytics suite.

<br>

[![Live Demo](https://img.shields.io/badge/Live_Demo-Open_App-2ea44f?style=for-the-badge&logo=cloudflare&logoColor=white)](https://YOUR-SITE.workers.dev)

![Status](https://img.shields.io/badge/Status-In_Development-f59e0b?style=flat-square)
![Privacy](https://img.shields.io/badge/Data-100%25_Local-0ea5e9?style=flat-square)
![Source](https://img.shields.io/badge/Source-Private-6b7280?style=flat-square)

<br>

![Dashboard](docs/assets/dashboard.jpg)

</div>

> [!NOTE]
> This repository is a showcase only. The source code is private. Try the app through the live demo above.

---

## Why SleepWell

**Private by design.** Trades, notes, and P&L live in your browser's IndexedDB. Nothing is sent to any server, and the built-in Privacy Audit proves it.

**Psychology meets metrics.** Pre- and post-market journaling, a Strategy Playbook, and Ghost Mode sit next to the numbers, so you can find and fix behavioural leaks.

**Risk-adjusted analytics.** R-multiples, drawdown, expectancy, profit factor, and time-of-day edge, with no spreadsheet formulas.

---

## Features

| | |
| :--- | :--- |
| **Portfolio Dashboard** | Equity curve, win rate, profit factor, net P&L, drawdown, and expectancy over custom time windows |
| **Ghost Mode** | Compares your real equity curve with a clean one that removes rule-breaking trades, showing what indiscipline cost you |
| **Strategy Playbook** | Define setups with rule checklists and pin your best trades as benchmarks |
| **Local Insights** | On-device engine that flags tilt, time-of-day leaks, and position-size skew |
| **Journal Health Radar** | Five-axis score for logging, prep, review, plan adherence, and R:R adherence |
| **Global Filters** | Slice everything by date, symbol, setup, tag, side, and account |
| **Heatmap Calendar** | Daily P&L with session notes and trade details |
| **Risk Engine** | FIFO matching, multi-fill pairing, planned vs. realized R:R, fees and slippage |
| **Theme Engine** | Ocean Night, Obsidian OLED, Evergreen, Starlight Festival, Ocean Breeze, Paper, Cloud, Pelican Town |
| **Markdown Journal** | Pre- and post-market templates with mindset prompts and execution audits |
| **Trade Cards** | Paste screenshots from the clipboard and export shareable trade cards |
| **CSV / Excel Import** | Presets for IBKR, Schwab, Thinkorswim, TradingView, MetaTrader, Robinhood, TradeStation |
| **Backups** | One-click JSON export and restore |

---

## Workflow

1. **Playbook:** define setups and pre-trade rules
2. **Pre-market:** review conditions and complete the mindset checklist
3. **Log trades:** manual entry with planned stop and target, or bulk import
4. **Review:** tag setups and mistakes, check R-multiples, write the debrief
5. **Analyze:** use Ghost Mode, Local Insights, and the Health Radar to find your edge and your leaks

---

## Built With

![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router_7-CA4245?style=flat-square&logo=reactrouter&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

Charts with Recharts, storage in IndexedDB, imports via PapaParse and SheetJS.

---

## Data & Backups

Everything runs in your browser, so **your data never leaves your device.**

- **Privacy Audit:** Settings → Privacy Audit confirms no external requests
- **Backups:** use Export backup regularly, because clearing site data erases IndexedDB
- **Moving devices:** export a backup, then use Import trades → Restore Backup on the new device

---

<div align="center">

Questions or feedback? Open an issue.

</div>
