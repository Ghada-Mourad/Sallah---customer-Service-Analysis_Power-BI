<img width="1492" height="807" alt="Screenshot 2026-08-05 001547" src="https://github.com/user-attachments/assets/e3ac397d-089a-4894-b048-78fa151c72fa" />
<img width="1392" height="847" alt="Screenshot 2026-08-05 001720" src="https://github.com/user-attachments/assets/a97a4023-54a5-4f63-b3bd-b95d60f8a5d3" />
<img width="1387" height="842" alt="Screenshot 2026-08-05 001801" src="https://github.com/user-attachments/assets/75843ad0-d9ac-4cc4-8d0b-54b50bf56121" />
<img width="1065" height="712" alt="Screenshot 2026-08-05 001839" src="https://github.com/user-attachments/assets/da3acbba-7211-48b7-9ac7-03c3de59abde" />
<img width="1918" height="831" alt="Screenshot 2026-08-05 001827" src="https://github.com/user-attachments/assets/a1cde29f-a026-41a8-861a-db76d25bfda4" />

📊 Sallah Call Center Performance & Operations Analysis
🎯 Project Objective
Transformed and analyzed 1.7 million call records from the "Sallah" call center into actionable business insights using Power BI. The goal was to evaluate operational performance, enhance customer experience (CX), and align operational forecasts with reality to minimize unnecessary expenditures.

📈 Detailed Analysis & Business Impact
1. Overall Service Efficiency Evaluation
Analytical Result: The call center achieved a 98.7% Handling Rate, an Average Speed of Answer (ASA) of just 9 seconds, and a very low Abandonment Rate of 1.3%.

Business Value:
Proves full compliance with the Service Level Agreement (SLA), ensuring high customer satisfaction.
Establishes these metrics as a benchmark for evaluating future branches or projects.

2. Workforce & Forecast Optimization
Analytical Result: The comparison between forecasted and actual calls revealed a significant variance, where forecasts were consistently higher than actual call volumes across all three months (e.g., February forecasted 700K calls vs. 450K actual). Additionally, daily trend analysis identified distinct peaks (e.g., days 7 and 24 reaching up to 80K calls).

Business Value:
Forecasting Model Fine-Tuning: Recalibrating the forecasting model prevents over-scheduling agents, thereby reducing unnecessary operational costs and labor expenses.
Smart Scheduling: Scheduling more staff on predictable peak days prevents bottlenecks and delays, while optimizing headcount on low-volume days.

3. Agent Performance Tracking & Training Needs
Analytical Result: Analyzing the abandonment rate by individual agents revealed performance variations; certain agents (e.g., Huda at 0.9% and Dina at 0.8%) recorded higher abandonment rates compared to the team average.

Business Value:
Directs targeted coaching and training to agents struggling with response times, avoiding costly, blanket team-wide training programs.
Identifies top-performing agents' best practices to share across the team and standardize quality.
4. Project Resource Allocation
Analytical Result: Project A handles the largest portion of call volume at 1.54M calls, followed by Project B (1.50M), and Project C (1.30M).

Business Value:
Reallocates support staff based on actual workload per project, preventing team burnout on high-volume projects and balancing overall workload distribution.
🛠️ Technical Stack & ArchitectureAnalytics & Visualization: Microsoft Power BIData Model: Star Schema architecture linking a central calendar dimension table (Calender) to monthly fact tables (Feb, Mar, Apr) via a $1 \to \infty$ relationship.Data Transformation & DAX: Built dynamic DAX measures to calculate total calls, handling rates, abandonment rates, and time averages.If you need a README.md raw code block for GitHub or specific sections adjusted, let me know!
