# Registration Form

## Bounded Power Framework — Structural Disclosure Form

> *v1: Initial diagnostic disclosure form. Framework-organized.*
> *v2: Embedded worked examples added to diagnostic prompts in Sections 1-9.*
> *v3: §10.7 amended to reference non-consenting affected population per SCBP-09 §II amendment (Round 1 stress test finding).*
> *v4: Final stress-test revisions across Sections 1, 2, 3, 4, 6, 7, 8 (Round 1-3 stress test findings).*

---

## What this form is

This is the Bounded Power Framework's Registration Form. Completing it produces a structured public document — a Mechanism Record — that surfaces an authority's scope, harm thresholds, dependencies, stop paths, and oversight gaps in a way most disclosure regimes never force into one place.

The form is organized around what the framework wants visible — not around how authorities typically describe themselves. Some sections ask questions an authority's own internal documents may not address. That is intentional. The framework's structural logic surfaces patterns of capture, drift, and proxy substitution that are easy to miss from inside.

Each section begins with a short *diagnostic prompt* — questions to consider before answering. The prompts are scaffolding for thinking; they are not part of the record. The record is what is written in the answer fields.

Where a section references specific constitutional rules (e.g., "R12, R39"), those references are footnoted at the end of the section. They are provided so readers can consult the underlying rule for context. They are not a citation requirement.

---

## Who fills it out

This form supports two kinds of users.

**Authorities registering themselves.** An authority that chooses to enter the Bounded Power Framework files this form as a public act of structural disclosure. The completed record enters the registry as an official Mechanism Record. The honesty assertions in §12 are binding commitments by the filing authority.

**Citizens, journalists, researchers, and civic actors producing structural diagnostics.** Anyone can use this form to produce a structured analysis of an authority that affects them, using publicly available information. Diagnostic uses do not require the authority's cooperation. Completed diagnostics are labeled `TEST / NOT AN OFFICIAL REGISTRATION` and filed under the `SCBP-REG-TEST-{IDENTIFIER}` naming pattern. The honesty assertions in §12 are reframed as "this reflects what could be verified from public sources; gaps are marked `UNKNOWN`."

The same form, the same rules, and the same SCBP-09 numerical bounds apply to both. The form's diagnostic power does not depend on the authority's cooperation.

For a guided way to complete a citizen diagnostic, see [00-Reading/AI-Registration-Bundle.md](../00-Reading/AI-Registration-Bundle.md).

---

## Before you begin — three things to know

1. **Filings are public the moment they are received.** There is no review queue; submissions are not edited for content. Once filed, a record can be updated but never deleted.

2. **The registry validates structural bounds, not the narrative.** Numerical declarations (response windows, aggregate thresholds, harm threshold values) must fall within the bounds defined in *SCBP-09 — Registry Acceptance Standards*. Out-of-bounds declarations are returned for correction. The registry does not assess whether descriptive claims are accurate.

3. **What is not disclosed is itself a finding.** This form ends with an explicit honesty assertion. The framework's response to undisclosed-but-discoverable information is structural, not punitive — but the gap becomes a public finding when it surfaces.

---

## How to submit

Submissions are made by opening a pull request on this repository, adding the completed Mechanism Record to [04-Registry/](../04-Registry/).

- Authority self-registrations follow the naming pattern `SCBP-REG-{NNNN}.md`
- Citizen diagnostics follow the naming pattern `SCBP-REG-TEST-{IDENTIFIER}.md`

There is no submission fee, no review queue, and no editorial gatekeeping. The repository's maintainers verify that the submission uses the form, meets SCBP-09 numerical bounds, and is labeled correctly. They do not assess content accuracy.

---

## SECTION 1 — What is this authority?

> *Diagnostic prompt:* Describe what your mechanism can actually do to people, institutions, or systems — not what it is called or how it is categorized. Authority is determined by functional effect, not by name (R04). If renaming or restructuring this mechanism would not change what it does, then this section should describe the underlying function. If you cannot describe what your mechanism does in plain functional terms, you cannot define its limits.
>
> *Example:* "This mechanism is the Riverbend Parking Enforcement Bureau" is a name, not a function. "This mechanism issues parking citations within city limits, may immobilize vehicles for unpaid balances ≥$300, and may tow after 72 hours of immobilization" is a function. Write the second kind.

