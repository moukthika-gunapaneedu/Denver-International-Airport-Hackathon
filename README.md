# Denver-International-Airport-Hackathon
## Overview
This project delivers an **interactive Power BI dashboard** that connects **ServiceNow enhancement requests** with **Azure DevOps (ADO) features** to give customers and internal teams a single, clear view of status, progress, and developer allocation. Missing values were predicted using **dspy**, and long descriptions were **summarized with NLP** for faster decision-making.



## Key Features
- **Work Status Tracking:** Real-time view of enhancement request progress  
- **Completion Progress:** Percent complete per request  
- **Estimated Start Date:** Predicted start dates for pending tasks  
- **Customer Distribution:** Requests by customer/segment  
- **Developer Allocation:** Workload per developer/team  
- **NLP Summaries:** Concise auto-summaries of long descriptions  

---
## Files Included
- `DEN_Hack.ipynb` - Jupyter Notebook for data preprocessing & prediction of missing values using dspy.
- `DEN_Dashboard-2.pdf` - Final Power BI dashboard with interactive visualizations.


---
## Installation & Setup

### Power BI Dashboard
1. Open Power BI Desktop.
2. Load the dataset (ensure correct paths).
3. Use the Power Query Editor for any modifications.
4. View interactive insights through dashboard elements.

### Jupyter Notebook (dspy-based Predictions)
1. Install dependencies:
```bash
pip install dspy pandas numpy matplotlib
```

2. Open the notebook:
```bash
jupyter notebook DEN_Hack.ipynb
```

3. Run all cells to process data and predict missing values.


---
## Insights & Impact

This dashboard enhances decision-making by:
- Empowering customers with real-time progress tracking.
- Helping internal teams balance workload & project timelines.
- Predicting missing data for more accurate insights.
- Improving transparency & efficiency in enhancement request handling.
---

## Future Improvements
- Implement real-time data sync with ServiceNow & Azure DevOps APIs.
- Enhance predictive modeling for task timelines.
- Integrate automated anomaly detection for request delays.

