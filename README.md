# Ihor · IRB888

Learning Web3 through practical tools and open-source contributions. I develop these projects with AI assistance and welcome reproducible bug reports and usability feedback.

## Try the projects

| Project | What it does | Links |
| --- | --- | --- |
| **Gas Planner** | Plans operation gas budgets with exact wei arithmetic, reserve breakdowns, Ethereum / Base / Optimism comparison and CSV / JSON export. | [Live demo](https://irb888.github.io/ethereum-gas-calculator/) · [Source](https://github.com/IRB888/ethereum-gas-calculator) |
| **Sale Planner** | Organizes research, readiness checks, deadlines and manual payment records, with separate currency totals, calendar export and backups. | [Live demo](https://irb888.github.io/token-sale-checklist/) · [Source](https://github.com/IRB888/token-sale-checklist) |

Both apps support English and Russian, work without a wallet connection, and store plans in your browser. Gas Planner contacts public market-data services only when you request a refresh. Sale Planner makes no external requests.

## Help test a real task

- **Gas Planner:** add a 21,000-gas ETH transfer, set 10 gwei and a 25% reserve. For that single operation, the Ethereum budget should be 0.0002625 ETH. Unknown L2 fees are shown as incomplete estimates. [Report a problem](https://github.com/IRB888/ethereum-gas-calculator/issues/new?template=bug_report.yml).
- **Sale Planner:** create a fictional project with a future deadline, save it, reload, and export its CSV record. Archive it and check that it leaves the upcoming-deadline list while remaining in the CSV. [Report a problem](https://github.com/IRB888/token-sale-checklist/issues/new?template=bug_report.yml).

Please include your browser, device, steps, expected result and actual result. Use fictional data; do not upload financial backups, private keys or identity documents.

## Open-source contribution

[ethereum.org PR #19361](https://github.com/ethereum/ethereum-org-website/pull/19361) proposes preventing clipboard controls from submitting surrounding forms. The linked PR shows the current review and merge status.

## Scope

These are independent planning tools, not official Legion integrations. They do not execute transactions or submit sale applications. AI assists implementation and documentation; code, tests and limitations are public for review.

[Project notes on X](https://x.com/bit_ihor)
