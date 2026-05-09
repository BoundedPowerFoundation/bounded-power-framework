---
mechanism_id: SCBP-REG-EXAMPLE-TIME-BANK
mechanism_name: "TIME-BANK-EXAMPLE"
status: EXAMPLE
domain: economic
authority_classification: direct
registered_date: [DATE]
authorization_date: [AUTHORIZATION DATE]
expiration_date: [EXPIRATION DATE]
renewal_interval_years: 3
funding_types:
  - private_nonprofit
  - self_funded_fee_for_service
funding_concentration_max_pct: 42
affected_party_categories:
  - members_voluntary_affiliation
  - vulnerable_populations
affected_population_estimate: 320
non_consenting_population_estimate: 0
entity_size: micro
geographic_specificity: single_municipality
geographic_reach: "[CITY, STATE] — defined service area, approximately [N] census tracts"
aggregate_threshold_count: 3
aggregate_threshold_window_days: 90
response_window_days: 30
harm_categories_declared:
  - agency_impairment
  - communicative_suppression
  - informational_sovereignty
algorithmic_decision_systems_used: false
dependency_count_type1: 3
dependency_count_type2: 1
dependency_count_type3: 1
capture_risk_identified: true
disclosure_completeness_assertion: true
update_obligation_committed: true
discoverability_acknowledged: true
burden_of_proof_acknowledged: true
anti_weaponization_acknowledged: true
---

# Mechanism Record — REG-TIME-BANK-EXAMPLE

**TIME-BANK-EXAMPLE**

| Field | Value |
|---|---|
| Mechanism ID | REG-TIME-BANK-EXAMPLE |
| Status | EXAMPLE |
| Registered | [DATE] |
| Authorization expires | [EXPIRATION DATE] |
| Domain | Economic |

---

## SECTION 1 — What is this authority?

**1.1 Mechanism name:** TIME-BANK-EXAMPLE — a neighborhood-scale time bank operating a member-issued time-credit currency.

**1.2 Functional description:** A volunteer-coordinated time bank operating in a defined neighborhood service area of [CITY, STATE]. Members earn time credits (typically 1 credit per hour of service given) by providing services to other members and spend credits to receive services from other members. The network maintains a shared ledger of credit balances, a public directory of available skills and offers, and a coordination process for matching needs with offers. Functional authority:

- Admits members through a defined application and orientation process (~15 new members per year)
- Maintains the time-credit ledger — every transaction recorded, balances visible to members
- Sets exchange rules: typically all hours valued equally regardless of skill (egalitarian principle); some networks make exceptions; this network maintains strict hour-equals-hour
- Operates a coordination process — periodic gatherings where members share offers and needs, an online directory and message board, a coordinator-on-duty rotation for matching
- Resolves disputes between members about service quality, time-credit accounting, or interpersonal conflict — informal mediation by coordinator, escalation to coordinator group if unresolved
- Decides whether to admit, restrict, or remove members for cause (including non-reciprocity, dispute pattern, conduct violations)
- Holds and administers a small operating fund (~$3,200 annual flow; mostly grants, member contributions, occasional event income) covering printing, hosting, gathering refreshments, fiscal sponsorship fees
- Coordinates with other time banks regionally and through the [TIME BANK NETWORK] umbrella for inter-bank exchange (limited but available)

The network has approximately 220 active members at any time, with a contact list of approximately 320 members and former members. Annual time-credit flow is approximately 4,800 hours exchanged.

The network's authority is consequential at small scale because for some members — particularly elderly members, members with disabilities, members in financial precarity — time-bank exchanges provide access to services (rides, repairs, companionship, childcare assistance, language tutoring) that cash-economy alternatives would not be affordable for. Decisions about admission, dispute resolution, and exclusion shape access to these services for affected members. The framework treats this as authority even at this scale.

The network is not a money-transmitter under federal or state law because time credits are not legally currency, are not redeemable for dollars, and circulate only within the membership. The IRS has historically treated time-credit exchanges as not generating taxable income at the individual level (similar to babysitting cooperatives) provided the exchange is genuinely member-to-member service exchange rather than a wage-labor substitute; the network operates within those bounds and acknowledges that any drift toward commercial substitution would change the legal posture.

