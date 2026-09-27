# Ordinox Desk Lite

**Lightweight local-first Windows desktop application for client and small-business management.**

[English](README.md) · [Ελληνικά](README_GR.md)

---

## Overview

Ordinox Desk Lite is a lightweight Windows desktop application designed for small businesses that need a simple and practical way to manage clients, products or services, prices, history, revenue and everyday business information from a single interface.

The application is intentionally focused and easy to use. It is designed for businesses that need more organization than spreadsheets or scattered notes, without the complexity of a large business-management system.

Typical use cases can include:

- Retail shops
- Service-based businesses
- Small local businesses
- Appointment-based businesses
- Businesses that keep client histories
- Businesses that need simple product, service and revenue tracking

The optical-store workflow shown in some screenshots is **one example configuration**. The core application concept is broader and can be adapted to different business needs.

The application follows a **local-first approach**, with normal business data stored and managed locally on the user's Windows device.

It is designed for **Windows PCs and Windows tablets**, with **English and Greek interface support**.

> **Portfolio showcase:** This public repository presents the application and its interface. The production source code is maintained privately and is not published here.

> **Demo data:** All names, client information, prices, records and other information visible in the screenshots are fictitious demonstration data.

---

## Client Management

![Ordinox Desk Lite Clients](assets/screenshots/clients.png)

Ordinox Desk Lite provides a simple client-management workflow designed for fast day-to-day use.

Features include:

- New client creation
- Client editing
- Client search
- Organized client list
- Quick access to client records
- Contact and client-related information
- Previous activity and history
- Information connected to products or services

The goal is to keep useful client information in one place instead of relying on separate spreadsheets, documents or paper notes.

---

## Client-Specific Information

![Ordinox Desk Lite Client Information](assets/screenshots/client-prescription.png)

Different types of businesses may need to store different information about their clients.

Ordinox Desk Lite can be adapted around structured client-specific information depending on the business workflow.

In this showcase, an optical-store configuration is used as an example and includes fields such as:

- SPH
- CYL
- AXE
- PD
- ADD
- Prescription dates
- Glasses-related information
- Contact lens-related information

These fields demonstrate one possible specialized use of the application.

Other configurations can use different client-specific information depending on the type of shop, service or professional workflow.

---

## Client History

![Ordinox Desk Lite Visit History](assets/screenshots/visit-history.png)

Client activity can be organized through a dedicated history.

Depending on the business, this can be used to review:

- Previous visits
- Purchases
- Services
- Prices
- Notes
- Client-specific information
- Previous transactions or activity

The purpose is to make previous client interactions easy to find without relying on external spreadsheets or separate documents.

---

## Revenue & Price Management

![Ordinox Desk Lite Revenue](assets/screenshots/revenue.png)

Ordinox Desk Lite includes tools for reviewing revenue-related information connected to client activity.

The application can help organize:

- Prices
- Products
- Services
- Client-related transactions
- Revenue information
- Historical entries
- Exportable financial information

This provides a simple overview of business activity without requiring a complex accounting or ERP system.

---

## Products & Services

![Ordinox Desk Lite Services](assets/screenshots/services.png)

Products or services commonly used by the business can be organized and reused throughout the application.

This helps:

- Reduce repetitive data entry
- Keep prices consistent
- Organize frequently used products or services
- Connect business activity with client history
- Make day-to-day work faster

The exact workflow can vary depending on the type of business using the application.

---

## Example Business Workflow

A typical Ordinox Desk Lite workflow can include:

1. Creating or locating a client
2. Reviewing existing client information
3. Recording information relevant to that client
4. Selecting or adding a product or service
5. Recording a price or transaction
6. Reviewing previous client history
7. Tracking related revenue
8. Exporting or backing up stored information

The optical-store example shown in this repository demonstrates one possible configuration.

The same core concept can be adapted to other types of small businesses.

---

## Backup & Import

![Ordinox Desk Lite Backup and Import](assets/screenshots/backup-import.png)

Data portability and recovery are built into the application.

Available functionality includes:

