# Examples

This directory holds twenty-five worked diagnostics — applications of the [Registration Form](../02-Forms/01-Registration.md) to authority types, showing what the form surfaces when applied honestly to each kind of authority.

The examples are not registrations. None has been submitted by the institutions described — those institutions have not filed anything. The examples ask: *if this form were filled out honestly about each of these authority types, what would the form surface, and would the surfacing produce something useful?*

Each file follows the same template a real Mechanism Record would use. The authority types are illustrative, not specific organizations: filenames use descriptive identifiers (e.g., `Municipal-Police-Department.md`, `Consumer-Credit-Reporting.md`). The structural facts in each record — population counts, dependency counts, harm thresholds, dismantling timelines — reflect what an honest application of the form to that type of authority would plausibly disclose, drawn from publicly known information about how authorities of each type actually operate (statutes, regulatory filings, public documentation, court opinions, investigative journalism, academic literature). The examples do not generate new information; they force existing information into a shape where its structural meaning is visible.

Every file uses `status: EXAMPLE` in its metadata and `SCBP-REG-EXAMPLE-{DOMAIN}` as its mechanism ID, to make the distinction from real records visible at every level. They confer no status on any real authority and are not statements about whether any specific real authority of the type described should register.

These worked diagnostics also serve as patterns. A citizen producing a structural diagnostic of a real authority (see [How to run a citizen inquiry](../00-Reading/05-Citizen-Inquiry-Guide.md)) can read the example most similar to their authority type for a sense of how the form's sections come out for that kind of authority.

---

## What the example set is built to test

The examples were chosen to span the framework's stress points: very large and very small authorities, direct and indirect authority, governmental and private and voluntary, single-jurisdiction and multi-jurisdiction, statutory and contractual. The set asks several questions simultaneously:

- Does a single registration form scale across authority types from a 940-person homeowners association to a 4-billion-cardholder payment network, or does it break somewhere in the middle?
- Does the form's structure produce useful disclosure when applied to authorities whose existing self-descriptions are heavily shaped by their own interests?
- What does honest disclosure of small voluntary authority look like compared to honest disclosure of large coercive authority? Are they the same shape, or does the form bend differently at different scales?
- What does the form fail to catch when filled out strategically? (See the bad-faith counter-example below.)

If the example set produces useful answers to these questions, the form has done some of the work it is designed for. If the answers are unclear or unsatisfactory, that is also useful information.

---

## The bad-faith counter-example

[Bad-Faith-Consulting.md](Bad-Faith-Consulting.md) is the most epistemically important document in this directory.

The other examples ask what the form surfaces when applied honestly. The bad-faith case asks the harder question: *what does the form fail to catch when an authority fills it out strategically?* It is the only example with editorial annotations, written in alongside the form's content to identify where the form holds and where it leaks.

A reader interested in whether the form is robust should read the bad-faith case before — or alongside — any of the honest examples. Knowing what the form misses changes how the honest examples read.

---

## The honest examples

The remaining twenty-four examples are organized below by approximate scale of affected population. Scale is one cut among several; readers may find more useful organizations (by domain, by direct vs. indirect authority, by governmental vs. private).

### Small-scale authority (under 5,000 affected)

These examples test the form at the smallest scale, where authority is most often informal, voluntary, and operationally close to the people it acts upon. Genuine exit is usually available; exit costs vary.

