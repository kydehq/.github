# KYDE

**The control layer for agent autonomy.**

AI agents drift. KYDE detects it, quarantines it,
and makes agents safe enough to run in critical environments.

Behavioral drift is measurable from operational behavior.
The detection core can be deterministic.
When you can detect drift at runtime, you can safely increase an agent's autonomy.

Not on the machine. Not in the agent. KYDE sits outside,
in the request path between your agents and every LLM provider —
every action intercepted, scoped, and signed before it executes.
Outside the agent. Cannot be overridden.

```sh
$ export OPENAI_BASE_URL=https://kyde.intranet/v1
```

Zero code changes. One environment variable.
Provider-agnostic, MCP-ready, <100 ms target latency.

## The problem we own

AI agents change their behavior over time.
They keep running. They report success.
They are no longer doing the same work.

That is behavioral drift.
In a demo it is an anecdote.
In a factory, a grid, a bank, or critical infrastructure it is an incident
waiting for a record that does not exist.

Vendors grade their own homework.
Provider logs live on their infrastructure, signed with their keys.
The suspect can't write the police report.

## OBSERVE → DETECT → QUARANTINE → INVESTIGATE → PROVE

Know what your agents are actually doing.

Every action crosses KYDE. We build a behavioral baseline
for each agent and continuously test what happens against it.

When behavior changes, KYDE detects the deviation.
High-risk agents can be quarantined automatically.
The underlying record remains available for investigation
and independent verification.

- **OBSERVE** — Every action at the boundary. Who acted, against which model,
  reaching which tool, why. Written as it passes — not reconstructed later
  from four vendor consoles.
- **DETECT** — Drift against the agent's own baseline, from operational behavior,
  in real time. Deterministic at the core.
- **QUARANTINE** — Restrict autonomy before a deviation becomes an incident.
  Deny-by-default at the boundary. The damage doesn't happen first
  and get explained later.
- **INVESTIGATE** — Replay what changed. Same run, present model.
  "Something feels off" becomes a difference you can point at.
- **PROVE** — An audit trail architecturally independent of every LLM provider:
  Ed25519-signed, hash-chained, captured at the boundary,
  undeletable by any agent.

Zero Trust is the mechanics.
Behavioral drift is the problem.
Autonomy is the outcome.

## Autonomy should be earned

An agent doesn't become trustworthy because someone switched it on.
It earns autonomy by demonstrating that it can operate
within its intended behavior over time.

Detect drift → restrict autonomy → investigate → restore when proven.

Start with limited responsibility.
Increase it as the record shows the agent held its lane.
A worker that stops producing that evidence comes back down.

KYDE is the layer that lets companies trust autonomous AI
enough to let it do real work.

## We're researching the problem we're building for

**Behavioral Drift in Autonomous LLM-driven Systems**

Our research surveys the detection landscape and asks a simple question:

Can we detect when an AI agent stops behaving like itself —
deterministically, in real time, from the actions it actually takes?

KYDE is the infrastructure that follows from that question.
Not a slogan we invented after the product.
The product of a problem we are measuring.

[Read the paper →](https://kyde.com/behavioral-drift)

## Start here

**KYDE Gateway Starter** — free, self-hosted, source-available.
Docker Compose plus one environment variable gives you an independent witness
for every agent action: dashboard, hash-chained append-only ledger,
coverage indicator, DLP alerts, compliance exports.
Works with OpenAI, Anthropic, Google, and local models.

Observe first. Enforce when ready.

**Gateway Enterprise** adds inline enforcement, HSM-backed signing,
deny-by-default role scoping, per-tool MCP policy,
quarantine of drifted agents, and the KYDE Trust Score™
with Coverage Report — behavior rated across every provider
in the same currency.

## Built for environments where failure has consequences

Factories · Energy · Infrastructure · Finance

Also: insurance, healthcare, public sector, manufacturing.
Built for NIS-2, DORA, the EU AI Act, and GDPR from day one —
built *with* regulated industries, not for them.

Your agents are a workforce.
Your workforce is critical infrastructure.
Govern accordingly.

kyde.com · Platform · Paper · Starter · Labs · hello@kyde.com

Early stage. Based in Germany.
Building the layer that lets autonomous AI do real work.

**[kyde.com](https://kyde.com)** · [Platform](https://kyde.com/platform) · [Trust Score™](https://kyde.com/trust-score) · [Starter](https://kyde.com/starter) · [Labs](https://kyde.com/labs) · [hello@kyde.com](mailto:hello@kyde.com)

Early stage. Based in Germany. Building for the industries where failure has consequences.
