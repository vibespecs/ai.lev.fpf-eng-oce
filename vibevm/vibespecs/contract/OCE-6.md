# OCE.6 - Establish Holder Assignments and Enabling Relations for Organization Change {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Organization Change Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/ORGANIZATION-CHANGE-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

> **Type:** Method pattern
> **Status:** Eternal alpha
>
> **Primary working result:** the **obtaining holder assignments and enabling relations** needed for a bounded organization contribution, together with their predicates, participants, authority, effectivity, evidence, unresolved gaps, and any possible-future specifications that have not yet taken effect.

## OCE.6:0 - Use This When {#use-this-when}

Use this pattern when a contribution architecture or position design names who must contribute, yet the actual holder assignment, authority, responsibility, resource, access, permission, or other enabling relation is unclear or not effective. Enter when a staffing decision, appointment letter, budget, licence, roster, or tool account is being treated as proof that the complete arrangement now obtains.

Begin with a bounded contribution need and candidate holder Systems. Use an `OCE.5` position when the assignment depends on one; otherwise begin from the direct contribution and the exact local system-role kind. Recover the authority under which each change can be made.

The first useful result can be partial: one effective assignment, its exact species and interval, separately effective enabling relations, and a visible list of pending, contradicted, expired, or missing relations. A truthful blocker is useful when authority or a direct predicate is absent.

Use `A.2.1` directly when the assignment species and occurrence are already known and no OCE coordination changes the result. Use Administration for participant records, provisioning, or service cases; Human Capability Development for developing a holder's capability; Corporate Governance, legal, labor, safety, security, finance, or another specialist practice for their decisions and predicates; and `OCE.9` for organization-capability realization.

## OCE.6:0.1 - Working Distinctions {#working-distinctions}

| Name used here | Meaning |
| --- | --- |
| candidate holder | An actual `U.System` being considered for an assignment. Assess classification, eligibility, capability, consent, and assignment under the criteria applicable to the proposed contribution. |
| assignment specification | Possible-future content naming a proposed direct assignment species, participants, applicability, intended interval, and conditions. |
| assignment decision | A separately governed decision to establish, change, suspend, or end an assignment. It creates an occurrence only when the admitted species predicate gives that decision constitutive effect and every condition is satisfied. |
| assignment occurrence | One obtaining occurrence of a directly declared species under `U.SystemRoleAssignment`, with holder, exact local system-role kind, every real additional participant, predicate, applicability, and uninterrupted interval recoverable. |
| position-sensitive assignment | An assignment species whose direct predicate requires an actual `OCE.5` organization position as a participant. The position is included only because it changes predicate or identity. |
| enabling relation | Readable OCE wording for one separately admitted authority, responsibility, permission, resource-allocation, access, membership, commitment, or other relation needed for the contribution. It is not a new root relation family. |
| capability evidence | Evidence bearing on a qualified ability claim about the holder under `A.2.2`. Assignment, title, position, training, resource, or tool presence does not replace it. |
| assignment-and-enabling result | The account of direct relation claims returned by this pattern, including effective relations, proposed changes, and unresolved conditions. |

## OCE.6:1 - Problem Frame {#problem-frame}

Organization change becomes operational when actual Systems hold effective assignments and the other relations needed for their contribution obtain. An appointment can identify a holder and system-role kind, while resource access, decision authority, responsibility, equipment availability, provider commitment, and capability remain separate. Each has its own participants or bearer, governing conditions, basis, and effective interval.

The practitioner therefore coordinates a small set of direct changes rather than filling one staffing row. They decide what should become effective, obtain the acts or services required by each owner, and then verify the relations that actually obtain.

## OCE.6:2 - Problem {#problem}

A chart or roster can show a name next to a position before an appointment is effective. A signed appointment can coexist with missing system access. A budget can exist without a resource-allocation relation for the Work. Responsibility can be stated without an admitted predicate. A capable person can lack authority, while an authorized holder can lack capability for the current envelope.

When these claims are bundled, later Work fails in ways that look personal or motivational. The organization cannot identify the exact missing relation, its owner, or its effective window. Conversely, a completed provisioning ticket can be mistaken for the whole organization change.

## OCE.6:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Speed | Contributions need holders quickly, while premature effectiveness claims hide blockers. |
| Exact species | Reusable assignment logic is valuable, while appointments, shifts, elected offices, provider assignments, and equipment roles have different participants and predicates. |
| Capability and authority | Both can be necessary for Work, while neither implies the other. |
| Resource readiness | Access and equipment can enable contribution, while their presence does not assign a holder or establish capability. |
| Several owners | Organization change needs a coherent result, while legal, governance, labor, security, finance, administration, and safety retain their authority. |
| Currentness | Assignment and access can expire or be suspended, while stale records remain visible. |

