# ANALYSIS-OF-NCR-LOG-BY-PARETO-CHART
 Pareto analysis is a statistical technique in decision-making used for selection of limited number of tasks that produce significant overall effect. It uses Pareto principle also known as 80/20 rule. With This technique we have analyzed the large data for the non-conformance logs and represented it in a graphical manner for better understanding.

1. SUM Function – Quantifying Total Impact
Used to calculate the total number of NCRs or total cost/impact associated with each category. 
Helped in identifying which categories contribute most to the overall non-conformance.

2. IF Function – Conditional Filtering
Enabled categorical analysis by filtering NCRs based on specific criteria (e.g., severity, department, type).

Supports dynamic calculations like:
Count only high-priority NCRs.
Sum costs only for a specific department.

3. VLOOKUP Function – Data Mapping
Used to fetch related information (e.g., root cause, corrective action, responsible team) from a master table.
Enhanced the analysis by linking NCR codes to detailed descriptions.

Pareto Chart Integration
After sorting categories by descending frequency or impact using SUM, the Pareto chart was created to visualize:
Top contributors to NCR's with the help of bar + line (Clustered) chart 
Cumulative percentage to apply the 80/20 rule.
