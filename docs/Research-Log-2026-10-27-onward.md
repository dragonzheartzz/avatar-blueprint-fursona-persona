# AI Avatar Discovery and Assembly Service: Research Log

**Opened:** 27 October 2026  
**Status:** Three-perspective review completed 28 October 2026; Metis recommends bounded Athena planning/specification; CEO decision pending; no implementation authorised  
**Purpose:** Preserve the evidence, hypotheses, failures, and reusable findings from this idea investigation so it can be revisited if conditions change.  
**Canonical concept brief:** [AI Avatar Discovery and Assembly Service](AI-Avatar-Discovery-and-Assembly-Service.md)

## 1. Investigation principles

This is an attempt to determine whether the idea should fail, be parked, or earn a limited validation test. The aim is not to persuade ourselves that it will work.

- Keep this service independent from the existing auto-avatar production project.
- Do not create a dedicated repository until evidence warrants a separate project.
- Record facts, inferences, open questions and disconfirming evidence separately.
- Preserve ideas that fail current viability criteria if their methods, assets, insights or timing may be useful later.
- Do not interpret compliments, clicks or general interest as willingness to pay.
- Research and documentation are authorised. This log does not authorise implementation, spending, launch, marketplace integration, asset acquisition, vendor contact or customer-data collection.

## 2. Hypothesis under test

A customer provides a persona or avatar specification. We research relevant assets across marketplaces and creator sites, identify candidate combinations, document compatibility evidence and dependencies, estimate costs, identify gaps requiring custom work, and return a portable plan the customer can use independently or take to any creator.

**Core value hypothesis:** customers will pay a small, fixed fee to reduce the time, uncertainty and technical friction of turning an avatar concept into a feasible asset plan.

**Strongest competing hypothesis:** existing free search/catalogue tools plus a creator's own sourcing and quoting process already solve enough of the problem that customers will not pay separately for discovery.

## 3. Early source-backed findings

### 3.1 Search and compatibility tools already cover meaningful parts of the proposed service

