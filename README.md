# Identify Customer Segments

This project applies unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. Using demographic data from the general population and customers, the analysis involves data preprocessing (handling missing values, encoding categorical features, engineering mixed-type features), feature scaling, dimensionality reduction with PCA, and clustering with K-Means. The final step compares cluster distributions to identify overrepresented and underrepresented segments in the customer data relative to the general population.

## Requirements

- Python 3.8+
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, jupyter

## Setup and Run

Create a conda environment with the required packages and run the Jupyter notebook:

```bash
conda create -n customer_segments python=3.8 numpy pandas matplotlib seaborn scikit-learn jupyter -y && conda activate customer_segments && jupyter notebook Identify_Customer_Segments.ipynb
```

This command creates the environment, activates it, and opens the notebook in your browser for execution.
