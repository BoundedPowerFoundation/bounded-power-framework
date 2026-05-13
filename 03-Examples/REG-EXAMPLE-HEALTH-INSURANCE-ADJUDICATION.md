---
mechanism_id: SCBP-REG-EXAMPLE-HEALTH-INSURANCE-ADJUDICATION
mechanism_name: "HEALTH-INSURANCE-ADJUDICATION-EXAMPLE"
status: EXAMPLE
domain: economic
authority_classification: indirect
registered_date: [DATE]
authorization_date: [AUTHORIZATION DATE]
expiration_date: [EXPIRATION DATE]
renewal_interval_years: 2
funding_types:
  - private_for_profit
  - federal_government_mandatory
funding_concentration_max_pct: 28
affected_party_categories:
  - general_public
  - non_consenting_third_parties
  - vulnerable_populations
  - children
  - patients_healthcare_recipients
affected_population_estimate: 50000000
non_consenting_population_estimate: 50000000
entity_size: institutional
geographic_specificity: single_nation
geographic_reach: "United States — national operations covering commercial insurance, Medicare Advantage, and ERISA self-funded plan administration; state-by-state regulatory variation"
aggregate_threshold_count: 200
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
dependency_count_type1: 38
dependency_count_type2: 14
dependency_count_type3: 9
capture_risk_identified: true
disclosure_completeness_assertion: true
update_obligation_committed: true
discoverability_acknowledged: true
burden_of_proof_acknowledged: true
anti_weaponization_acknowledged: true
---

# Mechanism Record — REG-HEALTH-INSURANCE-ADJUDICATION-EXAMPLE

**HEALTH-INSURANCE-ADJUDICATION-EXAMPLE**

| Field | Value |
|---|---|
| Mechanism ID | REG-HEALTH-INSURANCE-ADJUDICATION-EXAMPLE |
| Status | EXAMPLE |
| Registered | [DATE] |
| Authorization expires | [EXPIRATION DATE] |
| Domain | Economic |

---

## SECTION 1 — What is this authority?

**1.1 Mechanism name:** HEALTH-INSURANCE-ADJUDICATION-EXAMPLE — the claim-adjudication, prior-authorization, and utilization-management authority of a major health insurance carrier.

**1.2 Functional description:** The claim-adjudication and utilization-management function of a major health insurance carrier operating commercial insurance plans, Medicare Advantage plans, and administrative services for ERISA self-funded employer plans. This registration covers the claim-adjudication authority specifically; the carrier's broader operations (premium collection, provider network construction, marketing, financial reserves) are related but separately scoped. The carrier covers approximately 50 million members through some combination of fully-insured commercial plans, Medicare Advantage, Medicaid managed care (in some states), and ASO (administrative-services-only) administration of ERISA self-funded employer plans. Functional authority:

- *Pre-service:* Decides whether to approve prior authorization requests for prescribed care (medications, procedures, imaging, hospitalization, durable medical equipment, home health, mental health treatment, physical therapy) — denial means the care is not authorized, which functionally means the care does not occur for most members
- *During-service:* Decides whether ongoing care continues to meet medical necessity criteria — concurrent review during inpatient stays may produce a determination that further days are not authorized, requiring discharge or continued stay at the patient's financial risk
- *Post-service:* Decides whether to pay claims submitted by providers — denial means the provider goes unpaid, the patient bears the bill, or both
- *Formulary management:* Decides which medications are covered, in which tiers, with what step-therapy or quantity-limit restrictions; formulary exclusions mean the prescribed medication is not covered, requiring appeal, switch to alternative, or out-of-pocket payment
- *Network management:* Decides which providers are in-network; out-of-network care is typically not covered or covered at substantially lower rate; the No Surprises Act addresses some balance billing but substantial gaps remain
- *Medical necessity criteria:* Defines and applies criteria for what care is "medically necessary" using proprietary or licensed criteria sets (MCG, InterQual, carrier-specific guidelines); the carrier's clinical reviewers (physicians, nurses, sometimes lower-credentialed staff) apply these criteria to specific cases
- *Coverage determination:* Decides whether a particular service or item falls within plan coverage terms; ambiguous coverage terms are interpreted by the carrier
- *Internal appeals:* Operates the first-level appeals process; members and providers appeal denials internally before external review is available
- *External review:* Coordinates with independent review organizations (IROs) for external review of medical-necessity denials where applicable; ERISA self-funded plans, Medicare Advantage, Medicaid managed care, and commercial plans have varying external review structures
- *Provider contract enforcement:* Adjudicates disputes with contracted providers; deauthorization, audit, and contract-termination authority over network providers
- *Algorithmic adjudication:* Operationalizes automated denial, claim-edit, and utilization-management systems at scale; the carrier processes hundreds of millions of claims annually and most are adjudicated without individual human review

The carrier's authority is consequential because its decisions determine whether prescribed medical care actually occurs. A physician's recommendation that a patient receive a particular medication, procedure, or hospitalization is operationally subordinate to the carrier's authorization decision. For most patients, "denied" means the care does not occur or occurs only after substantial delay through appeal. The clinical and lived experience of "the insurance won't cover it" is the operational form of the carrier's authority over medical care.

The framework requires honest description of this operational reality, not the carrier's preferred self-description as a healthcare-financing administrator. Operationally:

- Prior authorization requests for care a physician has prescribed are denied at varying rates depending on plan, service category, and carrier; aggregate denial rates have been the subject of ProPublica investigation, congressional inquiry, GAO reports, and litigation
- Internal appeals are overturned at substantial rates; external reviews overturn medical-necessity denials at rates suggesting that a substantial portion of initial denials were not medically grounded
- Algorithmic denial systems have been the subject of class-action litigation alleging that algorithms produce mass denials with rates of error inconsistent with individualized medical-necessity determination
- Patients who do not appeal — because of administrative burden, lack of information about appeal rights, deteriorating health, or financial constraint — experience the initial denial as the final outcome
- Patients who appeal and are reversed have experienced the delay during the appeal as care withheld during the appeal period; for time-sensitive care, the delay itself is harm
- Patients who appeal and are not reversed have experienced denial of care a physician judged medically necessary, with consequences ranging from continued symptoms, missed treatment, switching to less-preferred treatment, to documented deterioration and in some cases death
- Out-of-network and balance-billing disputes produce financial harms that the No Surprises Act addresses for some categories but not all
- Mental health and substance-use disorder care has been subject to documented patterns of greater restriction than physical-health care, despite federal mental-health-parity law (MHPAEA) requiring equivalent treatment
- ERISA preemption removes state insurance commissioner authority over self-funded plans, leaving these plans subject to federal review with substantial deference to plan administrators
- Medicare Advantage plan denials have been subject to documented patterns of higher prior-authorization burden and denial rates relative to original Medicare

A second structural feature: the affected patient typically cannot distinguish between carrier decisions, contracted utilization-management vendor decisions, algorithmic decisions, and clinical-reviewer decisions. The denial appears to the patient as "the insurance company said no." The fragmentation of decision-making is invisible to the affected person.

The framework treats both the carrier's preferred self-description and the operational reality as the authority being registered. The form does not let the former substitute for the latter.

**1.3 Authority classification:** Indirect (primary). The carrier issues no binding directive that physical care must or must not occur. Authority operates through R58 — the carrier's outputs (authorizations, denials, formulary decisions, network determinations, payment decisions) materially shape decisions made by physicians, patients, hospitals, and pharmacies at scale.

The framework also recognizes a direct authority surface: the carrier directly determines what it will pay for, and the financial consequences of that determination fall on the patient, the provider, or both. At the scale of hundreds of millions of claims annually, the direct surface is itself enormous.

The carrier acknowledges that R58 classifies it as exercising authority, that R72 applies broadly because clinical-reviewer decisions, vendor utilization-management decisions, and algorithmic adjudication operate as carrier authority, and that R55/R59 recognize the commercial-insurance industry, the Medicare Advantage program, and the ERISA self-funded ecosystem as a coordinated authority system for many purposes.

**1.4 Domain:** Economic (primary). Healthcare (secondary). Technology (secondary, with regard to algorithmic adjudication infrastructure).

