<div align="center">

<br/>

<img src="./assets/nexa-banner.svg" alt="Nexa Banner" width="100%"/>

<br/><br/>

# Nexa Suite

**Cold-chain operations platform for coordinated B2B refrigerated food commerce.**

<br/>

[![Java 26](https://img.shields.io/badge/Java-26-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://jdk.java.net/26/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-4.1.0-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Angular 22](https://img.shields.io/badge/Angular-22-DD0031?style=for-the-badge&logo=angular&logoColor=white)](https://angular.dev/)
[![Flutter 3](https://img.shields.io/badge/Flutter-3-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)

<br/>

![Course](https://img.shields.io/badge/Course-1ASI0730%20Aplicaciones%20Web-0a2540?style=flat-square)
![Cycle](https://img.shields.io/badge/Cycle-2026--10-0a2540?style=flat-square)
![University](https://img.shields.io/badge/University-UPC-0a2540?style=flat-square)
![Team](https://img.shields.io/badge/Team-King-2a67d9?style=flat-square)
![Status](https://img.shields.io/badge/Status-Migration%20Active-22c55e?style=flat-square)

<br/>

</div>

---

## What is Nexa?

Nexa is an academic software platform designed to streamline B2B refrigerated food commerce. It replaces manual logistics and unscheduled communications with structured digital workflows, giving B2B buyers and distributors shared visibility over orders, inventory levels, routes, and invoices.

The project is currently undergoing a complete architecture and interface migration, transitioning from a legacy Vue/ASP.NET stack to a modern Angular/Spring Boot stack.

---

## Repository Map

### 🚀 Modern Migration Target Stack
These repositories represent the active modern migration path that will serve as the final production targets.

<table>
  <tr>
    <td width="50%">
      <p><strong><a href="https://github.com/nexa-suite/api-spring">api-spring</a></strong></p>
      <p>Central multi-tenant REST API backend. Built using Spring Modulith for robust boundary enforcement.</p>
      <p>
        <img alt="Java 26" src="https://img.shields.io/badge/Java-26-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
        <img alt="Spring Boot 4.1" src="https://img.shields.io/badge/Spring_Boot-4.1-6DB33F?style=flat-square&logo=spring&logoColor=white" />
        <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-18-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
        <img alt="Flyway" src="https://img.shields.io/badge/Migrations-Flyway-red?style=flat-square&logo=redhat&logoColor=white" />
      </p>
    </td>
    <td width="50%">
      <p><strong><a href="https://github.com/nexa-suite/platform-angular">platform-angular</a></strong></p>
      <p>Operations dashboard for internal users (owners, sales, and logistics coordinators).</p>
      <p>
        <img alt="Angular 22" src="https://img.shields.io/badge/Angular-22-DD0031?style=flat-square&logo=angular&logoColor=white" />
        <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-6-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img alt="Material" src="https://img.shields.io/badge/Material-22-757575?style=flat-square&logo=materialdesign&logoColor=white" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <p><strong><a href="https://github.com/nexa-suite/portal-angular">portal-angular</a></strong></p>
      <p>Buyer self-service portal for catalog browsing, purchase requests, and order tracking.</p>
      <p>
        <img alt="Angular 22" src="https://img.shields.io/badge/Angular-22-DD0031?style=flat-square&logo=angular&logoColor=white" />
        <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-6-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img alt="Material" src="https://img.shields.io/badge/Material-22-757575?style=flat-square&logo=materialdesign&logoColor=white" />
      </p>
    </td>
    <td width="50%">
      <p><strong><a href="https://github.com/nexa-suite/mobile">mobile</a></strong></p>
      <p>Cross-platform client for field operators, warehouse scanning, and logistics dispatch.</p>
      <p>
        <img alt="Flutter 3" src="https://img.shields.io/badge/Flutter-3-02569B?style=flat-square&logo=flutter&logoColor=white" />
        <img alt="Dart" src="https://img.shields.io/badge/Dart-3-0175C2?style=flat-square&logo=dart&logoColor=white" />
        <img alt="OS Support" src="https://img.shields.io/badge/OS-Android%20%7C%20iOS-lightgrey?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

### 🌐 Public Client
This repository represents the public face and legal landing page of the product.

<table>
  <tr>
    <td width="100%">
      <p><strong><a href="https://github.com/nexa-suite/website">website</a></strong></p>
      <p>Public landing website, commercial presentation, FAQ, pricing tables, and legal policies.</p>
      <p>
        <img alt="HTML5" src="https://img.shields.io/badge/HTML5-static-E34F26?style=flat-square&logo=html5&logoColor=white" />
        <img alt="CSS3" src="https://img.shields.io/badge/CSS3-responsive-1572B6?style=flat-square&logo=css3&logoColor=white" />
        <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
      </p>
    </td>
  </tr>
</table>

### 🏛️ Legacy Reference Stack
These repositories serve as the visual, database schema, and behavioral reference for migration. They will remain read-only during the modern transition.

<table>
  <tr>
    <td width="33%">
      <p><strong><a href="https://github.com/nexa-suite/api">api</a></strong></p>
      <p>Legacy C# API reference.</p>
      <p>
        <img alt=".NET Core 8" src="https://img.shields.io/badge/.NET%20Core-8-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
      </p>
    </td>
    <td width="33%">
      <p><strong><a href="https://github.com/nexa-suite/platform">platform</a></strong></p>
      <p>Legacy Vue operations dashboard.</p>
      <p>
        <img alt="Vue 3" src="https://img.shields.io/badge/Vue%203-35495E?style=flat-square&logo=vue.js&logoColor=white" />
      </p>
    </td>
    <td width="34%">
      <p><strong><a href="https://github.com/nexa-suite/portal">portal</a></strong></p>
      <p>Legacy Vue buyer portal reference.</p>
      <p>
        <img alt="Vue 3" src="https://img.shields.io/badge/Vue%203-35495E?style=flat-square&logo=vue.js&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

---

## Bounded Contexts & Product Areas

| Area | Purpose | Core Responsibilities |
| :--- | :--- | :--- |
| **Sales** | B2B Purchase Coordination | Order registration, approval workflows, commercial policies, client lists |
| **Logistics** | Dispatch Tracking | Routing sheets, delivery coordinates, shipment progress, temperature logs |
| **Warehouse** | Cold-Chain Inventory | Cold-storage lots, inventory levels, warehouse stock tracking, item reservations |
| **Invoicing** | Transaction Reconciliation | Automated invoices, receipts, payment records, billing logs |
| **Catalog** | B2B Product Listing | Active items, custom client pricing lists, food category listings |
| **IAM & Tenant** | Access & Membership | Tenant isolation, multi-tenant roles, workspace memberships, token issuance |

---

## Delivery & SCM Standards

We maintain clean engineering history and traceability using unified standards:

* 🌿 **Branch Strategy**: We adhere to **GitFlow** branch governance. Direct commits to `main` are restricted.
* 💬 **Conventional Commits**: Commit messages must follow the Conventional Commits 1.0.0 specification with explicit Context, Changes, Reason, and Validation blocks.
* 🏷️ **Semantic Versioning**: Deliveries correspond to SemVer 2.0.0 (`MAJOR.MINOR.PATCH`).
* 📜 **API Releases**: Release logs are risk-focused, documenting payload changes and deprecation timelines with active HTTP Sunset dates.

---

## Team

| Member | Code | Focus | GitHub Profile |
| :--- | :--- | :--- | :--- |
| **Yucra Sandoval, Diego Sebastian** | U202323040 | Team Leader / Sales | [@DiegoS284](https://github.com/DiegoS284) |
| **Marín Cueva, César Fernando** | U202411937 | Logistics & Sales | [@Cmarin2802](https://github.com/Cmarin2802) |
| **Verde Bueno, Joaquín Francisco** | U20241A054 | Warehouse | [@JoaquinVerde115](https://github.com/JoaquinVerde115) |
| **Torrejón De Los Santos, Gino Rodrigo**| U202416289 | Catalog & Warehouse | [@R0obxdnt-bit](https://github.com/R0obxdnt-bit) |
| **Rojas Mancilla, Gerard Gianpier** | U202413142 | Invoicing | [@GerardRojasMancilla](https://github.com/GerardRojasMancilla) |

---

## Academic Context

* **University**: Universidad Peruana de Ciencias Aplicadas (UPC)
* **Course**: Aplicaciones Web (*1ASI0730*)
* **Academic Cycle**: 2026-10
* **Course Focus**: Validating B2B Cold-Chain Distribution Platform UI & Architecture

---

<div align="center">
  <strong>Nexa Platform</strong> · Universidad Peruana de Ciencias Aplicadas · 2026-10
</div>
