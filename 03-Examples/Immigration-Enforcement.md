---
mechanism_id: SCBP-REG-EXAMPLE-IMMIGRATION-ENFORCEMENT
mechanism_name: "IMMIGRATION-ENFORCEMENT-EXAMPLE"
status: EXAMPLE
domain: government
authority_classification: direct
registered_date: [DATE]
authorization_date: [AUTHORIZATION DATE]
expiration_date: [EXPIRATION DATE]
renewal_interval_years: 2
funding_types:
  - federal_government_mandatory
funding_concentration_max_pct: 100
affected_party_categories:
  - general_public
  - residents_of_geographic_area
  - non_consenting_third_parties
  - vulnerable_populations
  - children
  - criminal_justice_involved_individuals
  - future_generations
affected_population_estimate: 47000000
non_consenting_population_estimate: 47000000
entity_size: institutional
geographic_specificity: single_nation
geographic_reach: "United States — interior enforcement; some operations within 100-mile border zone"
aggregate_threshold_count: 100
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

# Mechanism Record — REG-IMMIGRATION-ENFORCEMENT-EXAMPLE

**IMMIGRATION-ENFORCEMENT-EXAMPLE**

| Field | Value |
|---|---|
| Mechanism ID | REG-IMMIGRATION-ENFORCEMENT-EXAMPLE |
| Status | EXAMPLE |
| Registered | [DATE] |
| Authorization expires | [EXPIRATION DATE] |
| Domain | Government |

---

## SECTION 1 — What is this authority?

**1.1 Mechanism name:** IMMIGRATION-ENFORCEMENT-EXAMPLE — the federal interior immigration enforcement and removal authority.

**1.2 Functional description:** A federal civil enforcement authority that conducts interior immigration enforcement throughout the United States. The authority's core operational divisions are Enforcement and Removal Operations (ERO) and Homeland Security Investigations (HSI). This registration covers primarily ERO functions; HSI's criminal-investigation functions overlap with FBI/DEA/ATF authorities and are partially scoped here. Functional authority:

