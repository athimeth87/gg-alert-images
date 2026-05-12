# gg-alert-images

Public artifact host for the [gg-customer-alert](https://github.com/athimeth87/gg-customer-alert) project (private).

LINE Messaging API requires public HTTPS URLs for image messages, so generated stat cards land here so the LINE bot can fetch them anonymously.

## What's here

| File | Purpose |
|---|---|
| `pipeline-card.png` | Latest pipeline summary card (overwritten each run) |

Stat cards contain **aggregated counts only** (no customer names, no PII). The private repo holds the code and full per-customer details.
