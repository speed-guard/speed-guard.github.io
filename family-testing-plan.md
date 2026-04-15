# SpeedGuard Family Testing Plan (7 Days)

Last updated: 2026-04-15

This is a lightweight practical testing plan for internal or closed testing with family and friends.

## Goal

Validate that SpeedGuard installs, runs, alerts correctly, and remains stable in normal day-to-day use.

## 7-Day Plan

- **Day 1**: Install from Google Play test link and open the app.
- **Day 2**: Verify Start/Stop monitoring and foreground notification behavior.
- **Day 3**: Validate voice and vibration alerts at a low threshold.
- **Day 4**: Validate overlay alert flow (if enabled) and return to app.
- **Day 5**: Keep monitoring active in background for 10-15 minutes.
- **Day 6**: Switch activity profiles (car / bicycle / on foot) and verify normal behavior.
- **Day 7**: Send final tester feedback (1-2 sentences each).

## What to Collect From Each Tester

- Phone model and Android version
- Works / does not work summary
- One issue noticed (if any)

## Daily Message Template

```text
Please test only today’s step in SpeedGuard.
Reply with: phone model, works/doesn’t work, and anything unusual you noticed.
```

## Minimal Success Criteria

- At least 3-5 real testers installed and opened the app from Play
- Core flow validated: install, start/stop, alerts, background behavior
- At least one round of feedback collected and reviewed

## Useful Links

- Internal testing notes: https://speed-guard.github.io/internal-testing-notes
- Privacy policy: https://speed-guard.github.io/privacy-policy
- Support: https://speed-guard.github.io/support
