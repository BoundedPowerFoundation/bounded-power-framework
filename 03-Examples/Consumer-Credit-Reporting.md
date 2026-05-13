---
mechanism_id: SCBP-REG-EXAMPLE-CONSUMER-CREDIT-REPORTING
mechanism_name: "CONSUMER-CREDIT-REPORTING-EXAMPLE"
status: EXAMPLE
domain: economic
authority_classification: indirect
registered_date: [DATE]
authorization_date: [AUTHORIZATION DATE]
expiration_date: [EXPIRATION DATE]
renewal_interval_years: 2
funding_types:
  - private_for_profit
funding_concentration_max_pct: 18
affected_party_categories:
  - general_public
  - non_consenting_third_parties
  - vulnerable_populations
  - children
affected_population_estimate: 245000000
non_consenting_population_estimate: 245000000
entity_size: institutional
geographic_specificity: single_nation
geographic_reach: "United States — all 50 states, DC, and US territories"
aggregate_threshold_count: 250
aggregate_threshold_window_days: 90
response_window_days: 30
harm_categories_declared:
  - agency_impairment
  - communicative_suppression
  - informational_sovereignty
  - chronic_asymmetry
  - generational_binding
algorithmic_decision_systems_used: true
dependency_count_type1: 47
dependency_count_type2: 8
dependency_count_type3: 12
capture_risk_identified: true
disclosure_completeness_assertion: true
update_obligation_committed: true
discoverability_acknowledged: true
burden_of_proof_acknowledged: true
anti_weaponization_acknowledged: true
---

# Mechanism Record — REG-CONSUMER-CREDIT-REPORTING-EXAMPLE

**CONSUMER-CREDIT-REPORTING-EXAMPLE**

| Field | Value |
|---|---|
| Mechanism ID | REG-CONSUMER-CREDIT-REPORTING-EXAMPLE |
| Status | EXAMPLE |
| Registered | [DATE] |
| Authorization expires | [EXPIRATION DATE] |
| Domain | Economic |

---

## SECTION 1 — What is this authority?

**1.1 Mechanism name:** CONSUMER-CREDIT-REPORTING-EXAMPLE — a national consumer credit reporting agency.

**1.2 Functional description:** This authority operates a consumer credit reporting and scoring system covering approximately 245 million US adults. Functional outputs: (a) credit reports compiled from data supplied by approximately 3,400 furnishers (banks, lenders, utilities, landlords, collection agencies, courts, employers); (b) credit scores derived algorithmically from those reports; (c) classifications and indicators (e.g., "subprime," "thin file," "fraud alert") that influence access to credit, housing, employment, insurance, and certain government benefits. Reports and scores are used by approximately 28,000 institutional users as decision inputs in housing, employment, lending, insurance pricing, and rental approval decisions. The authority does not directly compel any outcome; its outputs materially shape outcomes determined by others.

**1.3 Authority classification:** Indirect. The authority issues no binding directives. Its authority operates through R58 — its outputs materially influence, condition, score, recommend, route, filter, and allocate access to credit, housing, employment, insurance, and other consequential decisions made by other parties at scale.

The authority acknowledges that R58 explicitly classifies systems of this kind as exercising authority despite not issuing binding directives, and accepts the constitutional consequences of that classification.

**1.4 Domain:** Economic (primary). Data/Information (secondary).

**1.5 Statutory or constitutional basis:** Operates under the federal Fair Credit Reporting Act (FCRA, 15 U.S.C. §1681) as a "consumer reporting agency." Regulated by the Consumer Financial Protection Bureau (CFPB) and the Federal Trade Commission (FTC). State law (varying by jurisdiction) creates additional obligations and permitted uses. Corporate existence established under [STATE] corporate law; authority to operate as a credit reporting agency derives from compliance with FCRA registration and operating requirements.

---

## SECTION 2 — Who can this authority act upon?

**2.1 Affected party categories:**
- [x] General public (no opt-in required to be affected)
- [x] Non-consenting third parties (essentially the entire US adult population is in the database without affirmative opt-in)
- [x] Vulnerable populations: elderly, victims of identity theft, victims of domestic violence whose financial autonomy is compromised, persons recovering from medical bankruptcy, formerly incarcerated persons, persons with limited English proficiency
- [x] Children (under age of majority): minors appear in the database in three contexts: (i) authorized users on parents' accounts; (ii) victims of synthetic identity fraud where the child's SSN was used; (iii) data subjects in family financial records.

