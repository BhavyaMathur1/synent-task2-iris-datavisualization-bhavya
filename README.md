# synent-task2-iris-datavisualization-bhavya
# 🌸 Iris Dataset — Data Visualization

**Internship:** Synent Technologies — Data Science Internship  
**Task:** Task 2 — Data Visualization  
**Level:** Basic  
**Tool used:** Google Colab, Python  

---

## 📌 Problem Statement

The goal of this project is to visualize patterns in the famous Iris dataset
using bar charts, histograms, and scatter plots to compare features across
three flower species: Setosa, Versicolor, and Virginica.

---

## 📂 Dataset Details

- **Name:** Iris Dataset  
- **Source:** Built into `sklearn.datasets` (no download needed)  
- **Rows:** 150 samples  
- **Columns:** 5 (sepal length, sepal width, petal length, petal width, species)  
- **Classes:** 3 species — Setosa, Versicolor, Virginica (50 each)  

---

## 🔧 Approach

1. Loaded the dataset using `sklearn.datasets.load_iris`
2. Converted to a pandas DataFrame for easy analysis
3. Explored data using `.describe()` and `.value_counts()`
4. Created the following visualizations:
   - **Bar chart** — average measurements per species
   - **Histogram** — distribution of each feature
   - **Scatter plot** — petal length vs petal width by species
   - **Pairplot** — all features compared across species

---

## 📊 Visualizations

| Chart | Description |
|-------|-------------|
| `chart1_bar.png` | Average sepal & petal size per species |
| `chart2_histogram.png` | Distribution of all 4 features |
| `chart3_scatter.png` | Petal length vs width, colored by species |
| `chart4_pairplot.png` | All feature combinations at once |

---

## 💡 Key Insights

1. Dataset has 150 samples — 50 per species, perfectly balanced.
2. **Setosa** has the smallest petals and is completely separable from the other two species.
3. **Virginica** has the largest petals and sepals on average.
4. **Petal length and width** are the most useful features to distinguish species.
5. **Versicolor and Virginica** overlap slightly in sepal measurements but are well-separated by petal size.
6. The pairplot clearly shows that petal features are better classifiers than sepal features.

---

## 🛠️ Libraries Used

- `pandas` — data handling  
- `numpy` — numerical operations  
- `matplotlib` — charting  
- `seaborn` — advanced visualizations  
- `sklearn` — loading the dataset  

---

## 📁 Files in this Repo



----

---

## 👤 Author

BHAVYA MATHUR  
Synent Technologies — Data Science Intern
