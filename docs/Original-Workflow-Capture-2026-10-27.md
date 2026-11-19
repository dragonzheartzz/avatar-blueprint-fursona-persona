# Initial capture note: AI Avatar Discovery and Assembly

> This is the original capture note preserved from the Company Ideas backlog. The current customer-facing service concept and research plan are documented in [AI Avatar Discovery and Assembly Service](AI-Avatar-Discovery-and-Assembly-Service.md). Keep this note as historical context; use the service document as the working specification.

# AI Avatar Discovery and Assembly Workflow

**Status:** CAPTURE for initial desk research at Company Opportunity Discovery on Tuesday, 27 October 2026. Research only. No build, purchases, marketplace access negotiation, vendor contact or commercial commitment authorised.

## Concept

A prompt-driven discovery workflow that helps a user turn an avatar persona or fursona, plus preferences and constraints, into a practical collection of compatible avatar assets. Instead of manually searching across many sites, the user describes the character and the system searches relevant avatar and creator marketplaces for suitable base avatars, bodies, heads, hairstyles, clothing, accessories, props and other advertised assets.

The output would be a curated assembly plan: suggested avatar/base options, compatible assets, item links and prices where available, free and paid alternatives, known requirements, and clear notes about what works together. The aim is to lower the barrier for users who want a distinctive avatar but feel overwhelmed by finding and assembling everything from scratch. The user would retain creative choice rather than being handed a single opaque answer.

## Possible longer-term connection

This could potentially become a discovery and asset-selection stage within the existing avatar automation project, which aims to move from an initial brief through avatar or asset creation and assembly toward a VRChat-ready deliverable. Discovery/selection and end-to-end avatar production are related but distinct workstreams; any connection to that project must be assessed against its existing architecture and roadmap rather than assumed.

The wider potential workflow might include:
1. Translate a persona/fursona and user preferences into searchable attributes.
2. Find candidate base avatars and individual assets across supported catalogues.
3. Check compatibility, dependencies, price, availability, licence and permitted use.
4. Rank options by fit, budget and technical requirements, while showing alternatives and uncertainty.
5. Produce an assembly recipe or shopping list the user can review and approve.
6. Where supported and separately authorised, hand selected, licensed assets into a later assembly/import pipeline.
7. In a future phase, investigate how much of avatar assembly, validation, packaging and VRChat upload can be automated using supported tools and platform permissions.

## Initial opportunity questions

- Do avatar creators and VRChat users currently lose significant time finding assets that fit a persona and are compatible with a chosen base/avatar?
- Which catalogues and search sites are most important, and do they expose documented search APIs, feeds, partner integrations or other permitted access methods?
- Can cross-site search be built reliably without prohibited scraping, brittle page automation, or dependence on access that a marketplace can withdraw?
- Can the system identify real compatibility between bases, bodies, clothing, hairstyles, props, rigging, shaders, Unity versions and avatar systems, rather than relying only on text similarity?
- What should the output be: discovery shortlist, compatible bundle/assembly recipe, purchase list, project manifest, or an integrated path into an avatar creation harness?
- Is the primary customer a beginner who needs guidance, an experienced creator who wants faster asset sourcing, or a creator/team automating production?
- Would users pay for convenience, or is a sustainable business model more likely to involve affiliate referrals, creator/marketplace partnerships, a paid creator workflow or B2B tooling?
- Which narrow workflow provides a useful first test without requiring a comprehensive index of every asset online?

## Trust, rights and platform constraints

- Respect each site's terms, robots/access policies and documented API limits. Do not assume unrestricted scraping or automated purchasing is allowed.
- Preserve attribution and link to the original creator/listing. Verify licences, commercial-use permissions, redistribution rules, modification rights and any restrictions on combining or re-uploading assets.
- Do not download, bundle, modify or redistribute paid assets unless the relevant licence and user permissions explicitly allow it.
- Treat pricing, availability, compatibility and licence information as time-sensitive; show source and last-checked date where possible.
- Separate confirmed compatibility from best-effort inference, and allow the user to inspect evidence and make final choices.
- Investigate VRChat's current requirements and supported ways to import, build, validate and upload. Do not assume unattended upload or account actions are available or permitted.
- Keep marketplace credentials, payment actions and third-party assets out of any early experiment unless there is a clear, authorised need and a safe design.

## Research plan for Tuesday, 27 October 2026

1. Map relevant avatar asset marketplaces and discovery tools, their coverage and permitted access methods.
2. Identify existing products that already offer cross-catalogue search, compatibility checks, curated bundles or avatar automation.
3. Examine the most difficult compatibility and licensing problems, not just search ranking.
4. Review how this might connect to the existing avatar project without duplicating work or expanding its scope prematurely.
5. Define one narrow target user and one end-to-end task to test manually before considering code.
6. Recommend **INVESTIGATE**, **WATCH/PARK**, or **STOP** based on real competitor and workflow evidence.

## Scope boundary

Desk research only at this stage. No crawler, scraper, marketplace integration, purchase flow, asset download pipeline or VRChat upload automation is authorised. The objective is to establish whether a useful, compliant and commercially differentiated workflow exists before proposing an implementation.
