# Registry

This directory is the public archive of records filed under the Bounded Power Framework. Two kinds of records live here.

**Mechanism Records.** A Mechanism Record is a completed Registration Form describing an authority's scope, harm thresholds, dependencies, stop paths, and oversight gaps. Every Mechanism Record uses the same form, the same YAML schema, and the same SCBP-09 numerical bounds, regardless of who produced it. Records can be filed by the authority being analyzed (the YAML field `filed_by` is `authority`, status `ACTIVE`) or by a third party — citizen, journalist, researcher, civic actor — analyzing the authority from public sources (`filed_by: third_party`, status `PUBLIC_SOURCES`). Third-party records carry the `PUBLIC SOURCES ONLY` banner at the top and bottom of the body, signaling that the record has not been confirmed by the authority it describes. Mechanism Records sit in this directory.

**Violation Reports.** Anyone affected by an authority can file a Violation Report documenting a specific incident in which the authority did, failed to do, or threatened to do something that violates SCBP-04 or exceeds the authority's own declared bounds. Violation Reports use the naming pattern `SCBP-VR-{IDENTIFIER}-{DATE}.md` and live in [Violations/](Violations/).

Both kinds of records use forms from [02-Forms/](../02-Forms/) and are governed by the same SCBP-04 constitutional rules and SCBP-09 numerical bounds.

For the Registration Form, see [02-Forms/01-Registration.md](../02-Forms/01-Registration.md). For the Violation Report Form, see [02-Forms/02-Stop-Trigger.md](../02-Forms/02-Stop-Trigger.md). For a guided way to produce a Mechanism Record from public sources, see [00-Reading/06-AI-Registration-Bundle.md](../00-Reading/06-AI-Registration-Bundle.md).

---

## How the records connect

**A Mechanism Record stands on its own.** It describes an authority's structure, regardless of whether any Violation Reports have been filed against it.

**A Violation Report can stand on its own.** Anyone affected by an authority can document a specific incident, whether or not that authority has a Mechanism Record in the registry. Standalone VRs reference SCBP-04 rules directly and carry `mechanism_id: NONE` in their frontmatter.

**The two cross-link.** Each Mechanism Record's footer lists the Violation Reports filed against the authority it describes. Each Violation Report's frontmatter references the Mechanism ID of the authority it concerns, or `NONE` if no Mechanism Record exists. When a Mechanism Record is later produced for an authority that already has standalone VRs filed against it, the new record links those existing VRs at creation time.

**Authority-after-third-party.** When a third party files the initial Mechanism Record about an authority and the authority later files corrections, the existing record is updated in place rather than duplicated. The mechanism_id and filename stay the same; the YAML flips from `filed_by: third_party`/`status: PUBLIC_SOURCES` to `filed_by: authority`/`status: ACTIVE`; `record_version` increments; the `PUBLIC SOURCES ONLY` banner is removed; and the Renewal Log inside the record documents the transition. Git history preserves the third-party-produced version.

**An authority operating without disclosure is itself a finding.** When Violation Reports exist for an authority but no Mechanism Record does, the absence of the Mechanism Record is the structural finding the framework surfaces. No additional "stub" record is needed — the gap is visible from any VR that references `NONE`.

---

## What is here

### [SCBP-REG-0001-BPF.md](SCBP-REG-0001.md) — Bounded Power Foundation self-registration

SCBP-REG-0001 is the framework's own self-registration: a Mechanism Record for the proposed registry-and-framework custodial body, filed under the same form that any other authority would use. It is interesting for two reasons.

First, it makes the framework's own proposed operator subject to the framework — including provisions that would allow the operator's authority to expire if no affected party convened a renewal review.

Second, it serves as a worked example of how a small, indirect-authority entity completes the Registration Form — a useful counterpoint to the larger authorities in [03-Examples/](../03-Examples/).

Note: the Bounded Power Foundation is the proposed name for a future custodial body and does not currently exist as an incorporated organization. SCBP-REG-0001 records what its declaration would look like, so the same structural scrutiny the framework applies to others applies to itself.

### [Violations/](Violations/) — Violation Reports

