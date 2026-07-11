<img src="https://raw.githubusercontent.com/tersignhq/.github/main/assets/banner.svg" alt="Tersign — the evidence layer for the agent economy" width="100%"/>

### When software buys from software, someone has to keep the records straight.

Agents now negotiate, transact, and settle at machine speed — on x402, AP2, MPP, ACP — and when something goes wrong, the "evidence" is whatever the interested parties say it was. Payments got standardized. **Proof didn't.**

Tersign is the neutral evidence layer: every receipt, agent action, and verdict is **counter-signed at transaction time** into a per-seller **hash chain** — so any court, regulator, auditor, or counterparty can verify what happened **without trusting the parties *or* us**.

```
offer ──▶ payment ──▶ receipt ─┐
agent action record ───────────┼──▶  countersigned · hash-chained · anchored
dispute verdict ───────────────┘            │
                                            ▼
                          verifiable by anyone, forever
```

| | |
|---|---|
| 🖋 **Counter-signed receipts** | seller-signed EIP-712, counter-signed into sequence — self-issued paper becomes third-party record |
| ⛓ **One ledger, every dialect** | x402 offer-receipts, AP2 mandates, MPP, ACP, agent action logs — normalized into a single chain |
| 📜 **Evidence packs** | EU AI Act Art-50 · audit-log mappings · e-invoicing records — compliance-grade exports for liability holders |
| ⚖️ **Dispute-ready** | deterministic triage + jury-ready evidence envelopes for any arbitration venue |
| 🔍 **Trustless verification** | no account, no API key — [verify a receipt yourself](https://tersign-ledger.kevinn-zhang.workers.dev/verify) |

**Live:** [ledger + public dashboard](https://tersign-ledger.kevinn-zhang.workers.dev) · **SDK:** [`npm i tersign`](https://www.npmjs.com/package/tersign) *(TypeScript, provenance-attested)* · **MCP:** [`io.github.tersignhq/evidence`](https://registry.modelcontextprotocol.io/?search=tersign) *(official registry)* · **Python:** `tersign` *(reserved)*

---

<sub>Venues rotate. **The transcript endures.**</sub>
