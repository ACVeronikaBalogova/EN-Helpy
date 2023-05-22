---
title: Czech Local Functionality - Multi Circuit Accounting 
description: The following topics describe the local functionality Multi Circuit Accounting in the Czech version of Business Central.
author: v-pejano

ms-service: dynamics365-business-central
ms.topic: article
ms.search.keywords: CZ, Czech, Localization, Finance  
ms.date: 05/12/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Groups of financial accounts - Multi-entity posting

According to accounting standards, an entity can post accounts under several accounting headings (Financial, Off-Balance Sheet and Corporate Accounting). You can mark the accounts that are relevant to you in this way.

To set up accounting circuits in the system:

1. Choose the![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what do you want to do"), enter **Chart of Accounts** and then select related link.
2. Open the tab of the selected financial account.
3. On the Financial Account tab, in the General tab, select in the field **Financial account group** one of the options:
    - Financial account
    - Intra-company account
    - Off-balance sheet account
4. Close the tab after setting up.

The posting is then checked and the system stops posting if financial accounts from different accounting headings are posted within the same accounting transaction.

## See also

[Core Localization Pack for Czech Republic](ui-extensions-core-localization-pack-cz.md)  
[Czech local functionality](czech-local-functionality.md)  
[Finance](../../finance.md)
