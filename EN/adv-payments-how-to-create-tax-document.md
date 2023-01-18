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

# Creating a tax document for an advance invoice

## Automatic charging of VAT on advance invoice

If the **Automatically charge VAT document** field in the sales advance header is set to **YES**, the advance tax document and the VAT entry are automatically created when the sales advance payment is posted.

The item **VAT payment** is entered into the advance payment history, in which the VAT base and amount are filled in.

### Print the VAT document for the advance invoice

To print a VAT document for an advance invoice, use the following steps:

1. Select icon![Lightbulb, which opens Tell me function](../../media/ui-search/search_small.png "Tell me what do you want to do"), enter **Sales Advance Invoice** and then select related link.
2. On the sales advance invoice summary, mark the line with the required advance.
3. Select function **Advance entries** in section **History**. Use the cursor to mark the line with the item type **VAT Payment**. Next, use the function in the Reports section **Tax Document**, which you can use to print an advance tax document with a VAT schedule.

- If more than one VAT rate is applied to the advance, a separate entry is created for each rate **VAT Payment**. If only part of the deposit has been paid, the **VAT payment** items will arise on a prorated basis.
- When the advance is paid in full, the **Advance Status** field changes to **To Use**. In the case of partial payment, the value in the deposit status field remains **To be paid**. The advance can be applied to the invoice up to the amount paid, even if it has not yet been paid in full.
- The advance tax document is posted with the document number according to the number series set in the advance tax document number series field in the advance tax document template.

## Manual posting of a VAT document

If the field **Automatically charge VAT document** in the sales advance header is set to **NO**, no advance tax document is automatically created when charging the sales advance payment.The advance payment can also be used in this way in the final sales invoice.

However, if you want to post the VAT document for payment, it is possible to start the creation and posting of the advance tax document from the history from **Advance items**.

### Manual creation of a VAT document

To manually create a VAT document, proceed as follows:

1. Select icon![Lightbulb, which opens Tell me function](../../media/ui-search/search_small.png "Tell me what do you want to do"), enter **Sales advance Invoice** and then select related link.
2. On the sales advance invoice summary, mark the line with the required advance.
3. Select function **Advance items** in section **History**. Use the cursor to mark the line with the item type **VAT payment**.
4. From the action bar, run the **Count tax document** action. The advance payment item **VAT payment** (and the related VAT and in-kind items) will be created with the same settlement date as the cleared payment.

- If the value in the **Automatically charge VAT document** field of the advance invoice is **NO** even when charging the invoice associated with this advance, the advance will not be automatically taxed and will need to be taxed manually. The value in the field can be additionally adjusted before the invoice is charged - if you set **Automatically charge the VAT document** to **YES**, the advance payment will be deducted when the invoice is charged.
- If an advance has been applied but not deferred when posting the final invoice, the deferral can be done manually afterwards.

### Manual deduction of VAT on advance payment

To manually deducation of VAT proceed as follows:

1. Select icon![Lightbulb, which opens Tell me function](../../media/ui-search/search_small.png "Tell me what do you want to do"), enter **Sales advance Invoice** and then select related link.
2. On the sales advance invoice summary, mark the line with the required advance.
3. Select function **Advance items** in section **History**. Place the cursor on the item of type **Use** and select the action **Account for VAT use**. This will result in the deposit being separated with the date and document number of the invoice posted.

## See also

[Advance payments for the Czech Republic (extension)](ui-extensions-advance-payments-localization-cz.md)  
[Czech local functionality](czech-local-functionality.md)  
[Finance](../../finance.md)
