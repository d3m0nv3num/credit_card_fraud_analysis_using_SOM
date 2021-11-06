# credit_card_fraud_analysis_using_SOM
this is a model for analysis of credit card fraud transactions, the name and identity and column names have been anonymized by kaggle dataset consisting of over 2.84lakh datarows over 31 columns.
By the use of SOM(self organising maps) an unsupervisied implementation of deep learning the high dimensionality is reduced to a form which can be visualized and analysed by people.
A random point in dataset is pciked and its distance to all the node is calculated and one with minimum value gets awarded with adjustment in weights and move closer to datapoint and the wieghts of neighbouring neurons are adjusted accordingly and this process is iterated till no more changes in neighbouring neurons are required.
Red shapes(partially visible in some cases) indicate the frauds and yellow shapes indicated the proper transactions 
with the model the value of x and y can be changed according with the marker values to get a different scaling for graph.
Three sample scaling outputs have been attached 15X15,25X25 and 35X35.*note: the image quality is normal, so for identifying red circles a zooming and good look is required.
