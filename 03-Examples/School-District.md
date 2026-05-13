---
mechanism_id: SCBP-REG-EXAMPLE-SCHOOL-DISTRICT
mechanism_name: "SCHOOL-DISTRICT-EXAMPLE"
status: EXAMPLE
domain: education
authority_classification: direct
registered_date: [DATE]
authorization_date: [AUTHORIZATION DATE]
expiration_date: [EXPIRATION DATE]
renewal_interval_years: 4
funding_types:
  - state_government_mandatory
  - local_government_mandatory
  - federal_government_discretionary
funding_concentration_max_pct: 41
affected_party_categories:
  - residents_of_geographic_area
  - children
  - vulnerable_populations
  - employees
  - non_consenting_third_parties
affected_population_estimate: 28000
non_consenting_population_estimate: 28000
entity_size: large
geographic_specificity: single_municipality
geographic_reach: "[SCHOOL DISTRICT] service area, [CITY, STATE]"
aggregate_threshold_count: 8
aggregate_threshold_window_days: 90
response_window_days: 30
harm_categories_declared:
  - bodily_harm
  - agency_impairment
  - communicative_suppression
  - chronic_asymmetry
  - generational_binding
  - informational_sovereignty
algorithmic_decision_systems_used: true
dependency_count_type1: 12
dependency_count_type2: 5
dependency_count_type3: 6
capture_risk_identified: true
disclosure_completeness_assertion: true
update_obligation_committed: true
discoverability_acknowledged: true
burden_of_proof_acknowledged: true
anti_weaponization_acknowledged: true
---

# Mechanism Record — REG-SCHOOL-DISTRICT-EXAMPLE

**SCHOOL-DISTRICT-EXAMPLE**

| Field | Value |
|---|---|
| Mechanism ID | REG-SCHOOL-DISTRICT-EXAMPLE |
| Status | EXAMPLE |
| Registered | [DATE] |
| Authorization expires | [EXPIRATION DATE] |
| Domain | Education |

---

## SECTION 1 — What is this authority?

**1.1 Mechanism name:** SCHOOL-DISTRICT-EXAMPLE — a public K-12 unified school district.

**1.2 Functional description:** This authority is a public K-12 school district serving approximately 18,000 students across 24 schools (15 elementary, 5 middle, 4 high schools). Functional outputs:
- Compulsory attendance enforcement (truancy proceedings)
- Special education determinations and IEP/504 plan administration
- Disciplinary actions including suspension, expulsion, and law enforcement referrals
- Grades, transcripts, and graduation determinations
- Curriculum development and implementation
- Student records (academic, behavioral, health, family)
- Employment decisions for ~2,400 staff (teachers, administrators, support staff)
- Procurement and contracting (~$240M annual budget)

**1.3 Authority classification:** Direct. The authority makes binding decisions affecting students, families, and staff.

**1.4 Domain:** Education (primary). Government (functional).

**1.5 Statutory or constitutional basis:** [STATE] School Code; [STATE] Constitution (right to education); federal authority including IDEA (special education), FERPA (records), Title VI/IX (civil rights), ESEA/ESSA (federal education funding). Authorized by [SCHOOL] Board of Education under state and local taxing authority.

---

## SECTION 2 — Who can this authority act upon?

**2.1 Affected party categories:**
- [x] Residents of geographic area (entire attendance area, ~78,000 residents)
- [x] Children (~18,000 students; ages 5–19)
- [x] Vulnerable populations: students with disabilities (~2,200 with IEPs); students in poverty (~52% qualify for free/reduced lunch); English Language Learners (~14%); LGBTQ+ students; students of color (~58% non-white)
- [x] Employees (~2,400 staff, of whom many are bound by tenure and union agreements)
- [x] Non-consenting third parties: parents/guardians of students who must interact with the District; contractors and vendors

**2.2 Approximate number of people directly affected:** ~28,000 (students + their families + staff).

**2.3 Non-consenting population:** Essentially all students under compulsory attendance laws are non-consenting (children cannot consent to enrollment). Parents/guardians are partially non-consenting — they can homeschool or private-school but face significant practical barriers. Approximately 28,000 individuals are non-consenting in some meaningful sense.

**2.4 Vulnerable population specifics:**
- [x] Children — yes, virtually entire affected population. Children are the primary subjects of authority. Special protections: parental notification requirements; due process for disciplinary actions; disability accommodations; mandated reporting of abuse/neglect; restraint and seclusion limits.
- [x] Patients during medical care — partial. Students with health conditions; school nurses provide care; coordination with medical providers.
- [ ] Detained or confined persons — not applicable in usual sense.
- [x] Persons in coercive economic relationships — yes. Staff who depend on District employment; families whose children's educational future depends on the District.
- [x] Persons unable to advocate for themselves — yes. Young children, students with cognitive disabilities, ELL students, families with limited English or limited resources.

