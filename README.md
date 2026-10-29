# City Hotspot Identification Using Smart Cyber Physical Social System

## Project Overview
This academic project explores hotspot identification using data analysis and network-based visualization. It analyzes province-level metrics and census-related variables to identify influential hotspots and visualize relationships between locations.

## Objectives
- Analyze province-level node metrics and census variables.
- Identify and visualize the top 10 influential hotspots.
- Explore relationships between locations using a network graph.
- Apply dimensionality reduction analysis using Principal Component Analysis (PCA).
- Present analytical results through visualizations.

## Methodology
1. **Data Collection:** Use the available province-level metrics and census-variable datasets.
2. **Data Preparation:** Load the datasets and prepare relevant variables for analysis.
3. **Hotspot Analysis:** Analyze node metrics to identify influential locations.
4. **Network Visualization:** Represent locations as nodes and their connections as edges.
5. **PCA Analysis:** Examine cumulative explained variance across different numbers of components.
6. **Result Visualization:** Generate charts to communicate the analysis results.

*Note: This methodology is based on the available output screenshots and filenames. Update it after verifying the exact steps implemented in `model.py` and `model.ipynb`.*

## Results and Visualizations

### 1. Top 10 Influential Hotspots
A bar chart displays the top 10 locations selected by the project. The plotted combined influence scores appear close to 1.0.

**Observation:** The current chart shows similar scores for the displayed locations. The exact ranking and score calculation should be verified in the source code before drawing conclusions.

### 2. Network Graph
The network graph represents locations as nodes and connections as edges. It provides a visual overview of relationships and connected groups in the network.

**Observation:** Several nodes and labels overlap in dense areas. Improving the graph layout and label placement would make the relationships easier to interpret.

### 3. PCA Explained Variance
The cumulative explained variance chart shows how the amount of variance represented changes as the number of principal components increases.

**Observation:** The plotted curve approaches 1.0 quickly. The number of components required to reach a chosen variance threshold should be confirmed from the actual PCA results.

## Technologies and Concepts
- Python
- Jupyter Notebook
- CSV datasets
- Data analysis and visualization
- Network graph visualization
- Principal Component Analysis (PCA)

*The exact Python libraries and algorithms should be listed after checking the source code.*

## Repository Files

| File | Description |
|---|---|
| `model.py` | Python source code |
| `model.ipynb` | Jupyter Notebook |
| `All_Province_Node_Metrics.csv` | Province-level metrics dataset |
| `ISTAT_census_variables_2011.csv` | Census-variable dataset |
| `Top10_Hotspots.csv` | Top 10 hotspot results |

## How to Run
1. Clone or download this repository.
2. Install Python 3.x and Jupyter Notebook.
3. Install the required packages after checking the imports in `model.py` and `model.ipynb`.
4. Open `model.ipynb` in Jupyter Notebook and run the cells in order, after confirming the dataset paths.

## Project Type
Academic Project

## Author
B.Tech Computer Science and Engineering Graduate
