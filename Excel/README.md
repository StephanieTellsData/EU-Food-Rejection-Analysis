## Excel Data Preparation

The dataset was cleaned and prepared in Excel before analysis.

### Key steps:
- Removed duplicates and irrelevant columns  
- Standardized date formats  
- Extracted year and month from the date field  
- Reviewed and structured categorical variables  
- Performed initial pivot table analysis  

### Feature Engineering:
- Created a **severity grouping** from the 'action_taken' field  
- Actions such as *destruction, re-dispatch, return, seizure, and prohibition* were classified as **Severe**  
- Less critical actions were grouped as **Moderate** or **Low**  

This transformation enabled consistent severity analysis across SQL and Power BI.
