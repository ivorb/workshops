---
title: 'Exercise 02: Intake Packet Structuring'
layout: default
nav_order: 3
has_children: true
---

# Exercise 02: Intake Packet Structuring

## Scenario

In the previous exercise, you built the Contoso Health ward feedback triage foundation by using `cog-contosohealth-lang` to analyze patient comments, detect language, extract entities, and redact PII. In this exercise, you extend that same healthcare insight workflow by extracting structured information from scanned and image-based intake content so Contoso Health can combine document-derived data with the ward-level feedback signals already prepared for Maya Patel and Jordan Lee.

As Avery Chen on the Contoso Health digital engineering team, you now create multimodal analyzers that turn paper-style intake packets and other visual content into machine-readable data. This helps Elena Rodriguez and Samir Khan reduce manual review, improve intake traceability, and prepare operational data that can later be correlated with patient experience trends without changing the source clinical systems.

> **What you need**
>
> - An active Azure subscription with permission to use resources in `rg-contosohealth-workshop`.
> - Access to the Microsoft Foundry portal at `https://ai.azure.com` and Content Understanding Studio at `https://contentunderstanding.ai.azure.com`.
> - The shared workshop resources already provisioned or available for use: `ai-contosohealth-foundry`, `cog-contosohealth-docintel`, and `stcontosohealthworkshop`.
> - A local folder where you can download and extract the sample content archive.
> - Familiarity with basic Azure portal and Foundry portal navigation.
> - If you are starting fresh, you need the Foundry project resources from the workshop available in `rg-contosohealth-workshop`.

> **Continuing from a previous exercise?**
>
> If you completed the previous exercise, you already have access to the shared workshop resource group `rg-contosohealth-workshop` and the Foundry project resources centered on `ai-contosohealth-foundry`. You can reuse those resources here, so you do not need to create a new resource group or re-establish the workshop environment before starting this exercise.

## Objectives

After you complete this exercise, you will be able to:

* Create or reuse the Microsoft Foundry project resources needed for multimodal extraction in `rg-contosohealth-workshop`.
* Download and inspect the sample content used to test multimodal analyzers.
* Use prebuilt Azure Content Understanding analyzers in the Foundry portal to explore document layout extraction.
* Connect Content Understanding Studio to `ai-contosohealth-foundry` and `stcontosohealthworkshop`.
* Create a custom document analyzer that extracts structured fields from sample intake-style documents.
* Create a custom image analyzer that extracts structured information from image-based content.
* Test built analyzers and review the extracted field data and JSON results.

## Duration

* **Estimated Time:** 40 minutes

---

**Next:** [1. Prepare the Contoso Health multimodal workspace]({{ site.baseurl }}/contoso_health_ward_insights_from_feedback_and_f/02_intake_packet_structuring/02_01/)
