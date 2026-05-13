---
mechanism_id: SCBP-REG-EXAMPLE-RENTAL-SUBSIDY-ADMINISTRATION
mechanism_name: "RENTAL-SUBSIDY-ADMINISTRATION-EXAMPLE"
status: EXAMPLE
domain: government
authority_classification: direct
registered_date: [DATE]
authorization_date: [AUTHORIZATION DATE]
expiration_date: [EXPIRATION DATE]
renewal_interval_years: 3
funding_types:
  - federal_government_mandatory
  - local_government_mandatory
funding_concentration_max_pct: 92
affected_party_categories:
  - residents_of_geographic_area
  - vulnerable_populations
  - children
  - non_consenting_third_parties
affected_population_estimate: 4200
non_consenting_population_estimate: 4200
entity_size: small
geographic_specificity: single_municipality
geographic_reach: "[PUBLIC HOUSING AUTHORITY] service area — [CITY, STATE] plus contracted suburban municipalities"
aggregate_threshold_count: 5
aggregate_threshold_window_days: 90
response_window_days: 30
harm_categories_declared:
  - bodily_harm
  - agency_impairment
  - communicative_suppression
  - chronic_asymmetry
  - generational_binding
  - informational_sovereignty
algorithmic_decision_systems_used: false
dependency_count_type1: 4
dependency_count_type2: 3
dependency_count_type3: 4
capture_risk_identified: true
disclosure_completeness_assertion: true
update_obligation_committed: true
discoverability_acknowledged: true
burden_of_proof_acknowledged: true
anti_weaponization_acknowledged: true
---

# Mechanism Record — REG-RENTAL-SUBSIDY-ADMINISTRATION-EXAMPLE

**RENTAL-SUBSIDY-ADMINISTRATION-EXAMPLE**

| Field | Value |
|---|---|
| Mechanism ID | REG-RENTAL-SUBSIDY-ADMINISTRATION-EXAMPLE |
| Status | EXAMPLE |
| Registered | [DATE] |
| Authorization expires | [EXPIRATION DATE] |
| Domain | Government |

---

## SECTION 1 — What is this authority?

**1.1 Mechanism name:** RENTAL-SUBSIDY-ADMINISTRATION-EXAMPLE — a municipal Section 8 Housing Choice Voucher administrator.

**1.2 Functional description:** This authority administers federal Section 8 Housing Choice Vouchers within a defined service area. Functional outputs:
- Determines applicant eligibility for housing assistance based on federal HUD criteria (income, family composition, citizenship, criminal history)
- Maintains a waiting list (currently ~12,000 applicants for ~2,100 available vouchers)
- Issues vouchers to eligible families, allowing them to rent from private landlords
- Inspects participating rental units for HUD Housing Quality Standards (HQS) compliance
- Calculates and pays the housing assistance portion of rent directly to participating landlords
- Conducts annual recertifications of family income and composition
- Terminates assistance for program violations (income changes, household composition changes, lease violations)
- Refers families to and from other housing programs

The authority can: deny eligibility; remove families from the waiting list; place a family in violation status; terminate vouchers; recover overpaid assistance. It cannot: directly evict; arrest or detain; place a person in another program without their consent.

**1.3 Authority classification:** Direct. The authority issues binding eligibility determinations, voucher terminations, and recoupment actions. Decisions can be appealed through internal grievance and HUD review.

**1.4 Domain:** Government (primary). Healthcare-adjacent and Education-adjacent in indirect ways (housing affects health and educational outcomes), but those are downstream effects.

**1.5 Statutory or constitutional basis:** Operates under federal authority — U.S. Housing Act of 1937 §8 (42 U.S.C. §1437f), HUD regulations (24 C.F.R. Parts 982, 5), and HUD's Annual Contributions Contract (ACC) with the [PUBLIC HOUSING AUTHORITY]. State law ([STATE] housing law) and city ordinance ([MUNICIPAL CODE SECTION]) further structure operations. The PHA's existence is established under [STATE] state public housing law; HUD authorizes its operation as a Section 8 administrator through the ACC.

**This authority is constitutionally a hybrid.** It exercises federal authority delegated through the PHA. Termination of the federal program would terminate this authority. The authority cannot operate independent of HUD authorization.

---

## SECTION 2 — Who can this authority act upon?

