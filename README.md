# Weather_prediction

How to do weather prediction?

1. Kindly download the dataset from https://www.kaggle.com/datasets/ananthr1/weather-prediction

2. The dataset is a collection of daily features and weather labels from 1 January 2012 to 31 December 2015.

3. The features are precipitation, maximum temperature, minimum temperature, and wind. And the prediction column is weather, which have dizzle, fog, rain, snow, sun classes.

4. I used random forest model to input features and output prediction.

5. There are only some ground truths for dizzle, fog, snow. Therefore, I tried to oversample the samples by using SMOTE.

6. I used correlation matrix to find similar features and feature importances to find important features.