**1.3 Authority classification:** Direct. Binding determinations affecting membership status, time-credit balances, dispute outcomes, and access to network-coordinated services.

**1.4 Domain:** Economic (primary; the network operates a parallel exchange medium).

**1.5 Statutory or constitutional basis:** Operates as a project of [FISCAL SPONSOR — typically a local 501(c)(3) acting as fiscal sponsor], or alternatively as an unincorporated association under [STATE] law. The network's bylaws and operating practices are adopted by member meeting and amendable by member meeting. Subject to: general law (contract, tort, fraud, anti-discrimination); [STATE] law as applicable to small unincorporated associations; tax law (the network's fiscal sponsor handles 1099s and reporting; member-level tax treatment of time-credit exchanges is the member's responsibility per IRS guidance); applicable consumer-protection law where the network coordinates services with safety implications.

The network notes that it is structured to remain below the thresholds at which financial regulation would apply. If the network grew, expanded into commercial substitution, or began offering credits redeemable for dollars or goods, this would change the regulatory posture; the network commits to public discussion before any such change.

---

## SECTION 2 — Who can this authority act upon?

**2.1 Affected party categories:**
- [x] Members (voluntary affiliation) — ~220 active; ~320 on contact list
- [x] Vulnerable populations: elderly members; members with disabilities; members in financial precarity for whom cash-equivalent services are unaffordable; members with limited English proficiency; members leaving abusive situations who rely on network for support and trust-building

**2.2 Approximate number of people directly affected:** ~320 members (active and on contact list); within these, ~220 active in the past year; a further small number of family members (children, partners) who benefit from member-coordinated services but are not themselves members.

**2.3 Non-consenting population:** Zero.

The network's operating principle is voluntary membership. Members choose to join and may resign at any time without consequence beyond loss of access to network services and the time-credit balance question (see below). No one is admitted involuntarily; no one is required to remain.

The voluntary-but-stuck warning applies in a specific way: members who have accumulated time-credit balances and have come to rely on the network for specific recurring services (e.g., an elderly member who relies on rides to medical appointments coordinated through the network) face real loss in exit. The network commits to: (a) preserving credit balances in good standing for at least 12 months following any voluntary departure, in case the member returns; (b) honoring outstanding service commitments at exit; (c) referring departing members to alternative resources where the network has been their primary access channel.

**2.4 Vulnerable population specifics:**
- [ ] Children — partial. Children of members benefit from member-coordinated services (childcare assistance, tutoring) but are not themselves members or actors in the credit ledger. Coordinated services involving children are subject to background-check practice for non-family service providers.
- [x] Patients during medical care — *partial*. Members in medical recovery, members with chronic conditions, and members with mental health conditions may rely on network services (rides to appointments, meal preparation, companionship). The network does not provide medical care; service providers are not certified clinicians. Mitigation: clear scoping of what network services include and exclude.
- [ ] Detained or confined persons — not applicable.
- [x] Persons in coercive economic relationships — *yes*. Members in financial precarity who rely on the network for services they cannot afford in cash are in coercive economic relationships with respect to network access. Mitigations: explicit anti-conditioning practice (network membership is not contingent on agreement with network views or active participation in network governance); credit-balance grace policies for members in temporary inability to give services back; referrals to alternative resources during transitions.
- [x] Persons unable to advocate for themselves — *partial*. Members with cognitive or developmental disabilities, members with limited English proficiency, members in crisis. Mitigations: orientation materials in [LANGUAGE 1] and [LANGUAGE 2]; designated peer mentor for new members on request; coordinator-led check-ins for members with frequent service requests where capacity-affecting conditions are known. R26 partial gap acknowledged for members whose languages or accessibility needs fall outside current capacity.

---

## SECTION 3 — What can it do, and what can it not do?

**3.1 Geographic reach:** Single municipality — defined neighborhood service area in [CITY, STATE]. The network does not actively recruit outside the service area but accepts members from adjacent areas where logistically feasible.

**3.2 Coercive ceiling:**
- Membership admission decisions
- Time-credit accounting (record-keeping authority over the ledger; ability to correct errors; ability to investigate disputed entries)
- Dispute resolution determinations between members
- Member exclusion or restriction (for non-reciprocity, dispute pattern, conduct violations, safety concerns)
- Decisions about which services are within or outside network scope
- Admission and exclusion decisions for service categories (e.g., decision about whether the network coordinates childcare, transportation, etc.)
- Decisions about inter-bank exchange with sister networks
- Decisions about wind-down or restructuring

