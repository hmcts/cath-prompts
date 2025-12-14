---
name: vision_statement
title: Product vision statement
description: Crafts a compelling product vision that articulates the problem, solution, and value proposition.
category: delivery
tags: ["product-management","vision","strategy","planning"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T08:11:47.162Z
updated: 2025-12-14T08:11:47.162Z
arguments:
  - name: product/service_name
    description: The name of the product or service
    required: true
  - name: target_users
    description: Description of the target users/customers
    required: true
  - name: problem_space
    description: The problem space the product operates in
    required: true
  - name: current_state
    description: Current state of the market/product
    required: true
  - name: competitive_landscape
    description: Overview of the competitive landscape
    required: true
  - name: strategic_goals
    description: Strategic goals of the organization
    required: true
---

As a Product Manager, craft a compelling product vision statement for {{product/service_name}}.

Context:
{{target_users}}, {{problem_space}}, {{current_state}}, {{competitive_landscape}}, {{strategic_goals}}

Instructions to follow:
- Make the vision aspirational yet achievable.
- Focus on the problem being solved and the value created, not features.
- Ensure the vision is memorable and can inspire the team.
- Ground the vision in user needs and business objectives.
- Make it clear who the product is for and who it's not for.
- Keep the core vision statement concise (1-2 sentences), then expand with supporting context.

Output required:
1. Core Vision Statement (1-2 sentences that capture the essence)
2. Expanded Vision:
- Target users/customers (who is this for?)
- Problem statement (what problem are we solving?)
- Solution approach (how are we uniquely solving it?)
- Value proposition (why should users care?)
- Success looks like (what does the future state look like?)
3. Vision Principles (3-5 guiding principles that inform product decisions)
4. What we are / What we are not:
- We are: [characteristics of the product]
- We are not: [anti-patterns or explicit boundaries]
5. Timeframe and scope (what's the horizon for this vision?)
6. Alignment to organisational strategy (how this supports broader goals)
7. Key metrics that would indicate vision success