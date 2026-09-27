# ORDINOX Desk Therapist

**Local-first Windows desktop practice management software for therapists and mental-health professionals.**

[English](README.md) · [Ελληνικά](README_GR.md)

---

## Overview

ORDINOX Desk Therapist is a Windows desktop application designed to support the day-to-day organization of a private therapy or mental-health practice.

It brings together client management, scheduling, session history, attendance, notes, documents, financial tracking, statistics, exports, backup and optional practice-management tools in one focused desktop environment.

The application follows a **local-first approach**, with normal practice data stored and managed locally on the user's Windows device.

It is designed for **Windows PCs and Windows tablets**, with **English and Greek interface support**.

> **Portfolio showcase:** This public repository presents the application and its interface. The production source code is maintained privately and is not published here.

> **Demo data:** All names, phone numbers, notes, appointments and other personal information visible in the screenshots are fictitious demonstration data created exclusively for presentation purposes.

---

## Today

The Today view provides a focused overview of the working day.

Depending on enabled features and available data, it can provide:

- Upcoming sessions
- Daily activity
- Quick access to common actions
- Practice reminders
- Backup-health information
- Optional follow-up information

![ORDINOX Desk Therapist - Today](assets/screenshots/01-today.png)

---

## Calendar & Scheduling

The Calendar provides a visual overview of scheduled sessions and supports both one-off appointments and recurring schedules.

Scheduling tools include:

- One-off sessions
- Recurring schedules
- Session status tracking
- Multiple recurrence patterns
- Working Hours guidance
- Time Off
- Waitlist
- Calendar export
- Historical recurring-session preservation

Working Hours are **advisory rather than restrictive**.

A session can still be booked outside the configured Working Hours. When warnings are enabled, ORDINOX can notify the user and allow them to continue with the booking.

![ORDINOX Desk Therapist - Calendar](assets/screenshots/02-calendar.png)

---

## Client Management

ORDINOX uses a desktop split-view interface that allows the professional to browse the Client List while working with the selected Client File.

The application supports:

- Individual Clients
- Group Clients
- Active and inactive Clients
- Search and filtering
- Structured Client Files
- Client-specific history and records

![ORDINOX Desk Therapist - Clients](assets/screenshots/03-clients.png)

---

## Client File

Each Client has a structured workspace containing the information and tools required for ongoing practice management.

Depending on the Client and the optional features enabled, the Client File can include:

- Session schedules
- Session history
- Client notes
- Session notes
- Managed documents
- Attendance statistics
- Client Timeline
- PDF output
- Optional Treatment Plans and Goals
- Optional Tasks / Follow-ups

![ORDINOX Desk Therapist - Client File](assets/screenshots/04-client-file.png)

---

## Group Clients

Groups are managed as Client entities and can be linked to existing Individual Clients.

This allows group schedules and history to remain organized while Individual Client records continue to exist independently.

Group members use their linked Individual Client records as the source of truth for their personal information.

![ORDINOX Desk Therapist - Group Client](assets/screenshots/05-group-client.png)

---

## Session History & Attendance

ORDINOX maintains structured session history together with attendance-related information.

Attendance information can include:

- Completed sessions
- Client cancellations
- Therapist cancellations
- No-shows
- Lateness

Historical recurring occurrences are preserved so that later schedule changes do not silently rewrite the previous session history.

![ORDINOX Desk Therapist - Attendance](assets/screenshots/06-attendance.png)

---

## Financial Overview

The Financial Overview provides a focused view of session-fee information.

It includes:

- Date filtering
- Client filtering
- Session Type filtering
- Session-status filtering
- Included-fee totals
- Session breakdown
- CSV export
- Native Excel `.xlsx` export
- PDF output

The application distinguishes between a session with no saved fee and a session with a zero fee.

![ORDINOX Desk Therapist - Financial Overview](assets/screenshots/07-financial.png)

---

## Statistics

Practice Statistics provide an at-a-glance overview of activity for a selected period.

Available information can include:

- Sessions
- Completed sessions
- Client cancellations
- Therapist cancellations
- No-shows
- Active Clients
- New Clients
- Included fees
- Attendance
- Session Types
- Session trends

Statistics are calculated locally from the application's database.

![ORDINOX Desk Therapist - Statistics](assets/screenshots/08-statistics.png)

---

## Session Types

Professionals can create their own Session Types with a default duration and suggested fee.

Session Types act as reusable defaults for new sessions and schedules.

Changes to a Session Type do not retroactively alter values already saved on previous sessions.

![ORDINOX Desk Therapist - Session Types](assets/screenshots/09-session-types.png)

---

## Client Timeline

The Client Timeline provides a chronological view of important Client activity.

Depending on available data and enabled features, it can include:

- Sessions
- Client notes
- Session notes
- Files
- Treatment Plans
- Goals
- Tasks / Follow-ups
- Other relevant Client events

Results are loaded in bounded pages to keep the interface responsive even with long Client histories.

![ORDINOX Desk Therapist - Client Timeline](assets/screenshots/10-timeline.png)

---

## Notes & Reusable Content

ORDINOX includes structured note tools for both Clients and individual Sessions.

Available functionality includes:

- Rich Client notes
- Rich Session notes
- Controlled text formatting
- Session Note Templates
- Quick Snippets
- Plain-text projection for search and reporting

Notes use a controlled structured format rather than arbitrary raw HTML.

---

## Optional Features

