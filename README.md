# Pakistan's Largest E-Commerce Dataset Analysis
This Jupyter Notebook (.ipynb) file contains an in-depth analysis of one of Pakistan's largest e-commerce datasets. The primary objective of this analysis is to study the relationship between product categories, payment methods, and order status.

## Overview
The analysis focuses on the following key aspects:

- Understanding the distribution of product categories in the dataset.
- Examining the different payment methods used by customers.
- Analyzing the relationship between product categories and payment methods with order status, such as complete, cancelled, or refunded.

## Dataset
The dataset contains the following attributes:

- Item ID
- Category Name
- Payment Method
- Order Status
- Date and time of purchase
- Order Quantity
- Order Price
- Customer ID
Other relevant order and product details
The dataset can be downloaded [here](https://www.kaggle.com/datasets/zusmani/pakistans-largest-ecommerce-dataset)

## Prerequisites
To run the notebook and reproduce the results, you need the following software and libraries installed on your system:

Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scipy
You can install the required libraries using pip:

`pip install jupyter pandas numpy matplotlib seaborn`

## Usage
To run the notebook, follow these steps:

- Clone this repository.
- Launch Jupyter Notebook by running jupyter notebook in your terminal or command prompt.
- Open the ipynb file in Jupyter Notebook.
- Run the cells in the notebook to explore the analysis and visualizations.

## Results
Based on the analysis, we draw the following conclusions:

- Out of 584,496 order records, 54% are successful (completed, received), while the remaining 46% are unsuccessful (canceled, refunded).
- Order status is affected by both category and payment method, with payment method having a stronger influence.
- The top 5 categories by total successful orders are Men's Fashion, Women's Fashion, Mobiles & Tablets, Superstore, and Beauty & Grooming.
- The top 5 categories by total successful revenue are Mobiles & Tablets, Appliances, Entertainment, Women's Fashion, and Others.
- The top 5 most preferred payment methods by total orders are COD, Payaxis, Easypay, Easypay_voucher, and Jazzwallet.

Based on these conclusions, we recommend the following strategies for emerging start-ups in Pakistan:

- Focus on the top 5 categories (based on total orders and total revenue):
  - Mobiles & Tablets (highest total order, highest total revenue)
  - Men's Fashion (2nd highest total order, 6th highest total revenue)
  - Women's Fashion (3rd highest total order, 7th highest total revenue)
  - Appliances (4th highest total order, 2nd highest total revenue)
  - Entertainment (10th highest total order, 3rd highest total revenue)

- Payment:
  - Use COD as the primary payment method to increase the order success rate. Alternatives are Easypay_voucher and Jazzwallet.
  - Avoid using Easypay and Payaxis for electronics categories such as Mobiles & Tablets, Entertainment, and Appliances.

## Contributing
Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License. Please read the license file for more information on using this project.
