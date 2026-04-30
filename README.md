# Global Temperature Clustering Analysis 

## Project Overview
This project analyzes historical temperature data across different regions, countries, cities, and years. The analysis uses Python to clean the dataset, visualize temperature patterns, and apply K-Means clustering to identify possible temperature-based groupings.

## Dataset
The dataset contains temperature records with the following columns:

- Region
- Country
- State
- City
- Month
- Day
- Year
- Temp

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Analysis Performed
- Loaded and cleaned the temperature dataset
- Checked missing values and data types
- Visualized temperature distribution over years
- Applied K-Means clustering
- Used the Elbow Method to identify the optimal number of clusters
- Generated plots to understand temperature trends and clustering behavior

## Key Visualizations

### Temperature Distribution by Year
This plot shows temperature values across different years and helps identify seasonal and regional temperature variation.

### Elbow Curve for K-Means Clustering
The elbow curve shows the Sum of Squared Errors (SSE) for different cluster values. The curve helps determine the best number of clusters for the K-Means model.

## Project Files
- `temperature_analysis.py` - Python code used for analysis and visualization
- `data/Data-Week6.csv` - Dataset used for the project
- `images/temperature_plot.png` - Temperature visualization
- `images/elbow_curve.png` - Elbow method output

## Conclusion
This project demonstrates how Python can be used for exploratory data analysis, visualization, and unsupervised machine learning. The K-Means clustering approach helps identify patterns in temperature data across time and locations.
