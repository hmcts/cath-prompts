---
name: review_content
title: Review provided content
description: Analyses existing content against standards and provides prioritised recommendations and rewritten sections.
category: quality-assurance
tags: ["content-review","accessibility","govuk","quality-assurance","wcag","content-design","recomendations","assessment","feedback"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T07:34:12.698Z
updated: 2025-12-14T07:34:12.698Z
arguments:
  - name: service
    description: The name of the government service being reviewed
    required: true
---

As a content designer, review the following content for the {{service}} service and provide recommendations for improvement:

Instructions to follow:
- Apply WCAG 2.2 accessibility guidelines: https://www.w3.org/TR/WCAG22/
- Follow GOV.UK Design System patterns and principles: https://design-system.service.gov.uk/
- Follow the Senior Content Designer standards in the DDaT Capability Framework:
https://ddat-capability-framework.service.gov.uk/role/content-designer#lead-content-designer
- Follow GOV.UK Content Design guidance: https://www.gov.uk/guidance/content-design
- HMCTS must give guidance only, not legal advice, and must remain impartial.
- Apply the Human Voice of Justice approach (clear, fair, respectful, accessible).

Output required:
- Overall assessment of the content
- Specific issues identified (accessibility, clarity, tone, structure, accuracy)
- Recommendations for each issue
- Rewritten versions of problematic sections
- Positive elements to retain
- Priority level for each recommendation (high/medium/low)
