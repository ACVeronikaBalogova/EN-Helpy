---
title: Czech Local Functionality - Posting groups in Transfer Orders | Microsoft Docs
description: In the Transfer Orders functionality, fields for Gen. Bus. Post. Groups for Ship and Receive posting were added.
author: v-pejano

ms-service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Finance, Localization, Transfer Order, Transfer Route, CZ
ms.date: 01/25/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Posting group in Transfer Orders

Czech Accounting Standards require that transfers be posted with a prescribed Inventory Adjustment Account distinct from other journal entries.

In Transfer Routes, a field has been added to allow you to specify a general business group account for accounting for deliveries and receiving. These settings are automatically copied to the Transfer Order based on the Transfer Route used. This functionality allows you to post different Transfer Orders with different general posting settings and at the same time you can set different posting compared to the G/L Journal.  

## Transfer Route Settings

First, set the General Sales Account Delivery and General Sales Account Receiving fields for the Transfer Routes.

1. Choose the ![Lightbulb that opens  the Tell me feature (Alt + Q)](../../media/ui-search/search_small.png "Tell me what you want to do (Alt + Q)") search **Transfer Routes**.
2. Select the desired combination of transfer locations and open **Special Transfer Details**.
3. Fill in the required fields and the fields General trading account for delivery and General trading account for receipt.
4. Confirm with Close.

## Use

When creating a Transfer Order, the set posting groups are automatically inserted from the Transfer Routes for the corresponding combination of warehouses between which the items are transferred.

1. Choose the ![Lightbulb that opens the Tell me feature (Alt + Q)](../../media/ui-search/search_small.png "Tell me what do you want to do (Alt + Q)") search **Transfer orders**.
2. Click **New** to create a new Transfer Order.
3. Select the desired location in the **Transfer-from-code** and **Transfer-to-code** fields.
4. According to the Transfer Route settings, the fields **General Sales Account Delivery** and **General Sales Account Receipt** are automatically pre-filled. The user can change these default account groups as needed.
5. In the Transfer orders lines, fill required items and amount, which you want to transfer from one warehouse to another.
6. Warehouseman from first warehouse posts the delivery.
7. Warehouseman from second warehouse posts receiving.
8. It is possible to check the validity of the posting in the Material Items.

## See Also

[Advanced Localization Pack for Czech Republic](ui-extensions-advanced-localization-pack-cz.md)  
[Czech Local Functionality](czech-local-functionality.md)  
