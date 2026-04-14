# Odoo Cooperative Accounting Logic
## Project Overview
Implementation of a custom Odoo ERP financial structure for **Tsheseng Unity Enterprise**.

**Technical Architecture Lab:** [Morganhub.lovable.app](https://morganhub.lovable.app)

### Key Technical Challenges Solved:
* **Asset Optimization:** Configured a Fixed Asset pipeline to capitalize renovation costs for the Old School Site.
* **Capital vs Revenue:** Automated distinction between Member Equity (R100) and Subscriptions (R30).
* **Data Integrity:** Established a relational onboarding strategy for 30 members using Odoo External IDs.

### Repository Structure
* `/chart_of_accounts`: Finalized Odoo-ready Excel import templates.
* `/member_management`: Partner relational data and receivable links.
* 
### Implementation Validation
![Odoo Import Validation](images/import_test.png)
*Validated the Chart of Accounts structure against Odoo 17/18 internal requirements, ensuring zero mapping conflicts.*

![Odoo Import Validation](images/success_import.png)
*Validated Import records successful- 129 records