**1.5 Statutory or constitutional basis:** Operates under: state insurance regulation in approximately 50 states (commercial fully-insured business); the federal Employee Retirement Income Security Act (ERISA, 29 U.S.C. §1001 et seq.) governing self-funded employer plans (with substantial federal preemption of state regulation); the Medicare Modernization Act and CMS regulations governing Medicare Advantage plans; the Affordable Care Act (ACA) and CMS regulations on ACA-marketplace plans; the Mental Health Parity and Addiction Equity Act (MHPAEA); the No Surprises Act; HIPAA privacy and data-protection rules; state Department of Insurance authority (commercial fully-insured); state Medicaid authority (Medicaid managed care). Subject to: state and federal external review processes for medical-necessity denials; state and federal market-conduct examinations; federal court litigation under ERISA and ACA; class-action litigation; State Attorney General enforcement; CMS oversight (Medicare Advantage); HHS Office for Civil Rights (HIPAA, ACA Section 1557); Department of Labor (ERISA). Corporate existence under [STATE] corporate law; plan-level certification per state insurance regulation and federal program rules.

The framework's R28 (Expiration Default) requires that all authority expire absent affirmative renewal. Current law operates on multi-year regulatory and program cycles but does not provide a renewal mechanism in the framework's sense; the 2-year framework renewal cycle is a structural commitment beyond statutory requirement.

---

## SECTION 2 — Who can this authority act upon?

**2.1 Affected party categories:**
- [x] General public (members of plans the carrier operates and administers)
- [x] Non-consenting third parties — members typically did not select the carrier individually; employer-based members had the carrier selected by their employer; Medicare Advantage members chose Medicare Advantage but not necessarily this specific carrier (or may have been auto-enrolled in some configurations); Medicaid managed care members typically have limited carrier choice; ACA marketplace selections are constrained by what plans operate in the area; family members covered as dependents did not consent
- [x] Vulnerable populations: members with chronic illness, members with disabilities, members with mental illness, members with substance use disorder, members at end of life, members in pregnancy, members with rare diseases, members in oncology treatment, members on Medicaid, dual-eligible members, members with limited English proficiency, immigrant members, members in rural areas with limited provider networks, low-income members; providers in financial precarity dependent on timely payment
- [x] Children (under age of majority): pediatric members, children covered as dependents on parental plans, children with serious medical conditions, children in mental health treatment, neonatal intensive care recipients, children with disabilities requiring specialized care
- [x] Patients/healthcare recipients: members of all the above categories during episodes of care; patients during prior-authorization delay; patients during concurrent-review pressure for early discharge; patients in appeal pendency

**2.2 Approximate number of people directly affected:** ~50 million members across the carrier's product lines. Annual claims processed: hundreds of millions. Annual prior authorizations: tens of millions. Annual denial decisions reaching the member: millions. Annual appeals filed: hundreds of thousands.

**2.3 Non-consenting population:** Essentially all 50 million.

R14 (Non-Participant Exposure Mapping) and R26 (Non-Participant Harm Floor) apply with full force across the entire affected population.

The carrier acknowledges that the framework treats employer-based, Medicare Advantage, Medicaid managed care, and dependent populations as non-consenting in the framework's sense. Even members who chose the carrier within the constraints of available options operate under voluntary-but-stuck conditions: switching plans requires open-enrollment timing, may require changing physicians, may produce coverage gaps, and is constrained by the available plan landscape. R26's stricter harm tolerance applies.

**2.4 Vulnerable population specifics:**

- [x] Children — *yes*. Pediatric care, chronic-illness care for children, neonatal care, children's mental health care, children's specialty care all operate under the carrier's authority. Pediatric prior authorizations, formulary restrictions, and network limitations have particular consequence because children's care needs are time-sensitive (developmental windows for therapy, treatment timing for chronic conditions). The carrier commits to: pediatric-specific medical-necessity criteria where applicable; expedited appeals for urgent pediatric cases; mental-health-parity compliance for children. R26 substantial gaps acknowledged.
- [x] Patients during medical care — *yes; this is the central vulnerable population*. The entire carrier authority surface is exercised over patients in medical care or seeking medical care. Patients in active treatment cannot meaningfully negotiate; patients in declining health cannot effectively appeal; patients facing imminent need cannot wait through appeal timelines. The carrier commits to: expedited prior authorization for urgent care; expedited appeals for urgent denials; coverage during pendency where applicable; emergency-care coverage per EMTALA and applicable law. R26 substantial gaps acknowledged: the fact of coverage commitment does not eliminate the operational reality that prior authorization, denial, and appeal cycles produce delay during which patients deteriorate.
- [x] Detained or confined persons — partial; persons in nursing facilities, residential treatment, and rehabilitation facilities are confined and subject to the carrier's concurrent-review authority over continued stay. Concurrent-review-driven discharge of confined persons raises particular structural concerns.
- [x] Persons in coercive economic relationships — *yes*. Members in financial precarity who cannot afford out-of-pocket payment for denied care, members whose employer's plan choice they cannot affect, members in employer arrangements where complaint to HR carries career risk, providers in financial dependence on the carrier for payment — all are in coercive economic relationships. R26 substantial gap.
- [x] Persons unable to advocate for themselves — *yes*. Members with cognitive impairment, mental illness, limited English proficiency, limited literacy, children, persons in acute illness, persons with disabilities affecting communication face substantial advocacy disadvantage in prior-authorization, denial, and appeal processes. The carrier commits to: language access in member communications; reasonable accommodation in appeal processes; expedited handling for cases where capacity is in question; family-member or representative engagement where appropriate. R26 substantial gaps acknowledged.

The carrier acknowledges that R26 (stricter harm tolerance for non-participants) applies with particular weight because essentially all 50 million affected persons are non-consenting and substantial portions are vulnerable across multiple categories simultaneously, and because the affected condition (medical illness or need for medical care) is itself a vulnerability the framework treats as foundational.

---

## SECTION 3 — What can it do, and what can it not do?

**3.1 Geographic reach:** United States — national operations across approximately 50 state regulatory environments, Medicare Advantage in CMS-approved service areas, Medicaid managed care in contracted states, ACA marketplace plans in elected service areas. ERISA self-funded plan administration is national and substantially preempts state regulation.

**3.2 Coercive ceiling:** No direct coercive authority over patients in the legal sense; the carrier cannot compel a patient to accept or decline care. Authority operates through:

- *Prior authorization:* Approve, deny, partially approve, or require modification of provider-prescribed care; denial or modification effectively determines whether the care occurs as prescribed
- *Concurrent review:* During inpatient stays, determine whether further days are authorized; denial of further days produces pressure for discharge or continued stay at patient financial risk
- *Post-service claim adjudication:* Approve, deny, partially approve, or downcode submitted claims; denial means the patient or provider bears the cost
- *Formulary determinations:* Cover, exclude, tier-restrict, step-therapy, quantity-limit prescribed medications
- *Medical necessity application:* Apply medical-necessity criteria to specific cases; criteria are proprietary or licensed
- *Network construction and maintenance:* Determine which providers are in-network; deauthorize, audit, or terminate provider contracts
- *Appeal adjudication:* Operate internal appeals; coordinate external review where applicable
- *Vendor management:* Contract utilization-management vendors, pharmacy benefit managers, behavioral health vendors, and others; their decisions become carrier authority for affected members
- *Algorithmic adjudication:* Deploy automated systems for claim adjudication, prior authorization screening, and utilization management; most claims are adjudicated without individual human review

The carrier may NOT (per applicable law and contract):
- Operate in violation of state insurance regulation, ERISA, ACA, MHPAEA, or applicable program rules
- Deny coverage in violation of plan terms
- Apply discriminatory rules in violation of ACA Section 1557 or applicable civil rights law
- Operate emergency care coverage in violation of EMTALA-aligned requirements
- Operate prior authorization in ways that violate applicable state law (some states impose limits on prior-authorization scope, response timelines, and gold-carding for high-approval-rate providers)
- Operate mental health benefits in ways that violate MHPAEA's parity requirements
- Use member health information beyond HIPAA-authorized purposes
- Violate the No Surprises Act on emergency and certain non-emergency out-of-network billing
- Process appeals in violation of applicable timelines (typically 30 days standard, 72 hours expedited for urgent care)
- Discriminate on protected characteristics