Individual reports of specific incidents in which an authority did, failed to do, or threatened to do something that violates SCBP-04 or exceeds the authority's own declared bounds. Each report is a permanent, public, timestamped record. Filing does not halt the authority, but it does create a documented record that the concern was raised and that a response is now required within a defined window.

---

## Naming and ID conventions

**Mechanism Records:**

```
SCBP-REG-####-{DESCRIPTIVE-SUFFIX}.md
```

Where:

- `SCBP-REG` is a fixed prefix indicating registration under this framework
- `####` is a zero-padded sequence number assigned in order of registration — the next integer after the highest existing `SCBP-REG-####` in the registry
- `{DESCRIPTIVE-SUFFIX}` is a short human-readable identifier for the authority (e.g., `CCCC-OH` for the Cuyahoga County Corrections Center, `NYPD` for the New York Police Department, `FOMC` for the Federal Open Market Committee)

The mechanism_id inside the file's YAML frontmatter is just `SCBP-REG-####` — the descriptive suffix is part of the filename only, for browsing convenience. The mechanism_id encodes only "the Nth thing registered." The authority's domain, function, location, and scope live inside the record's YAML and body — not in the ID. This keeps IDs stable across reclassification, rebranding, or restructuring, and avoids baking a functional claim into an identifier that may later prove inaccurate.

Sequential numbering applies to all Mechanism Records regardless of who filed them. A record filed by a third party and a record filed by an authority occupy the same numbering series. If `SCBP-REG-0001` and `SCBP-REG-0002` exist, the next record filed — whether by an authority or a third party — is `SCBP-REG-0003`.

**Violation Reports:**

```
SCBP-VR-{IDENTIFIER}-{DATE}.md
```

Where `{IDENTIFIER}` is a short string identifying the authority and `{DATE}` is the date of the incident being reported in `YYYY-MM-DD` format. If multiple VRs are filed for the same authority on the same date, a sequence suffix is added: `SCBP-VR-{IDENTIFIER}-{DATE}-A.md`, `SCBP-VR-{IDENTIFIER}-{DATE}-B.md`, etc.

Violation Reports live in [Violations/](Violations/), not in this directory's root.

---

## Frontmatter (YAML) convention

All Mechanism Records use the same YAML frontmatter schema. The canonical pattern is the one shown in [SCBP-REG-0001.md](SCBP-REG-0001.md) and in every record under [03-Examples/](../03-Examples/). It includes structural metadata the registry validates against SCBP-09 bounds (renewal interval, aggregate threshold, response window, harm categories, dependency counts), location and identity fields (country, region, subregion, authority acronym, primary address), record-lifecycle dates (registered, snapshot, last reviewed), and the five §12 honesty-assertion flags. The schema applies regardless of who filed the record; fields a third-party filer cannot determine from public sources are filled with `UNKNOWN` rather than omitted. The `status` field is `ACTIVE` for authority-filed records and `PUBLIC_SOURCES` for third-party records. The form's diagnostic power does not depend on the authority's cooperation, and the same structural floor applies regardless of who completes the record.

---

## How to file

Submissions are accepted by GitHub pull request, by GitHub issue, or by email to BoundedPowerFoundation@proton.me. Completed records are placed in:

- Mechanism Records (regardless of filer) → this directory
- Violation Reports → [Violations/](Violations/)

There is no submission fee, no review queue, and no editorial gatekeeping. The repository's maintainer verifies that:

- The submission uses the current form
- Numerical declarations fall within SCBP-09 bounds
- The YAML schema matches the canonical pattern, with `UNKNOWN` for unfillable fields
- Third-party-filed records (`filed_by: third_party`) carry the `PUBLIC SOURCES ONLY` banner at the top and bottom of the body
- Violation Reports include the required fields and cross-reference correctly
- The Mechanism ID or VR ID follows the naming convention above

The maintainer does not assess content accuracy. Filings are public the moment they are merged. A record can be updated but never deleted; prior versions remain in the repository's history.

---

## Records filed

| ID | Mechanism | Filed by | Status |
|---|---|---|---|
| [SCBP-REG-0001](SCBP-REG-0001.md) | Bounded Power Foundation — Public Registry and Framework | authority | ACTIVE |

---

*Registry — public archive of Mechanism Records and Violation Reports*  
*All records subject to the Structural Constitution (SCBP-04)*
