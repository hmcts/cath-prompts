---
name: email_notification_citizen
title: Email notification to Citizen
description: Drafts a clear, accessible email notification for citizens about important service updates or actions.
category: product-requirements
tags: ["email","notification","citizen","government","accessibility","govuk","WCAG","guidance"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T00:49:06.967Z
updated: 2025-12-14T00:49:06.967Z
arguments:
  - name: service
    description: The government service being used (e.g., 'HMCTS online services', 'DVLA vehicle tax', 'HMRC self-assessment')
    required: true
  - name: purpose
    description: The purpose of the notification (e.g., 'upcoming court hearing', 'tax return deadline', 'benefit claim update')
    required: true
---

As a content designer, draft an email notification for citizens using the {{service}} service to inform them about {{purpose}}.

Instructions to follow:
- Apply WCAG 2.2 accessibility guidelines: https://www.w3.org/TR/WCAG22/
- Follow GOV.UK Design System patterns and principles: https://design-system.service.gov.uk/
- Follow the Senior Content Designer standards in the DDaT Capability Framework:
https://ddat-capability-framework.service.gov.uk/role/content-designer#lead-content-designer
- Follow GOV.UK Content Design guidance: https://www.gov.uk/guidance/content-design
- HMCTS must give guidance only, not legal advice, and must remain impartial.
- Apply the Human Voice of Justice approach (clear, fair, respectful, accessible).

Output required:
- Subject line
- Opening greeting
- Main message (what's happened or what they need to know)
- What they need to do next (if applicable)
- Deadline or timeframe (if applicable)
- How to get help or where to find more information
- Sign-off
