# DevelopersHub Task 1: Iris Dataset Analysis

## 📌 Task Overview
**Company:** DevelopersHub Corporation  
**Internship:** AI/ML Engineering  
**Task:** Exploring and Visualizing a Simple Dataset  

## 🎯 Objective
Learn to load, inspect, and visualize a dataset to understand data trends, distributions, and relationships using the classic Iris dataset.

## 📊 Dataset
| Property | Details |
|----------|---------|
| Name | Iris Dataset (Fisher's Iris) |
| Source | Seaborn built-in (UCI origin) |
| Samples | 150 flowers |
| Features | sepal_length, sepal_width, petal_length, petal_width |
| Target | 3 species (setosa, versicolor, virginica) |

## 🔧 Technologies Used
- Python 3.x
- Pandas - Data manipulation
- NumPy - Numerical operations
- Matplotlib - Plotting
- Seaborn - Statistical visualizations

## 📈 Visualizations Created
| Plot Type | Purpose |
|-----------|---------|
| Scatter Plots | Show relationships between features |
| Pairplot | All feature relationships matrix |
| Histograms | Distribution of values by species |
| Box Plots | Identify outliers |
| Correlation Heatmap | Feature correlation analysis |

## 📊 Key Findings

### Species Separability
- **Setosa:** Petals completely separable (1.0-1.9 cm long, 0.1-0.6 cm wide)
- **Versicolor:** Medium petals (3.0-5.1 cm long, 1.0-1.8 cm wide)
- **Virginica:** Largest petals (4.5-6.9 cm long, 1.4-2.5 cm wide)

### Strongest Correlations
- Petal length vs petal width: **0.963** (very strong positive)
- Sepal length vs petal length: **0.872** (strong positive)

### Data Quality
- ✅ No missing values (150/150 complete)
- ✅ Perfectly balanced (50 samples per species)
- ⚠️ 3 outliers detected in sepal width (>4.05 cm)

## 🚀 How to Run

### Option 1: Google Colab (Recommended)
1. Go to [Google Colab](https://colab.research.google.com/)
2. File → Upload Notebook → Select `Task1_Iris_Analysis.ipynb`
3. Run all cells (Runtime → Run all)

### Option 2: Local Jupyter
```bash
pip install -r requirements.txt
jupyter notebook Task1_Iris_Analysis.ipynb
