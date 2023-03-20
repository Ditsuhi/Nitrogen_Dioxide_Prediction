# Bidirectional convolutional LSTM for the prediction of nitrogen dioxide in the city of Madrid

Nitrogen dioxide is one of the pollutants with the most significant health effects. Advanced information on its concentration in the air can help to monitor and control further consequences more effectively, while also making it easier to apply preventive and mitigating measures. Machine learning technologies with available methods and capabilities, combined with the geospatial dimension, can perform predictive analyses with higher accuracy and, as a result, can serve as a supportive tool for productive management. One of the most advanced machine learning algorithms, Bidirectional convolutional LSTM, is being used in ongoing work to predict the concentration of nitrogen dioxide. The model has been validated to perform more accurate spatiotemporal analysis based on the integration of temporal and geospatial factors. The analysis was carried out according to two scenarios developed on the basis of selected features using data from the city of Madrid for the periods January-June 2019 and January-June 2020. Evaluation of the model's performance was conducted utilising the Root Mean Square Error and the Mean Absolute Error which emphasises the superiority of the proposed model over the reference models. In addition, the significance of a feature selection technique providing improved accuracy was underlined. In terms of execution time, due to the complexity of the Bidirectional convolutional LSTM architecture, convergence and generalisation of the data took longer, resulting in the superiority of the reference models.


The data were obtained from Open data portal of the Madrid City Council (https://bit.ly/2TZzwEo) and the generated dataset using Arcpy library is available in the Zenodo repository (DOI:https://doi.org/10.5281/zenodo.6076631).

The _AirMetDataGeneration.ipynb_ and _TrafficDataGeneration.ipynb_ files contain Python code for generating data using ArcGIS Pro software with Arcpy library, which as an input was used for prediction algorithms. 