**2.1 Affected party categories:**
- [x] Residents of defined geographic area (service area total ~78,000 residents, of whom ~4,200 are program participants or applicants)
- [x] Vulnerable populations: low-income families (by definition — Section 8 income limits), elderly persons (~28% of voucher holders are over 62), persons with disabilities (~31% of voucher holders have a disabled household member), single-parent households (~62% of voucher holders), persons of color (~71% of voucher holders are non-white, exceeding the proportion in the general population)
- [x] Children (~38% of voucher household members are under 18; approximately 1,600 children directly affected at any given time)
- [x] Non-consenting third parties: private landlords participating in the program are subject to HQS inspection, lease compliance review, and termination of housing assistance payments. Approximately 380 landlords participate.

**2.2 Approximate number of people directly affected:** Approximately 4,200 active program participants (voucher holders + waiting list applicants). Adding non-participating residents who interact with the authority: approximately 5,000.

**2.3 Non-consenting population:** Approximately 4,200 — the full population of voucher holders, applicants, and participating landlords. Voucher holders technically applied voluntarily but are functionally non-consenting because (a) they have no real alternative for housing assistance at this scale; (b) they cannot decline the authority's authority while remaining in the program; (c) they are subject to ongoing recertification and inspection that they cannot opt out of without losing housing.

Landlords technically participate voluntarily but are subject to inspection and compliance authority that they cannot decline while remaining in the program.

R26 (Non-Participant Harm Floor) applies with full force — these populations have minimal exit options and are particularly vulnerable to the authority's actions.

**2.4 Vulnerable population specifics:**
- [x] Children — yes, substantial. Children's housing stability is materially affected by decisions. Voucher termination = potential homelessness for the children. Commitments: (a) special review of any termination affecting a household with children; (b) coordination with school district to minimize school disruption from moves; (c) child-protection-services notification when a termination would result in homelessness for children.
- [ ] Patients during medical care — partial. Voucher holders include many in active medical care; loss of stable housing affects health outcomes. No specific medical-protection procedures, but commitment to good-cause hearings considering medical circumstances.
- [ ] Detained or confined persons — limited. Persons returning from incarceration may have eligibility restrictions; the authority follows HUD criminal-record screening rules.
- [x] Persons in coercive economic relationships — yes, structurally. Voucher holders are in coercive economic relationship with the authority (lose voucher = lose housing); landlords are in coercive economic relationship (lose payments = lose tenant); voucher holders are also in coercive economic relationship with landlords (eviction = lose voucher in many cases).
- [x] Persons unable to advocate for themselves — yes. The authority serves elderly, disabled, low-literacy, and limited-English-proficient populations. Commitments: free language interpretation in 8 languages; accessible meeting locations; written materials at 6th-grade reading level; advocate-permitted hearings.

---

## SECTION 3 — What can it do, and what can it not do?

**3.1 Geographic reach:**
- [x] Single municipality with multi-municipality contract: [CITY, STATE] plus 6 contracted suburban municipalities ([CONTRACTED MUNICIPALITIES]).

This is multi-municipality but operationally a single geographic service area defined by the PHA's HUD-approved service area.

**3.2 Coercive ceiling:** The authority may:
- Determine eligibility for housing assistance per HUD criteria
- Place applicants on or remove from waiting list
- Issue or revoke Housing Choice Vouchers
- Inspect participating units (announced or unannounced per HUD rules) for HQS compliance
- Withhold housing assistance payments to landlords for HQS violations
- Terminate housing assistance for program violations following due-process hearings
- Recover overpaid assistance through state collection mechanisms

The authority may not: directly evict tenants; arrest or detain persons; remove children from households; refuse housing assistance based on protected classes; access information beyond what HUD authorizes; share program participant information except as HUD permits.

**3.3 Resource ceiling:**
- Maximum operating budget: $4.6M annually (administrative + housing assistance pass-through)
- Housing Assistance Payments authorized: ~$28M annually (passed through to landlords)
- Maximum staff: 22 FTE
- Maximum data systems: HUD-approved data systems (PIC, EIV, HCV) plus city HR/finance systems

