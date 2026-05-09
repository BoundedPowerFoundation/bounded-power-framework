---
mechanism_id: SCBP-REG-EXAMPLE-HOSPITAL-SYSTEM
mechanism_name: "HOSPITAL-SYSTEM-EXAMPLE"
status: EXAMPLE
domain: healthcare
authority_classification: direct
registered_date: [DATE]
authorization_date: [AUTHORIZATION DATE]
expiration_date: [EXPIRATION DATE]
renewal_interval_years: 3
funding_types:
  - private_nonprofit
  - federal_government_mandatory
  - state_government_mandatory
  - self_funded_fee_for_service
funding_concentration_max_pct: 38
affected_party_categories:
  - residents_of_geographic_area
  - patients
  - employees
  - vulnerable_populations
  - children
  - non_consenting_third_parties
affected_population_estimate: 285000
non_consenting_population_estimate: 18000
entity_size: large
geographic_specificity: multi_county
geographic_reach: "[COUNTY 1] and [COUNTY 2], [STATE]"
aggregate_threshold_count: 12
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
dependency_count_type1: 18
dependency_count_type2: 7
dependency_count_type3: 8
capture_risk_identified: true
disclosure_completeness_assertion: true
update_obligation_committed: true
discoverability_acknowledged: true
burden_of_proof_acknowledged: true
anti_weaponization_acknowledged: true
---

# Mechanism Record — REG-HOSPITAL-SYSTEM-EXAMPLE

**HOSPITAL-SYSTEM-EXAMPLE**

| Field | Value |
|---|---|
| Mechanism ID | REG-HOSPITAL-SYSTEM-EXAMPLE |
| Status | EXAMPLE |
| Registered | [DATE] |
| Authorization expires | [EXPIRATION DATE] |
| Domain | Healthcare |

---

## SECTION 1 — What is this authority?

**1.1 Mechanism name:** HOSPITAL-SYSTEM-EXAMPLE — a regional nonprofit integrated health system.

**1.2 Functional description:** A nonprofit integrated health system operating 4 hospitals (1 academic medical center, 2 community hospitals, 1 specialty psychiatric hospital), 28 outpatient clinics, a home health agency, a hospice program, and an employed physician group of ~640 physicians. Services provided:
- Inpatient acute care (~62,000 admissions annually)
- Emergency department services (~285,000 ED visits annually across 4 EDs)
- Outpatient and primary care (~1.4M outpatient visits annually)
- Surgical services (~38,000 surgeries annually)
- Behavioral health and psychiatric services (~12,000 admissions annually)
- Home health and hospice (~8,500 patients annually)
- Diagnostic services (laboratory, imaging, pathology)

Functional authority outputs:
- Admission and discharge decisions
- Treatment decisions (clinical judgment within standards of care)
- Medication administration and prescribing
- Restraint and seclusion (in inpatient psychiatric settings; bounded by federal CMS rules)
- Involuntary psychiatric commitment (per [STATE] Mental Health Code)
- Diagnostic determinations affecting insurance, employment, custody decisions
- Medical record creation, retention, and disclosure (per HIPAA)
- Employment decisions for ~14,000 staff
- Procurement and contracting

**1.3 Authority classification:** Direct. Binding clinical, employment, and operational decisions are made affecting hundreds of thousands of patients and tens of thousands of employees.

**1.4 Domain:** Healthcare (primary). Also: large employer (Government-adjacent for some functions), Data/Information (medical records), Education (residency training programs).

**1.5 Statutory or constitutional basis:** Operates as a 501(c)(3) nonprofit under [STATE] state law. Hospital licensure: [STATE DEPARTMENT OF PUBLIC HEALTH]. Federal Medicare/Medicaid Conditions of Participation (CMS). Joint Commission accreditation. State medical practice acts (governing physician licensure, separate from this authority). HIPAA (federal privacy). EMTALA (emergency treatment requirements). [STATE] Mental Health Code (involuntary commitment authority). Various federal civil rights statutes. Operations occur under at least 14 distinct statutory frameworks, plus accreditation requirements, plus payer contracts. Many decisions occur at the intersection of multiple frameworks.

---

## SECTION 2 — Who can this authority act upon?

