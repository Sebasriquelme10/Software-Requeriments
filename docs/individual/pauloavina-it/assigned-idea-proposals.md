# Assigned Functional Ideas #73-#96 - working proposals

No team standard or final generation is claimed. Parent issue updates are authorized working changes, separate from read-only individual tests.

# 73 - Display physical accessibility information

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** #74 filters by accessibility, #80 displays pre-event environmental information, and #81 submits confidential requests. They are related but do not establish that displaying ramps/elevators is already covered. Keep public accessibility information separate from private requests.

Related evidence:
- [#74: Filter events by expanded accessibility needs](https://github.com/Sebasriquelme10/Software-Requeriments/issues/74)
- [#80: Display room layouts, agendas, and environment info](https://github.com/Sebasriquelme10/Software-Requeriments/issues/80)
- [#81: Submit confidential accessibility requests during registration](https://github.com/Sebasriquelme10/Software-Requeriments/issues/81)

### User Story Proposal Summary
1. As an event viewer, I want to see available ramp and elevator information for an event location, so that I can assess physical access before attending.

**Boundary rationale and actors:** One viewing goal; ramps and elevators are attributes, not automatic separate stories. Event viewer is a provisional actor pending Use Case clarification.

### Open Questions
- Who supplies and validates accessibility information?
- Which locations and accessibility attributes must be shown?
- How should unknown, outdated, or unavailable information be represented?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 74 - Filter events by expanded accessibility needs

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** #239 covers date/category/department filters under #69, not sensory, neurodivergent, or dietary needs. Extend the common filtering experience if appropriate rather than duplicating it. #73 is physical information; #81 is a confidential request. Filtering must not imply a guaranteed accommodation.

Related evidence:
- [#73: Display physical accessibility information](https://github.com/Sebasriquelme10/Software-Requeriments/issues/73)
- [#69: Filter events by date, category, and department](https://github.com/Sebasriquelme10/Software-Requeriments/issues/69)
- [#239: As an event discovery user (actor to confirm), I want to filter events by date, category, and department, so that I can narrow results to events matching those criteria.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/239)
- [#81: Submit confidential accessibility requests during registration](https://github.com/Sebasriquelme10/Software-Requeriments/issues/81)

### User Story Proposal Summary
1. As an event discovery user, I want to filter events by physical, sensory, neurodivergent, and dietary accommodation information, so that I can find events relevant to my accessibility needs.

**Boundary rationale and actors:** One discovery goal across accessibility dimensions. Actor and supported classifications require confirmation.

### Open Questions
- Which accessibility categories and supported accommodations are defined?
- How do combined filters and unknown accommodation information behave?
- Who verifies accommodations, and how is availability distinguished from a guarantee?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 75 - Display sponsor booth locations on event map

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** #241/#160 display event locations on a campus map, not sponsor booths within an event. Reuse relevant map context without treating booths as events. #77 concerns external event navigation.

Related evidence:
- [#71: Explore nearby events using interactive campus map](https://github.com/Sebasriquelme10/Software-Requeriments/issues/71)
- [#160: Use Case: [UC-24] Explore Nearby Events on an Interactive Campus Map](https://github.com/Sebasriquelme10/Software-Requeriments/issues/160)
- [#241: As a student, I want to explore events with available campus locations on an interactive campus map and select an event to view its details, so that I can discover events in relation to campus locations.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/241)
- [#77: Display off-campus events on external maps with meeting info](https://github.com/Sebasriquelme10/Software-Requeriments/issues/77)

### User Story Proposal Summary
1. As an event attendee, I want to see sponsor booth locations on the event map, so that I can locate the booths I want to visit.

**Boundary rationale and actors:** One map-viewing goal. Attendee is provisional; publishing or editing booth locations is not documented here.

### Open Questions
- Who supplies and maintains booth locations?
- Which event map and booth details are available?
- What happens if a booth location or the map is unavailable?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 76 - Translate event descriptions into English

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** No equivalent translation story was identified in the reviewed issue bodies. Event modality labels (#79) and sharing links (#82) do not cover translated descriptions. Do not turn a translation need into a chosen translation provider or approval process.

Related evidence:
- [#79: Label events as On-Campus, Off-Campus, Virtual, or Hybrid](https://github.com/Sebasriquelme10/Software-Requeriments/issues/79)
- [#82: Share event links through external messaging apps](https://github.com/Sebasriquelme10/Software-Requeriments/issues/82)

### User Story Proposal Summary
1. As an international student, I want to read event descriptions in English, so that I can understand the events available to me.

**Boundary rationale and actors:** One reading goal. Translation authoring, automation, and original-language handling are unresolved implementation/business decisions.

### Open Questions
- Are translations human-written, automatic, or reviewed?
- Which descriptions require translation, and when are they updated?
- What is shown when the English description is missing or translation fails?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 77 - Display off-campus events on external maps with meeting info

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** #241/#160 concern campus event discovery; off-campus scope is explicitly an open question there. #77 adds an external map, address, meeting point, transportation information, and navigation options. Clarify the boundary before treating it as an extension or separate story.

Related evidence:
- [#71: Explore nearby events using interactive campus map](https://github.com/Sebasriquelme10/Software-Requeriments/issues/71)
- [#160: Use Case: [UC-24] Explore Nearby Events on an Interactive Campus Map](https://github.com/Sebasriquelme10/Software-Requeriments/issues/160)
- [#241: As a student, I want to explore events with available campus locations on an interactive campus map and select an event to view its details, so that I can discover events in relation to campus locations.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/241)
- [#75: Display sponsor booth locations on event map](https://github.com/Sebasriquelme10/Software-Requeriments/issues/75)
- [#79: Label events as On-Campus, Off-Campus, Virtual, or Hybrid](https://github.com/Sebasriquelme10/Software-Requeriments/issues/79)

### User Story Proposal Summary
1. As an off-campus event attendee, I want to view the event on an external map with its address, meeting point, transportation information, and navigation options, so that I can plan how to reach it.

**Boundary rationale and actors:** Keep the listed travel information in one attendee travel-planning goal; external routing behavior must be confirmed.

### Open Questions
- Which map/navigation applications are supported?
- Who maintains the address, meeting point, and transport information?
- What happens when information, an external application, or connectivity is unavailable?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 78 - Support hybrid events with dual capacities

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** #277/#204 cover generic capacity during event creation. #288/#214 cover external-guest capacity, a different distinction from physical versus virtual participation. Do not equate guest quotas with hybrid modality or assume a combined capacity formula.

Related evidence:
- [#33: Create events with capacity, date, and duration info](https://github.com/Sebasriquelme10/Software-Requeriments/issues/33)
- [#204: Create Events with Capacity, Date, and Duration Information](https://github.com/Sebasriquelme10/Software-Requeriments/issues/204)
- [#277: As an event organizer, I want to create an event with capacity, date, and duration information, so that the event can be managed and communicated with basic scheduling details.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/277)
- [#44: Set separate capacity limit for external guests](https://github.com/Sebasriquelme10/Software-Requeriments/issues/44)
- [#214: Set a Separate Capacity Limit for External Guests](https://github.com/Sebasriquelme10/Software-Requeriments/issues/214)
- [#288: As an event organizer or administrator, I want to configure a separate external-guest capacity limit, so that guest attendance can be controlled independently under the approved capacity rules.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/288)
- [#79: Label events as On-Campus, Off-Campus, Virtual, or Hybrid](https://github.com/Sebasriquelme10/Software-Requeriments/issues/79)

### User Story Proposal Summary
1. As an event organizer, I want to define separate physical and virtual capacities for a hybrid event, so that each participation mode has its own capacity information.
2. As a hybrid event participant, I want to access the information for the event's physical and virtual participation modes, so that I can understand how to participate.

**Boundary rationale and actors:** Two provisional actor goals: organizer capacity setup and participant access information. Registration allocation, capacity enforcement, and mode switching are not established by this idea.

### Open Questions
- Who may configure capacities, and what does each capacity count?
- Which access information is public or restricted to registered participants?
- Can participants change modes, and how should registrations affect each capacity?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 79 - Label events as On-Campus, Off-Campus, Virtual, or Hybrid

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** #78 concerns hybrid capacity/access and #77 off-campus navigation. Neither automatically covers showing the four modality labels. Classifying events may reuse event-management data but does not imply modality filters.

Related evidence:
- [#78: Support hybrid events with dual capacities](https://github.com/Sebasriquelme10/Software-Requeriments/issues/78)
- [#77: Display off-campus events on external maps with meeting info](https://github.com/Sebasriquelme10/Software-Requeriments/issues/77)
- [#33: Create events with capacity, date, and duration info](https://github.com/Sebasriquelme10/Software-Requeriments/issues/33)
- [#277: As an event organizer, I want to create an event with capacity, date, and duration information, so that the event can be managed and communicated with basic scheduling details.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/277)

### User Story Proposal Summary
1. As an event viewer, I want events to be labeled On-Campus, Off-Campus, Virtual, or Hybrid, so that I can understand their participation format.

**Boundary rationale and actors:** One presentation goal; label assignment authority is unresolved. Preserve all four source labels without inventing additional types.

### Open Questions
- Who assigns or changes the event label?
- Are the four labels exclusive and exhaustive?
- Where are labels shown, and how are missing or changed labels handled?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 80 - Display room layouts, agendas, and environment info

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** #73 covers ramps/elevators; #74 filters accessibility information. Room layouts, agendas, and environmental information may reuse those data but should not repeat or contradict them. The idea does not define who publishes the material.

Related evidence:
- [#73: Display physical accessibility information](https://github.com/Sebasriquelme10/Software-Requeriments/issues/73)
- [#74: Filter events by expanded accessibility needs](https://github.com/Sebasriquelme10/Software-Requeriments/issues/74)
- [#77: Display off-campus events on external maps with meeting info](https://github.com/Sebasriquelme10/Software-Requeriments/issues/77)

### User Story Proposal Summary
1. As an event attendee, I want to review available room layouts, agendas, and environmental information before an event, so that I can prepare for attending.

**Boundary rationale and actors:** One pre-event preparation goal unless source Use Cases later establish separate actors or independent outcomes. Attendee is provisional.

### Open Questions
- What environmental information and file formats are in scope?
- Who publishes and updates layouts and agendas?
- How are missing, outdated, or changed materials communicated?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 81 - Submit confidential accessibility requests during registration

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** Public accessibility data (#73/#74) are distinct from confidential individual requests. #249 governs attendance/RSVP/achievement visibility and is not an established authorization model for sensitive accommodation requests. Group-registration access also requires clarification.

Related evidence:
- [#73: Display physical accessibility information](https://github.com/Sebasriquelme10/Software-Requeriments/issues/73)
- [#74: Filter events by expanded accessibility needs](https://github.com/Sebasriquelme10/Software-Requeriments/issues/74)
- [#7: Control profile visibility and sharing preferences](https://github.com/Sebasriquelme10/Software-Requeriments/issues/7)
- [#249: As a user, I want to choose whether my attendance, RSVPs, and achievements are shared, so that I can control the visibility of my profile information.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/249)
- [#54: Request group registrations for multiple participants](https://github.com/Sebasriquelme10/Software-Requeriments/issues/54)
- [#224: As a student group leader, I want to submit one registration request for multiple participants at an event, so that registering the group does not require separate requests for each participant.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/224)

### User Story Proposal Summary
1. As a student registering for an event, I want to submit a confidential accessibility or accommodation request, so that my participation needs can be communicated privately.

**Boundary rationale and actors:** One confidential submission goal. Request processing, approvals, outcomes, and diagnostic information collection are not assumed.

### Open Questions
- Who can receive or access requests, with what consent and retention rules?
- Which request details are necessary, and may the student edit or withdraw a request?
- How does the flow work for group registration or a failed submission?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 82 - Share event links through external messaging apps

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** #256 concerns sharing earned certificates, not events. Event discovery provides context but does not cover external event-link sharing. Sharing must not imply access to private event content.

Related evidence:
- [#13: Download and share earned digital certificates](https://github.com/Sebasriquelme10/Software-Requeriments/issues/13)
- [#256: As a certificate recipient, I want to share an earned digital certificate, so that I can use it in my professional portfolio.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/256)
- [#71: Explore nearby events using interactive campus map](https://github.com/Sebasriquelme10/Software-Requeriments/issues/71)
- [#241: As a student, I want to explore events with available campus locations on an interactive campus map and select an event to view its details, so that I can discover events in relation to campus locations.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/241)

### User Story Proposal Summary
1. As a user viewing an event, I want to share its link through an external messaging application, so that I can invite others to discover the event.

**Boundary rationale and actors:** One sharing goal; copy-link, a list of supported apps, link previews, and recipient eligibility remain unconfirmed.

### Open Questions
- Which external messaging applications and platforms must work?
- Which events can be shared, and what can recipients see?
- What happens when sharing is cancelled or an application/link is unavailable?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 83 - Post questions on event pages with upvoting

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** Event-experience comments (#100/#127/#298) are not automatically questions. Official responses to feedback (#109/#139) are related but do not establish question answering. Organizer question moderation overlaps #91's moderator actions; define actor permissions and content types before duplicating moderation.

Related evidence:
- [#100: Allow attendees to post event comments](https://github.com/Sebasriquelme10/Software-Requeriments/issues/100)
- [#127: UC01: Post a Comment About an Event](https://github.com/Sebasriquelme10/Software-Requeriments/issues/127)
- [#298: UC02: View Comments About an Event](https://github.com/Sebasriquelme10/Software-Requeriments/issues/298)
- [#90: Automated filtering of spam, profanity, and links](https://github.com/Sebasriquelme10/Software-Requeriments/issues/90)
- [#91: Moderator tools to mute users, pin info, and close chats](https://github.com/Sebasriquelme10/Software-Requeriments/issues/91)
- [#92: Report inappropriate community content](https://github.com/Sebasriquelme10/Software-Requeriments/issues/92)
- [#93: Temporarily hide heavily reported content](https://github.com/Sebasriquelme10/Software-Requeriments/issues/93)
- [#109: Allow organizers to publish official responses](https://github.com/Sebasriquelme10/Software-Requeriments/issues/109)
- [#139: UC01: Publish an Official Response to Attendee Feedback](https://github.com/Sebasriquelme10/Software-Requeriments/issues/139)

### User Story Proposal Summary
1. As a student, I want to post a question on an event page, so that I can ask for information about the event.
2. As a community member, I want to upvote questions on an event page, so that I can indicate which questions I also want addressed.
3. As an event organizer, I want to moderate questions on the event page, so that I can manage the questions presented there.

**Boundary rationale and actors:** Three provisional goals for posting, voting, and organizer moderation. Do not split composing and submitting into separate stories without evidence. Moderation may reuse #91 after roles are clarified.

### Open Questions
- Who can read/post/vote, and what limits apply to voting?
- Which moderation actions may organizers perform, and how does this relate to #91?
- Are question answers in scope, and are identities and vote counts visible?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 84 - Create groups to attend events together

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** #224/#137 already cover registering multiple participants, not creating a social attendance group. #234/#154 cancel a group registration participant and must not be silently interpreted as social group management. #86 concerns preparation teams.

Related evidence:
- [#54: Request group registrations for multiple participants](https://github.com/Sebasriquelme10/Software-Requeriments/issues/54)
- [#137: Use Case: [UC-04] Register Group Participants for an Event](https://github.com/Sebasriquelme10/Software-Requeriments/issues/137)
- [#224: As a student group leader, I want to submit one registration request for multiple participants at an event, so that registering the group does not require separate requests for each participant.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/224)
- [#64: Cancel single participant from group registration](https://github.com/Sebasriquelme10/Software-Requeriments/issues/64)
- [#154: Use Case: [UC-18] Cancel One Participant from a Group Registration](https://github.com/Sebasriquelme10/Software-Requeriments/issues/154)
- [#234: As a group registration organizer, I want to cancel one participant from a group registration, so that the other participants’ registrations remain active.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/234)
- [#85: Find classmates attending the same event](https://github.com/Sebasriquelme10/Software-Requeriments/issues/85)
- [#86: Create event teams and assign preparation tasks](https://github.com/Sebasriquelme10/Software-Requeriments/issues/86)

### User Story Proposal Summary
1. As a student, I want to create a group to attend an event together, so that I can coordinate participation with other students.

**Boundary rationale and actors:** One social group-creation goal; registration, invitations, joining, and group lifecycle need clarification before additional stories are proposed.

### Open Questions
- How are people invited, admitted, or removed?
- Does a group belong to one event, and is its membership visible?
- Does creating a group also create any registration or reserve capacity?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 85 - Find classmates attending the same event

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** Possible existing coverage: #285 and UC #211 already display known colleagues at an event. #85 explicitly requires BOTH users to allow visibility; #285's title refers to the displayed colleague's permission, while the mutual requirement is not established. Confirm whether classmates equal known colleagues and preserve private-by-default behavior from #7/#249. Prefer clarification or refinement of #285 over an unnecessary duplicate.

Related evidence:
- [#41: View known colleagues attending an event](https://github.com/Sebasriquelme10/Software-Requeriments/issues/41)
- [#211: View Known Colleagues Attending an Event](https://github.com/Sebasriquelme10/Software-Requeriments/issues/211)
- [#285: As a user, I want to view known colleagues attending an event when they permit visibility, so that I can identify familiar people who may also participate.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/285)
- [#7: Control profile visibility and sharing preferences](https://github.com/Sebasriquelme10/Software-Requeriments/issues/7)
- [#174: UC: Manage Profile Information Visibility](https://github.com/Sebasriquelme10/Software-Requeriments/issues/174)
- [#249: As a user, I want to choose whether my attendance, RSVPs, and achievements are shared, so that I can control the visibility of my profile information.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/249)
- [#84: Create groups to attend events together](https://github.com/Sebasriquelme10/Software-Requeriments/issues/84)

### User Story Proposal Summary
1. As a student, I want to find classmates attending the same event only when both of us allow visibility, so that I can discover shared attendance under our privacy choices.

**Boundary rationale and actors:** This is a candidate refinement/reuse of #285, not a request for a new issue. A separate story is justified only if the team confirms a distinct classmate-discovery goal.

### Open Questions
- Does classmate mean the same relationship as known colleague in #41?
- Which setting must EACH user enable, and what does attending mean?
- Who may see which details, and how do private defaults and revoked consent apply?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 86 - Create event teams and assign preparation tasks

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** Social attendance groups (#84) and bulk registration (#224) do not establish preparation teams or task assignment. #280/#207 cover co-organizer permission delegation, not preparation-task management; creating a team must not silently grant permissions.

Related evidence:
- [#84: Create groups to attend events together](https://github.com/Sebasriquelme10/Software-Requeriments/issues/84)
- [#54: Request group registrations for multiple participants](https://github.com/Sebasriquelme10/Software-Requeriments/issues/54)
- [#137: Use Case: [UC-04] Register Group Participants for an Event](https://github.com/Sebasriquelme10/Software-Requeriments/issues/137)
- [#224: As a student group leader, I want to submit one registration request for multiple participants at an event, so that registering the group does not require separate requests for each participant.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/224)
- [#36: Assign custom permissions to co-organizers](https://github.com/Sebasriquelme10/Software-Requeriments/issues/36)
- [#207: Assign Custom Permissions to Co-Organizers](https://github.com/Sebasriquelme10/Software-Requeriments/issues/207)
- [#280: As an event organizer or administrator, I want to assign custom permissions to co-organizers, so that I can delegate selected event responsibilities safely.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/280)

### User Story Proposal Summary
1. As an event preparation coordinator, I want to create an event team, so that preparation work has an identified group.
2. As an event preparation coordinator, I want to assign shared preparation tasks to the team, so that preparation responsibilities can be coordinated.

**Boundary rationale and actors:** Two provisional goals: team creation and task assignment. Coordinator is a role placeholder, not an established permission grant; task tracking/completion is not specified.

### Open Questions
- Who can create teams and assign tasks?
- How is team membership established, and how is this different from co-organizers?
- Which task details are required, and are deadlines, acceptance, or completion in scope?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 87 - Distribute digital sponsor coupons to attendees

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** #97/#124/#300/#302 describe digital fallback vouchers after physical stock depletion, not ordinary distribution of sponsor coupons. #95 alerts about depletion and #96 prevents repeated redemptions. Clarify whether coupons and vouchers are the same artifact before duplicating issuance/access behavior.

Related evidence:
- [#94: Display live availability of sponsor promotional items](https://github.com/Sebasriquelme10/Software-Requeriments/issues/94)
- [#95: Notify students when promotional items run out](https://github.com/Sebasriquelme10/Software-Requeriments/issues/95)
- [#96: Use QR codes to prevent duplicate promo redemptions](https://github.com/Sebasriquelme10/Software-Requeriments/issues/96)
- [#97: Provide digital fallback vouchers when physical items run out](https://github.com/Sebasriquelme10/Software-Requeriments/issues/97)
- [#124: UC01: Issue Digital Fallback Vouchers](https://github.com/Sebasriquelme10/Software-Requeriments/issues/124)
- [#300: As a promotional-item manager, I want to issue a digital voucher when physical promotional items are confirmed depleted, so that recipients have a fallback.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/300)
- [#302: As an intended voucher recipient, I want to access the digital fallback voucher provided to me, so that I can use the digital alternative.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/302)

### User Story Proposal Summary
1. As a registered event attendee, I want to receive available digital sponsor coupons, so that I can access the sponsor benefits offered to attendees.

**Boundary rationale and actors:** One recipient distribution goal; redemption, fallback issuance, and stock management stay separate pending a shared coupon/voucher definition.

### Open Questions
- Are coupons the same as #97's vouchers, and who supplies/distributes them?
- Which registered attendees qualify, through which channel, and at what time?
- What happens when stock is depleted or delivery fails, and what terms apply?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 88 - Post lost items on event pages with privacy protection

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** Generic profile visibility (#249) does not define privacy for lost-item contact information. Community moderation (#90-#93) is relevant but does not specify item ownership verification or contact disclosure. Do not publish personal contact data by default.

Related evidence:
- [#7: Control profile visibility and sharing preferences](https://github.com/Sebasriquelme10/Software-Requeriments/issues/7)
- [#249: As a user, I want to choose whether my attendance, RSVPs, and achievements are shared, so that I can control the visibility of my profile information.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/249)
- [#90: Automated filtering of spam, profanity, and links](https://github.com/Sebasriquelme10/Software-Requeriments/issues/90)
- [#91: Moderator tools to mute users, pin info, and close chats](https://github.com/Sebasriquelme10/Software-Requeriments/issues/91)
- [#92: Report inappropriate community content](https://github.com/Sebasriquelme10/Software-Requeriments/issues/92)
- [#93: Temporarily hide heavily reported content](https://github.com/Sebasriquelme10/Software-Requeriments/issues/93)

### User Story Proposal Summary
1. As an event community participant, I want to post structured lost-item information with privacy-protected contact details on an event page, so that the item can be recovered without unnecessarily exposing contact information.

**Boundary rationale and actors:** One posting goal; actor, lost versus found scope, ownership verification, and recovery/contact flow remain provisional.

### Open Questions
- Which structured fields are required, and are lost and found items both in scope?
- Who may view or contact the poster, using which privacy mechanism?
- How are recovered items, retention, moderation, and invalid reports handled?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 89 - Publish post-event photo galleries

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** Profile attendance/RSVP visibility (#249) does not establish consent or audience rules for event photographs. Community-content moderation may be shared with #90-#93. No equivalent post-event gallery story was identified in the reviewed issue bodies.

Related evidence:
- [#7: Control profile visibility and sharing preferences](https://github.com/Sebasriquelme10/Software-Requeriments/issues/7)
- [#249: As a user, I want to choose whether my attendance, RSVPs, and achievements are shared, so that I can control the visibility of my profile information.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/249)
- [#90: Automated filtering of spam, profanity, and links](https://github.com/Sebasriquelme10/Software-Requeriments/issues/90)
- [#91: Moderator tools to mute users, pin info, and close chats](https://github.com/Sebasriquelme10/Software-Requeriments/issues/91)
- [#92: Report inappropriate community content](https://github.com/Sebasriquelme10/Software-Requeriments/issues/92)
- [#93: Temporarily hide heavily reported content](https://github.com/Sebasriquelme10/Software-Requeriments/issues/93)

### User Story Proposal Summary
1. As an authorized event gallery publisher, I want to publish a post-event photo gallery, so that the event's photographs can be shared with the intended audience.

**Boundary rationale and actors:** One publishing goal; publisher and intended audience are placeholders requiring approval. Viewer, editing, deletion, and photo-consent workflows are not assumed.

### Open Questions
- Who may publish, and who may view photographs?
- What consent, privacy, retention, or removal rules apply?
- Which file limits, moderation checks, and publication failure behavior are required?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 90 - Automated filtering of spam, profanity, and links

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** #104/#321/#327/#329 screen abusive or threatening feedback before organizer access. #90 targets spam, profanity, malicious links, and duplicate community posts. These may share a mechanism, but content domains, criteria, and outcomes differ. Detection alone does not imply rejection, deletion, or the report-count hiding policy in #93.

Related evidence:
- [#104: Automatically screen abusive or threatening feedback](https://github.com/Sebasriquelme10/Software-Requeriments/issues/104)
- [#321: UC01: Screen Feedback Before Organizer Review](https://github.com/Sebasriquelme10/Software-Requeriments/issues/321)
- [#327: As an event organizer, I want to receive only feedback screened for abusive or threatening content, so that potentially harmful material can be identified first.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/327)
- [#329: As an event organizer, I want to distinguish feedback flagged by screening from feedback that passes screening, so that I can follow the approved review process.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/329)
- [#83: Post questions on event pages with upvoting](https://github.com/Sebasriquelme10/Software-Requeriments/issues/83)
- [#88: Post lost items on event pages with privacy protection](https://github.com/Sebasriquelme10/Software-Requeriments/issues/88)
- [#89: Publish post-event photo galleries](https://github.com/Sebasriquelme10/Software-Requeriments/issues/89)
- [#91: Moderator tools to mute users, pin info, and close chats](https://github.com/Sebasriquelme10/Software-Requeriments/issues/91)
- [#92: Report inappropriate community content](https://github.com/Sebasriquelme10/Software-Requeriments/issues/92)
- [#93: Temporarily hide heavily reported content](https://github.com/Sebasriquelme10/Software-Requeriments/issues/93)

### User Story Proposal Summary
1. As a community user, I want community posts to be automatically screened for spam, profanity, malicious links, and duplicates, so that community content can be handled under the agreed safety rules.

**Boundary rationale and actors:** One provisional community-content screening goal; rules and handling must be defined. Do not create separate stories for each classifier by default.

### Open Questions
- Which community content types and languages are screened, at what point?
- How are flagged content, false positives, appeal, and screening failure handled?
- What is the relationship to feedback screening in #104 and temporary hiding in #93?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 91 - Moderator tools to mute users, pin info, and close chats

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** The body of #91 includes REMOVE MESSAGES in addition to mute, pin, and close; the issue title omits removal. Preserve all four behaviors. Organizer question moderation in #83 may overlap, while co-organizer delegation (#280) does not establish moderator authority.

Related evidence:
- [#83: Post questions on event pages with upvoting](https://github.com/Sebasriquelme10/Software-Requeriments/issues/83)
- [#90: Automated filtering of spam, profanity, and links](https://github.com/Sebasriquelme10/Software-Requeriments/issues/90)
- [#92: Report inappropriate community content](https://github.com/Sebasriquelme10/Software-Requeriments/issues/92)
- [#93: Temporarily hide heavily reported content](https://github.com/Sebasriquelme10/Software-Requeriments/issues/93)
- [#36: Assign custom permissions to co-organizers](https://github.com/Sebasriquelme10/Software-Requeriments/issues/36)
- [#207: Assign Custom Permissions to Co-Organizers](https://github.com/Sebasriquelme10/Software-Requeriments/issues/207)
- [#280: As an event organizer or administrator, I want to assign custom permissions to co-organizers, so that I can delegate selected event responsibilities safely.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/280)

### User Story Proposal Summary
1. As a moderator, I want to mute a user in the applicable community context, so that I can limit that user's participation under the agreed moderation rules.
2. As a moderator, I want to remove a community message, so that content can be removed under the agreed moderation rules.
3. As a moderator, I want to pin information in an event chat, so that relevant information remains easy to find.
4. As a moderator, I want to close an event chat after the event, so that the conversation can be ended under the agreed rules.

**Boundary rationale and actors:** Four provisional moderator outcomes with potentially distinct authorization and lifecycle rules. Human review may combine them if they form one coherent management goal. Removal is sourced from the body, not invented.

### Open Questions
- Who is a moderator, over which events/content/users, and how does this relate to organizers?
- What do mute, remove, pin, and close each do, for how long, and can they be reversed?
- What audit, notification, retention, and post-event timing rules apply?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 92 - Report inappropriate community content

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** Reporting by a user is distinct from automatic screening (#90), moderator actions (#91), and temporary hiding based on reports (#93). #104 concerns feedback screening, not necessarily community reporting. A report must not silently imply automatic removal or a finding of abuse.

Related evidence:
- [#90: Automated filtering of spam, profanity, and links](https://github.com/Sebasriquelme10/Software-Requeriments/issues/90)
- [#91: Moderator tools to mute users, pin info, and close chats](https://github.com/Sebasriquelme10/Software-Requeriments/issues/91)
- [#93: Temporarily hide heavily reported content](https://github.com/Sebasriquelme10/Software-Requeriments/issues/93)
- [#104: Automatically screen abusive or threatening feedback](https://github.com/Sebasriquelme10/Software-Requeriments/issues/104)

### User Story Proposal Summary
1. As a community user, I want to report inappropriate community content, so that it can be considered through the agreed moderation process.

**Boundary rationale and actors:** One reporting goal; reviewing and resolving reports require additional evidence rather than assumed stories.

### Open Questions
- Which content may be reported, by whom, and with which reasons or evidence?
- Who receives reports, and what privacy and duplicate-report rules apply?
- What acknowledgement, misuse protection, review, and failure behavior is required?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 93 - Temporarily hide heavily reported content

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** #92 supplies the report-submission goal; #93 temporarily hides heavily reported content UNTIL REVIEW. #91's removal is different from temporary hiding. Neither the threshold nor the post-review result is defined; do not convert hiding into permanent deletion.

Related evidence:
- [#92: Report inappropriate community content](https://github.com/Sebasriquelme10/Software-Requeriments/issues/92)
- [#91: Moderator tools to mute users, pin info, and close chats](https://github.com/Sebasriquelme10/Software-Requeriments/issues/91)
- [#90: Automated filtering of spam, profanity, and links](https://github.com/Sebasriquelme10/Software-Requeriments/issues/90)

### User Story Proposal Summary
1. As a community user, I want heavily reported content to be temporarily hidden pending review, so that community exposure can be limited while the content is assessed.

**Boundary rationale and actors:** One provisional exposure-control goal; reviewer workflow and restoration/removal decisions require clarification. Community user is a provisional beneficiary of system behavior.

### Open Questions
- What report threshold, time window, and distinct-reporter rules define heavily reported?
- Who may review hidden content, and who can still see it?
- What happens after review, on false reports, or when report counts/review status are unavailable?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 94 - Display live availability of sponsor promotional items

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** Displaying stock (#94) differs from distribution (#87), depletion alerts (#95), QR redemption control (#96), and fallback vouchers (#97). A shared source of availability may be needed; do not assume how live data is measured or how often it refreshes.

Related evidence:
- [#87: Distribute digital sponsor coupons to attendees](https://github.com/Sebasriquelme10/Software-Requeriments/issues/87)
- [#95: Notify students when promotional items run out](https://github.com/Sebasriquelme10/Software-Requeriments/issues/95)
- [#96: Use QR codes to prevent duplicate promo redemptions](https://github.com/Sebasriquelme10/Software-Requeriments/issues/96)
- [#97: Provide digital fallback vouchers when physical items run out](https://github.com/Sebasriquelme10/Software-Requeriments/issues/97)

### User Story Proposal Summary
1. As an event attendee, I want to see current sponsor promotional-item availability, so that I can understand which items may still be available.

**Boundary rationale and actors:** One viewing goal. Actor and what live means require confirmation; viewing availability must not imply reserving an item or guaranteeing stock.

### Open Questions
- Who updates stock and how is availability confirmed?
- What freshness, quantity, or availability detail should be displayed?
- How are stale, unknown, depleted, or unavailable stock data shown?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 95 - Notify students when promotional items run out

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** The body explicitly includes promotional items OR COUPONS and targets REGISTERED students; preserve both despite the shorter title. #94 displays availability, #97 provides fallback vouchers, and #87 distributes coupons. Quiet hours/thread preferences (#30/#273/#274) must not be silently overridden for this alert.

Related evidence:
- [#87: Distribute digital sponsor coupons to attendees](https://github.com/Sebasriquelme10/Software-Requeriments/issues/87)
- [#94: Display live availability of sponsor promotional items](https://github.com/Sebasriquelme10/Software-Requeriments/issues/94)
- [#97: Provide digital fallback vouchers when physical items run out](https://github.com/Sebasriquelme10/Software-Requeriments/issues/97)
- [#30: Allow students to configure quiet hours and mute threads](https://github.com/Sebasriquelme10/Software-Requeriments/issues/30)
- [#273: As a student, I want to configure quiet hours, so that applicable notifications do not interrupt me during the periods I choose.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/273)
- [#274: As a student, I want to mute or unmute a specific event notification thread, so that I can control notifications from that thread without changing other event notifications.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/274)

### User Story Proposal Summary
1. As a registered student, I want to be notified when event promotional items or coupons run out, so that I know they are no longer available.

**Boundary rationale and actors:** One depletion-notification goal across the two item types. A stock alert is not fallback voucher issuance; recipients and delivery rules require review.

### Open Questions
- Which registered students receive the alert, through which channel and at what time?
- How is depletion confirmed, and how are duplicate alerts or replenishment handled?
- Which notification preferences apply, and what happens if delivery or stock data fails?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->

# 96 - Use QR codes to prevent duplicate promo redemptions

<!-- paulo-requirements-analysis:start -->
## Requirements analysis - Paulo (pauloavina-it)

**Status: User Story proposals awaiting human review.** These are candidate boundaries, not approved full specifications or completed project User Stories. This working update was explicitly requested by the repository user and is separate from read-only individual agent testing. It does not record a team-standard selection.

**Personal agent:** [requirements-analyst-pauloavina-it.agent.md](https://github.com/Sebasriquelme10/Software-Requeriments/blob/individual/pauloavina-it-user-stories/.github/agents/requirements-analyst-pauloavina-it.agent.md).
**Source:** This Functional Idea; original Epic and Elicitation Source above remain authoritative.

### Existing Use Cases and repository coverage
No native Use Case or User Story sub-issues were linked under this Functional Idea at inspection time. Relevant existing requirements elsewhere were reviewed below; none are silently treated as this idea's Use Cases. The missing associated Use Cases must be recovered or clarified before claiming the assignment's Use-Case-based final coverage is complete.

**Duplicates, overlaps, and contradictions (reported before proposals):** Attendance/check-in QR (#140/#222/#284) is not promotional redemption and does not establish one-use promo rules. #304 leaves whether a voucher claim is redemption unresolved. Define the relationship among coupon, voucher, claim, and redemption before sharing identifiers or state transitions.

Related evidence:
- [#52: Generate unique QR code for event check-in](https://github.com/Sebasriquelme10/Software-Requeriments/issues/52)
- [#140: Use Case: [UC-05] Generate Event Check-In QR Code](https://github.com/Sebasriquelme10/Software-Requeriments/issues/140)
- [#222: As an event organizer, I want registered attendees to have a unique QR code that can be used for event check-in, so that I can verify attendance quickly and consistently.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/222)
- [#40: Scan attendee QR codes offline and sync later](https://github.com/Sebasriquelme10/Software-Requeriments/issues/40)
- [#210: Scan Attendee QR Codes Offline and Synchronize Attendance Later](https://github.com/Sebasriquelme10/Software-Requeriments/issues/210)
- [#284: As an event staff member, I want to scan attendee QR codes while offline and synchronize the attendance records later, so that check-in can continue without network connectivity.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/284)
- [#87: Distribute digital sponsor coupons to attendees](https://github.com/Sebasriquelme10/Software-Requeriments/issues/87)
- [#94: Display live availability of sponsor promotional items](https://github.com/Sebasriquelme10/Software-Requeriments/issues/94)
- [#97: Provide digital fallback vouchers when physical items run out](https://github.com/Sebasriquelme10/Software-Requeriments/issues/97)
- [#295: UC02: Claim a Digital Fallback Voucher](https://github.com/Sebasriquelme10/Software-Requeriments/issues/295)
- [#304: As an intended voucher recipient, I want to claim a digital fallback voucher made available to me, so that I can secure the digital alternative when physical items run out.](https://github.com/Sebasriquelme10/Software-Requeriments/issues/304)

### User Story Proposal Summary
1. As an actor responsible for promotional-item redemption, I want QR-based checks to prevent repeated redemption of the same promotional item, so that the same entitlement cannot be redeemed multiple times.

**Boundary rationale and actors:** One provisional redemption-control goal. Actor, meaning of same item/entitlement, and QR ownership are unresolved; no per-person/event limit or offline policy is invented.

### Open Questions
- What does same promotional item mean: a physical unit, coupon, entitlement, recipient, or promotion?
- Who scans the QR and when is a successful redemption recorded?
- How are concurrent/repeated scans, offline operation, failures, and corrections handled?
- Which existing Use Cases should be linked to this Functional Idea, or does its Use Case refinement still need review?

### Human review checkpoint
Review reuse/merge/split decisions and the candidate actors/scope first. After that review, prepare each approved full draft with Description, Acceptance Criteria, Frontend, Backend, Database, and Test Notes. Keep unresolved rules visible. Do not claim final approval or create a duplicate story. Any later published Use Case and User Story must be siblings under the original Functional Idea.

**Review limits:** Open and closed issue titles/bodies plus the native hierarchy for all 24 assigned ideas were inspected through pauloavina-it. Comments/history and every other issue hierarchy were not exhaustively reviewed. The repository may change; repeat equivalent-story checks before final publication.
<!-- paulo-requirements-analysis:end -->
