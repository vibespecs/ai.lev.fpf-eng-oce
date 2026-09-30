# OCE.7 - Coordinate Product-or-Service and Organization Architecture Decisions {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Organization Change Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/ORGANIZATION-CHANGE-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

> **Type:** Method pattern
> **Status:** Eternal alpha
>
> **Primary working result:** **coordinated but separately governed product-or-service and organization architecture decisions** that name both holons and selected structures, correspondence pressure, four candidate forms, expected gains and losses, authority, evolution window, realization returns, and observations that reopen either decision.

## OCE.7:0 - Use This When {#use-this-when}

Use this pattern when a product or service architecture and an organization design constrain each other strongly enough that deciding one side alone would create avoidable coordination, evidence, provider, safety, or evolution burden. Enter when “the organization should mirror the product”, “teams own services end to end”, or “change the platform to fit the organization” is being used as the decision.

Begin with one bounded contribution and at least one organization-side structure or candidate from `OCE.3` or `OCE.4`. Recover the product-or-service focus, concept, architecture claims, and qualified specialist contributions from Systems Engineering or another owning practice when available. State missing inputs and what they block.

The first useful result can be a bounded mismatch: two separately governed decisions that say which structures will align, which will remain deliberately non-isomorphic, what burden is accepted, and what observation will reopen that choice.

Use `C.32.CONWAY` directly when only correspondence candidate synthesis is needed. Use `C.32.PAD` or the owning domain pattern for each architecture decision. Use `OCE.4` when only organization contribution structure is changing, Systems Engineering when only the engineered product architecture is current, and Operations when the question concerns managing continuing Work rather than changing the organization.

## OCE.7:0.1 - Working Distinctions {#working-distinctions}

| Name used here | Meaning |
| --- | --- |
| organization-side architecture content | Actual or modal `C.30` content about the named organization holon and selected contribution, Work, decision, information, access, service, coordination, legal, or other structures. |
| product-or-service-side architecture content | Actual or modal architecture content about the named product, service System, offering System, platform, or other exact product-or-service-side holon. For each stated directional pressure, identify whether this content describes the influence-source side or the side being changed. |
| correspondence pressure | A bounded claim that one side's selected structures influence the feasibility or burden of candidates on the other side through a named relation. It is not a universal law or automatic decision. |
| correspondence frame | The `C.32.CONWAY` synthesis frame used while either side is modal or the direct influence relation is unresolved. |
| exact correspondence row | A reusable `C.32.CONWAY` row about one obtaining direct influence relation whose two participants are obtaining `C.30` architecture-relation occurrences, with each holon and selected structure recoverable. |
| evolution window | The period and expected change range over which the correspondence decision is intended to guide Work. |
| coordinated decision set | Two or more separately governed decisions linked by shared assumptions, constraints, and reopen conditions. |
| bounded mismatch | A deliberate choice to keep selected structures non-isomorphic for the stated window while accepting and managing the resulting burden. |

## OCE.7:1 - Problem Frame {#problem-frame}

Products and services are produced, operated, supported, assured, and changed through organizations. Communication, deployment, test, approval, provider, evidence, and capability-home structures can make some product or service architectures easier to sustain. Technical dependencies can in turn create coordination and specialization pressure in the organization.

Correspondence can help without becoming one-to-one mirroring. Independent safety acceptance, scarce specialist homes, legal entities, platform services, regional operations, provider contracts, and continuing service can justify deliberate non-isomorphism. The task is to decide both sides with their gains, losses, authorities, and evolution windows visible.

## OCE.7:2 - Problem {#problem}

One-sided decisions externalize burden. A modular product can be assigned to nominally independent teams that still share one test rig, safety decision, data source, or specialist. A reorganized stream can inherit a tightly coupled product that requires constant cross-stream integration. A service boundary can be redrawn without the provider authority, observability, or recovery conditions needed to operate it.

Mirroring language hides these facts when it treats similarity as adequacy or inevitability. Practitioners can also mistake an influence on the design, expressed in a chart, architecture description, or decision record, for the Work that realizes it. They then cannot tell what relation created the pressure, which System performed the Work, or which side should change.

## OCE.7:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Local autonomy | Aligned boundaries can reduce coordination, while shared safety, evidence, platform, and capability conditions can require cross-boundary relations. |
| Technical integrity | Product or service cohesion matters, while organization migration and provider arrangements constrain feasible change. |
| Specialist depth | Stable capability homes improve difficult Work, while contributors may face queues and extra handoffs across those boundaries. |
| Independent authority | Separate acceptance or governance can protect a characteristic, while it prevents full end-to-end ownership. |
| Evolution | Current alignment can be useful, while products, services, people, providers, and regulation change at different rates. |
| Evidence | Correspondence studies reveal contingent patterns, while a local decision still needs direct structures, relations, and consequences. |

