# Debt Relief Program Marketing Campaign Analysis

This repository contains an analysis of a debt relief program marketing campaign conducted over a five-month period. The goal is to assess the success of the campaign, recommend improvements, and determine how the campaign’s performance might change if it had been delayed.

### **📝 Tasks**
1. **Assess Marketing Campaign Success**  
   Analyze the effectiveness of the campaign run during Month 3. Select appropriate success metrics (e.g., client deposit behavior, client sign-ups, financial impact) and explain the rationale behind the choice of metrics.

2. **📈 Recommend Future Strategy Adjustments**  
   Based on the provided data, suggest potential changes to the campaign strategy that could improve performance in future campaigns.

3. **⏳ Evaluate Impact of Postponing the Campaign**  
   Simulate what would have happened if the campaign had been moved to Month 6, and compare the results with the success of the original campaign. Calculate the incremental differences to understand how performance might have changed.

### **📊 Data Description**

The analysis relies on three datasets provided:

1. **client_data.csv**  
   Contains details about fictional clients, such as:
   - `client_id`: Unique identifier for each client
   - `client_geographical_region`: Geographic region (based on U.S. Census)
   - `client_residence_status`: Whether clients rent or own
   - `client_age`: Age of the client

2. **deposit_data.csv**  
   Contains deposit-related information, including:
   - `client_id`: Unique identifier for each client
   - `deposit_type`: Scheduled or actual deposit record
   - `deposit_amount`: Amount deposited by the client
   - `deposit_cadence`: Timing and pattern of deposits
   - `deposit_date`: Date of deposit

3. **calendar_data.csv**  
   Provides the calendar reference for the campaign period:
   - `gregorian_date`: Actual date in the Gregorian calendar
   - `month_name`: Month names for the period (Month 1 to Month 5, where Month 3 is the campaign)

### **💡 Assumptions**

- The campaign was run evenly throughout Month 3 with no seasonal variations.
- Data from the datasets does not reflect actual client or deposit information.
- The scope of analysis excludes channel mix, targeting, and efficiency.

### **🛠️ Analysis Tools**
-Only python libs
---

This repository provides the necessary data and analysis framework to assess the marketing campaign's impact and make strategic recommendations based on quantitative findings.
