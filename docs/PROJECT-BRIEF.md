# Project Brief — GradePal

**Brief version:** 0.3 — source-baseline normalization  
**Owner:** William McAda · **Credit:** A WILLIAM MCADA PRODUCT  
**Status:** Canonical source identity reconciled; release, functional and deployment verification remain separately stated.  
**Repository:** `williammcada/GradePal`, branch `main`.  
**Current running version:** Not independently verified. Current preserved implementation exists; semantic release version is not established.  
**Source/baseline:** Canonical preserved source: `GradePal.html`, Git blob `7f637fdca5f72e2790941c1f8d52e7a30590c273`. The same bytes were previously stored as `GradePal_v4.html` and match the preserved `GradePal_v1.html`; therefore no semantic release version is established by either filename. Pre-normalization source checkpoint: `42fb0044b6afbb440c8ada0bb78898e412919142`.  
**Next work:** Use neutral `GradePal.html` as the source baseline. Assign a semantic version only after an actual change, verification checkpoint and release record.  

## 1. Purpose, audience and detailed scope

- Standalone offline teacher assessment-intelligence app focused on individual learners and classes. Imports GradeCam Student By Standard data and XLSX/CSV standards rather than collecting live student gameplay.
- Retain class and individual dashboards, class/student management, mastery grouping by domain/outcome/lesson, weak-domain/outcome priorities, instructional groups and parent-ready reports.
- Preserve ascending under-80 results table with selectable count and copyable output. Clarify what percentage/mastery values mean from imported evidence; do not equate them with game rewards.
- Local IndexedDB (recorded GradePalLocalV1) with localStorage fallback; retain clear/reset/delete controls and local-only data boundary. No silent cloud upload or account dependency.
- Reports must be usable for parents and teaching decisions, with print/copy functions and source traceability. No XLSX export is established by the retrieved record; do not promise one.
- Preserve landing page, embedded mascot, industrial palette and William McAda branding.
- Future MathQuest differentiation link is an ecosystem intention, not implemented synchronization. Student identity/privacy and data contract require separate approval.

## 2. This task and boundaries

This normalization establishes the exact repository source path, Git object identity and source-preservation checkpoint; creates the linked migration baseline; and retires stale pre-upload source-status wording. It does not change application behavior, approve new features, rerun product tests or convert source preservation into a release claim.

## 3. Standards and adoption

[Canonical handbook](https://github.com/williammcada/mcada-project-handbook). File blob revisions consulted: AI-START-HERE.md 6557a45aaa6d29d7d1abde808e6d0ac248b08820; UNIVERSAL-RULES.md aed6fe311aa2e88983f862a30a2d8f05d2ffc04d; CONDITIONAL-STANDARDS.md dad2d3a05ca0f18260196ea51ac6351bffffdc1c; PROJECT-TEMPLATE.md 574f4c6fcf19ecc2f9e27582fd856fb08123e8da. These are file blobs, not repository commit SHAs.

Relevant rules: U-01 identity, U-02 help, U-03 input validation, U-04 unambiguous math/text where applicable, U-05 reader/device, U-06 preservation, U-07 verification, U-08 local scope. Conditional selection: S-02, S-04.
Baseline adoption: selected for this documentation task within existing user instructions. Handbook still labels shared scope/modules seeded/draft; no new global rule ratification is inferred. Project-specific approved decisions control their own scope.

## 4. Must-retain behavior

The detailed scope above is the feature-preservation inventory. Preserve existing settings, data, accepted content, assets, exports and compatibility confirmed in source. Distinguish implemented behavior, accepted pending changes and historical requests during intake. A missing entry in this brief is not authorization to remove working behavior. Preserve valid user work during migrations and failures.

## 5. Source, release and deployment discipline

Canonical preserved source: `GradePal.html`, Git blob `7f637fdca5f72e2790941c1f8d52e7a30590c273`. The same bytes were previously stored as `GradePal_v4.html` and match the preserved `GradePal_v1.html`; therefore no semantic release version is established by either filename. Pre-normalization source checkpoint: `42fb0044b6afbb440c8ada0bb78898e412919142`.

See [`MIGRATION-BASELINE.md`](MIGRATION-BASELINE.md) for the authoritative source manifest and the checks actually performed.

DESIGN → CHANGE SPEC → IMPLEMENT → CHECKPOINT → VERIFY → VERIFIED CHECKPOINT → RELEASE → DEPLOY.

Use “implementation checkpoint” or “release candidate” before verification. Preserve candidate bytes and logs before packaging; recover that checkpoint after a ZIP/upload failure. Do not rebuild a verified implementation to fix delivery. Repository upload and website deployment are different operations.

## 6. Known issues, conflicts and open evidence

Earlier testing with 331 standards and 22 mock students was reported; not repeated here. The migration pack incorrectly reduced this existing app to a concept. Record missing-source status without discarding known functionality.

| Conflict or risk | Required handling |
| --- | --- |
| Historical claim versus current source | Inspect exact source; keep historical claim labeled until verified. |
| Proposed next scope versus working baseline | Use the approved version-specific specification; do not silently promote proposals. |
| Other project rules | Do not import AAC quotas, other-game retry counts, or a shared backend without explicit scope. |
| Handbook proposals | No additional exception or proposal is adopted by this brief. |

## 7. Verification contract

Import synthetic classes, compare class/student aggregates, sort/copy under-80 table, inspect parent reports, reload storage and exercise deletion; confirm no data upload.

| Evidence required | Result in this task |
| --- | --- |
| Exact source candidate/commit identified and preserved | Passed — canonical path and source checkpoint recorded in `docs/MIGRATION-BASELINE.md`; no functional verification inferred |
| Project-specific checks above, with inputs and expected/actual results | Not run |
| Save/import/export and malformed-input regression | Not run |
| Intended devices and real deployment path, where applicable | Not run |
| Version, release notes and delivered bytes agree | Not run |

The next build report must name the candidate, environment and test results; historical reports of passing tests do not transfer to a changed candidate.

## 8. Handoff and provenance

Current source identity is recorded in [`MIGRATION-BASELINE.md`](MIGRATION-BASELINE.md). That manifest supersedes earlier unknown-source or pre-upload statements while preserving the original migration note as history.

Required project records: committed neutral `GradePal.html`; this migration baseline’s prior-filename/blob equivalence record; synthetic GradeCam and standards fixtures; previous behavior and release notes without an unsupported semantic-version claim.

Provenance: previous migration brief and project-history audit in this conversation; directly read dossier/proposal where explicitly stated above. Records not explicitly marked read here are retrieval targets, not claims of fresh inspection. No current app code was tested for this brief.

Before substantive implementation retrieve these records, the current source, approved change spec and applicable handbook. If an indispensable spec is inaccessible, report the gap instead of filling it with invented details. Do not delete unique historical chats/assets until their contents are independently preserved.

## 9. Ecosystem boundary

Shared principles do not establish shared code, accounts or interfaces. MathQuest is engagement, TestForge assessment design, GradePal learner-level evidence, and DataDiver institutional analytics. Integration remains separately specified unless confirmed in source. Other projects remain independent unless their brief explicitly says otherwise.
