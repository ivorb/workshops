---
title: Introduction
layout: default
nav_order: 1
---

# Build Zava's Omnichannel AI Shopping Assistant

In this workshop, you'll plan, prototype, and extend an AI shopping assistant for Zava, a retail DIY chain that serves customers in stores and online. You'll start by framing the business requirements, responsible AI considerations, and technical architecture for a real-world AI development project. Next, you'll build task-focused AI agents using Azure AI Foundry tools in the portal and VS Code to handle common retail product and support scenarios. Finally, you'll create a vision-enabled chat app that can interpret shelf and product images so store associates and shoppers can get richer help when text alone isn't enough.

Zava is a fictional retail DIY chain with 60 stores, a growing e-commerce business, and a broad catalog of home improvement products, tools, and seasonal items. The company wants a single AI shopping assistant that works across its website and in-store associate devices. Shoppers should be able to ask product questions, compare options, and get help choosing the right item for a project. In stores, associates should be able to use the same assistant to inspect shelf photos, identify products or gaps, and quickly escalate complex situations to a human colleague when policy, safety, or customer frustration requires it.

As a developer on Zava's digital innovation team, you are helping turn that vision into a practical solution. The first step is to define the project foundations: business goals, user flows, data and safety considerations, and the Azure environment that will support development. With that groundwork in place, you'll create AI agents that can answer retail questions, guide shoppers through product discovery, and hand off edge cases in a controlled way. You will then enhance the experience with vision so the assistant can reason over shelf and product images submitted from the store floor or online chat.

By the end of the workshop, you will have built the blueprint and core implementation for **Zava Assist**, an omnichannel retail AI assistant. The solution will include a shared Azure environment, agent-based interactions for customer and associate support, and a vision-enabled chat experience that can combine text and images to answer product and merchandising questions.

## Exercises

This workshop has exercises on:

* Frame Zava Assist
* Prototype the Store and Shopper Agents
* Add Shelf-Aware Vision Chat

## Prerequisites

For running this workshop you will need:

* An Azure subscription with permission to create resource groups and Azure AI resources.
* Access to Azure AI Foundry and the ability to create and use projects.
* Visual Studio Code installed with current extensions used for Azure and AI development.
* Git installed and ability to clone, open, and run workshop code locally.
* Familiarity with Python or JavaScript for application development and basic command-line usage.
* Basic understanding of REST APIs, JSON, and secure handling of connection strings and keys.

## Source labs

The exercises were adapted from these Microsoft Learn labs:

* [Prepare for an AI development project](https://github.com/MicrosoftLearning/mslearn-ai-studio/blob/main/Instructions/Exercises/01-Explore-ai-studio.md)
* [Build AI agents with portal and VS Code](https://github.com/MicrosoftLearning/mslearn-ai-agents/blob/main/Instructions/Exercises/01-build-agent-portal-and-vscode.md)
* [Develop a vision-enabled chat app](https://github.com/MicrosoftLearning/mslearn-ai-vision/blob/main/Instructions/Exercises/01-gen-ai-vision.md)