## OCE.6:4 - Solution {#solution}

Start from the contribution and select the exact assignment species, then establish every needed neighboring relation through its own owner and predicate. Keep proposed, decided, effective, contradicted, expired, and missing states separate. Return only relations whose obtaining conditions are satisfied, along with explicit gaps that change Work entry or later realization.

Recognition is cheap: one required contribution with an ambiguous holder or missing enabling condition is enough to enter. Assurance is predicate-specific: the holder, local role kind, additional participants, authority, applicability, extent, basis, evidence, and currentness of every relied-on relation must be recoverable.

### OCE.6:4.0 - One bounded first return {#one-bounded-first-return}

For a small first use, take one contribution with a current, reusable assignment result and resolve the enabling gap that changes its next Work. In the PumpWorks case below, verify the appointment's continued effectivity and obtain the repository-access owner's current result. The practitioner can return this short account to the person arranging the integration:

> E27's release-integration appointment is effective from 2026-10-01 under PW-APPT-2026-17 and the declared PumpWorks appointment species. Its participants and uninterrupted interval are recoverable from that result. Provider-repository access is decided but not effective because identity federation is unfinished. Administration/security owns the access return. Provider-artifact integration remains blocked. The appointment still obtains; effective access and capability for provider-tool use require separate evidence.

Keep the existing assignment, authority and capability evidence with this account rather than reproducing it. When the access owner returns effective access, reassess the dependent Work; any other required but missing relation or capability remains a blocker. The fuller questions below are for new, unresolved or changed claims. This first use does not require re-declaring a current assignment species or surveying every possible enabling relation.

### OCE.6:4.1 - Pattern-Use Unfolding {#pattern-use-unfolding}

1. **Bind the contribution and use.** Name the organization, contribution, position when current, receiving decision or Work, scope, horizon, effectivity need, affected Systems, and first consumer of the result.
2. **Recover authority and participation conditions.** Identify who may establish or end each assignment and enabling relation, under which predicate, basis, scope, and interval. Obtain consent, labor, election, membership, or protection results when their owners require them.
3. **Identify candidate holder Systems.** Recover each actual System, exact local system-role-kind classification when needed, relevant capability evidence, availability, conflicts, and current assignments. Keep preference and development needs separate.
4. **Select or declare the direct assignment species.** Begin with an ordinary claim, such as “E27 is appointed as release integrator under the PumpWorks appointment conditions.” Reuse an applicable species under `A.2.1`; declare one only when the needed species is missing. Recover the holder slot, exact local assigned-kind domain, every real additional participant, predicate, applicability, and occurrence-identity law. Add an `OCE.5` position participant only when the species truly depends on it. For a new species, use `A.2.1:4.1–4.4` and `A.6.REL` together with the organization's applicable assignment rules. These sources explain participants, obtaining conditions and episode identity; the organization must supply its own appointment or election rule. If that rule or a required participant kind is absent, return the missing governor for this assignment. Reuse an existing species without declaring it again. Expose an episode identifier only when the receiving use must distinguish or cite that episode.
5. **Specify the proposed assignment.** State candidate holder, assigned kind, position or locus when required, intended interval, conditions, conflicts, and basis. Preserve possible-future status.
6. **Make or obtain the assignment decision.** Use the applicable decision and authority. Determine whether and when the direct species predicate becomes satisfied; a document or record is constitutive only when that predicate says so.
7. **Establish neighboring enabling relations.** For each required authority, responsibility, permission, resource, access, membership, commitment, compensation, provider, or equipment relation, obtain the direct owner's result and satisfy its predicate. Return `missing-governor` rather than inventing a general relation.
8. **Verify effectivity and contradiction.** Observe or otherwise ground the relation occurrence, participants, interval, basis, and currentness. Classify each claim as proposed, decided-not-effective, effective, contradicted, expired, suspended, or missing.
9. **Check capability separately.** Use `A.2.2` for the holder's ability under the required Work envelope. State whether a capability result supports current use, requires development, or remains unavailable. Assignment remains usable as a relation claim even when capability fit fails.
10. **Coordinate records and provision.** Use Administration for participant state, access cases, provisioning, reconciliation, and records when available. A record supports retrieval and evidence; the direct relation remains the result consumed here.
11. **Return precise downstream results.** Supply effective assignments and enabling relations to `OCE.9`; send the authorized holder/resource-assignment result to `ADM.2` under `XRI-07`; send gaps to the exact owner whose action can change them.
12. **Stop at entry sufficiency.** Return when the people preparing the receiving Work or realization decision can tell which relations obtain now, which conditions block entry, which owner must act, and which observation reopens the account.