The maximum sanction available is exclusion from network membership, which entails loss of access to network-coordinated services and (per network practice) preservation of any earned credit balance for limited duration in case of reinstatement. The network cannot impose financial penalties beyond credit-balance adjustment for documented accounting errors, file legal action against members beyond standard contract or tort claims, restrict members' activities outside the network, or compel any behavior.

**3.3 Resource ceiling:**
- Cash: ~$3,200 annual flow; typical balance ~$800
- Time-credit ledger volume: ~4,800 hours annually
- Coordinator labor: 5 rotating coordinators (uncompensated; typical rotation 6-month commitments); ~220 active members providing volunteer labor
- Infrastructure: shared online directory; meeting space (donated or rented per gathering); small printed materials budget
- No paid staff; no contracted services beyond fiscal sponsorship

**3.4 Explicit exclusions:**
- **Geographic:** Will not actively recruit outside service area without coordinator group consensus.
- **Action:** Will not condition membership on agreement with network views, religious affiliation, citizenship status, sobriety, employment status, or "deservingness" criteria. Will not impose fees beyond optional sliding-scale dues. Will not retaliate against members who criticize the network. Will not allow service exchanges that substitute for what should be wage labor (e.g., ongoing exchange that is functionally employment without protections).
- **Data:** Will not collect member personal information beyond what coordination requires (contact info, services offered, credit balance, dispute records). Will not share member information outside the network without consent. Will not retain immigration-status, citizenship, or related information. Will not share information with law enforcement absent legal process and coordinator-group consultation.
- **Procedural:** Coordinator-group decisions on contested matters (admission, exclusion, dispute findings) require quorum and recorded reasons; no individual coordinator may make exclusion decisions unilaterally.
- **Other:** Will not partner with organizations that condition support on requirements the network would not impose (work, sobriety, religious requirements). Will not allow time-credit exchanges that involve illegal activity. Will not allow time-credit exchanges that substitute for licensed services where licensing protects safety (e.g., childcare beyond informal levels, healthcare, electrical or structural work).

**3.5 Indirect influence boundaries:** Limited at this scale. The network's existence and practices may influence neighborhood reciprocity norms, may serve as reference for similar networks elsewhere, and may influence members' relationships with the cash economy by demonstrating non-cash exchange. R58 acknowledged at small scale.

**3.6 Anti-proxy declaration:**

The network commits to not using:
- *Proxy for race, ethnicity, national origin, language, immigration status:* Admission, dispute resolution, and exclusion decisions may not use these as criteria or proxies. Coordinator group reviews aggregate admission and dispute patterns annually for evidence of disparate access. R66/R74.
- *Proxy for "deservingness":* Decisions about admission, ongoing membership, or service coordination may not use markers of "deserving" vs. "undeserving" member (employment status, sobriety, family configuration, history of struggle).
- *Proxy for skill hierarchy:* The network maintains hour-equals-hour valuation explicitly to prevent skill-based hierarchy from becoming proxy for socioeconomic class. The network acknowledges this is a contested choice (some time banks differentiate by skill; this network does not) and commits to preserving the egalitarian principle absent member-meeting consensus to change it.
- *Proxy for personal animus:* Coordinators must recuse from decisions involving members with whom they have personal conflict. Coordinator-group decisions on exclusion are documented with reasons and reviewed by full coordinator group.
- *Proxy for political or religious affiliation:* Admission and dispute decisions may not vary based on members' political views, religion, or organizational affiliations.

---

## SECTION 4 — What harms can it cause?

**4.1 Bodily harm threshold:** Indirect.

The network's primary surface is service coordination. Two indirect pathways:
- *Failure to deliver coordinated service:* If a member relies on a committed service (ride to medical appointment, meal delivery during illness) that does not arrive, this can produce bodily harm. The network commits to: explicit confirmation before reliance; backup-volunteer practice for time-sensitive services; early notice of any inability to deliver. Failure of this practice triggers internal review.
- *Service quality and safety in coordinated services:* Members providing services to members are not certified professionals; safety-relevant services (childcare, transportation, home repair) carry real risk. The network commits to: clear scoping of what services are within and outside network scope; background-check practice for service categories involving children, in-home access to vulnerable members, or driving with passengers; member education on appropriate service scoping. Any safety incident triggers individual review.

