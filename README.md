# Mauricio Rodríguez Esparza

**Founding engineer — human-led AI systems for revenue operations.**

I build and operate the layer between *"a lead enters the CRM"* and *"a human closes the deal."*
Multi-branch businesses lose revenue in that gap: slow first contact, inconsistent follow-up,
bad data, no branch-level visibility. I build systems that close it — and hand the human a
qualified conversation with the context already attached.

I'm the technical co-founder of [PTS AI](https://ptsai.ai), building this for consumer-lending
branch networks. Architecture, the serverless layer, and the orchestration design are mine;
workflow implementation and client reporting are shared with a small team.

**[Growth Engine](https://github.com/gtm-ship-it/growth-engine)** — architecture and the
handoff contract ·
**[branch-manifest](https://github.com/gtm-ship-it/branch-manifest)** — runnable, 13 tests

---

## What I build

**AI and language systems** — voice agents that qualify inbound and reactivation calls;
post-call classification into structured CRM dispositions; role-specialized advisory agents
over an operating context.

**Orchestration** — event-driven workflows spanning CRM, enrichment, telephony and email,
carrying a record from intake through to a booked human conversation.

**Revenue operations** — CRM object and stage design, routing rules, lead scoring, and
branch-level reporting that a regional manager will actually open.

**Infrastructure** — serverless functions on edge runtime, gated client portals, per-client
isolation, secrets in environment variables and nowhere else.

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

**Evidence over adjectives.** A green workflow run is not proof. I validate the business result
in the system of record before calling anything done. Numbers I can't source, I don't publish —
including my own.

**Compliance is a gate, not a footnote.** Enforced in code, not in a runbook.

---

## On what's not here

The production system is private: it processes customer records and encodes how the business
operates. The two repos above are the architecture and the tooling, written from that work with
fictional data.

Client volumes and rates aren't published. I can walk through them in conversation — I don't
publish client figures without written consent.

---

## Background

I came to engineering from go-to-market, which is why these systems are designed around a
revenue outcome rather than a demo. On this work I've owned the commercial relationship and
the codebase at the same time — the offer, the customer calls, and the deploy.

Everything ships bilingual (EN/ES), because the operators using it are.

Open to conversations about founding-engineer and technical-lead roles in applied AI.

**team@ptsai.ai** · [ptsai.ai](https://ptsai.ai)