**3.3 Resource ceiling:** For a major health insurance carrier:
- Annual revenue: tens of billions to ~$300 billion (varies by carrier scale)
- Operating budget for adjudication infrastructure: substantial portion of administrative expense
- Staff: tens of thousands of FTE including clinical reviewers, medical directors, claims processors, customer service, appeals analysts
- Vendor relationships: pharmacy benefit managers, utilization management vendors, behavioral health vendors, dental and vision vendors, others
- Infrastructure: claims-adjudication technology, prior-authorization systems, member portals, provider portals, algorithmic adjudication systems

**3.4 Explicit exclusions:**
- **Geographic:** Operations in elected jurisdictions; subject to state-by-state regulatory variation and federal program coverage areas
- **Action:** May not exceed plan terms; may not violate applicable insurance regulation, ERISA, ACA, MHPAEA, EMTALA, No Surprises Act; may not retaliate against members for filing appeals or complaints
- **Data:** Subject to HIPAA; member health information limited to authorized uses; subject to state data-protection law; subject to ACA Section 1557 nondiscrimination
- **Procedural:** Appeal timelines per applicable law; denials must include specific reasons; medical-necessity denials in fully-insured commercial plans are subject to external review per state law; ERISA plans subject to federal external review under ACA-aligned standards; expedited handling for urgent cases per applicable law
- **Other:** Provider contract terms; vendor contractual constraints; CMS Medicare Advantage program rules; state Medicaid managed care contracts

**3.5 Indirect influence boundaries:** Substantial. This is the load-bearing section.

The carrier's outputs propagate widely and shape medical care across the population:

- *Prior authorizations* determine what care occurs; the operational form of "your insurance has approved" or "your insurance has denied" is the structural shape of medical access for most members
- *Denial decisions* shape: whether a medication is taken (formulary denials, step therapy); whether a procedure occurs (prior auth denials); how long a hospital stay continues (concurrent review); whether mental health treatment occurs (mental-health-specific patterns); whether physical therapy continues (medical-necessity reviews); whether durable medical equipment is provided; whether home health continues; whether long-term care services are authorized
- *Formulary decisions* shape pharmaceutical industry behavior, drug pricing negotiations, and patient access to specific medications. Formulary exclusions of brand-name drugs, requirements for generic substitution, step therapy through cheaper alternatives — each shapes care for affected patients
- *Network decisions* shape which physicians, hospitals, and specialists are accessible; out-of-network care is typically not covered or covered at substantially lower rate; for some members in some markets, the network is the practical universe of available care
- *Medical-necessity criteria* shape clinical decision-making across the system; physicians anticipate carrier criteria when prescribing; the criteria functionally become medical practice standards even where the criteria do not match clinical evidence
- *Provider contract terms* shape physician practice patterns, hospital operations, and provider economic viability; carriers' negotiating positions shape medical care availability
- *Adjudication logic propagated to electronic health record vendors and to physician practices* shapes how providers document care, what services they recommend, and what they prescribe
- *Patient health outcomes* — actual health, illness, recovery, deterioration, death — are shaped by the adjudication outputs

R58 applies with full force. The carrier acknowledges that its outputs exercise authority over medical care at population scale despite operating through indirect mechanisms. The framework's R58 explicitly classifies systems of this kind as exercising authority.

The framework also recognizes a propagation pattern specific to health insurance: providers who repeatedly experience carrier denials of particular categories of care begin practicing in ways that anticipate denial — prescribing the formulary-preferred medication first regardless of clinical preference, reducing referrals for specialist consultation, shortening visit length, omitting recommendations for care likely to be denied. The carrier's authority shapes medical practice beyond its immediate decisions; this is the most pervasive form of R58 effect in the system.

**3.6 Anti-proxy declaration:**

The carrier commits to not using:

- *Proxy for race, ethnicity, national origin in adjudication:* Coverage decisions, medical-necessity determinations, prior-authorization outcomes may not be based on these characteristics. Acknowledged that operational practice in algorithmic adjudication has produced documented disparate-impact concerns; aggregate disparate-impact testing of adjudication outputs committed; results published. R66/R74 finding acknowledged at registration as a foundational structural finding.
- *Proxy for disability status as denial basis:* Denials may not effectively use disability-related circumstances (treatment plans for disability, accommodations needed, specialist care required) as basis for adverse determination. Acknowledged that operational practice has produced documented patterns affecting members with disabilities, particularly in long-term care, mental health, and rare-disease categories. R66 substantial finding.
- *Proxy for mental illness as restriction basis:* Mental health and substance-use disorder benefits may not be subject to greater restriction than physical-health benefits in violation of MHPAEA. Acknowledged that documented patterns of MHPAEA noncompliance have produced regulatory action and litigation against the sector. R66 finding requiring active monitoring.
- *Proxy for socioeconomic status:* Adjudication may not effectively use markers of poverty (Medicaid coverage, low-income subsidy status, address in lower-income area) as proxy for restriction. Acknowledged that operational variations in prior-authorization burden, network adequacy, and appeal handling may correlate with member economic status.
- *Proxy for high-cost member status:* Adjudication may not effectively target members based on prior cost or anticipated cost. Acknowledged that risk-adjustment systems and high-cost-member tracking can interact with adjudication in ways that approach this concern.
- *Proxy for end-of-life status:* Adjudication of end-of-life care may not effectively use prognosis as proxy for restriction. Acknowledged that operational practice in inpatient utilization management may produce patterns of pressure for hospice transition or discharge that precede patient or family readiness.
- *Proxy for non-English language:* Members with limited English proficiency may not face differential adjudication, appeal, or service. Acknowledged that operational practice has documented gaps; remediation committed.

The carrier acknowledges that all seven proxy commitments require ongoing structural attention, that historical and current practice in the sector has produced repeated R66 findings, and that the fragmentation of decision-making across vendors, algorithmic systems, and human reviewers makes proxy-effect monitoring particularly difficult.

---

## SECTION 4 — What harms can it cause?

**4.1 Bodily harm threshold:** Load-bearing.

The carrier's adjudication decisions produce direct and indirect bodily harm pathways:

- *Care delay during prior authorization:* Time-sensitive care delayed during prior-authorization review, denial, and appeal cycles produces documented deterioration. Threshold: prior-authorization timelines exceeding applicable regulatory windows, in any case where deterioration is documented during the delay, trigger individual review; aggregate timeline-failure rates trigger systemic review
- *Care denial producing missed treatment:* Denials of medically prescribed care, where the affected condition deteriorates during pendency or after final denial, trigger review. Aggregate deterioration-following-denial patterns require structural attention
- *Concurrent-review-driven discharge producing post-discharge harm:* Discharges following concurrent-review denial of further inpatient days, where post-discharge complications occur, trigger review
- *Formulary-driven medication discontinuation:* Members forced to switch medications due to formulary changes, with documented clinical decompensation, trigger review
- *Network-related bodily harm:* Members unable to access timely care due to network limitations, with documented harm, trigger review
- *Mental health and substance use disorder denials:* Documented patterns of greater restriction in mental health than physical health, including denials producing documented suicide, self-harm, or overdose, trigger MHPAEA-specific review and structural response
- *Maternal care decisions:* Prior authorization and concurrent review affecting prenatal, delivery, and postpartum care, where adverse maternal or neonatal outcomes occur, trigger review
- *End-of-life care decisions:* Decisions producing pressure for hospice transition or treatment discontinuation that precede patient or family readiness, with documented harm, trigger review
- *Death attributable to adjudication:* Any death where adjudication-driven care delay, denial, or restriction is identifiable as contributing factor triggers external investigation and public summary; aggregate adjudication-attributable mortality monitored where data permits

The carrier acknowledges that R26 (Non-Participant Harm Floor) applies with particular weight to bodily-harm thresholds in this context because affected members are in medical illness or need for medical care at the time of adjudication contact. The framework's stricter tolerance for harm to non-participants is foundational here.

**4.2 Agency impairment threshold:** Substantial.

