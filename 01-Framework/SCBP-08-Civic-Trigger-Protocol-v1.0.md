# SCBP-08 — Civic Trigger Protocol

*Operational Layer*
*Subordinate to: the Structural Constitution*

---

## Purpose

This document defines the civic trigger mechanism — the structured process by which any party affected by a registered authority can initiate constitutional responses through public filings.

The civic trigger is the framework's primary means of surfacing concerns from outside the authority itself. Authorities are required by the Constitution to remain stoppable (R23, R24, R32) and to operate without penalty for those who invoke stop mechanisms (R15, R33). The civic trigger operationalizes those rules as filing channels available to anyone affected.

This document does not authorize the registry to act against any authority. It defines what filings are recognized, how they are recorded, what response clocks apply, and how reviewers convene. Adjudication of any filing is performed by stakeholder reviewers — not by the registry.

---

## Section I — Trigger Classes

There are three classes of civic trigger. Each invokes a distinct constitutional response and has a distinct response clock.

### Tripwire-class trigger

**Invokes:** R23 — Tripwire Protocol (provisional pause pending review)

**Filed when:** the filer alleges a defined harm threshold has been crossed by the authority. The threshold being crossed is the named threshold from the authority's Mechanism Record §7, not a general grievance.

**Effect on filing:** the registry logs the trigger publicly within the registry's standard operational window (per Registry Charter §7). The named authority is notified. The Mechanism Record's Stop Event Log records the filing.

**Response clock:** 30 days from filing, or the authority's declared response window (per SCBP-09 §III) if shorter.

**Review path:** stakeholders from the authority's declared affected-party categories (Mechanism Record §3) may convene a review of the alleged threshold breach. The review's findings are recorded in the Mechanism Record's Stop Event Log alongside the original trigger.

### Challenge-class trigger

**Invokes:** R70 — Time-Bound Compliance Requirement

**Filed when:** the filer alleges constitutional non-compliance that is not specifically a harm threshold breach. Examples: the authority has acted outside declared scope (R04, R05); a stop path has been obstructed (R15); the authority's renewal evidence appears incomplete (R47); declared values appear gamed (challenges to SCBP-09 declarations).

**Effect on filing:** identical recording process to Tripwire. The named authority is notified. The trigger is logged in the Mechanism Record.

**Response clock:** 30 days from filing, or the authority's declared response window if shorter.

**Review path:** stakeholders convene as for Tripwire. The reviewable question is whether the alleged non-compliance is substantiated.

### Aggregate-class trigger

**Invokes:** R34 — Aggregation Review Requirement

**Filed when:** the count of independent triggers (Tripwire and Challenge combined) against a single authority within a defined window reaches the authority's declared aggregate threshold (per SCBP-09 §II).

**Effect on filing:** automatic. No filer initiates an aggregate trigger directly. When the registry's count reaches the threshold, an aggregate trigger is initiated by the registry as a public Issue. The aggregate trigger references all underlying triggers that contributed to the count.

**Response clock:** 30 days from initiation.

**Review path:** stakeholders convene as for Tripwire and Challenge. The reviewable question is whether the aggregate pattern constitutes substantive concern about the authority's overall operation, beyond what any single trigger established.

---

## Section II — Who Can File

Any party affected by a registered authority may file a Tripwire or Challenge trigger.

"Affected" is interpreted broadly. The authority's Mechanism Record §3 declares categories of affected parties; filers from any of those categories qualify. Filers who do not fit a declared category but believe they are affected may file; the Mechanism Record's declared categories may be wrong, and contesting them is itself an acceptable Challenge.

Aggregate triggers are not filed by individuals — they are initiated automatically by the registry when the threshold is reached.

### Identity and disclosure

Filers may file:

- **Identified** — providing legal name, contact information, and stated relationship to the authority
- **Pseudonymous** — providing a stable identifier (e.g., GitHub handle) without legal name
- **Anonymous** — providing no identifying information

All three modes are accepted. Identification level is at the filer's discretion.

The framework recognizes that legal-name filing exposes the filer to potential retaliation — exactly the kind of friction Rule R15 prohibits. Pseudonymous and anonymous filing exist to honor that protection. The framework also recognizes that anonymous filing may be exploited by adversaries; that risk is addressed structurally in Section V (Filing Signals), not by restricting who may file.

### Good-faith protection

Good-faith filing is protected under R33. No party — including the authority named in the trigger, the Foundation, or any third party — may penalize a filer for good-faith use of the civic trigger mechanism. Retaliation against a filer is itself a Framework finding and may be the subject of further triggers.

---

## Section III — How to File

### Filing channel

