---
layout: post
title: "🧠 SMART Ticket Creation Framework"
categories: project-management
---

## Purpose

Ticket template adapts the SMART goals framework to make objectives easier to achieve. The SMART acronym represents these key characteristics:

* ✅ **Specific** - Clearly define what you want to accomplish (Output)
* ✅ **Measurable** - Establish concrete criteria for tracking progress
* ✅ **Achievable** - Set realistic and attainable targets
* ✅ **Relevant** - Ensure alignment with broader objectives (Outcome)
* ✅ **Time-bound** - Specify a deadline for completion

## Ticket Template

📝**Title**: (What needs to be done?)  
🎯**Goal**: (What do you want to achieve?)  
🔍**Scope**: (What is included in this work?)  
  ✓**Acceptance Criteria**: (List in bullet points or Given-When-Then format)  
⏱️**Estimate**: (Story points required)

## SMART Application

This template implements the SMART goals framework:
* **Title** defines what needs to be done (Specific)
* **Goal** defines the purpose of the task (Relevant)
* **Scope** makes the task achievable by limiting the work needed for completion (Achievable)
* **Acceptance Criteria** ensures the work is measurable (Measurable)
* **Estimate** provides time boundaries by limiting the effort allowed for completion (Time-bound)

## Validation Prompt

> Your goal is to verify that ticket follows the guidelines. Please review the ticket-description posted below and verify if it properly follows the required template structure by answering the following questions:
>
> 1. **TITLE**:
>     * Is there a clear title that describes what needs to be done?
>     * Is the title specific and action-oriented?
> 2. **GOAL**:
>     * Is there a goal section that explains what the ticket aims to achieve?
>     * Does it clearly state the purpose of this work?
> 3. **SCOPE**:
>     * Is there a defined scope section that outlines what is included in this work?
>     * Does it set clear boundaries for what should be accomplished?
> 4. **ACCEPTANCE CRITERIA**:
>     * Are acceptance criteria listed in either bullet points or Given-When-Then format?
>     * Do they clearly define when the work can be considered complete?
> 5. **ESTIMATE**:
>     * Is there an estimate provided in story points?
>     * Does the estimate seem appropriate for the described work?
>
> **Overall Template Compliance**:
> * Which sections of the template are properly completed?
> * Which sections are missing or need improvement?
>
> At the end provide recommendations for bringing this ticket into full compliance with the template.
>
> ```markdown
> <ticket-description>
> <!-- Paste ticket description here -->
> </ticket-description>
> ```
