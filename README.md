# Bidirectional convolutional LSTM for the prediction of nitrogen dioxide in the city of Madrid

Nitrogen dioxide is one of the pollutants with the most significant health effects. Advanced information on its concentration in the air can help to monitor and control further consequences more effectively, while also making it easier to apply preventive and mitigating measures. Machine learning technologies with available methods and capabilities, combined with the geospatial dimension, can perform predictive analyses with higher accuracy and, as a result, can serve as a supportive tool for productive management. One of the most advanced machine learning algorithms, Bidirectional convolutional LSTM, is being used in ongoing work to predict the concentration of nitrogen dioxide. The model has been validated to perform spatiotemporal analyses with higher accuracy, which means that in addition to the temporal factor, the geospatial factor is also taken into account in order to produce more accurate predictions. The analysis was carried out in the city of Madrid using the data from the periods of January-June 2019 and January-June 2020 in two scenarios developed based on the features used. The  Root Mean Square Error and the Mean Absolute Error were taken as evaluation metrics. The results show that the proposed model performs comparably better than the reference models, and the feature selection technique significantly improved the overall accuracy. In terms of runtime, the Bidirectional Convolutional LSTM took longer to converge, which can be explained by the complexity of the model.


The data were obtained from Open data portal of the Madrid City Council (https://bit.ly/2TZzwEo) and the generated dataset using Arcpy library is available in the Zenodo repository (DOI:https://doi.org/10.5281/zenodo.5101390).

The _AirMetDataGeneration.ipynb_ and _TrafficDataGeneration.ipynb_ files contain Python code for generating data using ArcGIS Pro software, which as an input was used for prediction algorithms.
The _BiConvLSTM_NO2.ipynb_ file inludes data preprocessing and predictive analysis.




