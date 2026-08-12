---
title: 'Exercise 02: Prototype the Store and Shopper Agents'
layout: default
nav_order: 3
has_children: true
---

# Exercise 02: Prototype the Store and Shopper Agents

## Scenario

In exercise 01, you created the shared Microsoft Foundry project and deployed a model in `rg-zava-workshop`, giving Zava Assist a reusable Azure foundation for the rest of the workshop. Now you build the next layer of the solution by prototyping the store and shopper agent experience that Maya Patel, Liam Chen, Sofia Ramirez, Noah Williams, and Priya Nair need across digital and in-store channels.

In this exercise, you use the existing `aiproj-zava-assist` project in the Foundry portal and Visual Studio Code to create a retail-focused agent that can answer product and policy-style questions, analyze uploaded store operations data, and support controlled escalation for more complex cases. You keep the same technical workflow as the original implementation, but you shape it around Zava Assist so the resulting prototype fits the omnichannel retail scenario established for Zava.

## Objectives

After you complete this exercise, you will be able to:

* Create a retail-focused AI agent in `aiproj-zava-assist` by using the Foundry portal.
* Configure the agent with instructions, grounding data, **File search**, and **</> Code interpreter**.
* Test the agent in the Foundry portal with shopper and store-associate scenarios.
* Open and test the same agent in Visual Studio Code by using the Foundry Toolkit extension.
* Build and run a Python client application that connects to the Zava Assist agent programmatically.
* Verify that the agent can answer grounded retail questions and analyze uploaded CSV data.

## Duration

* **Estimated Time:** 45 minutes
