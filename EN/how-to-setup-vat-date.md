---
title: Czech Local Functionality - Setup VAT date
description: This section describes Czech local functionality - VAT Date and Setup of the VAT Date Feature.
author: v-pejano

ms-service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Finance, VAT, Localization, CZ
ms.date: 01/24/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---


# VAT Date

The VAT Date is important for tax documents according to Section 28 of the VAT Act 235/2004 Coll. The VAT Date may differ from the date of posting or the date of the document. The VAT Date is an important field for VAT reporting.

This feature focuses on improving the following areas:

## Setting up the use of VAT Date

- General permission to use VAT Date in the system.
- Select how the system will display the default VAT Date value in different fields (Posting Date or Document Date).
- The VAT reporting period and the company's accounting period may often differ. To enable users to effortlessly report and post for VAT based on VAT reporting periods, as well as issue internal and other statutory reporting based on accounting periods, this feature newly introduces VAT Periods.
- Enable from/to VAT Posting - enter the time period in the from/to fields to avoid posting errors to closed accounting and VAT periods.

### Posting of transactions with a VAT Date

To post transactions using the VAT Date, the user must be able to enter the VAT Date in the application in the Document Headers and Journal Lines.
After posting, the VAT Date is included in the posted documents, G/L entries and VAT Entries.

### Calculation and posting of VAT Settlement

The system filters the VAT entries based on the VAT date (instead of the Settlement Date) by selecting the VAT period and prepares a report showing which entries will be transferred to the VAT Settlement account. The printout also contains the VAT Date information.

## See Also

[Core Localization Pack for Czech Republic](ui-extensions-core-localization-pack-cz.md)  
[VAT Control Report](how-to-create-vat-control-report.md)  
[VAT Statement](vat-statement.md)  
[Finance](../../finance.md)  
