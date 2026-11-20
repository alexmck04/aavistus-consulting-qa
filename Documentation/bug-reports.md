# Aavistus Platform QA -- Bug Reports

## AV-001 -- Workspace creation popup does not scroll

**Area:** Workspace creation
**Category:** Functional / UI
**Severity:** Minor

**Description:** When a facilitator creates a workspace, a popup containing additional creation options is displayed. However, the popup does not respond to scrolling, preventing the facilitator from accessing all available options.

**Reproduction steps:** 1. Log in as a facilitator. 2. Open workspace
creation. 3. Attempt to scroll through the creation-options popup.

**Expected result:** The popup scrolls correctly, allowing the facilitator to view and select all available creation options.
**Actual result:** The popup does not react to scrolling, leaving some
options inaccessible.
**Impact:** Facilitators cannot access the full set of workspace creation tools, limiting the functionality available when creating a workspace.
**Evidence:** The original report describes this issue in section 3.1 and includes a screenshot on page 8 showing the non-responsive creation tool. The screenshot demonstrates that the authentication strategy and part of the project name are obscured.
`aavistus-consulting-qa\images\Aavistus-create-project.png`

## AV-002 -- 2-D selector cannot be properly resized or edited

**Area:** Delphi session / selector configuration
**Category:** Functional
**Severity:** Moderate

**Description:** When a facilitator adds a 2-D selector to a session, it
appears very small and cannot be properly edited in terms of size or
content.

**Reproduction steps:** 1. Log in as a facilitator. 2. Open a workspace
and a session. 3. Add a 2-D selector. 4. Attempt to resize it and edit
its content.

**Expected result:** The selector appears at a usable size and can be
edited.
**Actual result:** The selector appears very small and cannot be
properly edited.
**Impact:** An important session feature is unavailable, limiting the facilitator's ability to collect more precise opinions from participants. This reduces the quality of information available when working towards a consensus.
**Evidence:** The original report describes this issue in section 3.1 and includes a screenshot on page 7 showing the non-functioning 2-D slider.
`aavistus-consulting-qa\images\Aavistus-slider.png`


## AV-003 -- Participant options cannot be accessed when inviting participants

**Area:** Participant management / invitations
**Category:** Functional / UI
**Severity:** Minor

**Description:** When a facilitator attempts to add a participant to a session, the participant-options popup does not allow scrolling. This prevents the facilitator from accessing all available participant options and inviting users.

**Reproduction steps:** 1. Log in as a facilitator. 2. Open a session
within a workspace. 3. Open the add-participant flow. 4. Attempt to
scroll through the participant options.

**Expected result:** The popup scrolls correctly, allowing the facilitator to access all participant options and invite users.
**Actual result:** The popup does not allow the facilitator to access all participant options, preventing invitations from being made through the affected flow.
**Impact:** Facilitators may be unable to invite participants,
disrupting the Delphi process.
**Related observation:** The original report notes that this issue is similar to AV-001, as both involve scrolling within a popup. It suggests a possible wider issue with popup reactivity across Aavistus. However, this is an observation from the assessment and not a confirmed root cause.
**Evidence:** Described in section 3.1 of the original report on page 2. No separate screenshot was included for this issue.

## AV-004 - Repeated logouts and inconsistent email/password authentication

**Area:** Authentication
**Category:** Functional / Authentication
**Severity:** Vital

**Description:** While working on Delphi rounds, the tester experienced repeated unexpected logouts and was temporarily unable to log back in using email and password. Signing in through a Google account remained available as an alternative.

**Indicative workflow:** 1. Log in using email and password. 2. Work on
Delphi rounds. 3. Observe whether the session unexpectedly logs out. 4.
Attempt to sign in again using email and password. 5. Compare with the
Google sign-in option.

**Expected result:** The user remains logged in during normal platform use and can reliably authenticate using email and password.
**Actual result:** Repeated logouts occurred and email/password authentication temporarily failed. Google sign-in remained available as an alternative method of accessing the platform.
**Impact:** Users may be unable to access or use the platform efficiently. In more serious cases, authentication failures could prevent users from accessing Aavistus entirely and interrupt the completion of Delphi rounds.
**Evidence:** Described in section 3.1 of the original report on page 2. No separate screenshot was included for this issue.

## Severity Summary

| Bug ID | Issue | Severity |
|---|---|---|
| AV-001 | Workspace creation popup does not scroll | Minor |
| AV-002 | 2-D selector cannot be properly resized or edited | Moderate |
| AV-003 | Participant options cannot be accessed when inviting participants | Minor |
| AV-004 | Repeated logouts and inconsistent email/password authentication | Vital |
