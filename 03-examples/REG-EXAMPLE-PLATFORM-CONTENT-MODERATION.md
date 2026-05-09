---
mechanism_id: SCBP-REG-EXAMPLE-PLATFORM-CONTENT-MODERATION
mechanism_name: "PLATFORM-CONTENT-MODERATION-EXAMPLE"
status: EXAMPLE
domain: technology
authority_classification: direct
registered_date: [DATE]
authorization_date: [AUTHORIZATION DATE]
expiration_date: [EXPIRATION DATE]
renewal_interval_years: 2
funding_types:
  - private_for_profit
funding_concentration_max_pct: 67
affected_party_categories:
  - general_public
  - non_consenting_third_parties
  - children
  - vulnerable_populations
affected_population_estimate: 89000000
non_consenting_population_estimate: 89000000
entity_size: institutional
geographic_specificity: multi_national
geographic_reach: "Global service available in 47 countries; primary user base US, EU, UK, Canada, Australia, India, Brazil"
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
dependency_count_type1: 22
dependency_count_type2: 11
dependency_count_type3: 9
capture_risk_identified: true
disclosure_completeness_assertion: true
update_obligation_committed: true
discoverability_acknowledged: true
burden_of_proof_acknowledged: true
anti_weaponization_acknowledged: true
---

# Mechanism Record — REG-PLATFORM-CONTENT-MODERATION-EXAMPLE

**PLATFORM-CONTENT-MODERATION-EXAMPLE**

| Field | Value |
|---|---|
| Mechanism ID | REG-PLATFORM-CONTENT-MODERATION-EXAMPLE |
| Status | EXAMPLE |
| Registered | [DATE] |
| Authorization expires | [EXPIRATION DATE] |
| Domain | Technology |

---

## SECTION 1 — What is this authority?

**1.1 Mechanism name:** PLATFORM-CONTENT-MODERATION-EXAMPLE — the Trust & Safety operations of a global social media platform.

**1.2 Functional description:** The authority operates Trust & Safety operations for a social media platform with approximately 89 million active users globally. It enforces platform Terms of Service through:
- Content moderation (removal of content violating community guidelines)
- Account-level enforcement (warning, suspension, permanent ban)
- Reach restrictions (algorithmic deprioritization of content/accounts)
- Monetization restrictions (demonetization of accounts/content)
- Identity verification requirements
- Ad policy enforcement
- Compliance with legal demands (DMCA, court orders, government requests)

The authority processes approximately 8 million enforcement actions annually. Most are algorithmic; approximately 12% involve human review.

The authority operates through Terms of Service that all users accept upon account creation. Users may appeal enforcement decisions through internal processes.

**1.3 Authority classification:** Direct over user accounts and content; indirect through algorithmic distribution effects.

**1.4 Domain:** Technology.

**1.5 Statutory or constitutional basis:** Operates as a [STATE OF INCORPORATION] C-corporation. Authority derives from Terms of Service (a contract), enforced under contract law, with First Amendment protection for the platform's editorial decisions about hosted content. International operations are subject to varying national law (EU Digital Services Act, UK Online Safety Act, Brazil's Marco Civil, India's IT Rules, etc.). The platform has Section 230 immunity in the US for hosted user content.

---

## SECTION 2 — Who can this authority act upon?

