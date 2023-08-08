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

# Linking the advance invoice to the final document

## Use of the advance invoice in the final invoice

To use an advance invoice in the final invoice, proceed as follows:

1. Enter the invoice into the system in the usual way. If you wish to attach one or more advances to the invoice, do so from the invoice header using the **Link Advance Invoice** action.
2. On the **Advance Reconciliation** page use **New** and click the **Advance No.** field to view the list of advances available for assignment to the invoice. Only advances with the same currency code and in amounts that have been paid no later than the posting date of the sales invoice are displayed. Confirm the advance selection and the advance will transfer to the **Advance Reconciliation** page to link the invoice and the advance.
In this way, you can continue with the selection of advances. Click the next line on the page to add more advances to the link again using the Advance Number field.
3. In the **Amount** field, you can specify the amount and from which advance to be invoiced. It is thus possible to draw multiple advances in partial amounts to the invoice.
4. If the advance assignment is set up the way the user wants to use the advances in the invoice, confirm the page with the **OK** button.

Note:

- The advance will always be deducted up to the maximum possible invoice value, i.e. even if the user does not reduce the value of the advance and the advance exceeds the invoice value, the advance will be deducted up to the maximum invoice value.
- If the user selects a partial drawdown of the advance, only the set portion will be deducted from the advance.
- If the user selects partial drawdown from multiple advances and the value of the advances to be used is higher than the invoice value, the system will automatically deduct the amounts from the advances according to the date the advances were paid.
- If the advance assignment is set up the way the user wants to use the advances in the invoice, confirm the page with the OK button.

## Information on the use of the advance invoice in the final document

- In the new **FactBox** of the sales invoice in the **Sales Advance Usage** section you can see the number of used advances, their numbers, references to VAT entries and the total amount of the invoice after deduction of advances.
- Standard document statistics do not include advances. However, it is possible to run a posting preview that will show all entries, including deposit entries, that will be generated during posting.

## Disconnecting the advance invoice from the final invoice

if the advance is not to be used on the invoice, it can be removed from the link:

1. Choose the ![Lightbulb that opens the Tell me Feature](../EN/Media/search_small.png "Tell me what you want to do"), enter **Sales Advance Orders** and then choose the related link.
2. Open the selected advance invoice, use the **Link Advance Invoice** action to open the page with the linked advances.
3. On the page you can edit the amounts or remove the entire line with the advance. You should always check that the page is in editable mode and the line edits will be recorded.
4. Select **Delete** via the selection button (three dots) and confirm the deletion of the line with the associated advance invoice.
After posting an invoice with an advance payment, an entry with Entry Type **Use** is created on the advance payment in the amount deducted from the invoice, and if an advance VAT document has been posted with the payment, an entry **VAT Use** with VAT deduction is automatically created.

You can print a tax credit note from the Advance History from the **VAT Usage** entry type.
The **VAT Usage** entry is created with the same date and document number as the sales invoice.

## Using an advance invoice created from an order

- If the advance is created from a purchase order, no settings modification is needed to use the advance from the purchase order.
- If an advance VAT document is created for the advance, when the invoice is posted, the advance is automatically taxed and an advance VAT credit is created.
- As with the invoice, the **FactBox** of the **Use of Sales Advance** order shows the number of linked advances, references to VAT and the total invoice amount after deduction of the advance.
- An order can be delivered and invoiced even if the deposit is not paid on the order posting date. The user is notified of this fact and can decide whether or not to post the document.
- If an advance created from an order is not paid and the order is posted and invoiced, the link between the order and the advance will be automatically broken and the advance can be used (after payment) for another final invoice.

## See Also

[Advance Payments localization for Czech Republic](ui-extensions-advance-payments-localization-cz.md)  
[Czech Local Functionality](czech-local-functionality.md)  
[Finance](../../finance.md)
