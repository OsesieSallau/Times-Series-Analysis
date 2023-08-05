# Times-Series-Analysis
This entails Data explorations and Visualizations. There is also an application of the XGBoost machine learning model used for prediction Analysis. 

Data preprocessing involved dropping of columns that were not needed for the analysis. The dates were parsed using the date time format. 
Columns were renamed and replacing missing values using the forward fill method. Visualisations of Data were carried out using Histograms. 
Temporal variables such as Seasons of the year and days of the week were created from the dataset. 
Descriptive statistics were used to investigate patterns of NO2 concentrations across the days of the week, months of the year, 
seasons and across the years investigated in the study. A prediction model was then created from the data set. A train test split was 
used to separate the training and test data set. NO2 concentrations from year 2012- year 2020, were used to predict NO2 concentrations 
for year 2020-2022. Use the XG boost regressor to create a prediction model and explore feature importance. Yearly and Weekly predictions 
of NO2 concentrations were made. The RMSE (Root Mean Square Error) was imported from the tensor flow libraries, and this was used to evaluate 
the accuracy of the model. The prediction Analysis showed the best ten predicted days and the worst ten predicted days based on accuracy 
between the predicted and actual values.
