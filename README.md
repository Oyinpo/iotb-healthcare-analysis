*IOTB TECH Hospital — Healthcare Data Analytics & Business Intelligence Report*

*Executive Summary*

Between January 2019 and May 2024, IOTB TECH Hospital processed 54,966 unique patient admissions, generating *$1.404 billion* in total hospital revenue thus averaging approximately *$25,540* per patient encounter.

While the hospital demonstrates strong financial stability, the analysis reveals a critical strategic reality: *revenue growth has plateaued.* Monthly revenue consistently fluctuates between $22M–$25M with minimal long-term upward movement, indicating the organization is likely operating near its current inpatient capacity ceiling.

Operationally, the hospital maintains a well-diversified patient and payer portfolio:

Gender distribution is effectively balanced (50/50)
Insurance revenue is evenly spread across five providers
No single medical condition dominates admissions volume

However, the analytics uncovered several high-impact operational and clinical concerns:

*33.5% abnormal laboratory result rate* suggests possible diagnostic QA or classification inconsistencies
*Asthma patients record the longest average Length of Stay (15.68 days)* — exceeding even Cancer admissions
Patients aged *65+ account for 30.8% of all admissions,* signaling a rapidly ageing patient base.


*Overall Business Health*
Area	Assessment
Financial Stability	✅ Strong
Operational Efficiency	⚠️ Moderate
Growth Trajectory	⚠️ Plateauing
Strategic Positioning	⚠️ Undifferentiated
Data Maturity	✅ Strong


*Business Objective*

This project was designed to transform raw healthcare records into actionable business intelligence using:

Microsoft Excel
Pivot Tables
Pivot Charts
Data Cleaning
Healthcare Analytics
Operational KPI Analysis.


The goal was to help hospital leadership better understand:

Patient behavior
Admission patterns
Revenue drivers
Insurance performance
Diagnostic trends
Medication utilization
Operational bottlenecks.


Data Engineering & Preparation

Before analysis, the dataset underwent full preprocessing and validation.

Data Quality Audit
Metric	Result
Original Records	55,500
Duplicate Records Removed	534
Final Clean Dataset	54,966
Missing Values	0
Blank Rows	None
Incorrect Data Types	None
Date Range	Jan 2019 – May 2024.


