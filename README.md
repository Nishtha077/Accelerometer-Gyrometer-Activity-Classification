# Human Activity Classification using Phone Accelerometer and Gyroscope Readings

## Overview

This project aims to classify human activity (active or not) based on data collected from phone accelerometers and gyroscopes. The dataset includes readings from these sensors, and various machine learning models have been employed to predict human activity.

## Models Used

1. Logistic Regression
2. Decision Tree (CART and ID3)
3. Random Forest Classifier
4. Support Vector Machine (SVM)

## Performance Metrics

The performance of each model was evaluated using the following metrics:
- Accuracy
- Precision Score
- Recall Score
- F1 Score

## Results

After evaluating the models, it was found that the Random Forest Classifier exhibited the best performance among the tested models. However, both Random Forest and Support Vector Machine (SVM) showed promising results after hyperparameter tuning.

## Files Included

- `accelerometer_gyro_mobile_phone.ipynb`: Jupyter notebook containing the code for data collection, data preprocessing, model training, evaluation, and hyperparameter tuning.
- `README.md`: This file providing an overview of the project.

## Instructions

1. Ensure that the necessary Python libraries are installed. You can install them using `pip`:

```bash
pip install pandas numpy matplotlib scikit-learn
```

2. Open the `accelerometer_gyro_mobile_phone.ipynb` notebook in a Jupyter environment.
3. Follow the instructions within the notebook to execute the code cells sequentially.
4. Analyze the results and performance of each model.
5. Experiment with hyperparameter tuning to potentially improve model performance further.

## References

- Scikit-learn Documentation: https://scikit-learn.org/stable/index.html
- Pandas Documentation: https://pandas.pydata.org/docs/
- Matplotlib Documentation: https://matplotlib.org/stable/contents.html
