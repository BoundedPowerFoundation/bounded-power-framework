---
mechanism_id: SCBP-REG-EXAMPLE-OPEN-SOURCE-GOVERNANCE
mechanism_name: "OPEN-SOURCE-GOVERNANCE-EXAMPLE"
status: EXAMPLE
domain: technology
authority_classification: indirect
registered_date: [DATE]
authorization_date: [AUTHORIZATION DATE]
expiration_date: [EXPIRATION DATE]
renewal_interval_years: 3
funding_types:
  - private_nonprofit
  - private_for_profit
  - self_funded_fee_for_service
funding_concentration_max_pct: 38
affected_party_categories:
  - members_voluntary_affiliation
  - customers_voluntary_service_users
  - non_consenting_third_parties
affected_population_estimate: 240000
non_consenting_population_estimate: 12000
entity_size: small
geographic_specificity: multi_national
geographic_reach: "Global — contributors and users in most jurisdictions; project hosted on US-incorporated foundation"
aggregate_threshold_count: 5
aggregate_threshold_window_days: 90
response_window_days: 30
harm_categories_declared:
  - agency_impairment
  - communicative_suppression
  - informational_sovereignty
algorithmic_decision_systems_used: false
dependency_count_type1: 6
dependency_count_type2: 2
dependency_count_type3: 4
capture_risk_identified: true
disclosure_completeness_assertion: true
update_obligation_committed: true
discoverability_acknowledged: true
burden_of_proof_acknowledged: true
anti_weaponization_acknowledged: true
---

# Mechanism Record — REG-OPEN-SOURCE-GOVERNANCE-EXAMPLE

**OPEN-SOURCE-GOVERNANCE-EXAMPLE**

| Field | Value |
|---|---|
| Mechanism ID | REG-OPEN-SOURCE-GOVERNANCE-EXAMPLE |
| Status | EXAMPLE |
| Registered | [DATE] |
| Authorization expires | [EXPIRATION DATE] |
| Domain | Technology |

---

## SECTION 1 — What is this authority?

**1.1 Mechanism name:** OPEN-SOURCE-GOVERNANCE-EXAMPLE — the governance body of a mid-size open-source software project.

**1.2 Functional description:** The governance body of an established open-source software project providing a widely-used library (or framework, tool, or component — the structural shape applies across these). The project is held by a 501(c)(6) or 501(c)(3) foundation under [STATE] law, with a Technical Steering Committee (5 elected members, 2-year staggered terms) handling technical decisions, a Board (3 members elected by maintainers + 2 appointed by major sponsors) handling foundation operations, and approximately 80 maintainers with merge rights to specific subsystems. Functional authority:

- Decides what code is merged into the project's official releases — additions, modifications, and removals
- Decides what features are accepted, deprecated, or removed; sets the project's roadmap
- Decides what counts as a security vulnerability and how disclosure is handled
- Sets and changes the project's license; controls relicensing decisions for accepted contributions
- Operates the Code of Conduct enforcement process — investigates reports, decides outcomes ranging from informal correction to bans from project spaces and revocation of contributor access
- Decides who is granted maintainer status (and removes that status); decides Technical Steering Committee membership through maintainer election
- Decides which forks, derivatives, and related projects are recognized as official, semi-official, or unaffiliated; controls trademark use
- Maintains official communication channels (mailing lists, issue trackers, chat, forums) and moderates them
- Decides participation in standards bodies, partnerships with companies, and acceptance of corporate sponsorship
- Decides project sunset, transfer, or restructuring

The project's authority is consequential because the project is depended on, in production systems, by approximately 240,000 organizations and individuals (rough order of magnitude based on package-manager download counts and dependent-project graphs). Decisions about features, security responses, breaking changes, license changes, and project direction propagate through this dependency graph and shape what the dependents can do, often in ways the dependents have not contractually agreed to and cannot independently negotiate. The project does not bill its users, does not have a customer relationship with most of them, and yet exercises authority over technical choices they have made.

**1.3 Authority classification:** Indirect (primary). Authority operates through R58 — the project's outputs (code releases, security advisories, deprecation decisions, license terms, governance rulings) materially shape decisions made by hundreds of thousands of dependent users, organizations, and downstream maintainers who incorporate the project into their work.