```
1.1 — Mechanism name (the public identifier, not the legal name):

1.2 — Functional description:
     What can this mechanism compel, restrict, allocate, require, or impose?
     Describe in plain language what it actually does.

1.3 — Authority classification:
     Is this authority direct (issues binding directives), or indirect
     (advisory, scoring, recommending, scoring, ranking, routing,
     filtering, allocating, or otherwise materially shaping decisions
     made by others)?
     [ ] Direct
     [ ] Indirect — describe the form of indirect influence:
     [ ] Both

1.4 — Domain (select primary; mark others if applicable):
     [ ] Government
     [ ] Economic
     [ ] Technology
     [ ] Infrastructure
     [ ] Data / Information
     [ ] Education
     [ ] Healthcare
     [ ] Cultural / Religious
     [ ] Voluntary association
     [ ] Other (describe):

1.5 — Statutory or constitutional basis (the upstream authority/authorities
      under which this mechanism operates — if any). For complex
      authorities operating under multiple frameworks (e.g.,
      federal + state + accreditation), list each separately:
```

*Rules addressed: R04 (Authority Classification Stability), R58 (Indirect Authority Recognition).*

---

## SECTION 2 — Who can this authority act upon?

> *Diagnostic prompt:* The framework distinguishes between people who chose to interact with this authority and people who did not. Non-consenting affected parties are weighted more heavily under R26 (Non-Participant Harm Floor). Be careful not to confuse "people we serve" with "people we can act upon." A parking enforcement bureau acts upon everyone who parks within city limits, not only those who pay parking fees.
>
> *Example:* A consumer-protection regulator's "served" population might be the consumers it represents. But the population it acts *upon* is the regulated industry — companies that did not consent to the regulator's existence. Both are affected; only the second is non-consenting.

```
2.1 — Affected party categories (select all that apply):
     [ ] General public (no opt-in required to be affected)
     [ ] Residents of defined geographic area (specify):
     [ ] Customers / voluntary service users
     [ ] Members (voluntary affiliation)
     [ ] Employees / workers
     [ ] Students / educational participants
     [ ] Patients / healthcare recipients
     [ ] Regulated industry participants
     [ ] Criminal justice involved individuals
     [ ] Children / minors
     [ ] Vulnerable populations (specify):
     [ ] Future generations (long-duration environmental or financial impact)
     [ ] Non-consenting third parties (describe):

2.2 — Approximate number of people directly affected:

2.3 — Of the affected population, what number/proportion are
      non-consenting (i.e., are subject to this authority without
      opting in):

      *Note on voluntary-but-stuck populations:* Affiliation that
      requires substantial cost to exit (financial, social,
      professional, geographic, network-effect) is not meaningfully
      voluntary in the framework's sense. If your authority operates
      over a population that is technically voluntary but
      structurally cannot exit, declare that population as
      non-consenting. The relevant test is not "did they sign up"
      but "can they meaningfully leave."

2.4 — Vulnerable population specifics:
      Does this authority act upon any of the following? If yes,
      describe the protective measures in place:
      [ ] Children (under age of majority)
      [ ] Patients during medical care
      [ ] Detained or confined persons
      [ ] Persons in coercive economic relationships (e.g., employees
          where the authority is the employer)
      [ ] Persons unable to advocate for themselves due to disability,
          incapacity, or circumstance
```

*Rules addressed: R14 (Non-Participant Exposure Mapping), R26 (Non-Participant Harm Floor).*

---

## SECTION 3 — What can it do, and what can it not do?

> *Diagnostic prompt:* Define the boundary explicitly. Anything not listed as authorized is by default not authorized. R35 (Scope Narrowing Default) means ambiguity will be resolved against expansion — so over-disclosure is structurally safer than under-disclosure. Geographic and coercive declarations must be specific (per SCBP-09 §VII and §VIII). "Wherever needed" or "appropriate enforcement actions" will be returned for correction.
>
> *Example of unacceptable specificity:* "Civil penalties as authorized by law." The framework cannot bound this — *what law, what penalties, what ceiling?* Acceptable: "Civil penalties up to $250 per violation per Riverbend Municipal Code §11-208."
>
> *Example of an exclusion that proxies a capture risk:* A municipal enforcement bureau excluding "contractor relationships where compensation is structured as a percentage of citation revenue" addresses R66 (Anti-Proxy) before any citation is issued. This kind of structural pre-commitment is what §3.4 is designed to capture.

