---
"e2e": patch
---

Telemetry no longer sends a project id outside git or in a shallow clone, and a coding agent that sets `CI` outside a CI vendor counts as the machine it runs on. EAS Build, Bitrise, Codemagic, and Xcode Cloud are recognized as CI vendors.
