---
mechanism_id: SCBP-REG-EXAMPLE-RISK-SCORING-VENDOR
mechanism_name: "RISK-SCORING-VENDOR-EXAMPLE"
status: EXAMPLE
domain: technology
authority_classification: indirect
registered_date: [DATE]
authorization_date: [AUTHORIZATION DATE]
expiration_date: [EXPIRATION DATE]
renewal_interval_years: 2
funding_types:
  - private_for_profit
funding_concentration_max_pct: 14
affected_party_categories:
  - non_consenting_third_parties
  - vulnerable_populations
  - criminal_justice_involved
affected_population_estimate: 480000
non_consenting_population_estimate: 480000
entity_size: medium
geographic_specificity: multi_state
geographic_reach: "United States — currently licensed to corrections departments in [N] states; product is used in pretrial detention, sentencing recommendations, parole decisions, and probation supervision intensity"
aggregate_threshold_count: 25
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
dependency_count_type1: 8
dependency_count_type2: 4
dependency_count_type3: 5
capture_risk_identified: true
disclosure_completeness_assertion: true
update_obligation_committed: true
discoverability_acknowledged: true
burden_of_proof_acknowledged: true
anti_weaponization_acknowledged: true
---

# Mechanism Record — REG-RISK-SCORING-VENDOR-EXAMPLE

**RISK-SCORING-VENDOR-EXAMPLE**

| Field | Value |
|---|---|
| Mechanism ID | REG-RISK-SCORING-VENDOR-EXAMPLE |
| Status | EXAMPLE |
| Registered | [DATE] |
| Authorization expires | [EXPIRATION DATE] |
| Domain | Technology |

---

## SECTION 1 — What is this authority?

**1.1 Mechanism name:** RISK-SCORING-VENDOR-EXAMPLE — a private vendor licensing a recidivism risk-assessment algorithm to state criminal justice authorities.

**1.2 Functional description:** This authority develops and licenses an algorithmic risk-assessment tool that produces numerical risk scores (1–10 scale) and risk categories (Low / Medium / High) for individuals in the criminal justice system. The score is intended to predict the likelihood of rearrest within 24 months. The model takes ~134 input variables (age, prior record, charge type, employment, housing stability, family ties, demographic, etc.) and produces the risk score through a proprietary machine learning model.

Outputs are *used by* corrections departments, courts, parole boards, and probation offices to inform: pretrial detention decisions, bail amounts, sentencing recommendations, parole eligibility decisions, supervision intensity assignments. **The authority does not make any of these decisions directly.** Its outputs are decision inputs operationalized by other authorities.

The licensed product is currently used in [N] US states across approximately 480,000 individual cases annually.

**1.3 Authority classification:** Indirect. The authority issues no binding directives. Authority operates through R58 — the score materially influences, conditions, and shapes decisions made by criminal justice authorities at scale. **Critically, the score's authority is *derived* under R60 — once a court or parole board operationalizes the score in a binding decision, the score inherits the constraints of the originating authority.**

The risk-scoring industry has been the subject of substantial academic critique and litigation alleging racial disparate impact (notably the published investigations of analogous risk-assessment tools in the mid-2010s). The authority acknowledges this history at registration.

**1.4 Domain:** Technology (primary). Criminal justice (functional context).

**1.5 Statutory or constitutional basis:** Operates as a [STATE] C-corporation. Product use is authorized in each customer state through procurement contracts and state administrative procedure approval. The risk-assessment product itself has no federal regulatory authorization specific to algorithmic risk assessment (this is a regulatory gap acknowledged here).

---

## SECTION 2 — Who can this authority act upon?

**2.1 Affected party categories:**
- [x] Non-consenting third parties (every individual scored — they did not consent to algorithmic risk assessment)
- [x] Vulnerable populations: pretrial detainees (presumed innocent, assessed before trial); persons returning from incarceration; persons of color (the product has documented disparate impact concerns)
- [x] Criminal justice involved individuals (essentially the entire affected population)

**2.2 Approximate number of people directly affected:** ~480,000 individuals scored annually across customer states. Cumulative population scored to date: ~3.2M individuals over 6 years of deployment.

