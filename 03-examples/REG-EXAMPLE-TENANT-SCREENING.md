---
mechanism_id: SCBP-REG-EXAMPLE-TENANT-SCREENING
mechanism_name: "TENANT-SCREENING-EXAMPLE"
status: EXAMPLE
domain: economic
authority_classification: indirect
registered_date: [DATE]
authorization_date: [AUTHORIZATION DATE]
expiration_date: [EXPIRATION DATE]
renewal_interval_years: 2
funding_types:
  - private_for_profit
funding_concentration_max_pct: 22
affected_party_categories:
  - general_public
  - non_consenting_third_parties
  - vulnerable_populations
  - children
affected_population_estimate: 90000000
non_consenting_population_estimate: 90000000
entity_size: institutional
geographic_specificity: single_nation
geographic_reach: "United States — national operations; some operations in U.S. territories"
aggregate_threshold_count: 100
aggregate_threshold_window_days: 90
response_window_days: 30
harm_categories_declared:
  - agency_impairment
  - communicative_suppression
  - chronic_asymmetry
  - generational_binding
  - informational_sovereignty
algorithmic_decision_systems_used: true
dependency_count_type1: 22
dependency_count_type2: 6
dependency_count_type3: 8
capture_risk_identified: true
disclosure_completeness_assertion: true
update_obligation_committed: true
discoverability_acknowledged: true
burden_of_proof_acknowledged: true
anti_weaponization_acknowledged: true
---

# Mechanism Record — REG-TENANT-SCREENING-EXAMPLE

**TENANT-SCREENING-EXAMPLE**

| Field | Value |
|---|---|
| Mechanism ID | REG-TENANT-SCREENING-EXAMPLE |
| Status | EXAMPLE |
| Registered | [DATE] |
| Authorization expires | [EXPIRATION DATE] |
| Domain | Economic |

---

## SECTION 1 — What is this authority?

**1.1 Mechanism name:** TENANT-SCREENING-EXAMPLE — a national tenant-screening and rental-applicant evaluation company.

**1.2 Functional description:** A national tenant-screening company that receives rental applications from landlords and property management companies, retrieves data on the applicant from multiple sources, applies its own rules and scoring, and returns to the landlord a recommendation typically expressed as "Approve," "Conditional," "Decline," or in some product configurations a numeric score, a tier classification, or both. Functional outputs:

- *Tenant screening reports* compiled from data sources including: criminal history records (county-court repositories, state criminal records, FBI National Crime Information Center where authorized, commercial criminal-data aggregators); eviction filing records (court records, often via commercial aggregators that index civil court filings); credit reports (from one or more of the three major consumer credit reporting agencies); rental payment history (from contributed data and commercial aggregators); income verification (employer-supplied or commercial verification); identity verification (commercial vendors); sex offender registry checks; OFAC/sanctions list checks; in some cases social media or public-records search
- *Scoring and classification* — a proprietary score, a tier classification (e.g., "Approved," "Approved with deposit increase," "Conditional," "Decline-recommended"), or a recommendation along these lines
- *Compliance documentation* for the landlord — the report typically includes regulatory-compliance language and FCRA-required disclosures
- *Aggregate analytics products* sold to property management companies for portfolio-level risk assessment, marketing, and operations

The company processes approximately 30 million rental applicant evaluations annually (rough order of magnitude; the tenant-screening sector as a whole evaluates approximately 60–80 million applicant records per year nationally; major individual companies process on the order of 5–30 million each). Rental applicants are evaluated for approximately 90 million distinct individuals across the sector over multi-year periods.

The company does not directly compel any landlord decision. Its outputs materially shape landlord decisions about who can access housing. Functionally, in the substantial majority of rental transactions where the company's output is consulted, the landlord follows the recommendation. A "Decline" or low-score outcome typically means the applicant cannot rent that unit; for an applicant who is repeatedly screened across multiple property searches, a single accurate-or-erroneous adverse record may produce systematic exclusion from rental housing across many properties for the duration that the record persists.

The framework requires honest description of the operational reality, not the company's preferred self-description as a technology platform or compliance solution. Operationally:

- The company's outputs propagate widely. A single rental application typically generates a report sent to one landlord; an applicant searching for housing across multiple properties may have ten or twenty reports generated within a month. Each report becomes part of the company's records and may be queried in subsequent applications by the same applicant or in disputes
- Source data quality is highly variable. Criminal records frequently contain errors of identity (matching the wrong person), errors of disposition (showing arrests without disposition, charges later dismissed, or sealed/expunged records that should not appear), errors of recency (records that should have been removed under retention rules), and errors of scope (records from other jurisdictions, civil records mistakenly tagged as criminal). Eviction-filing records are particularly problematic: a filing may persist in commercial databases regardless of whether the case was dismissed, the tenant prevailed, the eviction did not occur, or the filing was retaliatory
- Applicants typically do not know which screening company has evaluated them, what specific records produced an adverse outcome, or how to correct errors. FCRA requires the landlord to provide an "adverse action notice" identifying the screening company, but compliance varies; even when compliance occurs, the applicant must then contact the screening company, identify the disputed record, and pursue an FCRA dispute that often takes 30+ days during which the housing opportunity is lost
- Scoring algorithms are typically proprietary trade secrets. The factors that produce a particular score are typically not disclosed to applicants; the relative weight of criminal history, credit data, eviction history, and income is not public; the validation testing for disparate impact is typically not public
- Disparate impact is documented. Black and Hispanic applicants are more likely to have criminal records and eviction filings reflecting differential exposure to criminal-legal-system contact and to landlord eviction filings, both of which themselves reflect documented racial disparities. The use of those records in screening propagates the disparities into housing access
- Sector regulation is fragmented. The FTC and CFPB have FCRA enforcement authority but have brought a small number of actions; HUD has theoretical fair-housing authority over disparate-impact effects but has been inconsistent; state-level regulation varies widely; local ordinances in some cities (limiting use of criminal history, eviction filings, or credit history) operate against a fragmented industry

A second structural feature: tenant screening is more fragmented than consumer credit reporting (where three companies dominate). Multiple major tenant screening companies operate, plus dozens of regional and specialized vendors, plus tools embedded in property-management software, plus directly-contracted background-check companies. This fragmentation means an applicant rejected by one screener may be approved by another for the same unit, and means applicants cannot effectively monitor "their" screening data because there is no single repository.

The framework treats both the company's preferred self-description and the operational reality as the authority being registered. The form does not let the former substitute for the latter.

