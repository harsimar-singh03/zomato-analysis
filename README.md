# zomato-analysis
🧾 Executive Summary – Zomato Restaurant & Customer Analysis
🎯 Objective
The analysis aimed to explore Zomato’s restaurant dataset to understand:

1. Popular restaurant types
2. Customer rating patterns
3. Spending trends of couples
4. The impact of online vs offline ordering on ratings

📊 Data Preparation
The dataset Zomato data.csv was loaded and cleaned using pandas.
The “rate” column (ratings like “4.2/5”) was standardized by extracting the numeric portion for numerical analysis.
Exploratory visualizations were performed using Seaborn and Matplotlib.

🍴 Key Insights
1. Popular Restaurant Types
Using a count plot of listed_in(type), certain restaurant types (e.g., Casual Dining, Quick Bites, Cafes) showed the highest number of listings.
These categories represent the most common and in-demand formats among customers.

2. Restaurants with Most Votes
Grouping by listed_in(type) and summing votes identified which restaurant types received the most customer engagement.
Visualized via a line plot, the result indicated that a few categories dominate customer attention.

3. Rating Distribution
A histogram of ratings revealed the overall customer satisfaction levels.
Most ratings were concentrated between 3.0 and 4.5, suggesting generally positive feedback with a moderate spread.

4. Spending Behavior
Analysis of the column approx_cost(for two people) via a count plot showed the most frequent spending range among couples.
The data suggested typical customer spending patterns within mid-range restaurants.

5. Online vs Offline Orders
A boxplot comparing rate against online_order showed how ratings vary based on order type.
Initial patterns indicated that restaurants offering online orders tend to receive slightly higher ratings, reflecting the growing influence of digital convenience.

💡 Conclusions
Casual Dining and Quick Bites dominate both in number and customer votes.
Ratings are generally positive, with most restaurants performing well between 3–4.5.
Mid-range cost restaurants are the most common choice for couples.
Online ordering correlates with higher ratings, showing a preference shift toward digital dining experiences.

🚀 Recommendations
Zomato can promote top-rated restaurant types in popular categories like Casual Dining.
Encourage more restaurants to adopt online ordering systems for better visibility and customer satisfaction.
Analyze cost-to-rating correlation further to identify optimal pricing ranges for different restaurant categories.