## OCE.7:4 - Solution {#solution}

Frame one exact organization/product-or-service architecture pair and generate four candidate forms: change the organization side, change the product-or-service side, change both, or keep a bounded mismatch. Compare complete candidates across the declared evolution window. Make the organization and product-or-service decisions under their own authorities, then connect them through explicit constraints, accepted burdens, realization returns, and shared reopen conditions.

Recognition is cheap: one architecture choice whose feasibility depends on an unlike structure on the other side is enough to enter. Assurance is stronger: actual correspondence claims require the exact holons, selected structures, direct influence predicate and occurrence, conditions, evidence, and window. Modal material remains in the synthesis frame.

### OCE.7:4.0 - One first paired decision {#one-first-paired-decision}

An instrument maker's engineering organization and inspection product form one bounded pair: two contribution groups serve two product modules that share a test setup. For the next two releases, reuse their current architecture accounts, participant corrections and qualified test, safety and service constraints. The proposed coordination pressure stays in a synthesis frame unless its direct influence relation is established.

The two authorized decision-makers can work from one short paired note:

> The organization-only candidate would merge the groups and disrupt an existing specialist-service commitment. The product-only and joint candidates require redesign that cannot fit the two-release window under the current engineering assessment. We therefore choose a bounded mismatch. The product decision retains the module and test boundaries. The organization decision retains the two groups and specifies one integration contribution and exception return per release. The gain is low migration burden; the accepted cost is shared-test coordination and no claim of independent release by each group. Reopen both decisions if the shared-test burden defeats the protected service commitment, or when the two-release window ends.

Each decision-maker records the decision for their own subject and authority. Send the needed assignment, access, test-time and service-protection requests to their owners for action before the dependent releases. Keep the existing evidence with the note. Use the fuller questions below for an unresolved claim or consequence that could change the pair, rather than rebuilding settled architecture accounts.

### OCE.7:4.1 - Pattern-Use Unfolding {#pattern-use-unfolding}

1. **Bind the paired question.** Name the intended contribution, organization holon, product-or-service holon, decision subjects, authorities, current Work, horizon, evolution window, protected characteristics, and first users of both decisions.
2. **Recover both architecture sides.** Separate actual `ArchitectureRelation` occurrences from candidate, required, desired, or expected `ArchitectureClaim` content. Name each selected structure, description source, currentness, and known loss.
3. **Recover each directional pressure relation.** State which side supplies the influence source and which side contains the changed architecture referent for this candidate; the direction can reverse between pressures. State how a communication, Work, test, deployment, approval, evidence, provider, capability-home, legal, service, or other source structure constrains the transformed-side candidate. Use the applicable direct predicate or keep a `C.32.CONWAY` frame with a missing governor. A reciprocal claim requires its own reversed frame or relation occurrence.
4. **Select decision characteristics.** Name the few characteristics and burdens that can reverse the choice. Ask about the intended contribution, coordination, latency, changeability, safety, evidence, resilience, provider dependence, capability and service continuity, migration, effects on affected Systems, or another exact concern.
5. **Prepare all four candidate forms.** Change the organization side while retaining product/service content; change the product/service side while retaining organization content; change both; or keep a bounded mismatch with explicit cost and return. A form can be rejected quickly when a non-negotiable condition fails.
6. **Obtain qualified domain inputs.** Use available `SYSE.1`, `SYSE.2`, and `SYSE.9` results for engineering focus, linked use/System concepts, and professional contributions when compatible. Use qualified direct sources or return the missing result when a sibling body is unavailable.
7. **Compare whole consequences.** Include current and transition Work, provider and platform arrangements, independent authority, evidence paths, scarce capability, legal and service boundaries, affected Systems, reversibility, and the burden of preserving deliberate non-isomorphism.
8. **Challenge the preferred pair.** Ask which omitted dependency, exception, configuration, operating episode, or later evolution would reverse the choice. Use prototypes, simulations, participant criticism, sampled Work, or specialist results only within their evidence limits.
9. **Make separate decisions.** Use `C.32.PAD`, `C.11`, or the owning pattern for each decision. State selected structures, fixed constraints, open refinements, accepted losses, authority, effectivity, retained alternatives, and relation to the paired decision.
10. **Specify realization and coexistence returns.** Name the organization-change Work, product/service realization Work, continuing-service conditions, assignment/access needs, and observations each owner must return. Keep the realization Work and its evidence separate from the decisions selecting it.
11. **Reopen locally or jointly.** Reconsider only the affected decision when one side changes without altering the correspondence choice. Reopen both when the pressure relation, accepted mismatch, protected characteristic, or evolution window changes materially.
12. **Stop at coordinated sufficiency.** Return when both owners know what is selected, what remains open, why structures align or differ, which burden is accepted, and what evidence can reopen the pair.