---

## SECTION 3 — What can it do, and what can it not do?

**3.1 Geographic reach:** Single municipality — district attendance area ([CITY, STATE] plus small portions of two adjacent townships per state district boundary law).

**3.2 Coercive ceiling:**
- Mandatory enrollment of resident children of compulsory attendance age
- Truancy proceedings (referral to [TRUANCY OFFICE] and ultimately [FAMILY COURT])
- Disciplinary actions: detention, in-school suspension (up to 10 days/year per [STATE] law), out-of-school suspension (up to 10 days), expulsion (up to 2 years following Board hearing)
- Special education identification, placement, services
- Records collection and retention (academic, behavioral, health within parental consent rules)
- Search of student persons or property under reasonable suspicion (T.L.O. standard)
- Law enforcement referrals for criminal conduct on school property
- Employment decisions (hiring, discipline, termination per due process and union agreements)

May not: detain a student off school grounds or after school hours without legal authority; conduct strip searches; share student records beyond FERPA-permitted purposes; require religious observance; punish for protected speech (Tinker standard); discriminate on protected characteristics.

**3.3 Resource ceiling:**
- Operating budget: ~$240M annually
- Staff: ~2,400 FTE
- Data systems: Student Information System (SIS), special education management system, learning management systems, financial systems

**3.4 Explicit exclusions:**
- **Geographic:** May not enroll non-resident students except per inter-district transfer agreements; may not extend authority outside school grounds and school activities.
- **Action:** May not impose corporal punishment (illegal in [STATE]); may not use restraint or seclusion except per state regulations; may not conduct biased search; may not require waivers of FERPA rights.
- **Data:** May not share student records with ICE, federal immigration enforcement, or non-FERPA-authorized parties; may not use student data for marketing; may not share student data for research without parental consent and IRB approval; may not retain disciplinary records beyond statutory limits.
- **Procedural:** May not contract with vendors who collect student data for resale; may not employ staff with conflicts of interest in District contracts; may not allow gifts to staff from contractors.
- **Other:** May not propose, enact, or enforce policies that infringe on protected speech, religious practice, or association.

---

## SECTION 4 — What harms can it cause?

**4.1 Bodily harm threshold:** Substantive for a school district.

If any student is physically injured by staff use of restraint, seclusion, or other physical contact, that case is itself a finding triggering review (regardless of whether single-event).

If documented bullying or harassment within school grounds results in injury, suicide, or significant mental health crisis, and the District knew or should have known, this triggers review.

If facility safety standards (lead in water, asbestos, structural hazards) are documented and not abated within state-required timelines, this triggers review.

**4.2 Agency impairment threshold:** If special education determinations or 504 determinations are not completed within state-required timelines for more than 5% of cases, this triggers review.

If disciplinary actions are imposed without due process per [STATE] School Code, those cases are themselves findings.

**4.3 Ecological damage threshold:** Not directly applicable.

**4.4 Generational binding threshold:** Substantive.

Educational outcomes affect generations. Threshold: if outcomes (graduation rates, college readiness, post-secondary outcomes) for any demographic subgroup decline by more than 5 percentage points over any 3-year period without explanation, this triggers review.

If discipline rates produce a "school-to-prison pipeline" pattern (students who experience expulsion or law enforcement referrals subsequently enter the criminal justice system at rates exceeding peers without comparable referrals), this triggers review.

**4.5 Communicative suppression threshold:** If student or staff speech is suppressed beyond Tinker constitutional limits, those cases are findings.

If retaliation against students or staff for filing complaints, raising concerns, or participating in protected speech is documented, those cases are findings.

If curriculum or library decisions suppress information based on viewpoint discrimination rather than educational merit, this triggers review.

**4.6 Informational sovereignty threshold:**

- Student records shared beyond FERPA-permitted purposes triggers immediate review
- Records retained beyond statutory limits triggers review
- Student social media or personal-life monitoring beyond educational purposes triggers review
- Algorithmic monitoring of students (chat filtering, behavior prediction) without disclosure to parents triggers review

**4.7 Additional harm thresholds:**

*Discipline disparity threshold:* If suspension/expulsion rates by race, ethnicity, disability status, or LGBTQ+ identification exceed proportional rates in the student population at p<0.05 over any 12-month period, this triggers review.

*Achievement gap threshold:* If achievement gaps between demographic groups widen by more than 3 percentage points over any 3-year period, this triggers review.

*Restraint/seclusion threshold:* Each restraint or seclusion incident requires parent notification; aggregate use beyond state-defined thresholds triggers review.

