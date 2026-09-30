# OCE.5 - Define Organization Positions {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Organization Change Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/ORGANIZATION-CHANGE-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

> **Type:** Method pattern
> **Status:** Eternal alpha
>
> **Primary working result:** **organization-position descriptions and establishment or continuation decisions** that name the owning organization, effective establishment basis, identity-bearing expected contributions and assignment-eligibility criteria, continuation conditions, and evidence needs without asserting a holder or performed Work.

## OCE.5:0 - Use This When {#use-this-when}

Use this pattern when an organization needs a stable institutional position for expected contributions, but a title, job description, team label, or current holder is being used as the position itself. Enter when vacancy, holder replacement, eligibility, establishment, abolition, or continuation changes the decision.

Begin with a bounded organization and contribution need. A compatible `OCE.4` result is useful when the position follows from a new contribution architecture; an existing law, charter, bylaw, appointment scheme, or organization decision may instead supply the basis for a current position.

The first useful result names one owning organization, one position identity, its establishment and continuation basis, the expected contributions that distinguish it, the eligible system-role kinds, and a description usable by `OCE.6`. A vacant position is a complete result when no holder decision is current.

Use `A.2.1` directly when only a holder assignment is needed and no organization-position identity changes the use. Use `OCE.6` to establish assignments, authority, responsibility, resource, or access relations. Use Human Capability Development for developing a person's capability and applicable labor, legal, governance, compensation, privacy, or safety practice for their own decisions.

## OCE.5:0.1 - Working Distinctions {#working-distinctions}

| Name used here | Meaning |
| --- | --- |
| organization position | An organization-dependent institutional subject whose identity depends on one owning organization, an effective establishment basis, and identity-bearing expected-contribution and assignment-eligibility criteria. |
| establishment basis | The applicable constitutive rule and the authorized act or other facts satisfying it for the owning organization. A statute, charter, bylaw, or organization decision may supply the rule or its application basis. A document is evidence or a carrier unless the applicable rule gives its issuance constitutive effect. |
| continuation basis | The current facts and governed relation under which the position remains in force with the same identity-bearing criteria. |
| expected contribution | A possible-future contribution expected from a holder assigned through an eligible system-role kind. It is position content, not performed Work or evidence of result. |
| assignment-eligibility criteria | Criteria selecting which local system-role kinds may be assigned in relation to the position. Classify a particular System, assess its capability, and establish its assignment separately. |
| position description | An episteme describing the position, basis, expected contributions, eligibility, conditions, and neighboring requirements. Editing the description changes the episteme first. |
| holder | One actual `U.System` that may participate in an assignment concerning the position. A position can be vacant, and one System can hold several assignments. |
| title | A designation useful for recognition and retrieval. Title continuity does not prove position continuity; title change does not by itself reidentify the position. |

## OCE.5:1 - Problem Frame {#problem-frame}

Organizations need persistent contribution loci that survive ordinary holder changes. A safety-acceptance position, treasurer position, editorial-chair position, or release-integration position can remain while vacant, while different eligible Systems are assigned, or while its description is republished.

The persistent subject is institution-dependent. Its establishment, identity, and continuation depend on the owning organization and its applicable authority. Expected contributions and eligibility make the position usable for organization design, while the actual holder, assignment, capability, authority, responsibility, and Work remain separately governed.

## OCE.5:2 - Problem {#problem}

When title, position, role kind, holder, and assignment are merged, ordinary changes become ambiguous. Replacing a person can appear to abolish a position. Renaming a title can appear to create one. Readers can mistake a job description for a grant of authority or proof of capability. A vacant position can disappear from the model even though the organization still relies on its expected contribution.

The reverse error models every recurring contribution or temporary assignment as a position. The organization records supposed positions without an establishment basis, and downstream users cannot tell which vacancies, appointments, or descriptions have institutional force.

