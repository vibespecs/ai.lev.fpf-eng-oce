# OCE.6 - Establish Holder Assignments and Enabling Relations for Organization Change: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Organization Change Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/ORGANIZATION-CHANGE-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## OCE.6:5 - Archetypal Grounding -- PumpWorks Assignment and Access {#archetypal-grounding-pumpworks-assignment-and-access}

`PW-ReleaseEvidenceIntegrationPosition` exists and is vacant. PumpWorks considers `Engineer-E27`, an actual System classified under `SystemsIntegrationEngineerSystemRole`, for the recurring release-evidence integration contribution.

The organization declares `PumpWorksReleaseIntegrationAppointment <: U.SystemRoleAssignment`. Its required participants are the holder System, one assigned role-kind value from the PumpWorks integration-role domain, and the actual `PW-ReleaseEvidenceIntegrationPosition`. Its predicate requires an effective appointment decision issued under the named PumpWorks staffing authority, an in-force position, fixed participants, the required holder acceptance, and no current suspension. One occurrence is the maximal uninterrupted interval during which that predicate remains true for those participants.

Appointment decision `PW-APPT-2026-17` becomes effective on 2026-10-01. The resulting assignment occurrence has `Engineer-E27` as holder and `SystemsIntegrationEngineerSystemRole` as assigned kind. The decision record describes and supports the occurrence because this species gives the effective decision constitutive force; the file alone is not the assignment.

| Needed relation | Current result | Consequence |
| --- | --- | --- |
| release-integration assignment | effective from 2026-10-01 under the species above | Holder and assigned kind are usable for the bounded contribution |
| test-rig access | effective rig-access occurrence under the admitted PumpWorks rig-access predicate for the named rig and release window after provisioning evidence | Integration Work may use the rig within that scope; licence or account evidence outside the interval does not establish access during it |
| provider-artifact repository access | decided but not effective because provider identity federation has not completed | Work entry remains blocked for provider-artifact integration; Administration/security owns the provisioning return |
| release-evidence coordination responsibility | source text says “responsible”, but no admitted predicate and participants are current | Return `missing-governor`; do not convert the assignment or position expectation into a responsibility occurrence |
| safety-evidence acceptance authority | the direct safety-evidence-acceptance authority relation obtains for another named Safety holder under its own predicate and basis | `Engineer-E27` coordinates evidence and cannot issue the acceptance result |
| release authority | the direct release-authority relation obtains for the release director under its own predicate and basis | The integration assignment supplies no release decision power |
| holder capability | current evidence supports the required integration Work envelope except provider-tool use | HCD or a supervised trial can address the capability gap without changing the effective appointment |

The result supplied to `OCE.9` contains one effective assignment, one effective rig-access relation, one pending provider-access relation, two separately held authority relations, a missing responsibility governor, and the bounded capability gap. Return the authorized holder/resource-assignment result to `ADM.2` for the Administration work that depends on it.

### OCE.6:5.1 - Transfer Probes {#transfer-probes}

| Setting | Reusable move | Required return or changed content |
| --- | --- | --- |
| public-hospital emergency flow | Declare the exact appointment or shift-assignment species, recover licensed holder, clinical authority, access, equipment, and current interval | Statutory authority, licensure, labor, fatigue, privacy, safety, and bed/equipment availability can each block entry; verify the required conditions from their current evidence rather than the HR roster alone |
| distributed standards association | Declare bylaw- or election-sensitive assignment species for a volunteer position and recover publication, ballot, repository, and financial access | Employer assignments, volunteer acceptance, elected term, member authority, several time zones, and employer permission remain separate; no executive staffing predicate is imported |

## OCE.6:6 - Bias-Annotation {#bias-annotation}

| Recurring bias | Likely drift | Repair |
| --- | --- | --- |
| roster truth | A name in a staffing table is treated as an effective assignment. | Apply the direct species predicate and current interval. |
| title authority | Seniority or position title supplies authority. | Recover the independently obtaining authority relation. |
| budget readiness | Budget or headcount is treated as usable resource access. | Identify the resource, allocation/access predicate, scope, and effectivity. |
| capability by appointment | Selection is treated as ability. | Use holder-dependent capability evidence and fit for the Work envelope. |
| record completion | Provisioning or HR record closure is treated as organization realization. | Verify the direct relations needed by the receiving contribution. |
| universal assignment | Every appointment receives the same binary holder/kind form. | Declare exact species and every real participant that changes predicate or identity. |