ORDINOX is designed to keep the default experience focused and simple.

Additional features can be enabled from Settings when they are useful.

### Tasks / Follow-ups

Tasks are things the professional needs to do.

They can be related to a Client or used as general follow-ups.

Tasks are optional and can be enabled or disabled from Settings.

Disabling Tasks does **not** delete previously saved Task data.

### Treatment Plans / Goals

Treatment Plans describe what the professional is working toward with a Client.

Goals are the individual therapeutic objectives or steps within that plan.

Treatment Plans and Goals are optional and can be enabled or disabled from Settings.

Disabling the feature does **not** delete existing Treatment Plans or Goals.

This approach keeps the basic application simpler while allowing professionals to add more structured tools when they need them.

---

## Managed Documents

Client documents can be imported and managed locally through the application.

The document workflow is designed around:

- Local managed copies
- Safe import
- Missing-file detection
- Recovery handling
- Client-based organization

The application avoids unnecessary full filesystem scanning during normal clean startup.

---

## Search

ORDINOX includes local Global Search functionality.

Search can help locate relevant information across areas such as:

- Clients
- Sessions
- Notes
- Documents
- Other indexed practice information

Search operates locally and does not require a remote search service.

---

## Backup & Restore

Backup and Restore are important parts of the application.

The backup system is designed to support:

- Local backup creation
- Database backup
- Managed-document backup
- Streaming archive creation
- Backup validation
- Restore staging
- Restore validation
- Recovery from interrupted restore operations
- Forward migration of supported older backups

The objective is to keep practice data portable and recoverable without relying on a cloud service.

---

## Import & Export

ORDINOX includes several data portability tools, including:

- CSV Client import
- Financial CSV export
- Native Excel `.xlsx` financial export
- Calendar `.ics` export
- PDF generation
- Local Backup and Restore

Exports are generated locally from the application's stored data.

---

## Local-First Architecture

ORDINOX Desk Therapist is designed as a local-first Windows application.

Normal operation does not require:

- A cloud account
- A remote database server
- Browser-based hosting
- Continuous internet connectivity
- External analytics or telemetry services

Normal practice data is intended to remain on the user's local Windows device.

---

## Windows PC & Tablet

ORDINOX Desk Therapist is designed for:

- Windows desktop computers
- Windows laptops
- Windows tablets

The interface includes responsive behavior and zoom support so the application can remain practical across different Windows screen sizes.

The application can be provided with **English and Greek interface support**.

---

## Product Philosophy

ORDINOX Desk Therapist is designed around a simple principle:

**keep the information and everyday tools of a private practice together without turning the application into an unnecessarily complex system.**

The core experience focuses on clients, scheduling, sessions, notes, records, finance and practice organization.

Additional features can remain optional so each professional can keep the application as simple or as structured as they prefer.

---

## Future Commercial Model

For future commercial releases, the intended model is straightforward:

- One-time purchase
- Local installation
- No mandatory ongoing subscription to continue using the purchased version
- Local management of normal application data

Additional optional features or tailored versions may be offered in the future depending on professional needs.

---

## Technology

The application is built with:

- **Tauri 2**
- **Rust**
- **SQLite**
- **Vanilla JavaScript**
- **HTML5**
- **CSS3**

The Rust backend handles database operations, scheduling logic, files, backup and restore, imports, exports and other native desktop functionality.

---

## Performance & Reliability

The application is designed around bounded database queries, local processing and on-demand operations.

Development and regression testing includes scenarios involving:

- Approximately 1,000 Clients
- Tens of thousands of Sessions
- Large local search indexes
- Thousands of managed files
- Long recurring-session histories

Potentially expensive operations such as imports, exports, recurrence synchronization and filesystem recovery are designed to avoid unnecessary continuous background work.

---

## Development Approach

ORDINOX Desk Therapist is developed incrementally with an emphasis on preserving existing behavior and protecting user data.

The workflow includes:

1. Reviewing existing behavior
2. Planning the required change
3. Implementing focused modifications
4. Running regression tests
5. Reviewing possible side effects
6. Checking performance and data-safety implications
7. Refining the interface where necessary

Large rewrites are avoided unless there is a strong technical reason.

---

## AI-Assisted Development

AI-assisted software development is part of my workflow, including the use of **OpenAI Codex**.

AI tools are used for areas such as:

- Existing code analysis
- Feature implementation
- Debugging
- Regression investigation
- Code refinement
- Testing assistance
- Performance review
- Reviewing potential side effects

AI-generated changes are reviewed and tested incrementally rather than applied blindly.

The workflow combines AI-assisted implementation with manual verification, testing, debugging and product decisions.

---

## Privacy Note

The screenshots in this repository contain **only fictitious demonstration data**.

No real Client, patient or therapy-practice information is included.

---

## Source Code

The full production source code of ORDINOX Desk Therapist is maintained privately.

This repository is intended solely as a **product showcase and portfolio presentation**, containing documentation and visual material demonstrating the application's functionality.

The complete production source code is not included in this public repository.

---

## Project Status

**Active development / pre-release.**

ORDINOX Desk Therapist is currently in final product-development preparation before later security, packaging and commercial-release stages.

The core functional application is operational and continues to receive usability and product refinements.

---

## Author

Designed and developed by **Menelaos Tzatzanis**.

Part of the **ORDINOX** desktop software project family.

© 2026 Menelaos Tzatzanis. All rights reserved.