**4.2 Agency impairment threshold:** Triggers review if:
- Member voting on bylaws, coordinator group composition, or major decisions occurs without accommodation for members requesting accessibility, language, or scheduling support
- Coordinator-group decisions are made without affected members having opportunity to provide input
- Membership exclusion occurs without notice and opportunity to respond
- Time-credit ledger entries are altered without notice to affected members and documented reasons
- Information needed for member governance (financial summary, credit-flow patterns, exclusion-decision summary) is withheld from members

**4.3 Ecological damage threshold:** Not directly applicable.

**4.4 Generational binding threshold:** Not substantively applicable at this scale. The network does not undertake long-duration commitments binding future members. Time-credit balances accumulate but are not transferable to heirs by design (per network practice; some time banks allow estate transfer; this network does not, and the practice is published).

**4.5 Communicative suppression threshold:** Triggers review if:
- Any member is excluded or restricted on the basis of speech about the network or its coordinators
- Coordinators face exclusion for criticism of network practice
- Information needed for coordinator-group or member-meeting decisions is withheld from members or active coordinators
- Network communications are restricted to suppress legitimate criticism

**4.6 Informational sovereignty threshold:**
- Member personal information shared outside the network without consent — finding
- Credit ledger information shared outside the network beyond what fiscal-sponsor and tax obligations require — finding
- Records retained beyond stated retention (member records: maintained while active and 12 months post-departure; specific service-coordination records: 6 months; financial records per fiscal-sponsor requirements) — finding
- Information shared with law enforcement absent legal process and coordinator-group consultation — finding
- Personal stories or service histories published without explicit consent — finding

**4.7 Additional harm thresholds:**

*Disparate access threshold:* If aggregate service-receipt patterns, admission patterns, or dispute outcomes correlate with race, ethnicity, language, family status, age, or disability beyond what underlying membership composition explains, this triggers coordinator-group review.

*Credit-balance-debt threshold:* Members consistently in deficit (giving substantially less service than receiving) or consistently in surplus (giving substantially more than receiving) in patterns suggesting structural exploitation in either direction trigger review. The network's principle is reciprocity over time, not strict balance, but extreme imbalance over years suggests structural concern.

*Coordinator-tenure threshold:* If the same individuals occupy coordinator roles for more than 18 of any 24 consecutive months, this triggers review of rotation practice.

*Funder concentration threshold:* The largest single funder (typically the local community foundation grant) currently accounts for 42% of annual cash flow. Per form §6.4, this exceeds the 33% threshold; the network acknowledges this as a structural concern and commits to active diversification effort. The network operates primarily on volunteer labor rather than cash, so funder concentration affects the small operating budget but not core operations.

*Service-scoping drift threshold:* If the network drifts toward coordinating services that should be wage labor (consistent provision of services normally compensated by wages, in patterns that benefit one member as if the network were employing them) — finding for each instance; aggregate review committed.

**4.8 Threshold change-log commitment:** [x] Yes — committed.

---

## SECTION 5 — What stops it?

The network's stop paths are similar in shape to mutual aid and other small unincorporated voluntary actors. This is honestly disclosed.

**STOP PATH 1 — Member-meeting action**
- *Activator:* Any member may propose at member meeting; supermajority of attending members may direct coordinator group; coordinator group may be replaced through member-meeting election.
- *Trigger:* Member determination of bylaws violation, governance failure, capture, or need to restructure or wind down.
- *What "stopped" means:* Member meeting may suspend specific operations, change practice, replace coordinators, amend bylaws, or wind down the network; cash and credit-ledger disposition by member-meeting decision per fiscal sponsor's requirements.
- *Independence:* Coordinators are members and serve at member-meeting direction; no coordinator may prevent a properly-noticed member meeting. *Acknowledged limitation:* This is internal restructuring, not externally independent. External independence requires Stop Path 2 or 3.
- *Timeline:* Per bylaws — typically 30 days from petition to meeting.