```
3.1 — Geographic reach:
      Geographic specificity (select one):
      [ ] Single municipality (specify):
      [ ] Multi-municipality (specify each):
      [ ] Single county/parish:
      [ ] Multi-county (specify each):
      [ ] Single state/province:
      [ ] Multi-state/multi-province (specify):
      [ ] Single nation (specify):
      [ ] Multi-national (specify):
      [ ] Global, with acknowledgment of jurisdictional limits

3.2 — Coercive ceiling:
      What is the strongest action this authority can take against
      a person, organization, or system? List specific actions and
      their numerical or temporal limits.

3.3 — Resource ceiling:
      Maximum operating budget:
      Maximum staff (FTE):
      Maximum data systems and data volume:

3.4 — Explicit exclusions — what this authority may NOT do:
      List by category. Each exclusion is a structural commitment;
      the registry will treat any action outside the listed
      authorities as outside the authority's scope.
      [ ] Geographic exclusions:
      [ ] Action exclusions (what enforcement actions are off-limits):
      [ ] Data exclusions (what data may not be collected, retained,
          or shared):
      [ ] Procedural exclusions (e.g., may not enter into
          revenue-share contractor relationships):
      [ ] Temporal exclusions (e.g., may not act outside
          declared operational hours):
      [ ] Other exclusions:

3.5 — Indirect influence boundaries:
      If this authority is indirect (per §1.3), what outputs does
      it produce that materially influence decisions made by others
      (scores, rankings, classifications, recommendations,
      authorizations)?
      For each output: who uses it, and what decision does it
      shape?

3.6 — Anti-proxy declaration:
      The framework prohibits achieving restricted effects through
      proxies (R66, R74). For each restricted effect this authority
      cannot directly produce, identify any proxies, statistical
      substitutes, or behavioral indicators that this authority
      will not use to produce equivalent outcomes:
```

*Rules addressed: R04 (Functional Effect), R35 (Scope Narrowing Default), R55 (Fragmentation), R66 (Anti-Proxy), R74 (Proxy Equivalence Expansion). SCBP-09 §VII (Geographic Specificity), §VIII (Coercive Ceiling Specificity).*

---

## SECTION 4 — What harms can it cause?

> *Diagnostic prompt:* The framework's harm categories (R21) are six. For each one, you must either declare a measurable threshold that triggers a stop review, or mark "Not applicable" with justification. A measurable threshold is an observable condition (e.g., "particulate matter exceeds 150 µg/m³ averaged over 24 hours"), not an intention (e.g., "when air quality becomes harmful"). The framework's harm categories are *open* — the listed six are the floor, not the ceiling. If your authority can cause harm not captured by the six categories, declare an additional threshold.
>
> *Note on authorized harm:* For authorities whose authorized function predictably involves some level of harm (e.g., medical treatment, criminal justice supervision, hazardous occupational settings, surgery), distinguish *normal and expected* adverse effects from *excess* harm. Thresholds should target excess — rates exceeding peer benchmarks, preventable harm, or harm that exceeds informed consent. Normal expected harm (chemotherapy side effects, surgical recovery, supervised probation restrictions) is the cost of operation, not a threshold. Excess harm (preventable infections beyond peer rates, restraint-related injury, due process failures) is what these thresholds capture.
>
> *Example of a measurable threshold:* "If more than 8% of citations issued in any rolling 30-day period are subsequently dismissed by the Municipal Court for procedural error." Observable, time-bounded, automatic.
>
> *Example of an unmeasurable threshold:* "If enforcement becomes unfair." Untestable, judgment-dependent, cannot trigger anything reliably.
>
> *Example of "not applicable" done well:* "Bodily harm — not applicable. The Bureau's authority is limited to civil citations, vehicle immobilization, and towing. None of these actions involve direct physical contact with persons. If a stop trigger contests this, the contesting party may file a Challenge under SCBP-08." Justified, structural, appealable.

```
4.1 — Bodily harm threshold:
      Threshold (measurable condition that triggers review):
      [ ] Not applicable — justification:

4.2 — Agency impairment threshold:
      (Restrictions on someone's ability to communicate, participate
      in governance, access correction processes, or exercise
      rights)
      Threshold:
      [ ] Not applicable — justification:

4.3 — Ecological damage threshold:
      Threshold:
      [ ] Not applicable — justification:

4.4 — Generational binding threshold:
      (Commitments that bind future generations to obligations they
      cannot revise)
      Threshold:
      [ ] Not applicable — justification:

4.5 — Communicative suppression threshold:
      (Suppression, distortion, or monopolization of information
      others need to protect themselves or participate)
      Threshold:
      [ ] Not applicable — justification:

4.6 — Informational sovereignty threshold:
      (Permanent or indefinite informational indexing of individuals)
      Threshold:
      [ ] Not applicable — justification:

4.7 — Additional harm thresholds (any harm category not covered above):
      Category name:
      Threshold:

4.8 — Threshold change-log commitment:
      The authority commits to logging all threshold modifications
      publicly with justification and impact analysis at the time of
      change (per R08).
      [ ] Yes — committed
      [ ] Cannot commit — explain:
```

