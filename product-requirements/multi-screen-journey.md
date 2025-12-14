---
name: multi_screen_journey
title: Multi-screen Journey
description: Draft a sequence of screens for government services following GOV.UK design standards, WCAG accessibility guidelines, and HMCTS impartiality requirements for multi-screen journeys.
category: product-requirements
tags: ["government","accessibility","content-design","ux","govuk","journey-mapping","multi-screen"]
difficulty: intermediate
author: System
version: 1.0
created: 2025-12-14T00:42:03.054Z
updated: 2025-12-14T00:42:03.054Z
arguments:
  - name: service
    description: The government service being designed
    required: true
  - name: purpose
    description: The purpose or goal of the service journey
    required: true
---

As a content designer, draft a sequence of screens for the {{service}} service in order to {{purpose}}.
Describe each screen separately.

Instructions to follow:
- Apply WCAG 2.2 accessibility guidelines: https://www.w3.org/TR/WCAG22/
- Follow GOV.UK Design System patterns and principles: https://design-system.service.gov.uk/
- Follow the Senior Content Designer standards in the DDaT Capability Framework:
https://ddat-capability-framework.service.gov.uk/role/content-designer#lead-content-designer
- Follow GOV.UK Content Design guidance: https://www.gov.uk/guidance/content-design
- HMCTS must give guidance only, not legal advice, and must remain impartial.
- Apply the Human Voice of Justice approach (clear, fair, respectful, accessible).

Output required for each screen:
- Page title
- Summary or introductory line (if needed)
- Question(s)
- Options, inputs, or fields
- Hint text
- Error messages
- Any conditional content
- Notes on where each screen fits in the journey (previous/next step)