## OCE.5:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Continuity | The organization needs stable contribution expectations, while holders, descriptions, and Work change. |
| Local law | Position identity depends on the organization and applicable basis, while reusable modeling needs a common working move. |
| Contribution breadth | One position can expect several contributions, while a broad bundle can hide incompatible eligibility or authority. |
| Eligibility | The position needs qualified kinds of assignee, while kind membership, capability, and assignment require separate evidence. |
| Vacancy | Planning and governance may need the position while no holder exists. |
| Description usability | Practitioners need a readable description that distinguishes the institutional position from its description and holder assignments. |

## OCE.5:4 - Solution {#solution}

Define the position from its owning organization and institutional contribution, then recover the direct establishment and continuation predicates that give it force. Select only the expected contributions and eligibility criteria that distinguish the position for its current use. Publish a description after the position claim is recoverable, or publish an explicitly proposed description while establishment remains a future decision.

Recognition is cheap: enter when a decision about a position is blocked by confusion among vacancy, holder change, and description revision. Assurance is stronger: a current position claim needs its owning organization, direct establishment basis, identity-bearing criteria, continuation condition, scope, interval, and evidence.

### OCE.5:4.0 - One first position description {#one-first-position-description}

Suppose a standards association's effective bylaw 8 already establishes an editorial-chair position, its expected contribution and its eligible local role kind. An organizer preparing an appointment can begin with one short description:

> The association's EditorialChair position is established by bylaw 8 and is currently vacant. It remains the same position while that basis and its identity-bearing criteria remain in force. It expects amendment-packet preparation and the return of unsupported evidence to contributors. The association's defined MemberEditorSystemRole kind is eligible for assignment. Return publication access as an enabling need for the separate appointment decision. Holder selection, authority, and effective access remain to be established.

Return that description and its bylaw basis to the person arranging the assignment. The appointment, candidate's capability and effective access remain OCE.6 or direct-owner questions. If the establishment or continuation basis is missing, return a proposed description or unresolved position claim instead.

The fuller questions below become useful when the position's identity, eligibility, contribution or institutional basis is unresolved or must change. Reuse current answers and add only the neighboring requirements that change this position or the next assignment; no separate form is required.

### OCE.5:4.1 - Pattern-Use Unfolding {#pattern-use-unfolding}

1. **Bind the position question.** Name the owning organization, intended contribution, current design or operating need, decision subject, authority, horizon, and first receiver of the position description.
2. **Recover candidate claims.** Collect the current charter, bylaws, organization decisions, position descriptions, title uses, contribution architecture, assignments, holder facts, and observed Work. State what each source can establish.
3. **Find the establishment predicate.** Identify the applicable domain predicate, authority, act or relation that creates the position, its effective condition, and its owning organization. If the applicable predicate or establishment basis is unavailable, retain a proposed description or unresolved position claim.
4. **Set the identity-bearing criteria.** State the expected contributions and assignment-eligibility criteria that distinguish this position. Add another criterion only when changing it would change which institutional position the organization means.
5. **Specify eligible role kinds.** Name the exact local system-role-kind domain and criteria relevant to assignment. Keep System classification, candidate-holder capability, and actual assignment as later questions.
6. **Separate neighboring relations.** State responsibility, authority, permission, resource, access, compensation, reporting, or membership requirements as separately governed needs. Include one only when it changes the position design or downstream assignment.
7. **State continuation and termination.** Name the basis remaining in force, identity-bearing criteria that must remain, effectivity window, abolition or suspension condition, and evidence that triggers re-evaluation. Holder or description change alone preserves identity unless the applicable basis says otherwise.
8. **Write the position description.** Give the title or designations, owner, basis, expected contributions, eligibility, scope, conditions, neighboring requirements, vacancy status, and source return. Mark a proposal as possible-future content.
9. **Test identity changes.** Replay vacancy, holder replacement, title change, description correction, changed expected contribution, changed eligibility, abolition, and re-establishment. State which preserve identity and which require a new or unresolved position claim.
10. **Return assignment input.** Supply position identity, eligible kinds, expected contributions, establishment/continuation facts, and enabling needs to `OCE.6`. Return capability, legal, labor, governance, compensation, privacy, or safety questions to their owners.
11. **Stop at position sufficiency.** Return when a reader can tell whether the position exists, what makes it the same position, which contributions it expects, who may be assigned by kind, and what observation reopens that account.