*Rules addressed: R07 (Pre-Authorization Harm Threshold Requirement), R08 (Threshold Registry and Change Log), R21 (Open Harm Categories), R22 (Informational Sovereignty Constraint).*

---

## SECTION 5 — What stops it?

> *Diagnostic prompt:* A mechanism that cannot be stopped is not a mechanism — it is a permanent condition. Stop paths must be (a) at least three, (b) genuinely independent of the authority itself, and (c) costless to activate (R15, R32, R33). "Independent" means: if one stop path is blocked or captured, the others still function. Stop paths that all rely on internal cooperation are not multiple stop paths; they are one stop path with three names. Stakeholders evaluating your registration will press on independence — declare it carefully.
>
> *Example of three genuinely independent stop paths for a small-city authority:*
> 1. *City Council resolution* — Council can suspend operations by majority vote. Council exists outside the authority's reporting structure.
> 2. *Court order* — Municipal Court can order cessation on motion of any party with standing. Court is structurally independent of the executive branch.
> 3. *Citizen Review Office* — independent body of three members, no current or recent service in the authority. May order suspension at specific sites or by specific officers.
>
> *Example of three stop paths that look independent but are not:*
> 1. The authority's own director may suspend operations.
> 2. The authority's own internal complaints department may recommend suspension.
> 3. The authority's parent agency may revoke authorization.
>
> All three rely on the authority itself or its parent. None survives capture or refusal at the top of the chain. This is one stop path with three labels.

```
For each stop path, complete the following:

STOP PATH 1
  Who can activate it (must include parties outside this authority):
  Trigger condition (threshold-based, judgment-based, or both):
  What "stopped" means specifically (operations halt? authorization
  lapses? data collection ceases? all three?):
  Independence justification (why is this stop authority structurally
  independent of this authority — not just nominally?):
  Post-stop review process and timeline:

STOP PATH 2
  [same fields]

STOP PATH 3
  [same fields]

5.4 — Penalty for activating stop:
      The framework requires that no procedural, financial, or
      reputational penalty attach to good-faith stop activation
      (R15, R33).
      [ ] Confirmed — no penalty applies
      [ ] Exception claimed — describe specifically:

5.5 — Stop-path independence verification:
      Can the stop paths above be activated if the authority itself
      refuses to cooperate?
      [ ] Yes — explain how:
      [ ] No — this is a structural finding; explain remediation plan:

5.6 — Civic trigger acknowledgment:
      The authority acknowledges that any party affected by it may
      file a civic trigger (Tripwire, Challenge, or contribute to
      Aggregate) per SCBP-08, and commits to publicly responding
      within the response window declared in §10.
      [ ] Acknowledged
```

*Rules addressed: R13 (Unplug-Ability), R15 (Stop Friction Prohibition), R23 (Tripwire Protocol), R24 (Redundant Stop Activation), R32 (Independent Stop Authority), R33 (No Penalty for Good-Faith Challenge).*

---

## SECTION 6 — What does it depend on?

> *Diagnostic prompt:* Dependencies create capture risk and reversibility risk. The framework distinguishes three types:
> - **Type 1** — entities whose outputs you operationalize as if they were your own (R64 brings them inside your authority for compliance purposes)
> - **Type 2** — independent authorities you have a structural relationship with
> - **Type 3** — infrastructure dependencies whose failure would prevent you from being interrupted, stopped, or audited within declared windows
>
> Complete dependency mapping is structurally unattainable; the form asks for what is *known* and *stop-path-relevant*, not for an exhaustive list of every vendor.
>
> *Example of correctly distinguishing types:*
> - A boot-and-tow contractor working under flat-fee terms is a Type 1 dependency — their actions are operationalized as the bureau's own.
> - The Municipal Court that hears citation contests is a Type 2 dependency — independent authority with a structural relationship.
> - The license-plate-recognition camera vendor is a Type 3 dependency — if they refuse to export data, the bureau cannot demonstrate compliance with the 90-day retention threshold, and stop path 2 (court order based on retention violation) is compromised.
>
> Notice the cloud provider hosting the bureau's website is *not* on this list — its failure is operationally bad but does not compromise stop paths. Type 3 is narrow on purpose.

