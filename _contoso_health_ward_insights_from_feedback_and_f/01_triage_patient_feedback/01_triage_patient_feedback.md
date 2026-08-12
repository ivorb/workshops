---
title: 'Exercise 01: Triage Patient Feedback'
layout: default
nav_order: 2
has_children: true
---

# Exercise 01: Triage Patient Feedback

## Scenario

Contoso Health wants a faster, more consistent way to understand what patients are saying about their care experience. Today, Maya Patel and Jordan Kim rely on manual review of ward comments to spot issues related to wait times, bedside communication, discharge readiness, and care coordination. That process is slow, difficult to scale, and increases the chance that sensitive patient details are handled inconsistently.

In this exercise, you build the first part of the workshop solution: a text analysis workflow that triages patient feedback. You use Azure Language through Microsoft Foundry to detect language, identify named entities, and redact personally identifiable information (PII) from patient comments. This gives Olivia Chen a repeatable Azure-based baseline for ward-level insight and prepares the data foundation that Contoso Health will extend in the next exercise with multimodal document extraction.

## Objectives

After you complete this exercise, you will be able to:

* Create and use the shared Microsoft Foundry project for the Contoso Health workshop.
* Prepare a Python application that analyzes patient feedback comments.
* Connect to Azure Language by using the Python SDK and Microsoft Entra ID authentication.
* Detect the language of patient feedback comments.
* Extract entities from ward-level patient feedback text.
* Identify and redact PII in patient feedback to support privacy-aware downstream analysis.

## Duration

* **Estimated Time:** 30 minutes
