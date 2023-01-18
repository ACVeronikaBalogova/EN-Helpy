---
title: Advance Payments activation and upgrade
description: This section describes Advance Payments Localization for Czech extension functionality.
author: v-pejano

ms.service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Advance Payments, Localization
ms.date: 01/12/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Creating an advance invoice from an order  

The advance payment can also be made by order. To create an advance, please follow the following procedure:

1. Select icon ![lightbulb, which opens Tell me function](../../media/ui-search/search_small.png "Tell me what do you want to do"), enter **Sales order** and then select related link. For purchasing look for **Purchase order**.
2. Create new Sales order.
3. After creating the order (including lines), run the **Create Advance** function from the **Advance** section.  
4. In the advance creation dialog box, select **Advance Code** (a link to the Advance Template table) and the advance creation method. You can enter % of an advance or straight amount, on which you want to create an advance.  
If you select option **Suggest by line**, the advance is created 1:1 according to the order lines, i.e. how many lines the order contains, so many will be in the advance. If the **Suggest by line** option is not checked, amounts are accumulated in the deposit according to the rates and VAT account groups used in the order lines.
5. After confirming the advance creation, the advance tab opens.  It can be checked, edited if necessary, printed and issued ready for payment.

From the **Sales Advance Invoices** overview (in case of Purchase Advance Invoice purchases), you can use the **Linked Documents** function to view the document (order) to which the advance is linked.

## See also

[Advance payments for the Czech Republic (extension)](ui-extensions-advance-payments-localization-cz.md)  
[Czech local functionality](czech-local-functionality.md)  
[Finance](../../finance.md)
