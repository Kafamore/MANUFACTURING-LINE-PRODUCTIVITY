# MANUFACTURING-LINE-PRODUCTIVITY



### Table of content
- [Project overview](#project-overview)
- [Data soutce](#data-source)
- [Tools](#tools)
- [Data Cleaning and preparation](#data-cleaning-and-preparation)
- [Exploratory data analysis eda](#exploratory-data-analysis-eda)
- [Data analysis and findings](#data-analysis-and-findings)
- [Recommendation](#recommendation)
- [Conclusion](#conclusion)

### Project Overview
This project aims to evaluate the efficiency of a manufacturing production line, identify underperforming operators, analyze leading causes of downtime, 
and determine if specific operators struggle with particular types of errors. By leveraging data analysis techniques, the goal is to provide actionable 
insights for process optimization and efficiency improvement.

![Dashboard](Dashboard.png)


![manufacture dashboard](https://github.com/user-attachments/assets/d952370f-e22f-4f99-9557-095df5aba7b0)

### Data Source


Manufacturing line productivity data set: The primary data set used for this analysis is "manufacturing_line_productivity_data.csv" file

### Tools
- Power query in Power Bi for cleaning
- Power Bi for Analysis,Visualization and Report

  ### Data Cleaning And Preparation
- Handle Missing Values
- Standardize Formats
- Remove Duplicates
- Correct Inconsistent Data
- Fix Data Entry Errors
- Convert Data Types
- Validate Data Integrity

  ### Exploratory Data Analysis Eda
What is the overall line efficiency percentage, and how does it compare to industry benchmarks?
How does the total downtime impact the overall production performance?
Is there a correlation between total production time and total downtime?


  ### Data Analysis and Findings

1. Production Efficiency
- Current line efficiency is 64%, with  1,388 minutes (26%) lost to downtime, impacting productivity.  
- Significant inefficiencies suggest room for optimization.  
2. Operator Performance  
- Charlie (67%) is the most efficient, while Mac (61%) is the least efficient.  
- Performance gaps indicate a need for targeted improvements.  
3. Key Downtime Factors  
- Machine adjustments cause the most downtime, especially for Charlie (118 min) and Dennis (120 min).  
- Batch changes (Mac - 130 min) and inventory shortages (Dee - 85 min, Mac - 80 min) are other major delays.
   
4. Operator-Specific Challenges  
- Charlie & Dennis: Machine adjustments.  
- Dee: Inventory shortages.  
- Mac: Batch changes.  


### Recommendation

Reduce Machine Adjustment Downtime – Standardize procedures, train Charlie & Dennis, 
and implement preventive maintenance.

Optimize Batch Change – Streamline processes, train Mac, and explore automation.
Improve Inventory Management – Enhance tracking, strengthen supply chain coordination, and train Dee & Mac.
Boost Operator Performance – Provide targeted training and introduce cross-training.
Enhance Monitoring – Aim to increase efficiency from 64% to 75%, using data for continuous improvement.

  ### Conclusion

The production line is underperforming, with high downtime affecting efficiency.
Addressing machine adjustments, batch change delays, 
and inventory shortages will enhance performance and reduce productivity losses.
 
