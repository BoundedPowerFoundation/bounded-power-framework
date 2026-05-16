# Registry

This directory is the public archive of records filed under the Bounded Power Framework. Three kinds of records live here.

**Mechanism Records — authority self-registrations.** An authority that chooses to enter the Bounded Power Framework files a Mechanism Record declaring its scope, harm thresholds, dependencies, and stop paths. These records use the naming pattern `SCBP-REG-####.md` and sit in this directory.

**Mechanism Records — citizen-produced structural diagnostics.** Anyone affected by an authority — citizens, journalists, researchers, civic actors — can produce a Mechanism Record analyzing that authority using public information. Citizen diagnostics use the naming pattern `SCBP-REG-TEST-{IDENTIFIER}.md`, are labeled `TEST / NOT AN OFFICIAL REGISTRATION` throughout, and also sit in this directory.

**Violation Reports.** Anyone affected by an authority can file a Violation Report documenting a specific incident in which the authority did, failed to do, or threatened to do something that violates SCBP-04 or exceeds the authority's own declared bounds. Violation Reports use the naming pattern `SCBP-VR-{IDENTIFIER}-{DATE}.md` and live in [Violations/](Violations/).

All three kinds of records use forms from [02-Forms/](../02-Forms/) and are governed by the same SCBP-04 constitutional rules and SCBP-09 numerical bounds.

For the Registration Form, see [02-Forms/01-Registration.md](../02-Forms/01-Registration.md). For the Violation Report Form, see [02-Forms/02-Stop-Trigger.md](../02-Forms/02-Stop-Trigger.md). For a guided way to produce a citizen diagnostic, see [00-Reading/06-AI-Registration-Bundle.md](../00-Reading/06-AI-Registration-Bundle.md).

---

## How the records connect

**A Mechanism Record stands on its own.** It describes an authority's structure, regardless of whether any Violation Reports have been filed against it.

**A Violation Report can stand on its own.** A citizen can document a specific incident against any authority, whether or not that authority has a Mechanism Record in the registry. Standalone VRs reference SCBP-04 rules directly and carry `mechanism_id: NONE` in their frontmatter.

**The two cross-link.** Each Mechanism Record's footer lists the Violation Reports filed against the authority it describes. Each Violation Report's frontmatter references the Mechanism ID of the authority it concerns, or `NONE` if no Mechanism Record exists. When a citizen diagnostic is later produced for an authority that already has standalone VRs filed against it, the new Mechanism Record links those existing VRs at creation time.

**An authority operating without disclosure is itself a finding.** When Violation Reports exist for an authority but no Mechanism Record does, the absence of the Mechanism Record is the structural finding the framework surfaces. No additional "stub" record is needed — the gap is visible from any VR that references `NONE`.

---

## What is here

### [SCBP-REG-0001.md](SCBP-REG-0001.md) — Bounded Power Foundation self-registration

SCBP-REG-0001 is the framework's own self-registration: a Mechanism Record for the proposed registry-and-framework custodial body, filed under the same form that any other authority would use. It is interesting for two reasons.

First, it makes the framework's own proposed operator subject to the framework — including provisions that would allow the operator's authority to expire if no affected party convened a renewal review.

Second, it serves as a worked example of how a small, indirect-authority entity completes the Registration Form — a useful counterpoint to the larger authorities in [03-Examples/](../03-Examples/).

Note: the Bounded Power Foundation is the proposed name for a future custodial body and does not currently exist as an incorporated organization. SCBP-REG-0001 records what its declaration would look like, so the same structural scrutiny the framework applies to others applies to itself.

### [Violations/](Violations/) — Violation Reports

Individual reports of specific incidents in which an authority did, failed to do, or threatened to do something that violates SCBP-04 or exceeds the authority's own declared bounds. Each report is a permanent, public, timestamped record. Filing does not halt the authority, but it does create a documented record that the concern was raised and that a response is now required within a defined window.

---

## Naming and ID conventions

**Authority self-registrations:**

```
SCBP-REG-####-v#
```

Where:

- `SCBP-REG` is a fixed prefix indicating registration under this framework
- `####` is a zero-padded sequence number assigned in order of registration
- `v#` is the version of the record (incremented when the record is materially updated)

The ID encodes only "the Nth thing registered, in version N." The authority's domain, function, and scope live inside the record — not in the ID. This keeps IDs stable across reclassification and avoids baking a functional claim into an identifier that may later prove inaccurate.

Filenames match the ID with the version stripped: a file is named `SCBP-REG-####.md` and reflects the current version. The version is recorded inside the file.

**Citizen-produced structural diagnostics:**

```
SCBP-REG-TEST-{IDENTIFIER}.md
```

Where `{IDENTIFIER}` is a short string identifying the authority being diagnosed (e.g., `SCBP-REG-TEST-CCCC-OH` for the Cuyahoga County Corrections Center, or `SCBP-REG-TEST-IMPD` for the Indianapolis Metropolitan Police Department).

Citizen diagnostics do not consume sequence numbers from the authority-registration series, and they carry the `TEST / NOT AN OFFICIAL REGISTRATION` label throughout.

**Violation Reports:**

```
SCBP-VR-{IDENTIFIER}-{DATE}.md
```

Where `{IDENTIFIER}` is a short string identifying the authority (matching the convention above) and `{DATE}` is the date of the incident being reported in `YYYY-MM-DD` format. If multiple VRs are filed for the same authority on the same date, a sequence suffix is added: `SCBP-VR-{IDENTIFIER}-{DATE}-A.md`, `SCBP-VR-{IDENTIFIER}-{DATE}-B.md`, etc.

Violation Reports live in [Violations/](Violations/), not in this directory's root.

---

## Frontmatter (YAML) convention

All Mechanism Records — authority self-registrations and citizen diagnostics alike — use the same YAML frontmatter schema. The canonical pattern is the one shown in [SCBP-REG-0001.md](SCBP-REG-0001.md) and in every record under [03-Examples/](../03-Examples/). It includes the structural metadata the registry validates against SCBP-09 bounds (renewal interval, aggregate threshold, response window, harm categories, dependency counts) along with the six §12 honesty-assertion flags. Citizen diagnostics use exactly this schema; fields a citizen analyst cannot determine from public sources are filled with `UNKNOWN` rather than omitted, and the `status` field is set to `TEST_EXAMPLE` rather than `ACTIVE`. The form's diagnostic power does not depend on the authority's cooperation, and the same structural floor applies regardless of who completes the record.

---

## How to file

Filings are made by opening a pull request on this repository, adding the completed record to the appropriate location:

- Mechanism Records (both self-registrations and citizen diagnostics) → this directory
- Violation Reports → [Violations/](Violations/)

There is no submission fee, no review queue, and no editorial gatekeeping. The repository's maintainers verify that:

- The submission uses the current form
- Numerical declarations fall within SCBP-09 bounds
- Citizen diagnostics are labeled correctly and use the `TEST` naming pattern
- Violation Reports include the required fields and cross-reference correctly
- The Mechanism ID or VR ID follows the naming convention above

Maintainers do not assess content accuracy. Filings are public the moment they are merged. A record can be updated but never deleted; prior versions remain in the repository's history.

---

## Records filed

| ID | Mechanism | Type | Status |
|---|---|---|---|
| [SCBP-REG-0001](SCBP-REG-0001.md) | Bounded Power Foundation — Public Registry and Framework | Authority self-registration | ACTIVE |

---

*Registry — public archive of Mechanism Records and Violation Reports*  
*All records subject to the Structural Constitution (SCBP-04)*
