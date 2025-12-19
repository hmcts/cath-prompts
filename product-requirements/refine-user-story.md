---
name: refine_user_story
title: Refine user story
description: Reviews and improves user stories to ensure they're clear, testable, and appropriately sized.
category: product-requirements
tags: ["user-stories","product-management","requirements","refinement","quality-assurance","success-criteria","gherkin","sizing"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T07:50:28.747Z
updated: 2025-12-14T07:50:28.747Z
arguments:
  - name: ticket_number
    description: The ticket or issue number for tracking
    required: true
  - name: user_story
    description: The original user story text to be refined
    required: true
---

As a Business Analyst, review and refine the following user story for {{ticket_number}} to ensure it meets quality standards: {{user_story}}

Instructions to follow:
- Ensure the story follows the "As a... I want to... so that..." format correctly.
- Check that acceptance criteria are clear, testable, and follow the "Given, When, Then" format.
- Identify any missing information or ambiguities.
- Ensure the story is appropriately sized and not too broad.
- Verify that the business value is clearly articulated.

Output required:
- Refined user story with improved clarity
- Updated acceptance criteria
- List of questions or missing information that needs clarification
- Suggestions for splitting the story if it's too large
- Estimated complexity assessment