**1.3 Authority classification:** Indirect. The company issues no binding directives. Its authority operates through R58 — outputs (reports, scores, classifications, recommendations) materially influence landlord decisions about housing access at scale. The framework's R58 explicitly classifies systems of this kind as exercising authority despite not issuing binding directives; the company acknowledges this classification.

**1.4 Domain:** Economic (primary). Data/Information (secondary). Technology (secondary).

**1.5 Statutory or constitutional basis:** Operates under the federal Fair Credit Reporting Act (FCRA, 15 U.S.C. §1681) as a "consumer reporting agency" providing reports for tenant screening purposes. Regulated by the Consumer Financial Protection Bureau (CFPB) and the Federal Trade Commission (FTC). Subject to: federal Fair Housing Act and disparate-impact doctrine (Texas Dept. of Housing v. Inclusive Communities); state consumer-reporting and tenant-screening laws (which vary substantially by state — some states have substantial regulation, including limits on use of criminal records, eviction filings without favorable disposition, and credit data; many states defer to federal FCRA); local ordinances in some cities (Cook County, IL; Seattle; San Francisco; Newark; Oakland; New York City; others have ban-the-box-style laws affecting tenant screening); contract law as applicable to landlord and applicant relationships; data-protection law as applicable. Corporate existence under [STATE] corporate law.

The framework's R28 (Expiration Default) requires that all authority expire absent affirmative renewal. Current law does not provide a renewal mechanism in the framework's sense; the 2-year framework renewal cycle is a structural commitment beyond statutory requirement.

---

## SECTION 2 — Who can this authority act upon?

**2.1 Affected party categories:**
- [x] General public (any person applying for rental housing where the company has been engaged by a landlord)
- [x] Non-consenting third parties — applicants did not negotiate the company's role; landlords select the screening company; applicants typically learn the company's identity only after adverse action notice; applicants' household members appearing in records (co-applicants, prior household composition) are also non-consenting
- [x] Vulnerable populations: applicants with criminal records (including arrests without conviction and decades-old records); applicants with prior eviction filings (including dismissed filings, tenant-prevailed filings, retaliatory filings); applicants with poor or no credit history; immigrant applicants without long credit/rental history in the U.S.; applicants leaving institutional settings (shelter, recovery, incarceration, foster care); domestic violence survivors whose records reflect coercion-driven financial or rental history; survivors who fled tenancies and were named in eviction filings; applicants with limited English proficiency
- [x] Children: minors as household members appear in some records; minors as applicants in some categories (emancipated minors, college-housing applicants); the housing decisions affect the applicant's children's school stability, medical care continuity, and developmental environment

**2.2 Approximate number of people directly affected:**
- Annual applications evaluated by this company: ~30 million
- Distinct individuals evaluated by this company over a multi-year period: ~90 million
- Sector-wide annual applications: ~60–80 million
- Distinct individuals in tenant-screening data sector-wide: estimated population ~150–200 million Americans have records in tenant-screening databases (substantial portion of all American adults who have ever rented or applied)

**2.3 Non-consenting population:** Essentially all 90 million.

There is no meaningful opt-in mechanism. Applicants submit a rental application to a landlord; the application form typically includes a generic authorization for "background check" without specifying which company will be used or what records will be queried. The applicant cannot opt out of being included in tenant-screening databases without exiting the rental market, and even then prior records persist.

R14 (Non-Participant Exposure Mapping) and R26 (Non-Participant Harm Floor) apply with full force across the entire affected population. R26 applies in particular weight to applicants whose records reflect documented systemic disparities (criminal-legal-system contact, eviction filings, credit history) that themselves correlate with race, poverty, immigration status, and disability.

**2.4 Vulnerable population specifics:**

- [x] Children — *partial*. Children are not direct subjects of screening but are downstream affected when their parents are denied housing. Mitigations: the company commits to not using children's data as input to applicant scoring; aggregate tracking of family-application outcomes monitored where data permits.
- [x] Patients during medical care — *partial*. Applicants with medical conditions documented in court records (mental-health-related involuntary commitments, substance-use-related charges, civil commitment proceedings) face screening exposure. Medical data per se is excluded but proxies in court records persist. The company commits to: (a) not using medical data directly; (b) following CFPB rules on medical-debt exclusion in credit-data inputs; (c) ongoing review of court-records exposure that operates as medical-status proxy.
- [x] Detained or confined persons — *yes*. Persons exiting incarceration face systematic screening exclusion through criminal-record use. The company's practices regarding criminal-record age, severity, and disposition are central to this population's housing access. The company commits to: (a) age-based filtering of criminal records consistent with federal CFPB guidance and applicable state and local law; (b) exclusion of arrest-without-conviction records consistent with EEOC fair-housing guidance and applicable law; (c) compliance with ban-the-box-style laws in jurisdictions where they apply; (d) HUD 2016 disparate-impact guidance on criminal-record use in housing decisions. R26 substantial gap acknowledged: aggregate practice across the company's products and across the sector continues to produce documented disparate exclusion.
- [x] Persons in coercive economic relationships — *yes*. Applicants in financial precarity, applicants whose only available housing is in market segments where screening is universal, applicants whose immigration status creates pressure to avoid disputes — all face elevated structural risk from screening outcomes. R26 substantial gap.
- [x] Persons unable to advocate for themselves — *yes*. Applicants with limited English proficiency face disadvantage in: understanding the screening process; obtaining adverse-action notice; navigating FCRA dispute procedures; understanding their FCRA rights. Applicants with cognitive disabilities, mental illness, or limited literacy face similar disadvantage. The company commits to: FCRA disclosures in the applicant's preferred language where applicable; accessible dispute procedures; reasonable accommodations on request. R26 substantial gaps acknowledged in current operational practice.

The company acknowledges that R26 (stricter harm tolerance for non-participants) applies with particular weight because essentially all 90 million affected persons are non-consenting and substantial portions are vulnerable across multiple categories simultaneously.

---

## SECTION 3 — What can it do, and what can it not do?

**3.1 Geographic reach:** United States — national operations; some operations in U.S. territories.

**3.2 Coercive ceiling:** No direct coercive authority. Functional authority operates through:

- *Inclusion:* Automatic inclusion of any individual whose data appears in source systems the company queries; inclusion does not require applicant opt-in
- *Classification:* Assignment of scores, tier classifications, recommendations, and indicators based on company rules and algorithms
- *Distribution:* Sale or licensing of reports to landlords and property management companies; the company has approximately ~25,000 landlord and property-management customer accounts
- *Persistence:* Retention of reports and inputs per FCRA and applicable law; FCRA generally limits adverse-information reporting to 7 years (10 for bankruptcies), but underlying records may persist in source systems indefinitely
- *Aggregate-data products:* Sale of aggregate analytics to property management companies and other purchasers

