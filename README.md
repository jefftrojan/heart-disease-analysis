# Heart Disease Clustering Analysis

## Project Overview
This project performs clustering analysis on the UCI Heart Disease dataset to identify patterns and groups among patients based on their medical characteristics. The analysis employs multiple clustering algorithms and evaluates their performance to determine the most effective approach for grouping patients with similar health profiles.

## Dataset
- **Source**: UCI Machine Learning Repository - Heart Disease Dataset
- **Size**: 303 instances
- **Features**: 14 attributes including:
  - Age
  - Sex
  - Chest pain type
  - Blood pressure
  - Serum cholesterol
  - And more
- **Target Variable**: Presence/absence of heart disease

## Technologies Used
- Python 3.x
- Key Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - scipy

## Methodology
1. **Data Preprocessing**
   - Handled missing values
   - Scaled numerical features
   - Encoded categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Correlation analysis
   - Feature relationship visualization

3. **Clustering Algorithms Applied**
   - K-means clustering
   - Hierarchical clustering
   - DBSCAN
   - Gaussian Mixture Models (GMM)

4. **Dimensionality Reduction**
   - Principal Component Analysis (PCA)
   - t-SNE visualization

5. **Performance Evaluation**
   - Silhouette Score
   - Davies-Bouldin Index

## Key Findings
1. **Optimal Clustering**
   - K-means performed best with 3 clusters
   - Silhouette Score: 0.113
   - Davies-Bouldin Index: 2.531

2. **Risk Stratification**
   - Identified three main patient groups:
     - Low risk
     - Medium risk
     - High risk

3. **Feature Importance**
   - Age, cholesterol, and blood pressure were key determining factors
   - Strong correlation between age and heart disease risk

## Limitations
- Moderate cluster separation (Silhouette Score < 0.2)
- Complex overlapping patterns in medical data
- Challenging feature relationships

## Future Improvements
1. Feature engineering opportunities:
   - Create interaction terms
   - Remove less important features
   - Transform features using domain knowledge

2. Alternative approaches:
   - Try different scaling methods
   - Implement ensemble clustering
   - Explore other algorithms

## How to Run

### Prerequisites
```bash
# Install required packages
pip install numpy pandas scikit-learn matplotlib seaborn scipy
```

### Steps
1. Clone this repository
2. Navigate to the project directory
3. Run the Jupyter notebook:
```bash
jupyter notebook notebook.ipynb
```

## Results Interpretation
The clustering results show:
- K-means as the best performing algorithm
- Three distinct risk groups identified
- Typical clustering patterns for medical data
- Valuable insights for patient stratification

## Contributing
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request



## License
This project is open source and available under the MIT License.

## Acknowledgments
- UCI Machine Learning Repository for the dataset
- The medical research community for domain insights
- Open source community for tools and libraries