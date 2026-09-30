# OCE.4 - Design an Organization's Contribution Architecture {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Organization Change Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/ORGANIZATION-CHANGE-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

> **Type:** Method pattern
> **Status:** Eternal alpha
>
> **Primary working result:** an **inspectable contribution-architecture design**: a decision and possible-future description recording selected specialization boundaries, contribution-relation specifications, acceptance and exception conditions, affected burdens, receiving decisions, and the evidence needed to establish which direct relations later obtain.

## OCE.4:0 - Use This When {#use-this-when}

Use this pattern when an organization concept has been selected or narrowed, but its chart, topology, or operating-model label still does not say how contributions reach their receivers. Enter when specialization boundaries, supplied results, information use, decisions, services, resource access, or coordination must be designed before positions or assignments can be settled.

Begin with a compatible `OCE.1` focus, `OCE.2` current account, and `OCE.3` concept comparison or equivalent content. Name any tolerated evidence gap and any gap that blocks design.

The first useful result is small: one organization concept, a few decision-bearing contribution-relation specifications, their intended suppliers and receivers, the selected specialization boundaries, and the conditions under which later Work may realize or reopen them.

Use `C.30` directly when the question is only whether one actual or candidate structure is architecture-relevant. Use `OCE.5` for position identity, `OCE.6` for holder assignments and enabling relations, `OCE.7` for paired product-or-service and organization architecture decisions, and `OCE.9` for realization and organization-capability evidence.

## OCE.4:0.1 - Working Distinctions {#working-distinctions}

| Name used here | Meaning |
| --- | --- |
| specialization boundary | A selected boundary between domains of organization contribution or Work for the current design use. Decide separately which organization units, positions, assignments, and authority relations are needed at that boundary. |
| contribution-relation specification | Possible-future design content naming an intended direct relation kind or predicate, supplier and receiver, result or preserved condition, applicability, acceptance or use condition, exception return, scope, horizon, and evidence need. The specified relation remains proposed until its obtaining conditions are met. |
| contribution relation occurrence | One obtaining occurrence of the admitted direct relation named by a specification or current account. Its predicate, participants, applicability, interval, and evidence must be recoverable independently of the design. |
| contribution structure | An actual `A.22` structure selecting obtaining contribution relation occurrences and their participants for one declared use. Describe a candidate contribution structure as possible-future content until the selected occurrences obtain. Information-use, decision, access, service, coordination, legal-entity, and Work structures can remain separate. |
| contribution architecture | The way selected structures organize the named organization for its intended contribution, qualified under `C.30`. Actual architecture requires the applicable subject relations and architecture relation to obtain; candidate or desired architecture remains claim or description content. |
| position-design need | A need to decide whether one or more expected contributions warrant a stable organization position. `OCE.5` makes that decision and, when warranted, defines the position. |
| acceptance condition | The condition under which a receiver can use or accept the supplied result for the named decision. State the condition in the specification or claim, then use the applicable predicate and evidence to test whether it is met. |
| exception and escalation relation | An obtaining direct relation for returning an unusable result, resolving a conflict, or issuing a decision when ordinary contribution cannot continue. Specify that relation explicitly when designing a possible future. |
| contribution-architecture decision | A decision selecting possible-future organization structures, relation specifications, constraints, and open refinements for later change Work. It does not make those structures or relations actual. |

## OCE.4:1 - Problem Frame {#problem-frame}

Organization design often begins with grouping: functions, products, customers, regions, programmes, professions, or platforms. Grouping helps attention, yet the organization contributes through relations that cross those groups. Evidence is supplied and used, decisions are issued and accepted, materials move, services are provided, resources are accessed, and exceptions return.

A contribution-architecture description makes intended relation specifications, any obtaining occurrences, and their receiving decisions visible while distinguishing proposed from actual relations. It may use several structures because activity grouping, decision representation, legal entities, information use, and service provision answer different questions. The design can then state which boundaries should change and which cross-boundary contributions must remain.

## OCE.4:2 - Problem {#problem}

A target chart can move boxes while preserving the failed contribution path. A topology can give every group a familiar label while leaving the result, receiver, acceptance condition, or exception owner unknown. A generic “interface” can hide that one boundary carries evidence supply, a separate release decision, resource access, provider service, and field information.

The design then cannot guide position definition or realization. Teams infer authority from placement, capability from staffing, and acceptance from handoff. When problems appear, nobody can tell whether the missing element is Work, an assignment, access, an authority relation, a contribution predicate, or evidence that the relation obtains.