*Formatting Applied*
Column	Applied Format
Billing Amount	Currency ($#,##0.00)
Admission Date	Date
Discharge Date	Date.


*Calculated Fields*
***Length of Stay (LOS)***

Length of Stay=Discharge Date−Admission Date

LOS Metric	Value
Average LOS	15.5 Days
Minimum LOS	1 Day
Maximum LOS	30 Days


*Patient & Demographic Analysis*
***Gender Distribution***

Patient access remains highly equitable:

Gender	Admissions	Share
Male	27,496	50.02%
Female	27,470	49.98%

This indicates no measurable gender disparity in healthcare access or utilization.


***Age Group Analysis***
Age Group	Admissions
Under 18	116
18–34	13,485
35–49	12,154
50–64	12,288
65+	16,923.

**Key Insight**

Patients aged 65+ represent the hospital’s largest admission cohort (30.8%), establishing geriatric healthcare as a major operational dependency.

This demographic shift will likely intensify over the next decade and materially impact:

Bed occupancy
Staffing requirements
Care complexity
Insurance reimbursement structures

*Medical Condition Intelligence*
***Most Common Conditions***

Condition	Admissions
Arthritis	9,218
Diabetes	9,216
Hypertension	9,151
Obesity	9,146
Cancer	9,140
Asthma	9,095

The remarkably balanced distribution reduces concentration risk but also highlights a strategic weakness:

The hospital lacks a dominant specialty identity.

***Revenue by Medical Condition***
Condition	Total Revenue
Diabetes	$236.5M
Obesity	$236.0M
Arthritis	$235.2M
Hypertension	$233.4M
Asthma	$233.1M
Cancer	$229.9M


***Strategic Observation***

Although Arthritis is slightly more prevalent, Diabetes generates the highest overall revenue, making it the hospital’s most commercially valuable condition category.

This suggests strong opportunities for:

Endocrinology expansion
Chronic disease management programs
Long-term outpatient retention models
Diabetes Centers of Excellence.


*Operational Efficiency Analysis*
***Length of Stay by Condition***

Condition	Avg LOS
Asthma	15.68 Days
Arthritis	15.50 Days
Cancer	15.50 Days
Obesity	15.45 Days
Hypertension	15.44 Days
Diabetes	15.43 Days

***Critical Operational Finding***

Asthma patients staying longer than Cancer patients is clinically counterintuitive and suggests:

Weak discharge coordination
Inadequate outpatient follow-up systems
Delayed transition care
Overreliance on inpatient monitoring

Reducing Asthma LOS by even one day could recover 9,000+ annual bed-days.


*Revenue & Insurance Analytics*
***Total Hospital Revenue***

$1.404 Billion


***Revenue by Insurance Provider***
Provider	Revenue
Cigna	$284.3M
Medicare	$282.9M
Blue Cross	$280.4M
UnitedHealthcare	$279.9M
Aetna	$276.5M


***Business Interpretation***

Revenue diversification is exceptionally healthy.

No provider contributes disproportionately to cash flow risk, protecting the hospital from payer concentration exposure.

***Admission Revenue***
Admission Type	Revenue
Elective	$473.1M
Urgent	$469.2M
Emergency	$461.7M


**Key Insight**

Elective procedures remain the hospital’s most profitable and operationally predictable revenue stream.

Management should prioritize:

Theatre utilization optimization
Elective scheduling efficiency
Cancellation reduction systems


*Diagnostic & Laboratory Risk Analysis*
***Test Result Distribution***
Result	Count	Share
Abnormal	18,437	33.5%
Normal	18,331	33.3%
Inconclusive	18,198	33.1%


***High-Risk Observation***

The near-perfect three-way distribution is statistically improbable in real clinical populations.

This strongly indicates possible:

Laboratory calibration inconsistencies
Classification standardization errors
Diagnostic QA issues
Data entry normalization problems


**Immediate Recommendation**

A full independent laboratory audit should be commissioned within 30 days.


*Medication Utilization Analysis*
*Most Prescribed Medications*

Medication	Prescriptions
Lipitor	11,038
Ibuprofen	11,023
Aspirin	10,984
Paracetamol	10,965
Penicillin	10,956


*Medication Revenue*
Medication	Revenue
Ibuprofen	$283.8M
Aspirin	$281.2M
Paracetamol	$280.2M
Lipitor	$279.7M
Penicillin	$279.2M
Strategic Insight

Despite being prescribed less frequently than Lipitor, Ibuprofen generates higher revenue, indicating stronger association with higher-complexity or higher-intensity treatment episodes.

*Strategic Recommendations*
1. Expand Capacity Beyond Current Ceiling

Revenue growth has stalled due to operational saturation.

***Recommended Actions***
Expand bed capacity
Launch outpatient specialty centers
Increase elective procedural throughput
2. Establish Specialized Chronic Disease Centers

Prioritize:

Diabetes
Cancer
Geriatric care

These represent the strongest long-term clinical and financial growth opportunities.

3. Reduce Length of Stay Through Transitional Care

Introduce:

Home-health pathways
Pulmonology step-down care
Digital patient monitoring
4. Audit Diagnostic Infrastructure Immediately

The abnormal/inconclusive result pattern creates:

Financial risk
Operational inefficiency
Reputational exposure
5. Optimize Elective Procedure Operations

Elective care is:

Most profitable
Most schedulable
Most scalable

Protecting elective throughput should become a core operational KPI.

*Tools & Technologies Used*

Microsoft Excel
Pivot Tables
Pivot Charts
Data Cleaning
Healthcare Analytics
KPI Reporting
Business Intelligence Analysis


*Conclusion*

This project demonstrates how healthcare analytics can move beyond reporting into strategic decision intelligence.

Using Excel-based business intelligence techniques, the analysis uncovered:

Revenue plateau risks
Operational inefficiencies
Geriatric care pressure
Diagnostic QA concerns
Chronic disease monetization opportunities

The result is a practical executive-level healthcare analytics framework capable of supporting operational planning, financial optimization, and long-term strategic positioning for modern healthcare systems.