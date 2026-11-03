# Company brief

## Product
**Anthropic Radar MCP**: an MCP server that puts the existing `anthropic-radar` SDK (part of the Hyperscaler Radar suite) in front of Claude. Through it, Claude can:

- Scan an Anthropic organization's inventory: users, invites, workspaces and API keys.
- Report Messages API usage, Claude Code usage and cost.
- Run the findings engine to flag cost and hygiene anomalies.
- Export inventory to CSV or a draw.io architecture diagram.

It is built on the existing Hyperscaler Radar packages. Never rewrite a radar that already works; extend it.

## Launch date
**2026-11-06**

## Team
| Agent | Role | Owns |
|---|---|---|
| research-lead | Research | research/ |
| publications-lead | Publications | papers/ |
| product-lead | CTO | product/ |
| data-growth-lead | Data & growth | data/, gtm/ |
| ops-lead | Operations | ops/, STATUS.md upkeep |

## Rules (every agent, every task)
1. **Plan first.** At the start of a task, read this file and STATUS.md, write a short plan, share it with Mor, and wait for approval before changing anything.
2. **No credentials without explicit approval.** Never use, read, create or commit any API key, password, token or other credential unless Mor has explicitly said yes to that specific use or commit.
3. **Never push to `main`.** Work on a branch, open a pull request and summarize the diff for Mor. Only Mor merges.
4. **Stay in your own folders.** Ask the owning agent (through Mor) before changing another agent's folders.
5. **Every change ships with tests.**
6. **No raw personal data in the repo.** Run the scan-anonymize skill on any data first.
7. **Report status.** End every task by updating your section of STATUS.md with Done / Next / Blocked / Needs-from.

## Spend
The **$20 per month** budget is shared by all five agents together. Log every paid action in `ops/` and stop to ask Mor before going over budget.

## Who approves what
Mor approves everything:

| Decision | Approver |
|---|---|
| Starting work on a task plan | Mor |
| Using any key, password or credential | Mor (explicit yes, each time) |
| Merging to `main` | Mor |
| Publishing a paper or post | Mor |
| Launch go/no-go | Mor |
| Sharing or releasing data | Mor |
| Spending money | Mor |