**2.2 Approximate number of people directly affected:** Approximately 245 million US adults have credit files. Approximately 12 million minors appear in the database in some form. Total affected: ~257 million.

**2.3 Non-consenting population:** Essentially the entire affected population. There is no meaningful opt-in mechanism for being included in the database. Inclusion is automatic when any furnisher reports activity. Consumers may dispute records but cannot remove themselves from the system without proving the records are inaccurate.

This is a structural feature of consumer credit reporting that R14 (Non-Participant Exposure Mapping) and R26 (Non-Participant Harm Floor) apply to with full force.

**2.4 Vulnerable population specifics:**
- [x] Children — the authority commits to: (a) freezing minor credit files at no charge; (b) detecting and proactively investigating synthetic identity fraud; (c) deleting all minor records on the data subject's 18th birthday + 30 days unless affirmatively re-established by the now-adult subject; (d) providing parental access to minor file contents on identity verification.
- [x] Patients during medical care — medical debt under $500 is excluded from consumer-facing scores (per CFPB rule). Medical debt over $500 must be in collections for >12 months before reporting. Disputed medical debt records are investigated as priority items.
- [ ] Detained or confined persons — partially. Persons in detention may have records affected by inability to manage finances during detention. No specific protections currently; this is a R26 gap acknowledged here.
- [x] Persons in coercive economic relationships — data is used in employment screening; persons whose employer accesses credit reports are in coercive relationships with respect to that data. Mitigations: free annual reports; employment-context disputes handled within 30 days.
- [x] Persons unable to advocate for themselves — partial. Dispute mechanisms available in writing, online, and by phone in English and Spanish. Not currently available in other languages or in formats accessible to persons with disabilities affecting written communication. R26 gap acknowledged. Remediation: planned but not currently scheduled.

---

## SECTION 3 — What can it do, and what can it not do?

**3.1 Geographic reach:**
- [x] Single nation: United States — all 50 states, DC, and US territories. Data subjects must have a US address or social security number; expatriate data is retained but not actively reported.

**3.2 Coercive ceiling:** No direct coercive authority. Functional power exercised through:
- *Inclusion:* automatic inclusion of any individual in the database upon receipt of furnisher data
- *Classification:* assignment of credit scores, classifications (subprime/prime/etc.), and indicators (fraud alert, identity verified, thin file, etc.)
- *Distribution:* sale or licensing of reports to approximately 28,000 institutional users for decisions in lending, housing, employment, insurance, and benefits adjudication
- *Persistence:* retention of negative records for up to 7 years (10 for bankruptcies); positive records retained indefinitely

The functional ceiling: outputs shape access decisions affecting essentially any consequential transaction in modern US life. A credit score below ~580 effectively excludes a person from mainstream credit, much rental housing, certain employment, and standard insurance pricing.

**3.3 Resource ceiling:**
- Maximum operating budget: ~$3.2B annually (public company; budget governed by board and shareholder oversight)
- Maximum staff: ~12,000 FTE
- Maximum data systems and data volume: database contains approximately 28 billion historical credit data points. Active records cover ~257 million subjects.

**3.4 Explicit exclusions:**
- **Geographic exclusions:** May not include data subjects without a US address or SSN; may not export US consumer data outside US jurisdiction without explicit FCRA-compliant authorization.
- **Action exclusions:** May not refuse to include disputed information without investigation; may not retain negative records beyond 7 years (10 for bankruptcies); may not include certain protected information (race, national origin, religion, sexual orientation, gender identity, age in certain contexts) directly; may not respond to law enforcement requests without judicial process per FCRA §1681e.
- **Data exclusions:** May not collect or retain biometric data of consumers; may not collect or retain genetic data; may not collect or retain protected class information directly; may not retain data after dispute resolution if dispute results in deletion.
- **Procedural exclusions:** May not enter into pricing arrangements with users that incentivize specific outcomes (e.g., volume discounts that reward more denials); may not contract with data brokers for protected class information.
- **Temporal exclusions:** Data retention bounded per §3.4 above and FCRA timelines.
- **Other exclusions:** May not use credit scores or classifications to predict outcomes outside the credit/financial domain (e.g., political behavior, health outcomes, personal relationships); may not sell aggregate or de-identified data for surveillance purposes.

**3.5 Indirect influence boundaries:** This is the substantive section.

