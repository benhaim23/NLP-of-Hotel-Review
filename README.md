# NLP with Hotel Reviews

## Overview
This project, conducted as part of an assignment for Hotel Management Inc., applies Natural Language Processing (NLP) techniques to understand key factors that contribute to customer satisfaction in hotel stays. By analyzing hotel reviews and associated stay details, this study aims to uncover insights that can help improve customer experiences and satisfaction ratings.

## Assignment Instructions

### Exploratory Data Analysis (EDA)
- **Objective**: Load the data and perform EDA to draw actionable insights.
- **Tasks**:
  - Create a data dictionary.
  - Conduct basic statistical analysis.
  - Produce data visualizations.
  - Preprocess data for modeling.

### Preprocessing
- **Objective**: Prepare text data for modeling.
- **Tasks**:
  - Split the data into training and testing sets.
  - Use CountVectorizer with a cap of 500 features and exclude tokens appearing less than 10 times.
  - Merge vectorized text data with numeric features, using prefixes for clarity (e.g., `pos_` for positive reviews).

### Modeling
- **Objective**: Develop models to predict customer satisfaction.
- **Tasks**:
  - Fit and evaluate a logistic regression model.
  - Use a PCA-enhanced decision tree within a pipeline.
  - Optimize hyperparameters using 5-fold cross-validation.
  - Analyze model performance through metrics like precision and recall.

### Data and Resources
- **Dataset**: [Download the Dataset](https://drive.google.com/file/d/1NmNlJoaohuN2HqVGQz7twEb2iYqVI4M9/view?usp=sharing)
- **Jupyter Notebook**: (attached)

## How to Run the Notebook
Ensure Jupyter and necessary Python libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `nltk`) are installed. Open the downloaded `.ipynb` file in Jupyter and execute the cells in sequence to replicate the analysis.

## Requirements
- Python 3.x
- Jupyter
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK

## Author
- **Mark Benhaim**
- 📧 [Email](mailto:markbenhaim0@gmail.com or mbenhaim@umich.edu)
- 🌐 [LinkedIn](https://www.linkedin.com/in/mark-benhaim)
- 📁 [GitHub](https://github.com/benhaim23)

Feel free to reach out for discussions on potential improvements or collaborations on similar projects.
