---
marp: true
title: "📋 Not Just a Pretty Board: Making Azure DevOps Actually Work for You"
paginate: true
theme: default
---

# 📋 Not Just a Pretty Board  
## Making Azure DevOps Actually Work for You

---

## 🧭 Azure Scrum Board Overview

- **Hierarchy**:
  - **Epics** → **Features** → **Product Backlog Items (PBIs)**
- Helps organize work from high-level goals to actionable tasks

---

## 🔁 Dev Cycle Overview

- **Stages**:
  - Requirement Gathering  
  - Analysis  
  - Implementation / Development  
  - Testing  
  - Production Deployment  
  - Maintenance

---

## 🎯 Focus of This Presentation

- Zooming in on the **Development → Production Deployment** stages
- How to **track and visualize** these stages in Azure DevOps

---

## 👀 Visibility into Dev Stages on ADO Board

### 🔖 Tagging Commit Messages
- Use `#WorkItemID` in commit messages
- Automatically links commits to PBIs

---

## 🌿 Linking Branches

- Create branches from work items
- Ensures traceability between code and tasks

---

## 🧪 Linking Test Cases

- Associate test cases with PBIs
- Track test coverage and results directly in the board

---

## 🚀 Reporting Release Stages

- Use **Release Pipelines** to:
  - Track deployment progress
  - Visualize environments (Dev → QA → Prod)
  - Audit deployment history

---

## 🎥 Demo

- Walkthrough of:
  - Commit tagging
  - Branch linking
  - Test case association
  - Release tracking

---

## ⚠️ Fall Backs & Limitations

- YAML pipelines **not fully supported** in UI
- Must **enable specific settings** for full visibility
- Branches may **not auto-link** without manual association

---

## ✅ Summary

- Azure DevOps boards can go beyond task tracking
- With proper setup, they provide **end-to-end visibility**
- Empower your team with **traceability and transparency**

---

## 🙋 Q&A

- Open discussion and questions
