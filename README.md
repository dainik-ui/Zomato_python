# Zomato Data Analysis Project Using Python

![](https://github.com/dainik-ui/Zomato_python/blob/main/zomato-app.png)

## Project Overview

This project involves analyzing a dataset from Zomato to uncover insights about restaurant ratings, online order availability, cost distribution, and more. The analysis utilizes Python libraries such as NumPy, Pandas, Matplotlib, and Seaborn for data manipulation and visualization.
## Dataset Information
The dataset contains information about 148 restaurants with the following columns:

name: Name of the restaurant

online_order: Availability of online order (Yes/No)

book_table: Availability of table booking (Yes/No)

rate: Restaurant rating

votes: Number of votes received

approx_cost(for two people): Approximate cost for two people

listed_in(type): Type of the restaurant

## Key Analysis and Visualizations
1. Countplot of Restaurant Types

Description: This countplot visualizes the distribution of different types of restaurants in the dataset.

Insight: The most common type of restaurant in the dataset is "Dining," followed by "Cafes" and "Buffet." This provides a quick overview of the predominant restaurant categories.

2. Votes by Restaurant Type

Description: A line plot showing the total number of votes grouped by restaurant type.

Insight: "Dining" restaurants receive the highest total number of votes, indicating a higher level of customer engagement or popularity compared to other types like "Cafes" and "Buffet."

3. Rating Distribution

Description: A histogram displaying the distribution of restaurant ratings.

Insight: The majority of restaurants have ratings between 3.5 and 4.5, with very few restaurants rated below 3.0 or above 4.5. This indicates a generally positive trend in restaurant ratings.

4. Cost Distribution

Description: A countplot illustrating the distribution of approximate costs for two people.

Insight: The cost distribution shows that most restaurants have an approximate cost between 300 and 800 for two people, with a few outliers on both the lower and higher ends.

5. Boxplot of Ratings by Online Order Availability

Description: A boxplot comparing restaurant ratings based on whether they offer online orders.

Insight: Restaurants offering online orders tend to have slightly higher median ratings compared to those that do not, suggesting a possible correlation between online order availability and customer satisfaction.

6. Heatmap of Restaurant Type vs Online Order

Description: A heatmap showing the count of restaurants by type and their online order availability.

Insight: "Dining" and "Cafes" have a significant number of restaurants offering online orders. However, there is also a notable number of "Dining" restaurants that do not offer online orders.

7. Online Order Availability Pie Chart

Description: A pie chart visualizing the percentage of restaurants offering online orders.

Insight: A large majority of restaurants in the dataset offer online orders, indicating the widespread adoption of online ordering services.

8. Scatter Plot of Cost vs Votes

Description: A scatter plot exploring the relationship between the approximate cost for two people and the number of votes, categorized by restaurant type.

Insight: There is a noticeable trend where restaurants with moderate costs (around 500-800) tend to receive more votes. "Dining" restaurants dominate in terms of both higher votes and cost range, showing their popularity and potentially higher engagement levels.



## Conclusion
This project provides insights into restaurant data from Zomato, offering a better understanding of customer preferences and restaurant performance. The visualizations help in making data-driven decisions for business strategies.
