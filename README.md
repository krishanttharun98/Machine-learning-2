# Machine-learning-2
# Brain-Tumor-Detection Using CNN (Convolutional Neural Network) Machine learning implemented in a Robot

With help of a brain MRI images data set founded on Kaggle which can be found [here](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection).

The data set consists of 155 tumorous brain scans and 98 non-tumorous brain scans.

# data Augumentation:
This data augumentation is useful for tackling the data non linearity or imbalance issues in the data. 
After augumentation there are 1085 positive and 980 negative for tumour, totally 2065 image samples.

# Working
First datas are preprocessed such as cropping, resizing the image, and normaliation of the images. Then the data are splittedinto three catagories.
  1.Training   - 70%
  2.Validation - 15%
  3.Testing    - 15%
  
# Classifier used:
CNN - Convolutional Neural Network (CNN) is the deep learning technique to perform image classification. In this paper, we compared two model CNN find the best model CNN to classify tumours in Brain MRI Image. 

# Result:
With an Validation accuracy of 91% and text accuracy of 89%, we have made a possible aprroach on how to implement this on a pepper robot, which would be very useful in the medical for the doctors and technicians. 

# Project done By
Nirmal Kumar - S5168055
Krishant Tharun - S5168143
Shahrzad Eskandari Majdar - S5060737
