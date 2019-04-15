# Transfer_Learning
In this project, machine learning (ML) methods were used to predict and forecast quantitative characteristics of water bodies. Such predictions are aimed at providing water researchers with a better grasp on how various characteristics relate to each other. Machine learning models are highly dependent on data availability. For measuring stations where data is abundant, ML models learn from historical data. However, where data is sparse, transfer learning can be applied. Transfer learning is the ability to leverage knowledge gained from one ML model in another. The objectives of this project are:
  • Apply transfer learning to develop predictive models.
  • Compare transferred models to stand alone models.

Two approaches have been used to achieve the prior objectives: develop and fine tuned models.
  I. Preprocessing: Missing data, 240 measurement/day
  II. Reduction: 6 hours/day
  III. Splitting: 60%:20%:20%
    i. Train and test MLP, LSTM on the 1st station
    ii. Train and test MLP, LSTM on the 2nd station
    iii. Apply 2nd station models on 1st station
  IV. Compare the accuracy of i. and iii.
  
The data was obtained from the United States Geological Survey (USGS) at two stations: 1st Rockaway and 2nd Hog Island in the USA.
The measurements used were: elevation, temperature, specific conductance, salinity, and turbidity. The data is available in six minute time intervals and ranges from 2010 to 2018 for Hog Island whereas Rockaway has data from 2014 to 2018. This data is the input of the models.
