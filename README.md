# Marketing Sales Regression Analysis

### **Project Overview**
Simple Linear Regression analysis for Darey.io assignment.  
Goal: Recommend the marketing channel with the strongest ROI impact, explain model results clearly to a non-technical stakeholder`.

**Key findings:**
- **R² = 0.999**: Model explains 99.6% of sales variance
- TV  has a high impact on Sales
- TV and sales met key model assunptions ( linearity, normality and homoscedasticity.
- **Recommendation**: Allocate more budget to TV  for max ROI.

 

 ## **Assumptions**
  - Normality: Q-Q plot shows residuals follow the line, so normality assumption holds
- Homoscedasticity: Residuals vs Fitted plot shows constant variance around y=0

**Files:**
- `Regression_analysis.ipynb` - Jupyter notebook with EDA, model training, evaluation
- `marketing.csv` - Dataset with TV, Radio, Social Media, Sales columns

### **Environment Setup**
1. **Install Python 3.8+**
2. **Install dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