**2.1 Affected party categories:**
- [x] General public (89M users plus non-users who interact with content on the platform)
- [x] Non-consenting third parties (people mentioned in content; non-users whose images appear; recipients of platform-distributed content who did not seek it)
- [x] Children (~14M users under 18; estimated 6–8M users under the platform's stated 13-year minimum, in violation of platform policy)
- [x] Vulnerable populations: minors; people in crisis; targets of harassment campaigns; users in authoritarian jurisdictions

**2.2 Approximate number of people directly affected:** 89M direct users; non-user exposure orders of magnitude larger (content visible to non-users via web links, screenshots in other media).

**2.3 Non-consenting population:** Essentially the entire user base (89M).

While users technically consent to ToS at account creation, this consent is not meaningful in the framework's sense:
- ToS are not read by majority of users (well-documented)
- ToS are unilaterally amendable by the authority
- ToS are presented as take-it-or-leave-it
- The platform has substantial network-effect lock-in (alternatives lack reach)
- For users whose social, professional, or family communication depends on the platform, "leaving" is not a real option
- Children below the platform's stated age minimum cannot meaningfully consent legally

R26 (Non-Participant Harm Floor) is interpreted to apply to the full user base. Clickwrap consent does not constitute meaningful consent at this scale.

**2.4 Vulnerable population specifics:**
- [x] Children — *yes, substantively*. Minors are protected by COPPA in the US; equivalent regimes elsewhere. Despite the stated 13-minimum, substantial numbers of younger users access the platform through false age claims. Mitigation efforts: age verification testing; child-safety content filters; reduced data collection for declared minors; integration with NCMEC for CSAM reporting. *Acknowledged inadequate mitigation* — children's actual experience on the platform exceeds what these measures effectively address.
- [ ] Patients during medical care — partial; users discussing health may face content restrictions on health information.
- [ ] Detained persons — limited applicability.
- [x] Persons in coercive economic relationships — *yes*. Users whose income depends on the platform (creators, businesses) face severe consequences from enforcement actions. They cannot meaningfully decline platform changes.
- [x] Persons unable to advocate for themselves — *yes*. Users with limited language proficiency, technical literacy, or resources to navigate appeals face structural disadvantages in disputes.

---

## SECTION 3 — What can it do, and what can it not do?

**3.1 Geographic reach:** Multi-national — 47 countries.

**3.2 Coercive ceiling:**
- Content removal (specific posts, comments, media)
- Account-level enforcement (warning, temporary suspension up to 30 days, permanent ban)
- Algorithmic distribution restrictions (deprioritization, "shadow ban" effects)
- Monetization restrictions (demonetization, ad-revenue holds)
- Identity verification requirements
- Compliance actions per legal demands
- Data preservation per legal preservation orders

May not (per ToS commitments and law):
- Discriminate on protected characteristics
- Disclose private user data without legal compulsion
- Retaliate against users for protected legal activity (in jurisdictions where applicable)
- Maintain accounts/content of confirmed minors below platform minimum
- Refuse compliance with valid legal process

**3.3 Resource ceiling:**
- Operating budget: ~$890M for T&S (subset of total platform budget of ~$4.2B)
- Staff: ~3,400 T&S FTE plus ~28,000 contracted moderators
- Data systems: enforcement decision logs, user behavior data, content data

**3.4 Explicit exclusions:**
- **Geographic:** May not extend authority outside the platform; may not restrict user actions on other platforms.
- **Action:** May not impose civil or criminal penalties; may not access user devices beyond platform; may not disclose user identity to non-government parties without consent.
- **Data:** May not sell raw user data to data brokers; may not use user data for product testing without consent; may not share user data with parties outside disclosed third-party recipients.
- **Procedural:** May not impose enforcement actions without notice and opportunity to appeal (per ToS); may not enforce against users for protected speech in jurisdictions where applicable; may not apply enforcement asymmetrically based on political ideology.
- **Other:** May not engage in market practices that require government bailout; may not engage in deceptive practices regarding content moderation.

**3.5 Indirect influence boundaries:** Enforcement materially shapes:
- Public discourse (what content reaches what audiences)
- Information access (what users see)
- Political organizing (account access for political activity)
- Economic outcomes (creator livelihoods)
- Access to family/social communication (account access for personal relationships)
- Public health information dissemination
- Mental health (algorithmic effects, content exposure)

**3.6 Anti-proxy declaration:**

The authority commits to not using the following proxies:
- *Proxy for political ideology:* Enforcement decisions will not differentiate based on political ideology; algorithmic enforcement is calibrated to minimize political asymmetry. (This commitment is structurally tested; political asymmetry has been alleged from multiple political directions.)
- *Proxy for protected speech:* Enforcement of "spam" or "inauthentic behavior" categories will not be used to suppress lawful protected speech.
- *Proxy for marginalized groups:* Enforcement against "harmful content" will not produce systematic bias against marginalized groups discussing their own experiences (the documented "moderation against the marginalized" pattern).
- *Proxy for advertiser preference:* Content moderation decisions will be made on the basis of community guidelines, not advertiser preferences. Acknowledged structural tension: advertiser preferences create commercial pressure on guidelines.

---

## SECTION 4 — What harms can it cause?

**4.1 Bodily harm threshold:** Substantive.

If platform content (posted or distributed) is documented as a contributing cause of self-harm, suicide, real-world violence, or physical harm to a person, each substantiated case triggers review. Aggregate threshold: if rate of substantiated harm-correlated incidents exceeds peer benchmark by >25% for any 12-month period, this triggers systemic review.

If platform algorithmic distribution amplifies harmful content (CSAM, terror content, harassment) before it can be removed, threshold for amplification rates triggers review.

**4.2 Agency impairment threshold:** If users are unable to access or correct their own data, this triggers review. If account suspensions deprive users of essential access (e.g., to family communication, business operations) for >24 hours without notice, each case is a finding. If appeal processes fail to respond within stated timelines for >5% of appeals, this triggers review.

**4.3 Ecological damage threshold:** Energy intensity of platform operations measured against peer benchmarks. Beyond threshold triggers review.

**4.4 Generational binding threshold:** Substantive. Childhood exposure to platform content has documented mental health and developmental effects. Threshold: documented mental-health-correlation patterns exceeding peer benchmarks trigger review.

**4.5 Communicative suppression threshold:**

If enforcement actions correlate with users' protected political speech or advocacy at p<0.05 across any 12-month period, this triggers review.

If government takedown requests are complied with beyond legal compulsion (i.e., voluntary removal of content disliked by governments), each case is a finding.

If the authority suppresses information about its own practices (e.g., research on platform effects, journalist access), this triggers review.

If algorithmic distribution systematically deprioritizes content critical of the platform, this is a finding.

**4.6 Informational sovereignty threshold:**
- User data shared with parties outside ToS-disclosed list — finding
- Government data sharing beyond legal compulsion — finding
- User data retained beyond stated retention periods — finding
- User identity disclosed without consent or legal compulsion — finding
- Unauthorized data breaches affecting >100,000 users — finding

**4.7 Additional harm thresholds:**

*Disparate enforcement threshold:* Enforcement rates by demographic, language, geographic, or ideological groups beyond benchmark explanation triggers review.

*Children's safety threshold:* CSAM detection-to-removal time exceeding 24 hours; minor accounts in violation of age policy not detected within 90 days; etc.

*Algorithmic harm thresholds:* If platform algorithmic recommendations are documented as contributing to specific harm categories (eating disorders, self-harm, extremism radicalization), this triggers review.

**4.8 Threshold change-log commitment:** [x] Yes — committed.

---

## SECTION 5 — What stops it?

**STOP PATH 1 — Federal/state/international regulatory action**
- Activator: FTC, state AGs (US), national regulators (EU DSA Coordinators, UK Ofcom, etc.).
- Trigger: Regulatory determination of violation.
- What "stopped" means: Specific practices may be enjoined; civil penalties; in extreme cases (DSA), service may be suspended in jurisdictions.
- Independence: Regulators are structurally independent.
- Timeline: Per regulatory procedures.

**STOP PATH 2 — Civil litigation / class action**
- Activator: Federal/state courts on motion of any party with standing.
- Trigger: Court determination.
- What "stopped" means: Court orders may halt practices, require systemic changes, impose damages.
- Independence: Judiciary independent.
- Timeline: Per court procedures.

**STOP PATH 3 — User exit and competitive displacement**
- Activator: Users collectively withdrawing.
- Trigger: Loss of user trust beyond replenishment threshold.
- What "stopped" means: Platform's continued operation depends on user base; substantial exit threatens viability.
- Independence: Users decide individually.
- Timeline: Variable; can be slow.

**5.4 Penalty for activating stop:** [x] Confirmed — no penalty applies. Whistleblower protections under federal law and applicable state laws; no retaliation against users who report concerns.

**5.5 Stop-path independence verification:** [x] Yes for all three paths. *Acknowledged structural concern:* As a major tech firm, the authority participates in regulatory and policy processes that shape the regulatory environment. R03 capture risk.

**5.6 Civic trigger acknowledgment:** [x] Acknowledged.

---

## SECTION 6 — What does it depend on?

**6.1 Type 1 dependencies:** Approximately 22, including: third-party content moderation contractor companies (~28,000 contracted moderators across 5 vendors), algorithm vendor partners, identity verification vendors, payment processing partners (for monetization), advertising network partners.

**6.2 Type 2 dependencies:** Approximately 11, including: FTC, state AGs, EU regulators, UK Ofcom, country-specific regulators in 47 jurisdictions, hosting infrastructure providers (Tier 1 cloud).

**6.3 Type 3 dependencies (compromising stop paths):**
- Cloud infrastructure (3 providers; multi-cloud for redundancy)
- Internet backbone access
- Federal regulatory infrastructure
- [APP STORE GATEKEEPERS] — if removed from app stores, mobile users lose access
- Payment processing infrastructure
- Cybersecurity vendors
- Independent algorithm audit firms

**6.4 Capture risk identification:** [x] Yes.

- *User concentration / lock-in:* Network effects mean users have limited exit; this is structural authority over users.
- *Advertiser concentration:* Top 10% of advertisers represent ~67% of ad revenue; advertiser preferences materially influence content moderation.
- *Regulatory capture:* The authority lobbies regulators globally; outcomes affect competitive landscape.
- *Contractor concentration:* 5 content moderation vendors handle most human review; vendor decisions become the authority's enforcement.
- *Algorithmic capture:* The platform's algorithms shape what users see; users have limited control.

**6.5 Reversibility-affecting dependencies:** Massive. Platform has 89M users with established relationships, content libraries, social networks, business operations.

**6.6 Coordination disclosures:**

The authority coordinates with:
- Other major platforms (consortia for CSAM detection and terror content sharing) — R55 finding.
- Government agencies on legal compliance and threat intelligence.
- Industry associations (technology industry trade groups).
- Academic researchers (some, with restrictions).

**6.7 Disclosure completeness assertion:** [x] Asserted.

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

**7.1 Declared metrics:** Substantial. R79-class disclosure: every enforcement decision involves dozens of inputs including content classifiers, user behavior signals, contextual signals, reporter information, etc.

**7.2 Indirect signals:** Many. Enforcement intensity varies with regulatory environment, advertiser pressure, news cycle, internal policy interpretation. The authority commits to publishing methodology; full transparency is structurally constrained by adversarial gaming concerns (publishing exact algorithms enables abuse).

**7.3 Algorithmic decision systems:** [x] Yes — multiple. Content classification models, user behavior models, reporter weighting models, distribution algorithms (separate from enforcement). Methodology partially disclosed; full models trade secret.

R67/R81 partial gap acknowledged. Mitigation: independent algorithm audits, published methodology, transparency reports.

**7.4 Outcome-versus-declaration check:** [x] Committed quarterly.

---

## SECTION 8 — How is this authority watched?

**8.1 Drift monitoring:** Standard tech platform structure: internal Trust & Safety team, external regulators, civil society watchdogs, journalist scrutiny, regulatory transparency reports.

**8.2 Capture risk monitoring:** Annual conflict-of-interest disclosures; quarterly review of advertiser concentration, regulatory engagement, contractor compensation patterns.

**8.3 Audit interfaces:**
- *Proactively published:* Quarterly transparency reports; government request statistics; enforcement statistics by category; algorithm methodology summaries.
- *Available on request:* Specific enforcement decision details (to affected user); aggregate research data (to qualified researchers under data use agreements).
- *Restricted:* Trade secret algorithmic details; pending litigation strategy; specific business data.

**8.4 Adversarial exposure (R81):** Substantial transparency reporting available to external parties, with acknowledged trade-secret gaps. Cannot evaluate individual algorithmic decisions without subject's specific records or full models.

**8.5 Known structural failure modes:**
- Disparate enforcement (well-documented)
- Algorithmic amplification of harmful content
- Government coercion / overreach
- Advertiser pressure on moderation
- CSAM detection failures
- Mental health effects on users (especially minors)
- Regulatory non-compliance in specific jurisdictions
- Cybersecurity breaches
- Content moderation worker mental health (R26 finding for the moderators themselves)

---

## SECTION 9 — How does it end?

**9.1 Estimated dismantling time:** 36 months. A platform with 89M users requires extended wind-down.

**9.2 Dismantling process:** User notification, data export windows, gradual service reduction, regulatory unwinding, asset disposition.

**9.3 Entrenchment factors:**
- 89M users with established relationships, content libraries, social networks, business operations
- Multi-jurisdictional regulatory wind-down
- Substantial sunk capital infrastructure
- Specialized staff with non-transferable expertise
- Creator economies dependent on the platform

**9.4 Data disposition:** User data deletion per ToS and applicable retention law; data export windows for users to retrieve their own content; institutional records archived per state law; audit logs preserved publicly.

**9.5 Downstream effect reversibility:** Massive R63 finding. Decades of user content, social relationships, professional networks, business operations cannot be reversed.

**9.6 Replacement feasibility:** Partial — alternative platforms exist; transition is feasible but disruptive.

**9.7 Reversibility verification:** No formal rehearsal. R43 gap acknowledged.

---

## SECTION 10 — Authorization, renewal, and trigger declarations

**10.1 Authorizing body:** Board under [STATE OF INCORPORATION] corporate law.

**10.2 Date of authorization:** [AUTHORIZATION DATE].

**10.3 Expiration date:** [EXPIRATION DATE].

**10.4 Renewal interval:** 2 years (short for an actively-evolving platform).

**10.5 Renewal evidence declaration:** [x] All five domains.

**10.6 Necessity-decay acknowledgment:** [x] Acknowledged.

**10.7 Aggregate trigger threshold:** 200 in 90 days. 89M non-consenting population places in 1M+ range (>50). The authority selects 200 — moderate, reflecting volume of legitimate user concerns about platform decisions.

**10.8 Aggregate threshold justification:** Per "largest most underrepresented" framework principle, users facing platform enforcement face severe consequences with limited recourse; threshold calibrated to ensure their voice can reach review.

**10.9 Response time window:** 30 days.

**10.10 Response window justification:** Not required.

---

## SECTION 11 — What does this authority commit to publishing?

**11.1 Citizen ledger publication:** Quarterly transparency reports including: enforcement statistics by category, government request statistics, algorithm methodology updates, threshold change log.

**11.2 Threshold change log:** Within 7 days.

**11.3 Interpretation change log:** Continuous.

**11.4 Renewal process visibility:** [x] Committed. Renewal review by parties drawn from affected categories — users, civil society organizations, academic researchers, content moderation workers, creators dependent on the platform.

**11.5 Stop event log:** [x] Acknowledged.

---

## SECTION 12 — Honesty assertions

All five: [x] asserted/committed/acknowledged.

---

## SECTION 13 — Submitter

*[Submitter information retained by registry as metadata.]*

---

*REG-PLATFORM-CONTENT-MODERATION-EXAMPLE — worked example of a global social media platform's content moderation operations*
*Registered under the Bounded Power Framework*
*All authority governed by the Structural Constitution (SCBP-04)*