The functional ceiling: outputs shape access to rental housing in the substantial majority of formal-market rental transactions. A "Decline" recommendation or low score effectively excludes the applicant from that unit; for applicants whose adverse records persist across reports, exclusion from substantial portions of the rental market is the practical effect.

The company may NOT (per FCRA, federal fair-housing law, and applicable state and local law):
- Compile or distribute reports without an FCRA-compliant authorized purpose
- Refuse to investigate disputes within FCRA-required timelines
- Retain adverse information beyond FCRA-permitted periods
- Provide data for prohibited purposes (e.g., non-housing uses without separate authorization)
- Discriminate on protected characteristics; produce reports that operate as proxies for protected characteristics in violation of fair-housing law
- Operate in violation of state and local tenant-screening regulations (variable by jurisdiction)
- Sell aggregate or de-identified data for surveillance purposes beyond authorized purposes

**3.3 Resource ceiling:** For a major tenant-screening company:
- Operating budget: in the hundreds of millions to ~$1B range, depending on company scale
- Staff: thousands of FTE
- Database: tens of millions to ~100 million applicant records; hundreds of millions of underlying source records
- Customer relationships: thousands of landlord and property management customers

**3.4 Explicit exclusions:**
- **Geographic:** Bounded by U.S. operations subject to applicable law
- **Action:** May not refuse to provide an applicant her own report on FCRA request; may not refuse to investigate disputes; may not retain adverse records beyond FCRA periods; may not include records the applicant has corrected; may not include records expunged or sealed where law prohibits
- **Data:** May not collect medical information; may not collect protected-characteristic data directly (race, religion, national origin, sexual orientation, gender identity, disability beyond what fair-housing law permits); may not retain sex offender registry data beyond authorized purpose; may not share data outside FCRA-authorized purposes; subject to applicable data-protection law
- **Procedural:** May not use scoring methodologies that violate disparate-impact doctrine; may not omit FCRA-required disclosures; may not refuse reasonable accommodation in dispute procedures
- **Other:** Subject to state and local tenant-screening regulations; subject to evolving CFPB and FTC rulemaking; subject to ongoing class-action and individual litigation

**3.5 Indirect influence boundaries:** Substantial. This is the load-bearing section.

The company's outputs propagate widely:
- *Tenant screening reports* are used by landlords for rental decisions; "Decline" recommendations effectively exclude the applicant from that unit; cumulative across applications, persistent adverse records may exclude the applicant from substantial portions of the formal rental market
- *Scores and tier classifications* shape conditional approvals (deposit increases, co-signer requirements, lease term modifications) that materially affect applicants' financial position
- *Aggregate analytics products* sold to property management companies inform portfolio-level decisions including which markets to enter, which property types to acquire, and which applicant categories to target or avoid
- *Cross-application records* — the company's records of an applicant's prior screening history, including prior dispute activity, may inform subsequent screening
- *Source-data feedback loops* — when the company sources eviction filings from court records, the company contributes to the persistence of those records' practical effect; landlords filing evictions know that the filing will appear in screening regardless of disposition; this shapes filing behavior
- *Algorithmic decisions* propagate through the report; the underlying logic is typically not visible to applicant or landlord
- *Compliance-language framing* in reports normalizes scoring outputs as objective, even where the underlying methodology has documented disparate-impact concerns

R58 applies fully. The company does not directly compel any landlord action; its outputs materially shape outcomes determined by others at scale. The framework's R58 explicitly classifies systems of this kind as exercising authority.

The framework also recognizes a propagation pattern: because the same applicant may be screened by multiple landlords using the same or similar screening companies, an erroneous record persists across applications. Correction at one company does not necessarily correct the underlying source data or the same record at other screeners. The applicant's effective recourse is fragmented across the companies that may have evaluated her.

**3.6 Anti-proxy declaration:**

The company commits to not using:

- *Proxy for race, ethnicity, national origin:* Reports, scores, classifications, and recommendations may not be based on race, ethnicity, or national origin. Acknowledged that variables in operational use (criminal records, eviction filings, credit history, address history) correlate with race in this country in ways that are documented across decades. R66/R74 finding acknowledged at registration as a foundational structural finding; aggregate disparate-impact testing of scoring outputs and recommendation patterns is committed; results published. The company commits to compliance with HUD 2016 disparate-impact guidance on criminal-record use and to participation in HUD's evolving fair-housing rulemaking.
- *Proxy for poverty:* Scoring may not effectively use markers of poverty (low income, no credit history, prior subsidized-housing history, prior cash-payment-only rental history) as proxy for unsuitability. Acknowledged that operational practice substantially correlates outcomes with economic resources; the same conditions that limit applicants' financial profiles are treated as evidence of risk rather than as conditions the system might address. R66 substantial structural finding.
- *Proxy for criminal-legal-system contact in housing decisions:* Use of criminal records as input must comply with HUD disparate-impact guidance: individualized assessment, time-since-offense considerations, nature-of-offense considerations, evidence of rehabilitation. Acknowledged that operational practice across the sector frequently fails to implement these requirements adequately and that bright-line criminal-record exclusions remain common despite federal guidance. R66 finding.
- *Proxy for eviction filings regardless of disposition:* Use of eviction-filing records must consider disposition (dismissed, tenant prevailed, retaliatory filing). Acknowledged that operational practice frequently fails to distinguish; commitment to filtering by disposition where source data permits, and to flagging where disposition is unknown rather than treating unknown as adverse.
- *Proxy for non-conforming housing history:* Applicants with non-traditional rental history (subsidized housing, family-member tenancy, informal rental, transitional housing, recovery program housing) may not be disadvantaged on the basis of non-conformity alone.
- *Proxy for domestic-violence-survivor status:* Records reflecting coercive control by an abuser (financial records, eviction records reflecting fleeing tenancy, criminal records arising from coercion) may not function as proxy for unsuitability. The company commits to: special procedures for survivors with appropriate documentation; participation in evolving regulatory frameworks for survivor protection.
- *Proxy for disability:* Records reflecting disability-related circumstances (medical-related court records, disability-income reliance, accommodation-driven non-conformity) may not function as proxy.

