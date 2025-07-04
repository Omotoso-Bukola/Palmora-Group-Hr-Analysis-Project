# Palmoria Group HR Equality Analysis.

## An HR analytics report exploring gender disparities, salary equity, and performance fairness across regions.


## Overview

 This report was commissioned to support Palmoria Group’s efforts to address growing concerns around gender inequality, salary gaps, and regulatory compliance.

 Using emp-data from internal sources, this report provides an analytical foundation to guide policy reform and HR decision-making.



## Data Sources:

 - Palmoria Group emp-data.csv: Employee records including gender, region, department, salary, and ratings

 - Palmoria Group Bonus Rules.xlsx: Guidelines for allocating bonus payments based on performance


## Tools Used:

  Power BI for cleaning,dashboard design and DAX analysis


- Steps Taken:

-  Cleaned the employee data:

 Removed rows with missing salary or undefined departments

1. Re-coded "Undisclosed" gender as “N/A”


2. Analyzed gender representation, pay distribution, and performance ratings


3. Calculated bonuses using rating-based multipliers


4. Built interactive dashboards in Power BI with slicers by gender, department, and region

    Analysis & Findings

## Gender Representation

  Males dominate the workforce in nearly all regions and departments

  Lowest female representation in Manufacturing, Production.


  - Performance Ratings:

    Males are disproportionately present in higher performance brackets

    

- Salary Structure

  Gender pay gap is evident in at least 5 departments

-  Minimum Wage Compliance

   A significant number of employees earn below $90,000


-  Bonus Allocation:

   Bonus calculated using the predefined rating tiers

  High-performing employees receive significant bonus boosts, further increasing total disparity if ratings are biased


- Interpretation:

These results highlight systemic HR issues:

Possible unconscious bias in performance ratings

Regulatory compliance issues that expose the company to penalties

Bonus policies that reward top performers but could amplify existing inequities



- Bonus Rule Format

 Bonus rules were provided in Excel, not joined with the employee dataset, requiring a merge based on performance score

 Manual mapping and cleaning had to be done before applying rules