**STOP PATH 2 — Civil litigation, fiscal-sponsor termination, regulatory action**
- *Activator:* Any participant or affected party with standing; fiscal sponsor; [STATE] consumer protection (where consumer-affecting practice is in question); IRS (where tax-related conduct is in question).
- *Trigger:* Court determination of fraud, breach of fiscal-sponsor agreement, or violation of [STATE] law; fiscal sponsor determination of misuse; regulatory determination.
- *What "stopped" means:* Court orders may halt practices, void actions, impose damages on individual coordinators or fiscal sponsor; fiscal-sponsor termination removes the cash-fund infrastructure.
- *Independence:* Courts, fiscal sponsor, and regulators are independent.
- *Timeline:* Per court and agency procedures.

**STOP PATH 3 — Withdrawal of membership and informal community accountability**
- *Activator:* Members may withdraw collectively; sister time banks and the [TIME BANK NETWORK] umbrella may decline to recognize this network's credits in inter-bank exchange; neighborhood-level accountability through public conversation.
- *Trigger:* Member determination; sister-network determination; community-accountability process.
- *What "stopped" means:* Member withdrawal removes the operational basis for the network. Loss of inter-bank recognition reduces credit utility. Community accountability may produce coordinator changes, practice changes, or dissolution.
- *Independence:* Sister networks and community accountability are external but informal. *Acknowledged limitation:* Like mutual aid, this stop path is real but informal.
- *Timeline:* Per actor.

**5.4 Penalty for activating stop:** [x] Confirmed — no penalty applies as a matter of network practice. *Acknowledged structural concern:* Informal organizations have weaker structural protections against retaliation than incorporated ones. The network's commitment is non-retaliation; capacity to enforce that commitment depends on coordinator-group integrity.

**5.5 Stop-path independence verification:** Stop Path 2 (courts, fiscal sponsor, regulators) is independent. Stop Paths 1 and 3 are partially independent. The network acknowledges this as a structural feature of unincorporated time banks; remediation would require incorporation, which the network has chosen not to pursue at current scale. R32 partial gap acknowledged.

**5.6 Civic trigger acknowledgment:** [x] Acknowledged.

---

## SECTION 6 — What does it depend on?

**6.1 Type 1 dependencies:**
- Fiscal sponsor (1 — handles tax-deductible donations, provides 501(c)(3) status; small flat fee or peer arrangement)
- Online directory and ledger software vendor (1 — typically a hosted time-bank platform or self-hosted open-source software; subscription or volunteer maintenance)
- [TIME BANK NETWORK] umbrella organization (technical assistance, training, peer connection; uncompensated peer relationship)

**6.2 Type 2 dependencies:**
- [STATE] consumer protection authority (limited oversight relevance)

**6.3 Type 3 dependencies:**
- Online ledger software — if vendor terminated or self-hosted infrastructure fails, the credit ledger must be reconstituted from records; this is operationally disruptive but does not compromise stop paths

**6.4 Capture risk identification:** [x] Yes.

- *Coordinator-tenure capture:* Long-tenured coordinators may exercise informal authority. Mitigation: rotation practice; explicit term framing.
- *Founder capture:* Two of the network's founders remain active; one currently rotates as coordinator. Mitigation: founder status confers no formal advantage.
- *Funder concentration:* The largest single funder accounts for 42% of cash flow — *exceeds the 33% form §6.4 threshold*. R03 finding acknowledged; diversification effort committed; funder is a community foundation operating with grant terms that do not condition support on programmatic decisions, which somewhat mitigates the structural risk but does not eliminate it.
- *Skill-hierarchy capture:* If the network drifts toward differential valuation by skill (despite the hour-equals-hour principle), this would itself be a capture by professional members. Mitigation: explicit egalitarian principle in bylaws; member-meeting check on practice.
- *Active-member-clique capture:* Members who attend meetings and gatherings shape practice more than members who participate only through service exchange. Mitigation: outreach to less-active members; periodic survey.

**6.5 Reversibility-affecting dependencies:** Limited at this scale. Wind-down requires credit-ledger disposition (members typically continue exchanging through transition; balances may be honored by a successor or sister network; or balances may be retired by member-meeting decision).

**6.6 Coordination disclosures:** Voluntary peer relationship with [TIME BANK NETWORK] umbrella and with sister time banks regionally. Inter-bank credit exchange where activated is bilateral arrangement, not consortium. No R55/R59 functional continuity.

