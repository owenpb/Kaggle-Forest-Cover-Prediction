# [Kaggle-Forest-Cover-Prediction](https://www.kaggle.com/c/forest-cover-type-prediction)

## Notebook: [kaggle-forest-cover.ipynb](https://github.com/owenpb/Kaggle-Forest-Cover-Prediction/blob/main/kaggle-forest-cover.ipynb)

In this competition, the task is to predict the forest cover type (the predominant kind of tree cover) from cartographic variables. Each observation in our dataset corresponds to a $30\textrm{m} \times 30\textrm{m}$ patch of land located in the Roosevelt National Forest of northern Colorado. There are seven possible forest cover types:

**1. Spruce/Fir** <br>
**2. Lodgepole Pine** <br>
**3. Ponderosa Pine** <br> 
**4. Cottonwood/Willow** <br>
**5. Aspen** <br>
**6. Douglas-fir** <br>
**7. Krummholz** <br>

The training dataset for this Kaggle competition consists of $15120$ samples with $56$ features (a mixture of both continuous and categorical data), including the **Cover_Type** represented by an integer $\{1,2,3,4,5,6,7\}$. Our task is to classify test samples by cover type (i.e. this is a multi-class classification task).

We use a variety of classification techniques, including:

**1. Logistic Regression** <br>
**2. Support Vector Classifier** <br>
**3. K-Nearest Neighbors** <br>
**4. Decision Tree** <br>
**5. Random Forest** <br>
**6. XGBoost**<br>
**7. AdaBoost**<br>
**8. LightGBM**<br>
**9. Extra Trees Classifier**<br>

After tuning hyperparameters with GridsearchCV, our best model achieves a test score within the top 6.1% of the Kaggle leaderboard. For additional details and background information related to this dataset, see the Kaggle competition page at [kaggle.com/c/forest-cover-type-prediction](kaggle.com/c/forest-cover-type-prediction). 