---
title: 'Exercise 03: Add Omnichannel Shopping Agents'
layout: default
nav_order: 4
has_children: true
---

# Exercise 03: Add Omnichannel Shopping Agents

## Scenario



> **What you need**
>
> - An active Azure subscription with permission to use the existing workshop resources, including `rg-zava-workshop` and `ai-zava-foundry`.
> - Visual Studio Code installed locally.
> - Python 3.13 or later installed. This exercise has been successfully tested with Python 3.13.12.
> - Git installed locally.
> - Azure CLI installed and available from a terminal.
> - Basic familiarity with Python and Azure AI services.
> - Access to a Microsoft Foundry project endpoint and an available deployed model in the shared Foundry environment.

> **Continuing from a previous exercise?**
>
> If you completed the previous exercise, you already signed in to Azure, worked with Zava's shared AI environment, and validated a vision-enabled Python app that uses `DefaultAzureCredential`. You can reuse the same local tools and Azure sign-in, so you only need to create the agent, open the new lab files, and configure the agent client for this exercise.

## Objectives

After you complete this exercise, you will be able to:

* Create an AI agent in Microsoft Foundry for Zava's omnichannel shopping assistant.
* Configure the agent with retail-specific instructions, grounding data, and built-in tools.
* Test the agent in the Foundry portal and in Visual Studio Code.
* Build a Python client application that connects to the agent by using the Azure AI Projects SDK and `DefaultAzureCredential`.
* Run retail-focused prompts that use file search and code interpreter capabilities.

## Duration

* **Estimated Time:** 45 minutes

---

**Next:** [1. Create the Zava shopping agent in Microsoft Foundry]({{ site.baseurl }}/build_zava_s_omnichannel_ai_shopping_assistant/03_add_omnichannel_shopping_agents/03_01/)
