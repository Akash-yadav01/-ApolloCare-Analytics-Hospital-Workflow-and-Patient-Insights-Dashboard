# -ApolloCare-Analytics-Hospital-Workflow-and-Patient-Insights-Dashboard
A dynamic Power BI dashboard built to analyze hospital operations—tracking bed occupancy, patient admissions, doctor feedback, diagnosis types, and insurance vs. billing performance.
🛠️ Tech Stack

The dashboard was built using the following tools and technologies:
	•	📊 Power BI Desktop – Main data visualization platform used for designing the hospital workflow and patient insights dashboard.
	•	📂 Power Query – Data transformation and cleaning layer for preparing patient, billing, and feedback data.
	•	🧠 DAX (Data Analysis Expressions) – Used to create calculated measures, KPIs (e.g., Billing Amount, Bed Occupancy), and dynamic visuals.
	•	📝 Data Modeling – Relationships established among patient, doctor, diagnosis, insurance, and billing tables to enable cross-analysis.
	•	🗄️ SQL Database / Hospital Records – Underlying dataset structured from hospital management records (patient IDs, admit/discharge, billing, insurance, feedback).

 📂 DATA SOURCE

Source: Hospital management system records, provided as a SQL dataset and connected through Power BI.

The dataset is structured to capture multiple aspects of hospital operations, including:
	•	🧑‍🤝‍🧑 Patients – Patient_ID, admit date, discharge date, and follow-up details.
	•	🛏️ Bed Occupancy – Department-wise occupancy (ICU, Private, General) for monitoring capacity utilization.
	•	👨‍⚕️ Doctors & Feedback – Feedback volume for doctors (e.g., Jay Sinha, Mark Joy, Ravi D) to measure performance and patient satisfaction.
	•	🧾 Billing & Insurance – Financial records including total billing (~₹190.43M) and insurance claim amounts across diagnosis types.
	•	🩺 Diagnosis Types – Categorized illnesses such as Viral Infection, Flu, Malaria, Typhoid, Pneumonia, and Fracture, linked to billing and insurance data.

 🌟 Features / Highlights

• Business Problem

Hospitals generate large amounts of patient, billing, and operational data across multiple departments. Without proper visualization, it is difficult to answer questions such as:
	•	What is the current bed occupancy in ICU, Private, and General wards?
	•	Which diagnosis types are most prevalent among admitted patients?
	•	How do insurance claims compare against billed amounts?
	•	Which doctors receive the highest patient feedback and satisfaction scores?

• Goal of the Dashboard

To deliver an interactive hospital workflow and patient insights tool that:
	•	Tracks patient admissions, discharges, and follow-ups in a streamlined manner.
	•	Monitors real-time bed occupancy across wards for better capacity utilization.
	•	Analyzes doctor performance using patient feedback data.
	•	Compares health insurance amounts vs. billing amounts to highlight financial gaps.
	•	Provides actionable intelligence to improve hospital efficiency, financial planning, and patient care.

• Walkthrough of Key Visuals
	•	Key KPIs (Top Left) – Displays overall billing amount (~₹190.43M), admission/discharge timeline, and patient workflow ￼.
	•	Bed Occupancy Analysis (Clustered Bar Chart) – Shows occupancy counts across ICU, Private, and General wards.
	•	Doctor Feedback Volume (Ranking Table) – Lists doctors (e.g., Jay Sinha, Mark Joy, Ravi D) by total feedback volume, highlighting top performers.
	•	Diagnosis Type Breakdown (Pie/Bar Visuals) – Illustrates proportions of illnesses like Viral Infection, Flu, Malaria, Typhoid, Pneumonia, and Fracture.
	•	Insurance vs. Billing (Clustered Column Chart) – Compares health insurance claims against billed amounts for each diagnosis type.

• Business Impact & Insights
	•	Capacity Optimization – Real-time view of bed occupancy enables administrators to manage hospital resources more efficiently.
	•	Doctor Performance Evaluation – Feedback analysis supports HR decisions and helps improve patient satisfaction.
	•	Financial Planning – Insurance vs. billing comparison highlights gaps and supports negotiations with insurers.
	•	Diagnosis Monitoring – Identifying top illnesses helps allocate resources to high-demand treatments.
	•	Operational Efficiency – Unified dashboard reduces reporting delays and improves decision-making speed for hospital leadership.
 
   Screenshot
    

![Dashboard Overview](https://github.com/Akash-yadav01/Sales-Insights-Interactive-Market-Revenue-Analytics-Dashboard/blob/main/Snapshot%20of%20the%20Dashboard.png)
