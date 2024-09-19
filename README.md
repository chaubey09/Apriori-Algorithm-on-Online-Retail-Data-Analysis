# Apriori Algorithm on Online Retail Data Analysis

This project demonstrates the application of the Apriori Algorithm on an online retail dataset to identify association rules among purchased items. The Apriori algorithm is a popular tool used in market basket analysis to uncover hidden patterns in transactional data.

## Overview

The notebook includes the following steps:
- Reading and preprocessing the dataset, including handling missing values.
- Filtering transactions based on specific countries (France, United Kingdom, Portugal, and Sweden).
- Transforming the data into a binary format suitable for the Apriori algorithm.
- Applying the Apriori algorithm to identify frequent itemsets with a specified minimum support.
- Generating association rules using the lift metric to find interesting item relationships.
- Displaying the sorted rules based on confidence and lift values.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Mlxtend (for Apriori and association rules)

## How to Run

1. Install the required libraries using:
   ```bash
   pip install pandas numpy mlxtend