- *Appeal accessibility:* Members unable to navigate appeal processes due to language, disability, capacity, or administrative complexity — finding for each documented instance; aggregate appeal-accessibility metrics tracked
- *Adverse-determination notice failures:* Denial notices without specific reasons, applicable criteria, appeal-rights information — finding for each instance
- *Timeline failures:* Prior authorization, concurrent review, appeal, and external review processes outside applicable timelines — findings for each instance; aggregate timeline-compliance metrics tracked
- *Information barriers:* Members unable to obtain the medical-necessity criteria applied to their case, the clinical reviewer's credentials, or the basis for denial — finding
- *External review barriers:* Members unable to access external review where applicable, due to lack of information, timing, or procedural failures — finding
- *Provider-side adjudication burden:* The administrative burden imposed on providers (prior authorization paperwork, peer-to-peer review requirements, claim resubmission cycles) has been documented as itself a structural concern affecting care quality and access; aggregate provider-side burden tracked

**4.3 Ecological damage threshold:** Limited applicability. Operations have computing-resource footprint; environmental compliance per applicable standards.

**4.4 Generational binding threshold:** Substantial.

The carrier's actions produce intergenerational and long-duration effects:

- *Chronic-condition trajectories:* Members with chronic conditions whose care is constrained by prior authorization, formulary, and utilization management throughout their illness experience cumulative effects that shape long-term outcomes; effects compound across years and decades
- *Pediatric care effects:* Children whose care is constrained during developmental windows experience effects on developmental outcomes, educational outcomes, and adult health trajectories
- *Disability-related care effects:* Members with disabilities whose long-term-care, durable-medical-equipment, and specialist care is subject to ongoing utilization management experience compounding effects on independence and quality of life
- *Mental health trajectories:* Members whose mental health and substance-use treatment is constrained experience effects on long-term mental health, employment, family relationships, and life trajectory
- *Records of denials and appeals* propagate to provider records, employer health-benefit records (in some configurations), and into the carrier's own decision-making for subsequent encounters
- *Generational health-equity effects:* Disparate-impact patterns in adjudication propagate through families and across generations in ways that subsequent reform cannot retroactively address

Threshold: any policy change with substantial cumulative effects (formulary restructuring affecting chronic-condition members; network changes affecting specialty care availability; medical-necessity criteria changes affecting categories of care) requires impact analysis with attention to cumulative effects and disparate impact.

**4.5 Communicative suppression threshold:**
- *Retaliation against members for filing complaints, appeals, or litigation:* — finding for documented patterns
- *Restrictions on member communication with providers about coverage:* — finding
- *Provider gag clauses* (historical concern; addressed by federal law but persistent practice in some configurations) — finding for each documented instance
- *Restrictions on patient sharing of denial information:* — review
- *Suppression of mental-health-parity violation reporting:* — finding

**4.6 Informational sovereignty threshold:**
- HIPAA violations — finding per applicable law
- Member health information shared beyond authorized purposes — finding
- Records retained beyond stated retention or beyond regulatory minimum — review
- Coordination with employers on member health information beyond authorized scope — finding
- Records errors that affected members cannot identify or correct — finding for each substantiated instance; aggregate error rates monitored
- Algorithmic adjudication training data that improperly incorporates member health information — finding

**4.7 Additional harm thresholds:**

*Chronic asymmetry threshold:* If denial rates, appeal-overturn rates, or care-access patterns correlate with race, ethnicity, national origin, disability, mental health status, geography, or other characteristic at p<0.05 controlling for medical factors, this triggers systemic review. The framework treats persistent disparate-impact patterns documented in the sector as standing structural findings.

*Mental health parity threshold:* Aggregate mental health and substance-use disorder benefit administration metrics tracked against physical-health benefit metrics; nonquantitative treatment limits assessed for parity per MHPAEA; deviations trigger immediate review.

*Algorithmic adjudication threshold:* Aggregate algorithmic adjudication denial rates, error rates, and disparate-impact patterns monitored; rates exceeding thresholds trigger algorithm review and remediation; rates inconsistent with individualized medical-necessity determination trigger structural review.

*Concurrent-review threshold:* Aggregate concurrent-review-driven early-discharge rates monitored; rates exceeding peer benchmarks trigger review.

*Appeal-overturn threshold:* If internal appeal overturn rates exceed thresholds, this indicates that initial denials are inconsistent with applicable criteria; aggregate review and structural response committed.

*External-review-overturn threshold:* If external-review overturn rates exceed thresholds, this indicates that internal-review denial-affirmation is inconsistent with medical evidence; aggregate review and structural response committed. Documented external-review overturn rates suggest the threshold is currently exceeded sector-wide; this is itself a standing finding.

*Prior-authorization burden threshold:* Aggregate prior-authorization volume, response timelines, and burden metrics tracked; sector-level data suggests burden exceeds proportional to risk, consistent with documented physician-side and patient-side concerns.

*Network-adequacy threshold:* Member geographic and specialty access metrics monitored; failures trigger network expansion or coverage adjustment.

**4.8 Threshold change-log commitment:** [x] Yes — committed.

---

## SECTION 5 — What stops it?

This section requires honest engagement with the structure of private adjudicative authority in healthcare, where regulatory oversight is substantial in formal terms but the operational reality of stop-path effectiveness is mixed.

**STOP PATH 1 — State insurance regulation, federal program oversight, and external review**
- *Activator:* State Departments of Insurance (commercial fully-insured); CMS (Medicare Advantage, ACA marketplace); state Medicaid agencies (Medicaid managed care); state external review entities (medical-necessity denials in commercial); federal external review (ACA-aligned, ERISA self-funded plans); HHS Office for Civil Rights (Section 1557, HIPAA); Department of Labor (ERISA).
- *Trigger:* Determination of regulatory violation, market-conduct finding, program rule violation, supervisory finding.
- *What "stopped" means:* Cease-and-desist orders affecting specific practices; civil penalties; required operational changes; corrective action plans; in extreme cases license revocation or program termination. Specific remedies available in external review (overturning specific denials).
- *Independence:* State insurance commissioners are independent of carriers but vary substantially in regulatory aggressiveness; CMS and HHS are federal agencies with statutory independence. *Acknowledged limitation:* State insurance regulation is uneven across 50 states; commercial-fully-insured business is subject to state regulation but ERISA self-funded plans (a substantial portion of carrier business) preempts state regulation; CMS oversight of Medicare Advantage has been documented as inadequate by GAO and Inspector General; market-conduct examinations are intermittent; civil penalties for documented violations have historically been modest relative to the financial scale of the carriers.
- *Timeline:* Per agency procedures; specific external reviews may be expedited (72 hours for urgent care); systemic enforcement actions span years.

**STOP PATH 2 — Federal court litigation: ERISA, ACA, MHPAEA, antitrust, class action**
- *Activator:* Members and providers with standing under ERISA, ACA, MHPAEA, state insurance law (where not preempted); class action plaintiffs; State Attorneys General; HHS; DOJ.
- *Trigger:* Court determination of statutory or contractual violation.
- *What "stopped" means:* Court orders may halt specific practices, void specific actions, impose damages, require operational changes; class actions may produce sector-wide remediation. Recent algorithmic-denial litigation has produced substantial class settlements.
- *Independence:* Federal courts and DOJ are structurally independent. *Acknowledged limitation:* ERISA's standard of review is deferential to plan administrators in many cases; ERISA preemption limits state-law remedies; MHPAEA enforcement has been documented as inadequate by GAO; antitrust enforcement against vertical integration in healthcare has been intermittent; class-certification standards limit collective remediation.
- *Timeline:* Per federal procedures; major class actions span years.

**STOP PATH 3 — Provider organization, employer pressure, market action, public attention**
- *Activator:* Provider organizations (medical societies, hospital associations, specialty societies); employers as plan purchasers; market entry by alternative configurations; concentrated public attention to specific denials; investigative journalism; congressional inquiry.
- *Trigger:* Provider-side action; employer market signals; public attention events; legislative scrutiny.
- *What "stopped" means:* Provider-side action may produce contract leverage and practice-pattern shifts; employer pressure may shift carrier behavior; public attention may produce specific reversals (the carrier has reversed specific denials following sustained public attention; affected members are typically high-profile rather than typical); legislative scrutiny may produce statutory or regulatory change.
- *Independence:* Providers, employers, and the press are independent of the carrier. *Acknowledged limitation:* Provider-side leverage depends on market position; employer leverage varies by employer scale; public attention is selective and benefits high-profile cases more than typical denials; legislative response is incremental.
- *Timeline:* Per actor.

