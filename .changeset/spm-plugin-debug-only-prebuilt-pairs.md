---
'expo': patch
---

Link debug-only Expo modules under Swift Package Manager only as prebuilt Debug/Release pairs, and fail the sync when a pair is missing, so development code stays out of Release builds. A precompiled module that only debug-only modules use links its empty Release stub in Release builds, when the stub is available.
