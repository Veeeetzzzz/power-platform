---
title: "Key concepts for desktop Composer users (preview)"
description: "Overview of how key concepts in Composer translate to concepts in Power Virtual Agents preview."
ms.date: 10/10/2022
ms.topic: overview
author: v-alarioza
ms.author: v-alarioza
manager: shellyha
ms.custom: fundamentals, ceX, intro-internal
ms.collection: virtual-agent
searchScope:
  - "Power Virtual Agents"
---

# Key concepts for desktop Composer users (preview)

[!INCLUDE [Preview disclaimer](includes/public-preview-disclaimer.md)]

There are a number of differences and similarities in how bots are designed in the Bot Framework Composer and the Power Virtual Agents preview. The following table lists some key concepts in Composer and describes where to find information about similar concepts in Power Virtual Agents.

<!-- best viewed without wordwrap -->
| Composer concept               | Power Virtual Agents concept                        | Description                                                                                                                                                                                                                                        |
| :----------------------------- | :-------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Dialogs and triggers           | [Topics][]                                          | Use topics to organize conversation flow or paths. A topic has a set of _trigger phrases_ that indicate when the bot should start the topic and a set of _nodes_ that describe the conversation path for the topic.                                |
| Intents                        | [Trigger phrases][]                                 | Add trigger phrases to a topic for phrases, keywords, and questions that a user is likely to type related to a specific issue. Power Virtual Agents uses natural language understanding to parse what a customer types and find the most appropriate topic. |
| Actions and prompts            | [Nodes][]                                           | Use nodes on the authoring canvas to create the conversation path for each topic, such as messages, questions, and conditional branches.                                                                                                           |
| Bot response variation         | [Response variations][] and [question variations][] | Use response and question variations to add variety to your bot's messages and questions.                                                                                                                                                          |
| Suggested actions              | [Quick replies][]                                   | Use quick replies to provide default reply options to the user.                                                                                                                                                                                    |
| Entities                       | [Entities][]                                        | Define and use entities to extract semantic information from a user's utterance.                                                                                                                                                                   |
| State, storage, and properties | [Variables][]                                       | Use variables to track state.                                                                                                                                                                                                                      |
| Formulas and expressions       | [Power Fx][]                                        | Use Power Fx to create expressions.                                                                                                                                                                                                                |

[Entities]: advanced-entities-slot-filling.md
[Nodes]: authoring-create-edit-topics.md
[Power Fx]: advanced-power-fx.md
[question variations]: authoring-send-message.md#use-message-variations
[Quick replies]: authoring-send-message.md#use-quick-replies
[Response variations]: authoring-send-message.md#use-message-variations
[Topics]: authoring-create-edit-topics.md
[Trigger phrases]: authoring-create-edit-topics.md
[Variables]: authoring-variables.md