Outputs materially influencing decisions made by others:
- *Credit reports:* Used by lenders for credit decisions, by landlords for rental decisions, by employers for employment decisions (in jurisdictions where permitted), by insurers for pricing, by some government agencies for benefits eligibility.
- *Credit scores (FICO and proprietary scores):* Used as primary or substantial inputs in essentially all consumer credit decisions; thresholds used by lenders to automatically approve, manually review, or auto-deny applications.
- *Classifications and indicators:* "Subprime" classification; "thin file" indicator; "fraud alert" status; "identity verified" status; "delinquency" markers; "charge-off" markers; "bankruptcy" markers; "collections" markers — each materially influences downstream decisions.
- *Pre-screening lists:* The authority sells pre-screened consumer lists to lenders and marketers; these determine who receives credit offers.

For each: the institutional user, not the authority, makes the final decision. But the authority's output substantially shapes which decision is reached. R58 applies fully.

**3.6 Anti-proxy declaration:**

The authority commits to not using the following proxies:

- *Proxy for race, national origin, religion:* Does not use ZIP code as a direct input in credit scores. Acknowledged that variables in use (residential history, debt-to-income ratio, credit mix) correlate with protected classes. R66/R74 finding acknowledged here. The credit-reporting industry has historically been the subject of fair-lending litigation alleging that scoring produces racially disparate outcomes; the authority commits to: (a) annual fair-lending disparity testing of its primary scoring algorithm with results published; (b) third-party algorithmic audit every two years; (c) public methodology disclosure for primary scoring algorithm.
- *Proxy for political affiliation:* Does not collect or use political data. Does not sell data for political advertising.
- *Proxy for health status:* Excludes medical debt under $500 from consumer-facing reports. Does not collect or use health-related data points.
- *Proxy for citizenship status:* Distinguishes between thin-file consumers and consumers who have not used credit. Does not infer or report citizenship.
- *Proxy for sexual orientation or gender identity:* Does not collect or use this data; commits to investigating any reported case where outputs appear to discriminate on these bases.

The authority acknowledges that its scoring model is itself a proxy for "creditworthiness," which is operationally a proxy for "likelihood of repayment under prevailing conditions." The authority commits to operating only within the "creditworthiness for credit decisions" purpose; using outputs for other prediction purposes (employment screening, surveillance, political analysis) would be a R66 concern, and the authority commits to enforcing this through licensing terms and audit.

---

## SECTION 4 — What harms can it cause?

**4.1 Bodily harm threshold:** Not applicable. Outputs do not cause direct bodily harm. Indirect bodily harm (e.g., delayed medical care due to inability to obtain credit) is captured under §4.5 communicative suppression and §4.7 chronic asymmetry.

**4.2 Agency impairment threshold:** If more than 0.5% of disputes filed in any rolling 90-day period result in unresolved disputes after FCRA's required investigation timeline, the authority enters provisional review. An unresolved dispute means a data subject cannot correct a record affecting access to credit, housing, employment.

Additionally: if customer-facing dispute systems become inaccessible (web outage, phone wait times >60 minutes for >7 consecutive days, mail processing delays >30 days), the inaccessibility itself triggers review.

**4.3 Ecological damage threshold:** Not applicable.

**4.4 Generational binding threshold:** If a record affecting a deceased data subject continues to materially influence access decisions for that subject's family or descendants beyond 12 months after death, the authority enters provisional review. This addresses scenarios where a deceased parent's collections continue to be reported on the credit history of authorized users.

**4.5 Communicative suppression threshold:** If outputs are documented as having been used to retaliate against a specific data subject's protected speech or political activity, the case enters provisional review regardless of source. Substantiated patterns of such use trigger systemic review.

The authority commits to not selling or licensing data for use in chilling protected speech; allegations that products were used in such chilling enter immediate provisional review.

**4.6 Informational sovereignty threshold:** The primary harm category. Multi-part threshold:

- *Retention violations:* Negative records retained beyond FCRA timelines (7 years; 10 for bankruptcies) trigger immediate review.
- *Inaccurate records:* Records found to be inaccurate but not corrected within 30 days of dispute trigger review.
- *Unauthorized disclosure:* Any disclosure of data outside FCRA-permitted purposes triggers immediate review.
- *Synthetic identity fraud:* When data is used to perpetrate fraud against a real data subject (e.g., a minor whose SSN is used to construct a synthetic identity), the authority commits to: (a) investigating within 30 days; (b) restoring the subject's record; (c) tracking aggregate synthetic-fraud incidents and publishing trend data quarterly.
- *Aggregate-record threshold:* If aggregate disputed-record rate exceeds 2% of all active records over any 90-day period, this is a systemic finding triggering review.

