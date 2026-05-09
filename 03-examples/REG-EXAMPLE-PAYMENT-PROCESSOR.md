---
mechanism_id: SCBP-REG-EXAMPLE-PAYMENT-PROCESSOR
mechanism_name: "PAYMENT-PROCESSOR-EXAMPLE"
status: EXAMPLE
domain: economic
authority_classification: indirect
registered_date: [DATE]
authorization_date: [AUTHORIZATION DATE]
expiration_date: [EXPIRATION DATE]
renewal_interval_years: 2
funding_types:
  - private_for_profit
funding_concentration_max_pct: 14
affected_party_categories:
  - general_public
  - non_consenting_third_parties
  - regulated_industry_participants
  - vulnerable_populations
  - children
affected_population_estimate: 4000000000
non_consenting_population_estimate: 4000000000
entity_size: institutional
geographic_specificity: multi_national
geographic_reach: "Global — operations in approximately 200 countries and territories"
aggregate_threshold_count: 500
aggregate_threshold_window_days: 90
response_window_days: 30
harm_categories_declared:
  - agency_impairment
  - communicative_suppression
  - chronic_asymmetry
  - generational_binding
  - informational_sovereignty
algorithmic_decision_systems_used: true
dependency_count_type1: 84
dependency_count_type2: 18
dependency_count_type3: 14
capture_risk_identified: true
disclosure_completeness_assertion: true
update_obligation_committed: true
discoverability_acknowledged: true
burden_of_proof_acknowledged: true
anti_weaponization_acknowledged: true
---

# Mechanism Record — REG-PAYMENT-PROCESSOR-EXAMPLE

**PAYMENT-PROCESSOR-EXAMPLE**

| Field | Value |
|---|---|
| Mechanism ID | REG-PAYMENT-PROCESSOR-EXAMPLE |
| Status | EXAMPLE |
| Registered | [DATE] |
| Authorization expires | [EXPIRATION DATE] |
| Domain | Economic |

---

## SECTION 1 — What is this authority?

**1.1 Mechanism name:** PAYMENT-PROCESSOR-EXAMPLE — a global payment network operating one of the major payment rails through which a substantial fraction of consumer and business transactions are processed.

**1.2 Functional description:** A global payment network operating one of two dominant card-payment rails plus adjacent products. The network connects approximately 4 billion cardholders to approximately 100 million merchants in approximately 200 countries and territories, intermediating an estimated 200+ billion transactions annually with a transaction volume of trillions of dollars. The network does not lend money, hold consumer deposits, or issue cards directly to consumers; it operates the rules, technology, brand, and dispute infrastructure that allow card-issuing banks and merchant-acquiring banks to clear transactions. Functional authority:

- *Sets and enforces network rules* governing what merchants may accept payment for, what categories of business may obtain merchant accounts, what behavior triggers fines and termination, what chargeback procedures apply, what fees and interchange rates are permitted
- *Categorizes merchants* by Merchant Category Code (MCC) — a classification that determines fee tiers, dispute eligibility, rule applicability, and (functionally) whether certain businesses are accepted at all
- *Defines "high-risk" merchant categories* and "prohibited" merchant categories — businesses in prohibited categories cannot use the network regardless of whether their activity is legal
- *Determines which legal businesses may transact through the network* — explicit prohibitions or de facto exclusions affect specific businesses including some adult content, cannabis where state-legal, firearms in some configurations, certain political organizations, certain cryptocurrency businesses, and others. Categories shift based on network policy decisions, regulatory pressure, reputational considerations, and political pressure
- *Imposes fines and assessments* on issuing and acquiring banks for rule violations, which propagate to merchants and cardholders
- *Operates the dispute and chargeback infrastructure* that determines outcomes of customer-merchant disputes
- *Maintains the global authorization, clearing, and settlement infrastructure* — the technical systems that decide in milliseconds whether a transaction is approved, declined, or flagged for review
- *Operates fraud detection systems* that may decline transactions based on risk scoring; these decisions are made by algorithm at the network level, by the issuing bank, or both
- *Defines and enforces brand standards* — including standards affecting merchant-facing content, advertising, and communications
- *Operates tokenization, contactless, and related technologies* that lock in network position
- *Enters into agreements with governments, regulators, and standards bodies* shaping the global payments environment

The network's authority is consequential because it operates a chokepoint between buyers and sellers in essentially the entire formal economy. Decisions about which businesses may accept network payments determine which legal activities can participate in the modern economy. A merchant denied access to the network by category — adult content, cannabis, firearms in some configurations, certain political organizations — typically cannot find equivalent payment infrastructure through the other major network either, because the two dominant networks make similar category decisions and no comparable third option exists at scale.

The framework treats this honestly: the network is a private actor exercising authority comparable in scope and consequence to government regulation of who may transact in the formal economy, while operating without the constitutional, statutory, or due-process constraints that would apply to government action. The network's rule-making, enforcement, and exclusion decisions are made by private corporate governance accountable to shareholders, not by any process structurally comparable to public adjudication.

A second structural feature: account closures (or merchant-account closures, or category-based exclusions) typically include limited notice, limited explanation, and no comparable appeal. When affected, individuals and businesses may not know why they were closed, may not be able to challenge the underlying determination, and may be unable to obtain comparable service from the duopoly partner. The colloquial term "debanking" captures the experience; structurally, what is happening is private exercise of exclusion authority at population scale.

The framework requires honest description of these features, not the network's preferred self-description as a technology platform or payment network.

**1.3 Authority classification:** Indirect (primary). The network does not directly compel any merchant or cardholder action. Authority operates through R58 — the network's outputs (rule-making, category determinations, exclusion decisions, fraud-decline outputs, fee structures) materially shape decisions made by issuing banks, acquiring banks, merchants, and cardholders at scale.

The framework also recognizes a direct authority surface: the network directly excludes specific merchants, imposes specific fines, and makes specific decline determinations affecting specific transactions. At the scale of 200+ billion transactions annually, the direct surface is itself enormous.

The network acknowledges that R58 classifies it as exercising authority, that R72 applies broadly because acquiring-bank and issuing-bank decisions made under network rules are functionally network authority, and that R55/R59 recognize the duopoly structure of the dominant card-payment networks as a single authority system for containment purposes.

**1.4 Domain:** Economic (primary). Technology (secondary). Infrastructure (secondary).

