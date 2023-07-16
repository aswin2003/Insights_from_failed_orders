# Insights from Failed Orders

This project focuses on analyzing failed orders in the Gett platform, which is a technology platform focused on corporate Ground Transportation Management (GTM). The goal is to investigate the reasons behind order failures and analyze various metrics related to these failed orders.

## Dataset

The dataset used in this project consists of two CSV files: `data_orders.csv` and `data_offers.csv`. These datasets contain information such as order details, cancellation reasons, driver assignments, and time-related metrics.

## Project Description

In this project, we aim to perform the following tasks:

1. Build up distribution of orders according to reasons for failure: cancellations before and after driver assignment and reasons for order rejection.
2. Analyze the resulting plot to determine which category has the highest number of failed orders.
3. Plot the distribution of failed orders by hours to identify any trends or abnormal proportions during certain hours.
4. Identify the biggest failures based on hourly analysis and provide possible explanations for them.
5. Plot the average time to cancel with and without a driver assigned by the hour.
6. Draw conclusions from this plot regarding outliers in data or any patterns observed related to cancellation times.
7. Plot the distribution of average Estimated Time of Arrival (ETA) by hour and provide an explanation for this plot.

**BONUS**: Utilize h3 and folium packages to calculate hexagons containing 80% of all orders from original datasets based on size 8 hexes. Visualize these hexes on a map while coloring them based on fail counts.

## Dependencies

- Python 3.x
- Pandas
- Matplotlib
- H3
- Folium

Install dependencies using pip:
```
pip install pandas matplotlib h3 folium
```

## Usage

1. Clone this repository:
   ```
   git clone https://github.com/[aswin2003]/insights-from-failed-orders.git
   ```

2. Navigate to the project directory:
   ```
   cd insights-from-failed-orders
   ```

3. Run the main script or notebooks for each task.

Feel free to customize this README file according to your specific project details, dependencies, and usage instructions. Include any additional sections or information that you think would be relevant for users visiting your GitHub repository.