**3.4 Explicit exclusions:**
- **Geographic exclusions:** May not operate outside service area; may not move waiting list applicants to other PHA service areas without their consent and HUD coordination.
- **Action exclusions:** May not directly evict; may not impose criminal penalties; may not collect data beyond HUD-permitted purposes.
- **Data exclusions:** May not share program participant information with: ICE, federal immigration enforcement, federal databases not authorized by HUD, private companies for marketing or analytics purposes; may not retain data beyond HUD-required retention periods.
- **Procedural exclusions:** May not accept gifts from landlords or property managers; may not require waivers of due process rights; may not contract with vendors who have prohibited financial relationships with PHA staff.
- **Temporal exclusions:** Operations conducted during business hours unless HUD-authorized exception.
- **Other exclusions:** May not propose, lobby for, or otherwise advocate the elimination of program participants based on demographic characteristics or political activity.

**3.5 Indirect influence boundaries:** Outputs influencing decisions made by others:
- Eligibility determinations affect landlords' decisions to participate
- Inspection failures affect landlord property management decisions
- Voucher availability affects rental market dynamics in service area (modest effect)
- Annual reports to HUD influence federal funding allocations to service area

**3.6 Anti-proxy declaration:**
The authority commits to not using proxies for prohibited variables:
- *Proxy for race / national origin:* Will not use ZIP code, surname, language preference, or family composition pattern in eligibility determination, except as HUD-required indicators (e.g., language for service provision).
- *Proxy for political activity:* Will not collect or use information about voucher holders' political activity, advocacy, or public criticism of the authority.
- *Proxy for criminal history beyond HUD rules:* Will not extend HUD's prescribed criminal-history screening with additional informal criteria (e.g., social media review, neighborhood reputation).
- *Proxy for "deserving / undeserving" classification:* Will not use any informal classification of voucher holders as more or less deserving of services.

---

## SECTION 4 — What harms can it cause?

**4.1 Bodily harm threshold:** This is a substantive threshold.

If voucher termination results in homelessness for any household with children, persons over 62, or persons with disabilities, that case enters provisional review. Housing instability is documented as a direct cause of bodily harm (exposure, injury, mortality) for these populations.

If HQS inspection failures result in tenant exposure to documented hazards (lead, mold, structural failure) that are not abated within 30 days, this triggers review.

**4.2 Agency impairment threshold:** If administrative grievance or hearing processes result in more than 5% of decisions being overturned by HUD review or by state administrative court, this triggers review of decision-making procedures.

If interpretation services are unavailable (interpreter not provided when requested, written materials not provided in needed language) for any case, that case is itself a finding.

**4.3 Ecological damage threshold:** Not applicable.

**4.4 Generational binding threshold:** Substantive for a housing program.

Generations are affected by housing stability. R21 generational binding category is interpreted to include: (a) decisions that materially affect the housing stability of children whose entire childhood is lived in voucher housing (~14 years of dependent childhood within program); (b) decisions that affect family wealth-building over generations.

Threshold: if overall termination rate (% of vouchers terminated annually) exceeds 8% in any 12-month period, this triggers review of program practices.

**4.5 Communicative suppression threshold:** If termination patterns correlate with voucher holders' protected speech or political activity (e.g., voucher holders who file grievances are terminated at higher rates than those who don't), this triggers immediate review.

If the grievance system is documented as having processed grievances unfairly against complainants, this triggers review.

**4.6 Informational sovereignty threshold:** Multi-part:

If voucher holder data is shared with ICE, immigration enforcement, or any federal database not authorized by HUD, this is a finding regardless of single occurrence.

If voucher holder records are retained beyond HUD-required retention periods, this is a finding.

If voucher holder records are accessed by staff for non-program purposes (e.g., personal interest), each case is a finding.

**4.7 Additional harm thresholds:**

*Chronic asymmetry threshold:* If termination rates correlate with race, ethnicity, or limited English proficiency at p<0.05 across any 12-month period, this triggers immediate review.

*Geographic asymmetry threshold:* If voucher denial or termination rates vary across the 7 municipalities in the service area in ways not explained by demographic factors, this triggers review.

*Landlord asymmetry threshold:* If inspection or compliance actions correlate with landlord characteristics (size, demographics) at p<0.05, this triggers review.

**4.8 Threshold change-log commitment:** [x] Yes — committed.

---

## SECTION 5 — What stops it?

