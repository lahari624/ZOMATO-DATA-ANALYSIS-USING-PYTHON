📊 Zomato Data Analysis Using Python

This project performs exploratory data analysis (EDA) on Zomato restaurant data using Python libraries such as pandas, numpy, matplotlib, and seaborn. The analysis helps in understanding trends in restaurant ratings, online orders, cost for two, and popularity based on the number of votes.

🧹 Data Preprocessing :

Converted ratings from "x/y" format (e.g., 4.1/5) to float values.
Handled missing values and verified data types.
Ensured consistency in categorical features like online_order, book_table, and listed_in(type).

 

📊 Visualizations and Analysis :

  1) Count Plot of Restaurant Types :Showed distribution of restaurants by type (listed_in(type)).

  2) Votes per Restaurant Type : Grouped data by listed_in(type) and plotted total votes using a line graph.

  3) Restaurant with Maximum Votes : Identified "Empire Restaurant" as the one with the highest number of votes.

  4) Online Order Distribution : Count plot of whether restaurants offer online ordering.
  
  5) Rating Distribution : Histogram of restaurant ratings to understand their spread.

  6) Cost for Two : Count plot of approx_cost(for two people) to analyze pricing trends.

  7) Boxplot(Online Order vs Rating) : Analyzed if offering online ordering affects ratings.
  
  8) Heatmap : Created a pivot table of restaurant types vs online order availability. Visualized with a heatmap to identify 
               the relationship between the two.


📦 Requirementsc :

  Install the following libraries before running the notebook:

  pip install pandas numpy matplotlib seaborn


▶️ How to Run :

  1) Clone this repository or download the notebook and dataset.
  2) Ensure the dataset CSV file is correctly placed and the path is updated.
  3) Run the notebook in Jupyter or any Python IDE.


📈 Sample Output : 

  1) Highest voted restaurant: Empire Restaurant
  2) Most common restaurant types: Buffet, Cafes, etc.
  3) Online ordering has a slightly positive correlation with higher ratings.


📌 Conclusion : 

This project gives an overview of customer preferences, restaurant popularity, and pricing strategy using simple but effective visualizations. It provides useful insights into restaurant performance on Zomato.


📚 Future Improvements : 

  1) Add sentiment analysis using customer reviews (if available).
  2) Predict restaurant ratings using machine learning models.
  3) Perform geographical analysis based on city or locality.
