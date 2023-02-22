---
title: Czech Local Functionality - Fixed asset posting of Disposal | Microsoft Docs
description: Czech accounting standards require specific posting when a fixed asset is being disposed of or being sold.
author: v-pejano

ms-service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Fixed Asset, Localization, CZ
ms.date: 01/25/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Posting for disposal of assets

Czech accounting standards require specific posting when tangible assets are disposed of or sold. After the sale or posting of the disposal of a fixed asset (FA), posting of the disposal of the asset ensures that the value of the fixed asset remains the same as the value after the write-off.

Fixed assets remain unchanged after classification. If fixed assets are depreciated periodically, the corresponding amount is deducted from the cost of acquisition at the time of disposal. The balance amount is the current value of the fixed asset.

In the Depreciation book, check the box for **Matching G/L Entries on disposal** to make this feature functional. Select the **Match FA entry on disposal** checkbox to maintain consistency between G/L Entries and FA Entries.

## See Also

[Fixed Assets for Czech Republic](ui-extensions-fixed-asset-localization-cz.md)  
[Czech Local Functionality](czech-local-functionality.md)  