**4.7 Additional harm thresholds:**

*Chronic asymmetry threshold:* If the primary scoring algorithm produces statistically significant disparate outcomes (p<0.05) by race, ethnicity, national origin, or other protected class as documented by an independent fair-lending audit, the authority enters review.

*Geographic asymmetry threshold:* If access-to-credit denial rates correlate with ZIP code in ways that exceed what economic factors alone would predict, by margin >15%, this triggers review. ZIP-based redlining has been illegal since 1977; this threshold operationalizes monitoring.

*Survivor-of-violence threshold:* The authority commits to providing affirmative protective procedures for victims of domestic violence whose financial records have been weaponized by abusers. Failure to provide these procedures in any documented case constitutes a finding.

*Capture threshold:* If any single corporate user (e.g., a single bank) accounts for more than 25% of report-purchase revenue, this triggers review of capture risk.

**4.8 Threshold change-log commitment:** [x] Yes — committed.

---

## SECTION 5 — What stops it?

This section is structurally difficult because the authority is a large public company with substantial influence over its own oversight environment. Stop paths must be genuinely independent.

**STOP PATH 1 — CFPB enforcement action**
- *Who can activate:* The Consumer Financial Protection Bureau (federal regulator).
- *Trigger condition:* CFPB determination of FCRA violation, supervisory finding, or consent-decree violation.
- *What "stopped" means:* CFPB may issue cease-and-desist orders affecting specific practices; impose civil penalties; require operational changes; or in extreme cases, restrict the authority's ability to operate as a consumer reporting agency.
- *Independence justification:* CFPB is a federal agency with statutory independence (subject to ongoing political disputes about its structure). CFPB receives no funding from the authority. The authority cannot influence CFPB personnel decisions or budget. *Acknowledged limitation:* CFPB's effectiveness depends on its political support, which has varied with administrations. R32 partial-independence finding.
- *Post-stop review process and timeline:* CFPB enforcement actions follow administrative law procedures. The authority may contest in administrative court; appeals proceed through federal courts. Timeline: variable, often 12–24 months for major actions.

**STOP PATH 2 — Federal court order or class action**
- *Who can activate:* Any federal court, on motion of any party with standing under FCRA's private right of action.
- *Trigger condition:* Court determination of FCRA violation or constitutional violation.
- *What "stopped" means:* Court orders may halt specific practices, impose remediation, or in class actions, require systemic changes affecting millions of records.
- *Independence justification:* Federal judiciary is structurally independent. The authority cannot influence judicial appointments or rulings.
- *Post-stop review process and timeline:* Per federal court procedures.

**STOP PATH 3 — State Attorney General action**
- *Who can activate:* Any state Attorney General, under FCRA's grant of state enforcement authority.
- *Trigger condition:* State AG determination of FCRA violation or state law violation affecting state residents.
- *What "stopped" means:* State-specific enforcement; may involve injunctions limiting operations within that state, civil penalties, or required remediation.
- *Independence justification:* State AGs are elected officials in most states, structurally independent of the authority. The authority operates in all 50 states; influence over any single AG does not protect from action by any other.
- *Post-stop review process and timeline:* Per state procedures.

**5.4 Penalty for activating stop:** [x] Confirmed — no penalty applies. The authority cannot retaliate against employees, contractors, or business partners for raising compliance concerns. Whistleblower protections under FCRA, Sarbanes-Oxley, and Dodd-Frank apply.

**5.5 Stop-path independence verification:** [x] Yes. Each of the three stop paths can be activated even if the authority refuses to cooperate — federal regulator authority, federal court orders, and state AG actions are all enforceable against the authority without its consent.

*Acknowledged structural concern:* As a major industry actor, the authority participates in regulatory and legislative processes that shape FCRA itself. This is a R03 (Institutional Capture) risk that no individual stop path can address — it requires ongoing public attention to whether the regulatory framework is being weakened.

**5.6 Civic trigger acknowledgment:** [x] Acknowledged. The authority commits to publicly responding to civic triggers within 30 days. As an institutional actor with substantial legal resources, responses will likely include legal review — but the response itself, including any disputed legal positions, will be public.

