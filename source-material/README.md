# Source Material Staging Area

**Location**: `source-material/` (at repository root, git-ignored)

**Purpose**: **Staging folder for migration** - Temporary staging area where source content is placed before review and transformation into GitHub Foundations learning content.

---

## 🎯 Purpose

This folder is used to stage raw source materials (transcripts, notes, documents, etc.) before they are transformed into structured learning content for the GitHub Foundations certification journey.

---

## 📋 Critical Workflow

1. **Place materials**: Place source materials (transcripts, notes, documents) in `source-material/` folder
2. **Review and migrate**: AI assistant reviews content, identifies unique topics, and migrates/transforms following repository content rules
3. **Verify migration**: Confirm all unique content has been migrated to appropriate `src/` folders
4. **Keep source files**: After successful migration, keep source files in `source-material/` folder - you will delete manually when ready

---

## ⚠️ Important Rules

- ⚠️ **Files in `source-material/` are NOT required to be compliant** - this is a staging area for raw source content
- ❌ **NEVER MODIFY files in `source-material/`** - AI assistants must ONLY READ these files for migration purposes, never edit, format, or change them
- ✅ **Review rules apply DURING transformation** - ensure transformation process follows all content rules
- ✅ **When requesting migration**: Review ALL files in `source-material/`, identify unique content, and migrate following repository structure
- ❌ **Never commit `source-material/` content** - it's git-ignored for a reason
- ✅ **Keep `source-material/` folder** - it's a permanent staging area for future migrations

---

## 📁 Target Structure

After transformation, content should be placed in:

- `src/01_github-basics/` - Core GitHub concepts
- `src/02_working-with-repositories/` - Branching, commits, merges
- `src/03_collaboration/` - PRs, reviews, issues
- `src/04_github-tools/` - Actions, Pages, Marketplace
- `src/05_security-and-best-practices/` - Permissions, secrets, protection
- `src/06_open-source-and-community/` - Licenses, OSS workflows
- `src/labs/` - Hands-on exercises
- `src/notes/` - Exam tips, glossary, common mistakes
- `src/resources/` - Official links, practice questions, cheat sheets
- `src/progress/` - Milestones, study log, readiness tracking

---

## 🔄 Transformation Process

When you request migration:

1. **OBSERVE**: AI will scan and catalog source content
2. **ANALYZE**: Identify key concepts and learning objectives
3. **REASON**: Determine appropriate placement in `src/` structure
4. **TRANSFORM**: Create new educational content following repository rules
5. **VERIFY**: Review final content before committing

---

## 📝 Notes

- This folder is git-ignored - files here won't be committed to the repository
- Source files remain after migration - you delete them manually when ready
- All transformed content must follow the repository's content structure and naming conventions
- Content should be organized by GitHub Foundations exam domains

---

**Last Updated**: December 24, 2025

