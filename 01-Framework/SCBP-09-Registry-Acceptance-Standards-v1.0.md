*Part of a thought experiment. See [HOW-TO-READ-THIS.md](../HOW-TO-READ-THIS.md). Nothing described here is operating.*

---

# SCBP-09 — Registry Acceptance Standards

*Operational Layer*
*Subordinate to: the Structural Constitution*

---

## Purpose

This document defines the floors and ceilings the registry applies to authority-declared variables in Mechanism Records.

The Mechanism Record is filed by the authority itself. The authority declares its own scope, thresholds, response windows, and stop paths. This is by design — authorities know their own functional reality better than any external party. But unbounded self-declaration can be gamed: an authority can declare absurdly high response windows, unreachably high aggregate trigger thresholds, or insufficient stop paths, technically completing registration while making the framework's own mechanisms ineffective.

This document defines the structural bounds within which authority self-declaration is acceptable. Declarations outside these bounds are rejected at registration. Declarations within these bounds but visibly gamed for the authority's specific scope can be challenged by stakeholders through the civic trigger process (see SCBP-08).

This document is operational, not constitutional. It does not modify SCBP-04. It can be amended through the registry's amendment process without touching the frozen Constitution.

---

## Section I — Validation Principle

The registry validates Mechanism Records at registration and at any update. Validation is structural, not editorial. The registry checks that declared values fall within bounds; it does not assess whether the authority's narrative justification is persuasive or whether its self-classification is accurate.

If declared values fall outside the bounds defined in this document, the submission is returned for correction. Returns are logged publicly. Repeated returns of the same Mechanism Record without movement toward acceptable values are themselves a Framework finding.

If declared values fall within bounds but appear gamed for the authority's specific scope (technically compliant but practically unreasonable), the authority may register, but stakeholders may file a Challenge-class trigger contesting the declarations. The Challenge is reviewed under the standard SCBP-08 process; the registry does not adjudicate.

---

## Section II — Aggregate Trigger Threshold

The aggregate trigger threshold defines the number of independent stop triggers, filed within a defined time window against a single authority, that automatically initiate an aggregation review under R34.

Authorities declare their aggregate threshold at registration. The threshold must be expressed as `X triggers in Y days`.

### Population determining the threshold range

The aggregate threshold range is determined by the authority's **non-consenting affected population** as declared in the Mechanism Record (§2.3 of the registration form) — *not* by the broader voluntary affected population.

Rationale: civic triggers exist principally to give structural voice to those affected by an authority *without their consent*. People who voluntarily interact with an authority retain their normal exit options (they can decline the relationship, choose alternatives, or remove themselves). People in the non-consenting population have, by definition, no comparable exit. The threshold range must be calibrated to give that population meaningful access to aggregate review, even when they are the smaller of the affected groups.

The framework's bias is toward the largest, most underrepresented, and most structurally exposed population — not the largest population overall. Where these populations diverge, the non-consenting population governs the threshold range.

If an authority has multiple affected populations of different consent levels, the Mechanism Record must declare both populations distinctly (per §2.2 and §2.3), but the §10.7 threshold range is determined by §2.3 only.

### Floor and ceiling

Aggregate thresholds must fall within the proportional bounds shown below. Bounds are tied to the authority's declared **non-consenting** affected population (Mechanism Record §2.3), per the principle stated above.

| Non-consenting population | Minimum threshold | Maximum threshold |
|---|---|---|
| < 1,000 | 3 in 90 days | 10 in 90 days |
| 1,000 – 100,000 | 5 in 90 days | 25 in 90 days |
| 100,000 – 1,000,000 | 10 in 90 days | 50 in 90 days |
| 1,000,000 – 100,000,000 | 25 in 90 days | 250 in 90 days |
| > 100,000,000 | 100 in 90 days | 1,000 in 90 days |

### Why the bounds scale this way