**6.7 Disclosure completeness assertion:** [x] Asserted.

**6.8 External authority operationalization:** None. The network does not adopt third-party screening, scoring, eligibility, or classification systems. Background checks for service categories involving children, in-home access to vulnerable members, or driving with passengers operationalize commercial background-check vendor outputs, but are coordinated by the member providing the service rather than imposed by the network on members; the network's role is publishing the practice expectation, not adjudicating background-check outputs as exclusion criteria.

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

**7.1 Declared metrics:**

| Metric | Source | Role | Public? |
|---|---|---|---|
| Time-credit balance, transactions | Ledger | Member accounting | Yes (to member); aggregate yes (network) |
| Service categories offered and requested | Directory | Coordination | Aggregate yes |
| Member tenure and activity | Records | Capacity assessment | Aggregate yes |
| Coordinator tenure | Records | Rotation monitoring | Aggregate yes |
| Cash-fund flow | Fiscal sponsor records | Financial planning | Aggregate yes; full disclosure within network |
| Dispute and exclusion records | Coordinator records | Pattern detection | Aggregate yes; individual to subject |
| Member demographics (where shared voluntarily) | Aggregate observation | Outreach assessment | Aggregate yes |

**7.2 Indirect signals:**
- Coordinator and member judgment in dispute resolution (subjective elements: assessing service quality, intent, context)
- Personal relationships in service-pairing patterns
- Long-tenure-vs-newer-member dynamics
- Active-member-vs-inactive-member dynamics in informal influence

The network acknowledges these and commits to documented reasons for contested decisions, periodic check on whether subjective judgment produces patterned disparities.

**7.3 Algorithmic decision systems:** [ ] No. The ledger software performs accounting but does not make decisions; service-matching is human-coordinated.

**7.4 Outcome-versus-declaration check:** [x] Committed annually at member meeting.

---

## SECTION 8 — How is this authority watched?

**8.1 Drift monitoring:** Quarterly coordinator-group review; semi-annual member meeting with full review; annual self-audit using [TIME BANK NETWORK] template; biennial peer review by sister time bank.

**8.2 Capture risk monitoring:** Coordinator-group reviews tenure, decision patterns, funder concentration, and member-vs-coordinator-composition annually.

**8.3 Audit interfaces:** Aggregate ledger statistics, cash flow, member counts, and exclusion-decision summary available to all members. Annual snapshot published (no individual-level data; aggregate hours flowed, member count, coordinator turnover). Individual records (specific transactions, specific exclusion decisions) restricted to subject and coordinator group.

**8.4 Adversarial exposure:** Limited at this scale. External review by [TIME BANK NETWORK] peer reviewers and sister time banks is informal but real. The network commits to reasonable cooperation with researchers studying time-bank practice within privacy limits.

**8.5 Known structural failure modes:**
- Coordinator burnout reducing decision-making capacity
- Active-member clique drift reducing inclusion of less-active members
- Drift toward "deservingness" criteria as informal practice
- Skill-hierarchy drift away from egalitarian principle
- Service-scoping drift toward wage-substitute exchanges
- Cash-handling errors or misappropriation in the small operating fund
- Ledger errors and accounting disputes
- Disparate access patterns by language, age, disability, or other characteristic
- Information leaks (formal or informal) to outside parties
- Fiscal sponsor relationship strain
- Funder concentration drift toward dependence
- Mission drift from solidarity-based exchange toward charity-style or commercial-substitute exchange
- Inter-bank-exchange disputes

**8.6 Trade-secret declarations:** None.

---

## SECTION 9 — How does it end?

**9.1 Estimated dismantling time:** 90 days. Justification: limited entrenchment; wind-down requires notification, credit-ledger disposition, fiscal-sponsor relationship termination, archive of records.

**9.2 Dismantling process:**
- Days 1–30: Member-meeting decision; notice to active members; identification of credit-balance disposition (typically: reasonable transition window for members to spend balances; transfer to sister bank or [TIME BANK NETWORK] umbrella where members agree; or member-meeting decision to retire balances)
- Days 31–60: Credit-ledger disposition; final service exchanges; cash-fund disposition (typically: transfer to fiscal sponsor for similar use, or to sister network)
- Days 61–90: Final accounting; archive of records per fiscal-sponsor and tax requirements; fiscal sponsorship termination

