---
name: review_content
title: Review provided content
description: Review and provide recommendations for improving content for government services, following WCAG accessibility guidelines, GOV.UK Design System patterns, and HMCTS impartiality requirements. Provides structured feedback with priority levels and rewritten examples.
category: quality assurance
tags: ["review","content","quality","accessibility","govuk","wcag","hmcts","feedback"]
difficulty: intermediate
author: System
version: 1.0
created: 2025-12-14T07:24:24.212Z
updated: 2025-12-14T07:24:24.212Z
arguments:
  - name: service
    description: The government service the content is for (e.g., 'HMCTS Online', 'Civil Money Claims', 'Family Court', 'Universal Credit')
    required: true
  - name: content
    description: The content to review and provide recommendations for
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