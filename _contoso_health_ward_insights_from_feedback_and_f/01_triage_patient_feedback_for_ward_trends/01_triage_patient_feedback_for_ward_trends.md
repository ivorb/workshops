---
title: 'Exercise 01: Triage Patient Feedback for Ward Trends'
layout: default
nav_order: 2
has_children: true
---

# Exercise 01: Triage Patient Feedback for Ward Trends

## Scenario

Contoso Health is a five-hospital healthcare network that wants to improve how it reviews patient feedback across wards. Today, comments from discharge surveys and service recovery messages are read manually by quality teams, which makes it difficult for Maya Patel and Daniel Cho to identify recurring patterns such as communication issues, delays, and discharge planning concerns quickly enough to support ward-level reporting.

In this first exercise of the workshop, you build the baseline text analysis workflow for Contoso Health. You use Azure Language in Foundry Tools and the Azure Language Python SDK to process patient feedback text, detect language, identify entities, and redact personally identifiable information (PII). This gives Nurse Elena Ramirez and Dr. Samir Khan a safer, more consistent starting point for understanding ward trends while also supporting Olivia Brooks’ privacy expectations.

## Objectives

After you complete this exercise, you will be able to:

* Create a Microsoft Foundry project for the Contoso Health workshop scenario.
* Set up and configure a Python application that uses Azure Language in Foundry Tools.
* Connect to the Azure Language Text Analytics service by using `DefaultAzureCredential`.
* Detect the language of patient feedback text.
* Extract named entities from discharge survey comments and service recovery text.
* Identify and redact PII to support healthcare privacy requirements.

## Duration

* **Estimated Time:** 30 minutes
