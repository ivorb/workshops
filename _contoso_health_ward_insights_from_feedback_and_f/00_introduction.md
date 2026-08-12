---
title: Introduction
layout: default
nav_order: 1
---

# Contoso Health Ward Insights from Feedback and Forms

In this workshop, you'll help Contoso Health turn unstructured patient feedback and ward documents into usable operational insight. You’ll first analyze patient comments to identify sentiment, key phrases, and themes that matter to clinicians and operations leaders, then extend that solution by extracting structured information from multimodal documents such as scanned referral packets, discharge summaries, and ward reporting forms. By the end, you’ll have built a connected analytics flow that supports ward performance reporting while respecting healthcare requirements such as privacy, traceability, and careful handling of PHI.

**Contoso Health** is a fictional five-hospital network that delivers acute care, outpatient services, imaging, and care coordination across a regional healthcare system. Its clinical leadership wants a more reliable way to understand what patients are saying about their care experience and to combine that feedback with information trapped in scanned forms and mixed-format ward documents. Today, nurse managers and care coordinators read comments manually, while operations analysts rekey details from referral packets, discharge paperwork, and ward audit forms into spreadsheets. This delays reporting, makes trends hard to spot, and increases the risk of inconsistent handling of sensitive patient information.

You are a **data analyst** on Contoso Health’s transformation team, working with nursing leadership and operational stakeholders to modernize this process. The immediate goal is to improve how ward managers summarize patient feedback about wait times, communication, discharge readiness, and care coordination, then enrich those insights with structured data pulled from multimodal content. The scenario is grounded in healthcare realities: patient comments may contain PHI, documents can include handwritten notes and scanned tables, and the output must support auditability and responsible use in downstream reporting.

By the end of the workshop, you will have built a small but realistic analytics foundation for Contoso Health: a text analysis pipeline that classifies and summarizes patient feedback themes, followed by a multimodal extraction step that converts ward and care-related documents into structured fields for reporting. Together, these exercises form one continuous story: from understanding the voice of the patient to assembling a fuller operational picture of ward performance.

## Exercises

This workshop has exercises on:

* Triage Patient Feedback
* Structure Ward Documents

## Prerequisites

For running this workshop you will need:

* An Azure subscription with permission to create resource groups and Azure AI resources.
* Access to Azure AI services, including capabilities for text analysis and document/multimodal extraction.
* Access to Azure OpenAI in the selected region or an approved workshop environment where it is pre-provisioned.
* Basic familiarity with Azure portal navigation and running lab steps in Microsoft Learn exercises.
* Understanding of healthcare data sensitivity, including PHI/HIPAA-aware handling of patient-related content in demo datasets.
* A modern web browser and reliable internet access for Azure portal and lab environments.

## Source labs

The exercises were adapted from these Microsoft Learn labs:

* [Analyze text](https://github.com/MicrosoftLearning/mslearn-ai-language/blob/main/Instructions/Exercises/01-analyze-text.md)
* [Extract information from multimodal content](https://github.com/MicrosoftLearning/mslearn-ai-information-extraction/blob/main/Instructions/Exercises/01-content-understanding.md)
