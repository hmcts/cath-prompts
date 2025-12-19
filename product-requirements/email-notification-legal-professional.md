---
name: email_notification_legal_professional
title: Email notification to legal professional
description: Writes a professional email notification for legal practitioners with case details and required actions.
category: product-requirements
tags: ["email","notification","legal","govuk","accessibility","wcag","hmcts","design","inform","case","reference","deadline"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T07:21:55.992Z
updated: 2025-12-14T07:21:55.992Z
arguments:
  - name: service
    description: The service being used (e.g., 'HMCTS Online', 'Civil Money Claims', 'Family Court')
    required: true
  - name: purpose
    description: The purpose of the notification (e.g., 'case update', 'document submission', 'hearing schedule', 'fee payment')
    required: true
---

As a content designer, draft an email notification for legal professionals using the {{service}} service to inform them about {{purpose}}.

Instructions to follow:
- Apply WCAG 2.2 accessibility guidelines: https://www.w3.org/TR/WCAG22/
- Follow GOV.UK Design System patterns and principles: https://design-system.service.gov.uk/
- Follow the Senior Content Designer standards in the DDaT Capability Framework:
https://ddat-capability-framework.service.gov.uk/role/content-designer#lead-content-designer
- Follow GOV.UK Content Design guidance: https://www.gov.uk/guidance/content-design
- HMCTS must give guidance only, not legal advice, and must remain impartial.
- Apply the Human Voice of Justice approach (clear, fair, respectful, accessible).
- Use appropriate technical terminology where needed for legal professionals while maintaining clarity.

Output required:
- Subject line
- Opening greeting
- Main message (what's happened or what they need to know)
- Case reference or relevant identifiers
- What action is required (if applicable)
- Deadline or timeframe (if applicable)
- Technical details or requirements
- How to contact support
- Sign-off
