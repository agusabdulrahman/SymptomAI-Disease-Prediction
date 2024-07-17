# Disease Prediction from Symptoms

This project explores the use of machine learning algorithms to predict diseases from symptoms.

### Algorithms Explored

The following algorithms have been explored in code:

1. Naive Bayes
2. Decision Tree
3. Random Forest
4. Gradient Boosting

# Dataset

### Source

The dataset for this problem used with the Jupyter notebook is downloaded from here:

```
https://impact.dbmi.columbia.edu/~friedma/Projects/DiseaseSymptomKB/index.html
```

This dataset has 3 columns:

```
Disease  | Count of Disease Occurrence | Symptom
```

You can either copy paste the whole table from here to an excel sheet or scrape it out using Beautifulsoup.

# Directory Structure

```
|_ dataset/
         |_ training_data.csv
         |_ test_data.csv

|_ saved_model/
         |_ [ pre-trained models ]

|_ main.py [ code for laoding kaggle dataset, training & saving the model]

|_ notebook/
         |_ dataset/
                  |_ raw_data.xlsx [Columbia dataset for notebook]
         |_ Disease-Prediction-from-Symptoms-checkpoint.ipynb [ IPython Notebook for loading Columbia dataset, training model and Inference ]
```

# Usage

Please make sure to install all dependencies before running the demo, using the following:

```
pip install -r requirements.txt
```

## Interactive Demo

For running an interactive demo or sharing it with others, please run `demo.py` using Jupyter Notebook or Jupyter Lab.

```
jupyter notebook demo.ipynb
```

## Standalone Demo

For running the inference on test set or on custom inputs, you can also use the `infr.py` file as follows:

```
python infer.py
```

**NOTE:** **_This project is for demo purposes only. For any symptoms/disease, please refer to a Doctor._**
