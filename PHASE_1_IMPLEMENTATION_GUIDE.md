# PHASE 1 IMPLEMENTATION GUIDE
## Workspace Foundation

## Phase objective
Create the minimum governance, templates, repository structure, and quality process required before authoring the 25 planned Skills.

## Workstream 1 — Create the GitHub repository
Suggested repository name: `ai-teacher-workspace`

Recommended settings:
- Private repository initially.
- README enabled.
- Default branch: `main`.
- Use folders and Markdown for source documents.
- Keep personal/student data out of the repository.
- Commit meaningful changes with concise messages.

Suggested first commits:
1. `chore: initialize workspace repository`
2. `docs: add master blueprint and workspace standards`
3. `docs: add universal skill framework`
4. `chore: add skill library and QA structure`

## Workstream 2 — Add the foundation files
Copy these files into the matching repository paths:
- `README.md`
- `00_MASTER_BLUEPRINT/MASTER_BLUEPRINT.md`
- `01_CORE_SYSTEM/WORKSPACE_STANDARDS.md`
- `01_CORE_SYSTEM/UNIVERSAL_SKILL_FRAMEWORK.md`

## Workstream 3 — Create repository folders
```text
AI-TEACHER-WORKSPACE/
├── README.md
├── PHASE_1_IMPLEMENTATION_GUIDE.md
├── 00_MASTER_BLUEPRINT/
├── 01_CORE_SYSTEM/
├── 02_SKILL_LIBRARY/
│   ├── 01_planning_curriculum/
│   ├── 02_teaching_content/
│   ├── 03_assessment_evaluation/
│   ├── 04_teacher_administration/
│   └── 05_creative_ai_productivity/
├── 03_KNOWLEDGE_BASE/
│   ├── 01_curriculum/
│   ├── 02_pedagogy/
│   ├── 03_assessment/
│   ├── 04_subject_knowledge/
│   └── 05_source_register/
├── 04_DOCUMENT_TEMPLATES/
│   ├── 01_academic_document/
│   ├── 02_student_worksheet/
│   └── 03_planning_matrix/
├── 05_TESTING_QA/
│   ├── test_plans/
│   ├── test_cases/
│   ├── test_results/
│   └── release_checklists/
├── 06_RELEASES/
│   ├── draft/
│   ├── testing/
│   └── released/
└── 07_CHANGELOG/
```

## Workstream 4 — Define document profiles
Create a profile file for each document family. Do not force one layout on every output.

Initial profiles:
- Academic: A4, 2 cm margins, Cambria 12 pt, single spacing.
- Student worksheet: A4, top/left 3 cm, right/bottom 2 cm, Times New Roman 12 pt, single spacing.
- Planning matrix: A4 portrait or landscape, Cambria 10–12 pt, single spacing, readable tables.

Before release, test page breaks, tables, numbering, headers/footers, and editability in Microsoft Word or a compatible editor.

## Workstream 5 — Define QA process
For each Skill, prepare test cases for:
1. Normal complete input.
2. Missing required information.
3. Conflicting reference files.
4. Unsupported or out-of-scope request.
5. Output formatting and file delivery.

Record:
- Skill version.
- Test date.
- Input scenario.
- Expected behavior.
- Actual behavior.
- Pass/fail.
- Defects and fixes.
- Reviewer decision.

## Workstream 6 — Gemini import and execution
- Keep repository source files as the master copy.
- Package each Skill according to Gemini's currently supported import format.
- Upload only the relevant reference files for that Skill.
- Test the Skill in Gemini after import.
- Confirm that guided interaction, reference handling, file generation, and output quality work in practice.
- Record platform limitations; do not assume a repository file is automatically available to Gemini.

## Phase 1 exit criteria
- [ ] Locked design decisions documented.
- [ ] Master blueprint approved.
- [ ] Workspace standards approved.
- [ ] Universal Skill Framework approved.
- [ ] GitHub repository initialized.
- [ ] Folder architecture created.
- [ ] Three document profiles documented.
- [ ] QA templates created.
- [ ] One pilot Skill selected for Phase 2.
- [ ] Gemini import workflow tested with a minimal pilot.

## Recommended pilot
Start Phase 2 with `prota-promes-planner` or `teaching-material-architect`. Choose one as the pilot, not both simultaneously. The pilot must test the complete lifecycle: authoring, references, guided configuration, `PROCEED!`, DOCX output, QA, and release.
