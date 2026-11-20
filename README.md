# Aavistus Platform – QA Assessment

## Overview

This repository contains QA documentation from an outsourced software testing engagement involving the Aavistus platform.

The project involved assessing the platform's functionality and usability, identifying issues affecting users, and documenting recommendations for improvement. Testing focused on key facilitator and participant workflows, including workspace creation, session configuration, participant management and authentication.

The assessment combined structured test scenarios with exploratory testing to identify functional issues and areas where the user experience could be improved.

## Project Objectives

The main objectives of the engagement were to:

- Evaluate the functionality and usability of the Aavistus platform.
- Identify issues affecting facilitators and participants.
- Document bugs with clear descriptions, reproduction steps and expected and actual behaviour.
- Assess the severity and potential impact of identified issues.
- Recommend improvements to platform functionality and user experience.

## Issues Identified

Four main bugs were documented during the assessment:

| Bug ID | Issue | Severity |
|---|---|---|
| AV-001 | Workspace creation popup does not scroll | Minor |
| AV-002 | 2-D selector cannot be properly resized or edited | Moderate |
| AV-003 | Participant options popup cannot be scrolled | Minor |
| AV-004 | Repeated unexpected logouts and authentication issues | Vital |

The assessment also identified usability concerns involving external help resources and the feedback submission process.

## Testing Approach

The assessment used a combination of:

- **Functional testing:** Reviewing key platform features and user workflows.
- **Exploratory testing:** Exploring the application to identify unexpected behaviour and usability issues.
- **Test scenario design:** Defining scenarios covering important facilitator and participant activities.
- **Bug reporting:** Recording identified issues, reproduction steps, expected and actual behaviour, impact and supporting evidence.
- **Severity assessment:** Classifying issues according to their impact on platform functionality and users.

Robot Framework was among the testing tools used or considered as part of the original project methodology.

### Documentation

- **[Test Scenarios](documentation/test-scenarios.md):** Documents scenarios covering key platform functionality and usability.
- **[Bug Reports](documentation/bug-reports.md):** Provides detailed descriptions of the four identified bugs, including reproduction steps, expected and actual behaviour, impact and supporting evidence.
- **[Severity Assessment](documentation/severity-assessment.md):** Explains the severity classifications assigned to each bug and their recommended fix priority.

### Screenshots

The `images/` folder contains screenshots from the original assessment report, providing visual evidence for selected issues.

## Project Background

This project originated from an outsourced software testing engagement in which our class worked as a group to assess an external client's platform. The engagement provided practical experience in software QA, including functional testing, exploratory testing, bug reporting and usability assessment.

This repository presents the QA documentation as an individual portfolio project, demonstrating experience in test documentation, bug reporting, severity assessment and software quality analysis.

## Notes

This repository focuses on QA testing and documentation rather than the development of the Aavistus application itself. The documented issues reflect findings from the original assessment in April 2025 and should not be interpreted as confirmation that the same issues remain present in the current version of the platform.

**Original report:** *Consulting Report: Platform Assessment and Improvement Plan for Aavistus*  
**Assessment date:** 23 April 2025