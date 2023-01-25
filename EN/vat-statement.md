---
title: Czech Local Functionality - VAT statement 
description: This functionality describes improvements that the VAT Statement report contains.
author: v-makune

ms-service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Finance, VAT, Localization, CZ
ms.date: 01/24/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---


# VAT statement

The VAT statement contains a number of improvements and options:

- Stat. Reporting Setup with general settings for VAT reporting added.
- Two new line operations in the type field (Row Division and Row Multiplication) added.
- Settings for VAT on advances added.
- Filter the VAT Entries for the VAT Statement according to the Intermediate Trade mode in the EU. This step is necessary because Intermediate Trade (intermediary - 1 debtor) in the EU must be recorded on separate lines.
- Print the VAT Statement with a new option to round the calculated amounts in the VAT Statement to whole values.
- Filter data based on VAT Date using VAT Period.
- Filter data for older posted VAT Statements.
- Other types of VAT Statement - Standard, Subsequent, Supplementary - according to Section 43 (1) of the VAT Act 235/2004) the taxpayer may submit a supplementary VAT Statement (see below).
- Export VAT Statement into .xml file.
- Add comments and attachments to the export for the tax office.

## See also

[Core Localization Pack for Czech Republic](ui-extensions-core-localization-pack-cz.md)  
[Czech Local Functionality](czech-local-functionality.md)  
[VAT Control Report](how-to-create-vat-control-report.md)  
[VAT Date](how-to-setup-vat-date.md)  
[Finance](../../finance.md)  