The bounds scale sublinearly with affected population. A small authority is signaled to be in serious trouble by even a few independent triggers; a larger authority generates more background noise and requires a higher absolute count to indicate organized concern. Per-capita thresholds remain very low across all scales — the ceiling for the largest category is 1,000 in 90 days against an authority affecting 100M+ people, which is a per-capita rate of approximately 0.001 percent per quarter.

### Rationale

The minimum (floor) prevents authorities from declaring such a high threshold that aggregate review becomes practically unreachable. The maximum (ceiling) prevents adversarial filers from gaming a competitor's authority registration with an artificially low threshold that would trigger constant noise.

The default within the bounds is the authority's declaration, with justification recorded in the Mechanism Record.

### Time window flexibility

The 90-day window above is the structural default. Authorities may declare different windows (e.g., 30 days, 180 days) provided the resulting threshold remains proportionally reasonable. Short windows with low counts (e.g., 5 in 7 days) and long windows with high counts (e.g., 200 in 365 days) are both acceptable structurally; the registry does not enforce a single window length.

---

## Section III — Response Time Window

The response time window defines how long the authority has to respond publicly after a stop trigger is filed against it.

### Floor and ceiling

| Bound | Value |
|---|---|
| Minimum | 7 days |
| Maximum | 90 days |
| Default if unspecified | 30 days |

### Why these bounds

7 days is the floor because shorter windows are not realistic for any authority larger than an individual. 90 days is the ceiling because longer windows defeat the purpose of the response clock — by the time response is due, the precipitating concern may have already produced irreversible effects.

The default of 30 days matches the value declared in the existing stop-trigger form. Authorities may declare a shorter window as a public commitment to faster response. Authorities may declare a longer window only with explicit justification recorded in the Mechanism Record.

---

## Section IV — Stop Path Count

The Mechanism Record must declare at least three independent stop paths (per SCBP-03 §1.4).

### Floor

| Bound | Value |
|---|---|
| Minimum | 3 independent paths |
| Maximum | (none) |

The independence of stop paths is a substantive question, not a numerical one. Three paths that all depend on the same authority's internal cooperation are not three independent paths. Stakeholders may challenge the independence of declared paths through the SCBP-08 Challenge mechanism.

---

## Section V — Renewal Interval

Authorities declare their renewal interval at registration.

### Floor and ceiling

| Bound | Value |
|---|---|
| Minimum | 1 year |
| Maximum | 10 years |
| Recommended for high-coercion / novel mechanism | 1–2 years |
| Recommended for moderate scope | 3–5 years |
| Recommended for narrow scope, established function | 5–7 years |

The recommendations are from SCBP-03 §1.6 and are not enforced by the registry. The 10-year ceiling is enforced — no Mechanism Record will be accepted with a renewal interval longer than 10 years.

---

## Section VI — Harm Threshold Coverage

The Mechanism Record §7 declares harm thresholds across categories. The framework's open harm categories (R21) are:

- Bodily harm
- Agency impairment
- Ecological damage
- Generational binding
- Communicative suppression
- Informational sovereignty violations

### Floor

For each harm category that *applies* to the authority's function, at least one measurable threshold must be declared. Categories that do not apply may be marked "Not applicable" with brief justification.

The registry does not adjudicate whether a category applies. An authority that declares "Not applicable" across all categories or across categories that visibly should apply (e.g., a healthcare authority declaring bodily harm "Not applicable") may register, but stakeholders may file a Challenge-class trigger contesting the declarations.

### Threshold validity

Declared thresholds must be measurable — expressed as observable conditions, not intentions. SCBP-03 §1.3 provides examples. The registry checks that declared thresholds are stated as conditions; it does not validate that the conditions are well-chosen.

---

## Section VII — Geographic Reach

The Mechanism Record §6 declares geographic reach. The registry does not impose floors or ceilings on geographic reach itself, but the declaration must be specific. "Wherever needed" or similar non-specific declarations are returned for correction.

