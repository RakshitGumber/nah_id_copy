<!-- Use this template for tools like linear, postman, etc -->

# {{PROJECT_NAME}}

## {{ONE_LINE_DESCRIPTION}}

---

## Overview

| Field           | value             |
| --------------- | ----------------- |
| Project ID      | {{ID}}            |
| Status          | {{PROGRESS}}      |
| Priority        | {{PRIORITY}}      |
| Start Date      | {{MM-YYYY}}       |
| Target End Date | {{MM-YYYY}}       |
| Owner           | @username         |
| Team            | Python-Developers |
| Cycle           | Sprint {{NO}}     |

---

## Objective

Describe what this project aims to achieve and why it matters.

```
This project will deliver {{what}} for {{whom}} so that {{outcome}}.
Success is measured by {{metric}}.
```

---

## 📦 Scope

### ✅ In Scope

- [ ] Feature A
- [ ] Feature B
- [ ] Feature C

### ❌ Out of Scope

- Feature D (deferred to next phase)
- Feature E (not required)

| Milestone          | Status         | Owner | Due Date   |
| ------------------ | -------------- | ----- | ---------- |
| Research & Design  | ✅ Done        | @user | 2024-01-10 |
| MVP Implementation | ✅ Done        | @user | 2024-01-25 |
| Integration        | 🟡 In Progress | @user | 2024-02-10 |
| Testing & QA       | 🔴 Not Started | @user | 2024-02-20 |
| Deployment         | 🔴 Not Started | @user | 2024-02-28 |

---

## 🏗️ Technical Details

| Field            | Value                             |
| ---------------- | --------------------------------- |
| **Tech Stack**   | Next.js, Node.js, PostgreSQL      |
| **Repository**   | [link](https://github.com/...)    |
| **Environment**  | Staging / Production              |
| **API Base URL** | `https://api.staging.example.com` |
| **Branch**       | `main` / `develop`                |
| **CI/CD**        | GitHub Actions                    |

---

### Key Commands

```bash
# Install
npm install

# Dev
npm run dev

# Build
npm run build

# Test
npm run test

# Deploy
npm run deploy
```

---

## Links & Resources

| Resource           | Link                |
| ------------------ | ------------------- |
| GitHub Repo        | [link](https://...) |
| Figma Design       | [link](https://...) |
| API Docs (Postman) | [link](https://...) |
| Database Schema    | [link](https://...) |
| Linear Project     | [link](https://...) |
| Slack Channel      | `#project-name`     |
| Live Demo          | [link](https://...) |

---

## Notes

- Any additional context, decisions, or reminders go here.
- Architecture decisions: link to ADRs.
- Meeting notes: link to meeting docs.

---

## Changelog

| Date       | Version | Change              |
| ---------- | ------- | ------------------- |
| 2024-01-10 | v0.1.0  | Project initialized |
| 2024-01-25 | v0.2.0  | MVP completed       |

---

## 📄 `projects/internal-readme.md`

````markdown
# {{PROJECT_NAME}} — Internal README

> Internal documentation for the {{team}} team. Not for public consumption.

---

## 📖 What is this?

Short paragraph explaining the project, its purpose within the larger system, and who owns it.

---

## 🚀 Quick Start

```bash
# Clone
git clone git@github.com:org/{{repo}}.git
cd {{repo}}

# Install
npm install

# Environment
cp .env.example .env
# Ask @teammate for .env values

# Run
npm run dev
```
````
