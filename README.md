# AMLS_Assignment_2021-2022


Application for Brain Tumor Classification using SVM and DNN / CNN 

In this code we explore machine learning solutions for brain tumor classification on a given data set of MRI scans of a human brain. The binary as well as the multi-class categorical classification is addressed. Classifiers based on Support Vector Machines SVM and Deep Neural Networks DNN in combination with Convolutional Neural Networks are implemented.

The project was developed on google colab. Please use colab to run the program.

You can download the dataset(AMLS-2021_dataset.zip)  on the following link: http://shorturl.at/hquDP
To run the program, you have to upload the primary dataset on the google drive under the directory A/dataset
The Test dataset under the directory A/test

The necessary packages for this code to work are: matplotlib, skimage.io, numpy, pandas, sklearn, tensorflow , keras

The application accepts the following parameters : 
BINARY 1 executes Binary Classification 
             0 executes multiclass categorical classification
SVM =1 and DNN =0 executes using the SVM engine 
SVM =0 and DNN =1 executes using the DNN engine 
CNN =1 adds the Convolutional NN in front of the DNNq

All results are presented at the last 2 cells for the validation (y_pred) and the gioven test datasets (y1_pred)

During the first run, google colab takes a long time to load the files from google drive.
