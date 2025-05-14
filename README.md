# Donor Analytics Capstone Project (Synthetic Version)

This repository demonstrates the analytical workflow developed for a nonprofit donor segmentation and forecasting project, originally conducted for the **Grand Canyon Council, Scouting America**.

🚫 **Note:** All data in this repository is synthetic. No real donor or constituent information is exposed.

---

## Project Overview

The project aimed to:
- Reverse donation stagnation by identifying high-value donor segments
- Build predictive models to forecast donation behavior
- Develop strategic recommendations for targeted outreach
- Demonstrate the use of synthetic data for safe, shareable analysis

---

## Tools & Methods

**Conceptual:**
- RFM Segmentation (Recency, Frequency, Monetary)
- Behavioral Economics
- Strategic Persona Mapping

**Technical:**
- Python (pandas, scikit-learn, seaborn)
- Random Forest Regressor for donation prediction
- K-Means Clustering for behavior-based segmentation
- Streamlit Dashboard (in full project)

---

## Synthetic Dataset Features

The synthetic dataset simulates realistic donor behavior based on statistical distributions derived from anonymized trends:

| Column                         | Description                                   |
|-------------------------------|-----------------------------------------------|
| Donor ID                      | Unique synthetic donor identifier             |
| Donation Frequency            | Annual donation count                         |
| Average Donation              | Average donation amount in USD               |
| Digital Engagement Score      | Digital interaction intensity (0–100)         |
| Last Donation Recency (months)| Months since last donation (0–36)             |
| Wealth Index                  | Proxy for financial capacity (0–100)          |
| Event Participation           | Encoded level of event attendance (0–3)       |

---

## Sample Visuals  (Some Not Shown Here)

In the full report and internal version, we developed:

- **Donation Trend Lines Over Years** *(Not shown here)*  
  Showed changes in donor behavior and total donations across time.

- **Predicted vs Actual (Random Forest)**  
  Compared model predictions with actual donation values using synthetic data.

- **Segment-Specific Strategy Tables**  
  Mapped donor personas to action plans for targeted outreach.

- **Feature Importance Plot**  
  Ranked variables based on their contribution to the model.

- **City-Level High-Value Donor Heatmap** *(Not shown here)*  
  Identified local fundraising opportunities based on donor geography.

- **Cumulative Donation Curve** *(Not shown here)*  
  Demonstrated how the top 20% of donors contribute most of the funds.

- **Attention-Based Engagement Funnel** *(Not shown here)*  
  Proposed a conceptual model of donor progression over time.


---

### Predicted vs Actual (Random Forest)
This chart compares predicted vs. actual donation values using a Random Forest Regressor trained on synthetic data.
![Predicted vs Actual](charts/predicted_vs_actual.png)

---

### Segment-specific strategy tables
This visual aligns behavioral segments with marketing actions to help optimize donor engagement.
![Segment Strategy](charts/Segment_strategy_mapping.png)

---

### Feature Importance  
The most influential features in predicting annual donation are shown below.
![Feature Importance](charts/feature_importance.png)

---


> ⚠️ All data used in these visualizations is synthetic to reflect realistic but non-identifiable donor behavior. No real donor information is included.
---

## Data Privacy

This GitHub version uses **only synthetic data** to demonstrate reproducible analytics methods. The original dataset was provided under a nondisclosure agreement and includes personally identifiable donor information that **cannot be publicly shared**.

---

## Learn More

For full project context and business impact:
- Visit the [Grand Canyon Council](https://www.grandcanyonbsa.org/)
- Contact [Zih-Han Shen](https://www.linkedin.com/in/zih-han-shen-552983286/) for project details