---

## SECTION 6 — What does it depend on?

**6.1 Type 1 dependencies (operational extensions acting under this authority):**

The authority operates with approximately 47 Type 1 dependencies, including:
- Data furnishers (~3,400 — categorized: banks, credit unions, mortgage servicers, auto lenders, collection agencies, courts, utilities, landlords, employers using payroll-based reporting). Compensation: data furnishing is typically uncompensated; furnishers report data as part of the credit reporting ecosystem.
- Dispute investigation contractors (3 firms handling ~25% of dispute volume). Compensation: per-dispute flat fee; not revenue-share.
- Identity verification vendors (5 firms providing fraud detection services). Compensation: per-verification flat fee.
- Algorithm vendor (FICO Score License) — primary FICO scoring algorithm licensed from FICO Corporation. Compensation: per-score license fee.
- Cloud infrastructure (3 major providers; multi-cloud architecture).
- ~35 specialized data processing and analytics firms providing supplemental services.

**Funding-source disclosure:** Funding is from data sales to ~28,000 institutional users. No single user exceeds 18% of revenue. The 25% capture threshold (§4.7) is set above this current concentration.

**6.2 Type 2 dependencies (independent authorities with structural relationship):**

- Consumer Financial Protection Bureau (regulator) — supervisory and enforcement authority
- Federal Trade Commission (regulator) — concurrent enforcement authority
- Federal Reserve (indirect) — outputs are used in monetary policy via the credit channel
- State Attorneys General (50 + DC + territories) — concurrent enforcement authority
- The two other major credit reporting agencies — coordinate on certain industry standards via consortium; R55 finding addressed in §6.6
- Credit reporting industry trade association — represents the authority in policy advocacy
- FICO Corporation — provides the primary scoring algorithm; structural codependence
- US Treasury — certain data is reported to Treasury for tax compliance purposes

**6.3 Type 3 dependencies (infrastructure compromising stop paths):**

- *Data furnisher network:* if all furnishers ceased reporting, the authority could not maintain current records — but stop paths against the authority would still function
- *FICO scoring license:* if FICO terminated the license, FICO scores could not be produced — but core records would remain, and stop paths would still function
- *Federal regulatory infrastructure (CFPB, FTC, courts, state AGs):* if federal regulatory infrastructure were dismantled or captured, stop path 1 and significantly stop path 3 would be compromised. Acknowledged: this is a structural fragility outside the authority's control.
- *Cloud infrastructure providers:* outages would prevent operation but would not compromise stop paths against the authority
- *Multi-state legal counsel network:* compliance with 50+ jurisdictions' varying requirements depends on legal infrastructure — but compliance failure is itself a stop trigger, not a compromise of stop paths
- *Identity verification vendors:* failures here would affect dispute resolution times, potentially triggering §4.2 thresholds

**6.4 Capture risk identification:** [x] Yes. Multiple risks:

- *Industry concentration:* The authority is one of three major credit reporting agencies. The "Big Three" effectively coordinate via consortium; this approaches R55 fragmentation-defeating-containment territory.
- *Regulatory capture risk:* As a major regulated entity, the authority employs former CFPB staff and former state regulators; CFPB and state regulator staff sometimes move to the authority. Mitigation: 12-month cooling-off period for any new employee who served in CFPB/FTC/state regulator role.
- *Lobbying:* Approximately $4M annually on federal lobbying. Disclosure: required by federal lobbying law; the authority commits to making lobbying activity public quarterly via citizen ledger (§11).
- *Customer concentration:* No single user >18% of revenue currently; capture threshold set at 25%.
- *Algorithmic capture:* The authority licenses FICO scoring; FICO is itself a separately-incorporated entity with its own incentives. The authority does not solely control its own primary output.

**6.5 Reversibility-affecting dependencies:**
- The 28 billion historical records would need to be archived (per FCRA, in some form) or destroyed.
- Pending disputes (~340,000 active at any given time) would need processing.
- Furnisher relationships (3,400) would need to be wound down or transferred to successor entities.
- Multi-state regulatory obligations would need to be unwound.
- Estimated dismantling time: 24 months.

**6.6 Coordination disclosures:**

The authority coordinates with the other two major credit reporting agencies via:
- Industry data standards consortium (sharing data formats, dispute processing standards)
- Industry-wide fraud detection coordination (limited; legal under FCRA)
- Joint legal defense in some industry-wide litigation
- Joint regulatory response on industry-wide policy issues

