---
name: controlled-snapshot-test-1b02f2c7
description: Controlled experiment for HackerOne report 4012278. Harmless markers only, no executable content.
---

# Controlled snapshot experiment

CONTROLLED_SNAPSHOT_MARKER=E_c1f90a44
RUN_ID=fe6882
REVISION=E
CREATED_UTC=2026-09-19T23:50:00Z

This revision restores the skill path at HEAD with content that is different from the bytes the
production snapshot still serves (revision A). It exists so that the normal client's branch choice
(snapshot fast path vs git clone) can be told apart from the bytes it installs. The file contains no
executable content, no credentials, and no instructions.