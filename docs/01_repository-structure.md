# Repository Structure

**Version**: 1.0  
**Last Updated**: December 29, 2025  
**Purpose**: Single source of truth for repository structure

> **Note**: This document should be referenced from `README.md` and other documentation files. When the structure changes, update this file first, then update references.

---

## Complete Repository Structure

```text
az900-fundamentals-in-practice/
│
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── SECURITY.md
├── CODE_OF_CONDUCT.md
├── .gitignore
├── lychee.toml
├── progress.md
├── resources.md
│
├── docs/
│   ├── 01_repository-structure.md (this file)
│   └── images/
│       └── .gitkeep
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
│   ├── 99_notes/
│   │   ├── README.md
│   │   ├── glossary.md
│   │   ├── acronyms.md
│   │   └── mental-models.md
│   │
│   └── resources/
│       ├── official-links.md
│       ├── practice-questions.md
│       └── cheat-sheets.md
```

---

## Key Structure Notes

### File Naming Conventions

- **Domain Folders** (`src/01_cloud-concepts/` through `src/04_azure-security-compliance/`):
  - ✅ Use zero-padded numeric prefixes: `01_`, `02_`, etc.
  - ✅ Use hyphens for multi-word names: `01_cloud-concepts/`
  - ✅ Content files use numeric prefixes: `01_cloud-computing-basics.md`

- **Special Folders**:
  - `90_exam-prep/` - Exam preparation materials
  - `99_notes/` - Reference materials (glossary, acronyms, mental models)
  - `resources/` - Official links, practice questions, cheat sheets

### Content Organization

1. **Learning Progression**: Content follows AZ-900 exam domains (01 → 04)
2. **All Content Under `src/`**: All learning materials, notes, progress, and resources are organized under the `src/` directory
3. **Domain README Files**: Each domain folder contains a README.md that explains:
   - What the domain covers
   - Why it matters for the exam
   - Common misconceptions

### Special Directories

- **`src/90_exam-prep/`**: Exam preparation materials and strategies
- **`src/99_notes/`**: Reference materials (glossary, acronyms, mental models)
- **`src/resources/`**: Official links, practice questions, cheat sheets
- **`docs/`**: Additional documentation and images
- **`progress.md`**: Root-level progress tracking file

---

## Update Protocol

**When repository structure changes**:

1. ✅ **Update this file first** (`docs/01_repository-structure.md`)
2. ✅ **Update references** in:
   - `README.md` - Reference this file
3. ✅ **Verify consistency** across all documentation

**Self-Check Question**: "Did I update `docs/01_repository-structure.md` first?" - If no, STOP and do it NOW.

---

## References

- **Repository Structure**: This file (`docs/01_repository-structure.md`)
- **Learning Path**: `README.md`
