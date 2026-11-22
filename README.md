# 🛡️ A-to-Z SQA End-to-End Workflow & Live Simulator

[![Live Demo](https://img.shields.io/badge/Live_Demo-sqa.shoyebrabbi.com-2563eb?style=for-the-badge&logo=googlechrome&logoColor=white)](https://sqa.shoyebrabbi.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero_(Vanilla_HTML%2FCSS%2FJS)-f59e0b?style=for-the-badge)](#tech-stack)

An interactive, modular **Bento-Box Command Center** and **End-to-End SQA Workflow Simulator** designed to visualize, practice, and master the complete Software Quality Assurance lifecycle—from initial **Client Requirement Gathering (BRS)** and **Shift-Left SRS Analysis** to **Staging Execution, Jira Bug Loops, UAT, QA Sign-Off, and Production Handover**.

---

## ✨ Key Features

- **10-Step End-to-End SDLC + STLC Pipeline:** Interactive walkthrough covering every stage from client intake to live production release.
- **Role & Artifact Matrix (RACI View):** Clearly breaks down who actively works on each phase, who is excluded, and what deliverables are produced (`BRS`, `SRS`, `Query Log`, `Master Test Plan`, `Test Cases`, `RTM`, `Test Summary Report`, `QA Sign-Off`).
- **Shift-Left Query Log & SRS Gap Finder Lab:** Hands-on simulator based on an **ISP Billing & Auth** specification where you spot missing edge cases, log ambiguities, and resolve clarifications.
- **Live Smoke, API, SQL & Jira Bug Loop Runner:**
  - Execute Staging builds and inspect simulated **HTTP JSON payloads** and **PostgreSQL verification queries**.
  - Trigger a simulated `500` MikroTik webhook defect, auto-log it to **Jira**, deploy a developer fix patch, and verify via **Retesting & Regression**.
- **QA Sign-Off & Release Gatekeeper:** Enforces strict **Exit Criteria** (`100%` RTM coverage, `0` open critical bugs) before issuing official **QA Sign-Off** and running the final **Post-Release Sanity Check**.
- **Bilingual (`EN | BN`) & 4 Adaptive SQA Themes:**
  - Instant one-click toggle between **English (`EN`)** and **Bengali (`BN`)**—including spoken interview scripts and SQA flashcards.
  - Switch between **Clean Light**, **Dark Glass**, **Staging Lab**, and **Prod Live** themes, plus per-card contrast micro-toggles.

---

## 🗺️ The 10-Step SQA Workflow Covered

| Step | Phase Name | Primary Owner(s) | Key Deliverable(s) |
| :--- | :--- | :--- | :--- |
| **01** | **Requirement Gathering** | Client, PM, Business Analyst (BA) | `BRS` (Business Requirement Specification) |
| **02** | **Requirement Analysis & Gap Finding** | **SQA Engineer**, BA/System Analyst, Tech Lead | `SRS`, `Acceptance Criteria`, `SQA Query Log`, `Initial RTM` |
| **03** | **System Design & Test Planning** | **QA Lead / SQA**, Software Architect, UI/UX | `Master Test Plan`, `ERD`, `Wireframes` |
| **04** | **Test Case Design & RTM Mapping** | **SQA Engineer** | `Test Scenarios`, `Test Cases (BVA/ECP)`, `100% RTM` |
| **05** | **Environment Setup & Staging Build** | DevOps / Developers, **SQA Engineer** | `QA/Staging Build`, `Test Accounts & Seed Data` |
| **06** | **Test Execution (Smoke, UI, API, DB)** | **SQA Engineer** | `Test Execution Report`, `Postman & SQL Logs` |
| **07** | **Bug Reporting, Retest & Regression** | **SQA Engineer**, Developers | `Jira Bug Tickets`, `Regression Report` |
| **08** | **User Acceptance Testing (UAT)** | Client / Product Owner (with **SQA Support**) | `Client UAT Approval` |
| **09** | **Test Closure & Official QA Sign-Off** | **QA Lead / Senior SQA**, PM | `Test Summary Report (TSR)`, `QA Sign-Off` |
| **10** | **Production Release & Handover** | DevOps, **SQA Engineer**, Client | `Live App` + `Post-Release Sanity Check` |

---

## 🛠️ Tech Stack

- **Architecture:** Single-file, zero-dependency, offline-ready web application (`index.html`).
- **Layout:** Asymmetric responsive **Bento-Box CSS Grid** with CSS Custom Properties (`:root` design tokens).
- **Logic:** Vanilla ES6+ JavaScript for state management, bilingual switching, interactive labs, and toast notifications.

---

## 🚀 Quick Start (Local & GitHub Pages)

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/sqa-end-to-end-workflow.git
   cd sqa-end-to-end-workflow
   ```
2. **Run locally:**
   Open `index.html` (or `sqa_bento_workflow_simulator.html`) directly in any modern web browser—no build step or `npm install` required.
3. **Deploy on GitHub Pages:**
   - Rename `sqa_bento_workflow_simulator.html` to `index.html` in the root directory.
   - Go to **Repository Settings → Pages → Build and deployment**, select the `main` branch (`/(root)`), and click **Save**.

---

## 📂 Repository Structure

```text
├── index.html                        # Interactive Bento-Box SQA Workflow & Live Simulator
├── sqa_end_to_end_workflow.md        # Complete A-to-Z SQA Study Guide (Markdown)
├── client_to_requirement_analysis.md # Deep-dive notes on Client -> BRS -> SRS -> Query Log
├── test_planning_guide.md            # Master Test Plan components & Entry/Exit Criteria
└── README.md                         # Project documentation
```

---

## 👤 Author

**Shoyeb Rabbi**  
🌐 Portfolio & SQA Hub: [sqa.shoyebrabbi.com](https://sqa.shoyebrabbi.com)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).