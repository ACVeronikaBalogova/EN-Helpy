---
title: Finance - Czech Local Functionality | Microsoft Docs
description: This section describes Czech local functionality for Finance.
author: v-pejano

ms-service: dynamics365-business-central
ms.topic: conceptual
ms.search.keywords: CZ, Czech, Finance, Posting
ms.date: 12/30/2019
ms.reviewer: v-pejano
ms.author: v-pejano
---

# Finance

In Czech Republic, there are specific features for [!INCLUDE[prodshort](../../includes/prodshort.md)] you can use to track and manage your finances.

## Corrective posting (Red Cancellation)

According to the requirements of the legislation, costs and revenues are usually only charged to either the Debit or Credit G/L Account. Companies in Eastern Europe usually follow an accounting policy whereby certain inventory and financial transactions in the general ledger must be accounted for as adjustments. This is because auditors and financial authorities carry out accounting controls in accordance with this policy.

The purpose of this functionality is:

- Enable the head accountant to enforce corrective posting in the required GL accounts.
- Allow the head accountant to enforce inventory corrective posting (negative transfer entries, expected cost posting).
- Enable the head accountant to enforce corrective posting of reversal adjustment in fixed assets.
- Enable users to make one-click corrective posting (financial, inventory and job postings).

## Statutory information about the company

Currently there are many documents circulating outside and inside the company. Local legislation sets minimum requirements for such documents. These requirements can be roughly divided into three groups:

- The names of company representatives must appear on certain internal or external documents.
- Document footers – majority of external documents must contain basic information about the company in the document footers, usually in the language of the partner company.
- Company registration numbers must be prominently listed in internal and external documents.

This feature allows users to define company representatives and set them as CEO, Head Accountant and Finance Manager for use in internal and external documents.
Users can define document footers in different languages. These footers can be used in different reports and documents.

Additional company registration numbers and other registration information may be stored in the Company Information and used in documents.

## Internal receipts

Users carry out posting transactions and must be able to print documents with posting transactions that meet the requirements of the legislation in terms of appearance and content.
Users also want to print out documents for posting transactions that have already been posted. For the fore mentioned reasons, this feature provides the following reports:

- General Journal - test - report is used to print documents from the general journal.
- General ledger document - a report - is used to print posted accounting transactions.

## Outbound documents

This functionality provides the following reports to meet the output requirements of legislative requirements and local practices:

- General Journal
- General Ledger
- Accounting sheets
- Turnover report by Global Dimension
- Open G/L Entries To Date
- Inventory Account to the date
- Bank account Reconciliation
- Joining G/L Account Adjustment
- G/L VAT Reconciliation
- Payments on Hold
- Open Customer Entries at Date
- Open Vendor Entries at Date
- Fiscal Year Balance – modified standard report
- Trial Balance by Period - modified standard report

## Account Schedules - extension  

For one of the most used application areas for analysis and reporting, Eastern European countries require the following improvements to the functionality of standard Account Schedules:

- Shared expression list - the shared expression list contains named rows that can be used as formulas for all Account Schedules. This is achieved by defining one Account Schedule as a common list of expressions called Shared Account Schedule.
- Saving analysis results (current state) - this enhancement allows the user to save the results of an analysis performed using Account Schedules.
- Pattern Analysis - this extension allows the user to analyze the results of patterns. Analysis is now available for Sum Type - Formula. Analyzing a formula result will show the user a new form containing a list of elements used for the calculation and their description.
- Additional data sources - in addition to being able to perform analysis based on general ledger entries, users can now perform analysis based on VAT entries, customer entries, vendor entries and value entries.

## Statutory Statements

Companies must prepare financial statements in accordance with the Accounting Act No. 563/1991.  They must produce a Balance Sheet and a Profit and Loss Statement. This function provides the following statements:

- Balance Sheet
- Profit and Loss Statement

These statements use Account Schedules with a defined structure of statutory statements.

A new field has been added to the Account Schedule Name table in the Czech version:

- Type of Account Schedule - Balance Sheet or Profit and Loss Statement

New fields have been added in the line of Account Schedules in the Czech version:

- Row Correction – link to another line for the Balance Sheet.
- type Active/Passive - Assets or Liabilities for the Balance Sheet.
- Calculate - Always, Never, Positive, Negative

The Balance Sheet and Profit and Loss Statement are often prepared in Excel file templates with the necessary appearance for printing the statement. Users want to be able to map defined Account Schedules to prepared Excel templates.

For the fore mentioned reasons, this feature provides new Excel template settings and statement entries mapping. Based on these settings, users can export Account Schedule data to an Excel file.

## Extended posting of work in process  

Czech legislation uses the following new G/L accounts in posting for Work in Progress:

- Consumption Account
- Change in Work in Progress
- Change in Product Status

This feature enables correct posting of Work in Progress and Production according to Czech posting procedures. Thanks to it, it is possible to set up G/L Accounts for Consumption, change in Work in Progress and change in Subassembly goods and Products for combinations of Warehouse Location and Posting Groups. The new posting system is used for the following transactions:

- Consumption posting in Consumption Journals
- Cost posting of production operations in output journals
- Completion of product orders

## Additional Finance Features

The following table provides further information on the additional financial features available for the Czech Republic.

| Topic | Description |
| :-------------------------------------------------------- | :----------------------------------------------------------- |
| [Closing Operations](year-close-operations.md) | In order to comply with accounting regulations at the end of the fiscal year, certain ledgers must be closed or opened. |
| [Reconciliation General Ledger Entries](general-ledger-entries-application.md) | In addition to the use of customer and vendor entries, new functionality has been introduced for the application of G/L entries. Reconciliation of G/L entries is typically used to allow companies to work with Temporary and Transfer accounts in Finance. |
| [Update of Exchange Rate](exchange-rate-update.md) | Option to automatically update Exchange Rates from an external service provided by the CNB (Czech National Bank).|

## See Also

[Czech Local Functionality](czech-local-functionality.md)