Acceptable forms:
- Specific jurisdictions (named cities, counties, states, countries)
- Defined geographic areas (e.g., "the contiguous United States," "Western Europe as defined by [reference]")
- Global, with explicit acknowledgment

Unacceptable forms:
- Undefined or expansive language ("as needed," "wherever applicable," "global presence")

---

## Section VIII — Coercive Ceiling

The Mechanism Record §6 declares coercive ceiling. The registry does not impose floors or ceilings on coercive intensity itself, but the declaration must be specific and bounded.

Acceptable forms:
- Specific actions (fines up to $X, suspension up to Y days, license revocation, etc.)
- Specific maximum severity (e.g., "may issue civil penalties; may not detain or restrict movement")

Unacceptable forms:
- Open-ended language ("such measures as may be necessary," "appropriate enforcement actions")
- Self-modifying language ("up to and including any action authorized by [external authority]")

---

## Section IX — Validation Logging

Every validation event is logged publicly:

- Submission received (timestamp)
- Validation result (accepted / returned with specific bounds-violations listed)
- If returned, the resubmission (if any) and its validation result

The validation log is part of the registry's permanent record. Declarations that pass validation are not endorsed by the validation log — the log records only that the declaration met the structural bounds defined in this document.

---

## Section IX-A — Type 1 Compensation Structure (form §6.1)

Type 1 dependencies must declare compensation structure using the enumerated values in form §6.1. Free-text-only declarations are returned for correction.

Compensation structures `revenue_share` and `outcome_tied` are themselves capture risk signals under R03 (Institutional Capture Prohibition) and R66 (Anti-Proxy Substitution). Declarations using these structures must include:
- Specific percentage or formula
- The outcome metric the compensation is tied to
- Whether the structure was approved by the authority's governance body
- Whether the structure has been reviewed for R66 proxy concerns

Authorities operationalizing Type 1 dependencies under `revenue_share` or `outcome_tied` arrangements are flagged in the registry index for stakeholder attention. This is not an evaluative determination; it is a structural disclosure.

---

## Section IX-B — External Authority Operationalization (form §6.8)

Each entry in §6.8 requires:
- External authority name (or category if identity is restricted)
- Decision type the external authority makes
- How the decision is operationalized within the registering authority
- Whether affected parties can distinguish the registering authority's decision from the external authority's

Form submissions that declare R72-relevant operationalization without these four elements are returned for correction.

If the registering authority operationalizes external decisions but declares §6.8 as "none," and a subsequent civic trigger or stakeholder review surfaces undeclared operationalization, the resulting finding is a Disclosure Completeness Assertion violation under §12.1.

---

## Section IX-C — Metric Publication Status (form §7.1)

Each declared metric in §7.1 must indicate publication status across three dimensions:
- Aggregate publication (statistical summaries): Y/N
- Individual publication (specific case data): Y/N
- Methodology publication (computation/application logic): Y/N

Aggregate-N + Methodology-N combinations are flagged as R67 (Minimum Auditability Floor) concerns. The registry does not reject these declarations; it surfaces them for stakeholder review.

Aggregate-N + Individual-N + Methodology-N for any metric materially influencing outcomes is a presumptive R79 (Metric Completeness) failure and triggers automatic provisional review.

---

## Section IX-D — Trade-Secret / Confidentiality Declarations (form §8.6)

Trade-secret declarations must specify:
- Category of restricted information
- Source of restriction (vendor contract, regulatory restriction, competitive harm, statutory privilege, other)
- Auditability mitigation in place
- Specific R67 floor commitment despite restriction

A §8.6 declaration claiming "trade secret" without specifying source is returned for correction.

Trade-secret claims that effectively prevent independent evaluation of:
- Scope, or
- Effect, or
- Harm thresholds, or
- Dependencies, or
- Reversibility, or
- Stop capability

constitute R67 floor violations and trigger automatic provisional review regardless of restriction source.

---