```
6.1 — Type 1 dependencies (operational extensions acting under
      this authority):
      For each: name, what they do under this authority, contractual
      relationship, and compensation structure (select one — note
      that revenue-share and outcome-tied are themselves capture
      risks under R03/R66):
      [ ] Flat fee per action
      [ ] Hourly / project-based
      [ ] Retainer
      [ ] Revenue share — describe percentage and source
      [ ] Outcome-tied — describe specific outcomes
      [ ] Uncompensated / volunteer
      [ ] Other — describe

6.2 — Type 2 dependencies (independent authorities with a
      structural relationship to this one):
      For each: name, nature of relationship, whether their decisions
      are upstream (we depend on theirs) or downstream (they depend
      on ours).
      *If your authority has no Type 2 dependencies, state so
      explicitly — this is a legitimate disclosure for voluntary
      or fully-independent authorities.*

6.3 — Type 3 dependencies (infrastructure whose failure would
      compromise stop paths or auditability):
      For each: name, what specifically fails if this dependency
      is lost, what stop path or audit capability is compromised:

6.4 — Capture risk identification:
      Does any single funding source, contractor, vendor, or partner
      provide more than 33% of operating support, OR control critical
      data, OR provide infrastructure that cannot be replaced within
      90 days?
      [ ] No
      [ ] Yes — identify and describe the structural risk:

6.5 — Reversibility-affecting dependencies:
      Which dependencies, if removed, would make it harder to
      dismantle this authority within its declared dismantling
      timeline (§9.1)?

6.6 — Coordination disclosures:
      Does this authority coordinate, synchronize, or align
      operationally with any other authority in ways that, taken
      together, function as a single shared authority system (R55,
      R59)? If yes, name and describe.

6.7 — Disclosure completeness assertion:
      The authority asserts that the dependencies listed above
      include all Type 1, Type 2, and stop-path-relevant Type 3
      dependencies known to the authority at the time of
      registration. The authority acknowledges that complete
      dependency mapping is structurally unattainable, and that
      newly-discovered dependencies will be reported as
      Mechanism Record updates. Undisclosed but discoverable
      dependencies are themselves a Framework finding.
      [ ] Asserted

6.8 — External authority operationalization (R72):
      Identify any external authority (vendor algorithm, payer
      decision system, regulatory determination, contractor judgment)
      whose outputs you operationalize within your authority surface,
      such that the affected party experiences your authority but
      the underlying decision is external. For each:
      - Name of external authority
      - What they decide
      - How their decision becomes operationalized as your authority
      - Whether the affected party can distinguish your decision
        from theirs
      *If your authority does not operationalize any external
      decisions, state so explicitly. R72 (External System Equivalence
      Rule) treats operationalized external decisions as part of your
      authority for compliance purposes.*
```

*Rules addressed: R03 (Institutional Capture Prohibition), R12 (Dependency and Capture Review), R39 (Structural Dependency Disclosure), R50 (Capture Risk Monitoring), R55 (Fragmentation), R59 (Functional Continuity), R61 (Anti-Entrenchment), R64 (External Circumvention), R72 (External System Equivalence).*

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

> *Diagnostic prompt:* R79 (Metric Completeness Requirement) is one of the framework's hardest-edged rules. If observed outcomes cannot be explained by the declared metric set, undeclared influence is presumed, and that constitutes non-compliance. This section asks you to declare *everything* that materially shapes what your authority does — not only the metrics you formally report on, but the signals, classifications, and inputs that practically influence decisions. Including: anything an algorithm ingests, anything a human decision-maker considers, anything that determines prioritization.
>
> *Example of a metric that should be declared but often isn't:* A parking enforcement bureau's officers receive monthly patrol assignments. The assignment algorithm uses a "high-need zone" classification based on prior citation density. This classification materially influences where citations are issued — and therefore who is cited. It must be declared, even though it does not appear on any public dashboard.
>
> *Example of an indirect signal that materially influences outcomes:* Officers' performance reviews include "citations issued per shift" as a comparison metric. This is not a quota, but it influences enforcement intensity. It is a §7.2 disclosure, not a §7.1 declared metric — but it must still be disclosed.

```
7.1 — Declared metrics:
      List all metrics, variables, signals, classifications, and
      decision inputs that materially influence the authority's
      outcomes. For each: name, source, role in decision-making,
      and publication status across three dimensions:
      - Aggregate publication: [Y/N] (statistical summaries)
      - Individual publication: [Y/N] (specific case data)
      - Methodology publication: [Y/N] (how the metric is computed
        or applied)

7.2 — Indirect signals:
      Are there factors that influence outcomes informally — through
      staff judgment, organizational culture, prioritization
      practices, or pattern-of-operation — that do not appear in
      formal metrics? If yes, describe.

7.3 — Algorithmic decision systems:
      Does this authority use, rely upon, or operationalize
      algorithmic, automated, or AI-based decision systems? If yes:
      [ ] Yes — name the system, describe what decisions it
          influences, identify the vendor/source, and describe
          auditability provisions:
      [ ] No

7.4 — Outcome-versus-declaration check:
      The authority commits to maintaining a process by which
      observed outcomes are periodically compared to declared
      metric set, with discrepancies investigated and surfaced
      (per R79, R80).
      [ ] Committed — describe process:
      [ ] Cannot commit — explain:
```

