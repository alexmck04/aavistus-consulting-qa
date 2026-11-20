# Aavistus Platform QA – Severity Assessment

## 1. Overview

This document outlines the severity classifications assigned to the four bugs identified during the Aavistus platform assessment.

The classifications are based on the original consulting report, which assessed the impact of each issue on platform functionality and the user journey.

## 2. Severity Classification

| Severity | Description |
|---|---|
| Vital | Issues that can prevent users from accessing or using the platform efficiently, potentially disrupting the entire Delphi process. |
| Moderate | Issues that disable or significantly limit an important platform feature without preventing general platform access. |
| Minor | Issues that restrict certain functionality or affect the user experience but do not prevent general use of the platform. |

## 3. Bug Severity Assessment

| Bug ID | Issue | Severity | Justification |
|---|---|---|---|
| AV-001 | Workspace creation popup does not scroll | Minor | Restricts access to some workspace creation options but does not prevent general platform use. |
| AV-002 | 2-D selector cannot be properly resized or edited | Moderate | Removes an important session feature that would allow facilitators to collect more precise participant opinions. |
| AV-003 | Participant options cannot be accessed when inviting participants | Minor | Restricts access to participant invitation options, affecting the facilitator's workflow. |
| AV-004 | Repeated logouts and inconsistent email/password authentication | Vital | Authentication problems may prevent users from accessing the platform and completing their Delphi rounds. |

## 4. Recommended Fix Priority

Based on the original assessment, the recommended order for addressing these issues is:

1. **AV-004 – Vital:** Prioritise authentication reliability and unexpected logouts.
2. **AV-002 – Moderate:** Restore the functionality of the 2-D selector.
3. **AV-001 – Minor:** Resolve scrolling issues in the workspace creation popup.
4. **AV-003 – Minor:** Resolve scrolling issues in the participant invitation popup.

Both minor issues should still be addressed, as they restrict important facilitator workflows.