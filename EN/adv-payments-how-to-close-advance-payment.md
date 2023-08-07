---
title: Advance Payments activation and upgrade
description: This section describes Advance Payments Localization for Czech extension functionality.
author: v-pejano

ms.service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Advance Payments, Localization
ms.date: 02/24/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Conclusion of the advance invoice  

If an invoice paid in advance is not drawn down or exhausted, it may be closed. The function to close the advance is available on the Sales/Purchase tab of the advance invoice (not from the advance history entries), it is the **Close Advance** function.

To close the Advance, proceed as follows:

1. Choose the ![Lightbulb that opens the Tell me Feature](media/search_small.png "Tell me what you want to do"), enter **Sales Advance Invoice** and then choose the related link. In case of purchase, look for **Purchase Advance Invoice**.
2. Open the Advance Card.
3. In the action bar, select **Close Advance**.
4. When you close a Advance, you can select the date on which the Advance will be closed in the Advance Closure Dialog. When closing, the VAT is settled, and a **VAT Closing** entry is created for the advance tax credit. From the **VAT Closing** entry, the tax credit can be printed. For both **Closing** and **VAT Closing**, the No. series set in the advance tax credit No. series field in the advance tax credit templates is used.

The undrawn amount of the advance will be transferred to the customer's balance in the form of an open customer entry.  When a advance is closed, a Negative Source Entry is automatically created so that the amount of the advance to be paid is zero (the initial Source Entry minus the payments plus the closing amount).

## See Also

[Advance Payments localization for Czech Republic](ui-extensions-advance-payments-localization-cz.md)  
[Czech Local Functionality](czech-local-functionality.md)  
[Finance](../../finance.md)