Triggers are filed as pull requests on the registry repository on GitHub, adding the completed record to [04-Registry/Violations/](../04-Registry/Violations/). The filing becomes public when the pull request is merged. Public visibility *is* the act of filing — there is no separate publication step.

### Required fields

The required fields are defined in [02-Forms/02-Stop-Trigger.md](../02-Forms/02-Stop-Trigger.md). Future updates to that form are subject to the registry's amendment process.


---

## Section IV — Recording and Notification

### Recording

Every filing is recorded as a public Mechanism Record entry in [04-Registry/Violations/](../04-Registry/Violations/). The Issue:

- Receives a timestamp at creation
- Is labeled by trigger class (Tripwire / Challenge / Aggregate)
- Is linked from the named authority's Mechanism Record Stop Event Log, if a Mechanism Record exists
- Cannot be deleted; updates are appended

### Notification

The registry notifies the named authority by:

- Publishing the filing in the public registry (visibility-of-record is the primary notification)
- Sending a notification through the contact channel declared in the authority's Mechanism Record (if any)
- Linking the filing from the Mechanism Record, if one exists

If the authority has declared no contact channel, only the publishing-of-Issue notification applies. Authorities are expected to monitor their own Mechanism Record's Stop Event Log; failure to do so is not a defense against the response clock.

---

## Section V — Filing Signals

The registry publishes structural signals alongside each filing to help reviewers assess credibility. Signals are observational, not editorial — the registry does not adjudicate good faith or bad faith; it surfaces information from which reviewers can draw their own conclusions.

### Standard signals attached to each filing

- Filing timestamp
- Filer identity disclosure level (identified / pseudonymous / anonymous)
- Filing channel (GitHub direct / email transcribed)
- Email domain category (if email provided): major provider (gmail, outlook, etc.) / institutional / unknown / known disposable
- Whether the filer hash (if any) appears in other recent filings against the same authority
- Whether the filer hash (if any) appears in other recent filings across multiple authorities

### Aggregate-context signals

When an Aggregate-class trigger is initiated, additional context is published:

- Total filings contributing to the threshold
- Distribution of filer identity disclosure levels
- Distribution of email domain categories
- Distribution of filing timestamps (clustering, gaps)
- Distribution of filer hashes (concentration vs. spread)

These signals do not prove a filing or aggregate is genuine or manufactured. They provide reviewers with the structural information needed to apply judgment. The registry takes no position on the conclusions reviewers draw.

### Why the registry does not filter

Filtering at the form level cannot reliably distinguish good-faith filings from sophisticated bad-faith filings. Any filter strict enough to exclude bad-faith activity would also exclude legitimate vulnerable filers. Any filter loose enough to admit legitimate vulnerable filers would also admit bad-faith activity. The framework's response is to publish the signals and let review handle credibility.

This means the registry's record will sometimes include filings that are noisy, ill-founded, or made in bad faith. That is a deliberate property, not a defect. Visibility of the noise — including its structural signals — is part of the mechanism.

---

## Section VI — Stakeholder Review

The framework does not designate, recruit, or convene reviewers. Reviewers are stakeholders from the affected-party categories declared in the authority's own Mechanism Record §3. They self-organize.

### When review occurs

Review of a Tripwire or Challenge trigger is not automatic. The filing creates a public record and starts the response clock; whether stakeholders convene to evaluate the alleged breach depends on whether the filing surfaces concerns that affected parties consider worth investigating.

If no stakeholders convene, the filing remains in the public record and the response clock proceeds. The authority's response (or non-response) is logged. Subsequent filings may reference the unreviewed filing in establishing a pattern.

### How review proceeds

The registry does not specify the internal process of stakeholder review. Stakeholders may convene through any structure they find appropriate — informal discussion threads, formal panels, allied-organization processes, or other forms. The registry records the review's *findings* when they are submitted; it does not regulate the review's *process*.

### What a review produces

A stakeholder review produces a finding. The finding is filed as a public comment on the original trigger Issue. It includes:

- The reviewing parties (identified, pseudonymous, or anonymous, at their discretion)
- The conclusion (substantiated / unsubstantiated / inconclusive)
- The reasoning
- Any minority opinion, if reviewers disagreed

Findings do not bind the authority. They become part of the public record. The authority's response to the finding (or non-response) is itself logged.

### Multiple reviews

A single trigger may receive multiple stakeholder reviews from different groups. All reviews are recorded. The framework does not select among competing reviews. Readers — including authorities, regulators, journalists, courts, and future stakeholders — see all of them and make their own assessments.

---

## Section VII — Response Clock and Non-Response

### Authority response

The named authority is expected to respond publicly within the response window. Acceptable responses include:

- Acknowledgment and explanation
- Evidence of compliance
- Initiation of internal review
- Request for clarification of the filing
- Notice of dispute (with reasoning)
- Initiation of remediation

