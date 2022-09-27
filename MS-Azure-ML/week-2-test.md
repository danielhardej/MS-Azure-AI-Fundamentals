# Microsoft Azure Machine Leaning
## Week 2 Test

### What features and capabilities are available in Azure Machine Learning?

- [x] Train models
- [x] Prepare data
- [x] Publish predictive services
- [x] Monitor usage of used services

*Azure Machine Learning is a cloud-based service with a wide range of features and capabilities that help data scientists to prepare data, train models, publish predictive services, and monitor their usage.*

### True or False? After creating and running a pipeline to train the model, you need a second pipeline that performs the same data transformations for new data, and then uses the trained model to predict label values based on its features.

- [x] True
- [ ] False

*An inference pipeline will form the basis for a predictive service that you can publish for applications to use.*

### What type of compute resources can be created in Azure Machine Learning Studio?

- [x] Attached compute
- [x] Inference clusters
- [ ] Spot clusters
- [x] Compute instances
- [x] Compute clusters

*The four types of compute resources available in Azure Machine Learning Studio are: Compute instances, Compute Clusters, Inference clusters and Attached Compute.*

### You are creating a training pipeline for a regression model and you want to make sure that the dataset is complete, otherwise you need to perform various operations to fix the data. Which module should you add to the pipeline?

- [ ] Normalize data
- [x] Clean missing data
- [ ] Select columns in a dataset


*Clean missing data helps to check data for missing values and then perform various operations to fix the data or insert new values. The goal of such cleaning operations is to prevent problems caused by missing data that can arise when training a model.*


### You are creating a training pipeline for a regression model and your dataset contains hundreds of columns. For a particular part of your model, you want to use data only from some specific columns. Which module should you add to the pipeline?

- [x] Select columns in a dataset
- [ ] Clean missing data
- [ ] Normalize data

*This module is used to choose a subset of columns to use in downstream operations.*

### Which of the following scenarios can be resolved by using a regression model?

- [x] Predict daily rental demand of bicycles by using historic data.
- [ ] Determine if patients with some pre-existing conditions are more likely to suffer from diabetes
- [x] Predict selling price of a car using data like engine size, mileage, number of seats etc.
- [x] Predict yearly income of customers based on their occupation, age, education etc.

*Regression is a form of machine learning that is used to predict a numeric label based on an item's features*

### You created a machine learning model and trained it. Now you want to run the model to predict data. Which compute target should you use?

- [ ] Compute Instances
- [ ] Compute Clusters
- [x] Inference Clusters

*sInference Clusters are used as deployment targets for predictive services that use your trained models.*
