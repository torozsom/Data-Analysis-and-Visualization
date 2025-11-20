# Data Analysis and Visualization

This repository contains Jupyter notebooks that demonstrate data analysis and visualization workflows in Python, using popular libraries such as NumPy, Pandas, Matplotlib, Seaborn, Plotly, and Folium.

The project is intended as a compact reference / learning resource for:
- Cleaning and exploring tabular data
- Building static and interactive visualizations
- Creating geographic visualizations with Folium

---

## Repository Structure

- `notebook.ipynb`  
  General data analysis and visualization notebook.  
  - Data loading (CSV, Excel, etc.)
  - Data cleaning and preprocessing (missing values, type conversions)
  - Exploratory data analysis with pandas
  - Static visualizations with Matplotlib and Seaborn (histograms, boxplots, scatterplots, etc.)
  - Interactive charts with Plotly

- `maps_folium.ipynb`  
  Notebook focused on map-based visualizations using Folium.  
  - Setting up a base map
  - Adding markers, circles, and popups
  - Choropleth maps
  - Styling tiles and layers

- `requirements.txt`  
  Python dependencies used in the notebooks:
  - `notebook`
  - `ipykernel`
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `plotly`
  - `folium`

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/torozsom/Data-Analysis-and-Visualization.git
cd Data-Analysis-and-Visualization
```

### 2. Create and activate a virtual environment (optional but recommended)

```bash
python -m venv .venv
# On Linux/macOS:
source .venv/bin/activate
# On Windows (PowerShell):
.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter

You can use either Jupyter Notebook or JupyterLab.

```bash
jupyter notebook
# or
jupyter lab
```

Then open:

- `notebook.ipynb`
- `maps_folium.ipynb`

from the Jupyter interface.

---

## Usage

You can:

- Run the notebooks cell by cell to follow the analysis steps.
- Modify the data-loading cells to point to your own datasets.
- Experiment with different plotting options (colors, styles, plot types).
- Extend the Folium notebook to visualize your own geospatial data (e.g., points of interest, aggregated statistics per region, etc.).

If the notebooks expect specific data files (e.g., CSVs), you can add a short section here later (e.g. “Place `data.csv` in a `data/` directory”).

---

## Requirements

All Python dependencies are listed in [`requirements.txt`](requirements.txt).

The code has been tested with recent Python 3 versions (e.g. 3.10+ is recommended).

---

## Possible Extensions

Ideas for future improvements:

- Add example datasets and document where they come from.
- Add sections in the notebooks explaining the theory behind each visualization.
- Export key plots to PNG/HTML and link them here as examples.
- Turn parts of the notebooks into reusable Python modules or scripts.

---

If you use or build on this material, consider opening an issue or pull request with suggestions or improvements.