The company acknowledges that all seven proxy commitments require ongoing structural attention, that historical and current practice has produced repeated R66 findings, and that the algorithmic methodologies used in the sector have been the subject of academic critique, regulatory action, and litigation regarding disparate-impact patterns.

---

## SECTION 4 — What harms can it cause?

**4.1 Bodily harm threshold:** Indirect.

The company's primary surface is data and scoring. Indirect pathways:
- *Housing instability and homelessness:* Applicants systematically excluded from rental housing by adverse screening outcomes face elevated risk of homelessness, with substantial documented bodily-harm consequences (exposure, untreated medical conditions, vulnerability to violence, mental-health deterioration). Threshold: aggregate exclusion patterns reviewed against homelessness data where correlation can be assessed.
- *Domestic violence consequences:* Survivors unable to obtain rental housing due to records reflecting abuser-driven circumstances may be forced to remain in abusive situations, with documented bodily-harm consequences. Threshold: any survivor-specific complaint pattern triggers immediate review.
- *Health consequences of housing instability for applicants with medical conditions:* Documented in public health literature.

**4.2 Agency impairment threshold:** Substantial.

- *FCRA dispute timeline failures:* Disputes not investigated within 30 days as FCRA requires — finding for each instance; aggregate dispute-timeline metrics tracked
- *Adverse-action-notice failures:* Reports producing adverse landlord action without applicant receiving FCRA-required adverse-action notice — finding for each instance reaching the company's attention; aggregate landlord-compliance education and monitoring committed
- *Dispute-process accessibility:* Disputes inaccessible to applicants with limited English proficiency, disability, or limited literacy — finding for each substantiated instance
- *Free annual report failures:* FCRA-mandated free annual report to applicants on request, when not provided, is a finding
- *Dispute outcome quality:* Aggregate dispute-resolution rates tracked; high reaffirmation rates of contested records may indicate inadequate investigation
- *Wrongful-record-correction timeliness:* Records found erroneous but not corrected at the company, in source systems, and across distribution paths — finding for each instance

**4.3 Ecological damage threshold:** Not directly applicable.

**4.4 Generational binding threshold:** Substantial.

The company's data practices produce intergenerational effects:
- *Persistent records:* Adverse records affecting an applicant persist across application cycles, often for the FCRA maximum period (7 years for adverse information; 10 for bankruptcies) but with substantially shorter periods in some state and local jurisdictions. Persistent records shape housing access throughout the period
- *Cumulative effects across the rental career:* An applicant's first decade of independent housing applications shapes credit history, rental payment history, and eviction record that themselves become inputs to subsequent screening; early-career screening adversities compound
- *Generational housing instability:* Applicants who cannot access stable housing experience documented effects on children's school continuity, healthcare continuity, and developmental outcomes; these effects shape children's own future housing and economic opportunities
- *Records propagation:* Errors in the company's records may propagate to source systems (rental payment history contributed back), to other screening companies (where data sharing occurs), and to credit reporting (where rental data is now contributed in some configurations); affected persons cannot identify all systems where their records have propagated
- *Inability to escape past financial circumstances:* The company's product structure means that years of poor credit history or eviction filings shape access to housing during the recovery period from those circumstances, regardless of current capacity

Threshold: any record-correction process that fails to propagate corrections to all derivative systems within FCRA timeline — finding; aggregate correction-propagation metrics committed.

**4.5 Communicative suppression threshold:**
- *Retaliation against complainants and litigants:* Applicants who file FCRA disputes, file complaints with regulators, or participate in litigation against the company may not face informal disadvantage in subsequent reports — finding for documented instances
- *Suppression of credible domestic-violence-survivor information:* Where survivors provide documentation of coercion-driven records, failure to apply applicable protections — finding
- *Restrictions on applicant communication with the company:* Dispute communications must be accessible — finding for inaccessibility instances

**4.6 Informational sovereignty threshold:**

This is the central harm category for tenant screening.

- *Records retention beyond FCRA timelines:* Retention of adverse information beyond 7 years (10 for bankruptcies) — finding
- *Records retention beyond shorter state and local timelines:* Retention beyond shorter limits in jurisdictions imposing them — finding
- *Inaccurate records:* Records found inaccurate but not corrected within 30 days of dispute as FCRA requires — finding
- *Identity-mismatch errors:* Records attributed to wrong individual (common with criminal records due to common-name issues) — finding for each instance; aggregate error rates published
- *Eviction-filing records without disposition:* Records of eviction filings retained without corresponding disposition information (dismissed, tenant prevailed, settled) — finding
- *Sealed and expunged records:* Records that should not appear due to sealing or expungement, appearing in reports — finding
- *Cross-system propagation:* Errors corrected at the company that persist in source systems and other screening companies — finding for cases where the company has propagation duty under FCRA
- *Aggregate-product use:* Aggregate analytics products used in ways inconsistent with FCRA permissible-purpose framework — finding
- *Data security breaches:* Unauthorized access to applicant data — finding per applicable law

**4.7 Additional harm thresholds:**

*Chronic asymmetry threshold:* If recommendation patterns, score distributions, or decline rates correlate with race, ethnicity, national origin, immigration status, disability, or family status at p<0.05 controlling for declared inputs, this triggers systemic review. The framework treats persistent disparate-impact patterns documented across decades as standing structural findings; review focuses on whether the disparity is narrowing, stable, or widening in the current period.

*Criminal-record use threshold:* Aggregate use of criminal records in scoring reviewed against HUD disparate-impact guidance; ongoing review of compliance with state and local "ban-the-box" laws in jurisdictions imposing them.

*Eviction-filing-without-disposition threshold:* Aggregate proportion of eviction-filing records retained without disposition information tracked; high proportions indicate that the company is propagating records that may not represent actual eviction outcomes.

*Survivor-specific protection threshold:* Aggregate handling of survivor-specific records and dispute outcomes tracked; failure rates indicate inadequate procedural protections.

*Customer concentration threshold:* If any single landlord or property management customer accounts for more than 25% of revenue or report volume, this triggers review of capture risk.

*Algorithmic disparate-impact threshold:* Aggregate disparate-impact testing of scoring algorithms required annually; failures trigger algorithm review and remediation.

**4.8 Threshold change-log commitment:** [x] Yes — committed.

---

## SECTION 5 — What stops it?

