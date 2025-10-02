---
title: "Automating QA Workflows"
date: 2024-03-02
draft: false
description: "Lessons from introducing lightweight automation inside a gas infrastructure company."
author: "Alexander Büchler"
tags:
  - Automation
  - Process Design
  - Excel VBA
image: "https://images.unsplash.com/photo-1520607162513-77705c0f0d4a?auto=format&fit=crop&w=1200&q=80"
toc: true
---

During my time at GASCADE I was confronted with reams of hazardous substance documentation that had to be updated every time regulations shifted. The team did heroic manual work, but the process took days and inevitably introduced errors. Rather than mandate a new tool, I focused on augmenting the existing Excel-based workflow.

## Listening first

Job shadowing revealed dozens of tiny frictions: copy-pasting chemical IDs from PDF tables, forgetting to update reference sheets, and spending hours compiling reports for audits. I collected each pain point and grouped them into automation candidates.

## Prototyping in the tools people already use

I built the first helper in plain VBA. It scraped regulatory updates, highlighted changes, and produced a diff report directly inside the workbook. Because the script mirrored the team's manual checklist, trust came quickly and adoption was painless.

### The ripple effects

Once colleagues saw the time savings, they requested additional automations: automatic email summaries, validation prompts, and templated audit exports. Over six months the average update cycle dropped from three days to less than one.

The experience taught me that automation is about empathy as much as code. By respecting existing expertise and workflows, we created space for the team to focus on higher-value work.
