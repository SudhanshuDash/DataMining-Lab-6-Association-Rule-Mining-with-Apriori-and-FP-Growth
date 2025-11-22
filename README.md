# MSCS 634 - Lab 6: Association Rule Mining Using Apriori and FP-Growth

## Overview
This repository contains Lab 6 for the course MSCS 634 – Advanced Big Data & Data Mining.  
The lab explores association rule mining techniques using the Apriori and FP-Growth algorithms on a real-world transactional dataset (Online Retail).

The objective of this lab is to understand how frequent itemsets and association rules are generated, how support and confidence thresholds influence the results, and how identified patterns can be interpreted to support business decision-making.

## Files Included

- Lab6_Association_Rule_Mining.ipynb  
  Jupyter Notebook containing complete implementation, data preparation, visualizations, and association rule analysis.

- Lab6_Association_Rule_Mining_Explanation.docx  
  Detailed written explanation describing methodology, key insights, and challenges encountered.

## Techniques Implemented

- Transactional Data Cleaning & Preprocessing  
- Basket Matrix Transformation (Invoice × Items)  
- Frequent Itemset Mining:
  - Apriori Algorithm  
  - FP-Growth Algorithm  
- Association Rule Generation  
- Rule Evaluation Metrics:
  - Support  
  - Confidence  
  - Lift  
- Data Visualization:
  - Bar plots of frequent items and itemsets  
  - Co-occurrence heatmaps  
  - Confidence vs Lift scatter plots  

## Key Learnings

- How association rule mining reveals hidden purchasing patterns  
- Impact of support and confidence thresholds on rule generation  
- Performance differences between Apriori and FP-Growth  
- Importance of lift in identifying strong associations  
- Value of visualization in interpreting complex patterns  
- Practical use of association rules in retail analytics and recommendation systems  

## How to Run

1. Clone the repository or download the notebook file.  
2. Ensure the dataset is placed in the correct directory:
   Dataset/Online_Retail.xlsx  
3. Install required package:
   pip install mlxtend  
4. Open the notebook using Jupyter Notebook or Google Colab.  
5. Run cells sequentially to reproduce all outputs and visualizations.

## Author

Sudhanshu Sekhar Dash  
MSCS 634 – Advanced Big Data & Data Mining  
University of the Cumberlands  