## Section IX-E — R67 Minimum Auditability Floor (form §§3, 4, 5, 6, 7, 9, 10)

R67 (Minimum Auditability Floor) requires that no authority operate below a non-waivable level of auditability sufficient to evaluate eight dimensions: scope, effect, harm thresholds, dependencies, derived outputs, reversibility, expiration, and stop capability. R67 does not specify what minimum disclosure constitutes "sufficient." This section defines the structural floor — what a Mechanism Record must contain in each dimension to be accepted. It does not adjudicate substantive adequacy; that remains with stakeholders through the SCBP-08 Challenge mechanism. Substantive adequacy below the structural floor results in registration rejection. Substantive adequacy above the floor but visibly thin can be challenged.

The floor applies to the form sections that already operationalize each R67 dimension. The registry validates form completion against this schedule.

### Dimension 1 — Scope (form §§1.2, 3.1, 3.2, 3.3, 3.4)

Required minimum elements:
- A functional description (not categorical) of what the authority can compel, restrict, allocate, or impose
- A specific declaration of geographic reach per Section VII of this document
- A specific declaration of coercive ceiling per Section VIII of this document
- A bounded resource ceiling (budget, staffing, or operational capacity)
- Explicit exclusions for at least four of the form's five exclusion categories (geographic, action, data, procedural, other)

A Mechanism Record that completes §§1.2 and 3.1–3.4 with specific bounded values meets the floor for this dimension. A Record that returns "as needed," "appropriate," "varies," or any non-bounded language to a required field fails the floor and is returned for correction.

### Dimension 2 — Effect (form §§1.3, 3.5, 7.1)

Required minimum elements:
- A declaration of authority classification (direct, indirect, or both) under §1.3
- A declaration of indirect-influence boundaries under §3.5 if the authority is classified as indirect or both, identifying the categories of decision the authority's outputs shape
- A declared metric set under §7.1 sufficient to explain observable outcomes within the authority's declared scope

A Mechanism Record that classifies as indirect (§1.3) without populating §3.5, or that declares scope under §3 inconsistent with the metric set under §7.1, fails the floor for this dimension.

### Dimension 3 — Harm thresholds (form §§4.1–4.7)

Required minimum elements:
- For each of the six R21 harm categories (bodily harm, agency impairment, ecological damage, generational binding, communicative suppression, informational sovereignty), either at least one measurable threshold per Section VI of this document, or an explicit "Not applicable" declaration with brief justification
- At least one declared threshold across all categories total — a Mechanism Record that declares "Not applicable" to all six R21 categories fails the floor regardless of justification, on the grounds that any authority capable of being registered necessarily produces effects that fall under at least one harm category
- §4.8 threshold change-log commitment must be marked

A Mechanism Record with one or more harm categories returning a threshold stated as an intention rather than a measurable condition (per Section VI) fails the floor for that category.

### Dimension 4 — Dependencies (form §§6.1, 6.2, 6.3, 6.4, 6.5)

Required minimum elements:
- §6.1 Type 1 dependencies enumerated, or "None" declared with justification
- §6.2 Type 2 dependencies enumerated, or "None" declared with justification
- §6.3 Type 3 dependencies enumerated, or "None" declared with justification
- §6.4 capture risk identification declared (Yes / No), with the categories of capture risk listed if Yes
- §6.5 reversibility-affecting dependencies enumerated

A Mechanism Record returning "None" to all four dependency-type fields without justification fails the floor on the grounds that any authority operating at the scale required for registration necessarily has at least one external dependency in some category.

### Dimension 5 — Derived outputs (form §§3.5, 6.8, 7.1)

Required minimum elements:
- §3.5 indirect-influence boundaries declared if the authority's outputs are read, used, or operationalized by other parties
- §6.8 external authority operationalization completed per Section IX-B of this document, or "None" declared with justification
- §7.1 metric publication status declared per Section IX-C of this document for each metric