## OCE.4:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Specialization | Concentrated knowledge and equipment can improve contribution, while every boundary creates coordination and return needs. |
| Stable ownership | Receivers need reliable contribution, while fixed boxes can preserve obsolete Work and authority assumptions. |
| Several structures | One picture is easy to communicate, while contribution, decision, access, service, legal, and Work structures need not coincide. |
| Participant knowledge | People performing Work and using its results can expose hidden relations, while participation does not transfer design authority. |
| Provider boundaries | External provision can add capability and scale, while contracts, access, recovery, evidence, and decision authority remain separate. |
| Realization | Designers need a usable possible-future account now; later Work may realize the relations, and observations can support claims that they obtain. |

## OCE.4:4 - Solution {#solution}

Design from the intended contribution and the relations needed to produce, use, accept, and return results. Select the few structures that change the current decision. State possible-future crossings as contribution-relation specifications, then make a contribution-architecture decision that fixes only the boundaries and conditions later Work must realize.

Recognition is cheap: one selected organization concept whose result path cannot be stated from supplier to receiving decision is enough to enter. Assurance is relation-specific: each actual contribution, information-use, decision, service, access, material-transfer, or coordination claim needs its own predicate, participants, scope, window, and evidence.

### OCE.4:4.0 - One bounded first design {#one-bounded-first-design}

For a small first use, keep the selected concept and already qualified constraints fixed and resolve one troublesome contribution crossing. Suppose a small engineering organization has the authority and participant inputs needed to decide how compatibility evidence reaches its release integrator. A short design note can state:

> Electrical supplies a configuration-C7 compatibility-evidence package to Integration for Friday's review. Each claimed interface must have a traceable source and test; Integration returns an unsupported claim to Electrical before evidence closure. The design decision keeps electrical expertise with Electrical and package assembly with Integration, using the agreed review time rather than merging the two specializations. Safety acceptance and release remain separate decisions. A missing source or an unworkable review burden reopens this design. Use the first package to test whether the planned supply and exception return actually work.

This is one bounded design result, not evidence that the supply relation already obtains. Reuse the supporting focus, current account, participant correction and decision basis instead of restating them. Add another structure, alternative or specialist return when it can change this decision; a missing authority or protection premise remains a blocker. The same short note can carry the needed content listed below. Elaborate the questions that remain open rather than turning this first use into a full-organization redesign.

### OCE.4:4.1 - Pattern-Use Unfolding {#pattern-use-unfolding}

1. **Bind the design question.** Name the organization, intended outside contribution, selected concept, decision subject, authority, horizon, affected Systems, and first receiving use of the result.
2. **Recover the current relation basis.** Carry forward current Work and direct-relation evidence from `OCE.2`, plus constraints, participants, assumptions, and burdens from `OCE.3`. Record unavailable or incompatible inputs explicitly.
3. **Select structures by question.** Choose contribution, Work, decision, information-use, material-transfer, service, access, coordination, legal-entity, or other structures only when each changes the design. Use process, project, and case viewpoints on the same Work to expose different Method, coordination, state, and authority constraints. Retain the account of obtaining occurrences unless new evidence warrants revision; keep proposed structures and crossings modal. Preserve differences among the selected structures when those differences matter to the decision.
4. **Set specialization boundaries.** Group contribution or Work where shared knowledge, equipment, evidence, decision, locality, customer, product, service, or provider conditions justify it. State the condition and the burden moved by each boundary.
5. **Write contribution-relation specifications.** For every decision-bearing crossing, name the intended direct relation kind or predicate, supplier and receiver Systems, result or preserved condition, applicability, acceptance or use condition, exception return, scope, horizon, and evidence need. Use “interface” only as an orientation label after this content is visible. Do not report an occurrence before its predicate is satisfied.
6. **Obtain participant corrections.** Use participant-facing views to test actual Work, burden, accessibility, safety, provider, and service-continuity assumptions. Record whose contribution changed the design and which material voice is missing.
7. **Compare whole structures.** Compare how each candidate handles intended contribution, coordination load, decision latency, evidence, scarce capability, resilience, provider dependence, affected Systems, reversibility, and change burden. Keep unlike characteristics separate unless a justified aggregation Method exists.
8. **Make the architecture decision.** Use `C.32.PAD`, `C.11`, or the applicable decision pattern for the claim being made. State selected structures, accepted losses, fixed constraints, open refinements, rejected alternatives, and reopen observations. Preserve modal status.
9. **Return position and paired-architecture questions.** Send stable expected-contribution and eligibility needs to `OCE.5`. Send organization/product-or-service correspondence pressure to `OCE.7`. Keep holder, authority, capability, and realization questions with their owners.
10. **Specify realization evidence.** Name which later Work and observations can show that each specified relation obtains, fails, or remains unresolved. Supply design constraints to `OCE.9` without reporting organization capability.
11. **Stop at contribution sufficiency.** Return when affected practitioners can name the contribution path, boundaries, contribution-relation specifications, accepted burdens, open refinements, and observations that reopen the design.

