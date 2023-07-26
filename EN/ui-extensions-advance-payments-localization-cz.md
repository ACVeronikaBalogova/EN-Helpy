---
title: Advance Payments Localization for Czech (Extension) 
description: This section describes Advance Payments Localization for Czech extension functionality.
author: v-pejano

ms.service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Finance, Localization
ms.date: 05/22/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Advance payments for the Czech Republic (extension)

Extension **Advance payments** in [!INCLUDE[prodshort](../../includes/prodshort.md)] is used for creating invoices and making payments before delivery of the items or service. The Advance Payments solution helps companies meet the legal requirements for recording and posting advances, including VAT requirements in the Czech Republic.

Advance Payments functionality allows you to receive advance invoices from vendors, issue advance invoices to customers, to make advance payments, including payments subject to VAT, and to draw down advance payments on receipts. It also provides tax documents required by legislation, outputs for financial reports and VAT reports.

**The module includes:**  

- Sales and purchase invoices
- Advanced payments, recieved and issued
- Tax documents and tax credits for advance payments received or issued

**Main module functions:**  

- Creating sales or purchase advance invoices according to the settings of the advance invoice templates
- Create advances from sales orders based on a percentage or amount entered
- Proposal of advances in the payment order and, on the other hand, payment of advances by the bank
- Connection with the Cash desk module for the possibility of paying cash advances with cash
- Issue and print advance tax documents for advance payments automatically or manually
- Managing the use of advance payments with the final invoice
- Possibility of closing the unused advance, including tax settlement
- Working with foreign currency, exchange rate differences between advance payment and invoice
- Option to unassign payment of an advance invoice or additional linking
- Option to unlink final invoice to advance payment or additional linking
- Reports for recapitulation of advance payments and drawdowns, reports for recapitulation of VAT on advances  

**Restrictions of application:**  

- Use of one currency within a single business case
- The creation of advance invoices from documents or the additional allocation of free advance invoices to a document does not take into account billing or discounting
- Advances cannot be used on credit notes and return orders (resolved by detaching the advance from the invoice posted and crediting the invoice without advances)
- The service module does not work with advances
- The advances do not address additional currency
- The application does not include support for changing VAT rates

The following table describes the list of tasks with links to the topics that describe them.

| Function | link |
| --- | --- |
|Activate Advanced payments and upgrade current data.|[Activate and upgrade advanced payments](adv-payments-how-to-activate-advance-payments.md)|
|Understand the basic principles of Advance Payments, the advance payment life cycle. |[Basic principles of the posting and use of advance payments](adv-payments-principles.md)|
|Set up advance payment templates, VAT posting and VAT statement.|[Set up advance payments](adv-payments-how-to-setup-advance-payments.md)|
|Creating an advance invoices and print.|[Create an advance invoice](adv-payments-how-to-create-advance-invoice.md)|
|Creating an advance from an order.|[Create advance invoice from order](adv-payments-how-to-create-advance-invoice-from-order.md)|
|Advance payment by financial journal or cash desk.|[Advance payment](adv-payments-how-to-pay-advance-payment.md)|
|Creating a tax document for a deposit, correcting VAT on a purchase advance, printing the document.|[Create tax document for and advance](adv-payments-how-to-create-tax-document.md)|
|Creating the final invoice, linking it to the advance and posting it.|[Link advance to final invoice](adv-payments-how-to-link-invoice.md)|
|Closure of unused advance.|[Close advance payment](adv-payments-how-to-close-advance-payment.md)|
|Foreign currencies and advance invoices.|[Advance payment in foreign currency](adv-payments-foreign-currency.md)|
|Cancellation of an advance tax document, disconnection of an incorrect payment from the advance, additional connection of the payment to the advance, connection of the advance to an already booked invoice, disconnection of the advance from the booked invoice.|[Additional functions](adv-payments-additional-functions.md)|
|Overview of advance invoices, VAT on advance invoices, recapitulation of advance invoices.|[Check advance reports](adv-payments-check-reports.md)|

## See also

[Czech local functionality](czech-local-functionality.md)  
[Finance](../../finance.md)