**Acknowledged R55/R59 finding:** The "Big Three" function operationally as a single industry system on certain matters. The authority acknowledges that R55 and R59 may treat the three agencies as a single authority system for purposes of containment review.

**6.7 Disclosure completeness assertion:** [x] Asserted. The authority asserts that the dependencies listed above include all known Type 1, Type 2, and stop-path-relevant Type 3 dependencies at registration. Complete dependency mapping is structurally unattainable for an institution of this scale; newly-discovered dependencies will be reported as Mechanism Record updates within 30 days of discovery.

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

**7.1 Declared metrics:**

| Metric | Source | Role | Public? |
|---|---|---|---|
| Payment history (on-time/late by category) | Furnishers | Primary input to all scoring | Aggregate stats yes; individual no |
| Credit utilization (debt-to-limit ratio) | Furnishers | Primary scoring input | Aggregate yes |
| Length of credit history | Internal records | Scoring input | Aggregate yes |
| Credit mix (types of accounts) | Furnishers | Scoring input | Aggregate yes |
| New credit inquiries | Furnishers + authority | Scoring input | Aggregate yes |
| Public records (bankruptcies, judgments, liens) | Court filings | Reporting input | Yes (on individual records) |
| Collection accounts | Collections agencies | Reporting input | Yes (on individual records) |
| Identity verification status | Authority + verification vendors | Distinguishes verified from suspected synthetic identities | Aggregate yes |
| Fraud alerts | Subject + authorized contacts | Reporting input | Yes |

**7.2 Indirect signals:**

- *Algorithm features:* The primary scoring algorithm uses approximately 60 features. Most are direct inputs from the table above. Some are derived (e.g., trend over time, seasonality, ratios). The authority commits to publishing a plain-language description of all 60 features by Q2 of next reporting year. R79 gap acknowledged.
- *Internal classification tiers:* Internal tiers (e.g., "thin file," "fraud risk," "establishing credit") that influence how individual records are processed. Not currently fully disclosed; commitment to disclose by Q4 of next reporting year.
- *Algorithmic priorities for dispute investigation:* Dispute investigation prioritizes some types of disputes over others based on internal triage rules. Not currently public; commitment to disclose triage rules.
- *Pre-screened list filtering:* When pre-screened lists are created for marketing, internal filters determine who is offered specific products. Filters use a subset of credit data; the filtering logic is currently a trade secret. R79/R67 gap acknowledged; commitment to disclosure of filtering categories (not specific values) within next reporting year.

**7.3 Algorithmic decision systems:**

[x] Yes. Multiple algorithmic systems:

- *Primary FICO scoring algorithm:* Licensed from FICO Corporation. Used in approximately 80% of consumer credit decisions in the US. **Decisions influenced:** essentially every consumer credit decision. **Vendor:** FICO Corporation. **Auditability:** the authority does not own the algorithm and cannot fully expose its internals. Commitments: (a) advocating for FICO to publish algorithm methodology; (b) reporting fair-lending disparity testing results regardless of FICO's disclosure; (c) noting that this is a R67/R81 partial gap.
- *Proprietary supplementary scores:* Approximately 12 supplementary scoring systems for specific use cases (auto lending, mortgage, insurance, etc.). **Vendor:** in-house. **Auditability:** commitment to publishing methodology within next reporting year.
- *Fraud detection algorithms:* Mix of in-house and licensed. **Auditability:** internal model auditing; commitment to publishing aggregate effectiveness statistics.
- *Dispute prioritization algorithm:* (See §7.2)
- *Pre-screened list filtering:* (See §7.2)

**7.4 Outcome-versus-declaration check:** [x] Committed but with caveat. The authority commits to maintaining a process by which observed outcomes are periodically compared to declared metric set. Full compliance with R79 (Metric Completeness) is an ongoing project. Several disclosures referenced above (full feature list, filtering logic, triage rules) are committed for future quarters. R79 finding acknowledged at registration; full compliance committed within next reporting cycle.

---

## SECTION 8 — How is this authority watched?

