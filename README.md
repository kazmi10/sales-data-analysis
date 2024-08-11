# Sales Data Analysis Project

## Project Overview
This project involves analyzing sales data to identify trends, patterns, and insights. The project focuses on understanding sales distribution, identifying top products, and segmenting customers based on their purchasing behavior.

## Dataset Description
The dataset used in this project includes information on products, pricing, discounts, ratings, and customer reviews. It contains the following key columns:
- `product_id`: Unique identifier for products.
- `discounted_price`: Price after discount.
- `actual_price`: Original price before discount.
- `discount_percentage`: Discount percentage applied.
- `rating`: Customer rating of the product.
- `user_id`: Unique identifier for customers.

## Analysis Steps
1. **Data Preprocessing**:
   - Loaded the dataset, handled missing values, and cleaned the data.
   - Converted relevant columns to appropriate data types.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed the distribution of prices, discounts, and ratings.
   - Identified top-performing products and categories.
   - Conducted correlation analysis to find relationships between variables.

3. **Customer Segmentation**:
   - Applied K-Means clustering to segment customers based on total spending, number of purchases, and average discount received.
   - Analyzed the resulting clusters to derive actionable insights.

## Insights
- **Price Distribution**: Most products are priced under 5000 units, with discounts concentrated around 50%.
- **Top Products**: Small kitchen appliances and room heaters are among the top-performing products.
- **Customer Segments**:
  - Cluster 0: Budget-conscious customers who prefer high discounts.
  - Cluster 1: Mid-range spenders who are less price-sensitive.
  - Cluster 2: High-value customers who spend significantly more and receive moderate discounts.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, Matplotlib, Seaborn, Scikit-Learn
- **Tools**: Jupyter Notebook

## How to Run the Code
1. Clone this repository: `git clone https://github.com/kazmi10/sales-data-analysis.git`
2. Navigate to the project directory: `cd sales-data-analysis`
3. Open the Jupyter notebooks in the `notebooks/` directory to explore the analysis.
4. Ensure all required Python libraries are installed (`pip install -r requirements.txt`).