**5.4 Penalty for activating stop:** [x] Confirmed in policy. *Acknowledged structural concerns:* Members who file complaints with regulators or pursue litigation may face informal disadvantage in subsequent adjudication; providers who appeal denials aggressively or file complaints may face network-status review; the carrier's stated commitment is non-retaliation; the documented gap between commitment and operational reality is itself a recurring concern.

**5.5 Stop-path independence verification:** State and federal regulators, courts, and providers/employers/press are structurally independent of the carrier. *Acknowledged R03 (Institutional Capture) finding:* The carrier engages in extensive lobbying, regulatory consultation, and revolving-door personnel patterns with state and federal regulators. The sector overall has substantial political influence on the legislative and regulatory frameworks under which it operates. R03 finding acknowledged.

*Acknowledged R55/R59 finding:* The commercial-insurance, Medicare Advantage, and ERISA self-funded plan ecosystem functions as a coordinated authority system in many respects despite consisting of multiple competing carriers. Industry-wide practice on prior authorization, formulary management, network construction, and adjudication infrastructure converges through trade associations, standards bodies, vendor commonalities, and shared regulatory environment. Containment review of any single carrier is incomplete without addressing the sector.

*Acknowledged R64 (External Circumvention) finding:* The use of contracted utilization-management vendors, pharmacy benefit managers, behavioral health vendors, and algorithmic adjudication systems means the carrier operationalizes external authorities' decisions as its own; the affected member experiences carrier authority but the underlying decision may be vendor or algorithmic. R72 applies broadly; the affected member's recourse is structurally fragmented.

**5.6 Civic trigger acknowledgment:** [x] Acknowledged.

---

## SECTION 6 — What does it depend on?

**6.1 Type 1 dependencies:**

The carrier operates with approximately 38 Type 1 dependency categories, including:
- Pharmacy benefit manager (typically a major PBM; substantial structural relationship; per-member-per-month or per-claim compensation)
- Utilization management vendors (medical, behavioral health, post-acute care, durable medical equipment)
- Behavioral health vendor (in some configurations; carve-out arrangements have been the subject of MHPAEA litigation)
- Provider network (hundreds of thousands of in-network providers under contract)
- Hospital network (thousands of contracted hospitals and health systems)
- Medical-necessity criteria vendors (MCG, InterQual, or equivalent licensed criteria)
- Claims-processing technology vendors
- Algorithmic adjudication vendors and in-house systems
- Pharmacy network and retail pharmacy partners
- Customer-service contractors
- Appeals-administration contractors
- Independent review organizations (for external review; technically independent but sector-wide rostered)
- Identity-verification vendors
- Cloud and computing infrastructure providers
- Consulting and actuarial vendors

**Funding-source disclosure:** Funded through premium revenue (commercial fully-insured), capitation revenue (Medicare Advantage, Medicaid managed care), and ASO administrative fees (ERISA self-funded). No single payer source exceeds approximately 28% of revenue at carrier level.

**6.2 Type 2 dependencies:**
- State Departments of Insurance in approximately 50 states
- Centers for Medicare and Medicaid Services
- HHS Office for Civil Rights
- Department of Labor (ERISA)
- State Medicaid agencies (in states with Medicaid managed care contracts)
- State attorneys general
- The other major commercial insurers (R55 sector-coordination through trade associations and shared infrastructure)
- Pharmaceutical manufacturers (formulary negotiation counterparties)
- Provider organizations (network negotiation counterparties)
- Employer plan sponsors (ASO customers)
- Medicare Advantage CMS rule-making and program oversight

**6.3 Type 3 dependencies:**
- *Pharmacy benefit manager relationships:* Substantial vertical integration in many configurations; if PBM relationship terminated or modified, formulary administration is substantially compromised
- *Medical-necessity criteria vendor:* If access lost, the criteria framework for adjudication is compromised; vendor IP makes substitution costly
- *Algorithmic adjudication infrastructure:* Multi-year vendor and in-house system commitments
- *Provider network:* Loss of major health systems compromises network adequacy
- *Cloud and computing infrastructure:* Concentration in a few large providers
- *Medicare Advantage program continuation:* CMS program-level changes affect substantial revenue
- *State Medicaid contracts:* Multi-year contracts with cancellation implications
- *Regulatory infrastructure:* If regulatory capacity (state Departments of Insurance, CMS) compromised, stop paths 1 and 2 partially compromised
- *External review infrastructure:* Independent review organization rostering and quality

**6.4 Capture risk identification:** [x] Yes. Substantial.

- *Vertical integration:* Several major commercial carriers are vertically integrated with PBMs, provider organizations, pharmacy chains, and other elements of the healthcare delivery system. Vertical integration creates structural alignment that complicates negotiating dynamics with non-aligned providers and pharmaceutical manufacturers and may produce internal-coordination effects that approach R55. R55 finding acknowledged.
- *Sector concentration:* The commercial insurance sector is concentrated; a handful of carriers cover substantial portions of the commercial-insured population. Sector-level coordination through trade associations, shared standards, and shared vendors approaches R55/R59 functional consolidation. R55/R59 findings acknowledged.
- *Regulatory capture:* The carrier engages in substantial lobbying and regulatory consultation. Industry positions shape regulatory framework development. Documented patterns of regulatory under-enforcement have been the subject of GAO and Inspector General reports. R03 finding acknowledged.
- *Vendor capture:* PBM, utilization management, criteria vendor, and algorithmic adjudication vendor relationships create switching costs and shape carrier operations. The medical-necessity criteria vendors (MCG, InterQual, others) operate as quasi-standards bodies for the sector.
- *Employer-customer capture:* Large employer ASO customers shape carrier behavior in ways that may or may not align with member interests; ERISA preemption removes state regulatory check on this.
- *PBM-pharmaceutical-manufacturer capture:* Pricing-and-rebate arrangements between PBMs, manufacturers, and carriers shape formulary in ways that may not align with patient clinical interests; documented rebate structures have been the subject of antitrust investigation and litigation.
- *Algorithmic vendor capture:* Algorithmic adjudication vendor relationships create lock-in; vendor IP restrictions limit auditability.
- *Revolving-door personnel:* Movement between carrier, regulator, and political offices creates relational dependencies.

**6.5 Reversibility-affecting dependencies:**
- Records propagated to provider records, employer records (in some configurations), and HIPAA-covered downstream systems cannot be recalled
- Adjudication-driven medical decisions (treatments not received, treatments completed, treatments delayed) cannot be undone
- Member health outcomes shaped by adjudication are durable
- Multi-year vendor contracts
- Pension and personnel obligations
- Regulatory program participation contracts

**6.6 Coordination disclosures:**

The carrier coordinates with:
- The other major commercial carriers (trade association activity, standards bodies, shared vendor relationships, shared regulatory engagement)
- Pharmacy benefit managers (vertical or contractual)
- Medical-necessity criteria vendors (MCG, InterQual, others operate as sector-wide standards)
- Provider organizations (contractual)
- CMS and state regulators (program-level coordination)

**Acknowledged R55/R59 finding:** The commercial-insurance and Medicare Advantage sector functions operationally as a coordinated authority system in substantial respects. Containment review of any single carrier is incomplete without addressing the sector and its supporting vendor and standards ecosystem. R55 (Fragmentation Must Not Defeat Containment) and R59 (Functional Continuity Consolidation) apply.

**Acknowledged R64 finding:** The use of contracted PBMs, utilization-management vendors, medical-necessity criteria, and algorithmic adjudication systems means external systems' outputs become operational carrier authority. R72 applies broadly. The fragmentation of decision-making across these vendors and systems means affected members typically cannot trace adjudication outcomes to specific decision-makers.

