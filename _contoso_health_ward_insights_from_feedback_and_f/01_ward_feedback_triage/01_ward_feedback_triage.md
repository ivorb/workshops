---
title: 'Exercise 01: Ward Feedback Triage'
layout: default
nav_order: 2
has_children: true
---

# Exercise 01: Ward Feedback Triage

## Scenario

Contoso Health receives patient feedback from inpatient wards, outpatient clinics, and urgent care sites in free-text form. Today, Maya Patel and Jordan Lee rely on manual review to understand whether patients are reporting positive experiences, communication gaps, or service issues. That process is slow, inconsistent across wards, and difficult to scale when feedback volume increases.

In this exercise, you act as Avery Chen, a developer on Contoso Health's digital engineering team. You create the first part of a reusable healthcare insights workflow by building a Python application that connects to `cog-contosohealth-lang` through Microsoft Foundry and analyzes patient feedback text stored in `stcontosohealthworkshop`. The result is a working foundation for ward-level feedback triage that the rest of the workshop can extend with structured document extraction.

> **What you need**
>
> - An active Azure subscription with permission to create or use resources in `rg-contosohealth-workshop`.
> - Access to the Microsoft Foundry portal at `https://ai.azure.com`.
> - [Visual Studio Code](https://code.visualstudio.com/) installed.
> - [Python 3.13.x](https://www.python.org/downloads/release/python-31312/) installed. Python 3.14 may not work with all dependencies used in this exercise.
> - [Git](https://git-scm.com/install/) installed and configured.
> - [Azure CLI](https://learn.microsoft.com/cli/azure/install-azure-cli) installed.
> - Basic familiarity with Python files, virtual environments, and running commands in a terminal.

## Objectives

After you complete this exercise, you will be able to:

* Create or open the Microsoft Foundry project resources used for the workshop in `rg-contosohealth-workshop`.
* Configure a Python development environment for the Contoso Health text analysis application.
* Connect a Python app to Azure AI Language by using the Azure Identity and Text Analytics SDKs.
* Detect the language of patient feedback comments.
* Extract named entities from patient feedback text.
* Identify and redact personally identifiable information (PII) in healthcare-related feedback.
* Validate the output so it can serve as the ward insight foundation for later workshop exercises.

## Duration

* **Estimated Time:** 30 minutes

---

**Next:** [1. Set up the Contoso Health feedback triage workspace]({{ site.baseurl }}/contoso_health_ward_insights_from_feedback_and_f/01_ward_feedback_triage/01_01/)