**STOP PATH 1 — FCRA enforcement: CFPB, FTC, and state attorneys general**
- *Activator:* Consumer Financial Protection Bureau; Federal Trade Commission; state attorneys general (FCRA grants concurrent state enforcement); private FCRA plaintiffs.
- *Trigger:* Determination of FCRA violation, supervisory finding, or consent-decree violation.
- *What "stopped" means:* Cease-and-desist orders affecting specific practices; civil penalties; required operational changes; in extreme cases restriction on operating as a consumer reporting agency. Several major tenant-screening companies have been the subject of FCRA enforcement actions in recent years.
- *Independence:* CFPB and FTC are federal agencies with statutory independence. State AGs are elected officials with structural independence. *Acknowledged limitation:* CFPB and FTC enforcement against tenant-screening companies has been intermittent; resources for systematic FCRA enforcement in this sector have been limited; tenant-screening sector has historically received less regulatory attention than consumer credit reporting.
- *Timeline:* Per agency procedures; major actions typically span 12–36 months.

**STOP PATH 2 — Federal court action: FCRA private right of action, fair-housing disparate-impact litigation, class actions**
- *Activator:* Any person with standing under FCRA's private right of action; fair-housing organizations; class action plaintiffs; HUD under fair-housing authority.
- *Trigger:* Court determination of FCRA violation, fair-housing violation, or constitutional violation in narrower circumstances.
- *What "stopped" means:* Court orders may halt specific practices, void specific actions, impose damages, require operational changes; class actions may produce sector-wide remediation.
- *Independence:* Federal courts and HUD are structurally independent. *Acknowledged limitation:* Fair-housing disparate-impact litigation faces substantial doctrinal challenges; FCRA private actions face damages and standing limitations; class-certification standards have tightened.
- *Timeline:* Per federal procedures; class actions typically span years.

**STOP PATH 3 — State and local regulation, customer-side action, and source-data reform**
- *Activator:* State legislatures; state regulatory authorities; local governments adopting tenant-screening regulations; landlord and property-management customer demand for compliant products; reforms in source-data systems (court-record sealing, eviction-filing reform, criminal-record reform).
- *Trigger:* Legislative or regulatory determination; market pressure; reform in upstream systems.
- *What "stopped" means:* State and local regulation may modify or restrict specific practices; customer demand may shift industry practice; source-data reforms may reduce the records flowing into screening.
- *Independence:* State and local governments are structurally independent. Customer demand operates as market pressure. Source-data reforms occur in upstream systems independent of the company.
- *Timeline:* Per actor; state and local regulatory cycles vary; market shifts incremental.

**5.4 Penalty for activating stop:** [x] Confirmed in policy. *Acknowledged structural concern:* Applicants who file FCRA disputes or who file complaints may face informal disadvantage in subsequent reports if the company's records reflect "frequent disputer" status or similar; the framework treats such treatment as a finding regardless of whether explicit policy permits it. The company commits that no FCRA-protected activity may be used adversely.

**5.5 Stop-path independence verification:** Federal courts, federal regulators, state AGs, and state and local governments are structurally independent of the company. *Acknowledged R03 (Institutional Capture) finding:* The tenant-screening industry maintains substantial relationships with property-management trade associations, landlord-side legal organizations, and adjacent industry groups whose interests align with current screening practice. Reform efforts encounter structural resistance.

*Acknowledged R55/R59 finding:* Tenant screening operates as a fragmented industry rather than a duopoly, but coordination through trade associations, standards bodies, and shared source-data ecosystems means industry-wide practice changes slowly. Containment review of any single screening company is incomplete without addressing the sector and its source-data dependencies.

*Acknowledged R64 (External Circumvention) finding:* The use of court-records, criminal-records, and credit-data inputs operationalizes upstream authority systems' outputs as screening authority. Where the upstream systems contain documented errors, biases, or constitutional concerns, those concerns are inherited by the screening company's outputs through R72.

**5.6 Civic trigger acknowledgment:** [x] Acknowledged.

---

## SECTION 6 — What does it depend on?

**6.1 Type 1 dependencies:**

The company operates with approximately 22 Type 1 dependency categories, including:
- Credit reporting agencies (the three major consumer credit reporting agencies provide credit data inputs; substantial structural relationship)
- Criminal-records aggregators (commercial vendors compiling court-records data nationally)
- Eviction-filing aggregators (commercial vendors compiling civil court records)
- Identity-verification vendors
- Sex-offender-registry data providers
- OFAC/sanctions-list data providers
- Employer-verification services
- Algorithmic scoring vendors (some in-house, some licensed)
- Cloud and computing infrastructure providers
- FCRA dispute-management vendors
- Customer-relationship-management technology vendors
- Compliance-services vendors

**Funding-source disclosure:** Funded through fees for screening reports paid by landlord and property-management customers; no single customer exceeds approximately 22% of revenue.

**6.2 Type 2 dependencies:**
- Consumer Financial Protection Bureau (regulator)
- Federal Trade Commission (concurrent enforcement)
- State attorneys general (concurrent enforcement)
- HUD (fair-housing authority)
- The other major tenant-screening companies (R55 sector-coordination concerns)
- Tenant-screening industry trade association
- The three major consumer credit reporting agencies (substantial structural codependence)

**6.3 Type 3 dependencies:**
- *Source-data systems:* Court records, criminal records, credit reporting agencies — without access, the company cannot produce reports
- *Cloud and computing infrastructure:* Concentration in a few large providers creates dependency
- *FCRA regulatory infrastructure:* If FCRA enforcement infrastructure compromised, stop paths 1 and 2 partially compromised
- *Algorithm vendor relationships:* Switching costs in scoring vendor relationships
- *Customer relationships with major property-management companies:* Loss of large customers compromises operational scale
- *State and local regulatory variation:* Compliance infrastructure depends on tracking ~50 state and many local jurisdictions
- *Identity-verification vendor accuracy:* Errors propagate into reports
- *Court-records-aggregator data quality:* Errors in upstream aggregation propagate

**6.4 Capture risk identification:** [x] Yes.

- *Customer concentration:* Largest single customer accounts for ~22% of revenue; threshold for review at 25% per form §6.4 (set lower than the 33% standard given the structural significance of large property-management customers in this sector).
- *Industry coordination:* The tenant-screening industry coordinates through trade associations and standards bodies; this approaches R55 fragmentation-defeating-containment territory at the sector level.
- *Source-data lock-in:* Reliance on credit-reporting-agency data, criminal-records aggregators, and eviction-filing aggregators creates structural dependency that limits the company's ability to address quality issues in upstream data.
- *Algorithmic vendor capture:* Some scoring algorithms are licensed from third parties; the company does not solely control its own primary outputs (R67/R72 concern).
- *Regulatory capture:* Regulator engagement with the tenant-screening sector has been intermittent; the company engages in policy advocacy that may shape regulatory frameworks. Lobbying disclosure committed.
- *Litigation-defense alignment:* The company participates in industry-wide legal defense in some matters, creating R55-style alignment concerns.

