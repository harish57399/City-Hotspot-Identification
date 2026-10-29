# City Hotspot Identification Using Smart Cyber Physical Social System

## Project Overview
This academic project focuses on identifying influential hotspots using province-level metrics, census-related data, and network visualization. Python-based analysis is used to explore location relationships and present hotspot-related results.

## Objectives
- Analyze province-level node metrics.
- Explore census-related variables.
- Identify and visualize the top 10 influential hotspots.
- Visualize relationships between locations using a network graph.
- Study cumulative explained variance using Principal Component Analysis (PCA).

## Methodology
1. **Data Input:** Load the available CSV datasets.
2. **Data Preparation:** Prepare the data for analysis.
3. **Hotspot Analysis:** Examine node metrics to identify influential locations.
4. **Network Visualization:** Represent locations as nodes and connections as edges.
5. **PCA Visualization:** Plot cumulative explained variance across components.
6. **Result Presentation:** Display the results using charts and graphs.

*Note: Verify these steps against the source code before presenting them as the exact implemented methodology.*

## Results and Observations

### 1. Top 10 Influential Hotspots
The bar chart displays ten locations with combined influence scores close to 1.0. The score calculation and ranking should be verified from the source code.

### 2. Network Graph
The network graph represents locations and their connections. It helps visualize connected groups and relationships between locations.

### 3. PCA Explained Variance
The PCA chart illustrates how cumulative explained variance changes as the number of components increases. The exact number of components needed to reach a selected variance threshold should be confirmed from the computed results.

## Technologies and Concepts
- Python
- Jupyter Notebook
- CSV datasets
- Data analysis and visualization
- Network analysis
- Principal Component Analysis (PCA)

*Confirm the exact libraries and algorithms from the source code before adding them to this list.*

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
3. Check the imports in the source code and install the required packages.
4. Open `model.ipynb` in Jupyter Notebook.
5. Verify the dataset paths and run the notebook cells in order.

## Project Type
Academic Project

## Author
B.Tech Computer Science and Engineering Graduate
