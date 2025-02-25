---
title: Use Copilot in the Dynamics 365 Field Service web application
description: Learn how to use Copilot to summarize records, catch up on recent changes, and prepare for onsite jobs.
ms.date: 04/22/2024
ms.topic: how-to
author: jshotts
ms.author: jasonshotts
ms.reviewer: mhart
ms.collection: bap-ai-copilot
---

# Use Copilot in the Dynamics 365 Field Service web application

Copilot is a next-generation AI assistant that helps you be more productive and efficient in your daily work the Dynamics 365 Field Service web app. Copilot can summarize information about your work order and service accounts, help you catch up on recent changes to your records, prepare for onsite visits, and answer questions about related information. It has a chat interface that dispatchers and technicians can use to interact with Copilot in natural language.

## Prerequisites

An administrator has to enable the copilot feature for all users in the environment from the Power Platform admin center. For more information, see [Enable copilot for model-driven apps feature for your environment](/power-apps/maker/model-driven-apps/add-ai-copilot#enable-copilot-for-model-driven-apps-feature-for-your-environment).

## Open Copilot

To open the copilot pane, select the **Copilot** icon (:::image type="icon" source="media/copilot-icon.svg" border="false":::) on the app header.

Select the icon again to minimize the copilot pane.

:::image type="content" source="media/copilot-side-pane-web.svg" alt-text="Screenshot of Copilot in Field Service answering questions of a user in the Field Service web app.":::

## Chat with Copilot

Use predefined prompts to get the most out of Copilot. The following list provides a quick reference to predefined prompts.

- List work orders for {service account name}.
- Who is booked for work order {work order number}?
- What are the products used on work order {work order number}?

## Region availability and languages supported

To use this capability, your environment must be in the US region and have its language set to en-US.

You must allow data movement across regions for Generative AI features as a prerequisite for running copilot in Power Apps. This step is especially important if your organization and your environment are in different regions. For more information, see [Enable data movement across regions](/power-platform/admin/geographical-availability-copilot#enable-data-movement-across-regions).

## See also

- [Enable copilots and generative AI features](/power-platform/admin/geographical-availability-copilot)
- [Add copilot for app users in model-driven apps](/power-apps/maker/model-driven-apps/add-ai-copilot)
- [FAQ for Copilot in model-driven apps](/power-apps/maker/common/faqs-copilot-model-driven-app)