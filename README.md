# 📊 MORSHEDY GROUP Sales & Collection Analytics

📌 Project Overview
The real estate company sells units through installment plans. However, the collection data is stored across multiple project worksheets, making it difficult to monitor the overall collection performance.
________________________________________
🎯 Business Problem
- Data is distributed across 8 project worksheets.
- Installment information is stored in multiple columns and different business states.
- Management needs to identify paid, due, and not-yet-due installments.
- It is difficult to monitor collected and outstanding amounts in one place.
- Management needs visibility into bank exposure and project progress.
________________________________________
📂 Dataset
Source: [Dataset Source]
Time Period: [Start Year] – [End Year]
________________________________________
🧹 Data Preparation
The dataset was prepared using:
•	Data cleaning
•	Handling missing values
•	Removing duplicates
•	Data type transformation
•	Creating calculated columns
•	Creating relationships
•	Data modeling
________________________________________
🗂️ Data Model
We create two fact tables because we have two business processes: the unit sold & the installment for the unit sold
Example:
•	Fact Sales
•	Fact Installments
•	Dim Bank
•	Dim Customer
•	Dim Date
•	Dim Project
•	Dim Unit
________________________________________
🔑 Key Insights
Insight 1
Strong Overall Collection Performance
Installment 7 shows a major collection gap. Out of approximately EGP 158.7M issued for this installment, only EGP 3.35M has been collected, leaving around EGP 155.4M outstanding.
The collection rate for Installment 7 is only about 2.1%, compared with much higher rates for the earlier installments.
____________________________________________________
Insight 2
Outstanding Balance Is Concentrated in Three Projects
The total outstanding balance is approximately EGP 791.0M. Three projects account for about 60.2% of this amount:
Skyline Katamya Compound: EGP 198.0M 
Degla Landmark: EGP 155.2M 
One Kattameya Compound: EGP 122.8M 
Together, these three projects represent approximately EGP 476.0M of the total outstanding balance.
____________________________________________________
Insight 3
Installments 4 and 5 Also Need Collection Monitoring
Collection performance decreases in the later installment stages. Installment 4 has a collection rate of about 92.0%, while Installment 5 is about 92.5%. Their outstanding balances are approximately EGP 175.3M and EGP 110.9M, respectively.
________________________________________
💡 Business Recommendations
Based on the analysis:
1.	Management should maintain the current collection follow-up process while giving special attention to the remaining EGP 791.0M outstanding balance.
2.	Management should give these projects closer collection monitoring and review their outstanding installments regularly.
3.	Management should increase follow-up for later installments, especially Installments 4 and 5, before unpaid balances become larger.
________________________________________
🖼️ Dashboard Preview
Overview
Detailed Analysis
________________________________________
🛠️ Tools & Technologies
•	Power BI
•	DAX
•	Power Query
•	Excel
________________________________________
📁 Repository Structure
Project/
│
├── Dataset/
├── SQL/
├── Power BI/
├── Images/
├── Documentation/
└── README.md
________________________________________
👤 Author
Ali Magdy
🐙 GitHub [https://github.com/mralimagdy2001-dev] | 💼LinkedIn [https://www.linkedin.com/in/ali-magdy-mahmoud]



