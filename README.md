# 🛡️ Relational Database Design & Implementation for Fraud Detection and AML/KYC Management

## 🏫 Academic Framework
* **Institution:** Higher School of Communications of Tunis (SUP'COM)
* **Academic Year:** 2025-2026
* **Project:** Database Engineering (MCD / MLD / SQL)

---

## 📝 Project Overview
This project focuses on modeling and deploying a robust relational database engine using **Oracle SQL**, specifically engineered to meet the strict regulatory requirements of modern finance (**AML - Anti-Money Laundering** directives and **KYC - Know Your Customer** procedures).

The system centralizes and analyzes large volumes of core financial data in real time to automate anomaly detection, mitigate systemic banking risks, and prevent sophisticated financial fraud attempts.

---

## 🛠️ Repository Deliverables
This repository centralizes all technical engineering blueprints and documentation:
* **`cahier_des_charges.pdf`**: The technical specifications document detailing the core banking rules, system scope, and strict compliance constraints.
* **`Presentation_projet.pdf`**: The comprehensive project presentation highlighting the architecture, system goals, and analytical results.
* **`Looping1 (1).jpg`**: The Conceptual and Logical Data Models (MCD/MLD) generated using Looping to map complex relational interactions (Clients, Accounts, Financial Transactions, KYC Verification Logs, and Alerting Entities).

---

## 🧠 Core Algorithmic SQL Queries Deployed
The backend data engine integrates over 30 advanced data analytics and security audit scripts. Key algorithmic queries implemented include:

1. **Structuring / Smurfing Detection (Transaction Fractioning) - [Query 29]:**
   An advanced SQL script designed to isolate repeated transactions intentionally targeted between **€9,000 and €9,999** over a 7-day rolling window. This algorithm flags users attempting to bypass the standard legal mandatory reporting threshold of €10,000.
   
2. **Internal Corporate Auditing (Insider Threat Detection) - [Query 27]:**
   Instantly identifies employees accessing client profiles outside their specific branch or regional scope, flagging potential corporate espionage, internal database breaches, or collusion with fraudsters.

3. **Regulatory KYC Compliance Violations - [Queries 28 & 30]:**
   * Automates the restriction and isolation of financial transactions triggered by accounts holding expired identity documents.
   * Tracks and scores entities with 2 or more successive KYC verification rejections, systematically isolating potential identity theft or fraudulent onboarding attempts.

---

## 💻 Tech Stack & Regulatory Compliance
* **RDBMS:** Oracle SQL (PL/SQL)
* **Data Modeling:** Looping (MCD / MLD Generation)
* **Target Standards:** FATF/GAFI Recommendations, European Union 5th AML Directive, Tunisian Anti-Money Laundering and Counter-Terrorism Financing Laws.