**8.1 Drift monitoring mechanism:** Drift is monitored by:
- Internal compliance team (~280 FTE) — reports to Board of Directors, separate from operational executives
- Internal audit function — reports to Audit Committee of Board
- External annual audit (financial and regulatory)
- CFPB ongoing supervision
- FTC periodic review
- Fair-lending disparity testing (annually, by independent firm)
- Algorithm audit (every 2 years, by independent firm)
- 50 state regulator submissions

**8.2 Capture risk monitoring:**
- Quarterly review by Compliance team of: customer concentration, lobbying activity, revolving-door employment
- Annual disclosure to CFPB of major lobbying positions
- Ongoing tracking of: industry consortium positions, regulatory engagement, litigation patterns

**8.3 Audit interfaces:**
- *Proactively published:* Annual report (financial), quarterly transparency report, dispute resolution statistics, regulator submissions where law permits, citizen ledger (committed).
- *Available on request:* Individual record dispute investigations (to subject); fair-lending disparity test results (to regulators and litigants); specific algorithm methodologies (committed for future disclosure).
- *Restricted:* Trade secret algorithmic details (FICO Corporation's intellectual property is not the authority's to disclose); pending litigation strategy; specific business data.

**8.4 Adversarial exposure (R81):**
- An external party can evaluate: scope (declared); effect at population level (regulator data, audit results, litigation findings); harm thresholds (declared and measurable); dependencies (declared); reversibility (declared); stop capability (regulatory and judicial avenues).
- An external party *cannot* fully evaluate: individual algorithmic decisions (without subject's specific records); FICO Corporation's algorithm internals (the authority does not own); some pricing details.
- *Substantial gaps acknowledged:*
  - Trade secret restrictions limit some algorithm disclosure (R67 floor)
  - Individual records are private (necessarily)
  - Pre-screened list filtering details are partially restricted

Mitigations: (a) algorithm methodology disclosures committed in §7; (b) third-party algorithm audit within next reporting year; (c) ongoing transparency reporting per CFPB requirements.

**8.5 Known structural failure modes:**
- *Algorithmic disparate impact:* Documented historically; ongoing fair-lending litigation in multiple jurisdictions
- *Synthetic identity fraud:* Approximately 0.4% of records affected; mitigations in place
- *Regulatory complexity:* 50-state varying requirements create compliance gaps
- *Regulatory capture risk:* See §6.4
- *Industry coordination risk:* See §6.6
- *Trade secret tension:* Acknowledged in §8.4
- *Furnisher data quality:* The authority can only verify what furnishers report; misreported data creates record errors that are corrected through dispute, but baseline quality varies by furnisher
- *Catastrophic data breach:* Historical industry breaches have affected hundreds of millions; the industry has experienced breaches; risk is acknowledged but cannot be eliminated

---

## SECTION 9 — How does it end?

**9.1 Estimated dismantling time:** 24 months. Justification: scale (245M records, 3,400 furnishers, 28,000 customers, 12,000 employees, multi-state regulatory unwinding) requires extended timeline.

**9.2 Dismantling process:**
- *Months 1–3:* Cease accepting new furnisher data; notify users; begin transferring active disputes to successor or to direct individual records
- *Months 4–9:* Wind down customer relationships (typically 90-day notice); transition pending disputes to resolution; archive records per FCRA requirements
- *Months 10–18:* Transfer essential historical records to public archival institution or successor; settle outstanding contractual obligations; release personnel
- *Months 19–24:* Final compliance audit; multi-state regulatory wind-down; dissolution of corporate entity

**9.3 Entrenchment factors:**
- Records are used in essentially every consumer credit decision in the US. Sudden dismantling would create national credit-system disruption.
- Public companies cannot dismantle in less than 24 months without substantial business risk.
- Multi-state regulatory wind-down is complex.
- Approximately 12,000 employees would require severance.
- The successor question (does another agency take the data, or does it disappear) is itself a major structural decision affecting consumer access to credit.

**9.4 Data disposition:**
- *Personal data (consumer records):* Archived to public archival institution (e.g., National Archives, state archives, or successor consumer reporting agency) per FCRA requirements. Commitments: (a) ensuring public access to dispute history; (b) providing transition mechanism for consumers who need access to their own historical records.
- *Institutional records:* Archived per state corporate dissolution procedures.
- *Derived outputs:* Credit scores produced are not stored as derived outputs in R60's sense — they are computed on demand. Past scores referenced in user records (e.g., a bank's loan file) remain in the user's records.
- *Audit logs:* Archived publicly.

**9.5 Downstream effect reversibility:** This is the most concerning section.

