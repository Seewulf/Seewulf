# Prabin Bhusal: Business Central developer

I build and fix Microsoft Dynamics 365 Business Central extensions, integrations and reports, and upgrade NAV to Business Central. 3+ years on Business Central and NAV, mostly finance processes. Based in Nepal (UTC+5:45), open to part-time contract work.

[LinkedIn](https://www.linkedin.com/in/prabin-bhusal-44537635b) · [Fiverr](https://www.fiverr.com/prabin_bhusal) · [Upwork](https://www.upwork.com/freelancers/~01f604cbd2fa985b30)

## Code you can read

| Project | What it shows |
|---|---|
| [Explain and Resolve for Business Central](https://github.com/Seewulf/BC-Copilot-Across-Modules) | Three Copilot features: one checks an open purchase invoice against its receipts, the order and the vendor's posted invoices; one ranks overdue customers from the customer ledger; one checks a payment run for duplicates, bank account changes, unusual amounts and first payments. AL code computes every figure, the AI explains and drafts the emails, a person keeps or discards; nothing is posted or sent. Needs your own Claude API key (Azure OpenAI planned). Run live on a sandbox. 145 automated tests. |
| [Stripe Invoice Payments for Business Central](https://github.com/Seewulf/BC-Stripe-Invoice-Payments) | A customer pays a posted sales invoice by card on Stripe Checkout, and a Job Queue sync posts and applies the payment. Syncing twice posts once; one failed payment never stops the others. Run live in Stripe test mode. 31 automated tests. |
| [Royalty Accrual Sample for Business Central](https://github.com/Seewulf/BC-Royalty-Accrual-Sample) | Royalties from posted sales to the G/L: advance (minimum guarantee) recoupment, approval with an audit log, balanced accrual journal lines. 33 automated tests. |
| [Odoo API Integrations](https://github.com/Seewulf/Odoo-API-Integrations) | An AL extension that imports Odoo products over JSON-RPC: API key in isolated storage, paged sync into a staging table. |

All four are per-tenant extensions with no base-app changes, MIT licence.

## What I work on

- AL extensions: table and page extensions, codeunits, events, Job Queue tasks, permission sets
- Integrations: REST and OData APIs; payment gateways (the Stripe sample above; Nepal's eSewa and Fonepay, live in production); government e-invoicing (sync to Nepal's tax authority, IRD)
- Performance: a posting job that ran 8–10+ hours and sometimes crashed now finishes in 3–4 hours
- NAV to Business Central upgrades, C/AL to AL
- RDLC and Word report layouts

## How I work

Scope agreed in writing, built and tested in a sandbox, automated tests where the logic carries money, source code handed over, small commits you can review.