**2.3 Non-consenting population:** Essentially the entire affected population. Individuals scored cannot opt out; the score is generated when their case enters the criminal justice system.

**2.4 Vulnerable population specifics:**
- [x] Children (juvenile justice cases) — yes, partial. A separate juvenile model is used in some jurisdictions. The authority acknowledges this is a particularly sensitive deployment given children's developmental status.
- [ ] Patients during medical care — not directly applicable, though some scored individuals are in mental health treatment.
- [x] Detained or confined persons — yes. Pretrial detainees are the core affected population.
- [x] Persons in coercive economic relationships — yes. Persons facing detention have minimal practical options to contest the score's use.
- [x] Persons unable to advocate for themselves — yes. Many scored individuals lack adequate legal representation, language skills, or knowledge of the assessment process.

---

## SECTION 3 — What can it do, and what can it not do?

**3.1 Geographic reach:**
- [x] Multi-state: [N] US states currently ([CUSTOMER STATES]).

**3.2 Coercive ceiling:** No direct coercive authority. Functional power operates through:
- Score generation (1–10 scale; Low/Medium/High classification)
- Distribution to operationalizing authorities
- Methodology updates (minor model updates released ~quarterly)
- Documentation and training materials provided to operationalizing authorities

The functional ceiling: a "High" risk score has, in documented cases, contributed to denial of pretrial release, longer sentences, denial of parole, and intensive supervision. The score is not legally binding but is operationally consequential.

**3.3 Resource ceiling:**
- Maximum operating budget: ~$78M annually
- Maximum staff: 220 FTE
- Maximum data systems: training data sets (~12M historical records), customer-specific deployment data

**3.4 Explicit exclusions:**
- **Geographic exclusions:** May not deploy in jurisdictions where statute prohibits algorithmic risk assessment in criminal proceedings.
- **Action exclusions:** May not provide the score in contexts other than criminal justice supervision (e.g., not for employment screening, not for housing decisions, not for insurance pricing); may not modify scores after generation; may not produce scores from inputs outside the documented variable set.
- **Data exclusions:** May not collect or retain biometric data; may not retain individual case data after 30 days post-generation unless customer authority requests retention for audit purposes.
- **Procedural exclusions:** May not enter into pricing arrangements that incentivize specific score outcomes (e.g., volume discounts based on detention rates); may not employ former officials of customer agencies in revolving-door capacities (12-month cooling off period).
- **Other exclusions:** May not advocate for expansion of algorithmic risk assessment beyond current deployment scope; may not contract with for-profit prison operators.

**3.5 Indirect influence boundaries:**

Outputs are operationalized by:
- *Pretrial detention decisions:* score is one of multiple factors considered by judges
- *Sentencing:* score is one of multiple factors in some sentencing guidelines
- *Parole decisions:* score is a primary factor in some state parole boards
- *Probation supervision:* score determines supervision intensity in some jurisdictions

The score is operationalized differently in different jurisdictions. The authority does not control how the score is used downstream, but training materials and documentation shape understanding of the score's meaning.

**3.6 Anti-proxy declaration:**

This is the most substantive section of this registration.

The model's training process and variable selection raise R66/R74 concerns. Anti-proxy commitments:

- *Proxy for race:* The model does not include race as a direct variable. The authority acknowledges that several included variables (ZIP code, prior arrest record, charge type, family ties) statistically correlate with race in ways that produce disparate outcomes. **This is a known structural concern.** Mitigation: annual fair-impact testing by independent firm; recalibration when disparate impact exceeds documented thresholds; published disparity analysis.
- *Proxy for poverty:* The model includes employment history and housing stability as variables; both correlate with poverty. The authority acknowledges that the score's structure tends to assign higher risk to economically marginal individuals. Mitigation: continued research into separating economic status from risk prediction.
- *Proxy for political behavior:* Does not use information about political activity, advocacy, or speech.
- *Proxy for protected characteristics generally:* Full variable list and explanations of why each is included are published.

**Acknowledged structural concern:** The score is itself a kind of proxy — it operationalizes "predicted recidivism" through specific measurable inputs, and the choice of inputs has substantial effects on disparate outcomes. R66/R74 logic suggests that disparate outcomes producing materially equivalent effects to direct discrimination constitute proxy discrimination regardless of intent. The authority accepts this framing and registers under it.

