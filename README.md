# Melbourne Housing Prices
This repository is my encounters with the [Melnourne Housing Snapshot](https://www.kaggle.com/dansbecker/melbourne-housing-snapshot) dataset.<br>
I've done the exploratory data analysis of the dataset a clear understanding of terms and trends. The dataset had 13,580 examples which I splitted into 12,222 training examples and 1,358 test exapmles. The dataset has 21 columns, each of which indicated important information details of which are expalained in my EDA.<br>
<br>
This repository has 3 files:<br>
1. [Dataset](https://github.com/dochimekashiariri/Melbourne-Housing-Prices/blob/master/melb_data.csv)
2. [EDA](https://github.com/dochimekashiariri/Melbourne-Housing-Prices/blob/master/EDA.ipynb)
3. [Regression Model](https://github.com/dochimekashiariri/Melbourne-Housing-Prices/blob/master/Model.ipynb)
<br>
<br>
This data was trained on nine features - ** Rooms, Type, Distance, Bathrooms, Car, Landsize, Lattiude, Longtitude, and Propertycount** by models, **Polynomial Regression**, **Lasso Regression**, and **Decision Tree Regressor**. The R<sup>2</sup> Score of the models are mentioned in the table below.<br><br>

1. Polynomial Regression -  **0.999999999999997**    
2. Lasso Reggression - **0.9999916206262129** 
3. Decision Tree Regressor - **0.9999942091830432**   
<br>

From the above results it is pretty evident that in this case **Polynomial Regression** works better than **Lasso Regression** which works better than **Decision Tree Regressor** .<br> 

