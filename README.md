# 🌸 Task 1: Exploring and Visualizing the Iris Dataset
**DevelopersHub Corporation — AI/ML Engineering Internship**

---

## 📌 Task Objective
Load, inspect, and visualize the Iris dataset to understand data trends, distributions, and relationships between features using Python data science libraries.

---

## 📂 Dataset Used
- **Name:** Iris Dataset
- **Source:** Loaded directly via `seaborn.load_dataset('iris')`
- **Size:** 150 rows × 5 columns
- **Features:** `sepal_length`, `sepal_width`, `petal_length`, `petal_width`, `species`
- **Classes:** Setosa, Versicolor, Virginica

---

## 🛠️ Libraries & Tools
| Library | Purpose |
|---|---|
| `pandas` | Data loading, inspection, and summary statistics |
| `seaborn` | Statistical visualizations (scatter, box plots) |
| `matplotlib` | Histograms and plot customization |

---

## 🔍 Steps Performed

1. **Data Loading** — Loaded the Iris dataset using `seaborn` and converted to a pandas DataFrame
2. **Inspection** — Checked shape, column names, `.head()`, `.info()`, and `.describe()`
3. **Scatter Plot** — Visualized relationships between `sepal_length` and `petal_length`, colored by species
4. **Histograms** — Plotted value distributions for all four numerical features
5. **Box Plots** — Identified outliers across species for each feature

---

## 📊 Models Applied
> This task is focused on **Exploratory Data Analysis (EDA)** — no predictive model was trained.

---

## 💡 Key Results & Findings

- **Setosa** is clearly separable from the other two species based on petal length and width alone
- **Versicolor** and **Virginica** show some overlap, making them harder to distinguish visually
- **Petal features** show stronger class separation compared to sepal features
- A few **outliers** were identified in `sepal_width` for the Setosa class via box plots
- Histograms confirmed that `petal_length` and `petal_width` have **bimodal distributions**, hinting at natural class groupings

---

## 📁 File Structure
```
task1-iris-eda/
│
├── iris_eda.ipynb        # Main Jupyter Notebook
├── README.md             # Project summary (this file)
└── plots/                # Saved visualization images (optional)
```

---

## ▶️ How to Run

```bash
# Install dependencies
pip install pandas seaborn matplotlib jupyter

# Launch notebook
jupyter notebook iris_eda.ipynb
```

---

## 👤 Author
**Abdul Samad**
AI/ML Engineering Intern — DevelopersHub Corporation
