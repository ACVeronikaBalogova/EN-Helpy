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

# Conclusion of the advance invoice  

If an invoice paid in advance is not drawn down or exhausted, it may be closed. The function to close the advance is available on the Sales/Purchase tab of the advance invoice (i.e. not from the advance history items), it is the **Close Advance** function.

To close the advance, follow these steps:

1. Select icon ![Lightbulb, which opens Tell me function](../../media/ui-search/search_small.png "Tell me, what you want to do"), enter **Sales Advance Invoices** and then select the related link. For purchases, look for **Purchase Advance Invoices**.
2. Open the required backup tab.
3. Select **Close Advance** in the action bar.
4. When you close an advance, you can select the date on which the advance will be closed in the Advance Closure Dialog. When closing, the VAT is settled, and a **VAT Closure** entry is created for the advance tax credit. From entry **VAT Closure** it is possible to print the tax credit. For entry **Closure** and **VAT Closure** the number series set in the advance templates in the field for the number series of advance tax credits is used.

The undrawn amount of the advance will be transferred to the customer's balance in the form of an open customer item.  
When an advance is closed, a negative Original Entry is automatically created so that the amount of the advance to be paid is zero (the initial Original Entry minus the payments plus the closing amount).

## See also

[Advance payments for the Czech Republic (extension)](ui-extensions-advance-payments-localization-cz.md)  
[Czech local functionality](czech-local-functionality.md)  
[Finance](../../finance.md)
