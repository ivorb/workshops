---
title: 'Exercise 03: Launch the Shelf-Aware Chat App'
layout: default
nav_order: 4
has_children: true
---

# Exercise 03: Launch the Shelf-Aware Chat App

## Scenario

In the previous exercise, you built Zava product help agents in Microsoft Foundry and verified that they can answer grounded questions, analyze uploaded data, and support escalation workflows. Now you extend that foundation into the customer-facing experience Maya Patel wants for Zava Assist: a vision-enabled chat app that can interpret what a shopper or associate sees in a product or shelf photo.

At Zava, this matters across both e-commerce and store operations. Ethan Brooks can use the app to help customers when packaging is unclear on the shelf, Lucas Meyer can support associates with faster in-aisle answers, and Sofia Rossi can ensure the assistant stays aligned with approved product guidance. In this exercise, you use `ai-zava-foundry`, `aoai-zava-assistant`, and `aisvc-zava-vision` to build and test the multimodal chat experience that brings Zava Assist into real retail scenarios.

## Objectives

After you complete this exercise, you will be able to:

* Test a vision-capable model in Microsoft Foundry by submitting an image-based prompt.
* Prepare a Python client application that connects to Zava's shared Azure AI environment.
* Use the OpenAI SDK with Entra ID authentication to submit prompts that include image input.
* Modify the app to analyze both a remote image URL and a local image file.
* Validate that the shelf-aware chat app can support in-store and online product assistance scenarios.

## Duration

* **Estimated Time:** 30 minutes
