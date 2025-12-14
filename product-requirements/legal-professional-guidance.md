---
name: legal_professional_guidance
title: Legal-professional guidance
description: Generate guidance content for legal professionals using a specific service, following GOV.UK design principles, WCAG accessibility guidelines, and maintaining impartiality while using appropriate legal terminology.
category: product-requirements
tags: ["legal","guidance","govuk","accessibility","content-design"]
difficulty: intermediate
author: system
version: 1.0
created: 2025-12-14T00:47:07.063Z
updated: 2025-12-14T00:47:07.063Z
arguments:
  - name: service
    description: The specific service that legal professionals are using
    required: true
  - name: purpose
    description: The purpose or goal that the guidance helps legal professionals achieve
    required: true
---

As a content designer, draft guidance content for legal professionals using the {{service}} service to help them {{purpose}}.

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
- Page title
- Summary (what this guidance helps with)
- Main body content
- Subheadings (if needed)
- Procedural steps or requirements
- Technical details or specifications
- Examples or case scenarios (if helpful)
- Links to relevant legislation, practice directions, or related guidance
- Contact information for technical support