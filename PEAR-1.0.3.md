# PEAR 1.0.3

- Fixes the background health monitor crash reported as `CODESIGNING Code 4: Launch Constraint Violation`.
- Automatically re-registers the LaunchAgent after PEAR updates so launchd uses the new signed executable hash.
- Retains the fresh-install enrollment and protected-attachment fixes from PEAR 1.0.2.