### OCE.7:4.2 - Record the Result {#record-the-result}

| Result position | Required content |
| --- | --- |
| paired boundary | Contribution, two holons, decision subjects, authorities, current Work, horizon, evolution window, protected characteristics, and first users. |
| architecture sides | Actual relation or modal claim status, selected structures, descriptions, sources, currentness, and known losses for each side. |
| correspondence | Direction of each pressure, direct influence predicate/occurrence or synthesis frame, source and transformed architecture content, affected characteristic, evidence, and missing governor. |
| candidate forms | Organization-side change, product/service-side change, joint change, bounded mismatch, expected gain, known loss, migration burden, and rejected non-negotiables. |
| comparison | Contribution, coordination, safety, evidence, resilience, provider, capability, service, affected-System, reversibility, and uncertainty consequences that change this decision. |
| separate decisions | Selected option and structure effects, authority, fixed/open boundary, accepted losses, retained alternatives, effectivity, and cross-reference to the paired decision. |
| realization returns | Work, assignments, access, provider, coexistence, specialist, observation, and evidence results required from each owner. |
| continuation | Local and joint reopen observations, source-return conditions, and end of the evolution window. |

### OCE.7:4.3 - What Changes in Practice {#what-changes-in-practice}

Practitioners stop treating product and organization architecture as either independent or forced copies. They can change the cheaper or more valuable side, change both, or accept a visible mismatch. Independent safety, evidence, platform, provider, capability-home, and service boundaries become design constraints rather than embarrassing exceptions to a topology slogan.

## OCE.7:7 - Conformance Checklist {#conformance-checklist}

- [ ] The contribution, two exact holons, decisions, authorities, current Work, and evolution window are explicit.
- [ ] Actual architecture relations and modal claims remain distinguishable on both sides.
- [ ] The correspondence uses a direct predicate/occurrence or an explicitly provisional `C.32.CONWAY` frame.
- [ ] Organization-side, product/service-side, joint, and bounded-mismatch candidates are considered.
- [ ] Comparison includes the characteristics, independent/shared contributions, migration, affected Systems, and uncertainty that can change this decision.
- [ ] Systems Engineering or other domain results are consumed only when available and compatible.
- [ ] The paired decisions retain separate authorities, subjects, fixed/open boundaries, and realization Work.
- [ ] Local and joint reopen observations are stated.

## OCE.7:9 - Consequences {#consequences}

Product-or-service and organization changes become one coordinated design question without losing their distinct subjects and authorities. Deliberate non-isomorphism becomes a controllable decision with visible cost.

The cost is broader evidence and coordination. Two decision owners may need different sources, and the attractive joint candidate can remain blocked by migration, safety, provider, capability, or continuing-service conditions.

## OCE.7:12 - Relations {#relations}

- `OCE.3` supplies organization concepts and correspondence assumptions. `OCE.4` supplies the organization-side contribution-architecture design. `OCE.6` can supply effective assignments and enabling relations needed by realization.
- `C.32.CONWAY` supplies correspondence framing and exact rows; `C.32.PAD` supplies project architecture decisions; `C.30` and `A.22` govern architecture content and selected structures.
- Available compatible `SYSE.1`, `SYSE.2`, and `SYSE.9` results may supply engineering focus, linked use/System concepts, and qualified contributions. Systems Engineering retains product architecture and realization.
- `OCE.9` consumes organization design constraints and later returns actual relation/capability evidence. `OCE.11` can coordinate organization-change and continuing-service Work. Operations returns operating observations.
- Governance, Administration, legal, labor, safety, privacy, finance, providers, HCD, and other practices keep their decisions, predicates, evidence, and authority.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-oce/contract/OCE-3#root, spec://ai.lev/fpf-eng-oce/contract/OCE-4#root; FPF spec://ai.lev/fpf-spec/contract/C-30#root, spec://ai.lev/fpf-spec/contract/C-32-CONWAY#root, spec://ai.lev/fpf-spec/contract/C-32-PAD#root @status:spec/done

#source spec://ai.lev/fpf-eng-oce/source/OCE-7
