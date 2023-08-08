---
title: Czech Local Functionality Extended User Control 
description: The majority of companies in the Czech Republic request the following improvements to be implemented in user setup and control.
author: v-pejano

ms-service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Finance, Localization, CZ
ms.date: 05/26/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Advanced user controls

The Advanced User Checks functionality allows you to set various checks, restrictions and accesses using **User Settings** in combination with **User Settings Lines**. This tool can be used for additional settings where everything cannot be covered by user rights, or for very specific settings for a selected user.

Typical examples include limiting the receipt posting to a selected location, posting to selected dimensions, or just checking the posting date of a document.

An example of the options can be found below:

|Check|Description|
|-|-|
|**Setting the Responsibility Center filter** | Setting up the Cash Accountability Center for cash desk transactions. |
|**Check document dates**| Check when posting against a work date or system date. |
|**Check the Posting date** | Check when posting against a work date or system date. |
|**Check access to payment orders** | Check allowed Bank accounts for payment orders (settings in rows). |
|**Check access to bank statements** | Checking Allowed Bank Accounts for Bank Statements (settings in rows). |
|**Check bank accounts** | Enabled for posting (settings in rows). |
|**Check access to Journal Templates** | Check the enabled template for all types of journals (settings in rows). |
|**Check dimension values** | Permissions for posting (settings in rows). |
|**Check warehouse locations** | Enable to post separately for quantity increase and quantity decrease (setting in rows). |
|**Check warehouse locations** | Permission to issue separately for quantity increase and quantity decrease (setting in rows). |
|**Check the use of Invt. Movement templates** | Check for posting in the Item Journal. |
|**Enable closed period posting** | Allows posting in closed period. |
|**Allow job completion** | Allows job completion. |
|**Allow Item Unapply** | Allows cancellation when settling items. |

## Setting up checks (Checking receipt posting at a selected location)

1. Choose the ![Lightbulb that opens the Tell me Feature](../EN/Media/search_small.png "Tell me what you want to do"), enter **User Setup** and then choose the related link.
2. Select the user for whom you want to set or edit controls and click **Card**.
3. On the posting tab, select one of the options, for example the **Check Location Code** field.
4. On the **User Settings tab**, select the **Rows** function to define a controlled value.
5. On the **User Settings Lines** page, you can select what to check. In this case, for example, **Location (Increase Quantity)** and select the appropriate location.
6. After this setting, combined with the check on **User Settings Card** enabled, the user will be allowed to charge the receipt of items to the selected location.
7. If you want to disable the check, just select the check field on the **User Settings tab** and remove the selection, in this case **Check Location Code**.
8. After setting the checks, you can close the page.

## See Also

[Core Localization Pack for Czech Republic](ui-extensions-core-localization-pack-cz.md)  
[Czech Local Functionality](czech-local-functionality.md)  
