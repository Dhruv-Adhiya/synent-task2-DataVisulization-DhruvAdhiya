# Iris Dataset Visualization Project

## Problem Statement

The objective of this project is to visualize patterns and relationships in the Iris Dataset using different types of data visualizations.  
The project helps in understanding the distribution of features and comparison between different flower species through graphical representation.

---

## Dataset Details

- **Dataset Name:** Iris Dataset
- **File Used:** `Iris.csv`
- **Dataset Type:** Classification Dataset
- **Total Records:** 150
- **Total Features:** 5

### Features in Dataset

| Feature Name | Description |
|---|---|
| SepalLengthCm | Length of sepal in centimeters |
| SepalWidthCm | Width of sepal in centimeters |
| PetalLengthCm | Length of petal in centimeters |
| PetalWidthCm | Width of petal in centimeters |
| Species | Type of Iris flower |

### Species Included

- Iris-setosa
- Iris-versicolor
- Iris-virginica

---

## Approach

The following steps were performed in this project:

### 1. Import Required Libraries
Used:
- Pandas
- Matplotlib
- NumPy

### 2. Load Dataset
The Iris dataset was loaded using Pandas.

### 3. Create Visualizations

#### Bar Chart
- Created a grouped bar chart to compare average measurements of different species.

#### Histogram
- Created histogram to visualize distribution of sepal length.

#### Scatter Plot
- Created scatter plot to analyze relationship between sepal length and petal length.

#### Feature Comparison
- Compared petal length and petal width for different species using scatter plot.

### 4. Save Visualizations
All generated charts were saved as image files using `plt.savefig()`.

---

## Results

The visualizations clearly showed:

- Differences between Iris species
- Distribution of flower measurements
- Relationship between different features
- Feature comparison patterns among species

### Generated Output Files

- `bar_chart.png`
- `histogram.png`
- `scatter_plot.png`
- `feature_comparison.png`

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- NumPy

---

## Conclusion

This project successfully visualized important patterns in the Iris Dataset using different graphical techniques.  
The visualizations made the dataset easier to understand and helped compare different flower species effectively.