The steps are a reasoning aid. Existing structures may be repaired, new boundaries may be tried, and participant evidence may reopen an earlier decision at any time.

### OCE.4:4.2 - Record the Result {#record-the-result}

| Result position | Required content |
| --- | --- |
| design boundary | Organization, contribution, concept, authority, horizon, first receiver, and affected Systems. |
| selected structures | Structure kind, constituents, occurrence refs when actual, modal structure or relation claims when proposed, declared use, and known losses. |
| specialization decisions | Boundary, reason, expected gain, burden moved, retained cross-boundary contribution, and open refinement. |
| contribution-relation specifications | Intended direct relation kind or predicate, supplier, receiver, result or preserved condition, applicability, acceptance/use, exception return, scope, horizon, and evidence need; occurrence ref only when independently established. |
| participant corrections | Participants sought, design change made, missing voice, burden or protection limit, and unresolved claim. |
| architecture decision | Selected option, fixed constraints, accepted losses, rejected or retained alternatives, modal or actual status, and decision basis. |
| downstream returns | Position needs, paired product/service questions, realization constraints, specialist results, and missing governors. |
| continuation | Realization observations, evidence windows, and the smallest event that reopens the decision. |

### OCE.4:4.3 - What Changes in Practice {#what-changes-in-practice}

Practitioners design the contribution path before finalizing boxes. Every stable boundary has a reason, every decision-bearing crossing has an explicit relation specification, and every target relation retains its modal status until its direct predicate is satisfied. Position, assignment, capability, authority, and provider questions remain available for their own decisions instead of being hidden in the chart.

## OCE.4:7 - Conformance Checklist {#conformance-checklist}

- [ ] The organization, contribution, concept, authority, horizon, and first receiving use are explicit.
- [ ] Each selected structure answers a declared question and states its losses.
- [ ] Specialization boundaries name their gain and moved burden.
- [ ] Every decision-bearing crossing has a contribution-relation specification naming the intended direct relation kind or predicate, supplier, receiver, result, conditions, acceptance/use, exception return, and evidence need.
- [ ] “Interface” does not replace direct relation content.
- [ ] Participant knowledge changes or challenges identifiable design content.
- [ ] Contribution-relation specifications, modal architecture claims, and obtaining relation occurrences remain distinguishable.
- [ ] Position, holder, assignment, capability, authority, product/service, and realization questions have explicit returns.
- [ ] The decision states fixed constraints, open refinements, accepted losses, and reopen observations.

## OCE.4:9 - Consequences {#consequences}

The contribution-architecture design becomes inspectable before a chart is finalized. Position design can start from expected contributions, and realization can test independently obtaining relation occurrences against explicit specifications instead of visual conformity.

The cost is that one page may no longer contain the whole answer. Several structures and evidence returns may be needed, and an attractive topology can remain undecided when a provider, authority, access, safety, or service condition is missing.

## OCE.4:12 - Relations {#relations}

- `OCE.1` supplies the organization, contribution, authority boundary, and affected-System scope. `OCE.2` supplies current Work and direct-relation evidence. `OCE.3` supplies candidate relation structures, assumptions, participants, and burdens.
- `A.22` governs actual selected structures; `C.30` governs possible-future structure and relation content; `A.6.REL` and the applicable domain predicates govern obtaining direct relation occurrences; `C.32.PAD` governs an architecture decision when that use is current.
- `OCE.5` consumes stable position-design needs. `OCE.6` establishes holder assignments and enabling relations. `OCE.7` consumes organization-side structure for paired product-or-service decisions.
- `OCE.9` consumes design constraints and later returns realization evidence. `OCE.12` may consume contribution architecture for leadership-contribution distribution.
- Strategy, Corporate Governance, Operations, Administration, Systems Engineering, finance, legal, labor, safety, privacy, and other specialists supply only their available compatible results or qualified direct sources.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): OCE.1-OCE.3; FPF spec://ai.lev/fpf-spec/contract/A-22#root, spec://ai.lev/fpf-spec/contract/C-30#root, spec://ai.lev/fpf-spec/contract/C-32-PAD#root @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-cgov/contract/CGOV-4#root, spec://ai.lev/fpf-eng-cgov/contract/CGOV-5#root, spec://ai.lev/fpf-eng-oce/contract/OCE-5#root, spec://ai.lev/fpf-eng-oce/contract/OCE-6#root, spec://ai.lev/fpf-eng-oce/contract/OCE-7#root, spec://ai.lev/fpf-eng-oce/contract/OCE-9#root, spec://ai.lev/fpf-eng-syse/contract/SYSE-27#root @status:spec/done

#source spec://ai.lev/fpf-eng-oce/source/OCE-4
