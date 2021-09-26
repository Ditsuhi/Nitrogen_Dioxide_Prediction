# Bidirectional convolutional LSTM for the prediction of nitrogen dioxide in the city of Madrid

Nitrogen dioxide is one of the pollutants with the greatest health effects. Advanced information on its concentration in the air can help to monitor and control further consequences more effectively, while also making it easier to apply preventive and mitigating measures. Machine learning technologies with available methods and capabilities, combined with the geospatial dimension, can perform predictive analyses with higher accuracy and as a result  can serve as a supportive tool for productive management. One of the most advanced machine learning algorithms, Bidirectional convolutional LSTM, is being used in ongoing work to predict the concentration of nitrogen dioxide. The model has been validated to perform spatiotemporal analyses with higher accuracy, which means that in addition to the temporal factor, the geospatial factor is also taken into account in order to produce more accurate predictions. The analysis was carried out in the city of Madrid from January to June 2019 with time lags of 6 hours and 12 hours in two scenarios developed on the basis of the features used. The  Root Mean Square Error was taken as an evaluation metric. The results show that the proposed model performs comparably better than Convolutional LSTM and the feature selection technique significantly improved the overall accuracy. In terms of runtime, the Bidirectional Convolutional LSTM took longer to converge, which can be explained by the complexity of the model; moreover, it converged faster in a 12-hour lag than the 6-hour lag, which is related to the size of the training sets.


The dataset is available in the Zenodo repository with the following DOI:https://doi.org/10.5281/zenodo.5101390.

The _AirMetDataGeneration.ipynb_ and _TrafficDataGeneration.ipynb_ files contain Python code for generating data using ArcGIS Pro software, which as an input was used for prediction algorithms.
The _BiConvLSTM_NO2.ipynb_ file inludes data preprocessing and predictive analysis.




