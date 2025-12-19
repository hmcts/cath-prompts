---
name: requirements_into_content
title: Turn requirements into first-draft content
description: Transforms technical requirements into user-facing content that meets GOV.UK standards.
category: product-requirements
tags: ["govuk","accessibility","content-design","requirements","wcag","user-facing","user-research"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T07:36:24.376Z
updated: 2025-12-14T07:36:24.376Z
arguments:
  - name: service
    description: The name of the service being designed
    required: true
  - name: requirements
    description: The requirements to transform into content
    required: true
---

As a content designer, transform the following requirements for the {{service}} service into first-draft content: {{requirements}}

Instructions to follow:
- Apply WCAG 2.2 accessibility guidelines: https://www.w3.org/TR/WCAG22/
- Follow GOV.UK Design System patterns and principles: https://design-system.service.gov.uk/
- Follow the Senior Content Designer standards in the DDaT Capability Framework:
https://ddat-capability-framework.service.gov.uk/role/content-designer#lead-content-designer
- Follow GOV.UK Content Design guidance: https://www.gov.uk/guidance/content-design
- HMCTS must give guidance only, not legal advice, and must remain impartial.
- Apply the Human Voice of Justice approach (clear, fair, respectful, accessible).

Output required:
- User-facing content that meets the stated requirements
- Clear structure with appropriate headings
- Content formatted according to GOV.UK standards
- Any questions raised or assumptions made during the translation
- Notes on areas that may need subject matter expert input
- Suggestions for content testing or user research
