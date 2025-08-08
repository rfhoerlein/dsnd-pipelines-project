# Clothing Review Sentiment Analysis

This project builds a machine learning pipeline to predict whether a clothing review is positive or negative based on user reviews data. The model processes numerical, categorical, and text features using appropriate preprocessing steps, including lemmatization of review text, then trains a Random Forest classifier to predict if a review is recommended or not.

## Getting Started

Instructions for how to get a copy of the project running on your local machine.

### Dependencies

pandas
scikit-learn
spacy
matplotlib

Download the Spacy English model:

python -m spacy download en_core_web_sm

### Installation

1) Clone or download the project repository.

2) Install the required Python packages:

    pip install pandas scikit-learn spacy matplotlib
    python -m spacy download en_core_web_sm

3) Ensure the dataset reviews.csv is placed inside the data/ folder.

## Testing

To test model performance, run the script which outputs initial and final accuracy and F1 scores.

### Break Down Tests

- Initial Model Fit and Predict: Fits the pipeline with default parameters and predicts on test set.
- Parameter Search: Uses RandomizedSearchCV to tune hyperparameters for improved performance.
- Evaluation: Compares metrics before and after hyperparameter tuning.

## Project Instructions

This section should contain all the student deliverables for this project.

## Built With

* [pandas](https://pandas.pydata.org/) - Data manipulation and analysis
* [scikit-learn](https://scikit-learn.org/stable/) - Machine learning library for Python
* [spaCy](https://spacy.io/) - Industrial-strength natural language processing
* [matplotlib](https://matplotlib.org/) - Plotting and visualization

## License

[License](LICENSE.txt) - This project is licnesed under Udacity license - see the LICENSE.txt file for details.
