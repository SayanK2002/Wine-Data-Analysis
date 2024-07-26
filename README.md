# Wine-Data-Analysis

This project analyzes a wine quality dataset to understand the factors affecting wine quality. The analysis involves data visualization and data preprocessing for machine learning tasks. I have used various ML models in this project and compared their prediction accuracies. For this project, I have converted the target values to binary values (0 and 1) where each wine is either good quality(having a rating of 7 or more) or not (having a rating below 7).

## Dataset

The dataset used in this project is the Wine Quality dataset, characterized by 11 physicochemical properties such as acidity, pH, alcohol content and more.  Each sample is rated on a quality scale from 0 to 10, based on sensory data provided by wine experts. The dataset aims to explore the relationship between these chemical properties and the perceived quality of the wine, providing a rich ground for classification and regression analysis. The name of the dataset is `winequality-red.csv`

## Project Workflow

The project consists of the following steps:

1. **Data Loading and Data Exploration**
   - At first, we loaded the dataset using pandas.
   - Displayed the first few rows of the dataset.
   - Checked the shape of the dataset.

2. **Data Visualization**
   - Used a heatmap to visualize missing values and other correlations in our dataset.
   - Dropped the duplicate and irrelevant values from our dataset.
   - Plotted histograms to understand the distribution of each feature.
   - Compared each attribute with the `quality` rating using scatter plots.

3. **Analysis of Specific Questions**
   - Determining whether sweeter wines receive better ratings from drinkers.
   - Determining which level of acidity receives the highest average rating.
   - Analyzing the quantity of wines produced according to quality ratings.

4. **Data Preprocessing for Machine Learning**
   - Converting the quality ratings into a binary classification for machine learning tasks (0 if rating<7 else 1).
   - Implementation of feature selection and regression tasks.

5. **Model Training and Evaluation**
   - Training multiple machine learning models to predict wine quality.
   - Evaluating the accuracy of the models and comparing them at the end.

## ML Models used:
  1. Logistic Regression
  2. KNN (highest accuracy)
  3. Decision Tree
  4. Random Forest
  5. ANN

## Outcomes and Observations

- The correlation heatmap reveals the relationships between different properties and wine quality.
- Wines with slightly more acidity tend to have better ratings.
- There is close competition between sweet and less sweet wines regarding their quality ratings.
- The distribution of wine quality ratings shows the number of wines produced in each quality category.

## Model Comparison

Below is a screenshot of the accuracies achieved by the machine-learning models:

![download](https://github.com/user-attachments/assets/022bfad6-042d-47e5-bdd7-b76d147097c0)

## Usage

To run the analysis, please follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/wine_quality_analysis.git

2. Navigate to the project directory:
   ```sh
   cd wine_quality_analysis

3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
4. Run jupyter Notebook or google colab:
   ```sh
   jupyter notebook notebooks/wine_quality_analysis.ipynb

## Requirements
- Python 3.x
- Jupyter Notebook (or Google Colab)
- Scikit-learn
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Install these libraries: `pip install numpy pandas matplotlib seaborn scikit-learn`

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes (and please upvote if you liked my work!).
