Bike Sharing Data Analysis 

This is my first data science project.I analyzed a bike-sharing dataset using Python, Pandas, and Matplotlib.

This project helped me practice:
- Data exploration
- Grouping and aggregation
- Visualization
- Gaining insights from data



Dataset

The dataset is from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset) and contains daily bike rental counts along with weather and season information.

- File used: `day.csv`
- Columns include:
  - `cnt`: total bike rentals
  - `registered` and `casual` user counts
  - weather, season, working day, temperature, etc.


What I Did

Explored:
- Average bike count per **month**, **season**, and **day of the week**  
- Comparison between **registered** and **casual** users  
- Impact of **holiday vs non-holiday** and **workday vs weekend**  
- Relationship between **temperature** and bike usage  
- Effect of different **weather conditions** on bike demand  

Visualized:
- Line graphs
- Bar charts
- Scatter plots

All done using Pandas and Matplotlib in a Jupyter Notebook.

Some conclusions that I made:

-The season with the highest average number of bikes is fall, with around 5,600 average bikes.

-The months with the highest average bike usage are June and September, with nearly 5,700 average bikes.

-Registered users are more than four times the number of casual users.

-There is only a small difference in bike usage between weekdays.

-There is an average difference of about 1,000 bikes between holidays and non-holidays.

-There isn’t much difference between workdays and non-workdays — the average gap is around 200 bikes.

-As temperature increases, bike count also increases, peaking around 20–25°C, then slightly decreases on hotter days.




Tools Used

- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook
