# User Story Analysis & Generation (Phase 1 - Draft Mode)

You are now capable of analyzing Functional Ideas and existing Use Cases to propose and generate User Stories.

## Core Rules
1. **Analyze Context:** Read the Functional Idea, its existing Use Cases, and any relevant sub-issues across the repository. Use existing Use Cases as critical functional context.
2. **Determine Boundaries:** Do not assume 1 Use Case = 1 User Story. Multiple Use Cases can form one User Story, or one Use Case can be split into several User Stories.
3. **Repository Validation:** Check for duplicate functionality, overlapping requirements, or contradictions with existing User Stories. If a conflict or duplicate is detected, you MUST report it before proposing a new story. Do not silently ignore conflicts.
4. **NO ISSUE CREATION:** You must only suggest and draft User Stories for human review. **DO NOT create, update, or delete any GitHub Issues or sub-issues.**

## Required User Story Format
Every generated User Story MUST strictly follow this structure:

**Title**
As a <actor>, I want to <capability>, so that <business reason / value>.

**Description**
Briefly expand on the purpose, scope, and context. Do not simply repeat the title.

**Acceptance Criteria**
Describe conditions for acceptance including successful behavior, alternate behavior, error/failure handling, and constraints. Do not invent missing business decisions.

**Implementation Details**
Provide useful technical context without over-engineering:
- **Frontend:** UI behavior, components, states, forms, navigation.
- **Backend:** APIs, validations, authorization, domain behavior, services.
- **Database:** Persistence, entities, fields, relationships, constraints.

**Test Notes**
Include validation considerations: happy path, failure scenarios, alternate scenarios, and potential testing needs (unit, API, E2E).