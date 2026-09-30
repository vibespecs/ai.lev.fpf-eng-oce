# OCE.5 - Define Organization Positions: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Organization Change Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/ORGANIZATION-CHANGE-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## OCE.5:5 - Archetypal Grounding -- PumpWorks Release-Evidence Integration Position {#archetypal-grounding-pumpworks-release-evidence-integration}

The `OCE.4` design requires stable coordination of electrical compatibility evidence, platform test results, provider model artifacts, unresolved assumptions, and the evidence package used by Safety. PumpWorks decides that this expected contribution should persist beyond one release or holder.

`PumpWorks-EngineeringOrg` is the owning organization. Authorized organization decision `PW-OD-2026-04` establishes `PW-ReleaseEvidenceIntegrationPosition` from 2026-10-01 while the decision remains effective. The identity-bearing expected contribution is to maintain the traceable release-evidence assembly and return unresolved mismatches to the participants supplying the underlying evidence. The eligible local system-role kinds are `SystemsIntegrationEngineerSystemRole` and `ReleaseEvidenceCoordinatorSystemRole` under the current PumpWorks role-kind scheme.

The position description names coordination and evidence-return expectations; safety-evidence acceptance and release authority remain with their separate decision-makers. The description records test-environment and provider-artifact access as enabling needs for `OCE.6`. The position is initially vacant.

| Change | Position disposition |
| --- | --- |
| a holder is assigned on 2026-10-01 | Same position; `OCE.6` governs the assignment occurrence |
| holder leaves and the position becomes vacant | Same position while `PW-OD-2026-04` and identity-bearing criteria remain in force |
| title changes to “Release Evidence Coordinator” | Same position if the designation changes and the identity-bearing criteria do not |
| description clarifies a reporting view | Same position; the description episteme changes |
| expected contribution changes from evidence integration to issuing the release decision | Reopen identity and authority; do not silently continue the same position |
| `PW-OD-2026-04` is abolished with no continuation rule | The current position ceases; later re-establishment needs a new or explicitly continued identity basis |

The result supplied to `OCE.6` contains the position, eligible kinds, expected contribution, access needs, effectivity, and vacancy. It contains no candidate-holder selection or capability conclusion.

### OCE.5:5.1 - Transfer Probes {#transfer-probes}

| Setting | Reusable move | Required return or changed content |
| --- | --- | --- |
| public-hospital emergency flow | Define a clinical coordination or acceptance position from the hospital's applicable statutory and governance basis and its contribution | Clinical authority, licensure, labor agreement, shift assignment, privacy, and patient-safety conditions remain separate and can block assignment |
| distributed standards association | Define an editorial-chair or treasurer position from bylaws, member decision, expected contribution, eligibility, term, and continuation rules | Election, volunteer availability, employer permission, financial authority, publication access, and actual Work remain separate; no executive hierarchy is assumed |

## OCE.5:6 - Bias-Annotation {#bias-annotation}

| Recurring bias | Likely drift | Repair |
| --- | --- | --- |
| title realism | A familiar title is treated as the position identity. | Recover owner, establishment basis, expected contribution, eligibility, and continuation. |
| incumbent anchoring | The current holder's skills and habits define the position. | Start from the organization contribution and keep holder-specific capability or preference outside the identity. |
| document constitution | Publishing or editing a job description is treated as establishment. | Apply the direct establishment predicate and keep the description as an episteme. |
| hierarchy default | Every position is placed in a reporting tree. | Add reporting, authority, or membership only through their direct relations and when they change use. |
| vacancy erasure | An unfilled position disappears from organization design. | Retain the position while its establishment and continuation conditions obtain. |
| durable-object inflation | Every temporary contribution or assignment becomes a position. | Require an institutional establishment basis and stable identity-bearing criteria. |

## OCE.5:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | Repair |
| --- | --- |
| “The product manager role owns the roadmap.” | Recover whether the phrase denotes a position, role kind, assignment, authority, responsibility, contribution expectation, or current Work; establish each needed claim directly. |
| “Create a position by adding a box to the chart.” | Obtain the authorized establishment decision or other applicable constitutive basis, then publish the chart as a view. |
| “The position requires strategic thinking and leadership.” | State the expected contribution and eligible role kinds first; send measurable holder capability and person-development needs to their owners. |
| “The incumbent defines the job.” | Use observations of Work and participants’ knowledge as evidence, then decide the position from the organization’s intended contribution and institutional basis. |
| “No holder means no position.” | Check continuation conditions. Record vacancy and the assignment need separately. |