A Mechanism Record that declares no derived outputs but produces outputs read by other parties (publications, scores, classifications, recommendations) fails the floor on the grounds of metric incompleteness.

### Dimension 6 — Reversibility (form §§9.1, 9.2, 9.3, 9.4, 9.5, 9.6, 9.7)

Required minimum elements:
- §9.1 estimated dismantling time declared as a specific duration
- §9.2 dismantling process described in concrete steps
- §9.3 entrenchment factors declared, or "Minimal / None" declared with justification
- §9.4 data disposition declared
- §9.5 downstream effect reversibility declared per R63
- §9.6 replacement feasibility addressed
- §9.7 reversibility verification status declared (rehearsed, simulated, planned, or not yet attempted)

A Mechanism Record returning "Indefinite" or "Not applicable" to §9.1, or "None / Not applicable" to §9.2 without justification, fails the floor.

### Dimension 7 — Expiration (form §§10.1–10.10)

Required minimum elements:
- §10.1 authorizing body named
- §10.2 date of authorization declared
- §10.3 expiration date declared as a specific date
- §10.4 renewal interval within the bounds set in Section V of this document
- §10.5 renewal evidence declaration for all five domains
- §10.6 necessity-decay acknowledgment marked
- §10.7 aggregate trigger threshold within the bounds set in Section II of this document
- §10.9 response time window within the bounds set in Section III of this document

A Mechanism Record missing any of these elements is returned for correction.

### Dimension 8 — Stop capability (form §§5.1, 5.2, 5.3, 5.4, 5.5, 5.6)

Required minimum elements:
- At least three independent stop paths declared per Section IV of this document
- For each stop path: activator, trigger condition, definition of "stopped," independence justification, and post-stop review process and timeline
- §5.4 confirmation of no penalty for activating stop
- §5.5 stop-path independence verification
- §5.6 civic trigger acknowledgment

A Mechanism Record declaring three stop paths that all depend on the authority's internal cooperation, or three stop paths whose independence cannot be substantiated by the structure declared, fails the floor regardless of the count.

### Application

The registry validates each Mechanism Record against this schedule at registration and at each renewal. Records that pass the schedule meet the structural floor; passing the schedule is not endorsement of substantive adequacy. Stakeholders may file Challenge-class triggers under SCBP-08 contesting whether substantive adequacy is met.

A Record that passes the floor but is contested through a sustained pattern of substantively-grounded Challenge findings becomes a candidate for floor revision: the schedule above is amendable through the registry's amendment process, and persistent pattern-of-challenges is one signal the schedule may be too low for the dimension.

---

## Section X — Amendment

This document is subject to the registry's amendment process (Registry Charter §9). Amendments may adjust bounds, add categories, or refine validation rules.

Amendments take effect prospectively. Mechanism Records registered before an amendment are not retroactively re-validated, but at next renewal must comply with the bounds in effect at that time.

If an amendment would have rejected a currently registered Mechanism Record, that fact is logged but does not by itself invalidate the registration. The authority is notified and given until next renewal to bring declarations into compliance.

---

## Section XI — Relationship to Other Documents

This document operationalizes the registration validation referenced in:

- SCBP-03 — Operations Manual, Stage 1 (Authorization)
- SCBP-08 — Civic Trigger Protocol, where Challenge-class triggers may contest declared values
- Registry Charter §6, where the operator's role in validation is constrained

If conflict exists between this document and a Mechanism Record, this document governs. If conflict exists between this document and the Structural Constitution, the Constitution governs. If conflict exists between this document and the Registry Charter, the Charter governs the registry's operating role; this document governs validation criteria.

---

*SCBP-09 — Registry Acceptance Standards — Operational Layer*
*All authority governed solely by the Structural Constitution (SCBP-04)*

---

> *This document is part of a thought experiment. The "Bounded Power Foundation" is a construct of the experiment, not an organization. Nothing described here is operating. See [HOW-TO-READ-THIS.md](../HOW-TO-READ-THIS.md) for the full framing.*
