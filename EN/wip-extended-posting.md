---
title: Czech Local Functionality - WIP Extended Posting 
description: This section describes local functionality - WIP Extended Posting.
author: v-makune

ms-service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, WIP, Finance, Extended Posting, Localization, CZ
ms.date: 12/01/2020
ms.reviewer: v-pejano
ms.author: v-pejano
---


# Extended posting for work in progress

 This functionality enables correct posting of production consumption, activation/deactivation of work in progress and changes in the status of products/semi-finished goods according to Czech accounting procedures. It allows you to set up financial accounts for consumption, change in work in progress and change in semi-finished goods and products for combinations of Warehouse Location and Inventory Posting Groups.

The new posting system is used for the following transactions:

- Consumption Posting in Consumption Journal
- Posting Costs of Production Operations and Product Receipts in Output Journals.
- Completion of production orders.

Rounding Account in **General Posting Setup** allows you to post all costs from rounding inventory movements (Value Entries with Entries Type=Rounding) to a G/L Account other than the Inventory Adjmt. Account. Using the **Rounding Date** field in **G/L Setup** allows you to control the posting date of the rounding entry.

Czech legislation uses the following G/L accounts in posting for production operations:

- Consumption Account.
- Change Status in work in process.
- Change Status in Product.

## See Also

[Czech local functionality](czech-local-functionality.md)  
