---
title: Czech Local Functionality - Setup VAT date
description: This section describes Czech local functionality - VAT Date and Setup of the VAT Date Feature.
author: v-pejano

ms-service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Finance, VAT, Localization, CZ
ms.date: 12/01/2020
ms.reviewer: v-pejano
ms.author: v-pejano
---


# VAT Date

The VAT Date is important for tax documents according to Section 28 of the VAT Act 235/2004 Coll. The VAT Date may differ from the date of posting or the date of the document. The VAT Date is an important field for VAT reporting.

This feature focuses on improving the following areas:

## Nastavení použití Data DPH

- Obecné povolení používání Data DPH v systému.
- Výběr způsobů, jakým systém bude zobrazovat výchozí hodnotu Data DPH v různých oblastech (Zúčtovací datum nebo Datum dokladu).
- Období pro vykazování DPH a účetní období společnosti se mohou často lišit. Abychom umožnili uživatelům bezproblémově vykazovat a účtovat DPH podle období pro vykazování DPH a také vydávat interní a další statutární vykazování na základě účetních období, zavádí tato funkce nově Období DPH.
- Povolit účtování DPH od/do – zadání časové období v polích od/do, aby se zabránilo chybám účtování do uzavřených účetních a DPH období.Posting of transactions with a VAT Date 

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
