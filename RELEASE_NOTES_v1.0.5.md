# AudioMatchbox v1.0.5 — Development preview

**Date:** 10 November 2026 · **Status:** Private Windows acceptance testing

### Highlights

- Refined one-at-a-time dropdown popup behavior across Scan, Results, Quarantine and Settings.
- Unified results workspace: recording → format → individual file, with manual KEEP / CANDIDATE review.
- Full text on hover, context copy, and double-click column auto-fit.
- Centered, single-instance About dialog; simpler Windows icon consistency.
- Active Quarantine vs History views; `recycled` state for Windows Recycle Bin requests.
- Cross-format settings belong in the Scan workflow, not the Results screen.

### Safeguards

Audio comparison results are advisory. No files are automatically deleted. Moves require manual KEEP decisions, candidate selection and separate approval; files are rechecked before filesystem operations. Recycle Bin functionality still requires full Windows acceptance testing and is not an irreversible-deletion substitute for backups.

### Quality status

43 automated tests passed in the development build. There is no public signed executable and no claim of production certification. Stress testing continues before version 1.1 or general availability.
