# Community Mentorship

A comprehensive mentorship program management platform built for communities. This web application enables members to apply as mentors/mentees, view match results, track session progress, with full administrative capabilities for managing applications and monitoring program health.


## Why
We built a mentorship program on Coda and ran it for 2 years. 
- The original mentorship program on Coda has problems, including a lack of a test environment, performance issues, and a complex architecture due to shared permission constraints. 
- AI tooling popping up, we like to try and learn how to use AI to code.

## Goal
- Make a new mentorship program for the Fall 2025 Cohort
- Build it in public to share the learning
- The new program is open source; it can potentially be monetized by other organizations looking to run similar programs.

## What 
This project rebuilds our mentorship program, originally managed in Coda, into a full-featured web application. It retains all existing functionality while improving security, scalability, and maintainability. 
- Built with Flask (a Python framework) and deployed on Replit, the platform supports mentor/mentee workflows, session tracking, and admin tools in a unified system.
- Create one frontend (for mentors and mentees) and one backstage (for admins), with clearly defined roles and permissions.

### Technology Stack
- **Backend**: Flask (Python) with SQLAlchemy ORM
- **Database**: PostgreSQL with full migration support
- **Frontend**: Server-side rendered templates with Bootstrap 5
- **Styling**: Replit-themed dark mode Bootstrap CSS
- **Forms**: WTForms with enhanced validation
- **Testing**: Comprehensive end-to-end test suite

### How to collaborate
- Use Github to collaborate
- Use "Projects" to assign tasks and issues
- The main code is in platform
- The doc is in doc
- The matchiing algorithm will be in matching
