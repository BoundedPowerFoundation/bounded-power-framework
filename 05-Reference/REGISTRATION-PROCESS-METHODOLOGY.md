# Filling Out the SCBP Registration Form — Process & Methodology

*Written for the project lead, May 2026, after producing 10 dull-truth `REG-` examples and 10 fact-only `EDU-` educational versions in a single working session.*

---

## Part 1 — What I actually did this session

### 1.1 Starting state

You arrived with:
- The v4 registration form (locked, hash-registered)
- 11 stress-test outputs (`STRESS-TEST-1` through `STRESS-TEST-11`) produced over three rounds in a prior session, each fully populated under a fictional authority name (Riverbend, Atlas, MeshCast, etc.)
- A request: rewrite the stress-test outputs with generic domain-based names for an `/examples/` directory on the GitHub repo, and write educational versions for materials outside the repo.

The bad-faith stress-test was excluded from both deliverables — it's an adversarial-testing artifact that demonstrates evasion, not a model registration.

### 1.2 What I produced

Final deliverables:
- 11 renamed stress-test files (`/renamed-stress-tests/`) — content unchanged, filenames generified
- 10 dull-truth registration examples (`REG-` prefix) for the GitHub `/examples/` directory
- 10 fact-only educational examples (`EDU-` prefix) for educational materials outside the repo

### 1.3 The naming work

For the filenames I converted the fictional protagonist of each stress-test into a descriptive domain label:

| Stress-test name | Generic label |
|---|---|
| Riverbend Parking Enforcement Bureau | MUNICIPAL-ENFORCEMENT |
| Atlas Credit Reporting Services | CONSUMER-CREDIT-REPORTING |
| Consumer Goods Quality Initiative | VOLUNTARY-ADVOCACY |
| RHCVA (Section 8 voucher administrator) | RENTAL-SUBSIDY-ADMINISTRATION |
| Northstar Predictive Analytics | RISK-SCORING-VENDOR |
| Riverbend Unified School District | SCHOOL-DISTRICT |
| Riverbend Regional Health System | HOSPITAL-SYSTEM |
| Riverbend Covenant Assembly | CONGREGATIONAL-DISCIPLINE |
| MeshCast (social platform T&S) | PLATFORM-CONTENT-MODERATION |
| Maple Ridge HOA | HOA |

The criterion was: descriptive of the function without forcing a judgment. Early candidates like "MUNICIPAL-COERCIVE" and "BAD-FAITH-AUTHORITY" failed that test — they pre-loaded a conclusion. "MUNICIPAL-ENFORCEMENT" describes what the institution does; readers form their own conclusions.

### 1.4 The content work — three registers

The harder problem was prose calibration. We iterated through four registers before locking the right ones:

| Register | What it sounds like | When used |
|---|---|---|
| **Industry euphemism** | "Funded primarily through user-generated revenue mechanisms supporting public-safety operations" | Never used; this is what we were stripping out |
| **Dull truth / plain-disclosure** | "Citation revenue constitutes ~65% of operating budget. The §4.7 capture threshold sets a 75% ceiling. Revenue mix is monitored monthly." | The `REG-` files (GitHub examples) |
| **Fact-only, no softening** | "Of total operating budget, ~65% comes from fines paid by cited drivers. Unpaid balances are sent to collections, which appear on consumer credit reports and affect access to housing, employment, and credit for up to 7 years." | The `EDU-` files (educational) |
| **Hostile / blunt** | "The authority extracts revenue from drivers... 65% revenue dependency creates structural alignment between enforcement volume and operational continuity — enforcement intensity is not independent of revenue need." | Rejected — pre-loads judgments |

The principle separating dull-truth from fact-only is **what gets stated explicitly**:
- Dull-truth states the function in institutional voice, lets framework infrastructure (R-numbers, "capture threshold," "non-consenting population") do the analytical work. A defender of the institution can read it and recognize their operation.
- Fact-only adds the downstream consequence chains and the structural mechanics in functional language. Same numbers, more of the cause-effect spelled out. A reader without framework fluency can see what the institution does and to whom.

