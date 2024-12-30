## Country Data
[![](Image.jpg)](https://unsplash.com/photos/a-close-up-of-a-screen-tcJ6sJTtTWI)

### Overview
This project applies Principal Component Analysis (PCA) to a dataset containing country-level features. The goal is to reduce dimensionality while retaining most of the variance, enabling a more compact representation of the data. PCA is used to:
- Analyze the structure and variance of the dataset.
- Visualize the data in reduced dimensions.
- Evaluate reconstruction accuracy after dimensionality reduction.

<br>

### Project Workflow

1. **Data Preprocessing:**
    - Removed the 'country' column to focus on numerical features.
    - Standardized the data using StandardScaler to ensure zero mean and unit variance.

2. **Exploratory Data Analysis:**
    - Visualized the distribution of each feature before and after scaling.
    - Examined correlation matrices to understand relationships between features.

3. **PCA Application:**
    - Performed PCA on the standardized data.
    - Determined the explained variance for each principal component.
    - Identified the minimum number of components required to retain 95% variance.

4. **Evaluation:**
    - Calculated the reconstruction error (Mean Squared Error) to measure how well the reduced data approximates the original dataset.
    - Visualized the data using the first two principal components.

<br>

### Key Features

- **Data Scaling:** Essential preprocessing step to ensure accurate PCA results.
- **Cumulative Variance Analysis:** Determined how many components capture the majority of the data's variance.
- **Reconstruction Accuracy:** Measured using the Mean Squared Error to validate PCA performance.
- **Dimensionality Reduction:** Visualized the dataset in 2D space using the first two principal components.

<br>

### Results

- **Explained Variance:** The first few principal components retained most of the dataset's variance.
- **Optimal Number of Components:** Retaining 95% of variance required [number] components (determined dynamically).
- **Reconstruction Error:** Achieved a low Mean Squared Error, indicating effective dimensionality reduction.
- **Visualization:** Successfully plotted the data in 2D using the top two components, revealing underlying patterns.

<br>

### Repository Contents

- **`Data`:** Contains the [Original Dataset](https://www.kaggle.com/datasets/parnianmalekian/country-dataset) and you can see the cleaned dataset in notebook.
- **`Notebook`:** Jupyter notebook detailing the entire process, including data cleaning, visualization and modeling.
- **`README.md`:** Project documentation.

<br>

### How to Contribute
Contributions are welcome! If you'd like to improve the project or add new features:

1. **Fork the repository.**
2. **Create a new branch.**
3. **Make your changes and submit a pull request.**
