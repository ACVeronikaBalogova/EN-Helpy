---
title: Advance Payments activation and upgrade
description: This section describes Advance Payments Localization for Czech extension functionality.
author: v-pejano

ms.service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Advance Payments, Localization
ms.date: 02/27/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Creating an advance invoice from an order  

The Advance can also be set up via an order. To create an advance, please follow the following procedure:

1. Choose the ![Lightbulb that opens the Tell me Feature](../EN/Media/search_small.png "Tell me what you want to do"), enter **Sales Orders** and then choose the related link. In case of purchase, look for **Purchase Orders**.
2. Create new sales order.
3. After creating the order (including lines), run the **Create Advance** function from the **Advance** section.
4. In the advance creation dialog box, select **Advance Code** (a link to the Advance Template table) and the advance creation method. You can specify the % of the advance or the amount you want to create the advance for.
If you select **Suggest by Row**, a 1:1 advance will be created according to the order rows, i.e. as many rows as the order contains, so many will be in the advance. If **Suggest by line** is not checked, the amounts are accumulated in the advance according to the rates and VAT posting groups used in the order lines.
5. After confirming the advance creation, the advance card opens. It can be checked, edited if necessary, printed and issued ready for payment.

From the **Sales Advance Invoices** overview (in case of Purchase Advance Invoice), you can use the **Linked Documents** function to view the document (order) to which the advance is linked.

## See Also

[Advance Payments localization for Czech Republic](ui-extensions-advance-payments-localization-cz.md)  
[Czech Local Functionality](czech-local-functionality.md)  
[Finance](../../finance.md)