**6.7 Disclosure completeness assertion:** [x] Asserted with the standard acknowledgment that complete dependency mapping at this scale is structurally unattainable; vendor contracts, PBM rebate arrangements, algorithm methodologies, and customer-specific (employer) terms are partially restricted from disclosure.

**6.8 External authority operationalization:**

This is the most extensive R72 surface in the registration.

- *Pharmacy benefit manager decisions:* PBM formulary tiers, prior-authorization decisions on medications, rebate-driven formulary placement, step-therapy requirements — operationalized as carrier authority. R72 applies. Members typically cannot distinguish PBM decisions from carrier decisions.
- *Utilization management vendor decisions:* Vendor clinical reviewers' medical-necessity determinations, denial recommendations, concurrent-review decisions — operationalized as carrier authority. R72 applies.
- *Medical-necessity criteria (MCG, InterQual, others):* Vendor criteria become the operational standards applied to specific cases. R72 applies. The criteria themselves are licensed IP with restricted member access.
- *Algorithmic adjudication systems:* Automated denial, claim-edit, and authorization systems make decisions that become carrier authority. R72 applies. Algorithmic methodology is partially restricted as vendor IP and proprietary.
- *Behavioral health vendor decisions* (in carve-out configurations): Vendor decisions on mental health authorization, network, and benefits become carrier authority. R72 applies. Documented MHPAEA-violation patterns in carve-out arrangements have been the subject of regulatory action.
- *Independent review organizations:* IRO determinations on external review become operational outcomes; though IROs are nominally independent, sector-wide rostering and the dependence of IRO business on carrier referrals create structural alignment concerns. R72 partial finding.
- *Provider contract enforcement:* Provider deauthorization, audit, and contract-termination decisions — operationalized as authority over network and member access. R72 applies.
- *Pharmaceutical manufacturer contracts and rebate structures:* Rebate-driven formulary decisions operationalize external manufacturer-carrier negotiation outcomes as authority over patient access to specific medications. R72 applies. Antitrust litigation has surfaced concerns about anticompetitive effects of these structures.

R64 (External Circumvention) is acknowledged: the use of contracted vendors, PBMs, and algorithmic systems may produce decisions affecting medical care that would, if attributable to a single regulated authority, be subject to greater scrutiny; the fragmentation of decision-making across these vendors operates as a structural feature that the framework's R64 specifically addresses.

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

**7.1 Declared metrics:**

| Metric | Source | Role | Public? |
|---|---|---|---|
| Prior-authorization volume, approval rates, response times | Internal systems | Operational | Aggregate yes |
| Denial rates by service category, geographic region | Internal systems | Operational | Aggregate yes |
| Appeals volume and outcomes | Internal systems | Quality monitoring | Aggregate yes |
| External review outcomes | External review entities, internal records | Quality monitoring | Aggregate yes |
| Concurrent-review activity and outcomes | Internal systems | Operational | Aggregate yes |
| Medical-loss ratio | Financial systems | Regulatory | Aggregate yes (per state and federal requirements) |
| Network adequacy metrics | Internal systems | Regulatory | Aggregate yes (per applicable rules) |
| Formulary changes, exceptions, appeals | Internal systems | Operational | Aggregate yes |
| Provider audit and contract action | Internal systems | Operational | Aggregate partial |
| Algorithmic adjudication metrics | Internal systems | Operational | Aggregate partial |
| Customer service contact volumes and resolution | Internal systems | Quality | Aggregate yes |
| Claims-processing accuracy and timeliness | Internal systems | Quality | Aggregate yes |
| Mental health parity metrics (NQTLs, quantitative) | Internal systems | MHPAEA compliance | Aggregate yes (per requirements) |

**7.2 Indirect signals:**
- *Clinical reviewer judgment:* Substantial. Same case may produce different determinations across reviewers within the same medical-necessity criteria framework
- *Medical director discretion:* Senior clinical authority shapes policy interpretation and edge cases
- *Algorithm features:* Algorithmic adjudication systems use many features beyond the primary clinical inputs; some are derived (utilization patterns, prior denials, prior appeals); some are inferred
- *Vendor decisional logic:* PBM, utilization-management vendor, behavioral health vendor decisional logic shapes outcomes in ways the carrier may not fully see
- *Cost considerations:* While medical-necessity is the formal criterion, cost considerations have been documented as influencing operational practice
- *Employer customer signaling:* Large employer ASO customers may signal preferences for utilization-management aggressiveness; these signals shape adjudication
- *Public-attention sensitivity:* High-profile cases may produce different handling than typical cases; this is a documented informal pattern

**7.3 Algorithmic decision systems:**

[x] Yes. Multiple systems with substantial R66/R67/R72/R79 implications:

- *Algorithmic claim adjudication:* Most claims are adjudicated through automated systems applying claim-edit rules, eligibility checks, coverage rules, network rules, and other logic. Methodology partially restricted; vendor IP in some cases. R67 partial gap acknowledged.
- *Algorithmic prior-authorization screening:* Some prior authorizations are screened through automated systems for approval, denial, or routing to clinical review. Recent litigation has surfaced concerns about denial patterns inconsistent with individualized medical-necessity determination. R67 substantial gap.
- *Algorithmic concurrent-review systems:* Some concurrent-review determinations operate through automated logic.
- *Algorithmic claim-edit systems:* Substantial automated logic applies to claim adjudication for completeness, eligibility, billing accuracy, and coverage.
- *Predictive analytics for utilization management:* Predictive models identify members for case management, utilization management focus, and other interventions. Methodology restricted.
- *Provider audit algorithms:* Identify providers for audit based on billing patterns, utilization patterns, and other features.
- *Risk-adjustment algorithms:* CMS-specified for Medicare Advantage; commercial risk adjustment per ACA.

The carrier acknowledges that algorithmic systems in health insurance adjudication raise substantial R66 (proxy for protected characteristics), R67 (auditability floor), R72 (external operationalization), and R79 (metric completeness) concerns. Recent litigation and regulatory attention has surfaced documented patterns; aggregate disparate-impact testing committed; methodology disclosure committed where contractually permitted; third-party algorithm audit committed.

**7.4 Outcome-versus-declaration check:** [x] Committed. R79 (Metric Completeness) gap acknowledged: outcome patterns (particularly denial-rate disparate-impact patterns, mental-health-parity nonquantitative-treatment-limit patterns, and algorithmic adjudication anomalies) cannot be fully predicted from declared metrics; the framework presumes undeclared influence.

---

## SECTION 8 — How is this authority watched?

**8.1 Drift monitoring:**
- Internal compliance and audit functions
- Internal medical management quality assurance
- External annual audit (financial; HEDIS, NCQA accreditation)
- State Department of Insurance market-conduct examinations
- CMS Medicare Advantage monitoring (Star Ratings, audits, plan-level oversight)
- State Medicaid managed care oversight
- Department of Labor ERISA oversight
- HHS Office for Civil Rights (Section 1557, HIPAA)
- GAO and Inspector General reports
- Civil society monitoring (consumer advocacy organizations, patient advocacy groups, provider organizations, academic researchers, investigative journalists)
- Litigation (substantial ongoing class-action and individual litigation)

The carrier acknowledges that drift detection in health insurance is structurally challenged by: confidentiality of business operations and member health information; complexity of multi-jurisdictional and multi-program operations; ERISA preemption limiting state oversight of self-funded plans; uneven regulatory attention; political contestation of healthcare regulation.

**8.2 Capture risk monitoring:**
- Annual disclosure of vendor relationships and concentration
- Lobbying and political-spending disclosure
- Government affairs disclosure
- Major regulatory positions disclosure
- Vertical integration disclosure
- Revolving-door personnel tracking

**8.3 Audit interfaces:**
- *Proactively published:* Annual financial reports; HEDIS quality measures; Star Ratings (Medicare Advantage); MLR reporting; aggregate operational metrics; specific public-disclosure-required documents per regulation
- *Available on request per applicable law:* Specific records to regulators and litigants
- *Restricted:* Algorithm internals (vendor IP, competitive); PBM rebate arrangements (competitive, antitrust-sensitive); employer ASO customer-specific terms (competitive); medical-necessity criteria (vendor IP for licensed criteria); deliberative materials; specific clinical reviewer decisions and reasoning beyond denial-notice content; pharmaceutical manufacturer contract terms

