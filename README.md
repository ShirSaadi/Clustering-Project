### Clustering Project README

#### Overview
This repository contains code and documentation for a clustering project focused on analyzing articles from Kos Daily, a political blog covering the 2004 United States presidential election. The project explores and implements clustering algorithms to uncover thematic patterns and relationships within the dataset.

#### Dataset
The dataset (`MB10.1 - CSV (dailykos)`) comprises 3,430 articles published in Kos Daily during the election period. Each article's content is represented as word frequencies after preprocessing.

#### Project Structure
- `data/`: Contains the dataset file.
- `scripts/`: Includes Python scripts for clustering algorithms, data preprocessing, and visualization.
- `results/`: Stores output files, such as CSV files for clustered data and visualization plots.

#### Techniques Used
1. **Clustering Algorithms:**
   - Implemented K-means and DBSCAN clustering algorithms using sklearn.
   - Evaluated cluster quality using SSE, silhouette scores, and elbow method for K-means.

2. **Dimensionality Reduction:**
   - Applied PCA to reduce dimensionality and visualize clusters in a lower-dimensional space.

3. **Visualization:**
   - Used t-SNE and MDS algorithms for scatter plot visualization of clustered data points.

#### Results
- Identified distinct themes within clusters, such as discussions on the Iraq War, election polls, party rivalries, and primary elections.
- PCA significantly improved clustering quality, leading to clearer cluster formations.
- Optimal cluster counts: 4 clusters for both K-means and DBSCAN.

#### Dependencies
- Python 3.x
- numpy, pandas, matplotlib, seaborn
- sklearn

#### Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/ShirSaadi/clustering-project.git
   cd clustering-project
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the scripts in the `scripts/` directory according to your analysis needs.

#### Future Improvements
- Explore additional clustering algorithms (e.g., hierarchical clustering, spectral clustering) for comparison.
- Implement text mining techniques for more advanced feature extraction.
- Enhance visualization techniques for deeper insights into cluster characteristics.

#### Author
Shir Saadi

Feel free to use and modify according to your needs.
