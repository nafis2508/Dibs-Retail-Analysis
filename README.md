# Dibs Retail Analysis

## Project Overview

Dibs is a fast-growing retail company specializing in a wide range of products, including shoes, cosmetics, clothing, food, beverages, and souvenirs. Despite its rapid expansion, the company faces challenges in increasing sales and customer loyalty. The provided dataset contains customer purchase history across different malls, which is crucial for understanding customer behavior and improving sales and marketing strategies.

This project focuses on analyzing the provided data to uncover insights, identify patterns and trends, and make actionable recommendations to enhance sales and customer loyalty.

## Dataset

The dataset includes the following features:

- **invoice_no:** Invoice number (Nominal) - A combination of 'I' and a 6-digit integer uniquely assigned to each transaction.
- **customer_id:** Customer number (Nominal) - A combination of 'C' and a 6-digit integer uniquely assigned to each customer.
- **gender:** Customer's gender (String).
- **age:** Customer's age (Positive Integer).
- **category:** Product category (String).
- **quantity:** Quantity of each product per transaction (Numeric).
- **price:** Unit price in Turkish Liras (TL) (Numeric).
- **payment_method:** Payment method used (cash, credit card, or debit card) (String).
- **invoice_date:** Date of the transaction (Date).
- **shopping_mall:** Name of the shopping mall where the transaction occurred (String).

## Project Objectives

### Data Cleansing

1. **Handling Missing Values:** Address missing values in the dataset.
2. **Data Type Conversion:** Convert data types as needed for accurate analysis.
3. **Handling Duplicates:** Identify and remove duplicate records.
4. **Histograms:** Create histograms to check data distribution.
5. **Outliers:** Detect and manage outliers.

### Analysis

Perform insightful analysis using the following techniques:

1. **Customer Segments:** Identify which customer segments or categories should be targeted for marketing campaigns.
2. **Spending Behavior:** Create a box plot to compare the distribution of spending scores between male and female customers.
3. **Age and Spending:** Create a scatter plot to visualize the relationship between age and spending.
4. **Age Groups:** Segment customers into different age groups and analyze how spending scores vary across these groups.

### Recommendations

1. **Sales by Payment Method:** Visualize the proportion of total sales made by each payment method to understand customer payment preferences.
2. **Sales Trend Over Time:** Create a line chart to visualize total monthly sales and identify any trends or patterns.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/dibs-retail-analysis.git
   ```

2. **Install Dependencies:**
   Ensure you have the required Python packages installed:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook:**
   Start Jupyter Notebook and open the analysis notebook:
   ```bash
   jupyter notebook
   ```

4. **Access the Data:**
   The dataset and README file describing the features are included in the repository.

## Repository Structure

- `notebooks/`: Contains Jupyter Notebooks with data analysis and visualizations.
- `data/`: Includes the dataset file and description.
- `requirements.txt`: Lists Python packages needed for the project.

## Contributions

Contributions are welcome! If you have any suggestions or improvements, please submit issues or pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
