# Mart Management System & AgriCare AI

## 📌 Project Overview
This repository contains two core software engineering projects aimed at automating retail operations and revolutionizing agriculture through AI.

1.  **Mart Management System:** A three-tier desktop/web application for inventory, billing, and employee management.
2.  **AgriCare AI:** A mobile-first solution using Computer Vision to diagnose crop diseases and provide treatment plans for farmers.

---

## 🛠 Tech Stack & Architecture
- **Architecture:** Three-Tier Architecture (Presentation, Application, and Data layers).
- **AI Component:** CNN-based Image Classification (TensorFlow/PyTorch).
- **Database:** Relational Database (SQL-based).

---

## 🌿 Branching Strategy
We follow the **Git Flow** model to ensure code stability and seamless collaboration. All development work must be performed in dedicated branches.

### 1. Permanent Branches
* **`main`**: Contains the latest "Production-Ready" stable code. This branch is protected; no direct commits are allowed.
* **`develop`**: The main integration branch. All completed features are merged here for testing before moving to `main`.

### 2. Temporary Branches
* **`feature/ <task-name>`**: Used for developing new features (e.g., `feature/billing-module`).
* **`bugfix/ <issue-name>`**: Used for fixing bugs found in the `develop` branch.
* **`hotfix/ <issue-name>`**: Used for emergency fixes in the `main` branch.

### 3. Workflow Steps
1.  **Clone/Pull:** Always start by pulling the latest `develop` branch.
2.  **Branch:** Create a new branch: `git checkout -b feature/your-feature-name`.
3.  **Commit:** Use descriptive commit messages (e.g., `feat: add CNIC validation`).
4.  **PR:** Open a Pull Request to merge your feature into `develop`.
5.  **Merge:** Once reviewed and tested, the feature is integrated.

---

## 📋 Core Features (In Progress)
- [ ] **Auth:** Role-based login (Admin, Manager, Employee).
- [ ] **Inventory:** Low-stock and Expiry date automated alerts.
- [ ] **Billing:** Automated total calculation and discount logic.
- [ ] **AI (AgriCare):** Real-time leaf disease detection.

---

## 👥 Contributors
- **[Haseeb Ahmad]** - Lead Developer / System Architect
- **[Muhammad Faeiq]**
- **[Maira Waheed]**
- **[Iqra Abdul Malik]**
