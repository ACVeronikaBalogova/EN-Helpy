---
title: Czech Local Functionality Check of Posting Group changing – Customer, Vendor, item, bank account
description: The following topics describe the local functionality Check of Posting Group changing – Customer, Vendor, item, bank account in the Czech version of Business Central.
author: v-pejano

ms-service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Finance, Localization, CZ
ms.date: 01/23/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Check of posting group changing - customer, supplier, goods, bank account

The standard functionality has been upgraded to include checks in case of a request to change posting groups for customer, supplier, goods and bank accounts.

|Tab|Description|
|-|-|
|Customer tab|Change the customer's posting group on the Customer tab. If there are no open customer items, the Customer Posting Group can be changed. If there are open customer items, then the Customer Posting Group can't be changed.|
|Supplier tab| Change the supplier's posting group on the Supplier tab. If there are no open supplier items, then the Supplier Posting Group can be changed. If there are open supplier entries, then the Supplier Posting Group cannot be changed.|
|Item tab|On the Item Card, change the posting group of the item. If there are open goods items, then the Posting group can't be changed. If there are no open items and at the same time if there are uninvoiced closed items, then the Posting Group can't be changed. If there are no open goods items and there are no uninvoiced closed goods items, then the posting group can be changed.|
|Bank account tab|Change the bank posting group on the Bank Account Card. If the Balance or Balance (LM) is non-zero, then the bank posting group can't be changed.|

## See also

[Core localization pack extensions](ui-extensions-core-localization-pack-cz.md)  
[Czech local functionality](czech-local-functionality.md)  
[Finance](../../finance.md)  
