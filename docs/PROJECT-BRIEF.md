# Project Brief — GradePal

**Brief status:** Migration baseline / requires source verification where noted  
**Brief version:** 0.1  
**Last updated:** 18 September 2026  
**Owner:** William McAda  
**Product credit:** A WILLIAM MCADA PRODUCT  
**Handbook repository:** `williammcada/mcada-project-handbook`  
**Handbook baseline:** `6557a45aaa6d29d7d1abde808e6d0ac248b08820 (AI-START-HERE.md); UNIVERSAL-RULES.md @ aed6fe311aa2e88983f862a30a2d8f05d2ffc04d`  
**Repository:** `williammcada/GradePal`  
**Canonical source status:** TO ESTABLISH. Do not infer a current production version or working integrations from the ecosystem vision.  
**Current project state:** Planned/active product concept with learner-model and reporting role; exact implementation status must be verified from source before development.

## 1. Purpose and audience

GradePal is the intended student-by-standard learner model: persistent mastery/evidence by student, individual dashboards, and parent-facing reporting.

**Primary audience / operator:** Teachers, students, and parents using learner-level mastery/evidence information.

## 2. Standards selection

**Universal baseline:** U-01 through U-08 where applicable.

**Conditional modules:** S-02 Curriculum/Assessment/Evidence; S-04 Distribution/Deployment as applicable

Apply only the selected modules and project-local requirements. Do not import restrictions from unrelated projects.

## 3. Project-specific requirements

- Define exactly what counts as evidence, mastery, score, difficulty, and recency before interpreting data.
- Keep source evidence traceable to its assessment/activity origin.
- Do not conflate gameplay rewards with academic mastery.
- Parent reports must be understandable and grounded in actual recorded evidence.
- Any future student identity, retention, privacy, or synchronization behavior must be explicitly specified rather than inferred.

## 4. Preserve from the current accepted project

- Student-by-standard mastery concept.
- Individual dashboard/reporting role.
- Parent-reporting role.
- Separation from DataDiver's school/institutional analytics role.

## 5. Relationship to other projects

- Intended to receive evidence from assessment/activity systems in the future.
- MathQuest may eventually use GradePal for differentiation, but that integration does not yet exist unless separately implemented.
- DataDiver remains institutional analytics rather than the individual learner model.

A conceptual relationship is not proof of an implemented integration. Do not invent a shared API, data schema, identity layer, or deployment dependency without an explicit integration task.

## 6. Source and version discipline

The exact current source artifact or repository commit must be identified before a substantive build. If the field above says the source is not yet established, first locate the latest known-good local file/ZIP or existing repository state and record its exact identity here.

For substantial revisions use:

**DESIGN → CHANGE SPEC → IMPLEMENT → CHECKPOINT → VERIFY → VERIFIED CHECKPOINT → RELEASE → DEPLOY (when applicable)**

A packaging/export/deployment failure must not force reconstruction of an already verified build.

## 7. Definition of done

| # | Requirement / check | Result | Evidence / limitation |
| ---: | --- | --- | --- |
| 1 | Evidence ingestion preserves source and standard identity. | Not run | |
| 2 | Mastery calculations match the documented model. | Not run | |
| 3 | Student/parent reports match underlying evidence. | Not run | |
| 4 | Any synchronization/import/export path is tested end to end. | Not run | |
| 5 | Privacy/retention behavior is documented and verified if personal learner data is stored. | Not run | |

Allowed results: **Passed / Failed / Not run / Not applicable**. A "Passed" result requires an actual check against the identified candidate.

## 8. Known issues and migration notes

Treat this migration pack as documentation scaffolding until the latest GradePal source is identified.

## 9. Handoff files

A substantive AI implementation task should retrieve or receive:

1. `AI-START-HERE.md`;
2. `UNIVERSAL-RULES.md`;
3. the relevant sections of `CONDITIONAL-STANDARDS.md`;
4. this project brief;
5. the exact current source artifact/commit;
6. the approved version-specific change specification;
7. applicable assets and deployment configuration.

Do not reconstruct the current implementation from a historical chat summary when the actual source should be available.

## 10. Ownership

**William McAda**  
**A WILLIAM MCADA PRODUCT**
