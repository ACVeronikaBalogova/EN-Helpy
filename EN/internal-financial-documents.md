---
title: Czech Local Functionality - Internal Financial Documents
description: The following topics describe Internal Financial Documents - the local functionality in the Czech version of Business Central. Users perform General Ledger operations and must have the possibility to print documents for these operations with the layout in compliance with the legal requirements.
author: v-pejano

ms-service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, Finance, Localization, CZ
ms.date: 12/01/2020
ms.reviewer: v-pejano
ms.author: v-pejano
---


# Internal accounting documents

Users carry out posting transactions and must be able to print out documents with posting transactions that meet the requirements of the legislation in terms of appearance and content.

For the fore mentioned reasons, this function provides the following reports:

## General Journal - Test

Report that is used to check the entered internal document before posting from the General Journal.  

### Run the General Journal Report - Test

1. Choose the ![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Gen. Journal Template** and then choose the related link.
2. Choose Gen. Journal Template and fill out **ID report 11722 - General Journal - Test** field.
3. Přehled šablon finančního deníku můžete zavřít.
4. Choose the ![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **General Journals** and then choose the related link.
5. Choose the Journal template.
6. Fill out Internal Transaction Journal lines and then run report General Journal - Test by using button **Test report** and check the report output.

## General Ledger Document

A report that is used to check and print an posting operation that has been posted. The report can be printed out including dimensions.

### Run the General Ledger Document Report

1. Choose the ![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **General Journal Templates** and then choose the related link.
2. Choose the General Journal Template a vyplňte v poli **ID účtovací sestavy 11766 - Obecný účetní doklad**.
3. Přehled šablon finančního deníku můžete zavřít.
4. Vyberte ikonu ![Žárovky, která otevře funkci Řekněte mi](../../media/ui-search/search_small.png "Řekněte mi, co chcete dělat"), zadejte **Finanční deníky** a poté vyberte související odkaz.
5. Vyberte šablonu deníku.
6. Vyplňte řádky deníku interními transakcemi.
7. **Pro spuštění při účtování** použijte funkci **Účtovat a vytisknout** a zkontrolujte výstup reportu.
8. **Pro ruční spuštění** postupujte následovně:
    - Spustit a zkontrolovat výstup reportu Obecný účetní doklad s parametrem včetně dimenzí.
    - Spustit a zkontrolovat výstup reportu Obecný účetní doklad podle čísla věcné položky.
    - Spustit a zkontrolovat výstup reportu Obecný účetní doklad podle čísla dokladu.

## Viz Také

[Základní lokalizační balíček pro Česko](ui-extensions-core-localization-pack-cz.md)  
[Česká lokální funkcionalita](czech-local-functionality.md)  
[Finance](../../finance.md)  
