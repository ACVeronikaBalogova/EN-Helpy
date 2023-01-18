---
title: Advance Payments activation and upgrade
description: This section describes Advance Payments Localization for Czech extension functionality.
author: v-pejano

ms.service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Advance Payments, Localization
ms.date: 10/01/2021
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Creating an advance invoice

To Pro přímé založení zálohové faktury pustupujte následujícím způsobem:

1. Select icon![Lightbulb, which opens Tell me function](../../media/ui-search/search_small.png "Tell me what do you want to do"), enter **Sales advance Invoice** and then select related link. For purchasing look for **Purchases Advance Invoice**.
2. In the overview create new document by using the function **New**.
3. At the new document select **Advance template**, which will be used for document numbering, work method, work method with VAT, posting method etc.
4. Confirm entry **Number**, which creates an advance payment document in the relevant number series.
5. In the advance tab assign **Customer number**.
6. In the advance field enter **Invt. Posting Group** and **Total amount of the Advance**.
7. Default state of an advance is **New**, i.e. it can be changed in any way, it cannot be paid or used in an invoice. Use the **Release** function in the action bar to move to the **To be paid** state. The deposit will be ready for payment.  
The release creates an **Original Item** in the advance items with a date according to the settlement date in the advance header and the total amount entered at the time of release. The original entry has no accounting context, it is used to calculate the amount remaining to be paid.
8. You can print the advance using the action **Assembly– Advance** or generate as a PDF attachment using the **Assembly - Attach as PDF** action.
9. If an advance needs to be edited, you can use the **Re-open** function to bring it back to the **New** state and edit it.
A negative **Original item** is automatically created in the advance items.
10. In the advance FactBox it is possible to keep track of the value of the advance payment, the amount remaining to be paid, the amount remaining to be used and the overall record of the advance payment in terms of the VAT base and amount.

## See also

[Advance payments for the Czech Republic (extension)](ui-extensions-advance-payments-localization-cz.md)  
[Czech local functionality](czech-local-functionality.md)  
[Finance](../../finance.md)
