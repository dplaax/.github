<div align="center">

# dPLaaX

_Technology opens what **CAN** be. The market chooses what **SHOULD** be._
_Regulation carves what **MUST** be — then the market asks technology for the next **CAN**._

**Provenance has long only marked the points regulation demands.**
**But no matter how many points you stack, you never draw the line.**
**Continuous provenance — proving the line, not the points. That is the next CAN.**

A protocol for continuous, federated data provenance —
independently verifiable, boundary by boundary, across organizations.

</div>

---

## What this is

**dPLaaX** (_"data PipeLine as a X"_) is a protocol of **boundary commitments**.
Whenever data crosses the boundary of an organization or a system, dPLaaX records — in a
tamper-evident form — _who received what, what was done to it, and what was passed on_ — and
links each record to the one before it. The result is not a scattered set of audit points but a
single **line** that any third party can verify independently, without a central trust authority.

A fabricated point is cheap, and generative technology keeps making it cheaper. A fabricated
**line** is not: it would demand the keys of every boundary it crossed and consistency with
records already held downstream. dPLaaX shifts the weight of trust from _"does the artifact look
genuine?"_ to _"can the line be verified?"_

## The argument

That the content of a record is true can never be proven. This is not a
technical immaturity; it is a limit in principle. What AI changed is the
scope of that limit — from exception to default. Unverifiable stages —
model inference, human judgment — became standard pipeline components, and
the cost of forging a plausible artifact collapsed toward zero. The old
path of inferring trust from how convincing the artifact looks has closed.

If content cannot be guaranteed, one lever remains: raising the
**after-the-fact cost of a lie**. That cost cannot arrive without
attribution — a lie that cannot be pinned to anyone cannot be punished,
sued, or priced into a reputation. And between organizations that will not
appoint a single operator, attribution has to travel with the records
themselves: a chain of signatures at every boundary the data crosses.

This deterrence has preconditions. It reaches only parties who hold an
identity worth protecting, and on whom consequences can land. In the
economy of firms, those preconditions are already met: a firm _is_
accumulated credibility it cannot afford to lose, and inter-firm commerce
has always run on promises staked on a name. Contracts, audits,
double-entry bookkeeping — none of these are devices for proving content
true. They are devices for making lies attributable.

Trust in the age of AI, then, is not proof that content is correct. It is
the state in which **every claim is non-repudiably attributable to an
entity with something to lose**. dPLaaX is the protocol that establishes
that attribution across organizations, without an operator, cryptographically.

> **Trust is not a guarantee of truth. It is the attributability of lies.**

## What it does — and does not — promise

- ✅ **Authenticity and continuity** of the record: each link is signed, and the chain is unbroken and checkable.
- ❌ **Not** the truth of the contents. If a source records a wrong value, that value stays wrong even when the line is complete — and stays attributed.
- It does **not replace** domain-specific standards. It adds a common protocol for the layer they leave out of scope: keeping provenance connected across process boundaries.

## The spec

| Repository | What it is |
| --- | --- |
| [**spec**](https://github.com/dplaax/spec) | The normative body — rule catalog (YAML), wire schemas (JSON Schema 2020-12), conformance vectors. |
| [**site**](https://github.com/dplaax/site) | [dplaax.dev](https://www.dplaax.dev) — the public-facing site. |

Wire semantics start in the spec, not in an implementation. Read
[concept.md](https://github.com/dplaax/spec/blob/main/concept.md) for the why,
then the rule catalog for the letter.

## Implementations

- [**provin**](https://github.com/provin-line) — the reference implementation (Go):
  control plane, data plane, three-organization end-to-end tests, and the
  gate-scaling measurements.

## Status

**v0.1 draft — public, under review, exercised by a running implementation.**

- [dPLaaX spec](https://github.com/dplaax/spec) v0.1 draft — all rules in `draft` state, evolving on implementation feedback; public review welcome
- [provin oss v0.3.0](https://github.com/provin-line/oss) — the revision line evaluated in the systems paper
- Systems paper — acceptance decisions at delivery time, evaluated on
  public snapshots _(forthcoming)_
