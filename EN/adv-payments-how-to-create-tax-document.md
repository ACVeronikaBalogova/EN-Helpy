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

# Creating a tax document for an advance invoice

## Automatic charging of VAT on advance invoice

If the **Automatically post VAT document** field in the sales advance header is set to **YES**, the advance tax document and the VAT entry are automatically created when the sales advance payment is posted.

The entry **VAT payment** is entered into the advance history, in which the VAT base and amount are filled in.

### Printing a VAT document for an advance invoice

To print a VAT document for an advance invoice, proceed as follows:

1. Choose the ![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what you want to do"), enter **Sales Advance Invoice** and then choose the related link.
2. On the sales advance invoice list, mark the line with the required advance.
3. Select **Advance Entries** in the **History** section. Use the cursor to mark the row with the entry type **VAT payment**. Next, use the **VAT document** function in the Reports section to print a VAT advance document with the VAT breakdown.

- If more than one VAT rate is applied to the deposit, a separate **VAT Payment** entry will be created for each rate. If only a part of the advance has been paid for the advance set up in this way, the **VAT payment** entries will be created in proportion.
- When the deposit is paid in full, the **Advance Status** field changes to **To Use**. For partial payments, the value in the Advance Status field remains **To be used**. The advance payment can be applied to the invoice up to the amount paid, even if it has not yet been paid in full.
- The advance VAT document is posted with the document number according to the No. series set in the advance VAT document No. series field in the advance VAT document template.

## Manual posting of a VAT document

If the **Automatically post VAT document** field in the sales advance header is set to **NO**, an advance tax document will not be automatically created when posting the sales advance payment. The advance can still be used in the final sales invoice.

However, if you want to post the VAT document for payment, it is possible to start the creation and posting of the advance VAT document from the history from **Advance entries**.

### Manual creation of a VAT document

To manually create a VAT document, proceed as follows:

1. Choose the ![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what you want to do"), enter **Sales Advance Invoice** and then choose the related link.
2. On the sales advance invoice list, mark the line with the required advance.
3. Select **Prepaid Entries** in the **History** section. Use the cursor to mark the row with the entry type **VAT payment**.
4. From the action bar, run the **Post VAT document** action. The advance payment entry **VAT payment** (and the related VAT and G/L entries) will be created with the same Posting date as the cleared payment.

- If the value in the **Automatically post VAT document** field of the advance invoice is **NO** even when posting the invoice associated with this advance, the advance will not be automatically de-taxed and will need to be de-taxed manually. The value in the field can be additionally adjusted before the invoice is posted- if you set **Automatically post VAT document** to **NO**, the advance will be deaned when the invoice is posted.
- If an advance has been applied but not deferred when posting the final invoice, the deferral can be done manually afterwards.

### Manual deduction of VAT on advance payment

To manually deduct VAT from the advance, proceed as follows:

1. Choose the ![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what you want to do"), enter **Sales Advance Invoice** and then choose the related link.
2. On the sales advance invoice list, mark the line with the required advance.
3. Select **Advance Entries** in the **History** section. Place the cursor on the **Use** type item and select the **Post VAT usage** action. This will separate the advance with the date and document number of the invoice posted.

## See Also

[Extension Advance Payments Localization](ui-extensions-advance-payments-localization-cz.md)  
[Czech Local Functionality](czech-local-functionality.md)  
[Finance](../../finance.md)