*Rules addressed: R58 (Indirect Authority Recognition), R67 (Minimum Auditability Floor), R79 (Metric Completeness), R80 (Outcome Dominance Principle).*

---

## SECTION 8 — How is this authority watched?

> *Diagnostic prompt:* Authority must be auditable, monitored for drift, and observable in its operations (R38, R41, R44, R67, R81). This section is where the authority commits to *being watchable* — not just to disclosing, but to remaining accessible to ongoing evaluation. Closed audits, restricted interfaces, and "trade secret" exemptions reduce auditability and may not eliminate the minimum floor (R67).
>
> *Example of a real drift-monitoring mechanism:* The bureau publishes quarterly enforcement statistics broken down by census tract. If any tract's citation rate exceeds 3.0x the city-wide average for two consecutive quarters, an automatic review is initiated by the Citation Review Office (a Stop Path 3 trigger). The mechanism is operated by an independent body, runs automatically, and produces public output.
>
> *Example of drift monitoring that fails the bar:* "Bureau leadership reviews enforcement statistics monthly and addresses any concerns." Internal, judgment-dependent, no public output, no automatic trigger. Not auditable.

```
8.1 — Drift monitoring mechanism:
      What mechanism does this authority use to detect expansion
      beyond its original mandate? Who operates that mechanism
      and how often is it run?

8.2 — Capture risk monitoring:
      What ongoing monitoring detects regulatory or structural
      capture (e.g., revolving-door risk, contractor dependency
      drift, funding concentration changes)?

8.3 — Audit interfaces:
      What interfaces, data exports, or evaluation capabilities are
      available to independent reviewers? Specifically:
      - What data is published proactively?
      - What data is available on request?
      - What data is restricted, and on what grounds?

8.4 — Adversarial exposure (R81):
      Can an external party with no insider access evaluate this
      authority's scope, effect, harm thresholds, dependencies,
      reversibility, and stop capability? If not fully, identify
      the gaps.

8.5 — Known structural failure modes:
      What failure modes does this authority know about — failure
      modes that have been observed in similar authorities, in this
      authority's prior versions, or in this authority's design
      assumptions? (R42 requires these be documented; this is the
      registration declaration.)

8.6 — Trade-secret / confidentiality declarations:
      If portions of your authority's operations cannot be fully
      disclosed for reasons of trade secret, vendor IP, regulatory
      restriction, or other confidentiality:
      - What category of information is restricted? (algorithm
        internals, methodology details, vendor IP, business data,
        privileged communications, etc.)
      - What is the source of the restriction? (vendor contract,
        regulatory restriction, competitive harm, statutory privilege,
        other)
      - What auditability mitigation is in place despite the
        restriction? (aggregate disclosure, third-party audit,
        regulator review, summary methodology, none)
      - What R67 (Minimum Auditability Floor) commitment can the
        authority make despite the restriction?

      *Note:* R67 establishes a non-waivable floor of auditability
      sufficient to evaluate scope, effect, harm thresholds,
      dependencies, derived outputs, reversibility, expiration, and
      stop capability. Trade secrecy may alter the *form* of
      disclosure but may not eliminate the floor. If your authority
      cannot meet R67 within trade-secret constraints, that is
      itself a structural finding.
```

*Rules addressed: R38 (Transparency Sufficiency), R40 (Authority Surface Mapping), R41 (Institutional Drift Monitoring), R42 (Structural Failure Documentation), R44 (Independent Audit Capability), R50 (Capture Risk Monitoring), R67 (Minimum Auditability Floor), R81 (Adversarial Exposure Requirement).*

---

## SECTION 9 — How does it end?

> *Diagnostic prompt:* All authority expires unless renewed (R28). This section is your declaration of how this authority can be wound down. Reversibility is not a theoretical property — it must be demonstrable (R43). If dismantling would create cascading collapse beyond your authorized scope, that is a structural finding under R61 (Anti-Entrenchment).
>
> *Example of an honest entrenchment disclosure:* "The Bureau collects 65% of operating revenue through citation fees. Dissolution requires the city to either replace this revenue or cut city services dependent on it. This dependency is itself a structural finding under R61 and is the subject of the capture-monitoring threshold in §4.7."
>
> *Example of dishonest dismissal of entrenchment:* "Operations could be wound down within 30 days." (Without addressing the revenue dependency, the contractor relationships, or the sunk infrastructure, this declaration is not credible. It will be challenged.)