- [Worker-Cooperative.md](Worker-Cooperative.md) — single-facility worker-owned cooperative, ~50 affected. Member-ownership combines employment, governance, and capital; expulsion entails simultaneous loss of all three.
- [Community-Land-Trust.md](Community-Land-Trust.md) — single-jurisdiction community land trust, ~480 affected. Tripartite governance; 99-year ground leases as honest engagement with intergenerational binding.
- [Time-Bank.md](Time-Bank.md) — neighborhood time bank operating member-issued time-credit currency, ~320 affected. Credit-and-currency authority structured to remain below money-transmitter thresholds.
- [Mutual-Aid-Network.md](Mutual-Aid-Network.md) — neighborhood-scale volunteer-run mutual aid, ~1.4K affected. Most informal authority in the set; tests the form at the smallest scale.
- [Congregational-Discipline.md](Congregational-Discipline.md) — disciplinary council of a religious assembly, ~4.8K affected. Voluntary in form, often non-consenting in practice; high exit costs.
- [HOA.md](HOA.md) — single-subdivision homeowners association, ~940 affected. Micro-scale coercive authority pervasive in modern American suburbia.
- [Rental-Subsidy-Administration.md](Rental-Subsidy-Administration.md) — municipal Section 8 voucher administrator, ~4.2K affected. Small authority over a population for whom benefit loss is catastrophic.
- [Tenant-Union.md](Tenant-Union.md) — neighborhood-scale tenant union, ~2.4K affected. Member non-participation as a structural stop path; organizing authority shape.

### Mid-scale authority (5,000 to 1 million affected)

At this scale the form starts to surface dependencies and downstream effects more visibly than at small scale.

- [School-District.md](School-District.md) — public K-12 unified school district, ~28K affected. Direct authority over minors; vulnerable population is the entire affected population.
- [Public-University-Trustees.md](Public-University-Trustees.md) — flagship state research university board of trustees, ~95K affected. **High-existing-disclosure test case** — operates within state sunshine laws, public-records law, and accreditation reporting; tests what the form yields against an authority whose procedural transparency is already extensive.
- [Municipal-Police-Department.md](Municipal-Police-Department.md) — mid-size municipal police department, ~165K affected. Authorized lethal force; arrest records propagating to permanent federal databases.
- [Family-Court-Custody.md](Family-Court-Custody.md) — state family court authority over custody, visitation, parental rights, ~240K affected. Authority over the most intimate human relationships; termination of parental rights is permanent.
- [Open-Source-Governance.md](Open-Source-Governance.md) — open-source software project governance body, ~240K affected. The fork as the foundational stop path of open source; non-geographic, non-financial digital authority.
- [Hospital-System.md](Hospital-System.md) — regional nonprofit integrated health system, ~285K affected. Direct authority over patients during care; vulnerability is structural to the relationship.
- [Risk-Scoring-Vendor.md](Risk-Scoring-Vendor.md) — private recidivism risk-assessment vendor, ~480K affected. Indirect authority through a tool licensed to other authorities; classic R58 case.
- [Child-Protective-Services.md](Child-Protective-Services.md) — state child welfare agency and dependent foster care, ~850K affected. Disparate impact by race and poverty as foundational structural fact.

### Large-scale authority (1 million+ affected)

At population scale the form is asked to do its hardest work: registering authorities whose effects propagate through dependency chains across many other systems.

- [Immigration-Enforcement.md](Immigration-Enforcement.md) — federal interior immigration enforcement, ~47M affected. Civil detention without Sixth Amendment counsel; removal as permanent banishment.
- [Health-Insurance-Adjudication.md](Health-Insurance-Adjudication.md) — major health insurance carrier's claim-adjudication authority, ~50M affected. Private adjudication of medical-care access; bodily-harm pathways.
- [Platform-Content-Moderation.md](Platform-Content-Moderation.md) — Trust & Safety operations of a global social media platform, ~89M affected. Authority operating through Terms of Service rather than statute; clickwrap consent at scale.
- [Tenant-Screening.md](Tenant-Screening.md) — national tenant-screening company, ~90M affected. Records reflecting documented systemic disparities operationalized as housing-access decisions.
- [Voluntary-Advocacy.md](Voluntary-Advocacy.md) — national consumer product testing and advocacy nonprofit, ~195M affected. Small organization with massive indirect reach through trusted recommendations.
- [Consumer-Credit-Reporting.md](Consumer-Credit-Reporting.md) — national consumer credit reporting agency, ~245M affected. Indirect authority at population scale; non-consenting third parties as the default condition.
- [FOMC-Monetary-Policy.md](FOMC-Monetary-Policy.md) — Federal Open Market Committee monetary policy authority, ~340M affected directly with substantial global indirect effect. **High-existing-disclosure test case** — operates within an unusually thick disclosure regime (Humphrey-Hawkins reports, FOMC minutes, transcripts at five-year lag, quarterly press conferences); tests what the form yields when the authority's procedural transparency is already among the most developed in modern governance.
- [Payment-Processor.md](Payment-Processor.md) — global card-payment network, ~4B affected. Private duopoly deciding which legal businesses can transact.