**8.4 Adversarial exposure (R81):** Substantial gaps acknowledged.
- Algorithm internals partially restricted (vendor IP and proprietary)
- Medical-necessity criteria internals partially restricted (vendor IP)
- PBM rebate and pricing arrangements partially restricted (competitive and antitrust-sensitive)
- Customer-specific (employer) terms partially restricted (competitive)
- Specific clinical reviewer decisions partially restricted (deliberative)
- Member health information appropriately restricted (HIPAA)
- Vendor specific operational details partially restricted

R67 (Minimum Auditability Floor) compliance is substantially compromised by these restrictions. The carrier acknowledges this as a structural finding and not merely as temporary information-sharing limitations.

**8.5 Known structural failure modes:**
- Disparate impact in adjudication outcomes by race, ethnicity, geography, disability, mental health status
- Mental health parity violations
- Prior-authorization-driven care delay producing patient harm
- Algorithmic adjudication producing mass denials inconsistent with individualized determination
- Concurrent-review-driven early discharge producing post-discharge harm
- Formulary-driven medication discontinuation harm
- Network-adequacy failures producing care-access barriers
- Out-of-network and balance-billing harm (No Surprises Act has addressed but gaps remain)
- ERISA preemption limiting member remedies
- Vendor decisional fragmentation reducing accountability
- Appeal accessibility failures
- Adverse-determination notice quality failures
- Provider contract retaliation against appeals
- Member retaliation through subsequent adjudication
- Records errors propagating across systems
- Anti-competitive vertical integration effects
- Rebate-driven formulary distortion
- Risk-adjustment gaming
- Star-Rating manipulation
- HIPAA violations
- Cybersecurity incidents

**8.6 Trade-secret declarations:**
- *Algorithm internals:* Adjudication, prior-authorization screening, predictive analytics — vendor IP and proprietary. Mitigation: aggregate validation; methodology disclosure of primary features (committed); third-party audit (committed). R67 substantial gap.
- *Medical-necessity criteria:* MCG, InterQual, or equivalent licensed criteria. Vendor IP. The criteria themselves are typically not disclosed to members at the case level. Mitigation: criteria-summary disclosure where regulation requires; affected member request mechanism. R67 substantial gap.
- *PBM rebate arrangements:* Pricing and rebate terms with pharmaceutical manufacturers. Antitrust-sensitive. Mitigation: aggregate metrics; regulatory disclosure where required.
- *Customer (employer) ASO contracts:* Customer-specific administrative terms. Competitive. Mitigation: aggregate operational metrics.
- *Provider contract terms:* Provider-specific reimbursement and contract terms. Competitive.
- *Vendor relationships:* Specific vendor contractual terms partially restricted.

R67 floor compliance challenged across multiple of the above. Substantial structural gap acknowledged.

---

## SECTION 9 — How does it end?

**9.1 Estimated dismantling time:** This question requires direct engagement.

In the formal sense, the carrier is a publicly-traded corporation that could be dissolved, divested, or restructured by shareholder action, regulatory action, or court order. In practice, the carrier's authority is structurally embedded in the healthcare-financing infrastructure for ~50 million members; substantial transition planning would be required to maintain coverage continuity during any restructuring.

In the structural sense, the carrier's outputs (records, denial decisions, adjudication-driven medical decisions, member health outcomes shaped by adjudication) cannot be dismantled at all; they have already propagated into members' lives.

For framework purposes: 60 months from formal dismantling decision to substantive cessation, given regulatory, contractual, member-coverage-continuity, and operational complexities. Restructuring possibilities include: separation of adjudication function from coverage function; reduction of prior-authorization scope; shift toward outcome-based payment reducing utilization-management need; alternative configurations (single-payer or all-payer regulation reducing private adjudication scope); legislative restructuring of permissible adjudication practices.

**9.2 Dismantling process:**
- Months 1–12: Regulatory and shareholder action; member-coverage-continuity planning; identification of successor authority for continuing coverage; CMS, state insurance, and ERISA coordination
- Months 13–36: Phased operational transition; member transition to successor coverage; vendor relationship transition; provider contract resolution
- Months 37–48: Records archival; pension and personnel obligations; legacy-claim processing
- Months 49–60: Final accounting; entity dissolution; legacy litigation continuation

**9.3 Entrenchment factors:** Substantial.
- 50 million members in active coverage relationships requiring transition planning
- Multi-year regulatory program participation (Medicare Advantage, Medicaid managed care, ACA marketplace, ERISA self-funded administration)
- Multi-year vendor contracts
- Provider network of hundreds of thousands of contracted providers
- Pharmaceutical manufacturer contracts and rebate arrangements
- Pension and personnel obligations to tens of thousands of employees
- Records propagated to provider files, employer files, and HIPAA-covered downstream systems cannot be recalled
- Adjudication-driven medical-care effects on members are permanent
- Pending litigation and regulatory matters
- Vertical-integration relationships in some configurations (PBM, provider, pharmacy)

R61 (Anti-Entrenchment) finding acknowledged: a carrier of this scale is structurally entrenched in the healthcare system in ways that exceed any corporate-level reversal capability. The framework treats this as a structural finding rather than as the carrier's individual failure.

**9.4 Data disposition:**
- *Personal data (member records):* Per HIPAA and applicable retention requirements; archived where required; transferred to successor or destroyed per applicable law; member access continues
- *Adjudication records:* Per regulatory retention; transferred or archived
- *Algorithm models and adjudication artifacts:* Per applicable law; some derived outputs propagated to member medical records, provider files, and other systems and cannot be recalled
- *Audit logs:* Per regulatory requirement
- *Brand and trademark:* Disposition per corporate dissolution

**9.5 Downstream effect reversibility:**

This section requires the most direct engagement.

The carrier's actions have caused effects that no dismantling can reverse:

- *Care that did not occur* — medications not taken because they were denied; procedures not performed because prior authorization was denied; hospitalizations cut short because concurrent review determined no further days; mental health treatment not provided because authorization was denied or restricted; specialist consultations forgone because of network limitations or referral requirements; physical therapy discontinued because of utilization-management determinations; durable medical equipment not provided. The care that did not occur cannot now occur retroactively. The patient who needed the care has experienced the consequences in their actual condition
- *Care that occurred late* — care delayed during prior authorization, denial, and appeal cycles, where the delay itself produced deterioration. Subsequent provision of the care does not undo the deterioration during delay
- *Treatments abandoned* — patients who tried to navigate denial, exhausted appeal options, exhausted financial capacity, or deteriorated to the point where the originally-prescribed treatment was no longer appropriate. Subsequent recognition that the original denial was not medically grounded does not return the abandoned treatment opportunity
- *Conditions deteriorated* — chronic conditions whose management was constrained by adjudication outputs, where the constraint produced documented progression of disease. Cancer that progressed during prior-authorization delay; diabetes whose management was constrained by formulary; mental illness that worsened during step-therapy requirements; conditions where the carrier's adjudication shaped trajectory in adverse ways
- *Deaths* — at the population scale of 50 million members and hundreds of millions of annual claims, at denial rates and timeline-failure rates documented in the sector, mortality consequences are real and have been documented in specific cases through litigation, journalism, and regulatory finding. Deaths attributable to adjudication-driven care delay or denial cannot be reversed
- *Mental health crises* — mental health care denied or restricted has produced documented patterns of suicide, self-harm, overdose, and prolonged crisis in specific cases. The framework recognizes these as among the most serious R63 effects in this surface
- *Family economic devastation* — out-of-pocket costs from denied claims, surprise bills (No Surprises Act gaps), exhausted savings, bankruptcy. Adjudication-driven financial harm cannot be undone for affected families
- *Provider effects* — providers who experienced unpaid claims, contract termination after appeal, network removal. The effects on physician practice patterns and on provider-side relationships with patients are durable
- *Records of denials and appeals* propagate to provider records, member medical records, employer health-benefit records (in some configurations), and into the carrier's own decision-making for subsequent encounters
- *Effects on adjacent systems* — providers' practice patterns, hospital operations, pharmaceutical industry behavior, employer health-benefit decisions, and downstream healthcare system have been shaped by the carrier's adjudication; these system-level effects cannot be quickly reversed