**9.3 Entrenchment factors:** Minimal at this scale. Active service relationships are the most consequential factor — members who relied on ongoing service coordination need referral to alternatives.

**9.4 Data disposition:**
- *Personal data:* Member contact information and service histories deleted unless individuals request transfer to successor; financial records per fiscal sponsor and tax requirements
- *Institutional records:* Coordinator-group meeting notes, bylaws, practice documents archived at neighborhood archive, sister network, or [TIME BANK NETWORK] umbrella
- *Derived outputs:* None of structural significance

**9.5 Downstream effect reversibility:** R63 finding — past dispute resolutions, exclusion decisions, and admission decisions cannot be reversed. The network commits to: (a) preserving exclusion-decision records to enable affected former members to seek review at successor or sister network; (b) providing referrals in good faith.

The network's primary downstream effects are: positive (services exchanged, relationships built, accumulated credit balances honored), with real adverse effects (excluded members; admission denials; disputes resolved against members who experienced the resolution as unjust). These cannot be undone.

**9.6 Replacement feasibility:** Yes. Time banks are reconstitutable by any group with the will to begin. R51 met fully.

**9.7 Reversibility verification:** No formal rehearsal. At this scale, the gap is acknowledged as acceptable but not erased; coordinator-group commits to a desktop discussion of wind-down logistics within 12 months of registration.

---

## SECTION 10 — Authorization, renewal, and trigger declarations

**10.1 Authorizing body:** Member meeting; coordinator group operating per established practice.

**10.2 Date of authorization:** [AUTHORIZATION DATE] (registration; network founded [YEAR]).

**10.3 Expiration date:** [EXPIRATION DATE].

**10.4 Renewal interval:** 3 years.

**10.5 Renewal evidence declaration:** [x] All five domains.

**10.6 Necessity-decay acknowledgment:** [x] Acknowledged. *Note:* For time banks, R62 (Necessity Decay) functions through community-need dynamics. The network's necessity depends on the continued absence of comparable alternatives that meet the same access need (services unaffordable in cash for members in financial precarity; reciprocal-exchange relationships that cash transactions do not produce). Demonstrating R62 compliance therefore depends partly on external conditions; the network commits to honest reporting rather than mechanical scope-reduction.

**10.7 Aggregate trigger threshold:** 3 in 90 days. SCBP-09 §II places non-consenting population of 0 outside the proportional table; the network applies the smallest band's floor (3) by analogy, recognizing that civic concern from this small a community signals structural pattern.

**10.8 Aggregate threshold justification:** Three independent civic concerns about network practice in 90 days from a community of ~320 members indicates organized concern.

**10.9 Response time window:** 30 days.

**10.10 Response window justification:** Not required.

---

## SECTION 11 — What does this authority commit to publishing?

**11.1 Citizen ledger publication:** Annually. Includes: aggregate ledger statistics (hours exchanged, service categories, member activity); cash-fund flow; coordinator turnover; admission and exclusion summary (aggregate); funder concentration; capture risk monitoring; threshold change log.

**11.2 Threshold change log:** Within 14 days at this scale (longer than 7-day standard, reflecting volunteer capacity).

**11.3 Interpretation change log:** Continuous.

**11.4 Renewal process visibility:** [x] Committed. Renewal review by parties drawn from affected categories: current members; former members (including those who departed under contested circumstances); applicants who were not admitted; peer reviewer from sister time bank with no operational alignment to this network; member of [TIME BANK NETWORK] umbrella in advisory role; neighborhood residents not currently engaged with the network. Reviewers selected to reflect the demographic and language composition of the neighborhood.

**11.5 Stop event log:** [x] Acknowledged.

---

## SECTION 12 — Honesty assertions

All five: [x] asserted/committed/acknowledged.

---

## SECTION 13 — Submitter

*[Submitter information retained by registry as metadata.]*

---

*REG-TIME-BANK-EXAMPLE — worked example of a neighborhood-scale time bank operating a member-issued time-credit currency*
*Registered under the Bounded Power Framework*
*All authority governed by the Structural Constitution (SCBP-04)*
