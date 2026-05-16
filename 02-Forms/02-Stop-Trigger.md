# Stop Trigger / Violation Report Form

This is the form for filing a Stop Trigger — a structured public report that a specific authority did, failed to do, or threatened to do something that violates SCBP-04 or exceeds the authority's own declared bounds. The artifact produced by filing is called a Violation Report.

---

## What this does

Filing a Stop Trigger does not immediately halt any authority. It does three things:

- Creates a permanent public record that a specific concern was raised about a specific authority on a specific date
- Establishes a documented response window — the authority has 30 days to respond publicly, or the non-response itself becomes a finding in the public record
- Cross-links the Violation Report to the authority's Mechanism Record if one exists, or stands alone if it doesn't

The visibility is the mechanism. The record is public the moment it is merged into the registry. The authority's response — or absence of response — is also public.

---

## Who can file

Anyone affected by an authority. You do not need to be a lawyer, an expert, or a formal party. You do not need the authority to have registered itself. If an authority is doing something to you or people around you, you can file.

Good-faith filing is protected under Rule R33 of the Structural Constitution. Retaliation against a good-faith filer is itself a constitutional violation under R33 and can be the subject of its own Violation Report.

---

## How to file

Open a pull request on this repository adding the completed Violation Report to [04-Registry/Violations/](../04-Registry/Violations/).

Use the naming pattern:

```
SCBP-VR-{IDENTIFIER}-{YYYY-MM-DD}.md
```

Where `{IDENTIFIER}` is a short string identifying the authority (e.g., `CCCC-OH` for the Cuyahoga County Corrections Center, `IMPD` for Indianapolis Metropolitan Police Department) and `{YYYY-MM-DD}` is the date of the incident. If multiple reports are filed for the same authority on the same date, append a sequence suffix: `-A`, `-B`, etc.

---

## Violation Report template

Copy the template below into your new file and fill it in. Fields left blank or marked `UNKNOWN` are acceptable — partial information is better than no record. Only the frontmatter fields (mechanism_id, date, identifier) are strictly required.

```
---
vr_id: SCBP-VR-{IDENTIFIER}-{YYYY-MM-DD}
mechanism_id: SCBP-REG-#### | NONE
authority_name: [The authority being reported]
incident_date: YYYY-MM-DD
filed_date: YYYY-MM-DD
filer_anonymous: true | false
---

# Violation Report — [Authority Name] — [Incident Date]

## Authority

Authority name:
Authority location / jurisdiction:
Mechanism Record reference: [SCBP-REG-####, or NONE if no Mechanism Record exists]

## Date of observation

Date(s) when the condition was observed:

## What was observed

Describe what happened in plain language. What did the authority do, fail to do, or threaten to do?

## Which threshold or condition was breached

Mark all that apply:

[ ] A defined harm threshold in the authority's Mechanism Record was exceeded
[ ] The authority acted outside its authorized scope
[ ] A stop path was obstructed or made more difficult
[ ] The authority expanded without reauthorization
[ ] Someone was penalized for raising a concern (R33 retaliation)
[ ] Authorization has expired and the authority continues operating
[ ] The authority cannot be stopped by defined stop paths
[ ] An SCBP-04 rule was violated directly (specify which: e.g., R##)
[ ] Other (describe):

## Evidence or documentation

Describe any evidence available. You do not need to attach documents to file — a description is sufficient to create the record. Where evidence is public (news reporting, court filings, government records), include citations or links.

## Filer information (optional)

Name (you may file anonymously):
Contact (if you want to receive updates):
Your relationship to the authority:

## Anything else

Additional context, related incidents, or notes for future reviewers.

---

*Filed under the Bounded Power Framework*
*Good-faith filing is protected under R33 of the Structural Constitution*
```

---

## What happens after filing

**Immediately:** The Violation Report becomes public when the pull request is merged. The record exists in the registry's permanent history and cannot be deleted.

**Within 7 days:** If a Mechanism Record exists for the authority, the Violation Report's existence is added to the Mechanism Record's footer (cross-link from the Mechanism Record to the VR).

**Within 30 days:** The authority is presumed to have notice via the public record. A documented response — acknowledgment, explanation, evidence of compliance, initiation of internal review, request for clarification — is the expected good-faith response. Non-response within 30 days is itself logged as a finding and added to the Violation Report and, if applicable, the Mechanism Record.

**After review:** If the report raises credible evidence of a threshold breach or constitutional violation, it may be referenced in subsequent Mechanism Record updates, third-party-produced Mechanism Records, or SCBP-08 civic trigger escalations.

---

## Aggregate triggers

If 10 or more independent Violation Reports are filed against the same authority within any 90-day period, an automatic aggregation review is initiated, regardless of the individual report classifications. The aggregation review is itself a public record. See SCBP-08 for the full Civic Trigger Protocol.

---

## Filing against an authority with no Mechanism Record

If the authority you are concerned about does not have a Mechanism Record in the registry, you can still file. Use `mechanism_id: NONE` in the frontmatter and include as much identifying information as you have in the body.

The Violation Report stands on its own. It cites SCBP-04 rules directly rather than declared bounds. The absence of a Mechanism Record is itself a structural finding the framework surfaces: the authority is operating without disclosed scope, thresholds, or stop paths.

If a third-party-produced Mechanism Record (`filed_by: third_party`) is later created for that authority, the existing Violation Reports are cross-linked at that time. If the authority later files corrections to that record (`filed_by: authority`), the cross-linking remains in place.

---

*Stop Trigger / Violation Report Form*
*All submissions become permanent public records*
*Good-faith filing is protected under Rule R33 of the Structural Constitution*
