# Ihor · IRB888

Learning Web3 through practical tools and open-source contributions. I develop these projects with AI assistance and welcome reproducible bug reports and usability feedback.

## Try the projects

| Project | What it does | Links |
| --- | --- | --- |
| **Gas Planner** | Plans gas budgets with exact wei arithmetic, per-operation execution costs, separate reserves, Ethereum / Base / Optimism comparison and CSV / JSON export. | [Live app](https://irb888.github.io/ethereum-gas-calculator/) · [Source](https://github.com/IRB888/ethereum-gas-calculator) · [32-second walkthrough](https://x.com/bit_ihor/status/2105661837975183668) |
| **Sale Planner** | Organizes research, readiness checks, deadlines and manual payment records, with separate currency totals, workspace calendar export and backups. | [Live app](https://irb888.github.io/token-sale-checklist/) · [Source](https://github.com/IRB888/token-sale-checklist) · [32-second walkthrough](https://x.com/bit_ihor/status/2105664057978056922) |

Both apps support English and Russian, work without a wallet connection, and store plans in your browser. Gas Planner contacts public market-data services only when you request a refresh. Sale Planner makes no external requests. Videos use fictional examples and illustrate the workflow.

## Latest shipped work · 1 October 2026

- **Gas Planner v2.4:** expandable execution costs for each operation, including counts; other fees and reserve remain separate. [19 passing tests](https://github.com/IRB888/ethereum-gas-calculator/actions/runs/36876577457).
- **Sale Planner v2.4:** export all saved upcoming deadlines from open, non-archived projects in one UTC calendar file, without the ten-item agenda limit. Calendar exports are snapshots, not live synchronization. [26 passing tests](https://github.com/IRB888/token-sale-checklist/actions/runs/36876667004).

## Help test a real task

I am looking for 3–5 volunteers for a short usability test. Choose one task, use fictional data, and tell me where you got stuck.

1. **Gas budget:** leave one ETH transfer at 21,000 gas, set 10 gwei and a 25% reserve. The Ethereum budget should be 0.0002625 ETH. Expand the per-operation breakdown. Is the difference between execution and reserve clear?
2. **Deadline planning:** create a fictional project with a future deadline, save and reload. Export all upcoming dates as .ics. Archive the project and check that it leaves the agenda while remaining in the CSV records. Was the export easy to find?
3. **Mobile usability:** repeat either task on a phone. Report any clipped labels, hard-to-tap controls or confusing steps.

Send feedback through the [Gas Planner bug form](https://github.com/IRB888/ethereum-gas-calculator/issues/new?template=bug_report.yml) or [Sale Planner bug form](https://github.com/IRB888/token-sale-checklist/issues/new?template=bug_report.yml), or reply to the walkthrough on X. Include browser/device, steps, expected result and actual result. Do not upload financial backups, private keys or identity documents.

## Proposed open-source contributions

These proposals were open at the last check on 1 October 2026; the links show their current review and merge status.

- [ethereum.org #19361](https://github.com/ethereum/ethereum-org-website/pull/19361): prevent clipboard controls from submitting surrounding forms.
- [Library Management System #12](https://github.com/miteshanshu/Library-Management-System---RBAC/pull/12): include author matches in global search, with regression tests.
- [Legion protocol contracts #30](https://github.com/Legion-Team/legion-protocol-contracts/pull/30): make Quick Start commands copyable and enter the cloned directory before running Forge.

## Scope

These are independent planning tools, not official Legion integrations. They do not execute transactions or submit sale applications. AI assists implementation and documentation; code, tests and limitations are public for review.

[Project notes on X](https://x.com/bit_ihor)
