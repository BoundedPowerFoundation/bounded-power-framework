# Violations

This folder holds Violation Reports filed against authorities under the Bounded Power Framework.

A Violation Report (VR) is a structured public record documenting a specific incident in which an authority did, failed to do, or threatened to do something that violates SCBP-04 or exceeds the authority's own declared bounds. Filing does not halt the authority. It creates a permanent, timestamped, public record that the concern was raised — and that a documented response is now required within 30 days.

---

## How to file a Violation Report

Use the form at [02-Forms/02-Stop-Trigger.md](../../02-Forms/02-Stop-Trigger.md). Copy the template from that form into a new file in this directory, fill it in, and open a pull request to add it.

---

## Naming pattern

```
SCBP-VR-{IDENTIFIER}-{YYYY-MM-DD}.md
```

Where `{IDENTIFIER}` is a short string identifying the authority (matching the convention used in the registry — e.g., `CCCC-OH` for the Cuyahoga County Corrections Center) and `{YYYY-MM-DD}` is the date of the incident.

If multiple Violation Reports are filed against the same authority on the same date, append a sequence suffix: `-A`, `-B`, etc.

---

## Filing against an authority with no Mechanism Record

A Violation Report can stand on its own. If the authority you are reporting does not have a Mechanism Record in the registry, use `mechanism_id: NONE` in the frontmatter and cite SCBP-04 rules directly. The absence of a Mechanism Record is itself a structural finding — no stub record is needed.

---

## Reports filed

*No Violation Reports have been filed yet.*

---

*All filings become permanent public records*  
*Good-faith filing is protected under R33 of the Structural Constitution*
