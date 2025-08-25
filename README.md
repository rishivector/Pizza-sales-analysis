Pizza Sales Analysis (2015)
🍕 Introduction
This project provides a comprehensive analysis of a full year of sales data from a pizza restaurant. By diving into the dataset, we uncover key trends, identify top-performing products, and derive actionable insights to help drive strategic business decisions. The analysis explores sales performance by time of day, day of the week, and month, as well as by pizza category, size, and individual menu items.

Dashboard : https://public.tableau.com/views/pizzadashboard_17534688321110/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

📈 Key Insights & Features
This analysis extracts meaningful business intelligence from the raw sales data. Here are some of the key findings:

Peak Hours: The busiest times are the lunch rush (12 PM - 2 PM) and the dinner rush (5 PM - 7 PM).

Busiest Days: Sales build throughout the week, peaking on Friday and Saturday.

Top Category: The 'Classic' category is the most popular choice among customers.

Preferred Size: Large pizzas account for nearly 45% of all sales, indicating a trend towards group orders.

Best Sellers: "The Classic Deluxe Pizza" and "The Barbecue Chicken Pizza" are major revenue drivers.

Underperformers: "The Brie Carre Pizza" is the lowest-selling item, suggesting a need for marketing intervention or menu re-evaluation.

💻 Technologies Used
The analysis was conducted using the following technologies:

Python: The core language used for data manipulation and analysis.

Pandas: The primary library for cleaning, merging, and analyzing the dataset.

Jupyter Notebook (or any Python IDE): For executing the analysis script.

🚀 Getting Started
To replicate this analysis, follow these steps:

Clone the repository:

git clone https://github.com/your-username/pizza-sales-analysis.git

Navigate to the project directory:

cd pizza-sales-analysis

Ensure you have Python and Pandas installed:

pip install pandas

Run the analysis script to generate the insights from the provided CSV files.

📊 Data Sources
The dataset is comprised of four CSV files, which are relationally linked:

orders.csv: Contains the date and time of each order.

order_details.csv: Links pizzas to specific orders and includes the quantity of each pizza.

pizzas.csv: Contains the size, price, and type ID for each unique pizza.

pizza_types.csv: Provides the name, category, and ingredients for each pizza type.

💡 Recommendations
Based on the analysis, the following strategic recommendations were formulated:

Optimize Staffing: Align staff schedules with peak hours and days to improve service efficiency.

Targeted Marketing: Launch promotions for underperforming pizzas and introduce weekday specials to boost sales on slower days.

Menu Engineering: Leverage the popularity of the 'Classic' category and Large size by creating family bundles and combos. Consider discontinuing the XL and XXL sizes due to low sales volume.