**STOP PATH 1 — HUD enforcement action**
- *Who can activate:* Federal HUD, on supervisory finding of program violation, fair-housing rule violation, or civil rights complaint.
- *Trigger condition:* HUD determination of violation of federal housing rules.
- *What "stopped" means:* HUD may suspend the authority's authority to administer the program; place the authority under federal monitorship; terminate the Annual Contributions Contract; require systemic remediation.
- *Independence justification:* HUD is a federal agency structurally independent of the local PHA. HUD does not depend on the authority for funding or operations. HUD has historically suspended PHAs nationally for program violations.
- *Post-stop review process and timeline:* HUD enforcement procedures; appeals through HUD administrative process and federal courts; timeline 12–24 months for major actions.

**STOP PATH 2 — Federal court order or class action under Fair Housing Act / Section 8 statute**
- *Who can activate:* Federal court on motion of any party with standing under Fair Housing Act, Section 8 statute, civil rights statutes, or § 1983.
- *Trigger condition:* Court determination of violation.
- *What "stopped" means:* Court orders may halt specific practices, impose remediation, require systemic changes.
- *Independence justification:* Federal judiciary structurally independent.
- *Post-stop review process and timeline:* Per federal court procedures.

**STOP PATH 3 — PHA Board action**
- *Who can activate:* [PUBLIC HOUSING AUTHORITY] Board (5 members appointed by [CITY COUNCIL], 1 of whom must be a current voucher holder per HUD rules).
- *Trigger condition:* Board determination of mismanagement, ethics violation, or program failure.
- *What "stopped" means:* Board may direct executive director to make specific changes; may discipline or terminate executive director; may suspend specific staff or programs.
- *Independence justification:* Board has staff appointment authority; is structurally separate from operational staff. The voucher-holder Board member provides constituent-affected input.
- *Post-stop review process and timeline:* Board procedures; 60-day public input period for major decisions.

**5.4 Penalty for activating stop:** [x] Confirmed — no penalty applies. Whistleblower protections under federal HUD whistleblower program apply.

**5.5 Stop-path independence verification:** [x] Yes for HUD and federal courts. For PHA Board: independence is structural but partial — Board members are appointed by Mayor with Council consent; there is some political dependence. *R32 partial-independence finding acknowledged;* mitigation through staggered terms, voucher-holder Board member, public meetings.

**5.6 Civic trigger acknowledgment:** [x] Acknowledged.

---

## SECTION 6 — What does it depend on?

**6.1 Type 1 dependencies (operational extensions):**
- HQS inspection contractor (1 firm conducting half of inspections under flat-fee contract per inspection)
- Language interpretation service (1 firm providing per-call services)
- Hearing officer pool (3 contracted independent hearing officers per HUD requirements; flat fee per hearing)
- IT support contractor (1 firm; flat-fee retainer for HUD systems support)

**6.2 Type 2 dependencies (independent authorities with structural relationship):**
- *Federal HUD* — primary authorizer, regulator, and funder. The authority is structurally a creature of HUD authority. Direction of dependency: the authority depends entirely on HUD.
- *[PUBLIC HOUSING AUTHORITY] Board* — institutional governance.
- *[CITY COUNCIL]* — appoints Board members; provides administrative funding.

**6.3 Type 3 dependencies (infrastructure compromising stop paths):**
- *HUD's PIC, EIV, and HCV data systems* — the authority cannot operate without HUD's data infrastructure. If HUD systems fail or change without authority support, operations are compromised.
- *Federal funding flow* — operations depend on monthly federal funding. Federal shutdown or appropriation failure halts operations within 60–90 days. *Stop path compromise:* if federal funding fails for political reasons, the authority's ability becomes effectively suspended whether or not stop paths are activated.
- *State administrative court system* — accessible for administrative appeals.
- *Local landlord network* — operational dependency, not stop path.

**6.4 Capture risk identification:** [x] Yes.

- *Funding concentration:* 92% of housing assistance pass-through is federal HUD funds. The authority cannot operate without continuous federal funding. R03/R12 finding acknowledged here.
- *Landlord concentration:* No single landlord exceeds 4% of the portfolio. Capture risk from individual landlords is low.
- *Political capture:* Federal political pressure could alter program rules in ways that affect specific demographic groups. Mitigation: HUD's regulatory framework provides some insulation; class-action litigation is a check.

**6.5 Reversibility-affecting dependencies:**
- HUD authorization itself — termination of federal program eliminates authority
- Existing voucher contracts — committed assistance to ~2,100 households cannot be unilaterally terminated; requires HUD process
- Pending administrative cases — must be resolved before dismantling

**6.6 Coordination disclosures:**

