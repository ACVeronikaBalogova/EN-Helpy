---
title: Czech Local Functionality - Two steps Fixed Asset acquisition | Microsoft Docs
description: There are two steps to accomplish when acquiring a fixed asset in Czech accounting. This function describes them.
author: v-pejano

ms-service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Fixed Asset, Localization, CZ
ms.date: 01/25/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Two-step acquisition of fixed assets

According to Czech accounting, two steps must be taken when acquiring fixed assets. If a company receives an invoice for the acquisition of fixed assets, it must be posted. Fixed assets are posted from the moment they are first acquired. Both the acquisition and the classification are required and linked to the G/L Entry. Fixed assets are not depreciated until they are classified.

For this procedure, use the **Custom 2** posting type for the first step (**Acquisition**) and the fixed asset **Acquisition** posting type for the second step (**Classification**). To begin using this feature, check the **Acquisition of Fixed Assets as Custom 2** box in **FA Setup**.
The value "Custom 2" is renamed to "Acquisition" in Czech for proper identification and more intuitive understanding.

## See Also

[Fixed Assets for Czech Republic](ui-extensions-fixed-asset-localization-cz.md)  
[Czech Local Functionality](czech-local-functionality.md)  