**1.5 Statutory or constitutional basis:** Operates as a publicly-traded for-profit corporation under [STATE] corporate law (typically Delaware) and applicable national laws in each jurisdiction of operation. Subject to: federal banking and financial-services regulation in the United States, including the Dodd-Frank Act's Durbin Amendment regarding interchange (with respect to debit transactions), the Bank Secrecy Act, anti-money-laundering laws, sanctions law (OFAC), Consumer Financial Protection Bureau supervision in some respects; equivalent regulation in other jurisdictions including the European Union (PSD2, EU competition law, MIF Regulation), the United Kingdom, and approximately 200 other jurisdictions; antitrust law (subject to litigation and enforcement action over decades regarding network structure and exclusionary conduct); securities law as a publicly-traded entity; consumer-protection laws as applicable; tax law.

The network's authority over its rules and merchant categories is grounded in private contract law: issuing banks, acquiring banks, and merchants accept the network's rules as a condition of network participation. Enforcement is through contract — fines, suspension, termination — rather than through statute. This contractual framing is operationally consequential: rights that would attach to government action (notice, due process, reasoned decision) do not attach to network action.

The framework's R28 (Expiration Default) requires that all authority expire absent affirmative renewal. The network operates under permanent corporate authorization. The 2-year framework renewal cycle is a structural commitment beyond statutory requirement.

---

## SECTION 2 — Who can this authority act upon?

