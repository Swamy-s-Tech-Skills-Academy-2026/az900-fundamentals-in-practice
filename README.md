# az900-fundamentals-in-practice
A structured, exam-aligned learning and revision repository for the Microsoft AZ-900: Azure Fundamentals certification. Focused on core concepts, mental models, and exam readiness. This is a personal learning journey, not official training material.


That is a **sound and architecturally clean decision**.
Placing all learning content under a `src/` root aligns well with **professional repository hygiene** and keeps the repository extensible.

Below is the **recommended final structure**, with rationale and a repo-ready blueprint.

---

## ✅ Final Recommended Repository Structure

```
az900-fundamentals-in-practice
│
├── README.md
├── progress.md
├── resources.md
│
├── src/
│   ├── 01_cloud-concepts/
│   │   ├── README.md
│   │   ├── 01_cloud-computing-basics.md
│   │   ├── 02_cloud-service-models.md
│   │   ├── 03_cloud-deployment-models.md
│   │   └── 04_cloud-economics.md
│   │
│   ├── 02_azure-architecture-services/
│   │   ├── README.md
│   │   ├── 01_core-architectural-components.md
│   │   ├── 02_compute-services.md
│   │   ├── 03_networking-services.md
│   │   └── 04_storage-services.md
│   │
│   ├── 03_azure-management-governance/
│   │   ├── README.md
│   │   ├── 01_identity-access-management.md
│   │   ├── 02_cost-management.md
│   │   ├── 03_governance-features.md
│   │   └── 04_resource-management-tools.md
│   │
│   ├── 04_azure-security-compliance/
│   │   ├── README.md
│   │   ├── 01_shared-responsibility-model.md
│   │   ├── 02_azure-security-tools.md
│   │   ├── 03_compliance-offerings.md
│   │   └── 04_trust-privacy.md
│   │
│   ├── 90_exam-prep/
│   │   ├── README.md
│   │   ├── exam-tips.md
│   │   ├── common-trick-questions.md
│   │   ├── last-day-revision.md
│   │   └── mock-questions.md
│   │
│   └── 99_notes/
│       ├── README.md
│       ├── glossary.md
│       ├── acronyms.md
│       └── mental-models.md
```

---

## 🎯 Why `src/` Is the Right Choice

From an **architecture and repository design perspective**:

* `src/` clearly communicates: *this is the learning content*
* Root remains clean for:

  * README
  * progress tracking
  * meta documentation
* Easy future extension:

  * `labs/` (if ever needed)
  * `assets/` (diagrams)
  * `scripts/` (if you later automate checks)

This mirrors **real-world mono-repo discipline**, even for learning projects.

---

## 📌 Naming Convention Rules (Lock These In)

**Folders**

* Two-digit numeric prefix
* Hyphenated lowercase
* Exam-domain aligned

**Files**

* Two-digit numeric prefix
* Singular concept per file
* No dates
* No version numbers

✅ Good
`02_compute-services.md`

❌ Avoid
`compute_services_v1.md`
`azure-compute-notes.md`

---

## 📘 Folder-Level `README.md` (Pattern)

Each folder README should answer **three questions only**:

1. What does this domain cover in AZ-900?
2. Why it matters for the exam?
3. What misconceptions candidates commonly have?

Keep it under **1 page**.

---

## 🚀 Immediate Next Step (Recommended)

**Commit 1**

* Create the full folder structure under `src/`
* Add empty `README.md` files per folder
* No content yet

**Commit 2**

* Write `src/01_cloud-concepts/README.md`
* Write `01_cloud-computing-basics.md`

I strongly recommend starting with **Cloud Concepts** before touching any Azure service.

---

If you want, next I can:

* Review your **actual GitHub tree once pushed**
* Draft **folder README templates**
* Create **AZ-900 mental models (diagrams + text)**
* Cross-check this structure against the **latest Microsoft Learn AZ-900 outline**

Tell me how you’d like to proceed.