---

## SECTION 4 — What harms can it cause?

**4.1 Bodily harm threshold:** Substantive.

If the score contributes to detention or incarceration of individuals who, on subsequent review, were determined to have been wrongly classified, this triggers individual-case review. Aggregate threshold: if validated wrongful detention rate (subsequent acquittal, dismissal, or reversal) correlates with scores at p<0.05, this triggers systemic review.

**4.2 Agency impairment threshold:** If individuals are unable to view, contest, or appeal their score in any jurisdiction where the score affects their case, that jurisdiction's deployment is itself a finding.

**4.3 Ecological damage threshold:** Not applicable.

**4.4 Generational binding threshold:** Substantive. Scores affect individuals' criminal records, which affect their families across generations (children's housing stability, family wealth, educational opportunities, future employability of family members). Threshold: if documented downstream impact on family wealth or housing stability exceeds the impact attributable to underlying offense factors, this triggers review.

**4.5 Communicative suppression threshold:** If the score is used to retaliate against any individual's protected speech or political activity (e.g., higher score for jailhouse advocacy, prison reform participation), this triggers immediate review.

**4.6 Informational sovereignty threshold:**

Multi-part:
- If individual case data is retained beyond 30 days post-generation without customer authority request, this is a finding.
- If scores are shared with parties beyond the customer authority's authorized chain of custody, this is a finding.
- If individual scoring information is disclosed without judicial authorization, this is a finding.

**4.7 Additional harm thresholds:**

*Disparate impact threshold:* If the primary scoring algorithm produces statistically significant disparate outcomes (p<0.05) by race, ethnicity, or national origin in any 12-month period, the algorithm enters provisional review. **The authority acknowledges this threshold has been breached historically and is the subject of ongoing remediation.**

*Sub-population threshold:* If specific sub-populations (e.g., persons with serious mental illness, persons with developmental disabilities) face systematically worse outcomes from deployment, this triggers review.

*Validation threshold:* If predictive accuracy (validated against actual recidivism outcomes) drops below 65% (documented baseline ~71%), this triggers review.

**4.8 Threshold change-log commitment:** [x] Yes — committed.

---

## SECTION 5 — What stops it?

**STOP PATH 1 — Federal court order under 14th Amendment / Civil Rights Act**
- *Activator:* Federal court on motion of any party with standing
- *Trigger:* Determination that deployment violates equal protection or civil rights statutes
- *What "stopped" means:* Court orders may halt use in specific jurisdictions, require methodology changes, or in extreme cases halt all deployment
- *Independence:* Federal judiciary is structurally independent
- *Timeline:* Per federal court procedures

**STOP PATH 2 — State customer termination**
- *Activator:* Any state corrections, court system, or parole board can terminate its license; legislative action can prohibit algorithmic risk assessment
- *Trigger:* Customer authority discretion or state legislative action
- *What "stopped" means:* Specific state ceases use
- *Independence:* State customers are independent of the authority; legislative action is independent
- *Timeline:* Per state procedures and contract terms

**STOP PATH 3 — Class action or large-scale civil litigation**
- *Activator:* Class of individuals affected by scores
- *Trigger:* Court determination of systemic harm
- *What "stopped" means:* Court orders may require systemic methodology changes, cease specific practices, or impose damages
- *Independence:* Federal judiciary; class certification depends on standing
- *Timeline:* Class action procedures

**5.4 Penalty for activating stop:** [x] Confirmed — no penalty applies. Whistleblower protections under federal law.

**5.5 Stop-path independence verification:** [x] Yes for all three paths. *Acknowledged limitation:* federal court access requires legal resources; class actions require certification; state customer termination requires customer judgment. None of these are accessible to individual scored persons without organizational support.

**5.6 Civic trigger acknowledgment:** [x] Acknowledged.

---

## SECTION 6 — What does it depend on?