The authority acknowledges that outputs propagate widely:
- 28,000 institutional users have used authority-derived data in millions of decisions affecting consumer access to credit, housing, employment, insurance, and benefits over decades
- These decisions are typically not reversible — a denied loan does not become approved upon dissolution
- Authority data becomes part of users' decision histories and is preserved in user records

The authority cannot reverse downstream effects. R60 (Derived Authority Inheritance) and R63 (Downstream Effect Reversibility) apply with full force.

Mitigation: on dissolution, the authority commits to: (a) issuing public notice that its data is no longer authoritative; (b) providing transition pathways for consumers to obtain and contest historical records; (c) supporting development of alternative consumer reporting infrastructure if needed.

Acknowledged tension between scale and the framework's reversibility requirement.

**9.6 Replacement feasibility:** Dissolution would require successor infrastructure for consumer credit reporting. Without this, the credit-decision ecosystem would be substantially disrupted. R51 (Institutional Replacement Feasibility) requires that this disruption be manageable. The authority does not currently have a documented succession plan for the consumer-reporting-agency function it provides. R51 gap acknowledged. Remediation: commitment to participating in industry-wide successor planning.

**9.7 Reversibility verification:** No formal dismantling rehearsal has been conducted. The §9.1 timeline is estimated based on regulatory and contractual requirements. R43 gap acknowledged. Remediation: commitment to a regulatory desktop dismantling exercise within 24 months, with results public.

---

## SECTION 10 — Authorization, renewal, and trigger declarations

**10.1 Authorizing body:** Operates under FCRA federal authorization and [STATE] corporate authorization.

**10.2 Date of current authorization:** Variable — corporate existence predates registration; FCRA compliance is ongoing. For framework purposes: [DATE] (registration date).

**10.3 Authorization expiration date:** [EXPIRATION DATE]

**10.4 Renewal interval:** 2 years. Justification: scale and the rapid evolution of operations (algorithm updates, regulatory changes, data sources) warrant shorter renewal cycles than the framework's recommended 5-year guidance.

**10.5 Renewal evidence declaration:** [x] All five domains committed.

**10.6 Necessity-decay acknowledgment:** [x] Acknowledged. *Note:* As a regulated industry actor, claims of "decreasing necessity" depend on the broader regulatory framework. If FCRA and state credit-reporting law continue to mandate consumer reporting agencies, necessity is dependent on that mandate, not on the authority's own choice. R62 acknowledged with this contextual note.

**10.7 Aggregate trigger threshold:** 250 triggers in 90 days. SCBP-09 §II places authorities affecting >100M people in the "100 to 1,000 in 90 days" range. The authority elects 250 — below the midpoint.

**10.8 Aggregate threshold justification:** As above.

**10.9 Response time window:** 30 days (default).

**10.10 Response window justification:** Not required (default).

---

## SECTION 11 — What does this authority commit to publishing?

**11.1 Citizen ledger publication:** Quarterly. Includes operating metrics, lobbying activity, regulator submissions, dispute resolution statistics, threshold-proximity status, capture risk monitoring results.

**11.2 Threshold change log:** Within 7 days of any change.

**11.3 Interpretation change log:** Continuous.

**11.4 Renewal process visibility:** [x] Committed. Renewal review will be conducted by parties drawn from affected-party categories (consumers, civil rights organizations, financial regulators serving in personal capacity, academic researchers, affected-population advocacy organizations) — *not* by the authority, FICO, the trade association, or any party with material business relationship.

**11.5 Stop event log:** [x] Acknowledged.

---

## SECTION 12 — Honesty assertions

**12.1 Disclosure completeness assertion:** [x] Asserted, with acknowledgment that several disclosures (algorithm methodology, filtering logic, triage rules) are committed for future quarters and are partial at registration.

**12.2 Update obligation:** [x] Committed.

**12.3 Discoverability acknowledgment:** [x] Acknowledged.

**12.4 Burden of proof acknowledgment:** [x] Acknowledged.

**12.5 Anti-weaponization acknowledgment:** [x] Acknowledged.

---

## SECTION 13 — Submitter

*[Submitter information retained by registry as metadata.]*

---

*REG-CONSUMER-CREDIT-REPORTING-EXAMPLE — worked example of a national consumer credit reporting agency*
*Registered under the Bounded Power Framework*
*All authority governed by the Structural Constitution (SCBP-04)*
