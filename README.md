# E-commerce Promotion ROI Analysis


This project analyzes a transactional e-commerce dataset to help a retail business understand which of two marketing promotions—a "10% Flat Discount" or a "Buy 2, Get 1 Free" offer—is more profitable. The analysis provides a data-driven recommendation to optimize the company's marketing spend.

## Tech Stack
- **Python:** Pandas, Matplotlib, Seaborn, SciPy
- **BI Tool:** Microsoft Power BI (DAX)
- **Version Control:** Git & GitHub

## Key Findings

* **Profitability Analysis:** Both promotions were found to be **unprofitable**, with the 10% discount resulting in a -417% ROI and the B2G1 offer resulting in a -86% ROI.
* **Root Cause:** The promotions failed because they did not generate enough **incremental revenue** to cover their costs, largely due to sales cannibalization.
* **Behavioral Insights:** The 10% discount attracted lower-spending customers (lower AOV), while the B2G1 successfully drove sales volume but at an unsustainably high cost.

## Final Recommendation

The analysis concludes with a strong recommendation to **halt both promotions** in their current blanket format. The suggested next steps are to A/B test more controlled, targeted promotions, such as threshold offers (e.g., "10% off orders over $100") or offers on specific high-margin product categories.

## How to Use This Repository

1.  Clone the repository: 'git clone https://github.com/PRANAVBR/ecommerce-promotion-analysis.git`
2.  The main analysis is in the 'project 1.ipynb' Jupyter Notebook.
3.  The final interactive dashboard is in the `project1.pbix` file.
