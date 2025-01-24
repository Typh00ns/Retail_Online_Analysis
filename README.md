# Retail Online Analysis

This project explores the Online Retail II dataset to identify key trends, analyze customer behavior, and evaluate the impact of cancellations. Through this analysis, the aim is to practice data exploration and visualization techniques while building a portfolio that highlights my analytical expertise.

## Objectives
- Analyze sales performance: revenue, top products, and trends.
- Study customer behavior: frequency, spending, and segmentation.
- Examine cancellations: rates, financial impact, and key patterns.

## Dataset
- **Source**: UCI Machine Learning Repository. (2019). Online Retail II Dataset. Retrieved from "https://archive.ics.uci.edu/ml/datasets/Online+Retail+II".
- **Description**: The dataset contains transaction details for online retail sales.

### Key Files:
1. **Raw Data**:
   - `online_retail.xlsx`: Original dataset with transaction data.

2. **Processed Data**:
   - `retail_sales_cleaned.csv`: Cleaned retail transactions.
   - `cancellation_transactions_cleaned.csv`: Canceled transactions.
   - `bulk_sales_cleaned.csv`: Bulk orders with high quantities.
   - `bulk_cancellations_cleaned.csv`: Bulk orders that were canceled.

## Methodology
- Data cleaning and processing.
- Data analysis.
- Visualizations.

## Tools
- Python (`pandas`, `matplotlib`).
- Jupyter Notebooks as IDE.

## How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/Typh00ns/Retail_Online_Analysis.git

2. Install the required libraries:

pip install -r requirements.txt

3. Navigate through the following folders for insights:

    Notebooks/: Jupyter Notebooks for cleaning, analysis, and visualization.
    Data/: Raw and processed datasets.
    Reports/: Detailed PDF.

## Repository Structure

Retail_Online_Analysis/  
├── **README.md**  
├── **requirements.txt**
├── **Online_retail_ll_analysis-1.pdf**  

**Data/**  
├── **Raw/**  
│   ├── `online_retail.xlsx`  

├── **Processed/**  
│   ├── `retail_sales_cleaned.csv`  
│   ├── `cancellation_transactions_cleaned.csv`  
│   ├── `bulk_sales_cleaned.csv`  
│   ├── `bulk_cancellations_cleaned.csv`  

**Notebooks/**  
├── **Data_Cleaning/**  
│   ├── `online_retail_ll_data_cleaning.ipynb`  

├── **Retail_Analysis/**  
│   ├── `retail_analysis.ipynb`  
│   ├── `retail_cancellations_analysis.ipynb`  

├── **Bulk_Analysis/**  
│   ├── `bulk_analysis.ipynb`  
│   ├── `bulk_cancellations_analysis.ipynb`  

**Graphs/**  
├── `MoM sales growth.png`  
├── `Top 20 costumers.png`  
├── `Cancellation rate.png`  
├── `...ect.png`  


---

Feel free to explore and review the analysis!
