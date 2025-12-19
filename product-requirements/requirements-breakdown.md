---
name: requirements_breakdown
title: Requirements breakdown
description: Decomposes high-level requirements into a sequenced set of implementable user stories with dependencies.
category: product-requirements
tags: ["requirements","user-stories","product-management","agile","backlog","business-analyst","success-criteria","dependencies"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T07:52:31.414Z
updated: 2025-12-14T07:52:31.414Z
arguments:
  - name: requirement
    description: The high-level requirement to break down into user stories
    required: true
---

As a Business Analyst, break down the following high-level requirement into detailed, implementable user stories:
High-Level Requirement: {{requirement}}

Instructions to follow:
- Decompose the requirement into appropriately sized user stories.
- Ensure each story is independently valuable and deliverable.
- Identify dependencies between stories.
- Sequence stories in a logical implementation order.
- Consider technical constraints and architecture.

Output required:
1. List of user stories, each containing:
- Story title
- User story format (As a... I want to... so that...)
- Brief description
- Initial acceptance criteria outline
- Story points estimate (if applicable)
- Dependencies on other stories
2. Recommended sprint/release groupings
3. Technical dependencies or prerequisites
4. Risks or assumptions for each story