## OCE.5:10 - Rationale {#rationale}

A position is useful because it persists across ordinary holder and Work changes. That persistence requires an organization-dependent identity rather than a label or person. Expected contribution and eligibility provide the stable organization-design content; establishment and continuation provide institutional force.

Keeping the position separate from `U.SystemRoleAssignment` also preserves cases where an assignment has no position and cases where a position is vacant. It lets `A.2.1` retain exact assignment species while OCE supplies the domain subject needed by organization design.

## OCE.5:11 - SoTA-Echoing {#sota-echoing}

### OCE.5:11.1 - Current-Line Selection for Position Design {#current-line-selection-for-position-design}

| Comparison position | Selected result for practice |
| --- | --- |
| Current question | Does this recurring expected contribution need a stable organization-dependent position, or can direct assignments, tasks, projects, or other arrangements carry it? |
| Selected current line | Establish or preserve a position only when vacancy, holder replacement, continuation, institutional force, and identity-bearing expected contribution or eligibility change the decision. Otherwise keep the contribution and direct assignments without inflating a durable position. |
| Serious alternative | Treat the job title, job description, chart box, role taxonomy, or fully deconstructed task/project market as the default organization design. |
| When the alternative is sufficient | A direct task, project, or assignment is sufficient when no stable institutional locus must persist across holders and no establishment or continuation claim is needed. |
| When the selected line changes action | If the organization must recognize vacancy, continuation, abolition, eligibility, or the same contribution locus across holder changes, recover the owning organization and establishment predicate, then define identity-bearing criteria. |
| Reopen | Reconsider when unlike institutional settings defeat the identity test, current work-design evidence changes the position versus direct-assignment choice, or the institutional locus must persist outside any one owning organization. |

### OCE.5:11.2 - Source Contributions and Boundaries {#source-contributions-and-boundaries}

An organization position can persist across holders, carry several expected contributions and remain vacant. Determine which position is in force from the organization's rules for establishing and continuing it.

| Source line | Retained contribution | Use boundary |
| --- | --- | --- |
| Current FPF `A.2.1`, `A.2.2`, `A.6.REL`, `A.10`, `A.13`, and `A.15.1` | Role-kind classification, assignment, capability, relation obtaining, evidence, performer, and Work remain separately governed. | FPF does not currently define the organization-dependent institutional position. |
| Rogiers and Collings, [job-deconstruction paradoxes](https://doi.org/10.5465/amp.2022.0236) | Task- and project-based alternatives can add adaptability, while deconstructing jobs creates persistent human and organization paradoxes rather than a universal replacement for positions. | Make the local position-versus-direct-arrangement choice using the organization’s contribution and institutional conditions. |
| Grote et al., [contribution-based engineering role modeling](https://doi.org/10.1109/ISSE65546.2025.11370103) | Deriving contribution bundles from required process contributions and stakeholder evidence can expose gaps hidden by titles. | Test transfer beyond the bounded engineering cases; establish local positions and assignments under the owning organization’s rules. |
| Albert, [organization-structure perspectives](https://doi.org/10.1007/s41469-023-00152-y) | Activity grouping, decision representation, and legal-entity perspectives can give different evidence about a position's place. | Use the perspective as evidence, then recover the position’s establishment basis and any separate authority relation. |
| Fraccaroli, Zaniboni, and Truxillo, [work-design review](https://doi.org/10.1146/annurev-orgpsych-081722-053704) | Work characteristics and affected-person outcomes must inform position design and later holder use. | Combine work-design evidence with the organization’s establishment basis; assess a proposed holder’s current capability separately when a holder decision is current. |

Reopen when a representative institutional setting cannot distinguish position identity from assignment, a stronger source changes the position-versus-direct-arrangement choice or identity-bearing criteria, or the required institutional locus must persist outside any one owning organization.


## OCE.5:End {#end}
