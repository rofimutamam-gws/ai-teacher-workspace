# AI TEACHER WORKSPACE v1.0
**Personal Teacher Edition · Gemini Skills**

## Purpose
A modular personal AI workspace for educators. Each specialist Skill performs a clearly bounded job, follows shared operating standards, uses its own uploaded references, and produces quality-checked teaching artifacts.

## Locked design decisions
| Parameter | Decision |
|---|---|
| Audience | Personal teacher |
| Primary platform | Google Gemini Skills |
| Curriculum | Flexible / multi-curriculum |
| References | Uploaded per Skill |
| Documents | Specialized layout by document type |
| Interaction | Guided workflow |
| Production confirmation | `PROCEED!` |
| Conversation language | Indonesian |
| Skill instruction format | `SKILL.md` |
| Main deliverable | Editable DOCX |
| Master storage | GitHub |
| Development | Complete, phased |

## Repository map
- `00_MASTER_BLUEPRINT/` — product identity, architecture, roadmap.
- `01_CORE_SYSTEM/` — shared rules, skill framework, curriculum and reference policies.
- `02_SKILL_LIBRARY/` — specialist Skills grouped by department.
- `03_KNOWLEDGE_BASE/` — curated reference library and source register.
- `04_DOCUMENT_TEMPLATES/` — document profiles and reusable templates.
- `05_TESTING_QA/` — test plans, test cases, release checklists.
- `06_RELEASES/` — validated Skill packages ready to import.
- `07_CHANGELOG/` — project and Skill change history.

## Operating rule
The repository is the source of truth. Gemini is the execution environment. Never treat an untested Gemini upload as the only master copy.

## Current status
Phase 1 — Workspace Foundation. The three foundation documents are:
1. `00_MASTER_BLUEPRINT/MASTER_BLUEPRINT.md`
2. `01_CORE_SYSTEM/WORKSPACE_STANDARDS.md`
3. `01_CORE_SYSTEM/UNIVERSAL_SKILL_FRAMEWORK.md`

See `PHASE_1_IMPLEMENTATION_GUIDE.md` for the build sequence.