The principle separating fact-only from hostile is **whether the prose forces an opinion**. "Extracts revenue from drivers" forces a judgment (extraction is adversarial framing). "65% of operating budget comes from fines paid by cited drivers" is the same information without the framing. A hostile critic and a defender would both call the second one accurate.

### 1.5 Genericization rules I settled on

Within the form, the following pattern worked:

- **The authority's own name** → the domain label (e.g., "MUNICIPAL-ENFORCEMENT-EXAMPLE")
- **Self-references** ("the Bureau," "RRHS," "MeshCast") → "the authority" or "the Council" or "the platform" as fits the institutional type
- **Geographic context** (cities, counties, states) → `[CITY, STATE]`, `[COUNTY 1] and [COUNTY 2], [STATE]`, `[STATE]`
- **External bodies referenced** (the city council, the local court, the state DPH) → `[CITY COUNCIL]`, `[MUNICIPAL COURT]`, `[STATE DEPARTMENT OF PUBLIC HEALTH]`
- **Specific statutes / ordinances that are fictional** → `[MUNICIPAL ORDINANCE]`, `[STATE] Mental Health Code`
- **Fictional vendor names** → `[BOOT VENDOR]`, `[LPR CAMERA VENDOR]`, `[ELECTRONIC HEALTH RECORD VENDOR]`, `[PRIMARY SCORING ALGORITHM VENDOR]`
- **Specific dates** → `[DATE]`, `[AUTHORIZATION DATE]`, `[EXPIRATION DATE]`
- **Specific identifiers / numbers in `mechanism_id`** → `SCBP-REG-EXAMPLE-{DOMAIN}` (so the ID itself signals it's an example)

What gets preserved:
- **Quantitative data** (population sizes, dollar figures, percentages, threshold values) — these are the worked-example content; stripping them gives you a blank template instead of an example
- **Real federal infrastructure** (FCRA, CFPB, FTC, HUD, HIPAA, EMTALA, Joint Commission, NCMEC, Section 230, DSA, DMCA, COPPA, etc.) — these are universal regulatory facts; removing them removes the document's accuracy
- **Framework rule citations** (R26, R55, R64, R66, R74, R79, R81, etc.) — framework infrastructure
- **Field labels** that contain the word "coercive" (the form's own structural vocabulary) — distinct from prose use of the word

What gets removed:
- **Specific real-entity names** that aren't universal infrastructure (FICO → `[PRIMARY SCORING ALGORITHM VENDOR]`; Equifax/TransUnion → "the other two major US consumer credit reporting agencies"; Epic → `[ELECTRONIC HEALTH RECORD VENDOR]`; Apple/Google as app store gatekeepers → `[APP STORE GATEKEEPERS]`)
- **Stress-test framing** that called out the document as a stress test ("This is the most complex regulatory environment of any case in this stress test" — removed)
- **Bold emphasis used for editorial weight** rather than framework-defined emphasis

### 1.6 Lessons learned this session

**Calibration takes iteration.** I delivered three different versions of the municipal enforcement file before the register was right. Each iteration was specific feedback from you about what felt off, and each time I overshot in the opposite direction before settling. Plan for at least one sample-review cycle on any new domain before producing a full set.

**The bad-faith file doesn't belong with the legitimate examples.** Its content demonstrates evasion. A real authority finding it in an `/examples/` directory and using it as a starting template would be filing a worked example of how to game the framework. We excluded it on the right grounds; preserve that exclusion. If you ever want it published, put it in adversarial-testing materials with prominent labels, not in the example directory.

**Session state was sometimes inconsistent.** Twice I tried to write a file that already existed from earlier in our session — and the cached version had bugs in it (the FICO references that I'd claimed to have fixed but hadn't). Always verify the actual file state before continuing, especially after a long session. The fix is a simple grep for known-bad strings before declaring a file complete.

**The educational versions were lighter-touch than I expected.** Once we settled on "no softening, no opinion-forcing," the educational versions ended up only meaningfully different from the registration versions in §1.2 (functional description), §4 (harm thresholds), and §6.4 (capture risk identification). Most of the form structure produces the same content in both registers. This is good — it means the form itself does most of the structural-disclosure work; calibration choices only affect a handful of high-leverage prose sections.

**Voluntary advocacy was the hardest case for register calibration.** When the institution is mostly aligned with the public's interests, the no-softening register doesn't produce much sharpening relative to the dull register. That's correct, not a failure of the method. The framework treats aligned institutions honestly without manufacturing adversarial framing.

---

## Part 2 — General methodology

This is the distilled method you can apply to fill out the form for any authority, real or worked-example. Steps run in order; later steps depend on outputs of earlier ones.

### Step 1 — Decide what you're producing

Three distinct deliverables, with different rules:

| Deliverable | Audience | Register | Identifier prefix |
|---|---|---|---|
| Real registration (live in the registry) | Public, civic actors, regulators | Dull-truth / plain-disclosure | `SCBP-REG-{NNNN}` |
| Worked example for `/examples/` directory | Authorities considering registration; readers learning the form | Dull-truth / plain-disclosure | `SCBP-REG-EXAMPLE-{DOMAIN}` |
| Educational material outside the repo | Public, journalists, civic educators | Fact-only, no softening | `SCBP-EDU-{DOMAIN}` |

Don't mix these. The biggest single mistake to avoid is producing one document and trying to make it serve all three purposes.

### Step 2 — Map the authority before drafting

Before writing anything in the form, write down (in scratch notes):

1. **What is the institution called?** Both its formal name and its informal self-description.
2. **What does it actually do?** Function in plain language — what binding decisions does it make, against whom, with what consequences?
3. **What is the authority basis?** Statute, contract, license, ordinance, bylaws, recorded covenant, or institutional custom.
4. **Who is the affected population?** Direct, indirect, non-consenting. Get the rough numbers right; the form's thresholds depend on these.
5. **What stops it?** Identify the candidate stop paths before drafting. If you can't name three independent stop paths, the authority has a structural problem the form will surface.
6. **What does it depend on?** Type 1 (extensions acting under it), Type 2 (independent authorities with relationship), Type 3 (infrastructure that, if compromised, would break stop paths against it).
7. **What's the entrenchment story?** What makes this institution hard to dismantle? Sunk infrastructure, regulatory unwinding, downstream effects that propagate beyond the institution.

If you can't answer all seven before writing, fill in the gaps first. Drafting first and then trying to retrofit the answers produces inconsistent records.

### Step 3 — Draft the form, section by section

The v4 form has 13 sections. Work in this order:

1. **§1 (What is this authority?)** — Establish the institution and its functional outputs. Be specific about what the authority can do, can't do, and doesn't do.
2. **§2 (Who can it act upon?)** — Affected populations. Be honest about non-consent: ask whether members technically consenting on signup or property purchase or account creation are meaningfully consenting in the framework's sense. Usually they aren't.
3. **§3 (What can it do and not do?)** — Geographic reach, coercive ceiling, resource ceiling, explicit exclusions, indirect influence boundaries, anti-proxy declaration. The exclusions list is where you commit to the institution's outer bounds.
4. **§4 (What harms can it cause?)** — Each harm category gets a threshold. Use peer benchmarks where they exist; use absolute thresholds where they don't. The harder a number is to set, the more important it is to set one. Vagueness here makes the form unenforceable.
5. **§5 (What stops it?)** — Three stop paths with independence justification. If you can't write three, that's a finding. Document it.
6. **§6 (What does it depend on?)** — Type 1 / Type 2 / Type 3 dependencies. Capture risks. Be honest about funding concentration, customer concentration, regulatory revolving doors, and industry coordination.
7. **§7 (Metrics, signals, decision inputs)** — Declared metrics, indirect signals, algorithmic systems. R79 (metric completeness) and R67 (auditability floor) gaps go here.
8. **§8 (How is it watched?)** — Drift monitoring, capture risk monitoring, audit interfaces, adversarial exposure, structural failure modes.
9. **§9 (How does it end?)** — Dismantling timeline, process, entrenchment factors, data disposition, downstream effect reversibility, replacement feasibility, reversibility verification.
10. **§10 (Authorization, renewal, triggers)** — Authorizing body, dates, renewal interval, aggregate trigger threshold and justification.
11. **§11 (What does it publish?)** — Ledger publication, threshold change log, interpretation change log, renewal process visibility, stop event log.
12. **§12 (Honesty assertions)** — Five checkboxes. Each one is a binding commitment; don't check what you can't actually do.
13. **§13 (Submitter)** — Registry metadata, not part of the public record.

§2.3 (non-consenting population) and §4.7 (additional harm thresholds) are the most-skipped sections in poor registrations. Spend time there.

### Step 4 — Apply the register

After the draft has all the structural content right, do a register pass:

**For real registrations and `REG-` examples (dull-truth):**
- Use institutional voice ("the authority commits," "the authority acknowledges")
- Let framework vocabulary do the analytical work — terms like "capture risk," "non-consenting population," "structural alignment," "threshold proximity" are doing the heavy lifting
- State numbers directly; don't editorialize after them
- "Acknowledges" is the institutional way of admitting a finding; use it where the finding is real

**For `EDU-` educational versions (fact-only):**
- Add downstream consequence chains in §1.2 and §4 (what does the function actually do to people; what is the cause-effect chain)
- Spell out structural mechanics in functional language without softening verbs
- Don't add adjectives that force an opinion ("extracts," "predatory," "regressive," "captured"). The test: a hostile critic and a defender both call the sentence factually accurate
- Where industry euphemisms have crept in, replace with functional verbs ("denies," "removes," "shuts off," "imposes," "forecloses," "excommunicates," "shuns")
- The educational header banner goes at the top; it explicitly says "not a registration template"

### Step 5 — Genericize, if producing a worked example

If this is a worked example, not a real registration, run the genericization pass:

1. **Authority self-references** → the domain label
2. **Geography** → `[CITY, STATE]` placeholders
3. **External bodies referenced** → `[CITY COUNCIL]`, `[MUNICIPAL COURT]`, `[STATE DEPARTMENT OF PUBLIC HEALTH]`, etc.
4. **Fictional statutes** → `[MUNICIPAL ORDINANCE]`, `[STATE] Mental Health Code`
5. **Fictional vendors** → `[BOOT VENDOR]`, `[LPR CAMERA VENDOR]`, etc.
6. **Specific dates** → `[DATE]`, `[AUTHORIZATION DATE]`, `[EXPIRATION DATE]`
7. **Real named entities that aren't universal infrastructure** → genericize ("FICO" → `[PRIMARY SCORING ALGORITHM VENDOR]`)

Preserve:
- All quantitative figures (these are the worked-example values)
- All real federal/national regulatory infrastructure (FCRA, CFPB, HIPAA, EMTALA, NCMEC, Section 230, DSA, etc.)
- All framework R-citations

### Step 6 — Verify before publishing

Before declaring any document complete:

1. **Grep for fictional name leaks.** Run a check for every fictional name used in any source material. A single leftover "Riverbend" or "Atlas" undermines the rest of the document.
2. **Grep for register violations.** For `EDU-` files, search for opinion-forcing words: `extract|predator|prey|crush|hostile|regressive`. For `REG-` files, additionally search for the bolded-for-editorial-weight pattern.
3. **Verify the header and footer.** EDU files need the banner. Both EDU and REG examples need updated footers with cross-references and the correct prefix.
4. **Confirm `status:` field.** `EXAMPLE` for worked examples, `EDUCATIONAL` for educational versions, `ACTIVE` (or whatever your registry uses) for real registrations.
5. **Confirm `mechanism_id` field.** No real registration should have an example-pattern ID, and no example should have a real registry ID.
6. **Cross-reference R-citations.** Make sure every R-number cited is the right rule and that you haven't introduced a citation to a rule that doesn't exist.

A grep pass for these takes one minute. Skipping it is what produced the FICO leak in this session that I had to fix retroactively.

### Step 7 — Calibration check for the specific authority type

Some domains have specific things to get right:

- **Government enforcement authorities** (police, parking, code enforcement): get the funding-source disclosure honest. If revenue depends on enforcement volume, that's the capture risk; don't hide it.
- **Data/scoring authorities** (credit reporting, risk scoring, screening): get §3.5 (indirect influence) detailed. Their authority operates through other institutions' decisions; the indirect channel is the substantive one.
- **Healthcare/hospital authorities**: get §4.1 right with peer benchmarks. "We don't cause bodily harm" is wrong; the right framing is "we operate at these specific peer-benchmark rates."
- **Religious / membership institutions**: get §2.3 (non-consenting) right. Most members technically consented at affiliation; many didn't meaningfully consent in the framework's sense due to family-of-origin membership, social/economic embedment, or exit costs.
- **Platform authorities**: get §3.4 (data exclusions) right. ToS-based authority is broad; the form's value here is in what the platform commits *not* to do.
- **HOAs and small voluntary associations**: get §5 (stop paths) honest. HOA stop paths are weaker than government stop paths; acknowledge it.
- **Voluntary advocacy / ratings**: get §4.7 (additional harm thresholds) symmetric. The harm of getting it wrong runs in both directions — to the subjects rated and to the consumers relying on the ratings.

### Step 8 — Cross-link and file

Final placement:
- Real registrations → `/registry/SCBP-REG-{NNNN}.md`
- Worked examples → `/examples/REG-{DOMAIN}-EXAMPLE.md`
- Educational versions → wherever you keep educational materials (outside the repo, per your direction)

If both a REG-example and an EDU-example exist for the same domain, each footer should cross-reference the other. The EDU header banner already does this; the REG file's footer just says "registered under the Bounded Power Framework" — that's fine, no cross-reference back to EDU needed (since EDU materials live outside the repo).

---

## Part 3 — A few things I'd consider for future iterations

**The genericized examples could use a `/examples/README.md`.** A single-page guide explaining how to use the example directory: "These are worked examples of the SCBP form. Each one demonstrates how a different type of authority would complete the form. They are not registration templates. To register a real authority, complete the blank form at `/forms/registration.md` and submit it through the registry."

**The educational versions might benefit from an index.** Outside the repo, you might want a top-level page listing all 10 educational examples with a one-sentence description of each. That's where readers would land before clicking into a specific domain.

**The bad-faith stress-test deserves its own home.** Right now it lives in `/renamed-stress-tests/` under a generic name (REG-BAD-FAITH-EXAMPLE) which both undersells what it is and could mislead readers about its purpose. It's an adversarial-testing artifact and should probably be filed under SCBP-07 (Integration and Adversarial Testing) materials, with framing that makes its purpose unambiguous.

**Several domains we discussed didn't get done.** Your project brief listed many more domains than we produced (police departments, ICE, family court, CPS, payment processors, debanking, etc.). The work to produce examples for those domains would follow the same Step 1–8 method. If you want to extend the example set, the highest-impact additions are probably: police department, ICE, family court, payment processor, and platform algorithmic-distribution (separate from the content moderation we did, since the algorithmic-distribution side is where most of the framework's R58 indirect-authority concerns apply most directly).

**Renewal of the existing examples.** Examples don't need renewal in the registry sense, but they do need maintenance as the form evolves. If v5 of the form lands, every example will need to be updated to match — at minimum YAML metadata, possibly more substantive sections if v5 adds or restructures sections. Build that maintenance into the project rhythm.

---

*Document produced: May 2026*
*Project: Bounded Power Foundation — Public Registry and Framework*
*Companion to: the `/forms/registration.md` v4 form and the 10 REG-example and 10 EDU-example files produced in this session*
