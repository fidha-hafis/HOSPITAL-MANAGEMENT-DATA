Hospital Management Data Analysis Project

Project Overview

This Excel-based project analyzes hospital operations using patient, doctor, appointment, treatment, and billing records. The objective is to monitor appointment outcomes, treatment activity, and payment performance through a consolidated dataset, calculations, pivot tables, and a dashboard.

Project Objectives

* Evaluate appointment volume, completion, cancellations, and no-shows.
* Compare appointment activity across hospital branches, doctors, and specializations.
* Analyze treatment types, costs, and billing amounts.
* Track paid, pending, and failed payments.
* Provide actionable recommendations to improve hospital performance.

Dataset Overview

The workbook includes five source tables and one consolidated analysis table:

|Source sheet              |Records|Description                                                          |
|--------------------------|------:|---------------------------------------------------------------------|
|patients                |50     |Patient identifiers, demographics, contact and insurance details     |
|doctors                 |10     |Doctor identifiers, specializations, experience and hospital branches|
|appointments            |200    |Appointment dates, patient/doctor links, reasons and statuses        |
|treatments              |200    |Treatment identifiers, types, dates and costs                        |
|billing                 |200    |Billing amounts, methods and payment statuses                        |
|HOSPITAL MANAGEMENT DATA|200    |Consolidated appointment-level analysis table                        |

Other workbook sheets include CHANGE LOG, ANALYSIS, CALCULATIONS, pivot-table summaries, INSIGHTS&RECOMMENDATIONS, and DASHBOARD.

Tools and Techniques

* Microsoft Excel for data preparation, analysis and dashboard reporting.
* VLOOKUP and matching IDs to combine related tables.
* Pivot tables to summarize appointment status, treatment costs and billing.
* Calculated metrics for completion rates, no-show rates and payment shares.
* Excel dashboard for visual performance monitoring.

Data Cleaning and Transformation

1. Combined patient, doctor, appointment, treatment and billing information into a master dataset.
2. Created patient full names from first and last name columns.
3. Linked patient details using patient_id and doctor details using doctor_id.
4. Linked treatment and billing records through their relevant identifiers.
5. Checked lookup results for missing values and unmatched records, as documented in the workbook change log.
6. Prepared consolidated data for pivot-table analysis and dashboard reporting.

Key Business Questions

1. How many appointments were recorded?
2. What proportion of appointments were no-shows or completed?
3. How do appointment statuses vary by doctor, specialization and hospital branch?
4. What is the total billing amount, and how much has been paid?
5. Which treatment types have the highest costs and billing contributions?
6. How does billing vary over time?

Key Performance Indicators

|KPI                   |Result             |
|----------------------|------------------:|
|Total appointments    |200                |
|Completed appointments|46 (23%)           |
|No-show appointments  |52 (26%)           |
|Cancelled appointments|51 (25.5%)         |
|Scheduled appointments|51 (25.5%)         |
|Total billed amount   |551,249.85         |
|Paid amount           |173,424.90 (31.46%)|
|Pending amount        |184,612.01 (33.49%)|
|Failed amount         |193,212.94 (35.05%)|

Billing currency is not specified in the source workbook. Monetary figures are therefore shown without an assumed currency.

Key Findings

* Appointment completion is low: only 23% of recorded appointments are marked completed.
* No-shows are substantial: 26% of appointments are marked no-show.
* Payment collection needs attention: approximately 68.54% of billed value is pending or failed, while 31.46% is marked paid.
* High-volume areas: the workbook’s insights sheet identifies Central Hospital (84 appointments) and Pediatrics (98 appointments) as the leading branch and specialization by appointment count.
* Treatment cost: the workbook’s treatment-cost summary identifies Chemotherapy as the largest total treatment-cost category (128,855.68).

Recommendations

* Introduce appointment reminders and confirmation workflows to reduce no-shows.
* Follow up on missed and cancelled appointments and improve rescheduling.
* Review pending and failed payments regularly and improve insurance/card payment processing.
* Monitor high-volume branches and specialties for staffing and scheduling needs.
* Track treatment costs and billing trends periodically to support resource planning.

Limitations

* The workbook does not specify the currency of monetary amounts.
* Appointment status and treatment/billing entries coexist in the dataset; billing should not automatically be interpreted as cash received or treatment completed.
* The data should be treated as a project dataset rather than verified real-world hospital performance.
* The dashboard and calculations reflect the workbook as provided; no independent audit of all underlying records has been performed.

Conclusion

This project demonstrates how Excel can consolidate hospital data and turn it into operational insights. The analysis highlights opportunities to improve appointment attendance, payment follow-up, and resource allocation.
