# 🐧 Penguin Insights Dashboard

An interactive **data visualization dashboard** built with **Matplotlib** and **ipywidgets**, designed to explore the [Palmer Penguins dataset](https://allisonhorst.github.io/palmerpenguins/).  
This project allows users to interactively explore penguin species characteristics, visualize distributions, and gain insights into morphological differences.

---

## 📌 Project Overview

This dashboard demonstrates:
- **Interactive scatter plots** to explore relationships between features  
- **Histograms** to analyze feature distributions with mean overlays  
- **Bar charts** showing group-wise averages with error bars  
- **Correlation heatmaps** and **boxplots** for deeper statistical insight  

All plots update in real time when any filter or widget changes.

---

## 🚀 Features

- 📊 **Scatter Plot:** Explore relationships between numerical features (color by species option)
- 📈 **Histogram:** Dynamic bin size, normalization toggle, and mean line
- 📉 **Bar Chart:** Average + standard deviation grouped by species or island
- 🔄 **Reset Button:** Restore all filters to default
- 🎨 **Professional Styling:** Clean layout with LaTeX titles, tight layout, and consistent color palette
- 🧰 **Widgets:** Dropdowns, sliders, checkboxes, and reset button for full control

---

## 📂 Repository Structure
  ```bash
penguin-insights-dashboard/
│
├── penguin_dashboard.ipynb # Main Jupyter Notebook (interactive dashboard)
├── penguin_report/ # Auto-generated report folder
│ ├── Penguin_Dashboard_Report_Custom.docx
│ ├── scatter_custom.png
│ ├── histogram_custom.png
│ ├── bar_custom.png
│ ├── boxplot_custom.png
│ └── heatmap_custom.png
├── README.md # Project documentation (this file)
└── requirements.txt # List of dependencies
```


---

## 🛠 Installation

1. **Clone the repository**
```bash
git clone https://github.com/bhayanimahek/penguin-insights-dashboard.git
cd penguin-insights-dashboard
```