**6.1 Type 1 dependencies:**
- Cloud infrastructure (3 providers — multi-cloud)
- Data labeling contractor (1 firm)
- Machine learning infrastructure vendor (1 firm)
- Independent algorithmic audit firm (1 firm — annually)
- Five customer integration partners (state-specific)

**6.2 Type 2 dependencies:**
- [N] state customer authorities (criminal justice agencies)
- Federal regulatory environment (CFPB, FTC, DOJ Civil Rights Division)
- Independent academic research community (provides external scrutiny)
- Civil rights organizations (provide external accountability)

**6.3 Type 3 dependencies (compromising stop paths):**
- *Federal regulatory infrastructure:* if civil rights enforcement weakens, Stop Path 1 is compromised
- *Customer authority transparency requirements:* if customers reduce transparency about score use, oversight is compromised
- *Cloud infrastructure:* operational dependency
- *Independent audit firms:* if firms decline to audit (e.g., due to regulatory or reputational risk), the audit threshold cannot be met
- *Training data integrity:* if training data is corrupted or biased, model outputs cannot be trusted

**6.4 Capture risk identification:** [x] Yes.

- *Customer concentration:* No single state >14% of revenue. Capture threshold set above current concentration.
- *Customer-success incentive structure:* Contracts include performance metrics tied to detention/parole outcomes. **This is a R66/R74 capture risk** — the authority has financial incentives to produce scores that match customer agency preferences for outcomes. Mitigation: contracts specifically prohibit outcome-tied pricing; sales staff cannot influence model development; model updates require independent algorithm audit committee approval.
- *Industry coordination:* The authority competes with 3 other major vendors. Industry consortium exists; coordination is limited and disclosed in §6.6.
- *Regulatory capture:* The authority engages with state procurement processes; some former state corrections officials work at the company. 12-month cooling-off policy in place.

**6.5 Reversibility-affecting dependencies:**
- *Deployed scores already operationalized:* cannot reverse past detention/sentencing decisions made with the score. **R60/R63 finding:** propagated effects are irreversible at the individual case level.
- *Customer integration:* state customer systems integrate the score; deintegration takes time.
- *Personnel:* 220 specialized staff cannot be quickly redeployed.

**6.6 Coordination disclosures:**
- *Industry consortium:* Participation in the algorithmic-risk-assessment industry trade group. Coordination on industry positions; not on specific score outputs. R55 disclosed.
- *Customer states:* states share aggregate validation data; this could approach functional consolidation if all states begin operating the score in the same way. Not currently. Acknowledged for ongoing review.

**6.7 Disclosure completeness assertion:** [x] Asserted.

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

This is the substantive section for an algorithmic vendor.

**7.1 Declared metrics:** The model takes 134 input variables. Categories: demographics (age only — no race, gender, etc.), prior record (count and type of prior convictions, time since last conviction), current charge type, employment history, housing stability indicators, family ties (marital status, children, geographic ties), substance abuse history, mental health treatment history, education, certain neighborhood characteristics.

The full variable list is published in methodology documents. Each variable's coefficient in the model is partially disclosed (signed +/− direction; absolute weight is trade secret).

**7.2 Indirect signals:** None within score generation. The score is purely the model output; there is no human judgment layer in score generation.

However: how customer authorities *use* the score involves judgment that the authority does not control.

**7.3 Algorithmic decision systems:** [x] Yes — the scoring model itself is the algorithmic system. Vendor: in-house. Auditability: independent annual audit; methodology published; full code restricted as trade secret. **R67/R81 partial gap acknowledged at registration.**

**7.4 Outcome-versus-declaration check:** [x] Committed.

---

## SECTION 8 — How is this authority watched?

**8.1 Drift monitoring:** Quarterly model drift monitoring; annual independent algorithmic audit; quarterly disparate-impact testing.

**8.2 Capture risk monitoring:** Monthly customer concentration review; annual conflict-of-interest audit; ongoing tracking of personnel movements.

**8.3 Audit interfaces:**
- Proactively published: methodology documents, variable list, disparate-impact reports, validation studies
- Available on request: model methodology details (under NDA), specific case score breakdowns (to scored individual)
- Restricted: full source code (trade secret); customer-specific deployment details; training data

