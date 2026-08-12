---
title: 'Exercise 03: Add Shelf-Aware Vision Chat'
layout: default
nav_order: 4
has_children: true
---

# Exercise 03: Add Shelf-Aware Vision Chat

## Scenario

In the previous exercise, you built and tested Zava Assist agent experiences in `aiproj-zava-assist` for both shoppers and store associates. Now you extend that work so Zava can support situations where text alone is not enough, such as identifying products from shelf photos, understanding packaging, or helping an associate answer a shopper's question while standing in the aisle.

For Maya Patel, Liam Chen, and Sofia Ramirez, this vision-enabled experience helps make Zava Assist more useful across both `zava.com` and in-store devices. In this exercise, you use Azure AI Foundry and the OpenAI Python SDK to create a chat app that accepts image input, first by referencing an image URL and then by uploading a local file, so Ethan Brooks can prototype shelf-aware assistance in the shared Zava workshop environment.

## Objectives

After you complete this exercise, you will be able to:

* Test a vision-capable model in Azure AI Foundry by submitting an image-based prompt.
* Configure a Python chat application to use Zava's existing Azure OpenAI deployment.
* Use the OpenAI Python SDK with Microsoft Entra ID authentication to send text-and-image prompts.
* Update the application to analyze both a URL-based image and a local image file.
* Run and verify a vision-enabled Zava Assist prototype for retail support scenarios.

## Duration

* **Estimated Time:** 30 minutes
