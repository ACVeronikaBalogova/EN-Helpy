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

# Creating an advance invoice

To create an advance invoice directly, proceed as follows:

1. Choose the ![Lightbulb that opens the Tell me Feature](../EN/Media/search_small.png "Tell me what you want to do"), Enter **Sales Advance Invoices** and then choose the related link. In case of purchase look for **Purchase Advance Invoices**.
2. Create a new document in the list using the **New** action.
3. In the new document, select the **Advance Template** which will be used for document numbering, VAT handling, posting method and more.
4. Confirm the **Number** field to create a advance document in the appropriate No. series.
5. Assign a **Customer Number** in the Advance Card.
6. In the advance line, enter **VAT posting group** and **Total advance amount**.
7. The default status of the advance is **New**, i.e. it can be changed in any way, it cannot be paid or used in an invoice. Use the **Pay** function in the action bar to convert it to the **To be paid** status. The advance will be ready for payment.
The issue creates an **Initial Entry** in the advance entries with a date according to the posting date in the advance header and the total amount entered at the time of issue. The initial entry has no posting relationship, it is used to calculate the amount remaining to be paid.
8. You can print the advance using the **Report- Advance** action or generate it as a PDF attachment using the **Report- Attach as PDF** action.
9. If the advance needs to be edited, you can use the **Reopen** function to bring it back to the **New** state and edit it.
A negative **Initial item** is automatically created in the Advance entries
10. In Advances FactBox, you can continuously monitor the value of the advance, the amount remaining to be paid, the amount remaining to be used and the overall record of the advance in terms of the VAT base and amount.

## See Also

[Advance Payments localization for Czech Republic](ui-extensions-advance-payments-localization-cz.md)  
[Czech Local Functionality](czech-local-functionality.md)  
[Finance](../../finance.md)
