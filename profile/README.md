<div align="center">

<br />

<img src="./assets/nexa-logo.svg" alt="Nexa" width="240" />

<br /><br />

# Nexa

**Fast, role-focused B2B multi-tenant SaaS for importers and distributors, particularly cold-chain businesses.**

![Java 25](https://img.shields.io/badge/Java-25-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot 4.1](https://img.shields.io/badge/Spring%20Boot-4.1-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Angular 22](https://img.shields.io/badge/Angular-22-DD0031?style=flat-square&logo=angular&logoColor=white) ![Static Website](https://img.shields.io/badge/Website-static-2563EB?style=flat-square)

[Overview](#overview) · [Product ecosystem](#nexa-product-ecosystem) · [Product areas](#product-areas) · [Technology stack](#technology-stack) · [Security](#security)

</div>

---

## Overview

Nexa coordinates catalog, commercial operations, inventory, warehouse, fulfillment, and delivery for importers and distributors, with strong cold-chain support. The six current product repositories evolve independently; repository presence, build evidence, and release evidence remain separate claims.

## Nexa Product Ecosystem

<table>
<tr>
<td width="50%" valign="top">

### [Nexa Mobile](https://github.com/nexa-suite/mobile)

Documentation and native runway for future buyer and cold-chain field experiences. No application framework selected.

[Open Repository](https://github.com/nexa-suite/mobile)

![Markdown](https://img.shields.io/badge/Markdown-Documentation-000000?style=flat-square&logo=markdown&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-validation-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-validation-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Status](https://img.shields.io/badge/status-planned-64748B?style=flat-square)

</td>
<td width="50%" valign="top">

### [Nexa Mobile Report](https://github.com/nexa-suite/mobile-report)

Academic report, delivery evidence, and validation for the mobile planning runway.

[Open Repository](https://github.com/nexa-suite/mobile-report)

![Markdown](https://img.shields.io/badge/Markdown-Documentation-000000?style=flat-square&logo=markdown&logoColor=white) ![Python](https://img.shields.io/badge/Python-validation-3776AB?style=flat-square&logo=python&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-sprints-0052CC?style=flat-square&logo=jira&logoColor=white) ![GitFlow](https://img.shields.io/badge/GitFlow-academic-F05032?style=flat-square&logo=git&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Nexa API](https://github.com/nexa-suite/api)

Business and integration backbone for identity, tenant scope, and operational workflows.

[Open Repository](https://github.com/nexa-suite/api)

![Java](https://img.shields.io/badge/Java-25-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-4.1-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-18-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Flyway](https://img.shields.io/badge/Flyway-migrations-CC0200?style=flat-square&logo=flyway&logoColor=white) ![Release](https://img.shields.io/github/v/release/nexa-suite/api?display_name=tag&sort=semver&style=flat-square&label=release)

</td>
<td width="50%" valign="top">

### [Nexa Website](https://github.com/nexa-suite/website)

Public product experience and public product entry point.

[Open Repository](https://github.com/nexa-suite/website)

![HTML5](https://img.shields.io/badge/HTML5-static-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-responsive-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Release](https://img.shields.io/github/v/release/nexa-suite/website?display_name=tag&sort=semver&style=flat-square&label=release)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Nexa Buyer Portal](https://github.com/nexa-suite/portal)

Buyer-facing experience for catalog discovery, purchasing, and delivery visibility.

[Open Repository](https://github.com/nexa-suite/portal)

![Angular](https://img.shields.io/badge/Angular-22-DD0031?style=flat-square&logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Material](https://img.shields.io/badge/Angular%20Material-22-757575?style=flat-square&logo=materialdesign&logoColor=white) ![Release](https://img.shields.io/github/v/release/nexa-suite/portal?display_name=tag&sort=semver&style=flat-square&label=release)

</td>
<td width="50%" valign="top">

### [Nexa Platform](https://github.com/nexa-suite/platform)

Internal operational workspace for tenant teams, sales, warehouse, and logistics.

[Open Repository](https://github.com/nexa-suite/platform)

![Angular](https://img.shields.io/badge/Angular-22-DD0031?style=flat-square&logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Material](https://img.shields.io/badge/Angular%20Material-22-757575?style=flat-square&logo=materialdesign&logoColor=white) ![Release](https://img.shields.io/github/v/release/nexa-suite/platform?display_name=tag&sort=semver&style=flat-square&label=release)

</td>
</tr>
</table>
## Product Areas

| Area | Product responsibility |
|---|---|
| Catalog and pricing | Product discovery and commercial availability |
| Commercial operations | Purchase Requests and Sales Orders |
| Inventory and warehouse | Stock, lots, reservations, and fulfillment readiness |
| Logistics and delivery | Dispatch, incidents, tracking, and proof of delivery |
| Buyer self-service | Reliable purchasing and delivery visibility |
| Public experience | Product positioning, contact, and demo entry points |
| Mobile runway | Future buyer and field experiences with explicit acceptance boundaries |
| Delivery evidence | Report structure, validation, and traceable product evidence |

## Engineering Principles

- GitFlow, reviewable workstreams, and traceable delivery.
- Conventional Commits for reviewable history.
- Semantic Versioning for published repository releases.
- Security-aware delivery with repository-owned disclosure policies.
- Evidence-backed validation across build, tests, runtime, and browser checks.
- Current product truth kept separate from historical context.

## Technology Stack

| Surface | Verified technology |
|---|---|
| API | Java 25, Spring Boot 4.1.x, PostgreSQL 18, Flyway, Maven |
| Platform | Angular 22, TypeScript, Angular Material, Signals, RxJS |
| Buyer Portal | Angular 22, TypeScript, Angular Material, Signals, RxJS |
| Website | HTML5, CSS3, and vanilla JavaScript |
| Mobile | Documentation and native runway; framework not selected |
| Mobile Report | Markdown, Python validators, Bash, and PDF export tooling |

## Security

Current product repositories publish their own security guidance. Use the repository-owned Security Policy; do not report vulnerabilities through public issues.

## Legal

Copyright © 2026 Nexa. All rights reserved. No open-source license is selected by this profile.

<div align="center"><br />Nexa · Current product, explicit evidence boundaries</div>
