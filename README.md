# CottonDiseaseDetection

You can find the dataset from the https://www.kaggle.com/janmejaybhoi/cotton-disease-dataset

I sincierly thank D3v for making this dataset public.

I have used Keras library to read, train, test, and predict the data.

The dataset consists of 1929 train images belongs to 4 classes and 324 test images belongs to 4 classes.

Since this dataset consists of 4 classes we can build a model from the scratch and fine tune the hyperparameters that enhaces the model performance. But here we are using Inception v3 because it works great and less bias towards the trainset. 

Used ADAM optimizer and accuracy as the evaluation metrics and 20 epochs to train the model.

**Results are amazing we got training accuracy of 96% and testing accuracy of 94%. This shows that although our model is performing execptionally well on training set it is not overfitted.**

**It's not a good idea to add training files to github because that will bloat the repo size when someone want to use it. So please visit the above provided kaggle link and help yourself.**
