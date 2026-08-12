---
title: 'Exercise 02: Structure Ward Documents'
layout: default
nav_order: 3
has_children: true
---

# Exercise 02: Structure Ward Documents

## Scenario

In the previous exercise, you used the shared `contosohealthproj` Microsoft Foundry project to analyze patient feedback for Contoso Health, detect language, extract entities, and redact PII so Maya Patel, Jordan Kim, and Marcus Bell can review comments more safely. Now you extend that same workflow by extracting structured fields from mixed-format ward documents, so Olivia Chen and Samir Ahmed can combine narrative feedback insight with reportable operational data.

At Contoso Health, important details are still trapped in scanned forms, slide images, voicemail-style recordings, and meeting videos. In this exercise, you use Azure Content Understanding with the existing workshop resources to build custom analyzers that turn multimodal ward content into structured output that supports ward reporting and trustworthy operational review for Dr. Elena Ruiz and other clinical leaders.

## Objectives

After you complete this exercise, you will be able to:

* Use the shared `contosohealthproj` Microsoft Foundry project and `contosohealth-ai` resource to work with Azure Content Understanding.
* Test prebuilt Content Understanding analyzers against healthcare-related document content.
* Configure Content Understanding Studio to use `contosohealthsa` and the `contosohealthdocs` container for custom analyzer projects.
* Create and test a custom analyzer that extracts fields from scanned ward document content.
* Create and test custom analyzers for image, audio, and video healthcare scenarios so the extracted data can support downstream reporting.

## Duration

* **Estimated Time:** 40 minutes