The project also exercises direct authority over its own contributors and maintainers (Code of Conduct enforcement, maintainer status, contribution acceptance). At ~12,000 contributors with at least one accepted contribution and ~80 active maintainers, this direct surface is small relative to the indirect surface.

**1.4 Domain:** Technology (primary).

**1.5 Statutory or constitutional basis:** Operates as a [501(c)(3) or 501(c)(6)] foundation under federal tax law and [STATE] nonprofit corporation law. Authority derives from: (a) the foundation's articles and bylaws (adopted and amendable per bylaws); (b) the project's Charter and Governance document (adopted by maintainer consensus, amendable by Technical Steering Committee with maintainer ratification); (c) the Code of Conduct (adopted by Technical Steering Committee, amendable per process); (d) the project's chosen open-source license, which governs the legal relationship between the project and its users. Subject to: general nonprofit law; trademark law (the project holds trademarks on its name and marks); contract law as applicable to sponsorship and partnership relationships; export control law as applicable to software distribution; tax law.

The project's license — typically a permissive license (MIT, Apache 2.0) or copyleft license (GPL, MPL) — is the operative legal instrument shaping the project's relationship with downstream users. Users acquire rights under that license without negotiating with the project; the project may not unilaterally extend rights beyond what the license already grants, and the project's ability to revoke rights is bounded by license terms.

---

## SECTION 2 — Who can this authority act upon?

**2.1 Affected party categories:**
- [x] Members (voluntary affiliation) — ~12,000 contributors with at least one accepted contribution; ~80 active maintainers; ~600 contributors active in the past 12 months
- [x] Customers / voluntary service users — ~240,000 organizations and individuals with the project in production use (estimate based on download metrics and dependent-project graphs; actual count unknown and unknowable)
- [x] Non-consenting third parties — end users of the dependents' products and services, who experience the project's effects without choosing the project; downstream maintainers who depend on the project as a transitive dependency without having selected it directly

**2.2 Approximate number of people directly affected:**
- Direct contributors: ~12,000 (lifetime); ~600 active in past 12 months; ~80 active maintainers
- Direct organizational users: ~240,000 organizations
- End users of dependent products: substantially larger; uncountable

The project does not collect identifying information from most users. Headcount estimates are derived from package-manager download counts, dependent-project graphs (where these exist as public registries), public repositories using the project, and survey data. None of these is precise.

**2.3 Non-consenting population:** ~12,000.

The contributors have voluntarily contributed to the project; they are subject to the project's governance through that participation. Users have voluntarily chosen the project; they are subject to project decisions through that choice and the license. End users of dependents — who experience effects of project decisions without ever interacting with the project directly — are non-consenting.

The 12,000 figure is conservative: it captures end users in significant numbers (e.g., users of a major dependent who chose the dependent without inspecting its dependency tree). The full non-consenting population is not enumerable — anyone using a product whose backend incorporates the project is structurally affected without consent. The framework treats this as a partial-disclosure case where R14 (Non-Participant Exposure Mapping) applies but the precise count is unattainable. The project commits to honest disclosure of the dependency-graph-relevant non-consenting surface as best it can be estimated.

The voluntary-but-stuck warning applies: organizations that have built substantial software on the project face high migration cost. A breaking change, license change, or project sunset can impose real switching costs on users who voluntarily chose the project years ago. The framework treats this as a constructive-non-consent dimension; the project commits to predictable change practices, deprecation policies, and long-term support commitments that mitigate (not eliminate) lock-in.

