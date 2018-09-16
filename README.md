# Steps for POC

- We currently support drilldown only for the below options
  - Credit Risk Management
  - Credit Risk Managment > Pre Sanction Process
  - Credit Risk Managment > Pre Sanction Process > Quality of Appraisal
- The non drill down fields generate random scores on clicking the field.
- To Demo
  - Start with drill down to Quality of Appraisal page
  - Set breaches observed and risk matrix values for each field
  - Click on 'Rollup' which is visible when the sub total is calculated
  - Calculated score for quality of Appraisal is set and set the other fields
  - Click on 'Rollup' which is visible when the sub total is calculated for PreSanctionProcess
  - Set the other fields values which generates the set 1 subtotal followed by set 2 total and Aggregate.
- Note: This doesn't use a server so no state is saved. Rolling up from parent to child erases the child individual field values.
- To view the final result click on the link : https://rohanantony.github.io/AuditApp/
