# python_project_4
python_project_4

# Simple Rectangular (Bar) Chart Example

import matplotlib.pyplot as plt  # For plotting

# Data for the bar chart
categories = ["A", "B", "C", "D"]  # Categories on x-axis
values = [10, 25, 15, 30]  # Heights of the bars

# Create bar chart
plt.bar(categories, values, color="teal")  # Bar color

# Add title and labels
plt.title("Simple Bar Chart")
plt.xlabel("Categories")
plt.ylabel("Values")

# Display the chart
plt.show()