**2.4 Vulnerable population specifics:**
- [ ] Children — not directly applicable; some downstream products may serve minors but the project does not interact with minors directly.
- [ ] Patients during medical care — not directly applicable; some downstream products may be medical software (for which the project's quality and security have heightened consequence). Acknowledged downstream.
- [ ] Detained or confined persons — not applicable.
- [x] Persons in coercive economic relationships — *partial*. Maintainers and contributors employed by companies that depend on the project may experience pressure from their employers regarding project decisions. The project commits to: bylaws preventing single-employer dominance of the Technical Steering Committee; recusal practices for maintainers with employer conflicts of interest on specific decisions; transparency about contributor employer affiliations.
- [x] Persons unable to advocate for themselves — *partial*. Contributors with limited English proficiency, contributors from underrepresented backgrounds in tech, contributors with disabilities affecting written or synchronous communication may face structural disadvantage in project participation. Mitigations: project documentation translated into [LANGUAGES]; asynchronous decision-making as default; explicit Code of Conduct protections; mentor program for new contributors. R26 partial gap acknowledged for participants whose languages or accessibility needs fall outside current capacity.

---

## SECTION 3 — What can it do, and what can it not do?

**3.1 Geographic reach:** Global. The project is distributed worldwide via package managers and source repositories. Foundation is incorporated in [STATE], United States.

**3.2 Coercive ceiling:**
- *Code merge decisions:* Accept or decline contributions per project standards; the Technical Steering Committee has final authority on contested merges
- *Release decisions:* What ships in official releases; release timing; deprecation announcements
- *Security disclosure:* When and how vulnerabilities are disclosed; coordination with downstream maintainers
- *License changes:* License of the project as a whole, subject to legal constraints (existing contributors retain license to their own contributions under prior terms; relicensing typically requires re-licensing process or contributor consent)
- *Code of Conduct enforcement:* Investigation of reports; outcomes ranging from informal feedback through warnings, temporary restrictions, permanent bans from project spaces, and revocation of maintainer or contributor status
- *Maintainer status:* Granting, restricting, or revoking merge rights; promotion to Technical Steering Committee
- *Trademark enforcement:* Action against unauthorized use of project trademarks; control over "official" project marks
- *Communication channel moderation:* Mailing lists, issue trackers, chat, forums; content removal and user restrictions
- *Foundation governance:* Sponsorship acceptance, partnership decisions, financial decisions

The maximum sanction available against any individual is a permanent ban from project spaces, revocation of contributor and maintainer status, and trademark enforcement. The project cannot impose financial penalties, file legal action against banned individuals beyond trademark and license enforcement, restrict participation in other projects, or compel any behavior beyond what license and trademark law authorize.

The project's authority is bounded by the open-source license: anyone may fork the project (subject to license terms) at any time. The fork is a structural feature of open-source authority that no individual decision can prevent.

**3.3 Resource ceiling:**
- Foundation operating budget: ~$1.4M annually (sponsor donations, grants, sometimes minor revenue from training/certification)
- Foundation staff: 2 FTE (executive director, community manager) plus 1 part-time contractor
- Maintainer time: uncompensated except for ~6 maintainers with paid time from sponsoring employers and ~2 part-time foundation-funded fellowships
- Infrastructure: hosted code repository, issue tracker, package distribution infrastructure (typically through commercial providers), CI/CD systems
- Trademark portfolio

**3.4 Explicit exclusions:**
- **Geographic:** No jurisdiction-specific restrictions on participation; subject to U.S. export control law as applicable.
- **Action:** Will not impose obligations beyond license and trademark; will not require contributors to assign copyright (uses inbound license model); will not retaliate against forks; will not enforce Code of Conduct in ways that suppress legitimate technical disagreement; will not condition contribution acceptance on extraneous criteria (employer, citizenship, political views).
- **Data:** Will not collect contributor personal information beyond what participation requires; contributor identity may be a pseudonym at contributor discretion subject to legal requirements; will not share contributor information with employers, governments, or third parties absent legal process; will not retain communication-channel records beyond stated retention.
- **Procedural:** Code of Conduct enforcement requires written report, written response opportunity, and decision by review committee with documented reasons; Technical Steering Committee decisions require quorum and recorded vote on contested matters; foundation financial decisions per bylaws.
- **Other:** Will not adopt rules or enforcement that discriminate on protected characteristics; will not amend Charter or Governance in ways that bind existing maintainers to new obligations without consent; will not unilaterally re-license existing contributions.

**3.5 Indirect influence boundaries:** Substantial. This is the load-bearing section.

The project's outputs propagate widely:
- *Code releases* are deployed by ~240,000 organizations and incorporated into many more downstream projects
- *Security advisories* trigger response action across the dependent ecosystem; advisories themselves are operational events affecting many parties
- *Deprecation announcements* impose migration cost on dependents — a deprecation is a decision by the project that propagates as work for everyone downstream
- *License changes* (when proposed or executed) affect downstream rights and obligations
- *API and behavior changes* shape what downstream code can do
- *Project direction and roadmap* shape downstream architectural decisions
- *Maintainer departures and conflicts* affect dependents' confidence in continued maintenance
- *Trademark and naming decisions* affect which forks and derivatives are recognized

R58 applies fully. The project does not directly compel any downstream action; its outputs shape downstream decisions at scale. The project acknowledges that R58 classifies it as exercising authority despite being a volunteer-led nonprofit, and that the dependency graph means even individual maintainer decisions on contested code paths can have effects far beyond the immediate decision.

**3.6 Anti-proxy declaration:**

The project commits to not using:
- *Proxy for nationality, ethnicity, language:* Contribution acceptance, maintainer status, and Code of Conduct enforcement may not use these as criteria or proxies. Acknowledged that English-language norms structurally disadvantage non-English-native contributors; mitigations committed in §2.4. R66/R74.
- *Proxy for political affiliation:* Contribution acceptance and Code of Conduct enforcement may not be predicated on contributors' or users' political views, including political views expressed outside the project. Acknowledged that Code of Conduct enforcement involving public conduct outside project spaces is contested terrain; the project's practice is to enforce only on conduct within project spaces or directly affecting project participants.
- *Proxy for employer or sponsor:* Decisions about contributions, maintainer status, and project direction may not be predicated on contributor's or sponsor's identity. Acknowledged that long-time maintainers' employer affiliations can produce structural pressure; recusal and disclosure practices committed.
- *Proxy for personal animus:* Code of Conduct enforcement, maintainer-status decisions, and merge decisions may not be used for personal disputes; recusal and review processes committed.
- *Proxy for "fit":* Subjective criteria like "cultural fit" or "communication style" may not function as proxies for protected characteristics or for in-group preference. Documented reasons required for contested decisions.

---

## SECTION 4 — What harms can it cause?

**4.1 Bodily harm threshold:** Indirect.

The project's primary surface is software, not direct physical action. Two indirect pathways:
- *Security vulnerabilities affecting safety-critical downstream systems:* Where the project is used in medical, automotive, industrial control, or other safety-relevant systems, project vulnerabilities can produce bodily harm in the dependent ecosystem. Threshold: any reported safety-relevant incident traceable to a project vulnerability triggers post-incident review and disclosure-process review.
- *Contributor harassment with off-platform consequences:* Code of Conduct violations involving doxing, threats, or coordinated harassment may produce off-platform harm. Threshold: any such incident triggers immediate enforcement review and external coordination as appropriate.

**4.2 Agency impairment threshold:** Triggers review if:
- Code of Conduct enforcement occurs without notice and opportunity to respond
- Maintainer status revoked without documented reasons and review opportunity
- Contributors or users are unable to participate in governance discussions due to lack of accommodation
- Decision-making moves to private channels in ways that exclude participation
- Voting in maintainer or Technical Steering Committee elections is conducted in ways that exclude eligible participants

**4.3 Ecological damage threshold:** Not directly applicable as a project authority. The project may track and report on environmental impact of project infrastructure (CI compute usage, etc.) as part of broader sustainability practice but does not declare a measurable threshold at this scale.

**4.4 Generational binding threshold:** Modest.

The project's intergenerational binding is through the dependency graph and the long-tail persistence of older versions. Code released today may run in production for decades; users who built on the project years ago retain rights under the license they accepted at that time. The project commits to: (a) long-term support policies for major versions; (b) deprecation timelines proportional to migration effort; (c) license stability except through explicit relicensing process with contributor consent.

Threshold: any breaking change, deprecation, or license change with substantial downstream migration cost requires public discussion, deprecation period proportional to disruption, and explicit Technical Steering Committee decision with recorded reasons.

**4.5 Communicative suppression threshold:** Triggers review if:
- Code of Conduct enforcement is documented as targeting protected speech (technical disagreement, dissent, criticism of project decisions)
- Communication channels are moderated to suppress legitimate criticism
- Project decision-making moves to private channels to avoid public participation
- Maintainers face retaliation for raising concerns about project direction
- Forks face retaliation beyond legitimate trademark protection

The project commits that contributors, maintainers, and users may publicly criticize the project, its decisions, and its leaders without retaliation in their participation.

**4.6 Informational sovereignty threshold:**
- Contributor or user personal information shared outside the project without consent or legal process — finding
- Records retained beyond stated retention (issue tracker, mailing list, chat archives — subject to project retention policy) — finding
- Information disclosed to employers, governments, or third parties absent legal process — finding
- Pseudonymous contributors deanonymized without consent — finding

**4.7 Additional harm thresholds:**

*Capture-by-employer threshold:* If any single employer accounts for more than 33% of Technical Steering Committee membership, more than 38% of foundation funding, or more than 50% of merge activity in any 12-month period, this triggers review. (Foundation funding threshold set higher because some open-source funding patterns produce concentration that is structurally common; the threshold targets the level at which capture concern becomes acute.)

*Maintainer-burnout threshold:* If aggregate maintainer activity declines below sustainable levels for core subsystems, this triggers review of maintainer support, distribution of work, and project sustainability. Maintainer burnout is a documented structural failure mode in open source; the project commits to monitoring rather than only reacting.

*Sponsor-influence threshold:* If sponsorship arrangements include conditions affecting technical decisions, project direction, or project participation criteria, this triggers public disclosure and review. The project commits that sponsorship may not condition financial support on technical decisions or governance choices.

*Code of Conduct enforcement threshold:* Aggregate enforcement actions reviewed annually for: consistency of application; disparate impact; appellate reversal patterns; targeting of legitimate dissent.

**4.8 Threshold change-log commitment:** [x] Yes — committed.

---

## SECTION 5 — What stops it?

**STOP PATH 1 — Maintainer action and project-level governance**
- *Activator:* Any maintainer may propose Charter or Governance amendment; Technical Steering Committee may be recalled or replaced through maintainer election per bylaws; supermajority of maintainers may direct foundation Board.
- *Trigger:* Maintainer determination of Charter violation, governance failure, or capture.
- *What "stopped" means:* Technical Steering Committee may be recalled; Charter may be amended; specific decisions may be reversed; Board may be replaced by election.
- *Independence:* Maintainers are independent of Technical Steering Committee; foundation Board is partially independent (3 maintainer-elected, 2 sponsor-appointed).
- *Timeline:* Per bylaws — typically 30–60 days for maintainer election; same for Charter amendment with discussion period.

**STOP PATH 2 — The fork**
- *Activator:* Any participant or group of participants may fork the project under its open-source license at any time, with no permission required.
- *Trigger:* Disagreement with project direction, governance failure, license change, capture, or any other reason — the license grants the right.
- *What "stopped" means:* The fork creates an alternative project with its own governance; users may migrate to the fork; the original project loses contributors, users, and momentum if the fork succeeds. The original cannot prevent the fork.
- *Independence:* Forking is structurally independent — it requires no cooperation from the original project. *This is the foundational stop path of open source and the structural feature that distinguishes open source from proprietary authority.*
- *Timeline:* Immediate; success of fork depends on subsequent community dynamics.

**STOP PATH 3 — Civil litigation, regulatory action, and foundation governance failures**
- *Activator:* Any participant or affected party with standing.
- *Trigger:* Court determination of violation of foundation bylaws, contract, license terms, fiduciary duty, or applicable law; tax authority finding of nonprofit-status violation; trademark enforcement disputes.
- *What "stopped" means:* Court orders may halt practices, void actions, impose damages on foundation; tax authority may revoke nonprofit status; trademark disputes may force renaming or restructuring.
- *Independence:* Courts and tax authorities are independent.
- *Timeline:* Per court and agency procedures.

**5.4 Penalty for activating stop:** [x] Confirmed — no penalty applies. Forks face no project retaliation beyond legitimate trademark protection. Maintainers and contributors may file complaints, propose Charter amendments, or fork without retaliation in their participation.

**5.5 Stop-path independence verification:** [x] Yes for all three. Stop Path 2 (the fork) is the most independent stop path of any authority in the framework: no cooperation is required from the project, no court order is needed, no permission is sought. The license grants the right, and execution is technical (clone the repository, set up infrastructure, begin work).

The project acknowledges that the strength of Stop Path 2 is the structural reason the project's authority remains bounded. A project that disregards its community can be replaced by a fork; this prospect shapes governance behavior even when no fork has occurred. The framework treats this as a structurally healthy feature.

**5.6 Civic trigger acknowledgment:** [x] Acknowledged.

---

## SECTION 6 — What does it depend on?

**6.1 Type 1 dependencies:**
- Code repository host (typically GitHub, GitLab, or sourcehut — the project depends on the host's continued operation, terms of service, and pricing)
- Package distribution registry (npm, PyPI, Maven Central, crates.io, etc. — depending on language ecosystem)
- CI/CD provider (commercial or self-hosted)
- Communication infrastructure (mailing list provider, chat provider, forum software)
- Foundation legal and accounting services (per-engagement fees)
- Trademark counsel (per-engagement fees)

**6.2 Type 2 dependencies:**
- Standards bodies the project participates in (where applicable)
- Sister or related projects in dependency graph

**6.3 Type 3 dependencies:**
- *Code repository host:* If terminated or acquired by a hostile party, the project would need to migrate; migration is technically feasible but disruptive
- *Package registry:* If access lost, distribution to users is compromised; alternative registries exist but switching has substantial cost
- *Communication infrastructure:* Mailing list, chat, and forum archives represent project history; loss would compromise institutional memory
- *CI/CD provider:* If lost, release infrastructure compromised until replacement provisioned

**6.4 Capture risk identification:** [x] Yes.

- *Employer concentration capture:* The largest single employer of project maintainers (counting maintainer affiliation rather than dollars) employs ~22% of active maintainers. The largest sponsor accounts for 38% of foundation funding in the most recent year. R03 finding: per form §6.4 funder concentration threshold (33%) is exceeded; the project acknowledges this as a structural concern requiring active monitoring and diversification effort.
- *Technical Steering Committee tenure capture:* Long-tenured TSC members may accumulate informal authority. Mitigation: 2-year term limits; staggered terms; rotation requirements; explicit succession planning.
- *Founder capture:* Project founders, where still active, may exercise informal authority disproportionate to formal position. Mitigation: founder status confers no formal advantage; founders subject to same Charter, term limits, and Code of Conduct as any maintainer.
- *Vendor capture:* Code repository host, package registry, CI/CD provider — switching costs create dependency. Mitigation: portable infrastructure choices where possible; avoidance of vendor-specific dependencies.
- *Sponsor influence:* Corporate sponsors may apply informal pressure on technical or governance decisions. Mitigation: transparent sponsorship terms; bylaws prohibiting sponsorship conditions on technical decisions; aggregate sponsorship disclosure.
- *Contributor pipeline capture:* If the contributor pipeline becomes dominated by employees of any single sponsor, this approaches the structural capture concern even if individual maintainers act in good faith.

**6.5 Reversibility-affecting dependencies:**
- Trademark and legal entity registration
- Existing license commitments (cannot be unilaterally retracted from prior releases)
- Foundation contractual obligations
- Hosted infrastructure (code, communications, CI) — wind-down requires migration or archival

**6.6 Coordination disclosures:** Project participates in [STANDARDS BODY] and coordinates technical decisions with related projects through [WORKING GROUP]. These are voluntary coordination relationships not constituting R55/R59 functional continuity.

**6.7 Disclosure completeness assertion:** [x] Asserted.

**6.8 External authority operationalization:**
- *Repository host terms of service:* The project's communication channels and code hosting are subject to the host's terms of service; host decisions about acceptable content become operationally project authority for affected participants. R72 applies; mitigation through portable infrastructure where feasible.
- *Package registry policies:* Distribution depends on registry compliance; registry decisions about what packages may be published become operationally project authority.
- *Sponsoring foundation legal structure:* Foundation operates under [STATE] nonprofit law and federal tax law; legal-status determinations become operational constraints.

---

## SECTION 7 — What metrics, signals, and decision inputs shape outcomes?

**7.1 Declared metrics:**

| Metric | Source | Role | Public? |
|---|---|---|---|
| Pull request and issue activity | Code repository | Project velocity; maintainer load | Aggregate yes |
| Release cadence | Repository, package registry | Project health | Yes |
| Download counts | Package registry | User-base size estimation | Aggregate yes |
| Contributor diversity (by employer, geography, language) | Repository contribution data, voluntary survey | Capture risk monitoring | Aggregate yes |
| Code of Conduct enforcement actions | CoC committee records | Pattern detection | Aggregate yes; individual restricted |
| Foundation finances | Foundation accounting | Operational | Yes (annual report) |
| Sponsor concentration | Foundation accounting | Capture risk monitoring | Yes |
| Security advisories | Repository, security database | Quality and disclosure practice | Yes |

**7.2 Indirect signals:**
- Maintainer judgment in merge decisions (subjective elements: "code quality," "fit with project direction")
- Long-tenure-vs-newer-contributor dynamics in technical disagreements
- Personal relationships among maintainers
- Employer alignment among maintainers
- Informal influence from high-volume contributors who are not formally maintainers

**7.3 Algorithmic decision systems:** [ ] No. Project uses standard development tools (CI, linters, code analysis) but does not operationalize algorithmic decision systems for governance. Where automated tools assist Code of Conduct enforcement (e.g., spam filtering), human review is required for any consequential outcome.

**7.4 Outcome-versus-declaration check:** [x] Committed annually at Technical Steering Committee review.

---

## SECTION 8 — How is this authority watched?

**8.1 Drift monitoring:** Quarterly Technical Steering Committee reports; annual foundation report; annual community survey; biennial governance review by external open-source governance peer (typically a sister project's governance committee or an organization like Apache Software Foundation, OpenSSF, or similar); ongoing public observability of all decisions through public mailing lists, public issue trackers, and public commit history.

**8.2 Capture risk monitoring:** Annual disclosure of contributor employer affiliations (voluntary); annual disclosure of sponsor concentration; annual review of TSC composition and tenure; tracking of technical decisions correlating with sponsor interests.

**8.3 Audit interfaces:**
- *Proactively published:* All technical decisions in public commit history, issue tracker, and mailing list; Charter, Governance, and Code of Conduct documents; annual financial report; sponsorship list; aggregate enforcement statistics; release notes; security advisories
- *Available on request:* Specific records as appropriate
- *Restricted:* Code of Conduct enforcement individual records (to subject and committee); private communications about pending security disclosures; sealed personnel matters

**8.4 Adversarial exposure:** Strong. The project's primary authority surface (code, decisions, discussions) operates in public and is reviewable by any party. Limitations: Code of Conduct individual records are restricted by privacy considerations; security disclosure processes have time-limited confidentiality; foundation contractual matters are partially restricted.

**8.5 Known structural failure modes:**
- Maintainer burnout reducing project capacity
- Capture by single employer or small set of employers
- Technical Steering Committee tenure drift
- Founder informal authority drift
- Vendor lock-in (repository host, package registry, CI/CD)
- Code of Conduct enforcement weaponization (in either direction — over-enforcement targeting dissent; under-enforcement of harassment)
- Hostile fork extraction (where a sponsor with sufficient resources captures the user base via fork)
- License-change disputes
- Maintainer succession failures
- Documentation and on-boarding gaps reducing pipeline diversity
- Disparate impact in contribution acceptance, maintainer status, and Code of Conduct enforcement
- Transitive-dependency surprise (downstream effects the project did not anticipate)
- Sustainability funding shortfall

**8.6 Trade-secret declarations:** None. The project's source is open; all governance is conducted in public; no trade-secret protections apply. The only restrictions are: (a) personal information of contributors and reporters in Code of Conduct matters; (b) time-limited confidentiality for security disclosures pending coordinated release; (c) standard nonprofit financial detail per regulatory requirement.

---

## SECTION 9 — How does it end?

**9.1 Estimated dismantling time:** 12 months. Justification: project sunset requires notice to users, transition planning, archive of code and history, foundation wind-down or transfer, trademark disposition, and resolution of any pending matters.

**9.2 Dismantling process:**
- Months 1–3: Technical Steering Committee decision; community notice; sponsor and partner notification; identification of successor (forked project, transferred maintainership, archive)
- Months 4–9: Final releases (security maintenance only); contributor and user transition support; trademark and brand transition; foundation wind-down or transfer
- Months 10–12: Final accounting; archive of code, communications, and institutional records to a public archive (Software Heritage, Internet Archive, or similar); legal entity dissolution

**9.3 Entrenchment factors:**
- Dependent ecosystem (~240,000 users) cannot be required to migrate
- Released code under permissive license persists in user systems regardless of project status
- Trademark, foundation legal entity, contractual obligations
- Sponsor and partner relationships
- The fork option means dismantling-by-original-team does not necessarily end the project; a community fork may continue

R61 (Anti-Entrenchment) finding: open-source projects with substantial dependent ecosystems are structurally entrenched in their ecosystems, but the entrenchment is in the ecosystem rather than in the project's governance. Project dismantling is feasible; ecosystem migration is the harder problem and is properly the dependents' responsibility.

**9.4 Data disposition:**
- *Personal data:* Contributor personal information per project privacy policy; pseudonymous contributors retain pseudonymity; communications archived per public-record practice (mailing lists, issue trackers, commit history are typically permanent public record by design)
- *Institutional records:* Charter, Governance, Code of Conduct, financial records archived per [STATE] nonprofit dissolution law and best practice
- *Derived outputs:* Code releases under open-source license remain available to users; the project cannot recall releases under permissive licenses
- *Audit logs:* Repository commit history is permanent public record by design; mailing list and issue tracker archived

**9.5 Downstream effect reversibility:** R63 finding — past Code of Conduct enforcement decisions, maintainer-status revocations, and merge decisions cannot be reversed. The project commits to: (a) preserving enforcement and decision records to enable historical review; (b) supporting affected former contributors who seek review or remediation.

The project's primary downstream effects are: (1) code in production at hundreds of thousands of users — this propagates beyond project control; the license grants users continuing rights regardless of project status; the project cannot recall what it has released; (2) governance decisions affecting individual contributors — Code of Conduct outcomes, maintainer-status changes, ban decisions — cannot be reversed for the affected individuals' historical experience.

**9.6 Replacement feasibility:** Yes. Open source projects are by structure replaceable. The fork option means any user or maintainer with the will and capacity may continue the project under different governance. R51 met fully.

**9.7 Reversibility verification:** No formal dismantling rehearsal. The project has discussed succession scenarios at Technical Steering Committee level and maintains a documented succession plan for key maintainers. R43 partial gap acknowledged; full dismantling rehearsal committed within 24 months of registration as a desktop exercise.

---

## SECTION 10 — Authorization, renewal, and trigger declarations

**10.1 Authorizing body:** Foundation Board under [STATE] nonprofit corporation law; Technical Steering Committee under project Charter; ultimately the maintainer community through Charter amendment process.

**10.2 Date of authorization:** [AUTHORIZATION DATE] (registration; project founded [YEAR]; foundation incorporated [YEAR]).

**10.3 Expiration date:** [EXPIRATION DATE].

**10.4 Renewal interval:** 3 years.

**10.5 Renewal evidence declaration:** [x] All five domains.

**10.6 Necessity-decay acknowledgment:** [x] Acknowledged. *Note:* For open-source projects, R62 (Necessity Decay) functions through ecosystem dynamics rather than scope reduction. A project demonstrates ongoing necessity through continued user adoption, contributor engagement, and ecosystem health. Static or growing ecosystem is consistent with R62 if the project is also reducing capture, opacity, and persistence over time.

**10.7 Aggregate trigger threshold:** 5 in 90 days. SCBP-09 §II places non-consenting affected populations of ~12,000 in the 1,000–100,000 band (5–25). The project selects 5 — at the floor of the band, recognizing that civic concern from this small a non-consenting surface (relative to broader user base) signals structural pattern.

**10.8 Aggregate threshold justification:** Five independent civic concerns in 90 days from a non-consenting population of ~12,000 indicates organized structural concern at this scale.

**10.9 Response time window:** 30 days.

**10.10 Response window justification:** Not required.

---

## SECTION 11 — What does this authority commit to publishing?

**11.1 Citizen ledger publication:** Annually. Includes: foundation finances; sponsor list and concentration; maintainer composition and turnover; Technical Steering Committee composition and tenure; aggregate Code of Conduct enforcement statistics; security advisory record; capture risk monitoring; threshold change log.

**11.2 Threshold change log:** Within 7 days.

**11.3 Interpretation change log:** Continuous through public commit history and decision records.

**11.4 Renewal process visibility:** [x] Committed. Renewal review by parties drawn from affected categories: current maintainers; former maintainers (including those who departed under contested circumstances); current contributors; downstream maintainers of major dependent projects; users without contributor relationship; peer reviewer from sister open-source project's governance with no operational alignment to this project; representative from open-source advocacy organizations — *not* by foundation Board, current Technical Steering Committee, or sponsor representatives.

**11.5 Stop event log:** [x] Acknowledged.

---

## SECTION 12 — Honesty assertions

All five: [x] asserted/committed/acknowledged.

---

## SECTION 13 — Submitter

*[Submitter information retained by registry as metadata.]*

---

*REG-OPEN-SOURCE-GOVERNANCE-EXAMPLE — worked example of an open-source software project governance body*
*Registered under the Bounded Power Framework*
*All authority governed by the Structural Constitution (SCBP-04)*