**6.5 Reversibility-affecting dependencies:**
- Records propagated to customer files (landlord records of past applicant evaluations) cannot be recalled
- Records propagated to source systems through feedback (where the company contributes data back) cannot be recalled
- Multi-year contracts with major customers
- Pension and personnel obligations
- Customer relationships representing decades of operational continuity

**6.6 Coordination disclosures:**

The company coordinates with:
- The three major consumer credit reporting agencies (data-sharing relationships; standards-body participation)
- Other tenant-screening companies through trade association
- Industry data standards groups
- Source-data aggregators

**Acknowledged R55/R59 finding:** The tenant-screening sector functions as a coordinated authority system in some respects (data standards, industry positions, regulatory engagement) despite consisting of multiple competing companies. Containment review of any single company is incomplete without addressing the sector.

**Acknowledged R64 finding:** The reliance on upstream source-data systems (court records, criminal records, credit reporting) means the company operationalizes those upstream systems' outputs as its own authority. Where upstream systems contain documented errors, biases, or constitutional concerns, those concerns flow through.

**6.7 Disclosure completeness assertion:** [x] Asserted with the standard acknowledgment that complete dependency mapping at this scale is structurally unattainable; informal industry-coordination relationships and customer-specific contractual terms are partially restricted from disclosure.

**6.8 External authority operationalization:**

- *Court-records data:* Upstream court-record decisions become operational screening authority. Where court records contain errors of disposition, identity, or scope, the company propagates those errors. R72 applies.
- *Criminal-records data:* Upstream criminal-justice-system outputs (arrests, charges, convictions, dispositions, sealings, expungements) become operational screening authority. R72 applies; the underlying criminal-legal-system disparities documented across decades flow through.
- *Eviction-filing data:* Upstream landlord-tenant-court filings (regardless of disposition) become operational screening authority. R72 applies; landlords' filing decisions are not subject to the procedural protections that would attach to government action.
- *Credit-reporting data:* Consumer-credit-reporting-agency outputs become operational screening authority. R72 applies; the substantial registered-example treatment of consumer credit reporting (separately registered) covers the structural concerns flowing into this surface.
- *Algorithmic scoring vendor outputs:* Where scoring algorithms are licensed, vendor methodology becomes operational screening authority. R72 applies.
- *Identity-verification vendor outputs:* Vendor identity matches become operational screening authority. R72 applies.

R64 (External Circumvention) is acknowledged: the company's outputs operationalize upstream system outputs in ways that may achieve effects (housing exclusion based on records that would not survive direct adjudication, on arrests without conviction, on dismissed eviction filings) that constitutional or statutory protections would prevent if the underlying decisions were subject to direct review.

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

**7.1 Declared metrics:**

| Metric | Source | Role | Public? |
|---|---|---|---|
| Credit data | Credit reporting agencies | Scoring input | Aggregate yes; individual to subject |
| Criminal records | Aggregators, courts | Scoring input | Aggregate yes; individual to subject |
| Eviction filings | Aggregators, courts | Scoring input | Aggregate yes; individual to subject |
| Rental payment history | Aggregators, contributed data | Scoring input | Aggregate yes; individual to subject |
| Income verification | Employer or vendor | Recommendation input | Aggregate yes |
| Identity verification | Vendor | Match confidence | Aggregate yes |
| Score, tier, or recommendation output | Internal scoring | Customer-facing output | Methodology partial; outputs to landlord and applicant |
| Dispute volume and outcome | Internal records | FCRA compliance | Aggregate yes |
| Adverse-action notice issuance | Customer reporting | FCRA compliance | Aggregate partial |

**7.2 Indirect signals:**
- *Algorithm features:* The scoring algorithm uses many features beyond the primary inputs; some are derived (trend, ratio); some are inferred. The company commits to publishing a plain-language description of primary features within next reporting cycle. R79 gap acknowledged.
- *Customer-specific scoring tiers:* Some customers receive customized scoring or recommendation tiers; the customizations shape outcomes for affected applicants but are not transparent to applicants. R67/R79 gap acknowledged.
- *Vendor algorithm decisions:* Where licensed scoring algorithms are used, the vendor's logic shapes outputs in ways the company does not fully control. R67/R72 gap acknowledged.
- *Source-data quality variations:* Different jurisdictions provide different quality of court records; the company's algorithms must accommodate this variation, and the accommodations themselves shape outputs.
- *Threshold settings on scoring outputs:* Where landlords customize approval thresholds, the threshold settings shape outcomes; thresholds may be set in ways that produce disparate impact even with non-disparate underlying scoring.

**7.3 Algorithmic decision systems:**

[x] Yes. Multiple systems with substantial R67/R81 implications:

- *Primary scoring algorithm:* Proprietary scoring methodology. The company commits to: aggregate disparate-impact testing; methodology disclosure of primary features; third-party algorithm audit. R67 partial gap acknowledged.
- *Identity-matching algorithms:* Determines whether a record matches the applicant. Errors here produce wrong-person record attribution. Aggregate error rates committed for tracking and disclosure.
- *Eviction-record processing:* Logic determining how eviction filings are presented based on disposition data availability. R67 commitment to disclose logic.
- *Criminal-record processing:* Logic determining how criminal records are presented based on age, severity, disposition. Compliance with HUD guidance committed.
- *Dispute-prioritization algorithms:* If used in dispute investigation prioritization, methodology to be disclosed.
- *Customer-customization tools:* Tools that allow landlord customers to customize their thresholds and weighting. Customization patterns reviewed for disparate-impact effects.

The company acknowledges that algorithmic systems in tenant screening raise substantial R66 (proxy for protected characteristics), R67 (auditability floor), R72 (external operationalization), and R79 (metric completeness) concerns. Aggregate disparate-impact testing committed; methodology disclosure committed within constraints of vendor IP and competitive considerations.

**7.4 Outcome-versus-declaration check:** [x] Committed. R79 (Metric Completeness) gap acknowledged: outcome patterns (particularly disparate-impact patterns in scoring and recommendation) cannot be fully predicted from declared metrics; the framework presumes undeclared influence.

---

## SECTION 8 — How is this authority watched?

