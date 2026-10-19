# Matplotlib Learning Notebook 📊



This repository contains my hands-on practice with **Matplotlib**, a popular Python library used for data visualization.

The notebook explores different types of plots and charts, along with customization techniques to make visualizations clear and meaningful. It includes practical examples using Python, NumPy, and Matplotlib.

This project is part of my learning journey in Data Analytics, helping me build a strong foundation in data visualization and graphical representation of data.

## 🎯 Objectives

- Learn the fundamentals of Matplotlib.
- Create different types of charts and plots.
- Customize plot colors, markers, and line styles.
- Add titles, labels, and formatting to visualizations.
- Understand subplots and multiple plots.
- Represent data visually for better interpretation.

## 🛠️ Technologies Used

- Python
- Matplotlib
- NumPy
- Jupyter Notebook

## 📚 Topics Covered

### 1. Basic Plotting
- Creating line plots using `plt.plot()`
- Plotting data using NumPy arrays
- Displaying plots using `plt.show()`

### 2. Plot Customization
- Adding markers to plots
- Customizing marker size and colors
- Changing line styles and line width
- Using different colors for plots
- Customizing marker face and edge colors

### 3. Titles, Labels, and Formatting
- Adding plot titles
- Setting X-axis and Y-axis labels
- Customizing title position
- Changing font family, size, and color

### 4. Multiple Plots and Subplots
- Displaying multiple lines in one plot
- Creating horizontal and vertical subplots
- Displaying multiple plots in a single figure

### 5. Scatter Plots
- Creating scatter plots using `plt.scatter()`
- Customizing point colors and sizes
- Applying different colors to individual points
- Using color maps for visualization

### 6. Bar Charts
- Creating bar charts using `plt.bar()`
- Creating horizontal bar charts using `plt.barh()`
- Customizing bar colors and appearance

### 7. Histograms
- Creating histograms using `plt.hist()`
- Understanding the distribution of numerical data

### 8. Box Plots
- Creating box plots using `plt.boxplot()`
- Visualizing data distribution and variability

### 9. Pie Charts
- Creating pie charts using `plt.pie()`
- Adding labels to chart segments
- Customizing colors and chart appearance
- Highlighting sections using the explode parameter
- Displaying percentages and legends

## 💻 Sample Code

```python
import matplotlib.pyplot as plt
import numpy as np

# Sample data
x = np.array([1, 2, 3, 4, 5])
y = np.array([10, 20, 15, 30, 25])

# Create a line plot
plt.plot(
    x, y,
    marker='o',
    linestyle='--',
    color='blue'
)

# Add title and labels
plt.title("Sample Data Visualization")
plt.xlabel("X Values")
plt.ylabel("Y Values")

# Display the plot
plt.show()
```

## ▶️ How to Run the Notebook

1. Clone or download this repository.
2. Install Python on your computer.
3. Install the required libraries:

   ```bash
   pip install matplotlib numpy notebook
   ```

4. Open a terminal in the project folder.
5. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

## 🎓 Learning Outcomes

Through this notebook, I am developing practical skills in:

- Python data visualization
- Creating and customizing different chart types
- Representing numerical data graphically
- Understanding data distributions
- Improving the presentation of data
- Building visualization skills for data analytics projects

## 🚀 Future Learning

I plan to apply these visualization techniques to real-world datasets and continue developing my skills in Pandas, Seaborn, SQL, and Power BI.

## 👩‍💻 Author

**Anagha Sajeev**

 Data Analyst Intern  | Python | NumPy | Pandas | Matplotlib | SQL | Power BI

---

⭐ This repository documents my learning journey in Python data visualization. Feedback and suggestions are welcome!
