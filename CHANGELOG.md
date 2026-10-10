# Changelog

## 1.0.1 - 2026-10-10
### Fixed
- Individual sets can now be saved, so you can alternate between Squat and Deadlift.
  - app.js: blank unsaved trailing sets are skipped on save; opening an exercise resumes today's workout if it has fewer than 4 sets.
  - sw.js: cache name changed from strength-log-v1 to strength-log-v2 so installed apps load the new app.js.

## 1.0.0 - initial version
- First release.