**2.1 Affected party categories:**
- [x] General public (essentially anyone holding or accepting a card on the network)
- [x] Non-consenting third parties (cardholders did not negotiate the network's rules; merchants accepting cards have effectively no negotiating position; end users of dependent services experience network decisions without ever having a direct relationship with the network)
- [x] Regulated industry participants (issuing banks, acquiring banks, payment-services providers, merchants — all subject to network rules as a condition of network access)
- [x] Vulnerable populations: people in countries with limited alternative payment infrastructure; cardholders dependent on debit cards for benefit receipt and payroll; merchants in high-risk categories whose access to the formal economy depends on network decisions; small businesses with limited bargaining power; people whose income depends on platforms whose payment infrastructure is the network; political dissidents and organizations whose donations flow through the network
- [x] Children (under age of majority): cardholders under 18 (in some markets); minors as transaction participants; minors whose family economic life is shaped by the network's rules

**2.2 Approximate number of people directly affected:** Approximately 4 billion cardholders globally; approximately 100 million merchants. The full affected population includes essentially everyone in the formal global economy.

**2.3 Non-consenting population:** Essentially the entire affected population.

Cardholders typically receive cards through banks, employers, or benefit-administration systems. They accept cardholder agreements they have not read and cannot meaningfully negotiate. The cardholder cannot opt out of the network as a category and remain in the formal economy without substantial inconvenience.

Merchants accept the network's rules as a condition of accepting cards. For most merchants in most countries, refusing to accept cards is functionally refusing to participate in retail commerce. The merchant cannot meaningfully negotiate network rules; the merchant accepts them or exits.

Issuing and acquiring banks accept the network's rules as a condition of network access. Switching or refusing rules requires entry into competing network infrastructure, which at this scale typically does not exist.

R14 (Non-Participant Exposure Mapping) and R26 (Non-Participant Harm Floor) apply with full force. The framework treats the entire 4 billion cardholders + 100 million merchants as non-consenting in the framework's sense.

**2.4 Vulnerable population specifics:**

- [x] Children — *partial*. Minors as cardholders (in markets that permit) are subject to network rules and to the parental account structure that may shape their access. Minors as transaction participants (e.g., paying for school items, receiving benefits via card) are affected. The network's commercial-content rules affect what content is monetized in ways that reach minors as users of dependent services. Mitigations: minor-specific cardholder protections per applicable law; parental account structures; restrictions on content categories. R26 partial gap acknowledged: rule application to minors operates through issuing-bank and merchant practice rather than directly; aggregate effect on minors is not systematically tracked.
- [x] Patients during medical care — *partial*. Healthcare and medical-related transactions are subject to network rules; PCI compliance, HIPAA-related considerations, and merchant-category rules for healthcare apply. Transactions for sensitive healthcare (reproductive health, mental health, gender-affirming care) may be affected by network category decisions and by merchant-acquirer risk practices.
- [ ] Detained or confined persons — partial; correctional commissary and family-support payment products are subject to network rules in ways that have produced documented exploitative patterns; this is a downstream harm rather than a direct authority surface for the network as such.
- [x] Persons in coercive economic relationships — *yes, broadly*. Workers paid through payroll cards, benefit recipients receiving payments via card, gig economy workers paid through platforms whose payment infrastructure is the network, international remittance users — all are in coercive economic relationships with respect to network rules, fees, and access decisions. Account closure or category-based exclusion can be functionally catastrophic. R26 substantial gap acknowledged.
- [x] Persons unable to advocate for themselves — *yes*. Cardholders with limited financial literacy, limited language access in network-relevant disputes, cognitive or developmental disabilities, or other capacity-affecting conditions face substantial disadvantage in disputes with merchants, with issuing banks (under network rules), and with the network itself in the rare cases where network-level recourse is available. Mitigations: cardholder-protection rules backed by network policy; chargeback infrastructure. R26 substantial gaps acknowledged on a global basis given uneven implementation.

The network acknowledges that R26 (stricter harm tolerance for non-participants) applies with particular weight because essentially all 4 billion+ affected persons are non-consenting and substantial portions are vulnerable across multiple categories simultaneously.

---

## SECTION 3 — What can it do, and what can it not do?

**3.1 Geographic reach:** Approximately 200 countries and territories. Operations are global; corporate domicile is United States; substantial operations also in Europe, Asia, Latin America, Africa.

**3.2 Coercive ceiling:**
- *Network rules:* Set and modify rules governing all participants; rule changes propagate to all participants on stated effective dates with no negotiation
- *Merchant categorization:* Assign and modify Merchant Category Codes; category determines fee tiers, dispute eligibility, and (in some categories) eligibility at all
- *Merchant exclusion:* Define prohibited and high-risk merchant categories; specific merchants may be excluded by name
- *Fines and assessments:* Impose financial penalties on issuing banks, acquiring banks, payment service providers, and (through them) merchants for rule violations
- *Termination:* Suspend or terminate participation rights of issuing banks, acquiring banks, payment service providers, and through them merchants
- *Authorization decisions:* In real time, approve, decline, or flag transactions; some declines are issuer decisions, some are network decisions, some are joint
- *Dispute and chargeback determinations:* Outcome-determining authority over merchant-cardholder disputes within network rules
- *Tokenization, contactless, and identity infrastructure:* Operating control over technical infrastructure that lock-in network position
- *Brand and trademark enforcement:* Action against unauthorized use of network marks
- *Regulatory engagement:* Negotiate with governments, central banks, and regulators on payments policy
- *Acquisition and partnership:* Acquire or partner with related infrastructure

The network may NOT (per applicable law and contract):
- Operate in violation of antitrust law (subject to ongoing litigation and regulatory action)
- Operate in violation of sanctions law, anti-money-laundering law, or applicable financial-services regulation
- Discriminate on protected characteristics in cardholder treatment (subject to applicable consumer-protection law)
- Process transactions that violate applicable law in the jurisdiction of transaction
- Modify rules in violation of contractual notice and process requirements
- Misuse cardholder data (subject to data-protection law including PCI DSS, GDPR, and analogues)

**3.3 Resource ceiling:**
- Operating revenue: tens of billions of dollars annually (varies; public company)
- Operating expenses: per public filings
- Staff: tens of thousands of FTE globally
- Infrastructure: global authorization, clearing, and settlement systems; data centers; technology platform supporting 200+ billion annual transactions
- Capital: substantial; market capitalization in hundreds of billions of dollars
- Brand portfolio: trademark and brand portfolio of the network's marks

**3.4 Explicit exclusions:**
- **Geographic:** Subject to sanctions law and applicable national laws; certain jurisdictions excluded by sanctions
- **Action:** May not operate in violation of antitrust law (subject to ongoing constraints); may not modify rules in violation of contractual notice; may not engage in deceptive or unfair practices under applicable consumer-protection law
- **Data:** Subject to PCI DSS, GDPR, and applicable data-protection law; may not retain or share cardholder data beyond authorized purpose; may not market individually-identifiable cardholder data
- **Procedural:** Rule changes subject to contractual notice; major rule changes subject to issuing-and-acquiring-bank consultation per network governance; participant termination requires stated grounds and contractual process
- **Other:** Subject to ongoing antitrust monitoring and litigation in multiple jurisdictions

**3.5 Indirect influence boundaries:** This is the load-bearing section.

The network's outputs propagate widely:

- *Rule changes* shape merchant pricing, surcharging practice, refund policies, and chargeback exposure across 100 million merchants
- *Merchant Category Code assignments* shape fee structures, eligibility for products, and (functionally) acceptance into the formal economy
- *Prohibited and high-risk category determinations* effectively determine which legal businesses can participate in card payments at scale. Categories that have been the subject of network policy decisions include: adult content, sex work-adjacent businesses, cannabis (where state-legal but federally restricted in the U.S.), firearms in some configurations, certain cryptocurrency exchanges, some political organizations and dissident-associated transactions, some social-media-platform-monetization tiers, certain payment-aggregator structures
- *Fraud decisioning* — declines based on network risk scoring affect cardholders' immediate access to their funds and merchants' immediate access to revenue; affected cardholders may not know why a decline occurred
- *Chargeback rule changes* shift risk and cost between merchants and cardholders in ways that affect millions of merchants
- *Settlement timing* shapes merchants' cash flow at scale
- *Tokenization and standards decisions* lock in technical architecture
- *Regulatory engagement* shapes payments policy in dozens of countries
- *Network-rule-driven account closures* propagate to issuing-bank and acquiring-bank action; the affected merchant or cardholder typically cannot determine whether the decision originated at the bank, the network, or in coordination

R58 applies with full force. The framework recognizes the network's outputs as exercising authority over essentially the entire formal global economy.

The framework also recognizes a propagation pattern specific to payment networks: because the two dominant card-payment networks make similar category and risk decisions, exclusion from one network typically means exclusion from comparable infrastructure. The "duopoly" framing in §6.6 captures this; for practical purposes, a merchant excluded by one network has no comparable alternative at scale.

**3.6 Anti-proxy declaration:**

The network commits to not using:

- *Proxy for race, ethnicity, national origin, religion in cardholder treatment:* Authorization, fraud scoring, and dispute outcomes may not use these as criteria. Acknowledged that operational practice in fraud scoring has produced documented disparate-impact concerns; aggregate disparate-impact testing of fraud scoring committed; results published.
- *Proxy for political viewpoint:* Merchant categorization and exclusion decisions may not be predicated on political viewpoint. Acknowledged that merchant categories that have been subject to exclusion (some political organizations, certain dissident-associated transactions) may overlap with political viewpoint in ways that raise R66 concerns; the network commits that category decisions affecting political organizations require board-level review with documented reasons.
- *Proxy for legal-but-disfavored activity:* Merchant categorization may not effectively treat legal activity as illegal through category exclusion. Acknowledged that historical practice has treated legal-but-controversial categories (adult content, cannabis where state-legal, firearms in some configurations) in ways that approach this concern; the network commits to public disclosure of category criteria and to documented reasons for category-level exclusions.
- *Proxy for "reputation risk":* The network's reputation-risk framework has historically been used to justify category and merchant decisions where the underlying ground was political or moral pressure rather than legal or financial risk. R66 finding acknowledged; reputation-risk decisions affecting category eligibility require documented reasons and disclosure.
- *Proxy for sex worker, adult performer, or other protected-class activity status:* Cardholder and merchant treatment may not effectively treat membership in these categories as basis for adverse action.

The network acknowledges that all five proxy commitments require ongoing structural attention, that historical practice has produced repeated R66 findings on multiple of these dimensions, and that reputation-risk and category-exclusion decisions are the network's most substantive R66 vulnerability.

---

## SECTION 4 — What harms can it cause?

**4.1 Bodily harm threshold:** Indirect.

The network's primary surface is financial, not direct physical action. Indirect pathways:
- *Account closure causing inability to access medical care or essential goods:* If a cardholder's primary payment method is closed and replacement is delayed, downstream bodily harm may occur (missed medications, missed medical appointments, food insecurity). Threshold: aggregate complaint patterns regarding closure-related access loss tracked.
- *Merchant exclusion causing safety harm:* Category exclusions affecting safety-relevant goods (medications, harm-reduction supplies, safety equipment for sex work, etc.) may produce downstream bodily harm. Threshold: any documented safety-harm pattern traceable to network category decisions triggers review.

**4.2 Agency impairment threshold:** Substantial.

- *Account closure without notice or explanation:* A cardholder or merchant whose access is closed without notice or explanation, and without comparable appeal, has been substantively impaired in their ability to participate in the formal economy. Aggregate closure rates monitored; closure rates exceeding stated thresholds for any category trigger review. Closures affecting protected categories trigger immediate review.
- *Dispute and chargeback process inaccessibility:* Cardholders and merchants unable to navigate the dispute process due to language, capacity, or representation barriers face substantive impairment. Aggregate dispute outcomes by demographic monitored where data permits.
- *Authorization-decline patterns:* Aggregate decline patterns for cardholders, particularly patterns affecting specific demographic or geographic segments, trigger review.
- *Rule-change notice failures:* Rule changes implemented without adequate notice to affected participants — finding.
- *Procedural barriers in network governance:* Banks and payment service providers facing barriers to network governance participation — finding.

**4.3 Ecological damage threshold:** Limited applicability. Network operations have substantial computing-resource footprint; environmental compliance and disclosure committed per applicable standards.

**4.4 Generational binding threshold:** Substantial.

- *Lock-in through technical infrastructure:* Tokenization, contactless, and adjacent technologies create switching costs that bind participants over decades
- *Data retention:* Transaction history retained per regulatory requirements and for fraud-prevention purposes propagates affected persons' financial behavior into permanent record
- *Categorical exclusions persist:* A merchant excluded under a category designation faces ongoing exclusion until and unless network category policy changes; a cardholder closed for fraud-suspicion may face ongoing fraud-flag effects across multiple banks
- *Generational wealth effects:* Access to payment infrastructure shapes intergenerational economic outcomes; populations historically excluded from formal banking face compounding effects

Threshold: data retention policies, technical lock-in features, and categorical exclusion patterns reviewed for proportionality and necessity decay (R62) annually.

**4.5 Communicative suppression threshold:**
- *Category-based exclusion of journalism, advocacy, dissent organizations:* Exclusion affecting journalism or advocacy organizations — finding for each instance; aggregate pattern triggers systemic review
- *Suppression of sex worker organizing and harm-reduction work:* Categorical decisions affecting sex worker safety-and-organizing infrastructure raise R66 concerns; aggregate review committed
- *Restrictions on political donations, mutual aid, and legal-but-disfavored speech-related transactions:* — finding for documented patterns
- *Coordination with government request for transaction data without legal process beyond statutory requirements:* — finding

**4.6 Informational sovereignty threshold:**
- Cardholder transaction data shared beyond stated retention or stated purpose — finding
- Cardholder data sold or licensed in ways inconsistent with cardholder agreement — finding
- Coordination with foreign or domestic government beyond legal-process requirements — finding
- Errors in cardholder records, fraud-flag records, or merchant records that affected persons cannot correct — finding for each substantiated instance; aggregate error rates published

**4.7 Additional harm thresholds:**

*Chronic asymmetry threshold:* If account closure, fraud-flag, decline, or category-exclusion rates correlate with race, religion, national origin, or other protected characteristic at p<0.05, this triggers systemic review.

*Duopoly-coordination threshold:* If category decisions, exclusion decisions, or rule changes by this network are followed within 90 days by similar decisions by the duopoly partner, this aggregate pattern triggers review for R30/R31/R55 (coordination as power expansion) findings.

*Government-pressure threshold:* If category decisions or specific exclusion decisions follow government pressure (formal or informal) without legal process required for government action, this triggers review. This is a recurring R64 (External Circumvention Prohibition) concern: government cannot require certain exclusions directly, and informal pressure on private network may achieve the same result without due process.

*Reputation-risk-decision threshold:* Network decisions justified primarily on "reputation risk" grounds — review with documented reasons; aggregate use of reputation-risk justification monitored.

*Wrongful-closure threshold:* Aggregate closure-then-restoration rates (closures subsequently determined to have been erroneous) tracked; high rates indicate process drift.

**4.8 Threshold change-log commitment:** [x] Yes — committed.

---

## SECTION 5 — What stops it?

This section is structurally difficult. The network is among the largest and most politically-protected private actors in the global financial system. Stop paths must be evaluated honestly against the structural conditions that have shaped them.

**STOP PATH 1 — Antitrust enforcement and competition law**
- *Activator:* U.S. Department of Justice; Federal Trade Commission; European Commission; competition authorities in approximately 200 jurisdictions; private antitrust plaintiffs.
- *Trigger:* Determination of antitrust violation, abuse of dominant position, or anticompetitive coordination.
- *What "stopped" means:* Court orders may modify network rules, structurally separate functions, impose damages, or require divestiture. Historical antitrust actions against the major card networks have produced substantial structural changes (e.g., regarding interchange rules, exclusivity provisions, surcharging rules) but have not fundamentally altered the duopoly structure.
- *Independence:* Competition authorities are structurally independent. *Acknowledged limitation:* Antitrust enforcement against the dominant networks has produced limited structural change relative to the duopoly's ongoing market position; the underlying network-effects characteristics of payment infrastructure produce concentration that competition law has not effectively addressed at scale.
- *Timeline:* Antitrust actions typically span 5–15 years.

**STOP PATH 2 — Financial-services regulation and central-bank action**
- *Activator:* Consumer Financial Protection Bureau, Federal Reserve, OCC, FDIC, Department of Treasury (U.S.); equivalent regulators globally; central banks operating real-time payment alternatives.
- *Trigger:* Regulatory determination of violation; supervisory finding; rulemaking determination.
- *What "stopped" means:* Rules and supervisory actions may modify specific network practices; central-bank-operated payment alternatives (e.g., FedNow in the U.S., real-time payment systems in other countries, central-bank digital currencies in development) may reduce duopoly power.
- *Independence:* Regulators and central banks are structurally independent. *Acknowledged limitation:* Financial-services regulators have historically focused on safety-and-soundness rather than on the network's exclusion authority; consumer-protection enforcement against network rule decisions has been limited; central-bank alternatives are emerging but not yet at scale.
- *Timeline:* Per agency procedures; central-bank alternatives operate on multi-year deployment timelines.

**STOP PATH 3 — Civil litigation, market alternatives, and public attention**
- *Activator:* Class action litigation by merchants, cardholders, or excluded businesses; market entry by alternative payment infrastructure (real-time payment systems, account-to-account networks, cryptocurrency-based alternatives, regional networks); concentrated public attention to specific exclusion or closure decisions.
- *Trigger:* Court determinations; market dynamics; public-attention events triggering policy reversal.
- *What "stopped" means:* Litigation may produce damages, rule changes, or specific reversals. Market alternatives may erode network position over time. Public attention may produce specific policy reversals (the network has reversed specific exclusion decisions following sustained public attention; the affected merchants are typically high-profile rather than typical).
- *Independence:* Courts and market are independent of the network. *Acknowledged limitation:* Litigation and market entry are slow; public attention is selective and benefits high-profile cases more than typical exclusions.
- *Timeline:* Per actor.

**5.4 Penalty for activating stop:** [x] Confirmed in policy. *Acknowledged structural concern:* Merchants, banks, and payment service providers in ongoing relationships with the network may face informal disadvantage when raising regulatory or legal complaints. Whistleblowers within the network have had varying experiences. The network's stated commitment is non-retaliation; the documented gap is itself a recurring concern.

**5.5 Stop-path independence verification:** Antitrust authorities, financial regulators, central banks, and courts are structurally independent. *Acknowledged R03 (Institutional Capture) concerns:* the network engages in substantial regulatory and political activity globally, including lobbying, consultative participation, and revolving-door personnel patterns with regulators. Capture concerns at the regulatory and policy levels are documented and ongoing.

*Acknowledged R55/R59 finding:* The two dominant card-payment networks function operationally as a duopoly with substantially similar rules, similar category decisions, and similar exclusion patterns. R55 (Fragmentation Must Not Defeat Containment) and R59 (Functional Continuity Consolidation) require evaluation of the duopoly as a single authority system for many purposes. Antitrust law has historically had difficulty addressing this functional consolidation given the formal corporate separation.

**5.6 Civic trigger acknowledgment:** [x] Acknowledged.

---

## SECTION 6 — What does it depend on?

**6.1 Type 1 dependencies:**

The network operates with approximately 84 Type 1 dependencies, including:
- Issuing banks (~thousands worldwide; sponsoring relationships)
- Acquiring banks and payment service providers (~thousands; merchant-side)
- Technology infrastructure providers (cloud, networking, security)
- Tokenization and identity infrastructure providers
- Fraud detection and risk-scoring vendors and partners
- Card manufacturers and contactless-technology providers
- Settlement banks
- Regulatory and compliance technology providers
- Brand protection and trademark counsel
- Audit and assurance firms
- Marketing and advertising contractors
- Government affairs and lobbying contractors

**Funding-source disclosure:** The network operates on transaction-fee revenue across hundreds of millions of merchants and billions of transactions; no single counterparty exceeds approximately 14% of revenue. Per form §6.4, this is below the 33% threshold but the network operates at a scale where any individual large counterparty (largest issuing banks, largest acquiring banks, largest merchants) has substantial structural relationship.

**6.2 Type 2 dependencies:**
- Federal Reserve and other central banks (settlement infrastructure, monetary policy context)
- Financial-services regulators in approximately 200 jurisdictions
- Antitrust authorities globally
- Standards bodies (EMVCo, PCI Security Standards Council, ISO, others)
- The duopoly partner (R55/R59 functional-continuity relationship; substantial coordination at standards-body and rule-coordination level)
- Major issuing-bank groups
- Major acquiring-bank groups
- Major merchant groups (retail trade associations; merchant payment coalitions)

**6.3 Type 3 dependencies:**
- *Settlement infrastructure:* Federal Reserve and central-bank settlement systems
- *Standards body coordination:* PCI DSS, EMVCo standards
- *Issuing and acquiring bank network:* Loss of major participants would compromise operational scale
- *Tokenization and contactless infrastructure:* Standards and technology lock-in
- *Antitrust and regulatory monitoring infrastructure:* If regulatory infrastructure compromised, stop paths 1 and 2 compromised
- *Cloud and computing infrastructure providers:* Concentration of cloud providers creates compromise risk
- *International data flow infrastructure:* Cross-border data flow regimes (Privacy Shield successor frameworks, standard contractual clauses, sectoral arrangements)

**6.4 Capture risk identification:** [x] Yes. Substantial.

- *Duopoly structure:* The two dominant card-payment networks coordinate at standards-body and rule-coordination level in ways that approach R55/R59 functional consolidation. R55/R59 findings acknowledged.
- *Regulatory capture:* The network engages in extensive lobbying, regulatory consultation, and revolving-door personnel patterns. Mitigation: lobbying and political-spending disclosure (per applicable law); disclosure of major regulatory positions. R03 finding acknowledged.
- *Standards-body capture:* The network's dominant position at standards bodies (EMVCo, PCI SSC) creates capture concerns at the standards level. Mitigation: ongoing antitrust review; participation by other parties.
- *Government-pressure exposure:* Government pressure on the network to exclude specific categories or specific transactions raises R64 (External Circumvention) concerns: governments cannot require certain exclusions directly through legal process, and pressure on the private network may achieve equivalent results. R64 finding acknowledged; documented patterns include sustained pressure regarding adult content, cannabis where state-legal, certain dissident transactions.
- *Acquiring-bank concentration:* A small number of acquiring banks process the bulk of transactions; their decisions (often shaped by network rules but sometimes ahead of network rules in risk-aversion) effectively shape merchant access.
- *Issuing-bank concentration:* A small number of issuing banks issue the bulk of cards; their decisions shape cardholder treatment.
- *Cloud and technology infrastructure concentration:* Industry-wide concentration in a few large cloud providers creates capture-related risk.

**6.5 Reversibility-affecting dependencies:**
- Technical infrastructure (tokenization, contactless) has multi-year lock-in
- Issuing-and-acquiring-bank relationships have multi-year contractual structure
- International regulatory commitments
- Standards-body commitments
- Pension and personnel obligations
- Brand and trademark portfolio

**6.6 Coordination disclosures:**

The network coordinates with:
- The duopoly partner (standards bodies, rule coordination, certain industry positions) — *R55/R59 functional continuity acknowledged*
- Issuing-bank associations and acquiring-bank associations
- Standards bodies (EMVCo, PCI SSC, ISO)
- Government regulators worldwide
- Industry working groups

**Acknowledged R55/R59 finding:** The card-payment duopoly functions as a single coordinated authority system for many purposes. Rule changes, category decisions, and standards positions are frequently coordinated or sequentially adopted across the duopoly. R55 (Fragmentation Must Not Defeat Containment) requires evaluation of this functional continuity. Regulators evaluating either network in isolation are evaluating an incomplete authority system.

**Acknowledged R64 (External Circumvention) finding:** Government pressure on the network to exclude specific categories or specific transactions creates a structural concern: governments cannot require certain exclusions directly through legal process subject to constitutional protection, but informal pressure on the network may produce equivalent results without those protections. Documented patterns include pressure regarding adult content, cannabis in U.S. state-legal contexts, certain political and dissident transactions, and certain sex-work-adjacent businesses. R64 finding acknowledged.

**6.7 Disclosure completeness assertion:** [x] Asserted with the standard acknowledgment that complete dependency mapping at this scale is structurally unattainable; informal coordination relationships and government-pressure relationships are partially restricted from disclosure.

**6.8 External authority operationalization:**

- *Issuing-bank decisions:* Issuing-bank fraud declines, account closures, and decisions about which cardholders to serve are operationalized within the network surface. R72 applies. Affected cardholders typically cannot distinguish network decisions from issuing-bank decisions.
- *Acquiring-bank decisions:* Acquiring-bank merchant onboarding, ongoing monitoring, and termination decisions are operationalized within the network surface. R72 applies. Acquiring-bank decisions are often more restrictive than network rules require because acquiring banks bear chargeback risk and respond to network signals about category risk.
- *Government-pressure-driven decisions:* Where governments pressure the network to exclude categories or transactions without legal process, the network's compliance operationalizes government authority without the constraints that would apply to direct government action. R72/R64 apply.
- *Sanctions list compliance:* OFAC and equivalent sanctions lists are operationalized as network authority for affected parties. R72 applies.
- *Standards-body decisions:* PCI DSS and EMVCo decisions are operationalized as network authority for participants.
- *Algorithmic risk-scoring vendors:* Fraud-scoring algorithms (some network-operated, some third-party) shape transaction approval and decline decisions. R72 applies; vendor methodology partially restricted.

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

**7.1 Declared metrics:**

| Metric | Source | Role | Public? |
|---|---|---|---|
| Authorization, approval, decline rates | Network systems | Operational; risk monitoring | Aggregate yes |
| Chargeback rates by merchant, category, region | Network systems | Risk-pricing; rule-making | Aggregate yes |
| Fraud rates by category, geography | Network and partner systems | Rule-making; pricing | Aggregate yes |
| Settlement volumes and timing | Network systems | Operational | Aggregate yes |
| Merchant categorization (MCC) | Network and acquirer | Pricing; eligibility | Yes (categories published) |
| Account closure / merchant termination | Acquirer and network | Risk management | Aggregate partial |
| Transaction value, volume | Network systems | Operational | Aggregate yes |
| Regulatory and litigation status | Network records | Compliance | Public per regulatory requirement |

**7.2 Indirect signals:**
- *Risk scoring algorithms:* Network and acquirer risk scoring shapes transaction approval, fraud flagging, account-closure recommendations
- *Category-risk perceptions among acquiring banks:* Acquiring-bank reluctance regarding specific categories often shapes merchant access more than network policy explicitly does
- *Regulatory and political signaling:* Government communications, press attention, and political pressure shape category decisions and specific exclusions
- *"Reputation risk" assessments:* Internal network assessments of reputation risk shape category and merchant decisions in ways not formally measurable
- *Major sponsor and bank preferences:* Major participants' preferences shape rule-making
- *Standards-body coordination:* Standards-body positions shape technical and rule decisions

**7.3 Algorithmic decision systems:**

[x] Yes. Multiple systems with substantial R67/R81 implications:

- *Network fraud-scoring algorithms:* Score-based decline and flag decisions at network level. Methodology partially restricted; vendor IP in some cases. R67 partial gap.
- *Issuing-bank fraud-scoring algorithms (operationalized through network):* Each issuer's algorithms; methodology not network-controlled. R72 finding.
- *Acquirer risk-scoring algorithms:* Methodology not network-controlled. R72 finding.
- *Authorization decisioning:* Real-time approval, decline, flag decisions at network level. Methodology partially restricted.
- *Category-risk modeling:* Underwriting and rule-making models classifying merchant categories by risk. Methodology partially restricted.
- *Behavioral analytics:* Pattern detection across cardholder and merchant behavior. Privacy and methodology partially restricted.

The network acknowledges that algorithmic systems in payment authorization and fraud raise substantial R66 (proxy for protected characteristics), R67 (auditability floor), and R72 (external operationalization) concerns. Aggregate disparate-impact testing committed; methodology disclosure committed where contractually permitted.

**7.4 Outcome-versus-declaration check:** [x] Committed. R79 (Metric Completeness) gap acknowledged: outcome patterns (particularly disparate-impact patterns in fraud scoring and account closure) cannot be fully predicted from declared metrics; the framework presumes undeclared influence.

---

## SECTION 8 — How is this authority watched?

**8.1 Drift monitoring:**
- Internal compliance and audit functions
- External annual audit (financial; regulatory; PCI compliance)
- Regulator supervision in approximately 200 jurisdictions
- Antitrust monitoring globally
- Securities filings and shareholder oversight (publicly-traded entity)
- Standards-body participation
- Civil society monitoring (consumer protection organizations; merchant coalitions; academic researchers; financial inclusion advocates)
- Litigation (substantial ongoing antitrust, consumer-protection, and merchant-class litigation in multiple jurisdictions)

The network acknowledges that drift detection at this scale is structurally challenged by: confidentiality of business operations; complexity of global multi-jurisdiction operations; political contestation of regulation in this sector; and the absence of any single authority with comprehensive oversight.

**8.2 Capture risk monitoring:**
- Lobbying and political-spending disclosure (per applicable law)
- Government affairs disclosure
- Major regulatory positions disclosure
- Tracking of duopoly-coordination patterns (the network commits to disclosure of standards-body and rule-coordination activity that approaches R55/R59 territory)
- Tracking of revolving-door personnel patterns (current employees with prior regulator service; regulator hires from network)

**8.3 Audit interfaces:**
- *Proactively published:* Annual financial report; annual sustainability and compliance report; aggregate operational metrics; merchant category code publications; general rule structure; standards-body positions
- *Available on request per applicable law:* Specific records as appropriate to regulator and litigation
- *Restricted:* Specific algorithm internals (vendor IP and competitive); specific government coordination details (where not publicly disclosed); specific account closure individual records (privacy and contractual); specific pricing arrangements (competitive); specific reputation-risk assessments and internal communications about category decisions (deliberative)

**8.4 Adversarial exposure (R81):** Substantial gaps acknowledged.
- Algorithm internals partially restricted (vendor IP)
- Specific category-decision deliberations restricted (deliberative)
- Government-pressure-driven decisions partially restricted
- Specific account closure individual records restricted
- Acquiring-bank-level decisions not directly observable at network level
- Duopoly coordination details partially restricted (antitrust-sensitive)
- Specific pricing and contractual arrangements partially restricted (competitive)

R67 (Minimum Auditability Floor) compliance is substantially compromised by these restrictions. The network acknowledges this as a structural finding.

**8.5 Known structural failure modes:**
- Disparate impact in fraud scoring, account closure, merchant categorization
- Wrongful account closure with limited recourse
- Category-based exclusion of legal-but-disfavored businesses
- Government-pressure-driven exclusion without due process (R64)
- Duopoly coordination defeating containment
- Reputation-risk framework used as proxy for political or moral pressure
- Standards-body capture
- Regulatory capture
- Algorithmic vendor IP restrictions limiting auditability
- Cardholder data breaches
- Settlement disruption affecting merchants' cash flow
- Cross-border data flow disruption
- Anti-competitive conduct producing antitrust enforcement
- Errors in fraud-flag records propagating across cardholder financial life

**8.6 Trade-secret declarations:**
- *Algorithm internals:* Network and partner fraud-scoring algorithms. Mitigation: aggregate validation; methodology disclosure where contractually permitted; R67 floor commitments. Substantial R67 gap acknowledged.
- *Pricing and interchange formulas:* Competitive and antitrust-sensitive; partially restricted; aggregate metrics published.
- *Government coordination:* Some details restricted on diplomatic and antitrust grounds.
- *Reputation-risk deliberation:* Internal deliberation on category and merchant decisions restricted; the network acknowledges this restriction itself raises R67 concerns and commits to aggregate disclosure of reputation-risk-driven decision patterns.
- *Specific bank and merchant contracts:* Competitive; partially restricted.

R67 floor compliance challenged across multiple of the above. The network commits to floor mitigations within antitrust, competitive, and contractual constraints; substantial structural gap acknowledged.

---

## SECTION 9 — How does it end?

**9.1 Estimated dismantling time:** This question requires direct engagement.

In the formal sense, the network is a publicly-traded corporation that could be dissolved, divested, or restructured by shareholder action, regulatory action, or court order. In practice, the network's authority is structurally embedded in the global payment infrastructure in ways that no corporate dissolution alone would address; substantial transition planning would be required to maintain payment continuity for billions of cardholders and millions of merchants during any restructuring.

In the structural sense, the network's outputs (data records, rule precedents, exclusion records, standards positions) cannot be dismantled at all; they have already propagated.

For framework purposes: 60 months from formal dismantling decision to substantive cessation, given regulatory, contractual, technical, and continuity-of-payments considerations.

**9.2 Dismantling process:**
- Months 1–12: Regulatory and shareholder action; transition planning; identification of successor authority for continuing functions; international coordination
- Months 13–36: Phased operational transition; rule wind-down; technical infrastructure transition or transfer; participant relationship transition
- Months 37–48: Brand transition; standards-body role transition; pension and personnel obligations
- Months 49–60: Final accounting; entity dissolution; legacy litigation continuation

**9.3 Entrenchment factors:** Substantial.
- *Network effects:* Cardholders, issuers, acquirers, merchants are mutually locked in; transition requires coordinated action across the entire ecosystem
- *Technical infrastructure:* Tokenization, contactless, EMV chip standards represent decades of technical lock-in
- *Standards-body positions:* Standards adoption has created path-dependent infrastructure
- *Regulatory commitments:* Multi-jurisdictional regulatory commitments
- *Records propagated to cardholder and merchant histories cannot be recalled*
- *Cardholder fraud-flag records propagate across financial life regardless of network status*
- *Personnel obligations* to tens of thousands of employees
- *Pension and benefit commitments*
- *International data flow arrangements*

R61 (Anti-Entrenchment) finding acknowledged: a network of this scale is structurally entrenched in ways that exceed any corporate-level reversal capability. The framework treats this as a structural finding rather than as the network's individual failure.

**9.4 Data disposition:**
- *Personal data:* Per regulatory requirement and applicable data-protection law; archived where required; transferred to successor or destroyed per applicable law
- *Transaction records:* Per financial-services regulatory requirement (typically multi-year retention); transferred to successor or archived
- *Algorithm models and risk-scoring artifacts:* Per applicable law; transferred or destroyed; some derived outputs propagated to issuer and acquirer systems and cannot be recalled
- *Audit logs:* Per regulatory requirement
- *Brand and trademark:* Disposition per corporate dissolution

**9.5 Downstream effect reversibility:**

This section requires direct engagement.

The network's outputs have caused effects that no dismantling can reverse:

- *Categorically excluded businesses* — adult content, cannabis where state-legal, certain political organizations, certain dissident-associated transactions, certain sex worker-adjacent businesses — that lost access to formal payment infrastructure during periods of network exclusion experienced lost revenue, lost customer relationships, business closure, and in some cases criminal exposure (when forced into informal payment alternatives). Subsequent restoration, where it has occurred, does not undo the years of lost economic activity
- *Closed cardholder accounts* — cardholders whose accounts were closed for fraud-suspicion or other grounds, often without explanation or comparable appeal, may have suffered missed payments, damaged credit, lost access to services, downstream financial consequences. Closures based on erroneous determinations cannot have those years restored
- *Closed merchant accounts* — merchants whose acquiring-bank-level access was terminated under network rule pressure may have lost business, employment, and economic livelihood
- *Records of fraud flags, closures, and risk scoring* propagate to issuer and acquirer systems and to credit and risk databases that the network does not control. Affected persons cannot identify all the systems where their records have propagated
- *Generational economic effects* of differential payment-infrastructure access (across geographic regions, demographic groups, business categories) shape lifetime and intergenerational financial outcomes
- *Coordination with government pressure* (R64 findings) has produced exclusions that bypassed due-process protections that would have applied to direct government action; affected persons cannot recover the protections they would have had against government action
- *Standards-body lock-in* shapes payment-infrastructure development paths in ways that subsequent dismantling does not undo

R63 (Downstream Effect Reversibility) and R60 (Derived Authority Inheritance) apply with particular force. The network cannot reverse these effects. R65 (Propagation Duty) requires that on dismantling: (a) the network notify downstream systems that its data is no longer authoritative; (b) the network support remediation including correction processes for affected persons and businesses; (c) the network preserve records to enable historical investigation and remediation.

The framework's reversibility requirement is, for payment-network authority, a commitment to mitigate, to acknowledge, and to support remediation — not a commitment that effects can be undone. The gap between the structural authority to exclude legal businesses from the formal economy and the structural capacity to reverse exclusion effects is, for payment-network authority, among the largest of any authority type the framework registers. The fact that this gap is rarely articulated by the network or its industry counterparts does not reduce its structural reality.

**9.6 Replacement feasibility:**

R51 (Institutional Replacement Feasibility) requires that this authority be replaceable without destabilizing services beyond authorized scope.

Payment-network function *could* be replaced through alternative configurations: real-time central-bank payment systems (FedNow and equivalents); account-to-account payment networks; central-bank digital currencies; regional payment networks; cryptocurrency-based alternatives. Functional replacement is technically feasible at varying levels of maturity.

Replacement of the *specific institution* without disruption to global payment continuity is harder. Honest disclosure: the network does not maintain a current succession plan in the framework's sense. R51 substantial gap acknowledged.

**9.7 Reversibility verification:**

No formal dismantling rehearsal has been conducted. The network has continuity-of-operations planning for technical disruption but no operational practice of simulating cessation. R43 (Reversibility Verification) gap acknowledged at full scale.

The §9.1 timeline is estimated based on regulatory and operational complexity. It is not verified.

The network acknowledges that R43 applied honestly to global payment-network authority is a substantial commitment, and that the question "what would dismantling actually look like" has historically been treated as politically and operationally inadmissible rather than engaged.

---

## SECTION 10 — Authorization, renewal, and trigger declarations

**10.1 Authorizing body:** Board of Directors under [STATE] corporate law; shareholders; regulatory authorities in approximately 200 jurisdictions.

**10.2 Date of authorization:** Variable; corporate existence and operating authority predate registration. For framework purposes: [DATE] (registration date).

**10.3 Expiration date:** [EXPIRATION DATE].

**10.4 Renewal interval:** 2 years. Justification: scale, harm potential, the substantial open R26/R55/R63/R64/R67/R69 findings, and the rapid evolution of operations warrant the shorter end of SCBP-09's range. The 2-year cycle is a structural commitment beyond statutory requirement.

**10.5 Renewal evidence declaration:** [x] All five domains.

**10.6 Necessity-decay acknowledgment:** [x] Acknowledged. *Note:* The network's continued necessity depends on the continued absence of comparable alternative payment infrastructure. As real-time central-bank payment systems, central-bank digital currencies, account-to-account networks, and other alternatives mature, R62 (Necessity Decay) requires affirmative evidence that continued network authority remains necessary. Network position based on legacy network effects is not, in the framework's sense, the same as ongoing necessity.

**10.7 Aggregate trigger threshold:** 500 in 90 days. SCBP-09 §II places non-consenting affected populations >100,000,000 in the largest band (100–1,000). The network's affected population of ~4 billion is at the upper end of the largest band. The network selects 500 — at the midpoint of the largest band, recognizing scale of operations and the substantial structural concerns documented.

**10.8 Aggregate threshold justification:** Five hundred independent civic concerns about network practice in 90 days from a global affected population of this scale indicates organized structural concern.

**10.9 Response time window:** 30 days.

**10.10 Response window justification:** Not required (default).

---

## SECTION 11 — What does this authority commit to publishing?

**11.1 Citizen ledger publication:** Quarterly. Includes: aggregate operational metrics (volumes, approval rates, fraud rates by category and region); aggregate account closure and merchant termination statistics; merchant category decisions and changes; rule changes; lobbying and political activity; major regulatory positions and engagements; standards-body activity; antitrust litigation status; capture risk monitoring including duopoly-coordination disclosure; aggregate disparate-impact testing results for fraud scoring; threshold change log.

**11.2 Threshold change log:** Within 7 days of any change.

**11.3 Interpretation change log:** Continuous. Rule changes, category-decision changes, and policy memoranda affecting scope are logged.

**11.4 Renewal process visibility:** [x] Committed. Renewal review by parties drawn from affected categories: cardholders (selected to reflect global demographic and geographic composition); merchants of various scales and categories; small businesses with prior closure or category-related restriction experience; merchants in categories that have been subject to network exclusion (adult content, cannabis where state-legal, firearms, certain political organizations, certain sex-work-adjacent categories, others); financial inclusion advocates; consumer protection organizations; academic researchers in financial regulation; representatives from jurisdictions with limited alternative payment infrastructure — *not* by the network, the duopoly partner, major issuing or acquiring banks, or any party with structural alignment with the network.

**11.5 Stop event log:** [x] Acknowledged.

---

## SECTION 12 — Honesty assertions

**12.1 Disclosure completeness assertion:** [x] Asserted, with acknowledgment that several disclosures (algorithm internals, government-coordination details, specific category-decision deliberations, duopoly-coordination details, specific bank and merchant contractual terms) are partial at registration due to legal restrictions, antitrust considerations, and operational complexity. Partial-disclosure status is itself committed to be reported quarterly.

**12.2 Update obligation:** [x] Committed.

**12.3 Discoverability acknowledgment:** [x] Acknowledged.

**12.4 Burden of proof acknowledgment:** [x] Acknowledged. R69 places the burden of proving constitutional compliance on the authority. The network accepts that lack of evidence, restricted evidence, or inaccessible evidence results in non-compliance findings — and accepts that current restrictions on algorithm internals, government coordination, deliberative materials, and certain operational details produce R69 findings until those restrictions are addressed.

**12.5 Anti-weaponization acknowledgment:** [x] Acknowledged. Registration does not legitimize practices the framework's structural limits prohibit.

---

## SECTION 13 — Submitter

*[Submitter information retained by registry as metadata.]*

---

*REG-PAYMENT-PROCESSOR-EXAMPLE — worked example of a global payment network operating one of the major card-payment rails*
*Registered under the Bounded Power Framework*
*All authority governed by the Structural Constitution (SCBP-04)*