**8.1 Drift monitoring:**
- Internal compliance and audit functions
- External annual audit (financial; FCRA compliance)
- CFPB and FTC supervision and enforcement
- State AG enforcement and supervision
- HUD fair-housing authority (fragmented attention to tenant screening sector)
- State and local regulatory authorities in jurisdictions imposing tenant-screening regulation
- Civil society monitoring (consumer protection organizations; tenant rights organizations; fair housing organizations; academic researchers; legal services providers)
- Litigation (substantial ongoing FCRA, fair-housing, and consumer-protection litigation against the sector)

The company acknowledges that drift detection in tenant screening is structurally challenged by: confidentiality of business operations; fragmentation of the sector; uneven regulatory attention; absence of comprehensive sector-level outcome data; political contestation of fair-housing enforcement.

**8.2 Capture risk monitoring:**
- Customer concentration disclosure (annually)
- Lobbying and trade-association activity disclosure
- Major regulatory positions disclosure
- Source-data dependency disclosure

**8.3 Audit interfaces:**
- *Proactively published:* Annual financial report; aggregate operational metrics; major rule-making engagement; FCRA compliance attestations; aggregate disparate-impact testing results (committed)
- *Available on request per FCRA:* An applicant's own report; specific records as appropriate to regulator and litigation
- *Restricted:* Algorithm internals (vendor IP, competitive); customer-specific contractual terms (competitive); deliberative materials; specific reputation-risk and category-decision deliberations (deliberative)

**8.4 Adversarial exposure (R81):** Substantial gaps acknowledged.
- Algorithm internals partially restricted
- Customer-specific contractual terms partially restricted
- Aggregate disparate-impact data not consistently collected across the sector
- Source-data quality variation makes upstream-driven errors hard to attribute
- Sector-wide coordination and pricing arrangements partially restricted (antitrust-sensitive)
- Deliberative materials about scoring methodology partially restricted

R67 (Minimum Auditability Floor) compliance is partially compromised by these restrictions. The company acknowledges this as a structural finding.

**8.5 Known structural failure modes:**
- Disparate impact in scoring, recommendation, and approval outcomes
- Identity-mismatch errors producing wrong-person record attribution
- Eviction-filing records retained without disposition information
- Criminal-record use without HUD-guidance individualized assessment
- Sealed and expunged records appearing in reports
- Survivor-specific records used without protective procedures
- FCRA dispute-timeline failures
- FCRA adverse-action-notice failures (often by landlord customers; the company has structural role in compliance)
- Algorithmic vendor IP restrictions limiting auditability
- Customer-customization tools producing differential outcomes
- Cross-screener inconsistency (same applicant evaluated differently by different screeners)
- Source-data quality variation
- Records errors propagating across cycles
- Sector-wide capture by industry trade associations
- Regulatory enforcement gaps
- Class-action settlement compliance failures

**8.6 Trade-secret declarations:**
- *Algorithm internals:* Primary scoring methodology and supplementary scoring systems. Mitigation: aggregate validation; methodology disclosure of primary features (committed); third-party audit (committed). R67 substantial gap.
- *Customer-specific contractual terms:* Pricing and customization arrangements. Mitigation: aggregate metrics; FOIA-available portions where applicable.
- *Vendor algorithm IP:* Where scoring algorithms are licensed, vendor IP restricts disclosure. Mitigation: vendor methodology disclosure committed where contractually permitted; R67 floor commitments where not.
- *Source-data aggregator agreements:* Aggregator pricing and data-quality terms partially restricted.

R67 floor compliance challenged across multiple of the above. The company commits to floor mitigations within antitrust, competitive, and contractual constraints; substantial structural gap acknowledged.

---

## SECTION 9 — How does it end?

**9.1 Estimated dismantling time:** 24 months. Justification: scale (millions of applicant records, hundreds of customers, multi-jurisdictional regulatory unwinding) requires extended timeline. Less complex than consumer credit reporting (separately registered as a 24-month dismantling) but similar in shape.

**9.2 Dismantling process:**
- Months 1–3: Cease accepting new screening requests; notice to customers, regulators, source-data partners; begin transferring active disputes
- Months 4–9: Wind down customer relationships (typically 60–90 day notice periods); transition pending disputes to resolution; archive records per FCRA requirements
- Months 10–18: Transfer essential records to public archive or successor; settle outstanding contractual obligations; release personnel
- Months 19–24: Final compliance audit; multi-state regulatory wind-down; entity dissolution

**9.3 Entrenchment factors:**
- Records propagated to customer files (landlord records) cannot be recalled
- Records contributed back to source-data ecosystems may persist beyond company dissolution
- Multi-year customer contracts with cancellation costs
- Pension and personnel obligations
- Pending litigation and regulatory matters
- Source-data partner relationships
- Customer-side dependence on screening infrastructure during transition

R61 (Anti-Entrenchment) finding: a sector-significant tenant-screening company is structurally entrenched in landlord operations in ways that one-company dismantling does not address; the broader sector continues. The framework recognizes this as a sector-level structural finding.

**9.4 Data disposition:**
- *Personal data (applicant records):* Archived to public archival institution or successor per FCRA requirements; commitments to ensuring applicant access to dispute history
- *Institutional records:* Per [STATE] corporate dissolution and federal regulatory requirements
- *Derived outputs:* Scores produced are computed on demand and not stored as derived outputs in R60's sense; past scores referenced in customer records (landlord files) remain in customer records
- *Audit logs:* Archived per regulatory requirement

**9.5 Downstream effect reversibility:**

This is the most concerning section.

The company's outputs have caused effects that no dismantling can reverse:

- *Housing denials based on records the company produced* are not reversible. An applicant denied a unit based on the company's report did not get that unit; subsequent recognition that the report contained errors does not return the missed housing opportunity, missed school district, missed neighborhood
- *Cumulative effects on rental careers:* Applicants whose early-career screening adversities shaped their housing access in formative years cannot recover those years
- *Records propagated to landlord files* persist regardless of company status; landlords retain their own records of past applicant evaluations; the underlying records continue to shape that applicant's housing access
- *Effects on housing stability for families with children:* Children whose stability was disrupted by housing denials experienced school disruption, healthcare disruption, and developmental consequences that cannot be reversed
- *Effects on persons with criminal records, eviction filings, or poor credit:* Years during which these populations were systematically excluded from rental housing cannot be recovered
- *Records propagated to credit reporting through rental-payment-history feedback* (where this occurs) cannot be recalled
- *Records errors that affected persons cannot identify or correct:* Many affected persons do not know which screening company evaluated them, which records produced adverse outcomes, or how to pursue correction; the unrecovered errors persist
- *Coordination with upstream system errors* (criminal-records errors, eviction-filing errors, credit-data errors) propagated through the company's products produced housing exclusion that constitutional or due-process protections would have prevented if the underlying decisions were subject to direct review