- **Yorimichi Closet** describes itself as a BOOTH search and management service for VRChat avatar items, explicitly narrowing items to those compatible with a selected avatar. Its help pages describe category, price, sale, Modular Avatar and Quest filters; compatibility statuses include verified, tool required and adjustment needed. Basic features are free, with Premium mainly expanding closet slots and enabling private closets. Sources: [Help and FAQ](https://yorimichi.cc/en/help), [How to use this site](https://yorimichi.cc/en/guide).
- **VRCFinder** says it enriches BOOTH product listings with tags and keywords for mood, colour, style, season and compatible avatar. Its about page reports collection limits and explains that its dataset is periodically updated, not real-time. Source: [About VRCFinder](https://vrcfinder.net/en/about/).
- **BOOTHPLORER** presents itself as a BOOTH/VRChat asset and avatar search engine with compatibility linking and advanced filters. Its site reports a substantial indexed catalogue. Source: [BOOTHPLORER](https://boothplorer.com/).
- **Implication:** basic discovery, filtering, cross-category browsing and some compatibility signals are not unique. A paid report must demonstrate a materially better outcome than a customer using these tools directly.

### 3.2 A near-adjacent paid service already combines asset selection with implementation

- **baseworks** describes a service that chooses a base, helps select compatible outfits, hair and accessories, coordinates the design, fits assets, edits textures, configures Unity features, tests on PC and helps upload. Its published packages are $50 Basic Personalise, $150 Standard Custom Look and $300+ Premium Signature; paid assets are separate, and modelling from scratch is not included in standard packages. Source: [baseworks service and pricing](https://baseworks.design/en/).
- This is not a direct price comparison for a discovery-only report. It is evidence that customers can buy an integrated asset-selection-and-implementation service and that the seller already handles a similar upstream selection problem.
- **Implication:** we must test whether customers want a portable standalone plan before implementation, rather than assume a low-cost report is attractive because full commissions cost more.

### 3.3 Asset and marketplace costs, licence terms and workflow boundaries matter

- BOOTHPLORER and Yorimichi show that item prices and catalogue coverage vary, and their pages instruct users to verify listing details or describe non-real-time/collected data. Any report needs source links and a last-checked date.
- VRChat's official [Avatar Marketplace FAQ](https://help.vrchat.com/hc/en-us/articles/41810354825235-Avatar-Marketplace-FAQ) explains that purchasing an avatar in the in-platform marketplace does not normally provide source files; custom uploads remain supported. This reinforces that an in-platform ready-to-use avatar and an editable multi-asset build plan are different customer jobs.
- **Implication:** the service cannot simply aggregate a list of products. It must distinguish ready-to-use avatars from editable assets, record licence/usage restrictions, and state what the customer can actually do with the files.

### 3.4 Current price hypotheses remain unvalidated

The concept brief's £5–£9 basic and £12–£20 detailed-report prices are hypotheses, not proven market rates. Published commission packages provide context for adjacent labour, but they do not establish demand for a standalone report. For example, baseworks lists $50–$300+ for different levels of customisation, with assets separate. Source: [baseworks pricing](https://baseworks.design/en/).

**Do not claim that the discovery report is competitively priced until we have compared customer alternatives and measured actual delivery time.** A cheap report can still be a bad business if the manual research burden is high or if customers expect technical validation we cannot provide.

## 4. Initial falsification questions

The idea should be challenged against these failure modes:

1. **Free-substitute failure:** free search tools and creator communities solve the problem well enough.
2. **No standalone buyer:** customers want a finished avatar or a creator's advice, not a report.
3. **Wrong buyer:** the person who has the problem lacks budget, while creators who have budget already have their own workflows.
4. **Labour trap:** each persona requires so much bespoke research that the target price cannot cover delivery, corrections and support.
5. **Compatibility liability:** users interpret the report as a guarantee, while genuine compatibility may require downloading, opening Unity, fitting, testing or using licensed files.
6. **Source fragmentation:** important assets are missing from indexable catalogues, difficult to search across languages, or hard to compare reliably.
7. **Stale-data failure:** prices, availability, versions, licences or compatibility change too quickly for a low-cost report to stay trustworthy.
8. **Weak differentiation:** the report is a manually assembled list that a competent user could reproduce in a short time.
9. **Trust conflict:** customers suspect the report is merely a funnel into our separate production service. The standalone result must be useful without buying anything else.
10. **Platform concentration:** an offer built around VRChat/BOOTH cannot be generalised to other avatar ecosystems without separate research.
11. **Insufficient repeat demand:** the job is occasional, limiting subscriptions or recurring revenue. A fixed-fee product may still be possible, but this needs evidence.
12. **Rights and access risk:** source terms do not permit the data collection or workflows needed to deliver the service economically.

## 5. What would count as meaningful evidence?

### Evidence against proceeding
- Target users can complete the same task with existing free tools and little friction.
- Interviewees say a report sounds useful but cannot identify a real recent occasion when they would have paid for it.
- A realistic manual test takes too long for the plausible price, even after the scope is tightly bounded.
- The useful answer depends on technical testing that cannot be performed within the report price.
- Customers strongly prefer an integrated creator commission and see little value in portability.
- Reliable source coverage or licence verification is too weak for the promised deliverable.

### Evidence that may justify a limited validation step
- A specific customer segment has a recent, costly sourcing/compatibility problem.
- A repeatable report materially reduces time or prevents a concrete mistake.
- Users value independence from a particular creator and can explain why.
- A bounded report can be delivered consistently within a measured time budget.
- At least some target users demonstrate credible payment intent, ideally by accepting a clearly described paid test after an appropriate consent and refund approach is agreed.

No thresholds are finalised yet. Before a customer-facing test, set explicit pass/fail thresholds for task time, completeness, user value, willingness to pay and correction burden.

## 6. Specialist and Moonshot work

**Status at initial drafting on 27 October 2026:** Specialist reviews had not yet been completed. The three reports later received on 28 October (Pheme Social & Consumer Signals, Pheme Market Intelligence, and the Astro Teller-inspired challenge) are assessed in section 14. Other formal planning, architecture and post-test audits remain planned unless separately recorded.

- **Planning/requirements review:** define the exact job, first buyer, report boundaries and measurable success/failure criteria.
- **Architecture review:** assess whether the deliverable can be structured as a repeatable, portable blueprint without premature coupling to production software.
- **Pre-execution challenge:** identify hidden assumptions and invalid claims before any test is designed.
- **Post-evidence audit:** review what the test actually proves and what remains uncertain.
- **Moonshot-style failure challenge:** develop the strongest plausible case for stopping, including free substitutes, low willingness to pay, poor unit economics, rights constraints and lack of differentiation.

The Moonshot/Astro Teller source documentation has not yet been located and verified. Until it is found, use the points above only as a provisional falsification checklist, not as a claim that the documented house methodology has been applied. Search both Boardroom-Metis-Private and Aletheia-Emergence again when repository documentation access/path discovery is available.

## 7. Reusable learning to preserve if the idea is parked or stopped

Even if the standalone service fails, preserve these potentially reusable assets:

- A persona-to-asset research checklist.
- A compatibility evidence vocabulary distinguishing confirmed, source-supported, plausible/unverified and incompatible.
- A portable asset manifest including source URL, price date, licence checks, dependencies and confidence.
- A way to separate ready-to-use avatars from editable assets and custom-work gaps.
- A repeatable method for comparing free search tools against a defined customer brief.
- Evidence about where customers prefer a creator's integrated service over an independent report.
- Measured research time and error patterns that could inform a later avatar production workflow, without assuming integration now.

A stopped idea is not automatically worthless. Preserve the useful framework and the reason for the decision, then revisit only if the environment or assumptions materially change.

## 8. Current assessment

**Preliminary status: INVESTIGATE, with significant differentiation risk.**

The early research confirms that asset discovery and compatibility filtering are already served by free tools, and at least one paid service integrates selection with implementation. It does **not** yet establish that a persona-led, cross-source, portable report is valuable enough to buy. That is the central question for the next phase.

### Next steps
1. Complete a common-brief comparison across BOOTHPLORER, Yorimichi Closet and VRCFinder, recording the actual work each can and cannot do.
2. Choose one initial segment and one target ecosystem rather than claim a universal service.
3. Research real user pain and counter-evidence, prioritising specific recent examples over general opinions.
4. Run a timed manual dry run with a moderately complex fictional persona; no customer data or asset purchases.
5. Ask the relevant specialists to challenge the problem framing, delivery model and proposed thresholds.
6. Locate and read the retained Moonshot/Astro Teller documentation before claiming formal methodology alignment.
7. Return with a go / revise / park / stop recommendation. Do not create a dedicated repository or build the service before that decision.

## 9. Source register

All sources below were checked during the initial research sweep on 27 October 2026. Web content and catalogue counts can change.

- [Yorimichi Closet Help & FAQ](https://yorimichi.cc/en/help)
- [Yorimichi Closet Guide](https://yorimichi.cc/en/guide)
- [VRCFinder About](https://vrcfinder.net/en/about/)
- [BOOTHPLORER home](https://boothplorer.com/)
- [BOOTHPLORER asset search](https://boothplorer.com/search/assets)
- [baseworks service and pricing](https://baseworks.design/en/)
- [VRChat Avatar Marketplace FAQ](https://help.vrchat.com/hc/en-us/articles/41810354825235-Avatar-Marketplace-FAQ)


## 10. Community signal scan: problem evidence versus purchase evidence

A first, non-representative Reddit scan found examples of adjacent friction. These are qualitative signals, not a market-size estimate or proof that customers would buy a discovery report.

- In a January 2026 discussion about high-cost commissions, commenters described the time and specialist skill involved in custom modelling and kitbashing, and one user described paying others to avoid learning Blender and Substance Painter. This supports the broad existence of a time/skill barrier, but the discussion concerns full commissions rather than a standalone report. Source: [r/VRchat: reasoning behind spending over $1,000 on an avatar](https://www.reddit.com/r/VRchat/comments/1q4ry3m/for_those_who_spent_over_1000_usd_for_an_avatar/).
- A December 2023 poster wanted to buy BOOTH assets but lacked the time/knowledge to assemble an avatar and asked whether they could pay someone to add clothes and props. Replies pointed toward commission directories and tutorials, and raised concerns about scams. This is closer to a service need, but still points toward assembly/help rather than a paid plan alone. Source: [r/VRchat: Avatar Creation](https://www.reddit.com/r/VRchat/comments/18d7gdv).
- A December 2024 post raised concerns about the difficulty of judging BOOTH avatar asset quality before purchase, including technical problems that might only emerge during modification. This suggests that a mere list of products may be insufficient; verified compatibility/quality claims would require more evidence than catalogue search can supply. Source: [r/VRchat: Booth Avatar Review](https://www.reddit.com/r/VRchat/comments/1hat9hx).
- A June 2025 discussion argued that some users can set up and upload their own avatars using existing tools, while others value hassle-free ready-to-use avatars. This reinforces audience segmentation: technical self-starters may not need the service, while convenience-seekers may prefer a finished product rather than a report. Source: [r/VRchat: Why pay money for an avatar we can barely customize?](https://www.reddit.com/r/VRchat/comments/1l27j95/why-pay-money-for-an-avatar-we-can-barely/).

**Interpretation:** the scan supports several plausible pain points (skill/time barriers, trust and quality uncertainty, and the choice between self-service and convenience), but it does not validate willingness to pay for a standalone discovery blueprint. We have not conducted interviews, recruited customers, or tested a paid offer. Avoid treating Reddit anecdotes as representative.

## 11. Common-brief competitor comparison: first desk-based pass

To avoid comparing marketing claims in the abstract, use this fictional test brief in a later hands-on pass:

> “I want a dark-academia, slightly gothic VRChat avatar with a long black hairstyle, layered outfit, silver accessories and subtle violet accents. My budget for paid assets is limited. I have not yet chosen a base. I want to know what can be bought or obtained free, what fits together, what additional tools are required, and what would need custom work.”

| Task | BOOTHPLORER | Yorimichi Closet | VRCFinder | Standalone report opportunity |
|---|---|---|---|---|
| Search asset catalogue | Yes, BOOTH-focused asset/avatar search | Yes, BOOTH items and avatar catalogue | Yes, enriched BOOTH product search | Must search beyond one catalogue only if source access and rights allow |
| Filter by avatar compatibility | Compatibility linking and filters | Avatar-specific search and compatibility labels | Reverse lookup by compatible avatar | Can present a whole-look plan across multiple categories and sources |
| Search by style/mood/colour | Advanced filters advertised; exact task coverage needs hands-on test | Search and item/category filters; persona synthesis not established | Mood, colour, style and season tags explicitly described | Translate natural-language persona into a coherent set of candidate assets |
| Budget comparison | Price filtering and pricing display | Price bands, free items, sales | Search/filter; listing price needs verification | Build total asset budget and explain trade-offs |
| Compatibility confidence | Source/compatibility signals need item-level inspection | Explicit verified/tool-required/adjustment-needed statuses based on listing notes and user reports | Compatibility-aware discovery; exact evidence per result needs inspection | Explain evidence and uncertainty consistently across selected components |
| Dependencies and custom-work gaps | Not established as an end-to-end deliverable from reviewed page | Some tools/adjustment labels; no complete production gap report established | Search service rather than demonstrated end-to-end build plan | Map missing pieces, dependencies, and probable custom work |
| Portable independent deliverable | Search tool, not the proposed bespoke report | Closets/outfit posts help save/share combinations | Search tool, not the proposed bespoke report | Customer receives a report usable with any creator or self-build workflow |
| Price model | Search access appears free; no separate report fee observed | Basic features free; Premium chiefly adds private/larger closets | Public search tool; no standalone report fee observed | Fee only viable if the synthesis saves enough time or avoids costly mistakes |

This comparison is desk-based, based on publicly described features. It is not yet a hands-on execution test. We should not claim that a feature is absent merely because it was not visible on the pages reviewed.

### Preliminary differentiation conclusion

The report's plausible advantage is **synthesis and decision support**, not search. It would have to do the hard work of selecting a coherent whole look, explaining compatibility confidence, showing total costs, surfacing licence/dependency constraints, and identifying the parts no existing catalogue can solve. The counterpoint is that this synthesis may take enough human time to make a £5–£20 product uneconomic.

## 12. Revised next-step order

1. Run the common fictional brief through the three search tools manually and record results, elapsed time, dead ends and what still requires human judgement.
2. Narrow the first customer segment. Current candidates to compare: non-technical persona-led users, existing-base owners seeking a new look, and creators who want sourcing support.
3. Research recent real examples of asset-sourcing and compatibility friction, including counterexamples where free tools were sufficient.
4. Conduct a timed dry run and estimate labour at the proposed fee. Do not purchase assets or use customer data.
5. Obtain specialist reviews, then run the formal Moonshot-style challenge once the source methodology is found and read.
6. Set explicit thresholds before any external willingness-to-pay test.


## 13. Follow-up comparison pass: live page inspection (27 October 2026)

**Method and limitation:** I revisited the live public search pages and documentation for the same fictional brief. This pass verifies the visible search affordances and evidence boundaries, but it is **not yet the requested hands-on query execution or timed usability test**: the available page reader exposes the VRCFinder search controls but does not submit form inputs or preserve a reliable stopwatch-style task trace. I have not represented unexecuted searches as completed, and I have not used metered interactive browser automation without separate approval for its potential wallet cost.

### Observations from the pages inspected

- **VRCFinder product search:** the page visibly exposes category and price filters, free-only filtering, and detail-tag groups for appearance, body type, style, colour, outfit type, accessories, features, platform and season. It describes search across outfits, hairstyles, avatars, accessories and props. The about page says data is collected periodically, not in real time, and product tags are derived from listings and thumbnails then refined by hand. Sources: [product search](https://vrcfinder.net/en/search/), [asset search](https://vrcfinder.net/en/search/asset/), [about and data limitations](https://vrcfinder.net/en/about/).
- **Yorimichi Closet:** its guide describes starting from an avatar page to narrow results to items intended for that avatar. It documents price/category/sale filters and Modular Avatar and Quest support, alongside three compatibility states: Verified, Tool required and Adjustment needed. The states rely on shop compatibility notes and user fit reports, so an unmarked result should not automatically be treated as incompatible. Sources: [guide](https://yorimichi.cc/en/guide), [help and FAQ](https://yorimichi.cc/en/help).
- **BOOTHPLORER:** its public home and search descriptions confirm BOOTH-focused avatar and asset discovery, compatibility linking, advanced filtering, price filters and category-specific search. Source: [BOOTHPLORER](https://boothplorer.com/), [avatar search](https://boothplorer.com/search/avatars). The accessible page reader did not allow me to submit the fictional brief as an actual search.

### What this does and does not establish

The public pages strengthen the counter-hypothesis that the proposed service would be competing with capable free discovery tools, not solving a blank-space problem. VRCFinder visibly supports several persona attributes directly; Yorimichi makes avatar-specific compatibility and evidence labels central; BOOTHPLORER combines catalogue search with compatibility linking. The potential gap remains the **cross-tool synthesis**: a costed, coherent whole-look plan, evidence confidence for each component, dependencies and custom-work gaps, and a portable output that does not require buying implementation.

This is still a capability inspection, not proof that the three tools can or cannot satisfy the sample brief in practice. No result counts, successful product matches, exact task duration, licence checks or end-to-end compatibility claims are asserted here.

### Decision on the next test

The next valid experiment is a true interactive, timed run of the identical brief in all three tools, recording search terms, candidate results, price and source links, compatibility evidence, dead ends, and unresolved decisions. Because the available interactive browser workflow may incur metered wallet charges, obtain Tilly's explicit approval before using it. If that is not approved, continue with a clearly labelled desk-based test and do not claim measured task time.

### Pheme review scope (planned before review; completed 28 October 2026; see section 14)

Pheme's most useful independent assignment would be a **consumer-signal and segment challenge**, not another broad competitor summary:
1. Identify which plausible initial segment has the strongest observable recent pain: non-technical persona-led users, existing-base owners seeking a new look, or creators needing sourcing support.
2. Seek counterexamples where free tools, creator communities or ready-to-use avatars fully solve the job.
3. Separate evidence of general avatar-creation friction from evidence that someone would pay for a standalone portable discovery report.
4. Recommend a small number of falsifiable demand signals and explicitly state what evidence would justify parking the idea.

At the time this section was drafted, this was a proposed scope and no specialist opinion was attributed. Pheme's two reports have since been reviewed; the consolidated analysis is recorded in section 14.


## 14. Consolidated review of three specialist reports and CEO discussion (28 October 2026)

**Review status:** Three reports reviewed individually: Pheme Social & Consumer Signals, Pheme Research Architect & Market Intelligence, and the independent Astro Teller-inspired challenge. The reports are treated as distinct perspectives, not votes. Their pasted text fits the assigned roles, but literal authorship cannot be authenticated from pasted content alone. Some examples in the reports lack direct thread-by-thread URLs and need stronger traceability before being treated as auditable primary evidence.

**Session record:** [Avatar Blueprint three-perspective review, 28 October 2026](sessions/2026-10-28-avatar-blueprint-three-perspective-review.md).

### 14.1 Refined opportunity framing

The opportunity is **not merely a paid list of avatar asset links**. The current business hypothesis is a persona-to-blueprint service that turns a customer's full avatar requirement into a coherent, actionable plan.

- The customer can start with a guided form or provide an existing persona/fursona or avatar specification.
- The workflow should accommodate different paths, initially including humanoid and anthropomorphic avatars, without claiming all ecosystems are already supported.
- The blueprint should coordinate the whole look, not answer isolated questions: candidate base and components; relevant sources beyond a single catalogue where permitted; estimated total spend; compatibility evidence and uncertainty; dependencies; licence/use constraints; what requires adjustment or custom work; and practical next steps.
- The blueprint must provide honest standalone value. The customer can implement it themselves, take it to any creator, or request a separate quote from our own avatar-production service.
- The optional production route is a fair customer choice and a potential source of downstream work, not a reason to make the blueprint deliberately incomplete or misleading.
- The broader company hypothesis is a modest, affordable entry offer that can also introduce appropriate customers to a competitively priced full avatar-creation service. This combined value proposition was clarified by Tilly during the 28 October review.

This refined framing is broader than the standalone static-report proposition challenged most directly by the reports. It changes the question to test; it does not itself establish demand or viability.

### 14.2 What the reports converge on

**Consumer signals (Pheme):**
- Public discussions and specialist tools support the existence of friction around finding bases/assets, identifying items, checking compatibility, estimating cost, and navigating the skill gap between kitbashing and a finished avatar.
- The evidence is qualitative, selected and incomplete. It does not establish how representative these needs are or how often people would pay for a blueprint.
- People who ask for links, people who want a whole avatar built, and people who would buy an independent whole-persona plan may be different segments.

**Market intelligence (Pheme):**
- The competitive and substitute landscape is substantial. BOOTHPLORER, Yorimichi Closet and VRCFinder provide free discovery features; Yorimichi has described Premium features but made them free during its open beta. BOOTHPLORER and VRCFinder are described as free search services. Asset purchases themselves may cost money, which is different from paying the search service.
- The reviewed discovery tools are strongly BOOTH-oriented. A cross-source workflow that includes relevant creator catalogues and other permitted sources might be differentiated, but exhaustive source coverage has not been demonstrated. Do not claim a market-wide coverage gap until a source map and common-brief comparison show exactly what is and is not covered.
- Adjacent commissions demonstrate that creators sometimes monetise sourcing as part of a wider service. That is not equivalent to proof of standalone demand.
- Proposed basic (£5–£9) and detailed (£12–£20) prices remain unvalidated. No delivery-time study, customer conversion data, support-burden measurement, or repeated-purchase evidence exists.

**Independent challenge (Astro-inspired):**
- The strongest counter-hypothesis is that users either enjoy searching themselves or want a finished working avatar, not an intermediate plan.
- Main failure modes include a plan that does not overcome the technical barrier, free substitutes that are sufficient, a price too low for manual labour, mistakes that create support/refund burden, weak differentiation and lack of repeat demand.
- Alternative shapes (compatibility audit, creator-facing sourcing help, or free curated lookbooks with possible affiliate monetisation) are unvalidated fallbacks, not established superior choices.
- The report's **PARK / REJECT with high confidence** conclusion is stronger than its presented evidence: it has no direct willingness-to-pay or delivery-time study, and it assesses the standalone report more narrowly than the persona-to-blueprint-plus-optional-production model now clarified.

### 14.3 Independent source and platform observations

The initial desk research and later public-page inspection support these bounded statements:
- The three named discovery tools already provide meaningful search and filtering; basic search alone is not a defensible paid differentiation.
- Their publicly described coverage is materially BOOTH-focused. Whether a permitted cross-source workflow offers enough added value requires a defined source map and a real common-brief test.
- One integrated creator service, baseworks, advertises asset selection alongside fitting and implementation at substantially higher published package prices. This is adjacent evidence only, not a direct comparison or demand proof.
- Existing source notes describe a paid asset-finding add-on and other commissions bundling sourcing with implementation. These show that sourcing labour can be sold in some contexts, but do not prove that a standalone blueprint sells.
- The earlier competitor comparison is a desk-based capability inspection, not a timed hands-on search or end-to-end compatibility test. No result counts, measured task time, cross-asset validation, or licence audit have been claimed.

### 14.4 Automation and economics: promising hypothesis, not yet evidence

Tilly's intended operational hypothesis is that a repeatable workflow can use DSH Web or another authorised browser/search route to gather relevant information and assemble it into a useful report. A separate auto-avatar project is intended to investigate MCP/CLI-supported interaction with Blender and Unity for avatar assessment, preparation and production; its actual supported capabilities and interface have not been independently audited in this research review.

This may reduce marginal research or production costs, but the reduction is not yet measured or demonstrated. The economics still need to include:
- time to interpret and clarify the brief;
- source lookup and fallback routes where catalogues omit relevant assets;
- checking dates, prices, availability, licence wording and evidence of compatibility;
- report assembly, quality control, corrections, customer support and refunds;
- customer acquisition and payment/platform fees;
- production-specific modelling, rigging, fitting, testing, packaging, delivery and support.

A future workflow can use tiers and explicit scope limits, but cannot assume a flat price covers unlimited research or guarantee technical compatibility the service has not actually tested.

### 14.5 Asset originality, third-party rights and licensing

Tilly's intended production direction includes creating original meshes, textures, rigged bases and other assets in Blender for the customer's brief, rather than necessarily purchasing every third-party component.

That is a promising route to evaluate, but the claim that a recreated asset is safe simply because it is a new model or “different enough” must **not** be treated as established. UK government guidance says copyright protects expression and copying or using copyright material generally requires permission, a suitable licence, or a valid exception; whether a substantial part has been copied is case-specific. Licences can also restrict commercial use, adaptations and redistribution. Sources: [GOV.UK copyright guidance](https://www.gov.uk/using-somebody-elses-intellectual-property/copyright); [GOV.UK copyright overview](https://www.gov.uk/copyright); [UK Government Report on Copyright and AI, published 18 March 2026](https://www.gov.uk/government/publications/report-and-impact-assessment-on-copyright-and-artificial-intelligence/report-on-copyright-and-artificial-intelligence).

Practical boundary for future design:
- Prefer independently designed assets based on the customer's requirements and general style/function, with retained source files and design records.
- Do not assume that re-modelling, re-rigging, changing topology, or changing some visual details automatically clears rights if the result reproduces protected expression from a specific asset.
- When an existing product is merely a reference point, separate the customer's desired broad attributes from distinctive copied details. If the brief requests a replica or close adaptation, use a permitted licence/permission or escalate for qualified IP advice instead of treating “different enough” as a legal test.
- Record third-party licences, model/source provenance, AI/tool contribution where relevant, customer permissions, and permitted delivery/resale terms. Ensure any promise about ownership of the finished product matches the actual chain of rights and contract terms.
- This is a material design risk to manage, not a reason by itself to abandon the business. Do not make definitive legal conclusions without appropriate advice.

The service itself may promote creators by linking to their original listings and identifying purchasable assets. No evidence in the reports establishes that promotion is inherently unacceptable to creators or consumers, but terms of service, scraping/access rules, attribution, linking, privacy and marketplace policies must be checked per source. No creator contact or platform integration has been performed.

### 14.6 Consolidated conclusion and recommendation

**Metis recommendation: ADVANCE to a bounded concept-planning/specification stage with Athena. Do not yet advance to build, customer launch, marketplace integration, spending, or paid validation.**

Reasoning:
1. There is credible qualitative evidence of a real, multi-part problem, and the proposed holistic persona-to-blueprint model is sufficiently distinct from a basic directory to merit a structured requirements phase.
2. The intended downstream production offer gives the concept a coherent business role beyond earning a small report fee, while keeping the customer free to use the blueprint independently.
3. The current evidence does not justify rejection. Astro's strongest objections remain legitimate failure tests, but his high-confidence rejection is not demonstrated by the research.
4. The concept is not yet proven enough for implementation. The next stage should specify the exact customer promise, supported source coverage, deliverable, workflow, rights safeguards, cost model, and cheapest decisive test before any build is considered.

**This is Metis's recommendation, not an inferred CEO decision.** Tilly retains final authority. No build, spending, launch, marketplace integration, asset purchases, customer contact, customer-data collection, or external validation is authorised by this recommendation.

### 14.7 Athena hand-off: questions the planning phase must resolve

Ask Athena to turn the opportunity into a bounded requirements proposal, not a build mandate. At minimum, planning should define:

1. **Customer and start paths:** initial target segment; persona/fursona path; humanoid versus anthropomorphic flow; handling of an existing base or current avatar; budget, platform and must-have constraints.
2. **The complete blueprint:** recommended direction and alternatives; full component list; source links; estimated total costs with last-checked dates; compatibility-confidence labels; dependencies; licence/usage caveats; custom-work gaps; and explicit next steps.
3. **Cross-source boundaries:** first supported ecosystem and source list; permitted search/access method for each; behaviour when a source is unavailable, unindexed or stale; no unsupported promise to cover every marketplace.
4. **Fair offer architecture:** standalone blueprint remains useful; optional production quote is separate and transparent; scope limits and revision/support boundaries; no unvalidated prices or misleading funnel claims.
5. **Production hand-off:** identify what a future structured manifest might contain, but do not assume the auto-avatar project already supports it. Audit the relevant production repository and MCP/CLI/Blender/Unity interface separately before proposing integration.
6. **Asset rights and provenance:** first-principles rules for original creation versus third-party assets and adaptations; how permissions, licences, attribution and customer ownership/delivery rights are recorded; when an uncertain request must be declined or escalated.
7. **Delivery economics:** measurable time budget per tier, automation assumptions, quality checks, correction/support burden and a way to estimate true gross contribution rather than gross sale price alone.
8. **Fail-first validation plan:** specify the riskiest assumptions, measurable observable evidence, and stopping/revision conditions. Do not use arbitrary conversion thresholds or treat stated interest as proof of payment.

### 14.8 Gates after planning

A proposal may return for CEO review only when it states:
- a precisely bounded first offer and target customer;
- one example blueprint showing the claimed whole-persona value;
- confirmed versus inferred coverage, including rights/access limitations;
- a plausible manual or automated workflow with no unsupported capability claims;
- initial cost/time estimates and their evidence quality;
- the proposed smallest test, its approval needs, pass/stop criteria and privacy/rights conditions;
- remaining risks and what evidence would change the recommendation.

**Stage outcome:** The idea earns planning attention, not automatic investment. The aim of the next stage is to make the proposition precise enough that it can be tested and, if weak, rejected cheaply.
