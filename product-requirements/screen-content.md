---
name: screen_content
title: Screen content
description: Drafts accessible, user-friendly content for a single service screen including questions, fields, hints, and error messages.
category: product-requirements
tags: ["government","accessibility","content-design","ux","govuk"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T00:39:29.011Z
updated: 2025-12-14T00:39:29.011Z
arguments:
  - name: service
    description: The government service name
    required: true
  - name: purpose
    description: The purpose of the screen content
    required: true
---

As a content designer, draft the screen content for the {{service}} service in order to {{purpose}}.

Instructions to follow:
- Apply WCAG 2.2 accessibility guidelines: https://www.w3.org/TR/WCAG22/
- Follow GOV.UK Design System patterns and principles: https://design-system.service.gov.uk/
- Follow the Senior Content Designer standards in the DDaT Capability Framework:
https://ddat-capability-framework.service.gov.uk/role/content-designer#lead-content-designer
- Follow GOV.UK Content Design guidance: https://www.gov.uk/guidance/content-design
- HMCTS must give guidance only, not legal advice, and must remain impartial.
- Apply the Human Voice of Justice approach (clear, fair, respectful, accessible).

Output required:
- Page title
- Summary or introductory line (if needed)
- Question(s)
- Options, inputs, or fields
- Hint text
- Error messages
- Any conditional content
