# SAP-FI-Module-Case-Study
A new client account.  Your client, MobileCo, is very demanding and wants the system configured for Finance as soon as possible.
# MobileCo Financial Configuration Case Study

## Introduction
This repository contains the SAP AG project documentation and testing scenarios for MobileCo's financial configuration. MobileCo trades in mobile phones and accessories, operating in multiple countries, including the US, UK, Spain, and Egypt, each represented as a separate company code.

## Project Overview
This project aims to configure the SAP system to meet MobileCo's specific financial operations needs. This includes setting up general ledger (GL) accounts, accounts payable (AP), and accounts receivable (AR) and managing different payment terms for domestic and international vendors and customers.

## Key Configuration Details
- **Chart of Accounts:** Single chart across all company codes.
- **Financial Year:** July 1 to June 30, with only one period open at any given time.
- **GL Accounts Types:** Expense, Balance Sheet, Reconciliation, and Revenue.
- **Tolerance Groups:** Two levels for payment differences—default for normal employees and director group for higher discrepancies.

## Document Structure
- `FI Case_Intake 44. pdf`: Detailed financial configuration exercises, client requirements, and expected testing scenarios.

## Testing
Testing scenarios include:
- Posting vendor and customer invoices.
- Checking balances and reconciliations.
- Managing payment terms and discounts.
- Verifying system restrictions on document editing and period openings.

## Requirements
- SAP S/4HANA
- Access to MobileCo's specific company code settings for real-time testing and configuration adjustments.

## Setup Instructions
1. Clone the repository using `git clone https://github.com/[YourUsername]/MobileCo-Financial-Configuration.git`.
2. Follow the configuration guidelines in `FI Case_Intake 44. pdf` to set up the SAP environment.
3. Execute the listed test cases to ensure the configuration aligns with the business requirements.

## Contact Information
For further assistance or to report issues, contact:
- Email: ahmadmoshafy@outlook.com
- LinkedIn: www.linkedin.com/in/ahmedshafay06
