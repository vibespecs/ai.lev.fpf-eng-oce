# OCE.7 - Coordinate Product-or-Service and Organization Architecture Decisions: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Organization Change Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/ORGANIZATION-CHANGE-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## OCE.7:5 - Archetypal Grounding -- PumpWorks Product and Organization Decisions {#archetypal-grounding-pumpworks-product-and-organization}

PumpWorks is deciding how weekly AI-inspection releases should relate to the product's module/evidence structure. The organization-side input is the `OCE.4` contribution-architecture design. The product-side input identifies field-module boundaries, model artifacts, electrical compatibility evidence, shared platform services, safety evidence, and release configuration. Both sides remain possible-future where their direct relations do not yet obtain.

The current directional pressure uses the product-side architecture as influence source and the organization-side architecture as transformed side: module and evidence dependencies influence how independently release contributions can be prepared, tested, accepted, and deployed. The synthesis stays in a `C.32.CONWAY` frame until direct influence and both actual architecture relations are available. If an organization-side structure is later claimed to constrain a product-architecture candidate, PumpWorks records a second frame or occurrence with the direction reversed; reciprocity is not inferred from the first pressure.

| Candidate form | Proposed change | Main gain | Known loss or burden |
| --- | --- | --- | --- |
| organization-side change | Create one stream-aligned release configuration around the current product/evidence couplings | Shorter recurring coordination path | Cross-stream shared rig, Safety, platform, and scarce specialists remain bottlenecks |
| product/service-side change | Refactor module and evidence-package boundaries while retaining functional contribution homes | More independent test and evidence preparation | Product migration and assurance cost; organization coordination still spans releases |
| joint change | Align selected release-evidence packages and stream contributions while keeping shared platform and independent Safety relations explicit | Reduces some repeated crossings without hiding protected independence | Requires coordinated product refactoring, new assignments/access, and transition Work |
| bounded mismatch | Retain current product and functional organization for the window; add named integration and evidence-return relations | Lowest migration burden | Continuing coordination load and slower learning are accepted and measured |

PumpWorks selects the joint candidate for a bounded release family. The product architecture decision selects the alignment of module/evidence-package boundaries. The organization decision selects stream contribution boundaries and identifies the release-evidence integration need. Safety acceptance remains independent, platform and scarce capability homes remain shared, and provider support does not mirror a product module.

The two decisions cite the same assumptions and evolution window but retain separate authorities and realization Work. `OCE.6` supplies assignments and access; product realization remains with Systems Engineering; `OCE.9` later tests organization relations and capability; Operations supplies continuing-release and service observations. A changed safety regime, provider boundary, platform coupling, product family, or observed coordination burden reopens the affected decision pair.

### OCE.7:5.1 - Transfer Probes {#transfer-probes}

| Setting | Reusable move | Required return or changed content |
| --- | --- | --- |
| public-hospital emergency flow | Pair the hospital organization structures with the emergency-service architecture: triage, diagnostics, treatment, bed flow, escalation, and information continuity | There may be no product modularity question; statutory clinical authority, privacy, labor, safety, facility, and continuing Operations can justify deliberate non-isomorphism |
| distributed standards association | Pair volunteer/editorial organization structures with the standard-development and publication-service architecture | Bylaw decisions, ballots, employer resources, volunteer availability, repositories, publication services, and language communities evolve at different rates; no single firm boundary or executive authority is assumed |

## OCE.7:6 - Bias-Annotation {#bias-annotation}

| Recurring bias | Likely drift | Repair |
| --- | --- | --- |
| mirroring determinism | Structural similarity is treated as a law or quality. | Recover the exact pressure, candidate forms, gains, losses, and local decision. |
| organization-only repair | Teams move while product/service dependencies remain unchanged. | Include the product/service-side and joint candidates. |
| product-only repair | Technical modularity is expected to remove authority, evidence, or provider coordination. | Preserve organization-side structures and enabling relations. |
| autonomy prestige | End-to-end ownership hides shared safety, platform, capability, and service relations. | State protected independent/shared contributions and their burdens. |
| diagram causality | Architecture descriptions are said to create the result. | Name Systems, Work, direct influence relations, decisions, and realization separately. |
| window blindness | Current alignment is treated as permanent. | State the evolution window and asymmetric change rates. |

## OCE.7:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | Repair |
| --- | --- |
| “The organization must mirror the product architecture.” | State the exact structures and pressure relation, then compare all four candidate forms and accepted losses. |
| “Every service has one autonomous team.” | Recover shared platform, data, safety, evidence, provider, capability, Operations, and governance relations before deciding autonomy. |
| “Refactor the monolith and coordination will disappear.” | Name the organization Work and relations that the technical change is expected to alter, and observe them after realization. |
| “Reorganize around customer journeys.” | Identify the service and contribution structures, decision authority, shared capabilities, provider boundaries, and journeys' representation losses. |
| “The Conway workshop approved the target.” | Treat workshop output as candidate and participant evidence; make the separate architecture decisions under current authority. |

