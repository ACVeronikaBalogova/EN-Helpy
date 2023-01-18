---
title: Advance Payments activation and upgrade
description: This section describes Advance Payments Localization for Czech extension functionality.
author: v-pejano

ms.service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Advance Payments, Localization
ms.date: 01/11/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Activation of Advance Payment functionality and upgrade of existing data  

Activation of the Advance Payments for Czech Republic functionality is initiated via **Feature Management**. Activation is done in 2 steps - user permission and data update. The data update will upgrade the existing backup items and related agendas to the new tables.  

> [!NOTE]
>The data update process is **non-reversible**. Once the update is complete, the previous version of the backups will no longer be available and you will not be able to return to the original version of the backups.

Depending on whether or not the data is converted, either objects in the database will be available in the " outdated " version - e.g. Sales Backups (outdated), or " new " - e.g. Sales Backups.  

![Feature Management](Media/AdvP-Activate.png "Feature Management")

To activate the Advance Payments for Czech Republic functionality, use the following steps:

1. Select icon ![Lightbulb, which opens Tell me function](../../media/ui-search/search_small.png "Tell me, what you want to do"), enter **Feature Management** and then select the related link.
2. The **Feature Management** window will open.
3. Select the row for the function **Localization of advance payments for the Czech version** and in the field **Allowed for** select All users.
4. You will then go through the activation guide and data update settings.
5. Once the data has been upgraded from the previous backup version, the value of the **Current Company Status** field will be set to Data Upgrade Complete. From this point on, you can use the new version of the Advance Payments functionality.  

## See also

[Advance payments for the Czech Republic (extension)](ui-extensions-advance-payments-localization-cz.md)  
[Czech local functionality](czech-local-functionality.md)  
[Finance](../../finance.md)
