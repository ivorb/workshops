---
title: Introduction
layout: default
nav_order: 1
---

# Build Zava's Omnichannel AI Shopping Assistant

In this workshop, you'll step into the role of a developer building an AI shopping assistant for Zava, a retail DIY chain. You'll start by preparing the project foundations, success criteria, and Azure environment for a real-world AI solution. Then you'll create task-focused AI agents in Azure AI Foundry using both the portal and VS Code to handle product questions and escalation workflows. Finally, you'll extend the solution into a vision-enabled chat app that can interpret shelf and product photos, helping store associates and online shoppers get accurate answers across in-store and digital channels.

Zava is a fictional retail DIY chain with 60 stores, a growing e-commerce channel, and a product catalog spanning tools, paint, electrical supplies, garden equipment, and seasonal merchandise. The company wants to launch a single AI shopping assistant that serves both online shoppers and in-store associates. Customers should be able to ask product questions, compare options, and share shelf or product photos when labels are unclear. When the assistant cannot confidently resolve a request, it must hand off the case to a human colleague with the right context. Zava's leadership sees this as a way to improve customer engagement, reduce friction in stores, and help associates spend more time on high-value conversations.

In this workshop, you build that solution as one continuous project. First, you prepare the AI development effort by defining the business goals, core use cases, responsible AI considerations, and shared Azure foundation. Next, you build AI agents that can answer catalog and policy questions and support escalation workflows using Azure AI Foundry in both the portal and VS Code. Finally, you develop a vision-enabled chat app that can analyze shelf photos and product imagery so the assistant can answer questions grounded in what a shopper or associate is seeing. By the end, you will have assembled a practical prototype of Zava Assist, an omnichannel retail AI assistant for stores and e-commerce.

## Exercises

This workshop has exercises on:

* Frame Zava Assist
* Create the Product Help Agents
* Launch the Shelf-Aware Chat App

## Prerequisites

For running this workshop you will need:

* An Azure subscription with permission to create resource groups and Azure AI resources.
* Access to Azure AI Foundry and permission to create or use project resources.
* Visual Studio Code installed with the workshop-required extensions for Azure and AI development.
* Git installed and the ability to clone and run the provided workshop code locally.
* Basic familiarity with Python, REST APIs, and JSON.
* Basic understanding of Azure resource management in the Azure portal.

## Source labs

The exercises were adapted from these Microsoft Learn labs:

* [Prepare for an AI development project](https://github.com/MicrosoftLearning/mslearn-ai-studio/blob/main/Instructions/Exercises/01-Explore-ai-studio.md)
* [Build AI agents with portal and VS Code](https://github.com/MicrosoftLearning/mslearn-ai-agents/blob/main/Instructions/Exercises/01-build-agent-portal-and-vscode.md)
* [Develop a vision-enabled chat app](https://github.com/MicrosoftLearning/mslearn-ai-vision/blob/main/Instructions/Exercises/01-gen-ai-vision.md)
