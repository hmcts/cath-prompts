---
name: spec_from_user_story
title: Technical specification from user story
description: Converts a Jira user story into a comprehensive technical specification document for developers.
category: product-requirements
tags: ["technical-spec","user-story","jira","documentation","requirements","user-story","user-journey-flow","wireframe","accessibility","navigation"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T07:47:44.571Z
updated: 2025-12-14T07:47:44.571Z
arguments:
  - name: ticket_number
    description: The Jira ticket number (e.g., PROJ-123)
    required: true
  - name: user_story
    description: The user story text from Jira
    required: true
---

As a Business Analyst, write a technical specifications document for the following user story from ticket {{ticket_number}}:
{{user_story}}

Instructions to follow:
- Use technical language that is interpretable by both BAs and developers.
- Do not fill in missing details from the user story - ask for clarification if information is incomplete.
- Maintain a professional tone throughout.

Output required as markdown document titled "{{ticket_number}}: technical specification":
1. User Story
- As a... I want to... so that...
- Background
- Acceptance criteria (given, when, then format)
2. User Journey Flow (if required)
3. Low Fidelity Wireframe
4. Page Specifications (repeated per page)
- Content
- Validation
- Error messages
5. Navigation
6. Accessibility
7. Test Scenarios
8. Assumptions/Open Questions
