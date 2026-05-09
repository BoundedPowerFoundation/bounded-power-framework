*Part of a thought experiment. See [HOW-TO-READ-THIS.md](HOW-TO-READ-THIS.md). Nothing described here is operating.*

---

# Registry Charter

## Bounded Power Foundation

This Charter describes how the registry envisioned by the construction would govern itself if it operated. The Charter, like the rest of the construction, is part of the experiment — its job is to make visible what the rules of operating such a registry would have to be, so that those rules can be examined.

---

## What This Document Is

This Charter defines the registry as an institution. It establishes what the registry is, what it can and cannot do, who would operate it, and what would bind that operator.

This Charter is not the Bounded Power Framework. The Framework — defined by [the Structural Constitution (SCBP-04)](01-framework/SCBP-04-Structural-Constitution-v1.3.md) and its operational documents — sets the rules the construction proposes for all authority. This Charter governs only the operation of the registry that would record authorities choosing to declare themselves under that Framework.

The Charter is subordinate to the Structural Constitution. Nothing in this Charter authorizes the registry to act in ways the Constitution prohibits. Where conflict exists, the Constitution governs.

---

## Section 1 — Purpose and Identity

The registry is a public, append-only record-keeping infrastructure for the Bounded Power Framework.

The registry's purpose is to make declared authority visible, to receive and log stop triggers from affected parties, and to preserve a permanent public record of those filings and any responses. It is built to be reachable, to be honest about what it has and has not received, and to make absence visible when absence is the relevant fact.

The registry does not enforce the Framework. It does not adjudicate compliance. It does not determine whether an authority should continue. It does not designate reviewers. It does not validate claims made in registration filings. Its function is custody and visibility — nothing more.

---

## Section 2 — What the Registry Is Not

The registry is explicitly **not**:

- A regulator
- A court
- A licensor or certifier
- A grant-maker or fee collector
- A reviewer of compliance
- A representative of any registered authority's interests
- A proxy for the Bounded Power Framework's enforcement (the Framework is not centrally enforced; it is structured to be enforced through visibility and the actions of affected parties)

A registered authority's appearance in this registry does not constitute endorsement, certification, validation, or approval. Registration is a public declaration by the authority of its own scope, thresholds, and stop paths. The registry records the declaration.

---

## Section 3 — Custody Principles

These principles define what custody means for the registry.

**Append-only.** Once a record is filed, it is not deleted. Records can be updated, but updates are logged inside the record itself and the prior versions remain visible in version control history.

**No editorial discretion over content.** The registry does not edit, condense, rephrase, or selectively withhold submitted content. The registry may format submissions for publication consistency (e.g., apply a standard template) but may not alter the substance of any submission.

**Public on receipt.** Submissions become public when they are received. There is no review queue. There is no editorial gate. The act of filing is the act of publication.

**Mechanical errors are corrected with public logs.** If the operator makes a mechanical error (typos, broken links, formatting issues, duplicate entries), the correction is logged with timestamp and reason. Substantive content is never altered, only annotated.

**Filings are not validated.** The registry does not check whether a registration's claims are accurate, whether a stop trigger's allegations are credible, or whether a non-response is justified. The registry records what is filed and lets visibility be the mechanism.

---

## Section 4 — Operator

The Bounded Power Foundation is named in the construction as the registry's operator.

The Foundation is itself a registered authority under the Framework. Its Mechanism Record is [SCBP-REG-0001](04-registry/SCBP-REG-0001.md). It is bound by the Structural Constitution like any other registered authority.

Operating the registry does not grant the Foundation special authority. The Foundation has no power to compel, fine, suspend, or terminate any registered authority. Its sole capabilities are: maintain the records, log filings, notify parties named in filings, and make non-response visible when it occurs. These capabilities exist to keep the registry trustworthy. They do not constitute power over registered authorities.

---

## Section 5 — What the Operator May Do

The operator may:

- Add new Mechanism Records when registrations are filed
- Add new stub records (UNREG-####) when stop triggers name unregistered authorities
- Log stop triggers, responses, and non-responses against existing records
- Correct mechanical errors with logged annotations
- Initiate Charter renewal and Mechanism Record renewal of SCBP-REG-0001 itself, subject to the same independent-review requirements that apply to any registered authority
- Communicate publicly on behalf of the registry about registry operations

---

## Section 6 — What the Operator May Not Do

The operator may not:

- Delete any submitted record
- Edit the substantive content of any submission
- Suppress, hide, or selectively withhold filings from public view
- Decide whether a stop trigger is credible, actionable, or sufficient
- Designate, recruit, or select reviewers for any authority's renewal review (including for SCBP-REG-0001 itself)
- Issue findings of compliance or non-compliance against any registered authority
- Charge fees for registration, filing, or any other registry function
- Accept payment from any registered authority for any reason
- Grant exemptions from the Framework or from this Charter
- Transfer the registry, its records, or operator authority to any registered authority
- Communicate publicly *as* a registered authority — the operator speaks for the registry, not for any authority recorded in it

When the operator's individual judgment is required (e.g., classifying which template applies to a filing, deciding whether an issue is mechanical or substantive), the decision is logged with reasoning and remains subject to challenge through the same stop-trigger process available to any affected party.

---

## Section 7 — Self-Review and Conflict of Interest

When the Foundation itself is the subject of a stop trigger, a renewal review, or any other Framework process that would normally involve operator participation:

- The operator does not participate in the review
- The operator preserves the same evidence and procedural support that would be provided for any other registered authority
- Reviewers are drawn from affected parties via the civic trigger mechanism, not designated by the operator
- The operator publicly logs the recusal at the start of the review and the receipt of the review's findings at the close

The Foundation cannot grant itself an exemption from the Framework. SCBP-REG-0001's renewal would be conducted by parties affected by the registry — not by the Foundation. If no affected party convenes a review by the renewal deadline, SCBP-REG-0001 expires under R28 (Expiration Default) and the registry ceases to be a registered authority, regardless of whether it continues as infrastructure.

Continued operation of the registry without a current Mechanism Record is itself a finding the framework's logic surfaces — by R28, expired authority must enter provisional suspension. This reinforces the registry's commitment to seek genuine independent review, not to manufacture one.

An expired Mechanism Record is not deleted. It remains in the registry as historical record, with status `EXPIRED`. If the operator wishes to re-establish a registered authority covering similar function, this is done by filing a new Mechanism Record under a new sequence number (e.g., SCBP-REG-0002), not by editing or replacing the expired one. The new record is a fresh registration with its own scope, thresholds, and renewal cycle.

---

## Section 8 — Relationship to the Framework

This Charter is governed by [SCBP-04 — Structural Constitution](01-framework/SCBP-04-Structural-Constitution-v1.3.md). The Constitution defines the rules the construction proposes for all authority; this Charter defines how the registry operates within those rules.

If conflict exists between this Charter and the Constitution, the Constitution governs.

If conflict exists between this Charter and a Mechanism Record (including SCBP-REG-0001), the Charter governs general registry operation; the Mechanism Record governs the specific authority. Where they are inconsistent, the inconsistency is itself a finding.

This Charter does not authorize the registry to act in ways the Constitution prohibits. It does not interpret the Constitution. It does not override Framework documents.

---

*REGISTRY-CHARTER.md — Bounded Power Foundation*
*The registry is custody, not authority. Its function is to be reachable, to be honest, and to keep the record.*