```
9.1 — Estimated dismantling time:
      How long would full wind-down take from a termination order to
      complete cessation? Express as a number of days, with
      justification.

9.2 — Dismantling process:
      Describe the staged process. What happens in week 1? Months 1-3?
      Months 3-6? When are operations frozen, contracts unwound, data
      archived/destroyed, staff reassigned?

9.3 — Entrenchment factors:
      What factors, if any, would make dismantling harder than the
      timeline above suggests? Examples: budget dependencies, sunk
      infrastructure, contractual obligations with long termination
      windows, downstream systems that operationalize this
      authority's outputs.

9.4 — Data disposition:
      What happens to:
      - Personal data (collected from individuals)?
      - Institutional records?
      - Derived outputs (scores, classifications, decisions
        propagated downstream — see R60, R63, R65)?
      - Audit logs?

9.5 — Downstream effect reversibility:
      What decisions, classifications, restrictions, or records
      produced by this authority have been propagated to other
      systems? On termination, what mechanism reverses or invalidates
      those propagated effects (R63, R65)?

9.6 — Replacement feasibility:
      Could this authority be replaced or dissolved without
      destabilizing services beyond its authorized scope (R51, R61)?
      If not, what are the structural barriers, and what is the plan
      to address them?

9.7 — Reversibility verification:
      Has this authority ever rehearsed dismantling, simulated
      shutdown, or otherwise verified that the declared timeline is
      achievable? If yes, describe. If no, the declaration in §9.1
      is treated as estimated, not verified (R43).
```

*Rules addressed: R27 (Reversibility), R28 (Expiration Default), R43 (Reversibility Verification), R51 (Institutional Replacement Feasibility), R60 (Derived Authority Inheritance), R61 (Anti-Entrenchment), R63 (Downstream Effect Reversibility), R65 (Propagation Duty Requirement).*

---

## SECTION 10 — Authorization, renewal, and trigger declarations

> *Diagnostic prompt:* This section combines the formal authorization details with the framework's structural commitments around expiration, renewal, and civic-trigger response.

```
10.1 — Authorizing body (the entity that legally authorizes this
       mechanism):

10.2 — Date of current authorization:

10.3 — Authorization expiration date:

10.4 — Renewal interval (how often this authority must be
       affirmatively renewed):
       Min: 1 year, Max: 10 years per SCBP-09 §V

10.5 — Renewal evidence declaration:
       At renewal review, this authority commits to providing
       evidence across the following five domains (per SCBP-03 §5.1
       and R47):
       [ ] Scope integrity evidence (comparison of authorized vs.
           operational scope)
       [ ] Harm compliance evidence (threshold monitoring data,
           breach records, response records)
       [ ] Stop path integrity evidence (confirmation that stop
           paths remain functional and independent)
       [ ] Dependency and capture evidence (current dependency
           inventory, change since registration, capture risk
           findings)
       [ ] Reversibility evidence (updated dismantling plan,
           rehearsal records if any)

10.6 — Necessity-decay acknowledgment:
       The authority acknowledges that R62 (Necessity Decay
       Requirement) means continued necessity weakens over time
       unless supported by independently verifiable changes in
       external conditions. The authority commits to demonstrating,
       at each renewal, that scope, dependency, opacity, persistence,
       or downstream impact has been *reducing* over time, unless
       conditions independently require continuation.
       [ ] Acknowledged

10.7 — Aggregate trigger threshold:
       Number of triggers: ___
       Within window of: ___ days
       (Per SCBP-09 §II — bounds depend on declared **non-consenting**
       affected population from §2.3, NOT the broader affected
       population. See SCBP-09 §II proportional table.)

10.8 — Aggregate threshold justification:

10.9 — Response time window:
       Days from a stop trigger filing to required public response: ___
       Min 7, max 90, default 30 per SCBP-09 §III.

10.10 — Response window justification (required if longer than 30
        days):
```

*Rules addressed: R10 (Renewal Decision Rule), R28 (Expiration Default), R36 (Renewal Eligibility Condition), R37 (Renewal Process Independence), R47 (Renewal Evidence Standard), R57 (Expiration Enforcement), R62 (Necessity Decay), R76 (Mandatory Degradation).*

---

## SECTION 11 — What does this authority commit to publishing?

> *Diagnostic prompt:* The framework treats publication as a structural commitment, not a promise of best effort. R17 (Citizen Ledger Output) requires periodic public summaries; R8 (Threshold Registry) requires logging threshold changes; R16 (Interpretation Change Log) requires logging scope reinterpretations. This section captures all publication commitments in one place.