- Identifies, arrests, detains, and removes non-citizens determined to be removable under federal immigration law (Immigration and Nationality Act, 8 U.S.C.)
- Conducts arrests in homes (with administrative warrants — not Fourth Amendment judicial warrants — except where consent or probable cause for entry exists), workplaces, courthouses, hospitals, schools (subject to "sensitive locations" policy that varies by administration), public spaces, and during traffic stops conducted in coordination with state and local police
- Operates a nationwide system of approximately 200 detention facilities (primarily contracted to private prison corporations and county jails), with a typical daily population of approximately 30,000–50,000 detainees, including children in family detention where authorized
- Detains non-citizens for civil immigration proceedings — civil detention is not punitive in legal theory but is functionally indistinguishable from criminal incarceration, may extend for months or years, and provides no right to appointed counsel
- Issues detainer requests to state and local law enforcement for non-citizens in their custody
- Removes non-citizens under final orders of removal — removal is functionally permanent banishment from the United States, often for life, and severs family, employment, property, and community ties built over years or decades
- Conducts administrative proceedings before immigration judges (employees of the Department of Justice's Executive Office for Immigration Review, not Article III judges) — proceedings include bond hearings, removal hearings, and hearings on relief from removal
- Maintains databases including arrest records, biometric records (fingerprint, photo, DNA in some contexts), removal records, and intelligence files; shares these with state and local law enforcement, federal agencies, and in some contexts foreign governments
- Receives information from and operationalizes data from: federal benefit-administration systems (SSA, IRS), state DMV records (where state law permits), school enrollment systems (where accessed), license-plate-recognition vendors, commercial data brokers, social media monitoring, and 287(g) program local law enforcement partners
- Coordinates with foreign governments on identity verification, travel documentation, and removal logistics

The authority's functional reality includes several features that distinguish it from most other authorities in this framework:

- **Civil detention without Sixth Amendment protections.** Detained non-citizens have no right to appointed counsel; the burden of proof to remain in the United States rests on the non-citizen; many proceedings occur without representation; many detainees remain detained because they cannot afford bond.
- **Removal as permanent banishment.** A removal order is functionally permanent for most categories. Re-entry without authorization is a criminal offense. For long-term residents removed after decades in the United States, removal severs all U.S. connections — children, spouses, employment, community, often country of birth they have not seen since infancy.
- **Family separation.** Enforcement actions against parents result in U.S.-citizen children losing parental presence. Family detention as historical practice has held children with parents in carceral conditions. Foster placement of children whose parents are removed is a documented and recurring outcome.
- **Population-scale chilling effect.** The presence of enforcement authority materially shapes whether non-citizens, mixed-status families, and U.S.-citizen members of immigrant communities access medical care, report crimes, send children to school, attend court, drive to work, or engage with public institutions.

The authority acknowledges that these features are the structural reality of its operations, not aberrations to be denied or minimized. The framework treats them as such.

**1.3 Authority classification:** Direct. Binding determinations affecting liberty (detention), bodily integrity (use of force in arrests and detention), residence (removal), family integrity, employment authorization, and access to nearly every aspect of life in the United States for affected persons.

**1.4 Domain:** Government (primary).

**1.5 Statutory or constitutional basis:** Operates under: the Immigration and Nationality Act (8 U.S.C., as amended); the Homeland Security Act of 2002 (which created DHS and transferred immigration enforcement from the former INS); the Antiterrorism and Effective Death Penalty Act of 1996; the Illegal Immigration Reform and Immigrant Responsibility Act of 1996; subsequent statutes; presidential executive orders directing enforcement priorities; DHS and ICE policy memoranda. Subject to: limited Fourth Amendment protections in civil immigration enforcement (administrative warrants suffice for many actions, with constitutional limits on home entry and use of force); Fifth Amendment due process (which applies to all persons in U.S. territory, citizen or not, but with substantially limited content in immigration proceedings per Supreme Court doctrine); statutory protections for specific populations (asylum seekers, victims of trafficking and crime, unaccompanied minors, persons with credible fear of persecution); 8 U.S.C. §1357 governing arrest and detention authority; ongoing class-action and individual litigation.

The framework's R28 (Expiration Default) requires that all authority expire absent affirmative renewal. The authority acknowledges that current federal law does not provide a renewal mechanism in the framework's sense; the authority operates under permanent statutory authorization subject to congressional appropriations cycles. The authority's registration commits to a 2-year framework renewal cycle as a structural commitment beyond statutory requirement.

---

## SECTION 2 — Who can this authority act upon?

**2.1 Affected party categories:**
- [x] General public (anyone present in the United States may be subject to investigatory contact, including U.S. citizens who are erroneously contacted)
- [x] Residents of geographic area (the entire U.S. interior)
- [x] Non-consenting third parties (essentially the entire affected population is non-consenting)
- [x] Vulnerable populations: asylum seekers; victims of trafficking, domestic violence, and crime; unaccompanied children; persons with credible fear of persecution; persons with mental illness; persons with serious medical conditions; pregnant persons; LGBTQ+ persons in detention; persons fleeing political violence
- [x] Children: U.S.-citizen children of non-citizen parents (~5.5 million estimated); non-citizen children including unaccompanied minors and children in family units; children separated from parents by enforcement action
- [x] Criminal justice involved individuals: non-citizens with criminal records (whose enforcement priority varies by administration); non-citizens in pretrial detention encountered through ICE detainer requests; non-citizens transferred from criminal to immigration custody at end of criminal sentence
- [x] Future generations: removed parents' descendants who lose intergenerational connection to U.S. residence; mixed-status families' children whose life prospects are shaped by enforcement risk

**2.2 Approximate number of people directly affected:**
- Undocumented residents: approximately 11 million
- Lawful permanent residents (green card holders): approximately 13 million, who remain subject to potential removal under specific circumstances (criminal convictions, fraud findings)
- Naturalized citizens: approximately 23 million, subject to denaturalization in narrow circumstances and to enforcement contact errors
- U.S.-citizen children of non-citizen parents: approximately 5.5 million
- U.S.-citizen spouses of non-citizens in proceedings: substantial population not separately enumerated
- Annual enforcement contacts: hundreds of thousands of arrests, ~140,000 detentions, ~100,000–400,000 removals (varies dramatically by administration)

Total population materially affected by the authority's existence and operations: approximately 47 million, the rough sum of immigrant-status populations and their immediate U.S.-citizen family members. This count understates the chilling-effect population — anyone perceived as foreign-born by an enforcement officer is potentially affected.

**2.3 Non-consenting population:** Essentially the entire affected population.

R14 (Non-Participant Exposure Mapping) and R26 (Non-Participant Harm Floor) apply with full force. The framework treats non-citizens as full subjects of constitutional analysis where present in U.S. territory; their non-citizen status does not reduce the framework's protection of them as non-consenting subjects of authority.

**2.4 Vulnerable population specifics:**

- [x] Children — *yes, with substantial complexity*. Children encounter the authority as: targets of enforcement (in family unit detention); secondary subjects of enforcement (when parents are arrested or removed); subjects of separation and foster placement; unaccompanied minors apprehended at or after entry. The authority commits to "sensitive locations" protections (limiting enforcement at schools, daycare facilities, churches) per current policy memorandum, but acknowledges that this policy varies by administration. The authority commits to: notification of caregivers when a parent is detained; coordination with child welfare authorities for U.S.-citizen children whose parents are detained; restrictions on questioning of unaccompanied minors. R26 substantial gap acknowledged: policy and aggregate practice are not equivalent; family separation as practice has occurred under multiple administrations; separation effects on children are documented in long-term medical and developmental literature and cannot be reversed by subsequent reunification.
- [x] Patients during medical care — *yes*. Detained persons receive medical care through detention-facility contractors. Documented inadequacies in detention medical care are extensive, including deaths in custody from preventable conditions. The authority commits to medical-care standards in detention but acknowledges that aggregate compliance has been challenged by GAO, Inspector General, and external monitors. R26 substantial gap.
- [x] Detained or confined persons — *yes*. Approximately 30,000–50,000 persons in daily detention. The authority commits to: minimum standards for detention conditions (Performance-Based National Detention Standards or successor); detainee access to legal materials; access to phone communication; medical care; restrictions on use of force and isolation. R26 substantial gap acknowledged across all of the above; documented violations have produced consent decrees, settlement agreements, and ongoing class-action litigation. Deaths in custody trigger external investigation; aggregate death statistics published.
- [x] Persons in coercive economic relationships — *yes*. Workplace enforcement and the threat of workplace enforcement create coercive economic relationships between non-citizen workers and employers; enforcement consequences may discourage reporting of wage theft, workplace injury, and harassment. The authority's interaction with worksite enforcement materially shapes these dynamics.
- [x] Persons unable to advocate for themselves — *yes*. Detained persons have no right to appointed counsel; persons with mental illness, persons with limited English proficiency, persons with cognitive or developmental disabilities, persons unable to read or write face substantial advocacy disadvantage in proceedings. The authority commits to interpreter access and to mental-health-competency screening in detention; substantial R26 gaps acknowledged across all categories.

The authority acknowledges that R26's stricter harm tolerance for non-participants applies with particular weight to its operations because essentially all affected persons are non-consenting and a substantial portion are vulnerable across multiple categories simultaneously.

---

## SECTION 3 — What can it do, and what can it not do?

**3.1 Geographic reach:** The entire United States and its territories. Some operations within the 100-mile border zone (where reduced Fourth Amendment standards have been applied per Supreme Court doctrine) are functionally distinct in operational practice. International operations occur in coordination with foreign governments and U.S. embassies; this registration covers domestic operations.

**3.2 Coercive ceiling:**
- *Stop, detain, question:* Brief investigative stop on reasonable suspicion of removability; arrest on administrative warrant or on warrantless basis where statutory authority exists (8 U.S.C. §1357 grants warrantless arrest authority broader than typical Fourth Amendment standards in domestic criminal enforcement)
- *Search:* Per Fourth Amendment doctrine as applied to civil immigration enforcement, with administrative-warrant standards substantially lower than judicial-warrant standards
- *Use of force:* Per ICE use-of-force policy. Force continuum includes presence, verbal commands, physical control, chemical irritants, conducted electrical weapons, impact weapons, and lethal force. Lethal force authorized in defense of self or others against imminent threat
- *Detain civilly:* Indefinite civil detention pending immigration proceedings, subject to bond hearings and statutory limits (some categories mandatory detention, some discretionary). Detention may extend months to years; long-term detention up to and beyond 6 months has been challenged but continues in practice
- *Remove (deport):* Final orders of removal executed by physical removal from the United States. Removal is functionally permanent banishment for most categories; bars on re-entry vary from years to lifetime
- *Issue detainers:* To state and local law enforcement holding non-citizens
- *Operate detention facilities:* Through DHS-contracted private prison corporations, county jails, family detention centers, and ICE-operated facilities
- *Surveil:* Per Fourth Amendment doctrine; commercial data, social media, and license-plate-recognition data acquisition under legal frameworks more permissive than typical criminal-enforcement requirements
- *Maintain databases:* Per Privacy Act exceptions and statutory authorities; share with federal, state, local, and in some contexts foreign authorities
- *Share information internationally:* Including with countries from which removed persons originated, raising risks for asylum seekers and persons removable to countries of persecution

The authority may NOT (per constitutional and statutory law):
- Detain or remove U.S. citizens (errors occur and are documented; each is a finding)
- Operate without legal basis under the INA and implementing regulations
- Detain beyond statutory limits without bond hearing (subject to ongoing litigation about indefinite detention)
- Use force exceeding policy or statutory authorization
- Conduct enforcement in violation of applicable consent decrees
- Discriminate on race, ethnicity, or national origin in operational decisions (enforcement targeting based on these characteristics is constitutionally and statutorily prohibited; aggregate disparate-impact patterns have been litigated)
- Retaliate against persons exercising First Amendment rights or filing complaints
- Conduct enforcement at locations specified in the current sensitive-locations policy except per documented exception (subject to administration changes in policy)

**3.3 Resource ceiling:**
- Operating budget: approximately $9–10 billion annually (varies by appropriation cycle)
- ERO personnel: approximately 8,000 enforcement officers; HSI personnel: approximately 7,000 special agents
- Detention capacity: approximately 30,000–50,000 daily beds, primarily contracted
- Vehicle, technology, and operational resources: substantial federal procurement
- Federal data systems: ICE-operated databases plus access to federal, state, and commercial data sources

**3.4 Explicit exclusions:**

- **Geographic:** Domestic operations bounded by the United States and territories; international operations coordinated with foreign authorities.
- **Action:** May not detain or remove U.S. citizens; may not detain without statutory basis; may not use force exceeding policy; may not enforce in violation of consent decrees; may not detain unaccompanied minors beyond statutory and Flores-settlement timelines without judicial review.
- **Data:** Subject to Privacy Act and statutory limits; subject to consent decree limits where applicable.
- **Procedural:** Detainers may not be issued without statutory basis; bond hearings must be conducted within statutory windows; removal orders may not be executed before exhaustion of judicial review where pending; persons with pending asylum claims may not be removed during pendency.
- **Other:** Sensitive locations protections per current policy memorandum (subject to administration changes); restrictions on enforcement at courthouses per evolving policy; restrictions on enforcement during pandemic per emergency policy where applicable.

The authority acknowledges that several of these exclusions are policy-based rather than statute-based, and that policy can be changed by an incoming administration. The framework's R76 (Mandatory Degradation Requirement) requires that authority reduce scope, dependency, opacity, and intensity over time; policy-based protections that expand and contract with administration changes are not, in the framework's sense, structural reductions.

**3.5 Indirect influence boundaries:** Substantial. The authority's reach extends well beyond direct enforcement contacts.

- *Chilling effect on essential life activities:* The presence of enforcement authority shapes whether non-citizens, mixed-status families, and immigrant communities access medical care, send children to school, report crimes, attend court, drive to work, or engage with public institutions. Documented in substantial public health, criminology, education, and social-science literature
- *Family court and child welfare:* Enforcement actions against parents shape custody, foster placement, and child welfare proceedings; many U.S.-citizen children enter foster care because their parents have been detained or removed
- *Workplace enforcement and labor markets:* Worksite enforcement and the threat of it shape labor market conditions for non-citizen workers, including suppression of wage and harassment complaints
- *Healthcare access:* Hospitals, clinics, and public health programs experience reduced uptake by populations affected by enforcement risk; public health consequences extend to U.S.-citizen family members
- *School attendance:* School enrollment and attendance affected by enforcement context; documented declines in school participation following local enforcement events
- *Information sharing:* Data shared with state and local law enforcement, federal agencies, and foreign governments propagates beyond the authority's direct control
- *Detainer compliance:* Local jurisdictions vary in whether they honor detainers; the authority's reach varies accordingly with state and local cooperation
- *Shared databases:* Persons identified through fingerprint data shared via Secure Communities, the Joint Terrorism Task Force, or fusion centers may be subject to enforcement triggered by encounters they did not anticipate as enforcement-relevant

R58 applies to these effects. The authority's outputs (records of contact, arrest records, removal orders, biometric records) materially shape downstream decisions made by state and local law enforcement, foreign governments, future immigration adjudication, and commercial actors (employers, landlords, lenders) in ways that persist for the affected person's lifetime.

**3.6 Anti-proxy declaration:**

The authority commits to not using the following proxies:

- *Proxy for race, ethnicity, national origin, language:* Enforcement targeting may not be based on race, ethnicity, perceived national origin, language, or accent. Acknowledged that operational practice in many contexts has used location, occupation, language, and appearance as enforcement signals that correlate with national origin. R66/R74 finding acknowledged at registration; aggregate disparate-impact testing of stops, arrests, detention-bond decisions, and removal outcomes is committed; results published.
- *Proxy for political activity:* Enforcement and surveillance may not be used against persons for protected First Amendment activity, including immigration-related advocacy. Documented historical patterns of enforcement targeting of immigrant rights organizers raise R66 concerns; the authority commits that enforcement triggered within 90 days of a person's identifiable advocacy activity is reviewed.
- *Proxy for religion:* Enforcement may not be predicated on religion or perceived religion. Programs that have differentially affected persons of particular religions (e.g., country-of-origin-based registries or restrictions) raise R66 concerns; the authority acknowledges that R66 applies regardless of facially neutral framing.
- *Proxy for poverty as removability:* Detention-bond determinations and prosecutorial discretion may not effectively use ability-to-pay as a proxy. Acknowledged that current bond practice substantially correlates with ability to pay; this is a structural R66 finding.
- *Proxy for criminal history beyond statutory authorization:* Enforcement priorities established by policy may not effectively expand statutory removability through proxy. Acknowledged that policy expansions and contractions of "criminal alien" definition have functioned to shift the effective scope of removability without statutory change; R06 (Semantic Expansion Prohibition) applies.

The authority acknowledges that all five proxy commitments require ongoing structural attention and that historical practice in this authority and its predecessor has produced repeated R66 findings.

---

## SECTION 4 — What harms can it cause?

**4.1 Bodily harm threshold:** Load-bearing.

- *Use of force in arrest:* Any use of force resulting in serious bodily injury triggers individual review; aggregate use-of-force rate exceeding peer benchmarks triggers systemic review
- *Use of force in detention:* Any use of force in detention resulting in serious bodily injury triggers external investigation; aggregate facility-level rates monitored
- *Death in custody:* Any death of a person in detention triggers immediate external investigation with public summary; aggregate death statistics published quarterly
- *Death of person being removed in transit:* Any in-transit death triggers immediate external investigation
- *Sexual assault and abuse in detention:* Documented as recurring failure mode; aggregate incident reporting and PREA (Prison Rape Elimination Act) compliance reporting committed; any substantiated incident triggers external review
- *Medical neglect in detention:* Aggregate medical-care metrics (response time, specialist access, medication adherence, mortality) monitored against detention-standards benchmarks; failures trigger review
- *Use of solitary or restrictive housing:* Aggregate rates published; use beyond policy limits triggers review; mental-health detainees in solitary triggers individual review
- *Self-harm and suicide in detention:* Aggregate rates published; detention conditions correlated with self-harm trigger systemic review
- *Force during family separation operations:* Use of force during operations affecting children triggers immediate review

**4.2 Agency impairment threshold:** Multiple.

- *Right-to-counsel barriers:* Detention-facility location, transfer practices, and access-to-counsel infrastructure materially affect access to representation. Detention facility selection that places detainees more than 100 miles from immigration courts or pro bono legal services triggers review
- *Language access failures:* Failure to provide interpreter in proceedings or detention-facility communication — finding for each instance; aggregate language-access failures trigger systemic review
- *Procedural failures in proceedings:* Aggregate denial of asylum claims, denial of bond, or denial of relief at rates substantially exceeding benchmarks for represented populations — review
- *Detention transfers disrupting legal access:* Transfer of detained persons to facilities far from counsel and family without notice — finding
- *Errors in detainer issuance and U.S.-citizen detention:* Each instance of detention or arrest of a U.S. citizen is a finding; aggregate trends trigger systemic review
- *Failure to provide notice in language understood:* Finding for each instance

**4.3 Ecological damage threshold:** Limited applicability. Detention facility environmental compliance per applicable law.

**4.4 Generational binding threshold:** Substantial. Load-bearing.

The authority's actions produce intergenerational effects that no subsequent policy change can reverse:
- Removal of parents creates lifelong effects on U.S.-citizen children including educational disruption, foster placement, mental health consequences, and economic instability
- Family separation, where it has occurred as policy or in practice, produces documented developmental and medical harm to children that persists into adulthood
- Removal severs U.S.-citizen children's relationships with parents in ways that subsequent reunification cannot fully restore
- Records of contact, arrest, and removal propagate to permanent federal databases and to foreign governments; affected persons cannot escape these records
- Children of removed parents inherit immigration status complications that affect their own life prospects

R63 (Downstream Effect Reversibility) and R60 (Derived Authority Inheritance) apply with particular force. The authority's downstream effects are among the least reversible of any authority in this framework. The threshold here is honest acknowledgment, not numeric.

Specific operational thresholds:
- Any family separation event without judicial finding of unfitness triggers immediate review
- Any removal of a parent of a U.S.-citizen child without consideration of family unity factors triggers individual review
- Aggregate U.S.-citizen-children-affected statistics published quarterly; trends reviewed

**4.5 Communicative suppression threshold:**
- Surveillance, data collection, or enforcement against persons for protected First Amendment activity, including immigration-related advocacy — finding
- Restriction of detainees' communication with family, counsel, or media — finding
- Retaliation against complainants, witnesses, or whistleblowers (including detainees and contractors) — finding
- Enforcement targeting at or near protests, courthouses, sensitive locations beyond exception — finding
- Suppression of detainee communication or correspondence — finding

**4.6 Informational sovereignty threshold:**
- Records retained beyond Privacy Act and applicable retention requirements — finding
- Sharing of information with foreign governments in ways that endanger asylum seekers or persons fleeing persecution — finding for each instance
- Sharing of information with state and local actors beyond legal authority — finding
- Surveillance of social media, location data, or communications absent warrant where required — finding
- Errors in databases that propagate to other systems and that affected persons cannot correct — finding for each substantiated instance; aggregate error rates published

**4.7 Additional harm thresholds:**

*Chronic asymmetry threshold:* If detention, removal, or enforcement-contact rates correlate with race, ethnicity, or national origin at p<0.05 over rolling periods, beyond what underlying immigration-status distribution accounts for, this triggers systemic review.

*Chilling-effect threshold:* If documented declines in healthcare access, school attendance, crime reporting, or court attendance correlate with enforcement intensity in particular jurisdictions, this triggers review of enforcement practice in those jurisdictions.

*Family-separation threshold:* Any operational practice resulting in separation of children from parents without judicial finding of parental unfitness — finding for each instance; aggregate practice triggers immediate systemic review.

*Wrongful-removal threshold:* Any removal of a U.S. citizen, lawful permanent resident with valid status, asylum seeker with valid claim, or person with pending judicial review — finding for each instance.

*Detention-conditions threshold:* Aggregate detention conditions failing to meet detention standards (medical, sanitation, safety, due process) — review of facility-by-facility compliance committed; failures trigger contract review or termination.

*Consent-decree compliance threshold:* Failure to comply with applicable consent decrees (Flores Settlement, settlement agreements from class actions) — finding.

**4.8 Threshold change-log commitment:** [x] Yes — committed.

---

## SECTION 5 — What stops it?

This section is structurally difficult. The authority is a federal enforcement agency with substantial political support across both parties for its core function and substantial political opposition to many of its practices. Stop paths must be evaluated honestly against the structural conditions that have historically shaped them.

**STOP PATH 1 — Federal court action**
- *Activator:* Any person with standing under the INA, the Constitution, the Administrative Procedure Act, or 28 U.S.C. §1651 (habeas corpus); class actions; the Department of Justice (in narrow circumstances).
- *Trigger:* Court determination of constitutional or statutory violation; consent decrees; injunctions; class action findings.
- *What "stopped" means:* Court orders may halt specific practices, void specific actions, impose damages, require release of detainees, impose monitors, or in extreme cases require systemic operational changes. Habeas review may secure release of individuals.
- *Independence:* Federal courts are structurally independent. *Acknowledged limitation:* Substantial Supreme Court doctrine has limited the scope of judicial review in immigration matters; many immigration decisions are committed to executive discretion with limited judicial review; Article III courts have jurisdictional limits over immigration proceedings.
- *Timeline:* Habeas may be expedited; class actions and consent-decree litigation typically span years.

**STOP PATH 2 — Congressional oversight, appropriations, and legislative change**
- *Activator:* Congress (committees, full chambers, individual members through inquiry, hearings, and legislation).
- *Trigger:* Congressional finding of misconduct, inefficiency, or policy failure; appropriations restrictions; legislative change to underlying statute.
- *What "stopped" means:* Appropriations limits may restrict enforcement intensity, detention capacity, or specific programs; legislative change may modify or remove authority; oversight hearings may force policy change.
- *Independence:* Congress is structurally independent of the executive enforcement agency. *Acknowledged limitation:* Congressional oversight depends on majority support; immigration enforcement enjoys substantial congressional support that has typically prevented major restrictions even amid documented misconduct; appropriations cycles produce continuing-resolution patterns that lock in funding.
- *Timeline:* Congressional response cycles typically span years.

**STOP PATH 3 — Executive policy, DHS Inspector General, and internal accountability mechanisms**
- *Activator:* The President (through executive order and policy direction); the DHS Secretary; the DHS Inspector General; the ICE Office of Professional Responsibility; the Office for Civil Rights and Civil Liberties.
- *Trigger:* Policy determination; misconduct finding; civil rights complaint substantiation.
- *What "stopped" means:* Policy changes may modify or restrict enforcement; OIG investigations may produce findings and recommendations; internal accountability may produce discipline of individual officers.
- *Independence:* OIG and CRCL have statutory independence within DHS but are not structurally independent of the executive branch. The President's policy authority is comprehensive but subject to electoral cycles. *Acknowledged limitation:* Policy-based stops are reversible by subsequent administrations; internal accountability has produced limited individual discipline relative to documented misconduct.
- *Timeline:* Policy changes immediate; OIG investigations typically span months to years.

**5.4 Penalty for activating stop:** [x] Confirmed in policy. *Acknowledged structural concerns:* Detained persons who file complaints, organize hunger strikes, or engage in advocacy have faced retaliation through transfer, segregation, accelerated removal, and other adverse actions. Whistleblowers within the agency have faced retaliation. The authority's stated commitment is non-retaliation; the documented gap between commitment and practice is itself a recurring R26 and R33 finding. The authority commits to investigation of any retaliation complaint and to public reporting of substantiated findings.

**5.5 Stop-path independence verification:** Federal courts and Congress are structurally independent of the agency. Internal stops (OIG, CRCL, OPR, executive policy) are partially independent within the executive branch but not from it.

*Acknowledged R03 (Institutional Capture) finding:* The detention industry — primarily two large private prison corporations holding the majority of detention contracts — has substantial congressional lobbying presence and structural alignment with detention-bed funding levels. Reduction in detention would directly affect the contractors that house most detainees; this creates bidirectional capture risk.

*Acknowledged R55/R59 finding:* Coordination among ICE, CBP, USCIS, the Executive Office for Immigration Review, federal courts, state and local 287(g) partners, and the contracted detention system functions operationally as a single immigration-enforcement system. Containment review of any single component is incomplete without addressing the system.

**5.6 Civic trigger acknowledgment:** [x] Acknowledged.

---

## SECTION 6 — What does it depend on?

**6.1 Type 1 dependencies:**

The authority operates with approximately 38 Type 1 dependencies, including:
- Private prison corporations operating contracted detention facilities (primarily 2 dominant providers; the largest accounts for substantial detention-bed share). Compensation: per-bed daily rate; multi-year contracts. *R03/IX-A finding:* per-bed compensation creates structural alignment between contractor revenue and detention-bed levels — the contractor is structurally incentivized toward higher detention, which is itself a capture risk
- County jails contracted for detention (~hundreds of facilities; varies by year)
- Contracted medical providers in detention facilities (per-detainee or per-encounter fee)
- Contracted transportation providers (charter aircraft, ground transport for removals)
- Translation and interpretation contractors
- Records and case-management technology vendors
- Biometric and identity-verification vendors
- Commercial data brokers (LexisNexis Risk Solutions, Thomson Reuters, others — providing person-locator and financial data)
- License-plate-recognition vendors (commercial LPR network access)
- Social media monitoring contractors
- Foreign-government coordination contractors and arrangements

**Funding-source disclosure:** Funded essentially entirely through federal appropriation; concentration approaches 100%. R03/§6.4 funding-concentration finding noted; this is structural to federal agencies and cannot be remediated through diversification.

**6.2 Type 2 dependencies:**
- Department of Justice / Executive Office for Immigration Review (immigration courts)
- Customs and Border Protection (sister agency)
- USCIS (sister agency, civil benefit-determination authority)
- FBI, DEA, ATF (criminal-enforcement coordination)
- Federal courts (judicial review, habeas, civil rights litigation)
- State and local law enforcement (287(g) partners and detainer-honoring jurisdictions)
- Foreign governments (identity verification, removal logistics)
- Congress (appropriations, oversight)
- DHS Office of Inspector General; DHS Office for Civil Rights and Civil Liberties

**6.3 Type 3 dependencies:**
- *Detention contractor capacity:* If detention contractors withdrew, the authority's enforcement capacity would be substantially constrained. The dependency is bidirectional and creates capture risk
- *Federal data systems:* IDENT, ENFORCE, federal fingerprint databases — if access lost, the authority cannot conduct routine identification
- *Commercial data broker contracts:* If terminated, person-locator capacity would be reduced
- *State and local cooperation:* If sanctuary policies expand, the authority's reach contracts
- *Foreign government cooperation:* If foreign governments decline travel documentation or accept-back, removals are impossible regardless of removal order
- *Congressional appropriations:* If detention funding restricted, operations contract
- *Federal courts:* Judicial review compromised would compromise stop path 1
- *ICE personnel union:* The collective bargaining context shapes discipline and accountability provisions
- *DHS Inspector General independence:* If OIG capacity reduced, internal accountability compromised

**6.4 Capture risk identification:** [x] Yes. Substantial.

- *Detention-industry capture:* Two private prison corporations hold substantial detention contracts and engage in congressional lobbying for detention-bed levels. R03 finding acknowledged; contracts are reviewed periodically but the structural capture is not eliminable through individual contract review
- *287(g) and state-local capture:* State and local law enforcement participation in 287(g) creates federal-local coordination that may not be reachable through any single-jurisdiction stop path
- *Funding concentration:* 100% federal; structural to a federal agency
- *Industry-employee revolving door:* Movement between agency, contractor, congressional staff, and political offices creates relational dependencies
- *Vendor lock-in:* Records, biometric, and case-management vendors create switching costs
- *Bond bond-industry alignment:* Where private bond industry interacts with detention, financial-incentive alignment may emerge

**6.5 Reversibility-affecting dependencies:**
- Records propagated to permanent federal databases and to foreign governments cannot be recalled
- Removed persons cannot be straightforwardly returned (re-entry is itself a federal offense; many returned persons cannot obtain visas)
- Detention contracts have multi-year terms with cancellation costs
- Federal data-sharing relationships extend beyond agency control
- Congressionally-mandated detention-bed minimums (where they have existed in appropriations) lock in operational capacity
- Pension and personnel obligations to federal employees

**6.6 Coordination disclosures:**

The authority coordinates with:
- CBP, USCIS, EOIR (DHS and DOJ family of immigration agencies)
- FBI, DEA, ATF (criminal enforcement)
- State and local 287(g) partners; fusion centers; Joint Terrorism Task Forces
- Foreign governments
- Detention contractors operating as integrated operational extensions

**Acknowledged R55/R59 finding:** The federal immigration-enforcement system functions as a single coordinated authority across ICE, CBP, USCIS, EOIR, federal courts, state and local partners, and contracted detention operators. Containment review of any single component is incomplete. The framework's R55 (Fragmentation Must Not Defeat Containment) requires evaluation of the coordinated system.

**6.7 Disclosure completeness assertion:** [x] Asserted with the standard acknowledgment that complete dependency mapping for an institution of this scale is structurally unattainable; commercial data broker relationships in particular are extensive and partially restricted from public disclosure.

**6.8 External authority operationalization:**

- *Foreign-government identity verification:* Foreign-government determinations of nationality and travel-document validity are operationalized within agency authority. R72 applies. Affected persons typically cannot distinguish agency decisions from foreign-government determinations
- *Commercial data broker scoring:* Risk scores, person-locator confidence levels, and other commercial outputs are operationalized within agency targeting decisions. R72 applies; the commercial scoring is typically not accessible to affected persons or their counsel
- *Algorithmic risk-assessment tools:* Tools used in detention-bond, parole, and removal-priority decisions operationalize external scoring. R72 applies; methodology is partially restricted
- *State and local law enforcement determinations:* 287(g) deputization makes state and local officers' identification decisions operationally agency authority. R72 applies
- *Detention-contractor disciplinary and conditions decisions:* Detention contractors make daily decisions about housing, segregation, medical care, and discipline; these become agency authority for affected detainees. R64 (External Circumvention Prohibition) and R72 apply

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

**7.1 Declared metrics:**

| Metric | Source | Role | Public? |
|---|---|---|---|
| Arrests | ICE records | Enforcement output; performance | Aggregate yes |
| Detentions (admissions, daily population) | ICE records, contractor reports | Capacity utilization | Aggregate yes |
| Removals | ICE records | Enforcement output | Aggregate yes |
| Detainer issuances and honored | ICE records, jurisdiction reports | Local cooperation | Aggregate yes |
| Bond determinations | EOIR records | Detention duration | Aggregate yes |
| Use-of-force incidents | ICE records | Discipline; pattern detection | Aggregate yes; individual restricted |
| Detainer accuracy (citizen errors, etc.) | ICE records, litigation | Error tracking | Aggregate partial |
| Detention conditions metrics (medical, deaths, force) | Contractor reports, OIG, audits | Compliance | Aggregate yes |
| Family-separation events | ICE records | Practice monitoring | Aggregate where reported |
| Removed persons by destination, category | ICE records | Operational and demographic | Aggregate yes |
| Sensitive-locations enforcement events | ICE records | Policy compliance | Aggregate where reported |

**7.2 Indirect signals:**
- *Performance evaluation considerations:* Officer performance is shaped by enforcement metrics that may create pressure toward enforcement intensity
- *Operational priorities set by administration:* Enforcement targeting is shaped by administration policy direction more than by line-officer judgment
- *Contractor incentives:* Per-bed compensation creates structural pressure toward detention-bed utilization
- *Congressional pressure:* Detention-bed mandates and other congressional pressure shape operational practice
- *State and local cooperation patterns:* Local enforcement partner availability shapes where and how the authority operates
- *Commercial data broker scoring:* Influences targeting in ways not fully visible to subjects

**7.3 Algorithmic decision systems:**

[x] Yes. Multiple systems with substantial R67/R81 implications:

- *Risk Classification Assessment (RCA) and similar tools:* Used in detention-bond and parole decisions; methodology partially restricted; documented disparate-impact concerns. R67 partial gap acknowledged
- *Person-locator and risk-scoring from commercial data brokers (LexisNexis Risk Solutions, Thomson Reuters CLEAR, others):* Used in targeting; vendor methodology not transparent. R67 substantial gap
- *Social media monitoring tools:* Used in identification and targeting; vendor methodology partially restricted
- *License-plate-recognition databases (commercial):* Used in person-tracking; matching algorithm vendor IP. R67 partial gap
- *Facial recognition (where used):* Subject to evolving policy; usage in immigration enforcement raises substantial R66 concerns. R67 floor commitments where used
- *Biometric identification systems:* IDENT, HART (in development), and successor federal biometric infrastructure
- *Predictive analytics for case prioritization:* Methodology partially restricted

The authority acknowledges that algorithmic systems in immigration enforcement raise substantial R66 (proxy substitution for protected characteristics) and R67 (auditability floor) concerns and that current operational practice does not fully meet R67 floors.

**7.4 Outcome-versus-declaration check:** [x] Committed. R79 (Metric Completeness) gap acknowledged: agency outcomes (especially disparate enforcement patterns, detention conditions outcomes, and removal outcomes) cannot be fully predicted from declared metrics; the framework presumes undeclared influence.

---

## SECTION 8 — How is this authority watched?

**8.1 Drift monitoring:**
- DHS Office of Inspector General (audits, investigations, reports)
- DHS Office for Civil Rights and Civil Liberties (complaint investigation, policy review)
- ICE Office of Professional Responsibility (internal misconduct)
- GAO (Government Accountability Office reports)
- Congressional committee oversight (hearings, staff inquiries, investigations)
- Federal court oversight through litigation, consent decrees, and appointed monitors
- Civil society monitoring (American Immigration Council, ACLU, Detention Watch Network, university clinics, journalists)
- International monitoring (UN bodies, foreign governments through diplomatic channels)

The authority acknowledges that drift detection in immigration enforcement is structurally challenged by: classification of operational details; restricted access to detention facilities; case-by-case handling of removals that limits aggregate visibility; and the political contestation of immigration enforcement which makes external monitoring itself contested.

**8.2 Capture risk monitoring:**
- Annual disclosure of contractor relationships
- Lobbying disclosures of detention contractors and other vendors
- Revolving-door tracking (federal ethics rules)
- Funding concentration disclosure (single funder: Congress)
- 287(g) jurisdiction inventory

**8.3 Audit interfaces:**
- *Proactively published:* Annual report; aggregate enforcement statistics; some detention statistics; OIG and CRCL public reports; budget; policy memoranda
- *Available on request per FOIA:* Many records subject to FOIA, with substantial exemptions for law enforcement, deliberative process, and personal privacy
- *Restricted:* Case files (per Privacy Act with exceptions); intelligence files; commercial data broker contracts (partially); detention-facility records (varies by facility); officer-level data; many policy memoranda subject to law-enforcement exemption; foreign-government coordination records

**8.4 Adversarial exposure (R81):** Substantial gaps acknowledged.
- Personnel and discipline records substantially restricted
- Intelligence and investigative files restricted by statutory exception
- Detention-facility access restricted; in-person inspection by external reviewers conditional on agency cooperation
- Contractor data partially restricted
- Algorithmic vendor methodologies partially restricted (vendor IP)
- Foreign-government coordination records restricted
- Sensitive-locations enforcement events partially restricted
- Detainee communications subject to monitoring

R67 (Minimum Auditability Floor) compliance is substantially compromised by these restrictions. The authority acknowledges this as a structural finding and not merely as a temporary information-sharing limitation.

**8.5 Known structural failure modes:**
- Disparate enforcement by race, ethnicity, and national origin
- Wrongful detention of U.S. citizens
- Detention conditions failures (medical neglect, sexual abuse, deaths in custody)
- Family separation and child welfare consequences
- Removals to countries of persecution despite asylum claims
- Errors in databases propagating to permanent federal records and foreign-government records
- Civil rights violations in 287(g) partner jurisdictions
- Surveillance of First Amendment activity and immigrant rights advocacy
- Detention-industry capture of operational scope
- Retaliation against detainees and whistleblowers
- Use-of-force incidents in arrests, raids, and detention
- Misuse of administrative warrants and consent
- Operational practices outside sensitive-locations policy
- Court-house arrests and chilling of court attendance
- Records errors that affected persons cannot correct
- Misuse of commercial data broker outputs
- Inadequate language access in proceedings and detention

The authority acknowledges that this list, drawn from documented patterns, includes failure modes that have occurred extensively in the authority and its predecessor agencies.

**8.6 Trade-secret declarations:**
- *Algorithmic vendor systems:* Risk classification, person-locator, social media monitoring, LPR matching — vendor IP. Mitigation: aggregate validation where possible; methodology disclosure committed where contractually permitted. R67 substantial gap
- *Commercial data broker contracts:* Pricing and some operational terms restricted as trade secret. Mitigation: aggregate operational metrics; FOIA-available portions
- *Investigative methods and intelligence sources:* Restricted by statutory exception
- *Foreign-government coordination:* Restricted by diplomatic and statutory considerations
- *Detention-facility operational details:* Some restricted by contractor confidentiality

R67 floor compliance challenged by multiple of the above. The authority commits to floor mitigations but acknowledges that current operational restriction patterns do not meet the framework's R67 standard in full.

---

## SECTION 9 — How does it end?

**9.1 Estimated dismantling time:** This question requires direct engagement.

In the formal sense, the agency could be reorganized, transferred, or dissolved by act of Congress. In practice, immigration enforcement function has substantial bipartisan congressional support and is unlikely to be dismantled in current political conditions; what is realistic is restructuring (e.g., transfer of functions among federal agencies; abolition of specific functions like detention; replacement by alternative configurations).

In the structural sense, the authority's outputs (records of contact, removal orders, biometric records, family-separation effects, intergenerational effects) cannot be dismantled at all; they have already propagated. R63 applies fully and broadly.

For framework purposes: 60 months from formal dismantling decision to substantive cessation, given congressional, contractual, international, and personnel transition complexities.

**9.2 Dismantling process:**
- Months 1–12: Congressional action; transition planning; identification of successor authorities for any continuing functions; international notification; personnel transition planning
- Months 13–36: Phased cessation of operations; contract terminations and wind-downs; transfer of detained persons; closure or transfer of facilities; transfer of records to successor or to public archive per Privacy Act and applicable law
- Months 37–48: Pension and personnel obligations; ongoing litigation transition; international agreement wind-down
- Months 49–60: Final accounting; entity dissolution; legal continuation only as required for outstanding civil rights litigation and habeas

**9.3 Entrenchment factors:** Substantial.
- *Congressionally-mandated minimums and appropriations* shape operational scope; these cannot be unilaterally reduced by the agency
- *Multi-year detention contracts* with private prison corporations have substantial termination costs and legal complications
- *Records propagated to permanent federal databases and to foreign governments* cannot be recalled
- *Removed persons cannot be straightforwardly returned*; re-entry is a separate offense and many cannot obtain visas
- *Personnel obligations* to ~15,000 federal employees with pension and benefit commitments
- *International agreements* on identity verification and removal logistics extend beyond agency control
- *State and local 287(g) and information-sharing relationships* extend beyond agency authority
- *Pending criminal cases and immigration cases* depend on agency evidence and personnel
- *Pending civil rights litigation* requires preservation of records and personnel availability for years
- *Successor function* — whoever takes over remaining immigration enforcement inherits much of the same structural condition

R61 (Anti-Entrenchment) finding acknowledged: an enforcement system of this scale is structurally entrenched in ways that exceed any single-agency reversal capability. The framework treats this as a structural finding rather than as the agency's individual failure.

**9.4 Data disposition:**
- *Personal data:* Records archived per Privacy Act and applicable retention requirements; transferred to successor or public archive; persons whose records are transferred are notified where law requires
- *Biometric data:* Per applicable retention; some transferred to successor; some destroyed per applicable law
- *Institutional records:* Per federal records law
- *Derived outputs:* Records propagated to permanent federal databases (FBI, NCIC, biometric systems) and to foreign governments cannot be recalled by the agency. R63 finding fully applicable
- *Audit logs:* Archived per applicable law

**9.5 Downstream effect reversibility:**

This section requires the most direct engagement.

The authority's outputs have caused effects that no dismantling can reverse:

- *Removed persons* cannot be straightforwardly returned to the United States. Many cannot obtain visas; many are barred for life; many have lost the documentation, financial means, and personal connections required to return. For the substantial fraction of removed persons who built lives in the U.S. over decades, removal is permanent banishment that no subsequent agency dismantling reverses
- *Children separated from parents* cannot be made unseparated. Subsequent reunification, where it occurs, does not undo the developmental, medical, and emotional effects that the literature documents. For some separated children, reunification has not occurred
- *U.S.-citizen children of removed parents* lost parental presence during formative years — educational, developmental, and life-trajectory effects persist. Many entered foster care or extended family care arrangements that reshape their lives permanently
- *Persons removed to countries of persecution* face ongoing risk; some have been killed, tortured, or persecuted following removal
- *Detention-related medical harm* — including deaths in custody, sexual abuse, mental-health deterioration, and other documented harms — cannot be reversed for affected individuals
- *Records of immigration contact, arrest, and removal* propagated to FBI databases, foreign-government records, and (in many cases) commercial data sources cannot be recalled
- *Chilling effects on healthcare access, school attendance, crime reporting, and court attendance* shape the lives of millions of mixed-status family members; the cumulative effect of an entire generation having grown up under enforcement risk is part of the historical record

R63 (Downstream Effect Reversibility) and R60 (Derived Authority Inheritance) apply with particular force. The authority cannot reverse these effects. R65 (Propagation Duty) requires that on dissolution: (a) the agency notify downstream systems that its data is no longer authoritative; (b) the agency support remediation, including immigration relief for wrongfully-removed persons; (c) the agency preserve records to enable historical investigation and remediation by affected persons.

The framework's reversibility requirement is, for immigration enforcement, a commitment to mitigate, to acknowledge, and to support remediation — not a commitment that effects can be undone. The gap between the structural authority to cause harm and the structural capacity to reverse harm is, in immigration enforcement, among the largest of any authority type the framework registers. This is the foundational R63 acknowledgment.

**9.6 Replacement feasibility:**

R51 (Institutional Replacement Feasibility) requires that this authority be replaceable without destabilizing services beyond authorized scope.

Immigration enforcement function *could* be replaced through alternative configurations: civil immigration adjudication separated from enforcement; reduced detention with alternatives-to-detention programs; transfer of remaining enforcement to other federal entities; legislative restructuring of removability and relief categories. Functional replacement is possible; the question is political rather than technical.

Replacement of the *specific institution* without leaving operational gaps in immigration adjudication and humanitarian processing is harder. Honest disclosure: the authority does not maintain a current succession plan; succession planning would be a substantial undertaking dependent on congressional and executive direction. R51 substantial gap acknowledged.

**9.7 Reversibility verification:**

No formal dismantling rehearsal has been conducted. The agency has no operational practice of simulating cessation. R43 (Reversibility Verification) gap acknowledged at full scale.

The §9.1 timeline is estimated based on transition complexity, congressional process, contract obligations, and personnel transitions. It is not verified.

The authority acknowledges that R43 applied honestly to immigration enforcement is a substantial commitment, and that the question "what would dismantling actually look like" has historically been treated as politically inadmissible rather than operationally engaged. The framework treats this absence as itself a structural finding.

---

## SECTION 10 — Authorization, renewal, and trigger declarations

**10.1 Authorizing body:** Congress (statutory authorization through the INA and related statutes); the President (executive direction within statutory limits); the DHS Secretary; the ICE Director.

**10.2 Date of authorization:** Variable; agency formally created 2003 under the Homeland Security Act; predecessor INS existed under earlier statutory authority. For framework purposes: [DATE] (registration date).

**10.3 Expiration date:** [EXPIRATION DATE].

**10.4 Renewal interval:** 2 years. Justification: scale, harm potential, rapid policy variation across administrations, and the substantial open R26/R63/R69 findings warrant the shorter end of SCBP-09's range. The authority acknowledges that current federal law does not provide a renewal mechanism in the framework's sense; the 2-year cycle is a structural commitment beyond statutory requirement.

**10.5 Renewal evidence declaration:** [x] All five domains.

**10.6 Necessity-decay acknowledgment:** [x] Acknowledged. The authority acknowledges that R62 (Necessity Decay) requires affirmative evidence of reducing scope, dependency, opacity, persistence, or downstream impact. Historical operational practice in immigration enforcement has expanded rather than contracted across decades; demonstrating R62 compliance requires affirmative reduction, not stability.

**10.7 Aggregate trigger threshold:** 100 in 90 days. SCBP-09 §II places non-consenting affected populations in the 1,000,000–100,000,000 band at 25–250. The authority elects 100 — below the midpoint of the band, reflecting both the scale of operations and the public-attention level appropriate to a population this size.

**10.8 Aggregate threshold justification:** The authority's scale produces substantial baseline civic concern; 100 independent triggers in 90 days indicates organized structural concern rather than baseline noise. The authority elects below midpoint to ensure aggregate review remains accessible.

**10.9 Response time window:** 30 days.

**10.10 Response window justification:** Not required (default).

---

## SECTION 11 — What does this authority commit to publishing?

**11.1 Citizen ledger publication:** Quarterly. Includes: budget and expenditure status; staffing levels; aggregate arrests, detentions, removals broken down by category, demographic, and geography; detention-conditions metrics including medical, deaths, force, sexual abuse incidents; family-separation events; sensitive-locations enforcement events; bond decisions and outcomes; complaints filed and disposition; OIG and CRCL findings; consent-decree compliance status; 287(g) program activity; commercial data broker and algorithmic vendor activity; capture risk monitoring; threshold change log.

**11.2 Threshold change log:** Within 7 days.

**11.3 Interpretation change log:** Continuous. Policy memoranda affecting enforcement scope, sensitive locations, prosecutorial discretion, and similar are logged.

**11.4 Renewal process visibility:** [x] Committed. Renewal review by parties drawn from affected categories: removed persons (where reachable); persons with prior detention; mixed-status families; U.S.-citizen children of detained or removed parents; immigrant rights organizations; civil rights organizations; legal services providers; medical professionals with detention experience; academic researchers; family of persons who died in detention — *not* by the agency, the detention contractors, the unions, sister enforcement agencies, or any party with structural alignment with the agency.

**11.5 Stop event log:** [x] Acknowledged.

---

## SECTION 12 — Honesty assertions

**12.1 Disclosure completeness assertion:** [x] Asserted, with acknowledgment that several disclosures (algorithmic vendor methodology, commercial data broker scope, foreign-government coordination details, full operationalization mapping) are partial at registration due to legal restrictions and operational complexity. Partial-disclosure status is itself committed to be reported quarterly.

**12.2 Update obligation:** [x] Committed.

**12.3 Discoverability acknowledgment:** [x] Acknowledged.

**12.4 Burden of proof acknowledgment:** [x] Acknowledged. R69 places the burden of proving constitutional compliance on the authority. The authority accepts that lack of evidence, restricted evidence, or inaccessible evidence results in non-compliance findings — and accepts that current restrictions on personnel records, intelligence files, vendor algorithms, foreign-government coordination, and detention-facility operational details produce R69 findings until those restrictions are addressed.

**12.5 Anti-weaponization acknowledgment:** [x] Acknowledged. R53 (Anti-Weaponization) requires that the framework not be interpreted to justify harm the framework is designed to prevent. Registration under this framework does not legitimize practices the framework's structural limits prohibit; the authority acknowledges that registration is itself a structural disclosure rather than a grant of legitimacy.

---

## SECTION 13 — Submitter

*[Submitter information retained by registry as metadata.]*

---

*REG-IMMIGRATION-ENFORCEMENT-EXAMPLE — worked example of federal interior immigration enforcement authority*
*Registered under the Bounded Power Framework*
*All authority governed by the Structural Constitution (SCBP-04)*
