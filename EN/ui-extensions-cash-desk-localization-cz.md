---
title: Cash Desk Localization for Czech (Extension) | Microsoft Docs
description: The application covers the requirements of Czech legislation and best practices for Microsoft Dynamics 365 Business Central in the field of cash registers.
author: v-pejano

ms.service: dynamics365-business-central
ms.topic: article
ms.search.keywords: Czech, CashDesk, Finance, CZ, Cash
ms.date: 05/22/2023
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Liquid assets (extension)

V české verzi [!INCLUDE[d365fin](../../includes/d365fin_md.md)] pomáhá funkcionalita pokladen řešit legislativní požadavky a osvědčené postupy v pokladních operacích.

Funkcionalita pokladen a pokladních dokladů umožňuje definovat pokladní účty a pokladny pro fyzický příjem a výdej peněz. Každá pokladna musí mít samostatnou číselnou řadu pokladních dokladů. Pro pokladny je možné nastavit samostatné číselné řady příjmových a výdajových dokladů. Lze předdefinovat různé typy pokladních případů pro zjednodušení zadávání dokladů. Dále je možné nastavit uživatele zodpovědného za pokladnu a tuto zodpovědnost předávat mezi uživateli pokladny.  

## Klíčové funkcionality

- Nastavení pokladen, uživatelé pokladny
- Příjmové a výdajové doklady a jejich účtování
- Pokladní případy používané jako šablony obvyklých účetních případů
- Vyrovnání plateb s položkami zákazníků a dodavatelů
- Vyrovnání plateb se zálohovými fakturami
- Inventarizace pokladny
- Výstupní doklady (Příjmový pokladní doklad, Výdajový pokladní doklad)
- Sestavy (Pokladní kniha, Kniha pokladního účtu a Předání pokladny)

Karta pokladny obsahuje základní údaje o pokladně, jako jsou číslo, měna, kontaktní údaje apod. Dále obsahuje také nastavení pro účtování, definice pro kontroly a limity a přednastavení číselných řad pro pokladní doklady.

![Karta pokladny](Media/cash-desk.png)

Pokladní doklady jsou příjmové nebo výdajové a mohou být v různých měnách dle pokladny. Doklady dále umožňují vydání, účtování a tisk výstupních dokladů.

![POkladní doklad](Media/cash-desk-document.png)

## Nastavení uživatelů pokladen

1. Choose the ![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what you want to do"), enter **Cash Desk Setup** and then choose the related link.
2. Na stránce **Nastavení pokladen** v záložce **Navigace** použijte funkci **Uživatelé pokladny**.
3. Otevře se karta Uživatelů pokladen. Pro založení nového uživatele použijte funkci **Nový**.
4. V řádku vyberte **Číslo pokladny**, na které bude uživatel pracovat. Dále vyberte **ID uživatele** a vyberte, zda bude uživatel mít možnost **Vydat**, **Účtovat** nebo **Účtovat pouze EET**.
5. Po nastavení stránku zavřete.

## Nastavení číselných řad pro příjmové a výdajové doklady

1. Choose the ![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what you want to do"), enter **Cash Desk Setup** and then choose the related link.
2. Otevřete kartu vybrané pokladny.
3. Na **Kartě nastavení pokladny** naleznete v záložce **Číslování**.
4. V polích **Číslo příjmových pokladních dokladů** a **Číslo výdajových pokladních dokladů** vyberte číselnou řadu, kterou chcete použít.
5. Po nastavení kartu nastavení pokladny zavřete.

## Nastavení pokladních případů

1. Choose the ![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what you want to do"), enter **Cash Desk Events Setup** and then choose the related link.
2. Na přehledu **Pokladních případů** založte případ pomocí funkce **Nový**.
3. Vyplňte následující pole dle Vaší potřeby:
    - Kód, popis
    - Typ pokladního dokladu (příjem nebo výdej)
    - Typ účtu, číslo účtu, typ obecného účtování, Účto skupiny
    - Kód globální dimenze 1 a Kód globální dimenze 2 a případně, zda se jedná o transakci EET
4. Po nastavení přehled zavřete.

## Cash Inventory

For the purpose of cash desk inventory in Business Central, you can find a report for generating the balance in the cash desk.

### Nominal Value Setup

First, you need to define which banknotes and coins you use in different currencies. It is necessary to define their nominal value for each currency.

1. Choose the ![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what you want to do"), enter **Currency Nominal Values** and then choose the related link.
2. Create rows in the table using the combination of **Currency Code** and **Value**. Do not select a currency code to set the local currency of the system.
3. After defining the rows, you can close the page.

### Cash Inventory Report

1. Choose the ![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what you want to do"), enter **Cash Inventory** and then choose the related link.
2. On the page before running the report, select input parameters such as:
    - **Cash Desk Code** for which the inventory is being taken.
    - **Date** when the inventory is carried out.
    - Option **Show Statistics** of the cash register in the report.
    - Next on the page, fill in the table **Nominal values**, i.e. the number of individual banknotes and coins.
3. After setting the filters, use the **Preview and Close** button. You will then see a page where you can see the status of the selected cash desk.

![Cash Desk Inventory](Media/cash-desk-inven.png)

## Reconciliation of customer or vendor entries

The Reconcile Entries function can be run from the cash document lines to select customer or supplier entries to be reconciled. Similarly, functions are available for balancing with advance invoices.

1. Choose the ![Lightbulb that opens the Tell me Feature](../../media/ui-search/search_small.png "Tell me what you want to do"), enter **Cash Document** adn then choose the related link.
2. In the **Cash Document overview**, create a cash document using the **New** button.
3. Fill in the fields on the cash receipt card:
    - Document type: Receipt or Withdrawal
    - Payment Purpose: list the text that specifies the purpose of the payment
    - Posting date, Document date and VAT
    - Possibly other fields as required
4. In the lines select:
    - Typ účtu: Zákazník nebo Dodavatel
    - Číslo účtu: Vyberte číslo zákazníka nebo dodavatele
    - Ve funkcích nad řádkem použijte funkci **Vyrovnat položky** a najděte položku, kterou chcete vyrovnat.
5. Po vybrání položky můžete doklad zaúčtovat.

## See Also

[Czech Local Functionality](czech-local-functionality.md)  
[Finance](../../finance.md)