**8.4 Adversarial exposure (R81):** External parties can evaluate: methodology framework, variable list, validation results, disparate-impact reports. **Cannot fully evaluate:** complete source code; training data quality; specific weight values. R67/R81 partial gap.

Mitigation: independent annual audit by accredited firm; published audit results.

**8.5 Known structural failure modes:**
- Disparate impact (documented; ongoing remediation)
- Customer-incentive-pressure capture (mitigated through contract terms)
- Validation drift (model performance changes over time as criminal justice context changes)
- Generalization failure (model trained on past data may not predict future cases well)
- Black-box trust (customers may treat score as more reliable than it is)
- Adversarial gaming (sophisticated actors may attempt to manipulate inputs)

---

## SECTION 9 — How does it end?

**9.1 Estimated dismantling time:** 24 months. Justification: customer transitions, model deprecation, data deletion, multi-jurisdictional unwinding.

**9.2 Dismantling process:**
- *Months 1–6:* Customer notification; cease new contracts; transition planning
- *Months 7–18:* Wind down customer contracts; cease new score generation; coordinate with customers on alternatives
- *Months 19–24:* Final data deletion (training data, customer data); algorithm decommissioning; entity dissolution

**9.3 Entrenchment factors:**
- *Customer dependencies:* [N] states have integrated the score into systems; transition requires alternatives
- *Existing scored cases:* historical records cannot be unscored
- *Specialized staff:* expertise not easily redeployable

**9.4 Data disposition:** Training data deleted; customer data per customer agreement; methodology archived publicly; specific case data deleted per retention policy.

**9.5 Downstream effect reversibility:** **Substantial R60/R63 finding.** Scores have been operationalized in millions of decisions affecting detention, sentencing, parole. These decisions are not reversible.

Mitigation: on dissolution, public notice that scores are no longer current; transition support for customer authorities; archive methodology for historical analysis.

**9.6 Replacement feasibility:** Multiple competitor products exist; customer transitions are feasible. Does not create market vacuum.

**9.7 Reversibility verification:** No formal rehearsal. R43 gap. Remediation: simulation within 18 months.

---

## SECTION 10 — Authorization, renewal, and trigger declarations

**10.1 Authorizing body:** Board of Directors; state procurement authorities for each customer.

**10.2 Date of authorization:** [AUTHORIZATION DATE].

**10.3 Expiration date:** [EXPIRATION DATE].

**10.4 Renewal interval:** 2 years (short interval appropriate for active algorithmic system).

**10.5 Renewal evidence declaration:** [x] All five domains.

**10.6 Necessity-decay acknowledgment:** [x] Acknowledged.

**10.7 Aggregate trigger threshold:** 25 triggers in 90 days. SCBP-09 §II places ~480,000 non-consenting population in the 100,000–1,000,000 range (10–50). The authority elects 25 — middle of range — reflecting the structural vulnerability of the affected population while accommodating the volume of cases.

**10.8 Aggregate threshold justification:** As above.

**10.9 Response time window:** 30 days (default).

**10.10 Response window justification:** Not required.

---

## SECTION 11 — What does this authority commit to publishing?

**11.1 Citizen ledger publication:** Quarterly. Includes: customer state list, deployment metrics, validation studies, disparate-impact analyses, audit findings, methodology updates.

**11.2 Threshold change log:** Within 7 days.

**11.3 Interpretation change log:** Continuous.

**11.4 Renewal process visibility:** [x] Committed. Renewal review by parties drawn from affected categories: civil rights organizations, academic researchers in algorithmic fairness, persons formerly incarcerated, public defender organizations, criminal justice reform organizations. **NOT** by the authority, customer state corrections departments, industry trade association, or any party with material business relationship.

**11.5 Stop event log:** [x] Acknowledged.

---

## SECTION 12 — Honesty assertions

All five: [x] asserted/committed/acknowledged.

---

## SECTION 13 — Submitter

*[Submitter information retained by registry as metadata.]*

---

*REG-RISK-SCORING-VENDOR-EXAMPLE — worked example of a private algorithmic risk-assessment vendor licensing to state criminal justice authorities*
*Registered under the Bounded Power Framework*
*All authority governed by the Structural Constitution (SCBP-04)*
