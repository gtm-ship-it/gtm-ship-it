# Mauricio Rodríguez Esparza

**Founding engineer — human-led AI systems for revenue operations.**

I build and operate the layer between *"a lead enters the CRM"* and *"a human closes the deal."*
Multi-branch businesses lose revenue in that gap: slow first contact, inconsistent follow-up,
bad data, no branch-level visibility. I install systems that close it — and hand the human
a qualified conversation with the context already attached.

I'm the technical co-founder of [PTS AI](https://ptsai.ai). I designed the architecture, wrote the
serverless and orchestration layer, and run it in production for consumer-lending and tax-prep
branch networks.

**[→ See how the system works](https://github.com/gtm-ship-it/growth-engine)** ·
**[→ Case study: customer reactivation](https://github.com/gtm-ship-it/growth-engine/blob/main/case-studies/customer-reactivation.md)** ·
**[→ ptsai.ai](https://ptsai.ai)**

---

## Selected systems

| System | What it does | Status |
|---|---|---|
| **[Growth Engine](https://github.com/gtm-ship-it/growth-engine)** | Reference architecture for the whole stack: intake → enrichment → qualification → **human handoff** → measurement. Includes the handoff contract and a sanitized case study. | Production |
| **[Branch Manifest](https://github.com/gtm-ship-it/branch-manifest)** | A branch is a config, not a custom build. JSON Schema + validator + CLI that gates a location on compliance and ownership before it can go live. Runnable, tested. | Production tooling |

Client production code is private and contains customer data. Both repos above are written from
that work: real architecture and real interfaces, with synthetic fixtures and no customer records.

---

## What I actually build

**AI and language systems** — voice agents that qualify inbound and reactivation calls;
post-call classification into structured CRM dispositions; role-specialized advisory agents
over an operating context.

**Orchestration** — event-driven workflows across CRM, enrichment, telephony and email.
Seven production workflows move a lead from intake to a booked conversation.

**Revenue operations** — CRM object and stage design, routing rules, lead scoring,
branch-level reporting that a regional manager will actually open.

**Infrastructure** — serverless functions on edge runtime, gated client portals,
secrets in environment variables and nothing else, static deploys with per-client isolation.

---

## How I work

**Humans stay accountable.** Automation removes repetition, not responsibility. Every workflow
I build names the person who owns the outcome after the machine stops.

**Automation ends at a handoff, and the handoff is a contract.** Not "the bot sent an alert" —
a named owner, the context they need, the action expected, the time they have, and a recorded
outcome that improves the next cycle.

```
Business trigger → AI/automation → structured context → human owner
    → decision → recorded outcome → better next cycle
```

**Evidence over adjectives.** A green workflow run is not proof. I validate the business
result in the CRM before calling anything done. Numbers I can't source, I don't publish —
including my own.

**Compliance is a gate, not a footnote.** A branch with an unapproved messaging registration
does not get to send messages, regardless of what the launch calendar says. That rule is
enforced in code, not in a doc.

---

## Evidence

From the first production deployment — a consumer-lending network reactivating past customers:

- **10 branches**, June 2026: **13,159 dialed calls → 89 live transfers** to branch staff,
  plus **382 contacts** flagged high/medium intent for human follow-up.
- Transfers are counted **only when the branch was notified**; filtered and test calls excluded.
  Figures are itemized per branch in the client's own report.
- Expanded to **28 branches** in July 2026.

That's the observed pilot result, not a projection. Targets, forecasts and pipeline numbers
live in internal planning — not here.

---

## Background

I came to engineering from go-to-market, which is why these systems are designed around a
revenue outcome rather than a demo. On this work I've owned the commercial relationship and
the codebase at the same time — the offer, the customer calls, and the deploy.

Everything ships bilingual (EN/ES), because the operators using it are.

---

## Contact

**team@ptsai.ai** · [ptsai.ai](https://ptsai.ai)

Open to conversations about founding-engineer and technical-lead roles in applied AI,
and about revenue systems for multi-branch operators.

<!-- profile -->
