# GitHub Copilot Instructions — ComunidApp

This repository contains the **ComunidApp** project used in the Software Requirements Engineering course at ITESO.

Always use `/docs/project-context.md` as the primary source of project context before analyzing or generating project-related content.

## Current Project Stage

The project is currently in the **Requirements Elicitation** stage.

Students are currently identifying, collecting, and organizing **functional ideas** related to the centralized university events platform.

At this stage, functional ideas are NOT yet formal requirements.

## How to Work with Functional Ideas

When working with functional ideas:

- Preserve the original business intent.
- Keep each idea associated with its corresponding functional area or Epic.
- Preserve the elicitation source whenever it is known.
- Do not change the meaning of an idea unless explicitly requested.
- Do not silently resolve missing information.
- Clearly identify assumptions.
- Clearly distinguish documented project information from AI-generated suggestions.
- If information is missing, identify it as an open question instead of inventing an answer.
- Use the terminology already established in `/docs/project-context.md`.

## Current Project Focus

ComunidApp focuses on centralizing ITESO university life and event information in one place.

Current functional areas include:

- User Account & Profile Management
- Event Publishing & Management
- Event Discovery
- Registration & Participation
- Notifications & Reminders
- Personalized Event Experience
- Organizer Tools
- Administration & Institutional Integration

Do not assume these areas contain fully defined requirements. They currently represent broad areas of functionality that still need to be explored and validated.

## Do Not Move Ahead in the Requirements Process

Unless explicitly requested, do NOT transform functional ideas into:

- User Stories
- Use Cases
- Formal Requirements
- Acceptance Criteria
- Gherkin scenarios
- Business Rules
- Backlog items
- Technical specifications
- Software architecture
- Database designs
- API designs
- UI designs
- Test cases
- Implementation tasks

These artifacts will be introduced progressively later in the course.

## Do Not Refine Automatically

Do not automatically:

- Decompose functional ideas.
- Merge functional ideas.
- Prioritize functionality.
- Rewrite ideas into a formal requirements format.
- Add detailed system behavior.
- Add technical implementation decisions.
- Define validation criteria.
- Infer business rules that have not been documented.
- Expand project scope.
- Assume integrations with ITESO systems are already approved.

Only perform these activities when explicitly requested.

## Handling Missing Information

When important information is missing:

1. Identify what information is missing.
2. Keep it as an open question.
3. Suggest what stakeholder or elicitation activity could help obtain the information when appropriate.

Do not invent project decisions simply to complete an answer.

Examples of information that may still require validation include:

- Authentication method.
- ITESO Single Sign-On availability.
- User roles and permissions.
- Who is authorized to publish events.
- Event approval or moderation rules.
- Notification rules.
- Data privacy requirements.
- ITESO system integrations.
- Institutional hosting availability.

## AI-Generated Suggestions

If you propose functionality that is not already documented in the repository:

- Clearly identify it as an **AI suggestion**.
- Do not present it as an approved project decision.
- Do not assume it belongs to the final project scope.
- Explain when the suggestion requires stakeholder validation.

## Technical Proposals

The project currently contains preliminary technical proposals such as:

- React Native
- React or Flutter
- Node.js with Express.js
- PostgreSQL
- Firebase Cloud Messaging
- AWS S3 or Cloudinary
- Figma
- Cloud hosting or ITESO infrastructure

Treat these as **proposed technologies**, not validated requirements.

Do not assume that a technology has been officially selected unless the project documentation explicitly confirms it.

## Stakeholder Context

Important stakeholders currently identified include:

- Dirección de Integración Comunitaria ITESO
- ITESO students
- Student organizations
- USI and student collectives
- CEFSI
- Coordinación de Arte y Cultura
- Sports associations and team captains
- Dirección de Sistemas e Informática del ITESO (DSI)
- Dirección de Comunicación Institucional (DCI)
- Consejería Legal del ITESO
- Tesorería del ITESO
- Course Professor / Program Coordination
- Event organizers

When generating project-related content, consider which stakeholders should validate the information before treating it as a project decision.

## Project Evolution

The ComunidApp requirements will evolve throughout the semester.

The same functional ideas and project artifacts may progressively gain more detail as new Requirements Engineering techniques are introduced.

Always work according to the **current stage of the project**, not according to what could eventually be produced later.