```
11.1 — Citizen ledger publication:
       Frequency:
       [ ] Quarterly  [ ] Annually  [ ] Other:
       Content commitments — the ledger will include:
       [ ] Operating expenditures (high-level)
       [ ] Renewal status
       [ ] Stop events (triggers filed, responses, findings)
       [ ] Structural dependency status (changes since last ledger)
       [ ] Other (specify):

11.2 — Threshold change log:
       This authority commits to publishing all threshold
       modifications publicly within ___ days of change, including
       justification and impact analysis (per R08).

11.3 — Interpretation change log:
       This authority commits to logging all reinterpretations
       affecting scope or thresholds in a publicly auditable log,
       recorded at the time of interpretation (per R16).

11.4 — Renewal process visibility:
       At renewal review, all renewal evidence will be made publicly
       available. The renewal process itself will be conducted by
       parties structurally independent of this authority (R37).
       [ ] Committed

11.5 — Stop event log:
       All stop triggers filed against this authority, all responses,
       and all findings will be permanently recorded in the public
       Mechanism Record.
       [ ] Acknowledged (note: this is a registry-side commitment,
           but the authority confirms it understands)
```

*Rules addressed: R08 (Threshold Registry and Change Log), R16 (Interpretation Change Log), R17 (Citizen Ledger Output), R37 (Renewal Process Independence), R38 (Transparency Sufficiency), R75 (Evidence Integrity Requirement).*

---

## SECTION 12 — Honesty assertions

> *Diagnostic prompt:* This section is the authority's structural commitment to disclosure honesty. The framework is built around making things visible. The authority's commitment here is what makes the rest of the form load-bearing.

```
12.1 — Disclosure completeness assertion:
       I assert that the disclosures in this Mechanism Record reflect
       all information known to the authority at the time of
       registration relating to: scope, affected parties, harm
       thresholds, dependencies, stop paths, decision metrics, and
       structural risk factors.
       [ ] Asserted

12.2 — Update obligation:
       I commit to updating this Mechanism Record when any of the
       following change: declared scope, harm thresholds, stop paths,
       Type 1 or stop-path-relevant Type 3 dependencies, capture
       risk profile, decision metrics, or any field marked [committed]
       in this form. Updates will be filed within 30 days of change.
       [ ] Committed

12.3 — Discoverability acknowledgment:
       I acknowledge that undisclosed-but-discoverable information —
       information that should have been declared at registration but
       was not — is itself a Framework finding when it surfaces, and
       may be the subject of a Challenge-class civic trigger under
       SCBP-08.
       [ ] Acknowledged

12.4 — Burden of proof acknowledgment:
       I acknowledge that R69 (Burden of Proof Reversal) places the
       burden of proving constitutional compliance on this authority,
       not on stakeholders or the registry. Lack of evidence,
       incomplete evidence, or inaccessible evidence results in
       non-compliance findings.
       [ ] Acknowledged

12.5 — Anti-weaponization acknowledgment:
       I acknowledge that the Framework may not be interpreted to
       justify harm that the framework itself is designed to prevent
       (R53). Registration under this framework does not legitimize
       authority that exceeds the framework's structural limits.
       [ ] Acknowledged
```

*Rules addressed: R53 (Anti-Weaponization Clause), R69 (Burden of Proof Reversal), R75 (Evidence Integrity Requirement).*

---

## SECTION 13 — Submitter

> *Note: Submitter information is part of the registry's metadata but is not part of the published Mechanism Record. Only "Registered by [authority name]" appears in the public record. Submitter contact details are retained by the registry for follow-up only.*

```
Submitted by (full name):
Role / position within or relationship to the authority:
Date:
Contact for follow-up (email or other):
```

---

## What happens after submission

1. The submission is logged immediately as a public GitHub Issue.
2. The registry validates structural bounds (per SCBP-09). Out-of-bounds declarations are returned within 7 days for correction.
3. A Mechanism Record is created and assigned a unique ID in the format `SCBP-REG-####-v1`.
4. The Mechanism Record is published in the registry within 7 days of acceptance (per Charter §7).
5. The submitter is notified of the assigned ID.

Registration does not constitute endorsement, certification, or validation by the Bounded Power Foundation. It creates a public record that the authority exists and has declared its scope, thresholds, stop paths, and structural commitments.

---

## Updating a record

Updates follow the same submission process. An update PR/Issue must reference the existing Mechanism ID and describe the change. The existing Mechanism Record is preserved in version history; the file shows the current version. All updates are logged with timestamp and reason.


---

*Bounded Power Framework — Registration Form (v4)*
*All submissions become permanent public records*