The response is filed as a comment on the trigger Issue and is logged in the Mechanism Record's Stop Event Log.

### Non-response

Failure to respond within the response window is logged as a finding. Non-response is not a violation of any rule the registry can enforce — the registry has no enforcement authority. It is a fact placed in the public record.

Non-response patterns matter cumulatively. A single non-response may indicate temporary unavailability or processing delay. Patterns of non-response across multiple triggers indicate something more substantive about the authority's posture toward civic accountability. Patterns of non-response are themselves potential subjects of Aggregate or Challenge triggers.

### Response that contests the filing

An authority may respond by disputing the filing's accuracy or good faith. The dispute is recorded alongside the filing. Stakeholder reviewers, if they convene, may evaluate the dispute on its merits along with the filing itself.

The framework recognizes that some triggers will be filed in error or in bad faith. Disputed filings remain in the record but are visibly disputed. The framework does not pretend to know who is correct in a dispute; it preserves both positions and lets reviewers and readers judge.

---

## Section VIII — Aggregate Trigger Mechanics

### Initiation

When the count of distinct Tripwire and Challenge triggers against a single authority within the authority's declared aggregate window reaches the authority's declared aggregate threshold, the registry automatically initiates an Aggregate-class trigger.

"Distinct" is interpreted by filer hash where filer hashes exist, and by reasonable judgment where they do not. Multiple filings from a single hash are counted once. Filings without identifiers are counted individually but flagged in the aggregate context.

### Aggregate trigger as filing

The aggregate trigger is filed as a new entry in the registry:

- References every contributing trigger
- Publishes the aggregate-context signals (Section V)
- Notifies the authority through standard notification channels
- Starts a 30-day response clock

### Authority response to aggregate

The authority's response to an aggregate trigger is expected to address the *pattern*, not just individual filings. Acceptable responses include systemic acknowledgment, evidence of operational change, request for stakeholder dialogue, or substantive dispute of the aggregate pattern's validity.

A response that addresses each individual underlying trigger separately, while ignoring the aggregate pattern, is itself a finding.

### Stakeholder review of aggregate

Aggregate reviews carry weight beyond individual reviews. A stakeholder finding that an aggregate pattern reflects organized bad faith (e.g., a coordinated adversarial campaign) is a substantive conclusion that affects how subsequent filings against that authority are interpreted. A stakeholder finding that an aggregate pattern reflects genuine widespread concern is similarly substantive.

The registry preserves these findings without ranking them.

---

## Section IX — Trigger Abuse

The framework recognizes that triggers can be misused.

### Abuse by filers

A filer may submit triggers in bad faith — fabricated, frivolous, retaliatory, or part of a coordinated adversarial campaign. The framework's response is structural:

- All filings remain public; abuse becomes part of the public record
- Filing signals (Section V) make patterns visible
- Stakeholder reviews can find filings unsubstantiated
- Repeated patterns of unsubstantiated filings from the same filer hash become themselves a Framework finding

The framework does not editorially suppress filings on the operator's discretion. Abuse is addressed through visibility and review, not through gatekeeping.

### Abuse by authorities

An authority may attempt to discourage filings through informal retaliation, procedural harassment, or asymmetric response burdens. These are themselves rule violations:

- R15 prohibits stop friction
- R33 prohibits penalty for good-faith challenge
- R46 prohibits procedural harassment

Filers who believe they have been retaliated against may file Challenge-class triggers documenting the retaliation. Retaliation patterns are themselves grounds for Aggregate review.

### Abuse by the registry

The Foundation, as registry operator, is bound by the Charter's custody principles (Charter §3). The Foundation does not editorially suppress, alter, or selectively process filings. If the Foundation appears to have done so, that is itself grounds for a trigger against the Foundation as a registered authority (SCBP-REG-0001).

---

## Section X — Relationship to Other Documents

This document operationalizes the civic trigger references in:

- SCBP-04 §R23, R34, R70 (the rules invoked by trigger classes)
- SCBP-06 §Civic Trigger Layer (now superseded by this document; SCBP-06 retains a brief pointer)
- Registry Charter §10 (operator recusal during reviews of the Foundation itself)
- SCBP-09 (the floors and ceilings on aggregate threshold and response window)

The forms `02-Forms/02-Stop-Trigger.md` and `02-Forms/01-Registration.md` operationalize this document's filing requirements.

If conflict exists between this document and the Structural Constitution, the Constitution governs. If conflict exists between this document and the Registry Charter, the Charter governs registry operation; this document governs trigger mechanics.

---

*SCBP-08 — Civic Trigger Protocol — Operational Layer*
*All authority governed solely by the Structural Constitution (SCBP-04)*

---

