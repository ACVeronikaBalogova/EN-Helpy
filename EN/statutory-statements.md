---
title: Czech Local Functionality - Statutory Statements
description: This feature provides the reports - Balance Sheet, Income Statement.
author: v-makune

ms-service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Finance, Localization, CZ
ms.date: 12/01/2020
ms.reviewer: v-pejano
ms.author: v-pejano
---


# Statutory statements

Companies must prepare financial statements in accordance with the Accounting Act No. 563/1991.  They must produce a balance sheet and a profit and loss account.
This function provides the following statements:

- Balance Sheet
- Profit and Loss Account

These statements use Account Schedule with a defined structure of statutory statements.

In the table **Account Schedule name** a new field has been added in the Czech version:

- **Account Schedule Type** – Balance Sheet or Profit and Loss Account

New fields have been added to the **Account Schedule line** in the Czech version:

- **Row Correction** – link to another line for the preparation of the Balance Sheet
- **Asset/Liabilities type** – Assets or Liabilities for the preparation of the Balance Sheet
- **Calculate** - Always, Never, Positive, Negative

The Balance Sheet and Profit and Loss Statement are often prepared in Excel file templates with the necessary appearance for printing the statement. Users want to be able to map defined Account Schedule to prepared Excel templates.

For the above reasons, this feature provides new Excel template settings and statement entries mapping. Based on these settings, users can export Account Schedules data to an Excel file.

## See Also

[Core Localization Pack for Czech Republic](ui-extensions-core-localization-pack-cz.md)  
[Czech Local Functionality](czech-local-functionality.md)  
[Company Statutory Information](statutory-company-information.md)  
[Finance](../../finance.md)  
