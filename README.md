# Forest-Cover-Classification

![cov2f](https://user-images.githubusercontent.com/64009514/97299143-81f00680-187a-11eb-9a4f-a6622dfb03b4.jpg)





A short description I want to give of how I am going to solve this project before starting. Our goal in this project is to classify which forest type it is from the data given.  This study area includes 4 Wilderness Areas located in the Roosevelt National Forest of Northern Colorado. These area represent forests with minimal human-caused disturbances, so that existing forest cover types are more a result of ecological process rather than forest management practices.  Each observation is 30m x 30m forest cover type determined from US Forest Service (USFS) Region 2 Resource Information System (RIS) data. Independent variables were derived from the data originally obtained from US Geological Survey (USGS) and USFS data.  I have been given a total of 54 attributes/features, (excluding 1 target variable) these attributes contain Binary and Quantative attributes, and I need to predict which Forest Cover-Type is it from the given features. 
I will first explore the data, visualize it, know what the data wants to tell us. Remove any missing values and features that have null values and scale the data within a specific range.  Also perform dimensionality reduction procedure where I will use 4 models to tell us which are useful in order to predict the target variable, and then using features which gives us hgih score in the most models.
Those 4 Models are: 
1.Extra Trees Classifier (ETC) 
2.Random Forest (RF)
3.AdaBoost Classifier (ADBC) 
4.Gradient Boosting Classifier (GBC)  
Split the data 75%-25%, train-test set respectively. Will use 10 K-fold Cross Validation on train set.  Feed the training data to the Naive Bayes (Our Benchmark Model) and evaluate the result.  Training will be done on the Solution Models that I have chose, those are:-     
1.K-Nearest Neighbour (KNN),     
2.Random Forest (RF),     
3.Stochastic Gradient Descent Classifier (SGDC),     
4.Extra Trees Classifier (ETC),    
5.Logistic Regression (LG)
