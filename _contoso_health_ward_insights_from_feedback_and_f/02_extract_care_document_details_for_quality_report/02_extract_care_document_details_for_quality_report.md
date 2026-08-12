---
title: 'Exercise 02: Extract Care Document Details for Quality Reporting'
layout: default
nav_order: 3
has_children: true
---

# Exercise 02: Extract Care Document Details for Quality Reporting

## Scenario

In the previous exercise, you built the first part of Contoso Health's ward insights solution by using Azure Language to detect language, extract entities, and redact PII from patient feedback so Daniel Cho and Maya Patel could start identifying recurring themes safely.

In this exercise, you extend that workflow by extracting structured details from multimodal healthcare content so Contoso Health can enrich and validate its ward performance reporting. Using Azure Content Understanding, you create and test custom analyzers for scanned documents and images, helping teams such as Priya Nair and Nurse Elena Ramirez turn difficult-to-use content into report-ready fields while keeping the solution grounded in auditable Azure resources.

## Objectives

After you complete this exercise, you will be able to:

* Use prebuilt Azure Content Understanding analyzers in Microsoft Foundry to inspect document structure and extracted text.
* Configure Content Understanding Studio to use the existing Contoso Health Azure resources.
* Create a custom analyzer that extracts structured fields from scanned healthcare-related documents.
* Build and test a custom analyzer that extracts structured information from healthcare slide images.
* Review analyzer results as field values and JSON output that can support downstream reporting.

## Duration

* **Estimated Time:** 40 minutes
