---
title: 'Exercise 02: Create the Visual Product Finder Chat'
layout: default
nav_order: 3
has_children: true
---

# Exercise 02: Create the Visual Product Finder Chat

## Scenario

In the previous exercise, you created Zava's shared Microsoft Foundry environment, deployed a model for retail scenarios, and connected your development tools to the project. Now you build the next customer-facing capability: a visual product finder chat experience that helps Zava shoppers and store associates use images and natural language together.

Zava wants customers to be able to ask practical DIY shopping questions such as identifying a replacement part from a photo, understanding what a product is, or getting suggestions for compatible materials and next steps. In this exercise, you develop a Python chat app that uses Microsoft Foundry and the OpenAI SDK with image input so the assistant can combine visual understanding with conversational guidance for retail use cases.

> **What you need**
>
> - An active Azure subscription with access to the shared workshop resources, including `rg-zava-workshop`, `ai-zava-foundry`, and `aoai-zava-shop`.
> - Access to the Microsoft Foundry portal at `https://ai.azure.com`.
> - Visual Studio Code installed.
> - Python version **3.13.xx** installed. Python 3.14 is available, but some dependencies are not yet compiled for that release. This exercise has been tested with Python 3.13.12.
> - Git installed and configured.
> - Azure CLI installed.
> - Permission to sign in with `az login` and use the subscription that contains the workshop resources.
> - Basic familiarity with Python files, virtual environments, and running commands in the VS Code terminal.

> **Continuing from a previous exercise?**
>
> If you completed the previous exercise, you can reuse the shared Foundry project in `ai-zava-foundry`, the model deployment you already created, and the Azure OpenAI endpoint you already recorded. You do not need to create a new project or redeploy the model unless those resources are unavailable in your environment.

## Objectives

After you complete this exercise, you will be able to:

* Test a vision-capable model in Microsoft Foundry by submitting a prompt that includes an image.
* Configure a Python client app to connect to Zava's shared Azure OpenAI deployment.
* Authenticate to Azure by using Microsoft Entra ID and `DefaultAzureCredential`.
* Send image-based prompts to the model by using both a hosted image URL and a local image file.
* Run and validate a retail-themed chat experience that can identify items and answer DIY shopping questions.

## Duration

* **Estimated Time:** 30 minutes

---

**Next:** [1. Validate the shared vision-ready model in Foundry]({{ site.baseurl }}/build_zava_s_omnichannel_ai_shopping_assistant/02_create_the_visual_product_finder_chat/02_01/)
