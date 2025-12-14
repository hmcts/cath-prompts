---
name: ac_generator
title: Acceptance criteria generator
description: Creates comprehensive acceptance criteria in Given/When/Then format covering all scenarios and edge cases.
category: product-requirements
tags: ["acceptance-criteria","product-requirements","testing","ba","gherkin"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T07:55:53.736Z
updated: 2025-12-14T07:55:53.736Z
arguments:
  - name: user_story
    description: The user story for which to generate acceptance criteria
    required: true
---

As a BA, generate comprehensive acceptance criteria for the following user story:
User Story: {{user_story}}

Instructions to follow:
- Write acceptance criteria in "Given, When, Then" format.
- Cover happy path, alternative paths, and error scenarios.
- Ensure criteria are specific, measurable, and testable.
- Include accessibility requirements where relevant.
- Consider edge cases and boundary conditions.

Output required:
- Complete set of acceptance criteria organised by scenario type:
- Happy path scenarios
- Alternative path scenarios
- Error handling scenarios
- Edge cases
- Accessibility criteria
- Performance criteria (if applicable)
- Notes on any assumptions made
- Questions requiring clarification from stakeholders