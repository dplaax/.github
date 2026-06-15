<div align="center">

# dPLaaX

_Technology opens what **CAN** be. The market chooses what **SHOULD** be._
_Regulation carves what **MUST** be — then the market asks technology for the next **CAN**._

**Provenance has long only marked the points regulation demands.**
**But no matter how many points you stack, you never draw the line.**
**Continuous provenance — proving the line, not the points. That is the next CAN.**

A protocol for continuous, independently verifiable data provenance —
boundary by boundary, across organizations.

</div>

---

## What this is

**dPLaaX** (_"data PipeLine as a X"_) is a protocol of **boundary commitments**.
Whenever data crosses the boundary of an organization or a system, dPLaaX records — in a
tamper-evident form — _who received what, what was done to it, and what was passed on_ — and
links each record to the one before it. The result is not a scattered set of audit points but a
single **line** that any third party can verify independently, with no shared anchor of trust.

A fabricated point is cheap, and generative technology keeps making it cheaper. A fabricated
**line** is not: it would demand the keys of every boundary it crossed and consistency with
records already held downstream. dPLaaX shifts the weight of trust from _"does the artifact look
genuine?"_ to _"can the line be verified?"_

## What it does — and does not — promise

- ✅ **Authenticity and continuity** of the record: each link is signed, and the chain is unbroken and checkable.
- ❌ **Not** the truth of the contents. If a source records a wrong value, that value stays wrong even when the line is complete.
- It **complements** existing standards — W3C Verifiable Credentials, and efforts such as OASIS DPS and IETF SCITT — by carrying the layer they leave out of scope: continuity from the boundary of reception through to output. **Not a competitor.**

## Implementations

- **[provin](https://github.com/provin-line)** — reference implementation (Go).

## Status

Coming soon.
