---
title: Share information through knowledge articles
description: Learn about knowledge management and knowledge articles in Dynamics 365 Field Service.
ms.date: 06/09/2023
ms.topic: how-to
author: jshotts
ms.author: jasonshotts
ms.custom: bap-template
---

# Share information through knowledge articles

When technicians in the field work on assigned jobs, they need access to relevant information to solve the problems they encounter.

Knowledge management in Dynamics 365 Field Service associates relevant knowledge articles with work orders, incidents, products, and customer assets.

Access to knowledge articles help improve the fix rate and guide technicians through procedures.

## Create knowledge articles

Write a knowledge article to share information with technicians.

For more information on knowledge articles, see:

- [Create and manage knowledge articles](../customer-service/use/customer-service-hub-user-guide-knowledge-article.md)
- [Create templates for knowledge articles](../customer-service/use/create-templates-knowledge-article.md)
- [Set up a search provider](../customer-service/administer/set-up-search-providers.md)

:::image type="content" source="media/knowledge-article-new.png" alt-text="Screenshot of a list of knowledge articles in Field Service with callouts on controls.":::

1. In Field Service, go to **Settings** > **Knowledge management** > **Knowledge articles** and select **New** or **New From Template**.

1. Add text, pictures, and videos to the knowledge article.

1. **Save and publish** the knowledge article.

## Link knowledge articles to related entities

Create relationships between knowledge articles and other records, like incident types, products, or customer assets. When any of these records are added to a work order, the system automatically links the related knowledge articles.

1. In Field Service, go to **Settings** > **Knowledge management** > **Knowledge articles**.

1. Select an article. On the **Summary** tab, in the **Related Information** section, select the target entity for the relationship.

1. Select the vertical ellipsis &vellip; and choose **Add Existing Customer Asset**.

   :::image type="content" source="media/knowledge-article-associate-asset.jpg" alt-text="Screenshot of a Field Service knowledge article, showing the related information.":::

1. Choose which record in the target entity to link to the article.

1. Select **Save & Close**

> [!TIP]
> You can also link knowledge articles without configured relationship to incidents, assets, or products. On a target record, go to the **Linked Articles** tab and select **New Linked Article**.

## Next steps

- [Create a work order](create-work-order.md)
- [Create work order templates with incident types](configure-incident-types.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