### High-existing-disclosure test cases

Two of the examples above are flagged as **high-existing-disclosure test cases**: the public university board of trustees and the FOMC monetary policy authority. Both authorities already operate within thick procedural-transparency regimes. They are included to test a specific question: when an authority's existing public disclosures are already extensive, does the registration form yield anything beyond what is already public?

The brief answer, developed in the meta-notes of each example, is: yes, in a small but concentrated set of areas. Both examples find that the form's incremental yield against a high-disclosure authority is concentrated in a few sections — affected-population framing (§2), harm thresholds (§4), stop paths (§5), failure-mode cataloguing (§8.5), and the framework's expiration default (§10.3) — while adding little to others (statutory basis, coercive ceiling, metric publication, audit interfaces). Both findings cut both ways and are stated honestly in the records themselves.

---

## How to read an example

A reading order that gives the most useful comparison across scales:

1. Start with a small-scale example — [HOA.md](HOA.md) or [Worker-Cooperative.md](Worker-Cooperative.md) — to see the full shape of a Mechanism Record without the volume that comes with population-scale authorities.

2. Read a large-scale example — [Consumer-Credit-Reporting.md](Consumer-Credit-Reporting.md) — to see the same template applied at much larger scale.

3. Read the bad-faith case — [Bad-Faith-Consulting.md](Bad-Faith-Consulting.md) — to see what the form does not catch and where it leaks. The editorial annotations show what to look for in any record.

4. Read one mid-scale or large-scale coercive example — [Municipal-Police-Department.md](Municipal-Police-Department.md) or [Immigration-Enforcement.md](Immigration-Enforcement.md) — to see what the form does with the hardest cases.

After this, any example matching reader interest. Sections worth comparing across examples:

- **§1.2 Functional description** — the plain-language statement of what the authority does. The form requires this to describe the authority's actual operational behavior, not its preferred self-description. Comparing functional descriptions across the examples shows what straightforward language about authority looks like.
- **§2.3 Non-consenting population** — the count of people affected without affirmative opt-in. Several examples disclose that essentially the entire affected population is non-consenting.
- **§5 Stop paths** — what stops the authority and who can activate the stop. This section is where authorities that are formally voluntary often reveal that exit is not actually available, and where large coercive examples honestly disclose the structural conditions limiting their stop paths' real effectiveness.
- **§9.5 Downstream effect reversibility** — whether the authority can reverse the effects of its past decisions. The large-scale examples make this section unusually long because what those authorities cannot reverse is unusually consequential.
- **§9.7 Reversibility verification** — whether the authority has actually rehearsed dismantling. Most examples acknowledge they have not. This is structurally honest and structurally concerning.

The examples are deliberately uneven in length: a small worker cooperative's record is shorter than a payment processor's because there is less to declare. The form does not require a small authority to fill space; it requires it to disclose what is structurally present.

---

## Acknowledged gaps in the examples

Several gaps and acknowledgments appear in the examples (declined sections, "R26 gap acknowledged here" notes, dismantling-rehearsal admissions, R67 floor concerns). These are not failures of the examples — they are the kind of disclosure the form is designed to surface. An honest application of the form to any large institution would include such acknowledgments. Their presence is what an honest record looks like.

---

*Examples — worked diagnostics of authority types*  
*None constitute a registration of any real authority*
