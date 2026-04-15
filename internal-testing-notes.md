# Internal Testing Notes - SpeedGuard

Last updated: 2026-04-15

## How We Tested

We ran internal testing with real testers using Google Play internal test distribution.

Testers installed the app from the Play test link and validated core functionality on physical Android devices:

- app install and first launch
- foreground monitoring start/stop flow
- location-based speed updates
- threshold alerts (voice, vibration, optional overlay)
- background monitoring behavior with persistent notification

No critical crashes or blocking issues were observed during this internal validation phase.

## What We Changed Before Production Request

Before requesting production access, we completed Play Console setup, policy declarations, pricing setup, store listing assets, and internal testing validation with real users. We also improved runtime stability for alerting and monitoring behavior and verified successful installation and operation through Google Play test distribution.

## Contact

- Support email: `speedguard@111.md`
- Website: https://speed-guard.github.io/
- Privacy policy: https://speed-guard.github.io/privacy-policy
