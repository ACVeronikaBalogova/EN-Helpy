---
title: Czech Local Functionality - Automatic Creation and Update of Dimensions
description: This section describes local functionality - Automatic creation and update of dimensions in the Czech version of Business Central.
author: v-pejano

ms-service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Finance, Localization, CZ
ms.date: 05/10/23
ms.reviewer: v-pejano
ms.author: v-makune
---

# Automatic creation and update dimensions

Allows you to set the automatic creation of default dimension values according to predefined parameters.

## Settings for creating and updating dimensions

Settings for creating and updating dimensions  is set by the following steps:

1. Choose the ![Lightbulb that opens the Tell me Feature](../EN/Media/search_small.png "Tell me what you want to do"), enter **Dimensions** and then choose the related link.
2. Create new dimension.
3. Select the row with the new dimension, click **Account Type Default Dim.**.
4. In the **Table ID** field, type the table number.
5. In the **Value posting** field, select **Code required**. This step sets the necessity to fill the dimension when posting for the table record.
6. Next, select the **Automatically create** field. After this setting, when a new record is created, the new dimension will also be created.
7. To set the dimension description so that only numbers or codes are not recorded, use the **ID field of the dimension description field**. Select a field here, for example the number **3 - Description**.
8. The next step in the setup is **Dimension Description Update** with the option ***Update or Create***. In the first case, the dimension description will automatically change according to the record description. In the second case, the name will not change if the dimension name is manually overwritten.
9. At this point, when the record is created, the description of the record is transferred to the dimension description.
10. To set the dimension description template, use the **Dimension Description Format** field, where for example you can use ***"Record - %1"***.
11. If you want to always post a newly created dimension within the record, set the **Automatic Cr. Value Posting** field to **Same Code**.
12. If you want to add dimensions to existing projects according to the new settings, use the **Automatically Update Default Dimensions** on the **Default Account Type Dimensions** report.

## Use, create and update dimensions

As an example, we will show the setup and application on the projects.

1. Choose the ![Lightbulb that opens the Tell me Feature](../EN/Media/search_small.png "Tell me what you want to do"), enter **Dimensions** and then select the related link.
2. **Create new Dimension** for example *"Project"*.
3. Select the row with the **Project** dimension, click the **Default Account Type Dimensions** button.
4. Enter the number **167** (Projects) in the **Table ID** field.
5. In the **Value posting** field, select **Code required**. This step sets the necessity of filling in the dimension when posting to the project.
6. Next, select the **Automatically create** field. This setting will also create a new dimension when you create a new project.
7. To set the dimension description so that only numbers or codes are not recorded, use the **ID field of the dimension description field**. Select field number **3 - Description** here.
8. The next step in the setup is **Update Dimension Description** with the option ***Update or Create***. In the first case, the dimension description will automatically change according to the project description. In the second case, the name will not change if the dimension name is manually overwritten.
9. At this point, when the project is created, the project description is transferred to the dimension description.
10. To set the dimension description template, use the **Dimension Description Format** field, where for example you can use ***"Project - %1"***. Now when you create a "Production Line" project, the dimension name will be *"Project - Production Line "*.
11. If you want to always post to a newly created dimension within the project, set the **Accounting value for automatic creation** field to **Same code**.
12. If you want to add dimensions to existing projects according to the new settings, use the **Automatically Update Default Dimensions** on the **Default Account Type Dimensions** report.
13. After setting up, close the reports.

## See Also

[Core Localization Pack for Czech Republic](ui-extensions-advanced-localization-pack-cz.md)  
[Czech Local Functionality](czech-local-functionality.md)