### OCE.6:4.2 - Record the Result {#record-the-result}

| Result position | Required content |
| --- | --- |
| use boundary | Organization, contribution, position or direct need, receiving Work/decision, scope, horizon, and first consumer. |
| holder basis | Candidate Systems, local kinds and classifications when current, capability references, availability, conflicts, and evidence limits. |
| assignment species | Species, holder, assigned-kind domain, additional participants, predicate, applicability, identity law, and authority. |
| assignment branches | Proposed specification, decision, effective occurrence, interval, basis, evidence, and proposed/decided-not-effective/effective/contradicted/expired/suspended/missing disposition. |
| enabling relations | One row per direct authority, responsibility, permission, resource, access, membership, commitment, provider, equipment, or other relation actually needed; predicate, participants, basis, interval, evidence, and gap. |
| capability boundary | Required Work envelope, current capability result or unavailable return, and development or alternative-holder question. |
| records and provision | Available Administration or specialist result, record/source reference, and the direct relation it supports without replacing. |
| continuation | Work-entry effect, downstream receivers, expiring conditions, contradictions, and smallest reopen observation. |

### OCE.6:4.3 - What Changes in Practice {#what-changes-in-practice}

Practitioners stop asking whether a position is “filled” as if that settled readiness. They can point to the exact effective assignment, authority, access, resource, and capability claims needed by the receiving Work. Missing relations become actionable returns to their owners instead of character judgments about a holder.

## OCE.6:7 - Conformance Checklist {#conformance-checklist}

- [ ] The contribution, receiving Work or decision, position when current, scope, horizon, and first consumer are explicit.
- [ ] Every assignment uses one directly declared `A.2.1` species with exact participants, predicate, applicability, identity, and interval.
- [ ] The position participates only when it changes the direct assignment species.
- [ ] Proposed, decided-not-effective, effective, contradicted, expired, suspended, and missing branches remain distinguishable.
- [ ] Authority, responsibility, permission, resource, access, membership, commitment, provider, equipment, and compensation relations use direct predicates.
- [ ] Capability is holder-dependent and separately evidenced for the required Work envelope.
- [ ] Records and provisioning support but do not replace direct relations.
- [ ] Downstream results name only relations that obtain and the exact gaps that block use.

## OCE.6:9 - Consequences {#consequences}

Assignments and enabling relations become usable by later Work, Administration, and capability realization without being bundled. Expiration, suspension, partial provision, and missing authority can be handled locally.

The cost is coordination across owners. Legal authority, security permission, labor consent, finance allocation, and specialist capability require the relevant owners’ actions and evidence; the coordinated design must make those dependencies visible.

## OCE.6:12 - Relations {#relations}

- `OCE.4` supplies contribution and enabling needs. `OCE.5` supplies position identity, eligibility, expected contributions, and effectivity when a position-sensitive assignment is current.
- `A.2.1` governs assignment species and occurrences. `A.2.2` governs capability. `A.13` and `A.15.1` govern performer and Work; `F.6` applies only when precise assignment-bound attribution is needed.
- `OCE.9` consumes effective assignments and enabling relations for realization and organization-capability evidence. `ADM.2` may consume the authorized holder/resource-assignment result under `XRI-07`.
- Administration can supply records, access cases, provision, and reconciliation. Corporate Governance, legal, labor, security, safety, finance, privacy, HCD, and other practices keep their predicates, decisions, and evidence.
- When a sibling result is unavailable, use a qualified direct source if it answers the needed question; otherwise retain an explicit missing result.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-oce/contract/OCE-4#root; conditional spec://ai.lev/fpf-eng-oce/contract/OCE-5#root; FPF spec://ai.lev/fpf-spec/contract/A-2-1#root, spec://ai.lev/fpf-spec/contract/A-2-2#root, spec://ai.lev/fpf-spec/contract/A-6-REL#root @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-adm/contract/ADM-2#root, spec://ai.lev/fpf-eng-mkt/contract/MKT-11#root, spec://ai.lev/fpf-eng-oce/contract/OCE-10#root, spec://ai.lev/fpf-eng-oce/contract/OCE-12#root, spec://ai.lev/fpf-eng-oce/contract/OCE-9#root, spec://ai.lev/fpf-eng-syse/contract/SYSE-27#root @status:spec/done

#source spec://ai.lev/fpf-eng-oce/source/OCE-6