## OCE.7:10 - Rationale {#rationale}

Mirroring is useful as a contingent hypothesis about coordination and cognitive burden. Current reviews and cases also show co-evolution, changing causal direction, value- and regulation-sensitive exceptions, and situations where deliberate non-correspondence supports search or contribution. A four-form comparison turns that evidence into constructive alternatives instead of a slogan.

Separate decisions preserve accountability and distinguish selected changes from realized ones. An organization change can be selected while product realization is still future, or a product architecture can change while the organization remains stable. Their correspondence matters only through named relations and consequences.

## OCE.7:11 - SoTA-Echoing {#sota-echoing}

### OCE.7:11.1 - Current-Line Selection for Coordinated Architectures {#current-line-selection-for-coordinated-architectures}

| Comparison position | Selected result for practice |
| --- | --- |
| Current question | Which organization-side, product-or-service-side, joint, or bounded-mismatch candidate best serves the contribution across the declared evolution window? |
| Selected current line | Treat architecture correspondence as contingent, directional, and co-evolving. Compare all four candidate forms because value capture, regulation, authority, evidence, search, migration, provider, and capability conditions can make correspondence or deliberate non-correspondence preferable for a bounded use. |
| Serious alternative | Apply universal mirroring or fixed end-to-end ownership from product modularity, a communication pattern, or a team-topology slogan. |
| When the alternative is sufficient | Similar boundaries can be selected when direct local evidence shows that they reduce the decision-bearing burden without defeating protected shared or independent relations. |
| When the selected line changes action | If value, search, regulation, authority, shared platform, independent assurance, provider, or changing interorganization boundaries alter the consequences, retain the unlike structures and compare joint change and bounded mismatch explicitly. |
| Reopen | Reconsider when a recurring case needs another candidate form, current evidence changes the correspondence answer, or observed realization exposes a missed pressure or burden. |

### OCE.7:11.2 - Source Contributions and Boundaries {#source-contributions-and-boundaries}

| Source line | Retained contribution | Use boundary |
| --- | --- | --- |
| Current FPF `C.30`, `C.32`, `C.32.CONWAY`, `C.32.PAD`, `A.22`, and `A.6.REL` | Exact holons, actual and modal architecture, candidate synthesis, four correspondence forms, decisions, structures, and relation obtaining remain distinct. | Apply these distinctions while the authorized owners make the organization and product/service decisions separately. |
| Joseph and Sengul, [current organization-design review](https://doi.org/10.1177/01492063241271242) | Contemporary organization design is multi-approach and contingent; coordination and structure cannot be reduced to one representation or feature. | Select the local product/organization pair and test the relevant consequences before deciding. |
| Zani, Denicol, and Broyd, [megaproject organization-design review](https://doi.org/10.1016/j.ijproman.2024.102634) | Temporary and interorganizational boundaries evolve, and integration of product and organization architectures is a distinct design question. | Qualify transfer from megaprojects before using the evidence to choose a lifecycle, correspondence strategy, or product change in another setting. |
| Brusoni et al., [twenty-year modularity synthesis](https://doi.org/10.1093/icc/dtac054) | Product, organization, and industry architectures co-evolve; causal direction and the value of fit depend on context, evolution, and the question being asked. | Recover local authority and any claimed direct influence, then compare candidates for the declared window. |
| Burton and Galvin, [value and mirroring exceptions](https://doi.org/10.1016/j.jbusres.2022.07.023) | Regulation and value capture can make deliberate non-correspondence and stronger supplier ties preferable despite product modularity. | Treat the result as evidence from one industry case; test whether its value and regulatory conditions apply to PumpWorks. |
| Conway, [historical communication/architecture anchor](https://www.melconway.com/Home/Committees_Paper.html) | Communication arrangements can shape designed-system structure. | Use this historical anchor to ask about communication pressure; qualify the direct local relation and compare mirroring with the other candidate forms. |
| MacCormack, Rusnak, and Baldwin, [historical product/organization architecture study](https://doi.org/10.1016/j.respol.2012.04.011) | Comparable products developed under different organization forms provide evidence of architecture correspondence. | Test correspondence in the local pair and compare redesign consequences before selecting a change. |
| Colfer and Baldwin, [mirroring evidence and exceptions](https://doi.org/10.1093/icc/dtw027) | Mirroring is prevalent but not universal; exceptions and organizational forms matter. | Assess local adequacy separately; recover decision authority and, when realization is claimed, the actual performers and Work. |
| DORA, [loosely coupled teams](https://dora.dev/capabilities/loosely-coupled-teams/) | Team independence, testing, deployment, and coordination load provide practitioner recognition and possible pressure variables. | Use this software-heavy practitioner guidance for recognition, then test local relations and ownership against the broader research and the organization’s conditions. |

Reopen when a recurring organization/product-or-service case needs another decision-changing candidate form, a current source changes the correspondence answer, or observed realization shows that the selected pressure and burden variables miss the actual constraint.


## OCE.7:End {#end}
