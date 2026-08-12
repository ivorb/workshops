---
title: 'Exercise 01: Frame Zava''s AI Assistant Project'
layout: default
nav_order: 2
has_children: true
---

# Exercise 01: Frame Zava's AI Assistant Project

## Scenario

Zava is a fictional omnichannel DIY retail chain that wants to build an AI shopping assistant for customers and store associates. Shoppers often arrive with photos of damaged fittings, appliance parts, paint samples, or handwritten shopping lists, and Zava needs a practical way to turn those real-world inputs into useful product guidance, faster product discovery, and more consistent assisted selling across online and in-store experiences.

In this first exercise of the workshop, you frame the project foundations for that assistant. You set up the shared Microsoft Foundry environment that Zava's developer team will use across the workshop, explore the model capabilities that will support the assistant, and review the endpoints and tools that Liam Chen and the rest of the team will use in later implementation exercises. Along the way, you keep Zava's business priorities in view: trustworthy responses, strong catalog support, operational efficiency, and a reusable Azure-based foundation.

> **What you need**
>
> - An active Azure subscription with permission to create resources in `rg-zava-workshop`.
> - Access to the [Microsoft Foundry portal](https://ai.azure.com) using the same Azure account that you use for resource creation.
> - [Visual Studio Code](https://code.visualstudio.com/) installed.
> - [Python 3.13.x](https://www.python.org/downloads/release/python-31312/) installed. Python 3.14 is available, but some dependencies are not yet compiled for that release. This exercise has been tested with Python 3.13.12.
> - [Git](https://git-scm.com/install/) installed and configured.
> - [Azure CLI](https://learn.microsoft.com/cli/azure/install-azure-cli?view=azure-cli-latest) installed.
> - Basic familiarity with Azure resources, model deployments, and Visual Studio Code.

## Objectives

After you complete this exercise, you will be able to:

* Create the shared Microsoft Foundry project environment for Zava's AI shopping assistant.
* Deploy and test a generative AI model that can support retail assistant scenarios.
* Identify the resource-level and project-level endpoints that developers use to connect applications and services.
* Connect Visual Studio Code to the shared Foundry project by using the Foundry Toolkit extension.
* Establish the technical foundation that will support later workshop exercises for vision and agent-based retail experiences.

## Duration

* **Estimated Time:** 30 minutes

---

**Next:** [1. Create Zava's shared Foundry project]({{ site.baseurl }}/build_zava_s_omnichannel_ai_shopping_assistant/01_frame_zava_s_ai_assistant_project/01_01/)
