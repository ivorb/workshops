---
title: Introduction
layout: default
nav_order: 1
---

# Contoso Health: ward insights from feedback and forms

**Difficulty** ▰▰▰▱▱ **L300**

In this workshop, you'll build an end-to-end healthcare insight workflow for Contoso Health using Azure AI services. You'll start by analyzing patient feedback text to identify sentiment and key themes by ward, then extend the solution by extracting structured data from scanned patient intake forms and other multimodal documents. Along the way, you'll apply a realistic hospital scenario with privacy, auditability, and operational reporting needs in mind.

Contoso Health is a regional hospital group that operates multiple inpatient wards, outpatient clinics, and urgent care sites. Its clinical operations team wants a clearer view of patient experience and intake bottlenecks, but the data arrives in inconsistent formats: free-text feedback from post-visit surveys, handwritten or scanned intake forms, and supporting documents captured at registration. Today, ward managers and care coordinators review this information manually, which slows service improvement and makes it difficult to spot recurring issues such as long waits, communication gaps, or missing registration details. Because the information may include PHI, the solution must support careful handling, traceability, and operational use without changing the source EHR.

As the learner, you are acting as a developer on Contoso Health's digital engineering team. You will first create a text analytics workflow that processes patient feedback comments and surfaces sentiment and key discussion topics that can be grouped into ward-level insight for the clinical operations team. You will then build on that foundation by extracting structured information from multimodal patient intake content so registration and care coordination teams can turn paper-based submissions into usable operational data.

By the end of the workshop, you will have built a connected prototype that helps Contoso Health transform unstructured patient experience data and intake documents into consistent, machine-readable insight. The result is a reusable pattern the hospital group can extend for patient intake, triage preparation, service quality monitoring, and downstream integration with clinical and administrative systems.

## Workshop at a glance

| Exercise | Difficulty | Time |
|---|---|---|
| Exercise 01: Ward Feedback Triage | ▰▰▰▱▱ **L300** | 30 minutes |
| Exercise 02: Intake Packet Structuring | ▰▰▰▱▱ **L300** | 40 minutes |

## Exercises

This workshop has exercises on:

* Ward Feedback Triage
* Intake Packet Structuring

## Prerequisites

For running this workshop you will need:

* An Azure subscription with permission to create resource groups and Azure AI resources.
* Familiarity with basic Azure portal navigation.
* Basic developer experience with REST, SDKs, or running sample code.
* Awareness of healthcare privacy requirements such as handling PHI/HIPAA-sensitive content in demos and test data.

## Source labs

The exercises were adapted from these Microsoft Learn labs:

* [Analyze text](https://github.com/MicrosoftLearning/mslearn-ai-language/blob/main/Instructions/Exercises/01-analyze-text.md)
* [Extract information from multimodal content](https://github.com/MicrosoftLearning/mslearn-ai-information-extraction/blob/main/Instructions/Exercises/01-content-understanding.md)

---

**Next:** [Exercise 01: Ward Feedback Triage]({{ site.baseurl }}/contoso_health_ward_insights_from_feedback_and_f/01_ward_feedback_triage/01_ward_feedback_triage/)
