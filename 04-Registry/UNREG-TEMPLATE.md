*Part of a thought experiment. See [HOW-TO-READ-THIS.md](../HOW-TO-READ-THIS.md). Nothing described here is operating.*

---

# Unregistered Authority Stub Template

This file is the template used when a stop trigger is filed against an authority that is not registered under the Bounded Power Framework.

A stub record is created at `04-registry/UNREG-####.md` (zero-padded sequence, assigned in order of first stop trigger received). The stub captures whatever information the filer was able to declare. Every section the authority itself has not declared is preserved as `[Not declared — operating without registration]`.

A stub record is **not** a registration. It does not assert that the authority has agreed to be bound by the framework. It records, in the framework's own structural vocabulary, the visible fact that an authority exists, exercises power, and has not declared what it is, what it is bound by, or how it can be stopped.

When and if the authority registers, the stub is replaced by a full Mechanism Record under a `SCBP-REG-####` ID, and the UNREG file is preserved as historical record showing the period of unregistered operation.

---

## Workflow

1. A stop trigger is filed naming an unregistered authority (via [stop-trigger.md](../02-forms/stop-trigger.md))
2. The Foundation logs the trigger as a public GitHub Issue within 7 days
3. The Foundation creates a stub Mechanism Record using this template, populated with whatever the filer declared
4. The stub is published at `04-registry/UNREG-####.md` and indexed in `04-registry/README.md`
5. The standard 30-day response clock begins; if the authority responds and chooses to register, the stub becomes a full Mechanism Record
6. If the authority does not respond, the non-response is logged in the stub and the stub remains as a permanent record of unregistered operation

A stub never expires. It can only be superseded by a full registration or remain as historical record.

---

## Template

Copy everything below this line when creating a new stub. Replace bracketed placeholders with actual content. Leave `[Not declared — operating without registration]` in any section the authority itself has not declared.

---

```
# Unregistered Authority Stub — UNREG-####

**[Authority name as known to filer]**

| Field | Value |
|---|---|
| Stub ID | UNREG-####-v1 |
| Status | UNREGISTERED |
| First trigger received | YYYY-MM-DD |
| Authority registered? | No |
| Authority responded? | [Not yet / Yes — see Section 12 / No — non-response logged YYYY-MM-DD] |

---

## Section 1 — Identification

**Authority name (as known to filer):**
[Name as the filer described it]

**Functional description (as known to filer):**
[What the authority appears to do — compel, restrict, require, impose. Based on filer's observation, not the authority's own description.]

**Domain (as inferred):**
[Government / Economic / Technology / Infrastructure / Data-Information / Education / Healthcare / Other / Unknown]

---

## Section 2 — Funding

[Not declared — operating without registration]

---

## Section 3 — Affected Parties

**Filer's relationship to the authority:**
[As described in stop trigger]

**Other parties known to be affected:**
[Not declared — operating without registration]

---

## Section 4 — Entity Size

[Not declared — operating without registration]

---

## Section 5 — Authorization

**Authorizing body:** [Not declared — operating without registration]

**Date of current authorization:** [Not declared — operating without registration]

**Authorization expiration date:** [Not declared — operating without registration]

**Renewal interval:** [Not declared — operating without registration]

---

## Section 6 — Scope Boundaries

**Geographic reach:** [Not declared — operating without registration]

**Coercive ceiling:** [Not declared — operating without registration]

**Data collection:** [Not declared — operating without registration]

**Resource ceiling:** [Not declared — operating without registration]

**Explicit exclusions:** [Not declared — operating without registration]

---

## Section 7 — Harm Thresholds

[Not declared — operating without registration]

---

## Section 8 — Stop Paths

[Not declared — operating without registration]

The authority has not declared any defined stop pathway, threshold, or response process. Concerns regarding this authority can currently only be filed as stop triggers in this registry; the authority has not committed to respond, and any response is voluntary.

---

## Section 9 — Operational Dependencies

[Not declared — operating without registration]

---

## Section 10 — Reversibility

[Not declared — operating without registration]

---

## Section 11 — Stop Triggers Filed

| Date filed | Filer | Issue # | Trigger summary | Response | Response date |
|---|---|---|---|---|---|
| YYYY-MM-DD | [name or anonymous] | #N | [one-line summary] | [Pending / Acknowledged / Disputed / No response] | [YYYY-MM-DD or —] |

---

## Section 12 — Authority Response Log

*[If the authority responds at any point, log here with date, channel, and content summary. If the authority registers, replace this stub with a full Mechanism Record and link to the registration here.]*

---

## Section 13 — Notes

[Optional. Use for clarifications, links to external coverage, or filer-supplied context that does not fit the structured sections.]

---

*UNREG-#### — Bounded Power Foundation*
*This is a stub record. It does not certify the authority's existence, scope, or behavior. It records the fact that an authority has been named in a stop trigger and has not declared the structural information this framework requires of registered authorities.*
*Sections marked "[Not declared — operating without registration]" are gaps in the authority's own declarations, not gaps in this record.*
```

---

> *This document is part of a thought experiment. The "Bounded Power Foundation" is a construct of the experiment, not an organization. Nothing described here is operating. See [HOW-TO-READ-THIS.md](../HOW-TO-READ-THIS.md) for the full framing.*
