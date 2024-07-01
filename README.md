# Diabetes Prediction using Fusion-Ensemble Machine Learning Techniques

## Introduction

This repository contains the code and data for the paper "Anticipating Diabetes using Fusion-Ensemble Machine Learning Techniques" by Alber S. Aziz, Khaled Ibrahim, Ahmed Elsharkawy, and Nariman Khaliel.

Diabetes mellitus (DM) is a chronic metabolic disorder that affects carbohydrate, protein, and fat metabolism. This project aims to develop a decision support system for predicting the probability of diabetes using machine learning algorithms and fuzzy logic to handle uncertainty. The prediction model is created using various classification algorithms, and a fusion (ensemble) model is implemented to enhance classification accuracy.

## Dataset

The dataset used in this project is sourced from Kaggle and contains the following attributes:
- Plasma glucose concentration
- Two hours of serum insulin
- Age
- Class variable (1: tested positive for diabetes, 0: tested negative for diabetes)
- Blood pressure
- BMI (Body Mass Index)
- Insulin sensitivity
- Skin Thickness
- Pregnancy

## Methodology

1. **Data Collection and Preprocessing**
    - The dataset is preprocessed to handle missing values, normalize features, and encode categorical variables.
    
2. **Model Development**
    - The prediction model is built using 12 classification algorithms from Scikit-learn.
    - The accuracies of these algorithms are compared to identify the best-performing model.
    - A fusion (ensemble) model is applied to improve classification accuracy by combining multiple classifiers.

## Results

The fusion (ensemble) model demonstrated enhanced accuracy in predicting diabetes compared to individual classifiers, proving its potential as a reliable decision support system for healthcare providers.

## Getting Started

### Prerequisites

To run the code in this repository, you need to have the following libraries installed:

- Python 3.x
- Scikit-learn
- Pandas
- Numpy
- Matplotlib

### Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/diabetes-mellitus-implementation.git
    cd diabetes-mellitus-implementation
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. Download the dataset from Kaggle and place it in the `data` directory.

2. Run the preprocessing script to clean and prepare the data:

    ```bash
    python preprocess_data.py
    ```

3. Train the models and compare their accuracies:

    ```bash
    python train_models.py
    ```

4. Apply the fusion (ensemble) model:

    ```bash
    python ensemble_model.py
    ```

5. Evaluate the model performance and view the results:

    ```bash
    python evaluate_model.py
    ```


## Authors

- Alber S. Aziz "albershawky.csis@o6u.edu.eg"
- Khaled Ahmed Ibrahim "khaledahmed872003@gmail.com"
- Ahmed Elsharkawy "ahmed.yaser.el.sharkawy@gmail.com"
- Nariman Khaliel "narimankhaliel.eccat@suez.edu.eg"


## Acknowledgments

We would like to thank Kaggle for providing the dataset used in this project.

## References

- [Paper DOI](https://sciencesforce.com/index.php/scin/article/view/307/475)
- [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)