The authority coordinates operationally with:
- [MUNICIPAL POLICE DEPARTMENT] on certain unit inspections (police accompaniment for unsafe locations)
- [CHILDREN'S SERVICES] for households where children's wellbeing is at issue
- Local HUD Field Office for case escalation
- Other Section 8 PHAs in the region for household transfers between service areas

**Acknowledged R55/R59 finding:** The authority is functionally part of the federal Section 8 system. Stakeholders evaluating the authority may evaluate the federal system as a whole; conversely, federal policy changes affect operations in ways the Mechanism Record alone cannot capture. Mitigation: this Mechanism Record covers local operations specifically; federal-level concerns are addressed through HUD enforcement (Stop Path 1) and federal litigation (Stop Path 2).

**6.7 Disclosure completeness assertion:** [x] Asserted.

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

**7.1 Declared metrics:**

| Metric | Source | Role | Public? |
|---|---|---|---|
| Income (verified through EIV system) | HUD EIV + applicant documentation | Eligibility, recertification | Aggregate yes |
| Family composition | Applicant; verified through documentation | Eligibility, voucher size | Aggregate yes |
| Citizenship/residency status | Applicant; verified through documentation | Eligibility | Aggregate yes |
| Criminal history (within HUD's prescribed scope) | Background check | Eligibility, exception process | Yes (criteria) |
| Disability status (when applicant requests reasonable accommodation) | Applicant; verified through documentation | Reasonable accommodation determination | Aggregate yes |
| Inspection results (HQS pass/fail) | Inspector reports | Subsidy continuation | Yes |
| Lease compliance (per landlord and tenant reports) | Landlord and tenant complaints | Termination consideration | Aggregate yes |

**7.2 Indirect signals:**
- *Hearing officer judgment:* hearings include subjective elements; mitigation via training, peer review, HUD-required hearing officer qualifications.
- *Inspector judgment:* HQS inspections have subjective elements (e.g., what constitutes "habitable"); mitigation through inspector training and re-inspection.
- *Tenant-landlord disputes:* the authority receives information from both sides; assessment of credibility involves judgment.

**7.3 Algorithmic decision systems:** [ ] No. Eligibility determination is rule-based and individually adjudicated, not algorithmic. Waiting list management uses date-of-application order plus HUD-approved priority categories — also rule-based.

**7.4 Outcome-versus-declaration check:** [x] Committed. Annual review by compliance staff and HUD field office.

---

## SECTION 8 — How is this authority watched?

**8.1 Drift monitoring mechanism:** Annual HUD on-site monitoring; quarterly internal audit; monthly metric review.

**8.2 Capture risk monitoring:** Annual financial conflict-of-interest review; quarterly review of contractor relationships; tracking of personnel movements between the authority and landlord/contractor companies.

**8.3 Audit interfaces:**
- *Proactively published:* Annual report to HUD; quarterly demographic and program metrics; HQS inspection summary; complaints summary.
- *Available on request:* Specific case files (with privacy redactions per HUD rules); contractor financial details (annual aggregate).
- *Restricted:* Individual voucher holder identifiable information per privacy law; individual hearing details.

**8.4 Adversarial exposure (R81):** External parties can evaluate:
- Program operations (HUD reporting, public statistics)
- Eligibility criteria (HUD rules public)
- Demographic outcomes (HUD reporting)
- Financial flows (audit reports public)
- Stop capability (HUD authority public; federal courts open)

*Gaps:* Individual case files are private. Some HUD systems data is restricted. R67 floor met.

**8.5 Known structural failure modes:**
- *Disparate impact in eligibility:* Documented historical issues nationally; ongoing fair-housing litigation
- *Termination patterns affecting vulnerable populations:* Documented concern; mitigation through child/elderly review
- *Inspector inconsistency:* Documented concern; mitigation through training
- *Federal funding instability:* Cannot mitigate; structural concern
- *Geographic disparities in service quality across municipalities:* Mitigated through standardized procedures
- *Landlord exit risk:* If landlords leave the program, voucher holders lose access; mitigation through landlord retention efforts

---

## SECTION 9 — How does it end?

**9.1 Estimated dismantling time:** 18 months. Justification: ~2,100 active vouchers must be wound down with HUD authorization; transition planning for affected families; landlord notification; federal regulatory unwinding.

**9.2 Dismantling process:**
- *Months 1–3:* HUD notification; cease accepting new applicants; inform existing waiting list; transition planning for active participants
- *Months 4–9:* Wind down voucher contracts on natural turnover; coordinate with HUD on transfers to other PHAs for participants who remain
- *Months 10–15:* Final inspections; landlord notifications; data archive per HUD retention requirements
- *Months 16–18:* Final HUD compliance audit; entity dissolution per state law

**9.3 Entrenchment factors:**
- *Active vouchers:* ~2,100 households would face housing instability
- *Federal program continuity:* the authority cannot dissolve without HUD coordination
- *Landlord relationships:* 380 landlords have business relationships
- *Specialized HUD systems:* knowledge transfer required

**9.4 Data disposition:**
- *Personal data:* Per HUD retention rules (typically 3 years post-program-exit); then deleted
- *Institutional records:* Archived to PHA archives; some transferred to HUD per ACC requirements
- *Audit logs:* Public archive per FOIA

**9.5 Downstream effect reversibility:** Outputs affecting downstream:
- Voucher holders' housing status (cannot reverse past housing or evictions)
- Landlords' participation history (cannot reverse past compliance findings)
- Children's school stability (cannot reverse past disruptions)

Mitigation: dissolution coordinated to minimize abrupt impact; transition pathways to other PHAs.

**9.6 Replacement feasibility:** Dissolution would require either: (a) program transfer to another PHA covering the service area; (b) federal program suspension within service area. Either is feasible but requires HUD coordination.

**9.7 Reversibility verification:** No formal dismantling rehearsal. R43 gap acknowledged. Remediation: desktop simulation within 24 months with HUD coordination.

---

## SECTION 10 — Authorization, renewal, and trigger declarations

**10.1 Authorizing body:** Federal HUD via Annual Contributions Contract; PHA Board.

**10.2 Date of current authorization:** [AUTHORIZATION DATE] (ACC effective).

**10.3 Authorization expiration date:** [EXPIRATION DATE] (ACC term).

**10.4 Renewal interval:** 3 years (matches ACC term).

**10.5 Renewal evidence declaration:** [x] All five domains committed.

**10.6 Necessity-decay acknowledgment:** [x] Acknowledged. Note: necessity for the federal Section 8 program itself may evolve based on broader housing policy; the authority commits to demonstrating reduction in scope or operational footprint over time, while acknowledging it cannot independently terminate the federal program.

**10.7 Aggregate trigger threshold:** 5 triggers in 90 days. SCBP-09 §II places authorities with non-consenting populations of 1,000–100,000 in the 5–25 range. Non-consenting population is ~4,200. The authority elects 5 — the floor — because the affected population is structurally vulnerable, has limited exit options, and faces meaningful retaliation risk for filing.

**10.8 Aggregate threshold justification:** As above. The framework's principle of "largest most underrepresented / most destructive harm" applies — voucher holders face severe consequences (homelessness, family separation) from termination, and their voice in civic systems is structurally underrepresented.

**10.9 Response time window:** 30 days (default).

**10.10 Response window justification:** Not required.

---

## SECTION 11 — What does this authority commit to publishing?

**11.1 Citizen ledger publication:** Quarterly. Includes: program metrics, demographic outcomes, complaints summary, HUD compliance status, contractor relationships, threshold-proximity indicators.

**11.2 Threshold change log:** Within 7 days.

**11.3 Interpretation change log:** Continuous.

**11.4 Renewal process visibility:** [x] Committed. Renewal review by parties drawn from affected categories: voucher holders, advocates for low-income housing, civil rights organizations, the voucher-holder Board member, fair-housing advocacy organizations.

**11.5 Stop event log:** [x] Acknowledged.

---

## SECTION 12 — Honesty assertions

**12.1 Disclosure completeness assertion:** [x] Asserted.

**12.2 Update obligation:** [x] Committed.

**12.3 Discoverability acknowledgment:** [x] Acknowledged.

**12.4 Burden of proof acknowledgment:** [x] Acknowledged.

**12.5 Anti-weaponization acknowledgment:** [x] Acknowledged.

---

## SECTION 13 — Submitter

*[Submitter information retained by registry as metadata.]*

---

*REG-RENTAL-SUBSIDY-ADMINISTRATION-EXAMPLE — worked example of a municipal Section 8 Housing Choice Voucher administrator*
*Registered under the Bounded Power Framework*
*All authority governed by the Structural Constitution (SCBP-04)*