**4.8 Threshold change-log commitment:** [x] Yes — committed.

---

## SECTION 5 — What stops it?

**STOP PATH 1 — Board of Education**
- Activator: Board of Education (7 elected members, 4-year terms)
- Trigger: Board determination of mismanagement, policy violation, or systemic problem
- What stopped means: Board may direct administrative action, suspend programs, or remove Superintendent
- Independence justification: Board is elected, not appointed by administration; serves staggered terms
- Timeline: Board meeting cycle (monthly)

**STOP PATH 2 — Federal/State court order or class action**
- Activator: Federal or state court on motion of any party with standing
- Trigger: Court determination of constitutional or statutory violation
- What stopped means: Court orders may halt practices, require systemic remediation
- Independence justification: Judiciary structurally independent
- Timeline: Per court procedures

**STOP PATH 3 — State Board of Education enforcement**
- Activator: [STATE] Board of Education
- Trigger: State Board determination of state law violation
- What stopped means: State Board may suspend specific programs, require remediation, or in extreme cases place district on academic watch or financial oversight
- Independence justification: State Board is state-level, structurally independent of local district
- Timeline: State Board administrative procedures

**5.4 Penalty for activating stop:** [x] Confirmed — no penalty applies. Whistleblower protections under [STATE] law and federal law.

**5.5 Stop-path independence verification:** [x] Yes for all three paths.

**5.6 Civic trigger acknowledgment:** [x] Acknowledged.

---

## SECTION 6 — What does it depend on?

**6.1 Type 1 dependencies:**
- Special education service providers (3 contracted firms — therapists, evaluators)
- Transportation contractor (1 firm — bus services)
- Food service contractor (1 firm — meal services)
- Custodial/maintenance contractor (1 firm)
- Substitute teacher service (2 firms)
- Educational software vendors (~10 — student information system, learning management, behavioral monitoring)
- Health services contractor (1 firm — school health services)

**6.2 Type 2 dependencies:**
- [STATE] Board of Education
- Federal Department of Education
- Local [CITY COUNCIL] (some funding coordination)
- Adjacent school districts (inter-district agreements)
- [CITY GOVERNMENT] (public safety, facilities)

**6.3 Type 3 dependencies:**
- Student Information System vendor — operational core; failure prevents grades, attendance, communications
- State funding flow — annual disbursement; failure halts operations
- Federal funding flow (Title I, IDEA) — failure halts specific programs
- Building infrastructure — schools cannot operate without facilities
- IT infrastructure
- Special education contractor network

**6.4 Capture risk identification:** [x] Yes.

- Funding concentration: 41% state, 38% local, 21% federal — diverse but state largest
- Vendor capture: educational technology vendors have ongoing relationships; some have lobbying presence
- Political capture: school board members are elected; political activity affects district decisions
- Union dynamics: teachers' union has substantial influence; this is structural, not capture per se
- Real estate impact: school quality affects property values, creating pressure from real estate interests

**6.5 Reversibility-affecting dependencies:**
- 18,000 students in active enrollment
- 2,400 staff with various tenure protections
- Multi-year contracts with major vendors
- State and federal program participation requires multi-year commitments