- Local data backup
- JSON export
- Data import
- Backup restoration
- Imported-data validation
- Recovery of stored application information

This allows users to keep their own copies of important business data independently from the application installation.

---

## Local-First Architecture

Ordinox Desk Lite is designed primarily for local operation on the user's Windows device.

For normal use:

- No remote backend is required
- No cloud database is required
- No cloud account is required
- Application data is stored locally
- Backup files can be created by the user
- Existing data can be restored through the import workflow
- Continuous internet connectivity is not required

This makes the application suitable for businesses that prefer a straightforward standalone desktop solution.

---

## Windows PC & Tablet

Ordinox Desk Lite runs as a standalone Windows application using **Tauri 2**.

It is designed for use on:

- Windows desktop computers
- Windows laptops
- Windows tablets

The interface is intended to remain practical across different Windows screen sizes.

The application can be provided with **English and Greek interface support**.

---

## Product Philosophy

Ordinox Desk Lite is designed around a simple idea:

**keep the information related to clients, products, services, prices, history and everyday business activity together in one practical application.**

It is intentionally lighter than a large ERP or CRM platform.

The goal is not to add unnecessary complexity, but to provide the tools that a small business actually needs.

Different versions or configurations can include additional optional functionality depending on the needs of the business.

---

## Future Commercial Model

For future commercial releases, the intended model is straightforward:

- One-time purchase
- Local installation
- No mandatory ongoing subscription to continue using the purchased version
- Local ownership of normal application data

Additional optional functionality or customized versions may be offered depending on the needs of the user or business.

---

## Data Export

The application includes functionality for exporting stored information in practical formats.

Depending on the workflow, exported information can include:

- Client-related data
- Revenue information
- Spreadsheet-compatible files
- Printable or PDF-ready output
- JSON backup files

These tools make it easier to archive, transfer or use information outside the application when required.

---

## Technology

Ordinox Desk Lite is built using technologies including:

- **Tauri 2**
- **Rust**
- **Vanilla JavaScript**
- **HTML5**
- **CSS3**
- **WebView local storage**
- **JSON**
- **CSV / spreadsheet-compatible exports**
- **Windows desktop packaging**

The application uses a web-based interface inside a native Windows desktop environment.

Tauri provides the desktop runtime and packaging layer, while the application interface and business logic are implemented primarily with HTML, CSS and JavaScript.

---

## Development Approach

The application has been developed incrementally.

The development workflow includes:

1. Understanding the required business workflow
2. Designing the appropriate feature
3. Implementing focused changes
4. Reviewing affected code
5. Running and testing the application
6. Checking existing functionality for regressions
7. Refining the interface where necessary
8. Avoiding unrelated changes

This approach helps keep the application understandable and stable while functionality evolves.

---

## AI-Assisted Development

AI-assisted development tools, including **OpenAI Codex**, are part of my development workflow.

They are used for tasks such as:

- Existing code analysis
- Feature implementation
- Debugging
- Investigating bugs
- Code refinement
- Reviewing possible side effects
- Exploring implementation alternatives
- Testing and validation assistance

AI-generated changes are not applied blindly.

Changes are reviewed and tested incrementally, combined with manual verification, debugging and product decisions.

---

## Test Data & Privacy

All names, phone numbers, prices, optical information, visits and other personal or business information visible in the screenshots are **fictional demonstration data**.

They do not represent real clients or individuals.

No real client data is included in this portfolio repository.

---

## Source Code

The full production source code of Ordinox Desk Lite is maintained privately.

This repository is intended as a **product showcase and portfolio presentation**, containing documentation and visual material demonstrating the application's functionality.

The complete production source code is not included in this public repository.

---

## Project Status

**Functional Windows desktop software project.**

Ordinox Desk Lite is a working application focused on practical client and small-business management.

The product can continue to evolve with additional optional features and configurations for different professional or business needs.

---

## Author

Designed and developed by **Menelaos Tzatzanis**.

Part of the **ORDINOX** desktop software project family.

© 2026 Menelaos Tzatzanis. All rights reserved.