## OCE.6:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | Repair |
| --- | --- |
| “The position is staffed, so the team is ready.” | Recover the assignment occurrence, capability fit, authority, permissions, resources, access, provider conditions, and receiving Work separately. |
| “RACI assigns responsibility.” | Treat the matrix as a description; apply an admitted responsibility predicate or return a missing governor. |
| “The manager delegated it in chat.” | Recover the communicative Work, authority, delegation predicate, participants, scope, effectivity, acceptance, and evidence required by the applicable domain. |
| “The tool licence grants access.” | State the actual access or permission occurrence and its current scope; licence ownership can be a separate condition. |
| “The employee completed training, therefore can perform.” | Use HCD evidence and `A.2.2` to establish the holder's bounded ability and its fit to the receiving demand; training completion remains a separate result. |
| “The assignment ended because the record is stale.” | Distinguish missing current evidence from demonstrated predicate failure; record the occurrence as ended only when its direct identity law supports that conclusion. |

## OCE.6:10 - Rationale {#rationale}

An assignment answers who holds which local system-role kind under one direct species. Organization contribution often needs more: authority to decide, responsibility to respond, access to resources, provider commitments, and capability under current conditions. These requirements matter together, but each calls for its own claim and evidence.

Separating specification, decision, and effectivity also gives the practitioner an honest path from design to actuality. A partial result can guide the next action without claiming that the complete arrangement exists.

## OCE.6:11 - SoTA-Echoing {#sota-echoing}

### OCE.6:11.1 - Current-Line Selection for Assignment and Enabling Relations {#current-line-selection-for-assignment-and-enabling-relations}

| Comparison position | Selected result for practice |
| --- | --- |
| Current question | Which holder assignment and enabling relations actually support the bounded contribution now? |
| Selected current line | Begin from the contribution and interdependent Work, select or declare the exact assignment species, and verify assignment, authority, responsibility, permission, resource, access, provider, and capability claims through their separate predicates and current intervals. Return partial and missing states rather than a completed staffing row. |
| Serious alternative | Use a roster, RACI, appointment letter, function-allocation table, budget, or provisioned account as the complete readiness result. |
| When the alternative is sufficient | Such an artifact is sufficient as a retrieval view when every relied-on direct relation is already established, current, and recoverable from its owner. |
| When the selected line changes action | If Work entry depends on another owner, predicate, effectivity window, or evidence for consent, access, authority, resources, provider support, or capability, verify the affected claim separately and return its exact gap. |
| Reopen | Reconsider when actual use exposes a recurring relation state the result cannot express, a direct source changes the holder/enabling action, or a needed relation has no applicable definition. |

### OCE.6:11.2 - Source Contributions and Boundaries {#source-contributions-and-boundaries}

| Source line | Retained contribution | Use boundary |
| --- | --- | --- |
| Current FPF `A.2.1`, `A.2.2`, `A.6.REL`, `A.13`, `A.15.1`, `F.6`, and `A.10` | Direct assignment species, holder capability, relation obtaining, performer, Work, assignment-bound attribution, and evidence remain separate. | Obtain responsibility, authority, resource, and access predicates from their owning domains; select a coordination Method for the organization’s contribution. |
| Joseph and Sengul, [current organization-design review](https://doi.org/10.1177/01492063241271242) | Configuration, control, channelization, and coordination expose different organization-design features and consequences. | Use these design features to find the local assignments and enabling relations that need current evidence. |
| Grote et al., [contribution-based engineering role modeling](https://doi.org/10.1109/ISSE65546.2025.11370103) | Required contributions and stakeholder evidence can expose candidate holder/role bundles and gaps. | Use the bundles as candidate input; establish assignments and positions, recover authority, and assess capability separately. |
| Fraccaroli, Zaniboni, and Truxillo, [work-design review](https://doi.org/10.1146/annurev-orgpsych-081722-053704) | Technology, algorithmic management, diverse work arrangements, and affected-person outcomes change holder and enabling conditions. | Recover assignment identity and authority and access predicates from the applicable local rules. |
| Waterson et al., [function allocation for responsible AI](https://publications.ergonomics.org.uk/uploads/Function-Allocation-for-Responsible-Artificial-Intelligence-How-do-we-allocate-trust-and-responsibility.pdf) | Allocation should expose interdependence, joint operation, decision points, responsibility points, outcomes, authority, and dynamic trust. | The evidence comes from an early framework and small experiments. Test its fit for the local human–AI arrangement; qualify responsibility allocation and authority transfer under their own rules. |

Reopen when a recurring assignment species or enabling relation lacks an applicable definition, when a stronger direct source changes the holder/enabling action, or when actual use shows that the partial-result states cannot guide Work entry.


## OCE.6:End {#end}