R63 (Downstream Effect Reversibility) and R60 (Derived Authority Inheritance) apply with full force. The company cannot reverse these effects. R65 (Propagation Duty) requires that on dissolution: (a) the company notify downstream systems that its data is no longer authoritative; (b) the company support remediation, including expungement and correction processes; (c) the company preserve records to enable historical investigation and remediation.

The framework's reversibility requirement is, for tenant screening, a commitment to mitigate, to acknowledge, and to support remediation — not a commitment that effects can be undone. The gap between the structural authority to exclude applicants from housing access and the structural capacity to reverse exclusion effects is, for tenant-screening authority, among the larger of any authority type the framework registers, and is comparable in shape to consumer credit reporting (separately registered) but with weaker regulatory scrutiny historically.

**9.6 Replacement feasibility:**

R51 (Institutional Replacement Feasibility) requires that this authority be replaceable without destabilizing services beyond authorized scope.

Tenant-screening function *could* be replaced through alternative configurations: substantial reform of source-data systems (court records, eviction filings, criminal records); legislative restructuring of permissible inputs to housing decisions; landlord-side direct review of applicant documentation rather than third-party screening; community-based reference systems; regulatory restructuring that emphasizes individualized assessment over algorithmic scoring.

Replacement of this specific company without sector disruption is feasible at sector level (multiple competitors exist); without sector disruption (replacement of the sector by alternative configurations) is harder and depends on legislative and regulatory action. R51 partial gap acknowledged.

**9.7 Reversibility verification:**

No formal dismantling rehearsal has been conducted. The company has continuity-of-operations planning for technical disruption but no operational practice of simulating cessation. R43 (Reversibility Verification) gap acknowledged. Commitment to a desktop dismantling exercise within 24 months of registration with results public.

---

## SECTION 10 — Authorization, renewal, and trigger declarations

**10.1 Authorizing body:** Operates under FCRA federal authorization and [STATE] corporate authorization.

**10.2 Date of authorization:** Variable; corporate existence and FCRA-compliant operation predate registration. For framework purposes: [DATE] (registration date).

**10.3 Expiration date:** [EXPIRATION DATE].

**10.4 Renewal interval:** 2 years. Justification: scale, harm potential, the substantial open R26/R63/R66/R67/R69 findings, and the rapid evolution of operations, source data, and regulatory environment warrant the shorter end of SCBP-09's range. The 2-year cycle is a structural commitment beyond statutory requirement.

**10.5 Renewal evidence declaration:** [x] All five domains.

**10.6 Necessity-decay acknowledgment:** [x] Acknowledged. *Note:* As an FCRA-regulated industry actor, claims of "decreasing necessity" depend on the broader regulatory framework and on the continued absence of alternative configurations. R62 compliance requires affirmative evidence of reducing scope, dependency, opacity, persistence, and disparate impact; current operational practice does not yet demonstrate substantive reduction across these dimensions. R62 commitment with structural caveat.

**10.7 Aggregate trigger threshold:** 100 in 90 days. SCBP-09 §II places non-consenting affected populations of ~90 million at the upper boundary of the 1,000,000–100,000,000 band (25–250). The company elects 100 — below midpoint but reflecting scale.

**10.8 Aggregate threshold justification:** One hundred independent civic concerns about company practice in 90 days from a non-consenting population of ~90 million indicates organized structural concern.

**10.9 Response time window:** 30 days.

**10.10 Response window justification:** Not required (default).

---

## SECTION 11 — What does this authority commit to publishing?

**11.1 Citizen ledger publication:** Quarterly. Includes: aggregate operational metrics (reports issued, dispute volume and outcomes, adverse-action statistics, error rates); aggregate disparate-impact testing results; methodology disclosure (primary scoring features); customer concentration metrics; lobbying and regulatory engagement; settlements and consent decrees; algorithmic vendor activity; threshold change log.

**11.2 Threshold change log:** Within 7 days of any change.

**11.3 Interpretation change log:** Continuous.

**11.4 Renewal process visibility:** [x] Committed. Renewal review by parties drawn from affected categories: applicants who have been subject to adverse outcomes (including those with criminal records, eviction filings, poor credit, who can speak to the operational reality); domestic violence survivors with screening experience; persons reentering society from incarceration; immigrant applicant advocates; tenant rights organizations; fair housing organizations; legal services providers for tenants; consumer protection advocates; academic researchers in housing and consumer reporting — *not* by the company, the trade association, sister screening companies, source-data partners, or any party with structural alignment.

**11.5 Stop event log:** [x] Acknowledged.

---

## SECTION 12 — Honesty assertions

**12.1 Disclosure completeness assertion:** [x] Asserted, with acknowledgment that several disclosures (algorithm internals, customer-specific terms, full source-data dependency mapping, complete propagation tracking) are partial at registration due to vendor IP, competitive considerations, and operational complexity. Partial-disclosure status is itself committed to be reported quarterly.

**12.2 Update obligation:** [x] Committed.

**12.3 Discoverability acknowledgment:** [x] Acknowledged.

**12.4 Burden of proof acknowledgment:** [x] Acknowledged. R69 places the burden of proving constitutional and statutory compliance on the company. The company accepts that lack of evidence, restricted evidence, or inaccessible evidence results in non-compliance findings — and accepts that current restrictions on algorithm internals, vendor methodology, customer-specific terms, and disaggregated outcome data produce R69 findings until those restrictions are addressed.

**12.5 Anti-weaponization acknowledgment:** [x] Acknowledged. Registration does not legitimize practices the framework's structural limits prohibit. The company acknowledges that the historical operational practice of the tenant-screening sector — the use of records reflecting documented systemic disparities as inputs to housing-access decisions, with limited transparency to affected applicants and limited regulatory scrutiny — has been operationalized in ways the framework's structural-honesty review identifies as themselves harms.

---

## SECTION 13 — Submitter

*[Submitter information retained by registry as metadata.]*

---

*REG-TENANT-SCREENING-EXAMPLE — worked example of a national tenant-screening and rental-applicant evaluation company*
*Registered under the Bounded Power Framework*
*All authority governed by the Structural Constitution (SCBP-04)*