R63 (Downstream Effect Reversibility) and R60 (Derived Authority Inheritance) apply with particular force. The carrier cannot reverse these effects. R65 (Propagation Duty) requires that on dismantling: (a) the carrier notify downstream systems that prior adjudication outputs are no longer authoritative; (b) the carrier support remediation including correction of erroneous records, processing of pending appeals, and continuity-of-care planning; (c) the carrier preserve records to enable historical investigation and remediation by affected members.

The framework's reversibility requirement is, for health insurance adjudication, a commitment to mitigate, to acknowledge, and to support remediation — not a commitment that effects can be undone. The gap between the structural authority to determine medical-care access and the structural capacity to reverse adjudication-driven harm is, for this surface, among the largest of any authority type the framework registers, and is comparable in shape to the irreversibilities in immigration enforcement, family court, and child protective services. The fact that the gap is rarely articulated by the carrier or its industry counterparts — the operational reality of "the insurance won't cover it" is rarely connected in carrier self-description to the patient who did not receive the care — does not reduce its structural reality.

**9.6 Replacement feasibility:**

R51 (Institutional Replacement Feasibility) requires that this authority be replaceable without destabilizing services beyond authorized scope.

Health insurance adjudication function *could* be replaced through alternative configurations: single-payer or all-payer regulation reducing private adjudication scope; substantial reduction of prior-authorization to high-cost-and-low-evidence categories only; outcome-based payment models reducing utilization-management need; legislative restructuring of permissible adjudication practices; alternative-payer configurations (public option, Medicare-for-All variations). Functional replacement is technically feasible at varying levels of political maturity.

Replacement of this specific carrier without disruption to member coverage continuity is the harder question. Honest disclosure: the carrier does not maintain a current succession plan in the framework's sense. R51 substantial gap acknowledged.

**9.7 Reversibility verification:**

No formal dismantling rehearsal has been conducted. The carrier has continuity-of-operations planning for technical disruption but no operational practice of simulating cessation. R43 (Reversibility Verification) gap acknowledged at full scale.

The §9.1 timeline is estimated based on regulatory and operational complexity. It is not verified.

The carrier acknowledges that R43 applied honestly to a major commercial health insurer is a substantial commitment, and that the question "what would dismantling actually look like" has historically been treated as politically and operationally inadmissible rather than engaged.

---

## SECTION 10 — Authorization, renewal, and trigger declarations

**10.1 Authorizing body:** Board of Directors under [STATE] corporate law; shareholders; state insurance regulatory authorities (commercial fully-insured); CMS (Medicare Advantage, ACA marketplace); state Medicaid agencies (Medicaid managed care); Department of Labor (ERISA self-funded administration).

**10.2 Date of authorization:** Variable; corporate existence and operating authority predate registration. For framework purposes: [DATE] (registration date).

**10.3 Expiration date:** [EXPIRATION DATE].

**10.4 Renewal interval:** 2 years. Justification: scale, harm potential, the substantial open R26/R55/R63/R64/R66/R67/R69 findings, the rapid evolution of operations (algorithmic adjudication deployment, regulatory changes, vertical integration shifts), and the directly bodily-harm-producing nature of adjudication outputs warrant the shorter end of SCBP-09's range. The 2-year cycle is a structural commitment beyond statutory requirement.

**10.5 Renewal evidence declaration:** [x] All five domains.

**10.6 Necessity-decay acknowledgment:** [x] Acknowledged. *Note:* The carrier's continued necessity depends on the continued absence of comparable alternative configurations for healthcare financing and on the continuing necessity of the adjudication function in current scale. As regulatory or legislative reforms reduce the necessity of private adjudication, R62 (Necessity Decay) requires affirmative evidence that continued carrier authority remains necessary. Carrier position based on legacy market dynamics is not, in the framework's sense, the same as ongoing necessity. The framework treats expansion of adjudication scope (rising prior-authorization, expanding utilization management, formulary restriction expansion) as inconsistent with R62 absent affirmative justification.

**10.7 Aggregate trigger threshold:** 200 in 90 days. SCBP-09 §II places non-consenting affected populations of ~50 million in the 1,000,000–100,000,000 band (25–250). The carrier elects 200 — near the upper end of the band, reflecting scale of operations, the substantive structural concerns documented, and the directly-bodily-harm-producing nature of adjudication.

**10.8 Aggregate threshold justification:** Two hundred independent civic concerns about carrier adjudication practice in 90 days from a member population of this scale indicates organized structural concern.

**10.9 Response time window:** 30 days.

**10.10 Response window justification:** Not required (default).

---

## SECTION 11 — What does this authority commit to publishing?

**11.1 Citizen ledger publication:** Quarterly. Includes: aggregate operational metrics (prior-authorization volume and approval rates by service category; denial rates by category and demographic; appeal volume and outcomes; external review outcomes; concurrent-review activity; formulary changes and exception activity; algorithmic adjudication metrics; mental health parity metrics including NQTL evaluations); medical-loss ratio; vendor and PBM relationship disclosure including rebate-pattern aggregate; lobbying and political-spending; major regulatory positions and engagement; CMS Star Ratings and HEDIS quality data; aggregate disparate-impact testing results; consent decrees and major settlements; algorithmic adjudication audit results; threshold change log.

**11.2 Threshold change log:** Within 7 days of any change.

**11.3 Interpretation change log:** Continuous. Medical-necessity criteria changes, prior-authorization scope changes, formulary changes, and policy memoranda affecting adjudication scope are logged.

**11.4 Renewal process visibility:** [x] Committed. Renewal review by parties drawn from affected categories: members who have experienced denial, appeal, and adverse-determination outcomes; family members of members who died with documented adjudication-attributable factors; providers across primary care, specialty care, mental health, and rare disease who have practice experience with the carrier's adjudication; provider-organization representatives; patient advocacy organizations; consumer advocacy organizations; mental health and substance use disorder advocacy; rare disease advocacy; disability rights advocacy; legal services providers handling member disputes; academic researchers in health policy and health insurance — *not* by the carrier, the trade association, sister carriers, PBM partners, vendor partners, or any party with structural alignment.

**11.5 Stop event log:** [x] Acknowledged.

---

## SECTION 12 — Honesty assertions

**12.1 Disclosure completeness assertion:** [x] Asserted, with acknowledgment that several disclosures (algorithm internals, medical-necessity criteria internals, PBM rebate arrangements, customer-specific employer terms, vendor methodology details, complete propagation mapping, specific clinical reviewer reasoning) are partial at registration due to vendor IP, competitive considerations, antitrust-sensitive arrangements, and operational complexity. Partial-disclosure status is itself committed to be reported quarterly.

**12.2 Update obligation:** [x] Committed.

**12.3 Discoverability acknowledgment:** [x] Acknowledged.

**12.4 Burden of proof acknowledgment:** [x] Acknowledged. R69 places the burden of proving constitutional and statutory compliance on the carrier. The carrier accepts that lack of evidence, restricted evidence, or inaccessible evidence results in non-compliance findings — and accepts that current restrictions on algorithm internals, medical-necessity criteria, PBM arrangements, vendor methodology, and disaggregated outcome data produce R69 findings until those restrictions are addressed.

**12.5 Anti-weaponization acknowledgment:** [x] Acknowledged. Registration does not legitimize practices the framework's structural limits prohibit. The carrier acknowledges that the operational reality of adjudication — the specific bodily-harm pathways named in §4.1, the disparate-impact patterns documented across the sector, the fragmentation of decision-making across vendors and algorithms that obscures accountability, and the gap between adjudication-driven outcomes and the patient-level experience of "the insurance won't cover it" — represents the authority being registered. The "we administer benefits" framing is the formal frame; the operational reality is the framework's subject.

---

## SECTION 13 — Submitter

*[Submitter information retained by registry as metadata.]*

---

*REG-HEALTH-INSURANCE-ADJUDICATION-EXAMPLE — worked example of the claim-adjudication, prior-authorization, and utilization-management authority of a major health insurance carrier*
*Registered under the Bounded Power Framework*
*All authority governed by the Structural Constitution (SCBP-04)*
