# Awesome-Personal-Finance-Budgeting

# Top Personal Finance & Budgeting Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Local-First Data Ownership, Envelope Budgeting & Self-Hosted Sync*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Personal Finance & Budgeting**. These tools help individuals and households track spending, assign every dollar a job, and understand where their money goes — with a spectrum running from polished subscription services to local-first applications that keep financial data on your own hardware.

**Examples** include Actual Budget, Firefly III, Maybe, HomeBank, YNAB, Copilot Money, Monarch Money, Simplifi by Quicken, PocketGuard, and Tiller Money (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, envelope budgeting, and transparent data portability — ideal for privacy-conscious users who want YNAB-style budgeting without uploading bank records to someone else's cloud.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[YNAB (You Need A Budget)](https://www.ynab.com/)**  
  **The reference envelope-budgeting app** that popularized zero-based budgeting. Assign every dollar a job, roll with the punches, and age your money. **Subscription-based** with a free trial. **Trade-offs**: cloud-only, subscription fatigue, and no self-hosting path. **Best for users wanting the most polished envelope-budgeting experience** and willing to pay monthly.

- **[Copilot Money](https://copilot.money/)**  
  **Design-forward personal finance app** for iOS and web with AI-powered categorization and spending insights. Subscription-based. **Best for users prioritizing beautiful UX and automatic categorization** over data ownership.

- **[Monarch Money](https://www.monarchmoney.com/)**  
  **All-in-one personal finance dashboard** with budgeting, net worth tracking, and collaboration for couples. Subscription-based. **Best for households wanting a shared financial picture** without self-hosting.

- **[Simplifi by Quicken](https://www.quicken.com/)**  
  **Modern personal finance app** with spending plans, watchlists, and projections. Subscription-based. **Best for Quicken ecosystem users** wanting a lighter-weight web-first option.

- **[PocketGuard](https://pocketguard.com/)**  
  **"In My Pocket" budgeting** that shows what's safe to spend after bills and savings. Subscription-based. **Best for users wanting simple, automated spending guardrails** without manual envelope management.

- **[Tiller Money](https://www.tillerhq.com/)**  
  **Spreadsheet-powered personal finance** that pipes bank data into Google Sheets or Excel. Subscription-based. **Best for spreadsheet power users** who want full control over formulas and reports.

## Open-Source GitHub Projects

- **[Actual Budget](https://github.com/actualbudget/actual)**  
  **The leading open-source YNAB alternative** — MIT licensed, **29,000+ GitHub stars**, actively maintained with commits within hours . **Local-first envelope budgeting** where you assign every dollar a job, with **optional end-to-end encrypted multi-device sync** via a self-hosted server . **Bank sync via GoCardless (EU/UK banks, free) and SimpleFIN (US/CA, ~$1.50/month)** . **Transaction imports** from QIF, OFX, QFX, CAMT.053, and CSV, plus **YNAB4 and nYNAB migration** . **Runs as a lightweight PWA** — works offline and syncs when reconnected . **Resource footprint is tiny**: 256 MB RAM minimum, 512 MB recommended, SQLite storage with no external database . **Headless API** via `@actual-app/api` for programmatic access . **Self-host via Docker** (`actualbudget/actual-server`) or one-click Railway deployment . **Best for anyone wanting YNAB-style budgeting on their own hardware** with full data ownership.

- **[Firefly III](https://github.com/firefly-iii/firefly-iii)**  
  **The feature-packed self-hosted personal finance manager** — AGPL-3.0 licensed, **24,800+ GitHub stars**, PHP/Laravel based . **Double-entry bookkeeping system** with budgets, categories, tags, and recurring transactions . **Rule-based transaction handling** lets you create your own automation rules . **REST JSON API** covering almost every part of the application . **Piggy banks** for saving toward goals, **2FA authentication**, multi-currency support, and extensive financial reports . **Completely self-hosted and isolated** — never contacts external servers unless you explicitly tell it to . **Deployment**: Docker, Kubernetes, Cloudron, Yunohost, and more . **Trade-offs**: **steeper learning curve** than Actual — double-entry accounting and rule configuration require more setup . **Best for users wanting comprehensive financial tracking** with double-entry rigor and deep customization.

- **[Maybe](https://github.com/maybe-finance/maybe)**  
  **The open-sourced revival of a $1M-built finance app** — AGPL-3.0 licensed . **Previously a commercial personal finance + wealth management app** with an "Ask an Advisor" feature; shut down in 2023 and **revived as a fully open-source project** . **Tracks net worth across accounts and assets** with goal tracking and projections . **Self-host with Docker** or one-click deploy . **Note**: the original React codebase relied on external services (Plaid, Finicity, Auth0) and is archived — the active project is a fresh implementation . **Best for users wanting a comprehensive wealth dashboard** who are comfortable with a project still maturing after its revival.

- **[HomeBank](https://github.com/homebank/homebank)**  
  **The long-standing open-source desktop finance app** — GPL-2.0 licensed . **Multi-platform** (Linux, Windows, macOS, BSD) with **comprehensive analysis tools, recurring transactions, detailed reports, and multi-language support** . **Free and local** — no self-hosting server required . **Best for desktop users wanting a mature, simple finance tracker** without web or sync complexity.

### Additional Strong Open-Source Options

- **Beans** — Self-hosted envelope/zero-based budgeting tool, actively developed (v2 in progress) .
- **YAFFA** — Powerful open-source budget app for managing expenses, budgets, and investments with secure self-hosting. GPL-3.0 licensed, 2,900+ stars .
- **monetr** — Open-source alternative for paycheck-to-paycheck budgeting. FSL-1.1-MIT licensed, 680+ stars, actively maintained .
- **Paisa** — Open-source personal finance manager with AI receipt scanning, multi-currency support, and import from GnuCash and Firefly III. 5,700+ stars .

**Frameworks for building custom systems**: Combine **Actual Budget** for the closest YNAB-style envelope budgeting with self-hosted sync and tiny resource footprint, **Firefly III** for comprehensive double-entry bookkeeping with rule automation and REST API, **Maybe** for a wealth-tracking dashboard still maturing as an open-source project, and **HomeBank** for a simple desktop-first tracker — to build a personal finance stack tailored to your budgeting philosophy, technical comfort, and data-ownership requirements.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Personal finance tools differ significantly in budgeting methodology, data ownership, and operational complexity. **Actual Budget is the closest open-source YNAB alternative** with envelope budgeting, encrypted sync, and bank sync via GoCardless/SimpleFIN — and it runs on as little as 256 MB RAM . **Firefly III offers double-entry bookkeeping and rule automation** but requires more setup and accounting knowledge . **Maybe's original React codebase is archived** and relied on external services; the active project is a fresh implementation still maturing . **Self-hosting financial data means you own backups, security patches, and bank connection maintenance** — losing your budget database is your responsibility, not a vendor's .
- Self-hosted open-source solutions require proper backups (SQLite file for Actual, PostgreSQL for Firefly III), TLS configuration, and careful handling of bank sync credentials.

---

**Made for individuals and households building personal finance and budgeting systems they can own and control.**
Let's make personal finance and budgeting more open, local-first, and data-sovereign.
