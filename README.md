# 📊 Are We Wasting Billions? A Deep Dive into Healthcare Spending and Outcomes

## 📖 Overview
This project analyzes healthcare spending and its relationship with health outcomes. Using data analysis and visualization techniques, it explores inefficiencies in spending patterns to uncover potential areas for improvement.

## 📂 Repository Structure
- `Are We Wasting Billions? A Deep Dive into Healthcare Spending and Outcomes.ipynb` – Jupyter Notebook containing the analysis.
- `US_Mortality_Trends.ipynb` – Jupyter Notebook containing the analysis.
- `data/` – Folder for datasets used in the analysis (if applicable).
- `figures/` – Folder containing visualizations and plots generated in the notebook.
- `README.md` – This file, providing an overview of the project.

## 📌 Insight

##Where Does the Money Go? Ranking America's Healthcare Spending Priorities

![Ranking America's Healthcare Spending](https://github.com/user-attachments/assets/e08273ff-587e-4390-bc26-5b1d3078400c)


### **Data Interpretation**: Where Does the Money Go? Ranking America's Healthcare Spending Priorities
Spending Trends (1999–2016):

- **Top Spending Areas**: Personal Health Care, Private Health Insurance, and Hospital Care grew significantly.
- **Low Spending Areas**: Dental Services, Home Health Care, and Durable Medical Products.
- **Death Rate Decline**: Age-adjusted death rate dropped from 140 to 120 per 100,000, likely linked to increased spending.

**Insight**: More spending focuses on essential healthcare areas, leading to improved outcomes (lower death rates).

##Can Money Cure It All? Healthcare Spending vs Death Rates

<img width="948" alt="Correlation Heatmap" src="https://github.com/user-attachments/assets/bb3fd50d-d687-44df-bdeb-0dd10673ac80" />

### **Data Interpretation**: Can Money Cure It All? Healthcare Spending vs Death Rates

- **Strong Positive Correlations:**  
   - **Suicide (0.93)** and **Alzheimer's disease (0.92):** Despite spending, these causes have **high death rates**, indicating challenges in addressing them effectively.  
   - **Unintentional Injuries (0.80):** Spending is high, yet death rates remain significant, reflecting difficulties in prevention.  

- **Strong Negative Correlations:**  
   - **Cancer (-0.98)**, **Heart disease (-0.98)**, and **Stroke (-0.97):** Increased spending significantly **reduces death rates**.  
   - **Influenza and Pneumonia (-0.95):** Spending effectively lowers death rates for these treatable conditions.  

- **Mixed Results:**  
   - **Kidney Disease (-0.13):** Weak correlation suggests spending has minimal impact on reducing death rates.  

**Insight:**  
While increased healthcare spending helps reduce death rates for many diseases (e.g., **cancer**, **stroke**), it struggles to solve complex challenges like **suicide** and **Alzheimer's disease**, where non-medical factors or treatment limitations play a role.  

![Ageadjusted Death Rate for Other Causes](https://github.com/user-attachments/assets/8ab22144-6fd6-411e-9f15-39e473b2a67d)

### **Data Interpretation**: A Time Series View: When Spending Isn't Enough for Suicide Alzheimer's and Unintentional Injuries
- **Alzheimer's Disease (Right Chart):**  
   - Death rates **increased sharply** (30 to 50 per 100,000) despite rising spending, highlighting **treatment limitations** and lack of prevention.  

- **Suicide (Right Chart):**  
   - Death rates **rose steadily** despite increased spending, showing the impact of **non-medical factors** like mental health and societal challenges.  

- **Unintentional Injuries (Right Chart):**  
   - Death rates climbed alongside spending, reflecting gaps in **prevention** and **safety policies**.  

- **Other Causes (Left Chart):**  
   - Diseases like **heart disease** and **cancer** saw declining death rates, showing effective outcomes from increased spending.  

**Insight:**  
Healthcare spending helps reduce death rates for treatable diseases but struggles with **suicide**, **Alzheimer's**, and **injuries**, where non-medical factors and prevention play a larger role.  


## 🚀 Getting Started
1. Clone the repository:
   ```sh
   git clone https://github.com/nkdneab/healthcare-spending-outcomes.git
   cd healthcare-spending-outcomes
