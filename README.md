# Food Order Data Visualization Dashboard
This Dash application provides interactive visualizations for analyzing food order data. The visualizations help in understanding various aspects such as total price per cuisine type, number of orders by restaurant, distribution of orders by food category, and more.

## Features
### 1) Total Price per Cuisine Type Ordered in a Month: Line chart showing the total cost of orders for each cuisine type.
### 2) Number of Orders by Restaurant: Scatter plot displaying the number of orders placed at each restaurant.
### 3) Distribution of Orders by Category of Food: Pie chart depicting the distribution of orders across different food categories.
### 4) Distribution of Cuisine Type: Percentage bar chart showing the distribution of different cuisine types.
### 5) Distribution of City: Percentage bar chart representing the distribution of orders across different cities.
### 6) Distribution of Day Type: Percentage bar chart illustrating the distribution of orders across different days of the week.

## Requirements
To run this application, you need the following libraries:
### 1) dash
### 2) pandas
### 3) plotly

## Data
The application uses two CSV files for data:

### food_order.csv: Contains information about the food orders including cuisine type, cost of the order, restaurant name, and day of the week.
### foodorder1.csv: Contains detailed information about the food items ordered including the category and city.

## Usage
Ensure you have the required libraries installed.
Place the CSV files (food_order.csv and foodorder1.csv) in the same directory as the script.
Run the script using Python:
bash
Copy code
python app.py
Open your web browser and navigate to http://127.0.0.1:8050/ to view the dashboard.
Application Layout

## The dashboard consists of several visualizations:

### Visualization 1: Line chart for the total price per cuisine type.
### Visualization 2: Scatter plot for the number of orders by restaurant.
### Visualization 3: Pie chart for the distribution of orders by food category.
### Visualization 4: Percentage bar chart for the distribution of cuisine types.
### Visualization 5: Percentage bar chart for the distribution of orders by city.
### Visualization 6: Percentage bar chart for the distribution of orders by day type.