**2.1 Affected party categories:**
- [x] Residents of geographic area (~2.1M residents across service area; ~285,000 use services annually)
- [x] Patients (the primary affected population)
- [x] Employees (~14,000 staff)
- [x] Vulnerable populations: critically ill patients; pediatric patients (~38,000 children/year); psychiatric patients; elderly patients; patients with limited English proficiency; uninsured/underinsured patients; patients in coercive conditions (e.g., emergency presentations)
- [x] Children (~38,000 pediatric patients/year, including approximately 6,500 NICU/pediatric ICU patients)
- [x] Non-consenting third parties: patients in emergency conditions who lack capacity to consent; involuntary psychiatric committees; mandated reporting subjects (e.g., child abuse, elder abuse); insurance authorization processes

**2.2 Approximate number of people directly affected:** ~285,000 patients annually + ~14,000 employees + family members and visitors = approximately 600,000 total interactions/year.

**2.3 Non-consenting population:** Structurally complex for a healthcare system.

Most patients consent to treatment voluntarily. However:
- Emergency patients lacking capacity (~12,000/year — patients arriving unconscious, with altered mental status, etc.) cannot meaningfully consent at presentation
- Involuntarily committed psychiatric patients (~1,800/year) are explicitly non-consenting
- Pediatric patients (~38,000/year, though parents consent on their behalf — the child themselves is non-consenting in the framework's sense)
- Patients subject to mandated reporting (~4,200/year — child abuse, elder abuse, certain communicable diseases)

Total non-consenting population: approximately 18,000 individuals annually whose interaction with the authority is non-voluntary in some meaningful sense.

This is less than the total affected population (285,000) but represents the population with structurally limited exit options where R26 (Non-Participant Harm Floor) applies most strongly.

**2.4 Vulnerable population specifics:**
- [x] Children — *yes*. ~38,000 pediatric patients with parental consent; the child themselves cannot consent. Special protections: pediatric-specific clinical protocols; child life specialists for hospital experience; mandated abuse reporting; foster care coordination; pediatric IRB requirements for research.
- [x] Patients during medical care — *the primary affected population by definition*. All patients are vulnerable in some sense due to information asymmetry, illness-related impairment, and the structural power differential of healthcare encounters.
- [x] Detained or confined persons — *yes*. Inpatient psychiatric admissions (voluntary and involuntary) are confined while admitted. Court-ordered evaluations occur. Involuntary holds are time-bounded by [STATE] Mental Health Code (initially 24 hours, extendable through judicial process).
- [x] Persons in coercive economic relationships — *yes*. Patients facing significant medical bills are in coercive economic relationships with the authority regarding payment, billing disputes, and collection. Employees depend on the authority for healthcare benefits as well as employment.
- [x] Persons unable to advocate for themselves — *yes*. Many patients (cognitive impairment, intoxication, severe illness, limited English, no family present) cannot effectively advocate during medical encounters. Mitigation: surrogate decision-maker laws; ethics consultation; patient advocate program; interpretation services in 24 languages.

---

## SECTION 3 — What can it do, and what can it not do?

**3.1 Geographic reach:**
- [x] Multi-county: [COUNTY 1] and [COUNTY 2], [STATE].

The authority does not operate outside this region. Its emergency departments accept patients regardless of origin (per EMTALA), but it does not maintain non-emergency services outside the geographic area.

**3.2 Coercive ceiling:**
- Admission and discharge decisions
- Treatment decisions within standards of care
- Use of physical restraint per CMS regulations (limited duration, requires physician order, requires monitoring)
- Use of chemical restraint per CMS regulations
- Involuntary psychiatric commitment per [STATE] Mental Health Code (initial hold up to 24 hours; extension requires judicial process)
- Mandated reporting (legally required to report suspected abuse)
- Refusal of non-emergency services for non-payment (subject to charity care policies)
- Billing and collections actions
- Employment actions

May NOT:
- Force treatment on a competent patient (informed consent required except in emergencies)
- Hold a competent patient against their will (except per Mental Health Code)
- Disclose protected health information except per HIPAA
- Discriminate on protected characteristics
- Refuse emergency stabilization for inability to pay (EMTALA)
- Discharge a patient without appropriate continuing care arrangements
- Conduct research without informed consent and IRB approval
- Use restraint or seclusion as punishment or for staff convenience

**3.3 Resource ceiling:**
- Operating budget: ~$2.1B annually
- Staff: ~14,000 FTE
- Beds: 1,840 licensed acute beds + 280 psychiatric beds = 2,120
- Data systems: Electronic Health Record ([ELECTRONIC HEALTH RECORD VENDOR]); financial systems; research databases (with IRB approval); analytics systems

**3.4 Explicit exclusions:**
- **Geographic:** Does not operate non-emergency services outside [COUNTY 1] / [COUNTY 2].
- **Action:** May not conduct experimental treatment without IRB-approved research protocol; may not refuse emergency stabilization (EMTALA); may not retaliate against staff or patients for raising safety concerns; may not disclose PHI without HIPAA-permitted basis; may not enter into financial arrangements with referring physicians that violate Stark Law or Anti-Kickback Statute.
- **Data:** May not share patient data with marketing firms; may not retain identifiable patient data beyond regulatory retention requirements (typically 7–10 years post-discharge); may not use patient data for research without consent and IRB approval; may not share data with ICE absent judicial process; may not share substance use treatment records absent specific authorization (42 CFR Part 2).
- **Procedural:** May not pay physicians based on volume of referrals or specific orders (Stark/AKS); may not allow gifts from pharmaceutical or device manufacturers above per-event limits; may not require waivers of patient rights; may not restrict patient access to their own records (HIPAA right of access).
- **Other:** May not propose, lobby for, or enforce policies that discriminate; may not engage in deceptive billing practices; may not balance bill in violation of No Surprises Act.

---

## SECTION 4 — What harms can it cause?

This section is structurally distinctive for healthcare. Unlike most authorities, the authority routinely engages in actions with predictable adverse effects (medication side effects, surgical complications, treatment-related infections). The R21 framework requires distinguishing *normal and expected* adverse effects from *negligent or excess* harm.

**4.1 Bodily harm threshold — multi-tiered:**

*Hospital-acquired conditions (HACs):*
- If hospital-acquired infection rates exceed CMS-published peer benchmarks by >25% for any infection category over any 12-month period, this triggers review.
- If serious patient safety events ("Never Events" per CMS list) occur at any rate above 1 per 100,000 patient-days, this triggers review.

*Mortality and morbidity:*
- If risk-adjusted mortality rates exceed peer benchmarks by >15% for any service line over any 12-month period, this triggers review.
- If readmission rates exceed CMS targets by >20% for any condition, this triggers review.

*Restraint and seclusion:*
- Each restraint incident is documented; aggregate use beyond CMS-defined thresholds (e.g., excessive duration, inappropriate clinical justification) triggers review.
- Any restraint-related injury triggers immediate review.

*Medication errors:*
- Serious medication errors (errors causing patient harm, errors requiring intervention) tracked monthly; rates above peer benchmark by >25% trigger review.

*Maternal mortality and severe maternal morbidity:*
- Given documented racial disparities in US maternal outcomes, the authority sets a specific threshold: if Black maternal mortality or severe morbidity rates exceed white rates by >2x in any 12-month period (current US baseline is 3.2x, indicating systemic problem), this triggers immediate review.

*Pediatric-specific:*
- Pediatric serious safety events tracked separately; any preventable pediatric mortality triggers review.

The framework's bodily-harm threshold is operationalized as a series of measurable metrics with peer-benchmark and absolute components. *Normal and expected* harm (e.g., chemotherapy side effects, surgical recovery pain) is not in this category — it is the cost of care that is consented to. *Excess* harm (rates exceeding peer benchmarks; preventable harm) is what these thresholds capture.

**4.2 Agency impairment threshold:**
- If patient grievance/complaint resolution rates fall below 95% within state-mandated timelines, this triggers review.
- If interpretation services are unavailable when needed for any encounter, that encounter is itself a finding.
- If patients are denied access to their own medical records beyond HIPAA-allowed limits, those denials are findings.
- If informed consent is documented as inadequate (post-hoc determination by ethics committee or Joint Commission) for any procedure, this triggers review.

**4.3 Ecological damage threshold:** Hospital operations have substantial environmental footprint (energy, waste, pharmaceuticals in wastewater). Threshold:
- Joint Commission environmental standards compliance must be maintained
- Pharmaceutical waste disposal compliance with EPA standards
- Energy intensity tracked; beyond peer benchmarks triggers review

**4.4 Generational binding threshold:** Healthcare decisions affect generations through:
- Genetic information disclosure affecting family members
- Reproductive decisions
- Information about hereditary conditions
- Long-term medical record retention

Threshold: if outcomes (population health metrics, equity in access) for specific demographic groups produce intergenerational disparities not attributable to upstream factors, this triggers review.

**4.5 Communicative suppression threshold:**
- If the authority retaliates against patients, families, or staff who file safety complaints, raise quality concerns, or speak publicly about practices, this triggers review.
- If patient or staff speech is suppressed beyond legitimate confidentiality requirements, this triggers review.
- If the authority fails to disclose safety information to patients (e.g., known equipment failures, infection outbreaks) in violation of disclosure duties, this triggers review.

**4.6 Informational sovereignty threshold:**
- HIPAA violations (impermissible disclosure of PHI) — each substantiated case is a finding.
- Records retained beyond regulatory limits — finding.
- Records shared with parties outside HIPAA-permitted disclosures (including ICE, marketing, etc.) — finding.
- Genetic information used for non-clinical purposes — finding.
- Substance use disorder records disclosed in violation of 42 CFR Part 2 — finding.

**4.7 Additional harm thresholds:**

*Disparities threshold:* If quality outcomes (mortality, complications, readmissions, access) correlate with race, ethnicity, primary language, or insurance status at p<0.05 across any 12-month period, this triggers review. The healthcare disparities documented in US data are substantial; commitment to monitoring and remediation.

*Financial harm threshold:* If patient billing practices result in collections actions exceeding [defined threshold] or correlate with patient demographic characteristics, this triggers review. Commitment to robust charity care policies.

*Diagnostic error threshold:* If documented diagnostic errors (per peer review) exceed peer benchmarks, this triggers review.

*Behavioral health treatment access threshold:* Given psychiatric capacity limits, if behavioral health patients face access delays exceeding 14 days for non-emergency conditions, this triggers review.

*Maternal-infant separation threshold:* If practices separate mothers from newborns (e.g., NICU policies, child welfare reports leading to separation) without clear medical or safety justification, this triggers review.

**4.8 Threshold change-log commitment:** [x] Yes — committed.

---

## SECTION 5 — What stops it?

**STOP PATH 1 — CMS / Medicare termination**
- Activator: CMS, on supervisory finding of Conditions of Participation violation.
- Trigger: CMS determination of violation.
- What "stopped" means: CMS may terminate Medicare/Medicaid agreements, which would effectively close most operations (these payers represent ~62% of revenue).
- Independence justification: CMS is federal regulator structurally independent of the authority.
- Timeline: CMS regulatory procedures; emergency termination possible for serious immediate jeopardy.

**STOP PATH 2 — [STATE DEPARTMENT OF PUBLIC HEALTH] licensure action**
- Activator: [STATE DEPARTMENT OF PUBLIC HEALTH], on licensure violation finding.
- Trigger: State licensure violation.
- What "stopped" means: The state agency may suspend or revoke hospital licensure, prohibiting operation.
- Independence justification: State agency.
- Timeline: State administrative procedures.

**STOP PATH 3 — Joint Commission accreditation withdrawal**
- Activator: Joint Commission, on accreditation review.
- Trigger: Accreditation standards violation.
- What "stopped" means: Loss of accreditation affects payer contracts and patient referrals; functionally limits operations significantly.
- Independence justification: Joint Commission is independent accreditation body.
- Timeline: Joint Commission review cycle.

**Additional pathways noted but not formal stop paths:**
- Federal court orders (HIPAA, civil rights, malpractice class actions)
- Patient/family malpractice litigation
- Whistleblower actions under federal False Claims Act
- Board of Directors action (governance — internal)

**5.4 Penalty for activating stop:** [x] Confirmed — no penalty applies. Whistleblower protections under federal False Claims Act, HIPAA, [STATE] law, and accreditation standards.

**5.5 Stop-path independence verification:** [x] Yes for all three paths.

**5.6 Civic trigger acknowledgment:** [x] Acknowledged.

---

## SECTION 6 — What does it depend on?

**6.1 Type 1 dependencies:**
- Medical staff (physicians) — substantial number are employed; some are independent contractors with privileges. Compensation: salary or contract, not directly tied to volume in ways that violate Stark/AKS.
- Nursing staff (employed)
- Allied health staff (employed and contracted)
- Anesthesia services contract group
- Hospitalist services contract group
- ED physician staffing contract group
- Specialty contract groups (radiology, pathology, etc. — 5 separate contracts)
- Laboratory services (mix of in-house and reference labs)
- Pharmacy services (in-house plus 2 specialty pharmacy contractors)
- Dialysis contractor
- Transportation services (ambulance, transfer vehicles)
- Housekeeping/dietary contractors
- Security services contractor
- IT services (internal plus 2 vendor relationships)
- Research administration partners
- Continuing medical education partners
- Foundation/development office contracted services
- Architectural/construction project contractors

**6.2 Type 2 dependencies:**
- CMS / Medicare/Medicaid
- [STATE DEPARTMENT OF PUBLIC HEALTH]
- Joint Commission
- Federal HHS / Office for Civil Rights (HIPAA)
- Local health departments
- Regional EMS coordination
- Affiliated medical schools (academic medical center has teaching responsibilities)

**6.3 Type 3 dependencies (compromising stop paths):**
- *[ELECTRONIC HEALTH RECORD VENDOR]:* the authority cannot operate without EHR; failure prevents care delivery and stop path documentation.
- *Pharmaceutical supply chain:* drug shortages affect care; supply chain failures could halt operations.
- *Medical device supply (PPE, implants, equipment):* supply failures affect specific services.
- *Energy and utilities (must be uninterrupted for patient safety):* failures create immediate patient safety crises.
- *Diagnostic radiology PACS systems:* imaging unavailability affects clinical decisions.
- *Laboratory information systems:* lab results essential to care.
- *Insurance authorization systems:* delays affect access.
- *Federal regulatory infrastructure (CMS, FDA, HHS):* failures would compromise stop path 1.

**6.4 Capture risk identification:** [x] Yes. Multiple risks:

- *Funding concentration:* Medicare 38%, Medicaid 24%, commercial insurance 31%, self-pay 7%. Large dependence on government payers; political risk associated with payment policy changes.
- *Pharmaceutical industry capture:* substantial physician interactions with pharmaceutical industry historically. Mitigation: conflict-of-interest policies; restricted gifts; transparency reporting (Open Payments).
- *Medical device industry capture:* surgeon training, device demonstrations, research relationships create dependency patterns. Mitigation: conflict policies; centralized device evaluation.
- *Health insurer capture:* the authority contracts with payers; payer concentration creates leverage. Mitigation: diversified payer mix.
- *Academic-industry research relationships:* research funding from industry creates dependencies. Mitigation: IRB review; conflict policies.
- *Physician self-interest:* fee-for-service incentives can drive utilization. Mitigation: salaried physicians; care management programs.
- *Construction and capital market exposure:* major construction projects create dependencies on financing markets.

**6.5 Reversibility-affecting dependencies:**
- Active inpatients: dismantling cannot strand patients.
- Pending surgeries and procedures: must be completed or transferred.
- Multi-year payer contracts.
- Long-term physician employment agreements.
- Sunk capital in facilities (~$1.8B).
- Specialized staff with non-transferable expertise.

**6.6 Coordination disclosures:**

The authority coordinates operationally with:
- Other regional health systems for capacity sharing during emergencies.
- Public health authorities for outbreak response and reporting.
- Children's Services for mandated reporting.
- Law enforcement for forensic patients (R55 finding — joint operations expand de facto authority).
- Insurance authorization and care management vendors (R72 finding — external systems whose decisions become operationalized).
- Affiliated medical schools (academic relationships).

**6.7 Disclosure completeness assertion:** [x] Asserted.

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

**7.1 Declared metrics:**

| Metric | Source | Role | Public? |
|---|---|---|---|
| Clinical metrics (mortality, complications, readmissions, etc.) | EHR + claims | Quality performance, accreditation | Aggregate yes (CMS publishes some) |
| Patient satisfaction (HCAHPS) | Patient surveys | Federal reporting, internal QI | Aggregate yes |
| Staffing ratios | HR systems | Patient safety, regulatory compliance | Aggregate yes |
| Infection rates | Infection control surveillance | Public reporting per state law | Aggregate yes |
| Medication errors | Safety reporting system | Internal QI; regulatory | Aggregate yes |
| Wait times | EHR | Operations, patient safety | Aggregate yes |
| Demographic outcomes | EHR + financial systems | Equity monitoring | Aggregate yes |
| Financial performance | Financial systems | Sustainability, board reporting | Aggregate yes (990 filings) |
| Research outcomes | Research systems | Academic reporting | Aggregate yes |

**7.2 Indirect signals:**
- Physician judgment in clinical decisions (subjective; mitigated through evidence-based guidelines)
- Triage decisions in ED (subjective; mitigated through standardized acuity scoring)
- Insurance authorization decisions (vendor algorithms; *external authority operationalized within the authority — R72 finding*)
- Diagnostic algorithms (decision support tools embedded in EHR)
- Risk scoring tools (sepsis risk, fall risk, etc.)
- Resource utilization patterns affecting patient access

**7.3 Algorithmic decision systems:** [x] Yes. Multiple systems:

- *Sepsis early warning system (EHR-embedded):* algorithm flags potential sepsis. Vendor: [ELECTRONIC HEALTH RECORD VENDOR] + clinical decision support layer. Auditability: methodology disclosed; outcomes monitored.
- *Insurance prior authorization vendors:* the authority operationalizes payer authorization decisions, which are themselves algorithmic in many cases. Significant R72 finding — payer algorithms become operationalized in care decisions. Mitigation: appeal processes; documented overrides; advocacy.
- *Predictive risk scores:* fall risk, readmission risk, deterioration risk. Mostly internal models, validated locally.
- *Diagnostic imaging AI:* radiology AI for certain imaging studies. Vendor: 2 firms. Auditability: regulatory approval pathways; validation data published.
- *Pharmacy alert systems:* drug interaction, dosing alerts. Standard clinical decision support.

**7.4 Outcome-versus-declaration check:** [x] Committed annually through Quality Committee review.

---

## SECTION 8 — How is this authority watched?

**8.1 Drift monitoring:** Quality Committee of Board (quarterly); CMS surveillance (continuous); Joint Commission triennial review; state inspections; medical staff peer review; ethics committee review of cases; multiple internal audit functions.

**8.2 Capture risk monitoring:** Annual conflict-of-interest disclosures (all medical staff and senior leaders); Open Payments compliance; pharmaceutical industry interaction tracking; payer relationship audit; Stark/AKS compliance review.

**8.3 Audit interfaces:**
- *Proactively published:* Annual quality reports; CMS-mandated public reporting (Hospital Compare); 990 nonprofit filings; safety incident summaries.
- *Available on request:* Specific case quality reviews (with privacy redactions); contractor financials (annual aggregate); research outcomes.
- *Restricted:* Individual patient records (HIPAA); peer review materials (state peer review privilege); some quality improvement data (federal Patient Safety Organization protections).

**8.4 Adversarial exposure (R81):** External parties can evaluate quality outcomes (Hospital Compare, state public reporting), financial flows (990, audited financials), board governance (public board meetings), accreditation status (Joint Commission). Cannot evaluate individual patient cases (necessarily) or some peer review (privileged).

**8.5 Known structural failure modes:**
- Diagnostic errors (estimated 5–10% of clinical encounters nationally)
- Hospital-acquired infections (despite improvements, ongoing risk)
- Medication errors (frequent at higher prevalence than recognized)
- Maternal mortality disparities (severe and racial)
- ED boarding (psychiatric patients, capacity issues)
- Burnout-related staff failures (patient safety risk)
- Cybersecurity breaches (industry-wide vulnerability; the authority has experienced breaches)
- Substance use among healthcare workers (rare but high-impact)
- Disparate care quality across populations
- Financial conflicts driving over-utilization in some specialties

---

## SECTION 9 — How does it end?

**9.1 Estimated dismantling time:** 36 months (3 years). Justification: a large integrated health system cannot dismantle quickly without abandoning patients. Wind-down requires patient transitions, staff dispositions, regulatory unwinding, asset disposition.

**9.2 Dismantling process:**
- *Months 1–6:* Decision and planning; community notification; regulatory notification (CMS, state DPH, Joint Commission).
- *Months 7–18:* Service reduction; transfer of specialized services to other regional providers; cease accepting new patients in services scheduled for elimination.
- *Months 19–30:* Patient transitions; staff dispositions; facility decommissioning; data archival per HIPAA.
- *Months 31–36:* Final regulatory closures; entity dissolution per state law; charitable asset disposition per [STATE] nonprofit law.

**9.3 Entrenchment factors:**
- Active inpatients (~1,200 average daily census).
- Active outpatient relationships (~285,000 patients/year).
- Specialized services (academic medical center status; regional referral patterns).
- Major capital investments (~$1.8B in facilities).
- 14,000 employees with employment relationships.
- Community dependence on healthcare access.
- Region's overall capacity (the authority represents ~28% of regional hospital beds; closure would create a regional access crisis).

**9.4 Data disposition:**
- Patient records retained per HIPAA (typically 7–10 years post-discharge).
- Patient access to own records preserved.
- Research data per IRB protocols.
- Personnel records per HR retention.
- Audit logs preserved publicly.

**9.5 Downstream effect reversibility:** R63 finding — clinical decisions, diagnostic findings, and treatment outcomes propagate to patient records, life insurance, disability determinations, custody decisions, employment screening, etc. Cannot be reversed.

**9.6 Replacement feasibility:** Dissolution would require successor providers. This would be a regional healthcare crisis. R51/R61 finding — the authority may be sufficiently entrenched in regional healthcare delivery that dismantlement creates cascading collapse. Mitigation: any dismantling must coordinate with regional providers; partial dismantling (specific services) more feasible than total dissolution.

**9.7 Reversibility verification:** No formal rehearsal. R43 gap acknowledged. Remediation: emergency operations plans cover service closures; broader dismantling has not been simulated.

---

## SECTION 10 — Authorization, renewal, and trigger declarations

**10.1 Authorizing body:** Board of Directors under [STATE] nonprofit law; CMS via Medicare provider agreement; [STATE DEPARTMENT OF PUBLIC HEALTH] via state license; Joint Commission via accreditation.

**10.2 Date of authorization:** [AUTHORIZATION DATE] (most recent renewal cycle).

**10.3 Expiration date:** [EXPIRATION DATE].

**10.4 Renewal interval:** 3 years.

**10.5 Renewal evidence declaration:** [x] All five domains.

**10.6 Necessity-decay acknowledgment:** [x] Acknowledged. Commits to demonstrating reduction in scope, dependency, opacity, persistence, or downstream impact over time, while acknowledging that healthcare service necessity for the regional population persists.

**10.7 Aggregate trigger threshold:** 12 triggers in 90 days. SCBP-09 §II places ~18,000 non-consenting in 1,000–100,000 range (5–25). The authority selects 12 — middle of range.

**10.8 Aggregate threshold justification:** Healthcare's non-consenting population includes structurally vulnerable individuals (emergency patients, involuntary committees, pediatric, mandated reporting). The authority calibrates to ensure their voice in civic systems while accommodating the legitimately high volume of routine clinical complaints that would not constitute structural concerns.

**10.9 Response time window:** 30 days (default).

**10.10 Response window justification:** Not required.

---

## SECTION 11 — What does this authority commit to publishing?

**11.1 Citizen ledger publication:** Annually (annual community benefit report) plus quarterly Board updates plus public quality reporting.

**11.2 Threshold change log:** Within 7 days.

**11.3 Interpretation change log:** Continuous.

**11.4 Renewal process visibility:** [x] Committed. Renewal review by parties drawn from affected categories: patient advocates, family caregivers, current and former employees (independent of administration), healthcare quality researchers, civil rights organizations, disability rights advocates, community health advocates, regional public health officials.

**11.5 Stop event log:** [x] Acknowledged.

---

## SECTION 12 — Honesty assertions

All five: [x] asserted/committed/acknowledged.

---

## SECTION 13 — Submitter

*[Submitter information retained by registry as metadata.]*

---

*REG-HOSPITAL-SYSTEM-EXAMPLE — worked example of a regional nonprofit integrated health system*
*Registered under the Bounded Power Framework*
*All authority governed by the Structural Constitution (SCBP-04)*
