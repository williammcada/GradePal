# Migration Baseline — GradePal

**Recorded:** 18 September 2026  
**Repository:** `williammcada/GradePal`  
**Branch:** `main`  
**Source-preservation checkpoint:** `42fb0044b6afbb440c8ada0bb78898e412919142`  
**Record status:** Current source identity. This is not by itself a functional-test, release, or deployment claim.

## Canonical source identity

| Field | Value |
| --- | --- |
| Canonical source path after normalization | `GradePal.html` |
| Git blob SHA | `7f637fdca5f72e2790941c1f8d52e7a30590c273` |
| Prior repository filename | `GradePal_v4.html` |
| Preserved comparison filename | `GradePal_v1.html` |
| Version represented | Current preserved implementation; semantic release version not established |
| Repository source checkpoint | `42fb0044b6afbb440c8ada0bb78898e412919142` |

The checkpoint above identifies the application/planning source immediately before this normalization record was committed. Later documentation-only commits do not change the preserved application bytes.

## Verification status

| Check | Result | Evidence / limitation |
| --- | --- | --- |
| Source exists in the default branch | Passed | Repository paths and Git object identities were read directly on 18 September 2026. |
| Byte-preservation comparison | Passed | Passed — the two differently named files are byte-identical. The `v4` name was not evidence of an upgrade. |
| Functional workflow | Not run | Source preservation does not establish that imports, gameplay, reports, storage or exports work. |
| Hosted/running application | Not run | Not verified; this task changes source identity documentation and filename only. |

## Documentation authority

- [`PROJECT-BRIEF.md`](PROJECT-BRIEF.md) records purpose, scope, must-retain behavior and verification requirements.
- [`change-specs/INDEX.md`](change-specs/INDEX.md) identifies approved or directional change records.
- [`MIGRATION-NOTE.md`](MIGRATION-NOTE.md) is retained as historical migration context but its pre-upload source-status language is superseded by this baseline.
- This file controls current source identity when an older brief or note says the source was unknown or “TO ESTABLISH.”

## Next gate

Use neutral `GradePal.html` as the source baseline. Assign a semantic version only after an actual change, verification checkpoint and release record.

Do not label a future commit a verified release until the exact candidate has passed the project brief’s required verification and that evidence is preserved.
