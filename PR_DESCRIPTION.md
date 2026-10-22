## Summary

- Add focused tests for BatchFundingForm review totals, fee estimates, skipped rows, and returning to edit.
- Cover batch parser edge cases for mixed line endings, original line numbers, and amount precision.
- Test TelemetryConsentPrompt visibility and consent actions.
- Test ErrorBoundary recovery, custom fallbacks, error reporting, and in-flight transaction links.

## Validation

- Focused issue tests: 41 passed.
- Lint: passed with existing warnings.
- Full test suite, typecheck, and production build are blocked by unrelated pre-existing failures.
- E2E command completes, but all 21 specs are skipped by the current setup.

Closes #745
Closes #746
Closes #747
Closes #748