**6.6 Coordination disclosures:**
- *The District coordinates with [MUNICIPAL POLICE DEPARTMENT]:* School Resource Officer program; this is a R55 finding because it operationalizes police authority within school setting in ways that effectively expand the District's coercive reach. Mitigation: SRO program subject to annual review; SRO actions not directed by District administrators.
- *The District coordinates with [CHILDREN'S SERVICES]:* Mandated reporting and case coordination.
- *The District coordinates with adjacent districts:* IGAs for transfers, special programs.

**6.7 Disclosure completeness assertion:** [x] Asserted.

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

**7.1 Declared metrics:**

| Metric | Source | Role | Public? |
|---|---|---|---|
| Attendance | SIS | Truancy enforcement | Aggregate yes |
| Grades | Teacher input via SIS | Promotion, graduation | Individual yes (to family); aggregate yes |
| Disciplinary records | Administrator entries | Cumulative discipline tracking | Aggregate yes |
| Special education evaluations | Multidisciplinary team | IEP determinations | Individual yes (to family) |
| Standardized test scores | State testing | Curriculum decisions, federal compliance | Aggregate yes |
| Teacher evaluations | Administrator evaluations | Employment decisions | Individual no |
| Student behavior monitoring (digital tools) | Various vendors | Risk identification | Aggregate yes |

**7.2 Indirect signals:**
- Teacher referral patterns to special education or discipline (subjective; can produce disparate outcomes)
- Administrator discretion in disciplinary decisions
- Algorithmic flags from behavioral monitoring software (e.g., social media monitoring vendors flag certain patterns)

**7.3 Algorithmic decision systems:** [x] Yes.

- *Behavioral monitoring software:* Used by ~3 schools; monitors student communications on district-provided devices for safety concerns. Vendor: [BEHAVIORAL MONITORING VENDOR]. Auditability: methodology partially restricted by vendor; District publishes aggregate alert rates.
- *Predictive risk identification:* Some schools use analytics to identify students at risk of dropping out. Vendor: in-house plus consultant. Auditability: methodology disclosed to Board.

**7.4 Outcome-versus-declaration check:** [x] Committed annually.

---

## SECTION 8 — How is this authority watched?

**8.1 Drift monitoring:** Annual report to Board; state Board annual review; quarterly internal compliance review.

**8.2 Capture risk monitoring:** Annual conflict-of-interest disclosure for staff and Board members.

**8.3 Audit interfaces:** Standard district transparency: Board minutes, financial reports, annual reports, state Board submissions, FOIA-eligible records.

**8.4 Adversarial exposure (R81):** External parties can evaluate aggregate outcomes, demographic patterns, financial flows, Board decisions. Cannot evaluate individual student records (necessarily private) or some personnel matters.

**8.5 Known structural failure modes:**
- Discipline disparities by race/disability (well-documented nationally; district-specific testing required)
- Special education over/under-identification
- Curriculum politicization
- Vendor data security failures
- Staff misconduct
- Bullying systemic failures
- School-to-prison pipeline patterns

---

## SECTION 9 — How does it end?

**9.1 Dismantling time:** Not realistically dismantleable in framework's reversibility sense — public schools are not dissoluble. *However:* the District could be dissolved and merged with another district per [STATE] school district reorganization law; estimated 24 months.

**9.2 Dismantling process:**
- Voter referendum or state Board–approved reorganization
- Multi-year transition planning
- Student transfers to successor district
- Staff reassignment per union agreements
- Asset transfer per state law
- Final accounting and dissolution

**9.3 Entrenchment factors:**
- 18,000 students must continue education
- 2,400 staff with tenure/union protections
- Multi-year contracts and obligations
- Property assets ($380M+ in facilities)
- Community identity attached to schools

**9.4 Data disposition:** Student records transferred to successor district per FERPA; institutional records archived per state law.

**9.5 Downstream effect reversibility:** R63 finding — student records, transcripts, disciplinary records propagate widely (colleges, employers, criminal justice). Cannot be reversed.

**9.6 Replacement feasibility:** Could merge with adjacent districts; structurally feasible; politically and emotionally difficult.

**9.7 Reversibility verification:** No formal rehearsal. R43 gap acknowledged.

---

## SECTION 10 — Authorization, renewal, and trigger declarations

**10.1 Authorizing body:** Board of Education under [STATE] state law.

**10.2 Date of authorization:** [AUTHORIZATION DATE] (Board renewal cycle).

**10.3 Expiration date:** [EXPIRATION DATE].

**10.4 Renewal interval:** 4 years.

**10.5 Renewal evidence declaration:** [x] All five domains.

**10.6 Necessity-decay acknowledgment:** [x] Acknowledged.

**10.7 Aggregate trigger threshold:** 8 triggers in 90 days. SCBP-09 §II places ~28,000 non-consenting in 1,000–100,000 range (5–25). The District elects 8 — slightly above floor — reflecting structural vulnerability of students and the framework's bias toward underrepresented populations.

**10.8 Aggregate threshold justification:** Per SCBP-09 amendment principle of "largest most underrepresented / most destructive harm" — children's voices in civic systems are structurally underrepresented; harms to children's educational outcomes have lifetime consequences.

**10.9 Response time window:** 30 days (default).

**10.10 Response window justification:** Not required.

---

## SECTION 11 — What does this authority commit to publishing?

**11.1 Citizen ledger publication:** Annually (annual report) plus quarterly Board updates.

**11.2 Threshold change log:** Within 7 days.

**11.3 Interpretation change log:** Continuous.

**11.4 Renewal process visibility:** [x] Committed. Renewal review by parties drawn from affected categories: parents/guardians, current and former students, civil rights organizations, disability rights advocates, education researchers, classroom teachers (independent of administration).

**11.5 Stop event log:** [x] Acknowledged.

---

## SECTION 12 — Honesty assertions

All five: [x] asserted/committed/acknowledged.

---

## SECTION 13 — Submitter

*[Submitter information retained by registry as metadata.]*

---

*REG-SCHOOL-DISTRICT-EXAMPLE — worked example of a public K-12 unified school district*
*Registered under the Bounded Power Framework*
*All authority governed by the Structural Constitution (SCBP-04)*