### OCE.5:4.2 - Record the Result {#record-the-result}

| Result position | Required content |
| --- | --- |
| use boundary | Owning organization, contribution need, decision, authority, horizon, and first receiver. |
| position identity | Position reference or proposed reference, owning organization, direct establishment predicate and basis, identity-bearing criteria, scope, and interval. |
| expected contributions | Receivers, results or preserved conditions, applicability, acceptance needs, and relation to `OCE.4` when current. |
| eligibility | Exact local system-role kinds, criteria, exclusions justified by the contribution, and unresolved classification or capability questions. |
| neighboring requirements | Separately governed authority, responsibility, permission, access, resource, compensation, reporting, membership, legal, or safety needs that change later assignment. |
| continuation | Current basis, continuation evidence, suspension or abolition condition, and identity-changing observations. |
| description | Title/designations, content, source return, publication boundary, current or proposed status, and known losses. |
| assignment return | Inputs and gaps supplied to `OCE.6`; no holder or Work assertion. |

### OCE.5:4.3 - What Changes in Practice {#what-changes-in-practice}

Practitioners can keep a position visible while vacant and can replace a holder without rewriting the position. They can also change a title or description without claiming an institutional change. When expected contribution or eligibility changes materially, the organization makes that identity question explicit instead of hiding it in a revised document.

## OCE.5:7 - Conformance Checklist {#conformance-checklist}

- [ ] One owning organization and one current or proposed position are explicit.
- [ ] The establishment predicate, authority, basis, effectivity, and evidence are stated or a missing governor is returned.
- [ ] Identity-bearing expected contributions and eligibility criteria are distinguishable from descriptive detail.
- [ ] Eligible system-role kinds come from an exact local domain; eligibility does not classify or assign a holder.
- [ ] Vacancy, holder change, title change, description change, identity-criterion change, abolition, and re-establishment have explicit dispositions.
- [ ] Authority, responsibility, permission, access, resources, compensation, reporting, membership, capability, and Work use their own relations when current.
- [ ] The position description states current or proposed status and its source return.
- [ ] The `OCE.6` return contains no inferred assignment or capability.

## OCE.5:9 - Consequences {#consequences}

Position continuity, vacancy, assignment, and description revision become manageable. Organization design can name persistent expected contributions while separately recording the actual holders and position descriptions.

The cost is local grounding. Different organizations can establish positions through different legal, governance, membership, or organization predicates. A reusable title list cannot replace that work.

## OCE.5:12 - Relations {#relations}

- `OCE.1` supplies the organization and contribution boundary. `OCE.2` supplies current descriptions, assignments, holders, Work, and gaps in the position-establishment or identity basis. `OCE.3` and `OCE.4` supply possible position needs and expected contributions.
- `A.2.1` defines direct assignment species and occurrences. `A.2.2` defines holder capability. `A.6.REL` governs direct relation obtaining and occurrence identity.
- `OCE.6` consumes position identity, eligibility, expected contributions, effectivity, and enabling needs; a position must have its own establishment basis when one is needed.
- Legal, labor, governance, compensation, privacy, safety, licensing, membership, and other domain practices govern their own predicates and decisions. An OCE position description can cite their available results without absorbing them.
- `OCE.9` later tests organization capability and actual relations. That test requires organization-level evidence beyond the holder-assignment and vacancy facts.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-oce/contract/OCE-1#root; conditional spec://ai.lev/fpf-eng-oce/contract/OCE-4#root; FPF spec://ai.lev/fpf-spec/contract/A-2-1#root, spec://ai.lev/fpf-spec/contract/A-6-REL#root @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-cgov/contract/CGOV-4#root, spec://ai.lev/fpf-eng-oce/contract/OCE-6#root @status:spec/done

#source spec://ai.lev/fpf-eng-oce/source/OCE-5
