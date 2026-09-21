# ComunidApp — Project Context

## Project Overview

ComunidApp is a digital platform designed for the ITESO university community.

The platform is intended to centralize information about university activities in one place so students can easily discover what is happening on campus.

Examples of activities may include:

- Academic conferences
- Workshops
- Sports tournaments
- Cultural activities
- Social events
- Student organization activities
- University department events
- Other extracurricular activities

The main problem identified by the team is that information about these activities is currently distributed across several channels, including institutional email, social media, posters, websites, and messages from university departments. This causes students to miss events or learn about them too late.

## Business Opportunity

ITESO already organizes many academic, cultural, social, and sports activities.

However, the information about these activities is not centralized.

ComunidApp explores the opportunity to:

- Centralize university event information.
- Increase student participation in campus activities.
- Make events easier to discover.
- Reduce the need to search through multiple communication channels.
- Help students organize their participation.
- Improve communication between event organizers and students.
- Increase attendance at university events.
- Strengthen interaction within the ITESO community.
- Give organizers a direct channel to communicate with their target audience.

The desired future state is a more connected ITESO community where students can easily discover, filter, save, register for, and receive information about activities that match their interests.

## Target Community

Potential users and beneficiaries include:

- ITESO students
- Professors
- ITESO staff
- Student organizations
- USI and student collectives
- CEFSI
- Coordinación de Arte y Cultura
- Sports associations and team captains
- Event organizers
- University departments

Other groups may also be affected by or participate in the platform, including alumni, event sponsors, campus services, security personnel, and cafeteria concessionaires.

## Sponsor

The project sponsor identified in the current project documentation is:

**Dirección de Integración Comunitaria ITESO**

Other important institutional stakeholders include:

- Dirección de Sistemas e Informática del ITESO (DSI)
- Dirección de Comunicación Institucional (DCI)
- Consejería Legal del ITESO
- Course Professor / Program Coordination
- Tesorería del ITESO

These stakeholders may influence technical integration, communication processes, legal considerations, institutional support, and project evaluation.

## Current Functional Areas

### 1. User Account & Profile Management

Functionality related to users accessing the platform, managing their profiles, preferences, interests, and identity within the ITESO community.

### 2. Event Publishing & Management

Functionality that allows authorized organizers or coordinators to create, publish, edit, and maintain information about university events.

Event information may include:

- Event name
- Description
- Date
- Time
- Location
- Category
- Organizer
- Promotional images or posters

### 3. Event Discovery

Functionality that allows users to explore the activities happening at ITESO.

This may include:

- Browsing upcoming events
- Searching for activities
- Filtering events
- Discovering activities according to interests
- Viewing event categories

### 4. Registration & Participation

Functionality related to students registering for activities and managing their participation.

Possible functionality includes:

- Registering for events
- Saving events
- Viewing registered activities
- Tracking attendance
- RSVP management

### 5. Notifications & Reminders

Functionality that informs users about relevant activities.

Possible notifications may include:

- New events
- Event reminders
- Schedule changes
- Updates to registered events
- Activities related to user interests

### 6. Personalized Event Experience

Functionality related to adapting event discovery to each student.

The platform may allow students to:

- Select interests
- Receive personalized event information
- Filter activities
- Discover events related to their preferences

### 7. Organizer Tools

Functionality designed for student organizations, university departments, and event coordinators.

Possible capabilities include:

- Publishing events
- Updating event information
- Managing registrations
- Uploading promotional material
- Reviewing attendance
- Managing event calendars

### 8. Administration & Institutional Integration

Functionality related to managing the platform at an institutional level.

This area may involve:

- User permissions
- Role-based access
- Event moderation
- Platform administration
- ITESO systems integration
- Institutional communication
- Data privacy considerations

## Current Requirements Stage

The project is currently being developed as part of a **Software Requirements Engineering** process.

The team has already worked on:

- Individual problem definitions.
- A consolidated problem definition.
- Stakeholder identification.
- Stakeholder descriptions.
- Power-Interest stakeholder maps.
- Individual solution proposals.
- A consolidated solution proposal.
- Preliminary technology alternatives.
- Initial assumptions and limitations.

Some assumptions still need to be formally validated with ITESO stakeholders.

## Current Proposed Solution

The current team proposal is a **custom multi-platform solution** with both:

- Mobile application
- Web application

The mobile application is intended to provide fast access for students, while the web platform can support organizers and coordinators when creating and managing events.

The current technology proposal includes:

- Frontend: React Native / Flutter and web technologies
- Backend: Node.js with Express.js
- Database: PostgreSQL
- Notifications: Firebase Cloud Messaging
- Image Storage: AWS S3 or Cloudinary
- Design / Prototyping: Figma
- Hosting: Cloud infrastructure such as Google Cloud, AWS, Netlify, Vercel, or ITESO infrastructure

These technologies are currently proposals rather than validated final requirements.

## Current Scope Boundaries

At the current stage, the project documentation does not yet provide fully validated definitions for:

- Final authentication method
- Confirmed ITESO Single Sign-On integration
- Exact user permissions
- Detailed event publishing rules
- Final moderation rules
- Formal data privacy requirements
- Confirmed institutional server access
- Detailed notification rules
- Formal business rules
- Complete technical architecture
- Final implementation design

