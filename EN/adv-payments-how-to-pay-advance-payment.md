---
title: Advance Payments activation and upgrade
description: This section describes Advance Payments Localization for Czech extension functionality.
author: v-pejano

ms.service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Advance Payments, Localization
ms.date: 03/01/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Payment of advance invoice

If an advance invoice is in the For Payment status, it can be paid using a General journal or Cash order.

## Payment of the advance invoice by General Journal

1. Choose the ![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what you want to do"), enter **General Journal** and then choose the related link.
2. Select General Journal Template.
3. To pay an advance invoice in the General journal, fill in the field **Document type = payment**.
4. Enter the corresponding **Customer/Vendor Number** (depending on the type of advance invoice: purchase/sales).
5. A list of all outstanding or partially outstanding advances is available in the **Advance Number** field on the General journal line. The list of advances is filtered by the currency code selected on the General journal line.
Select the advance invoice you want to pay and confirm the selection in the Journal line. You can reduce the suggested amount if the advance is to be paid only partially.
Only one advance invoice can be attached to a General journal line. Payment of several advances at the same time must be split over several lines.
6. After posting the General journal, an entry with **Entry Type = Payment** will be created in the advance entries.

## Payment of the advance invoice by cash order

When paying an advance invoice by cash desk, the user proceeds in a similar way as in the General journal.

1. Choose the ![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what you want to do"), enter **Cash Order** and then choose the related link.
2. Create new Cash Order.
3. Enter the appropriate **Customer/Vendor Number** (depending on the type of advance invoice: purchase/sales).
4. A list of all outstanding or partially outstanding advances, filtered by cash register currency code, is available in the **Advance Number** field on the cash order line
Select the advance invoice you want to pay, confirm the selection in the cash order line. The amount proposed can be reduced if the advance is to be partially paid. Only one advance payment can be attached to one cash order line. Payment of multiple advances at the same time must be split over multiple lines.
5. After posting the cash order, an entry with **Entry Type = Payment** will be created in the advance entries.

## See also

[Advance Payments localization for Czech Republic](ui-extensions-advance-payments-localization-cz.md)  
[Czech Local Functionality](czech-local-functionality.md)  
[Finance](../../finance.md)
