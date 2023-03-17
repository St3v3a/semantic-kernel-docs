---
title: Planner in Semantic Kernel
description: What is Planner in Semantic Kernel
author: johnmaeda
ms.topic: concepts
ms.author: johnmaeda
ms.date: 02/07/2023
ms.service: mssearch
---

# What is Planner?

| ASK⇾ | [Kernel](/semantic-kernel/concepts-sk/kernel) | Planner | [Skills](/semantic-kernel/concepts-sk/skills)| [Memories](/semantic-kernel/concepts-sk/memories) |[Connectors](/semantic-kernel/concepts-sk/connectors) | >>>|  ⇾GET | 
|---|---|---|---|---|---|---|---|

[!INCLUDE [fullview.md](../includes/fullview.md)]

The _planner_ works backwards from a goal that’s provided from a user's _ASK_. 

![Image of step-by-step process of Semantic Kernel](../media/goaloriented.png)

We call this approach "goal-oriented AI" — harking back to the early days of AI when researchers aspired for computers to beat the world's reigning chess champion. That grand goal was achieved eventually, but with the unusual competence of new LLM AI [models](/semantic-kernel/concepts-ai/models) to provide step-by-step directions for practically any goal can be attainable when the right _skills_ are available. 

Because the _planner_ has access to either a pre-defined library of pre-made [skills](/semantic-kernel/concepts-sk/skills) and/or a dynamically defined set of [skills](/semantic-kernel/concepts-sk/skills) it is able to fulfill an ASK with confidence. In addition, the _planner_ calls upon [memories](/semantic-kernel/concepts-sk/memories) to best situate the ASK's context and [connectors](/semantic-kernel/concepts-sk/connectors) to call APIs and to leverage other external capabilities.

> [!TIP]
> Try the [Book creator sample app](/semantic-kernel/samples/bookcreator) to see the Planner in action.

## What is the value of "goal-oriented" AI?

The ["Jobs To Be Done (JTBD)"](/semantic-kernel/support/bibliography#jobs-to-be-done) movement has popularized a shift in moving from work _outputs_ to work _outcomes_. Instead of focusing on the features or the functions of a product or a service, the JTBD approach emphasizes the goals and desires of the customer or the user, and the value or the benefit that they seek or expect from using the product or service. By understanding and articulating the JTBD of the customer or the user, a product or service can be designed and delivered more effectively. You just need to make the right ASK that isn't just "turn on the lights" and instead a more challenging goal like "I want a job promotion."

## What if the Planner needs a Skill that's unavailable?

The _planner_ will operate within the [skills](/semantic-kernel/concepts-sk/skills) it has available. In the event that a desired skill does not exist, the planner can suggest you to [create the skill](/semantic-kernel/concepts-sk/skills). Or, depending upon the level of complexity the kernel can help you write the missing skill.

## Take the next step

Now that you know about the _kernel_ and the _planner_, you are ready to learn about _skills_.

> [!div class="nextstepaction"]
> [Learn about Skills](skills.md)