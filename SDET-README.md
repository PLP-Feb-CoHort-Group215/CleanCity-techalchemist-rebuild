# CleanCity: Tech Alchemist Rebuild

> Enterprise QA Automation & SDLC Showcase | React · FastAPI · Cypress · GitHub Actions

**Domain:** CivicTech / QA Automation / CI/CD
**Version:** v2.0 (Rebuilt for QA Governance)
**Status:** Active (Under RespokeTech Labs)

---

## Overview

**CleanCity: Tech Alchemist Rebuild** is an enterprise-grade modernization of the *CleanCity Waste Pickup Scheduler* — re-engineered under **Tech Alchemist QA Governance**.

This rebuild demonstrates a **complete Software Development Lifecycle (SDLC)** from **requirements → architecture → QA automation → CI/CD**, showcasing professional-grade **SDET (Software Development Engineer in Test)** capabilities.

It is designed as a **portfolio-quality QA sandbox** for:
- Demonstrating automation architecture design
- Practicing TDD + BDD principles
- Implementing end-to-end CI/CD pipelines
- Integrating performance, security, and accessibility testing
- Producing auditable QA documentation (Vision Docs, PRD, Test Policy, etc.)

---

## Core Objectives

| Goal                   | Description                                                                        |
| ---------------------- | ---------------------------------------------------------------------------------- |
| **SDET Readiness**     | Demonstrate mastery of test automation frameworks, CI/CD, and QA architecture      |
| **Full SDLC Showcase** | Include business docs, PRDs, governance charters, and test policies                |
| **Enterprise Tooling** | Integrate static analysis, unit/integration testing, and pipeline automation       |
| **Recruiter-Facing**   | Position as a real-world QA platform demonstrating ownership & delivery discipline |

---

## Key Enhancements

| Area               | Old Version                    | Rebuild Improvements                                    |
| ------------------ | ------------------------------ | ------------------------------------------------------- |
| **Architecture**   | React-only front-end           | Modularized monorepo (client/server/docs/tests)         |
| **Documentation**  | Single README                  | Full QA suite (Vision, BRD, PRD, Test Policy, RTM)      |
| **Testing**        | Manual + React Testing Library | Cypress, Jest, Playwright + API & Performance tests     |
| **DevOps**         | Local builds only              | GitHub Actions CI/CD + Dockerized environment           |
| **Governance**     | No formal policies             | QA Governance Charter + Requirements Review workflows   |
| **AI Integration** | None                           | Optional AI-powered test analytics (LLM-based insights) |

---

## Tech Stack

**Frontend:** React + Vite + TailwindCSS
**Backend:** FastAPI / Express (mock API service)
**Database:** PostgreSQL / SQLite (lightweight mode)
**Testing Stack:**
- **Unit:** Jest + React Testing Library
- **E2E:** Cypress / Playwright
- **API:** Postman / Newman
- **Performance:** JMeter / k6
- **Accessibility:** Axe / Lighthouse

**DevOps:** GitHub Actions + Docker + Netlify (Client) + Render (API)
**Reporting:** Allure / HTML Reports / Coverage dashboards

---

## QA Governance Flow

```
Vision Document / Project Charter
   ↓
Business Requirements Document (BRD)
   ↓
Product Requirements Document (PRD)
   ↓
Requirement Review Report
   ↓
Requirements Traceability Matrix (RTM)
   ↓
Test Strategy → Test Plan → Test Cases
   ↓
Automated & Manual Testing
   ↓
CI/CD & Reporting
```
Each stage is version-controlled and stored in `/docs/qa/` for transparency.

---

## Folder Structure

```
cleancity-techalchemist-rebuild/
├── client/                     # React frontend (Refactored UI)
├── server/                     # Mock API or FastAPI backend
├── tests/                      # Unit, API, E2E, and load tests
├── docs/
│   ├── qa/                     # Test policy, RTM, reports
│   ├── product/                # Vision, BRD, PRD, requirement reviews
│   └── architecture/           # ADRs, diagrams, CI/CD pipelines
├── scripts/                    # CI/CD, setup, or data scripts
├── .github/workflows/          # GitHub Actions pipelines
├── .vscode/                    # Dev environment configs
├── docker/                     # Containerization setup
├── LICENSE
├── README.md                   # Main repo documentation
└── commitmessage.txt           # PR / commit message template
```
---

## QA Deliverables

| Artifact                              | Description                                        |
| ------------------------------------- | -------------------------------------------------- |
| **Vision Document / Project Charter** | Defines purpose, scope, and QA objectives          |
| **Test Policy / Governance Charter**  | Establishes QA authority, principles, and tooling  |
| **BRD / PRD**                         | Maps business → technical → testable requirements  |
| **Requirement Review Report**         | QA’s feedback on requirement clarity & testability |
| **RTM**                               | Trace matrix mapping requirements → tests          |
| **Automated Tests**                   | Unit, integration, and E2E suites with reporting   |
| **CI/CD Reports**                     | Pipeline reports with build/test results           |
| **Defect Log**                        | Controlled bug tracking for intentional test cases |

---

## Setup

```
# Clone the repo
git clone https://github.com/RespokeTech/cleancity-techalchemist-rebuild.git
cd cleancity-techalchemist-rebuild

# Install dependencies
npm install

# Run locally
npm start

# Run tests
npm test
npm run e2e

# Build for production
npm run build
```

## Strategic Value

- Recruiter-ready QA portfolio project
- Industry-standard SDET governance demo
- Reusable structure for any enterprise QA automation project
- Aligns with Nobuntu / LuntuHealth ecosystem narrative

---

## Brand Attribution

**Original Project:** CleanCity — Waste Pickup Scheduler  
**Developed Under:** [PowerLearnProject Africa Software Testing Specialization Lead](https://github.com/PLP-Database-DEPT) (February Cohort 2025)  
**Original License:** Educational Use Only  

**Rebuild Title:** CleanCity: Tech Alchemist Rebuild  
**Authored & Maintained By:** Sir Poeksie (RespokeTech / Personal Brand)  
**Purpose:** QA Automation, SDLC Governance, and SDET Portfolio Demonstration  
**Theme:** “Automation with Purpose. Governance with Empathy.”

---

## License

This repository contains a **personal rebuild and extension** of the *CleanCity Waste Pickup Scheduler*, originally developed as an academic project.  

All educational assets, technical specifications, and requirement documents remain under their respective institutional licenses.  
This rebuild and all QA automation, DevOps, and documentation enhancements are released under the **RespokeTech Public QA License v1.0**, for **educational and portfolio demonstration** purposes only.

> © 2025 RespokeTech / Sir Poeksie  
> Attribution required for derivative works.  
> No commercial use without written permission.

This repository includes educational materials originally developed under an academic license.
Additions and modifications © 2025 RespokeTech (Sir Poeksie).
Released under the RespokeTech Public QA License v1.0 for non-commercial, educational demonstration.
