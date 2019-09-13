# Welcome to the BusinessCentralBankImportFormat repository!

This repository is a hub where Microsoft and our partners can share data exchange definitions that let businesses around the world electronically exchange information with banks. 

## Backstory
Microsoft Dynamics 365 Business Central is a global business management application. No matter where our customers are located, an important part of their operations is exchanging information with their bank, or in many cases, their banks. 
Business Central offers capabilities that make it easy to exchange information with banks electronically, for example, to apply payments to reconcile bank, receivables, and payables accounts. For more information, see [Applying Payments Automatically and Reconciling Bank Accounts](https://docs.microsoft.com/en-us/dynamics365/business-central/receivables-apply-payments-auto-reconcile-bank-accounts).
Business Central offers two ways to import bank statements:

• Convert a bank statement file, from any format, to a data stream that you can import. For more information, see [Set Up the Bank Data Conversion Service]( https://docs.microsoft.com/en-us/dynamics365/business-central/bank-how-setup-bank-data-conversion-service).

• Import bank statements as a bank feed by setting up and enabling Envestnet Yodlee Bank Feed service, and then linking bank accounts to the related online bank accounts.

> The Envestnet Yodlee Bank Feed service available only in the United States, Canada, and the United Kingdom. However, for the UK the extension will only support bank statements from banks that do not support open API standards. That is, they still support screen scraping.  

## Setting Up Data Exchange Definitions
There are tens of thousands of banks around the world, which means there are many different formats. The bank data conversion service in Business Central can handle most of them. 

For formats that aren’t already supported, you can set up your own data exchange definition for bank statement files. In a nutshell, data exchange definitions map to the fields that contain the information that banks require. For more information about data exchange definitions, see [Set Up Data Exchange Definitions](https://docs.microsoft.com/en-us/dynamics365/business-central/across-how-to-set-up-data-exchange-definitions).

## Contributing
This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
