# Aavistus Platform QA – Test Scenarios

## 1. Overview

This document outlines the test scenarios identified during the assessment of the Aavistus platform.

The scenarios cover key facilitator and participant workflows, including workspace creation, session configuration, participant invitations, authentication and access to support resources.

They are based on the original consulting report and are intended to demonstrate the areas considered during testing.

## 2. Test Scenarios

### TS-001 – Create Workspace

**Feature:** Workspace Creation  
**Objective:** Verify that a facilitator can access all available options when creating a workspace.

**Preconditions:**
- The facilitator is logged into the Aavistus platform.

**Test Steps:**
1. Navigate to the workspace creation area.
2. Open the workspace creation popup.
3. Attempt to scroll through the available options.
4. Check whether all creation options can be accessed.

**Expected Result:**
The workspace creation popup should scroll correctly, allowing the facilitator to view and access all available options.

**Related Bug:** AV-001 – Workspace creation popup does not scroll.

---

### TS-002 – Configure 2-D Selector

**Feature:** Session Configuration  
**Objective:** Verify that a facilitator can use and configure the 2-D selector.

**Preconditions:**
- The facilitator is logged into the platform.
- A project or session is available for configuration.

**Test Steps:**
1. Navigate to the relevant session configuration area.
2. Locate or add the 2-D selector.
3. Attempt to edit or resize the selector.
4. Check whether its size and content can be adjusted.

**Expected Result:**
The 2-D selector should be displayed at a usable size and allow the facilitator to edit or resize it as required.

**Related Bug:** AV-002 – 2-D selector cannot be properly resized or edited.

---

### TS-003 – Access Participant Invitation Options

**Feature:** Participant Management  
**Objective:** Verify that a facilitator can access all available options when inviting participants.

**Preconditions:**
- The facilitator is logged into the platform.
- A project or workspace is available.

**Test Steps:**
1. Navigate to the participant management area.
2. Open the participant invitation options.
3. Attempt to scroll through the popup.
4. Check whether all available options can be accessed.

**Expected Result:**
The participant options popup should scroll correctly, allowing the facilitator to access all available invitation options.

**Related Bug:** AV-003 – Participant options popup cannot be scrolled.

---

### TS-004 – Log In Using Email and Password

**Feature:** Authentication  
**Objective:** Verify that users can successfully log in using their email address and password.

**Preconditions:**
- The user has an existing Aavistus account.
- The user has valid login credentials.

**Test Steps:**
1. Navigate to the Aavistus login page.
2. Enter a registered email address.
3. Enter the corresponding password.
4. Submit the login form.
5. Check whether the user can access the platform.

**Expected Result:**
The user should be able to log in successfully using valid email and password credentials.

**Related Bug:** AV-004 – Repeated logouts and inconsistent email/password authentication.

---

### TS-005 – Maintain Login Session During Delphi Rounds

**Feature:** Authentication / Session Management  
**Objective:** Verify that a user's login session remains active while working through Delphi rounds.

**Preconditions:**
- The user is logged into the Aavistus platform.
- The user has access to an active Delphi project or round.

**Test Steps:**
1. Log into the platform.
2. Navigate to an active Delphi project.
3. Begin working through the available round activities.
4. Continue navigating and interacting with the platform.
5. Check whether the user remains logged in throughout the process.

**Expected Result:**
The user's session should remain active while working through Delphi rounds, without unexpected logouts or interruptions.

**Related Bug:** AV-004 – Repeated logouts and inconsistent email/password authentication.

---

### TS-006 – Access Help and Support Resources

**Feature:** Help and Support  
**Objective:** Verify that users can access the platform's help and support resources.

**Preconditions:**
- The user can access the Aavistus platform.

**Test Steps:**
1. Navigate to the Help and Support section.
2. Open the available help resources.
3. Check whether the resources are accessible.
4. Review the available information for frequently asked questions and troubleshooting guidance.

**Expected Result:**
Users should be able to access useful help resources and find relevant answers to common questions or problems.

**Observation:**
The original assessment found that the Help and Support section redirected users to an external Notion page called the Aavistus Wiki. Although useful resources were available, the FAQ and troubleshooting pages had not been implemented.

---

### TS-007 – Access Feedback and Suggestions Form

**Feature:** User Feedback  
**Objective:** Verify that users can access the feedback and suggestions form.

**Preconditions:**
- The user can access the Aavistus platform.

**Test Steps:**
1. Navigate to the feedback and suggestions section.
2. Open the available feedback form.
3. Check whether the form is accessible.
4. Review the questions and consider whether they are relevant to the user's role.

**Expected Result:**
Users should be able to access a feedback form that allows them to submit suggestions and provide feedback about the platform.

**Observation:**
The original assessment found that the feedback section redirected users to an external Google Docs survey. The survey was lengthy and used the same questions for all user roles, rather than providing shorter, role-specific surveys.

## 3. Summary

| Test ID | Test Scenario | Related Bug |
|---|---|---|
| TS-001 | Create Workspace | AV-001 |
| TS-002 | Configure 2-D Selector | AV-002 |
| TS-003 | Access Participant Invitation Options | AV-003 |
| TS-004 | Log In Using Email and Password | AV-004 |
| TS-005 | Maintain Login Session During Delphi Rounds | AV-004 |
| TS-006 | Access Help and Support Resources | UX Observation |
| TS-007 | Access Feedback and Suggestions Form | UX Observation |