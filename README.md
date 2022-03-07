# Brain-Tumor-Detection
Convolutional Neural Network (CNN) is the deep learning technique to perform image classification. In this paper, we compared two model CNN find the best model CNN to classify tumours in Brain MRI Image and at the end, I have trained CNN and obtained a prediction accuracy of up to 99.99%.

Magnetic resonance imaging (MRI) is the imaging technique used to diagnosing brain tumor disease. Early diagnosis of brain tumors is an essential task in medical work to find out whether the tumor can potentially become cancerous. Deep learning is a handy and efficient method for image classification. Deep learning has been widely applied in various fields including medical imaging, because its application does not require the reliability of an expert in the related field, but requires the amount of data and diverse data to produce good classification results. 

# The Dataset 

The data set consists of two different folders that are Yes or No. Both the folders contain different MRI images of the patients. Yes folder has patients that have brain tumors whereas No folder has MRI images of patients with no brain tumor. There are a total of 155 images of positive patients of brain tumor and 98 images of other patients having no brain tumor. All the images are of 240X240 pixels. 

# Brain Tumor Classification Model

First, we need to enable the GPU. To do so go to ‘Runtime’ in Google Colab and then click on ‘Change runtime type’ and select GPU. Once the runtime is changed we will move forward importing the required libraries and dataset. We will be directly importing the data set from kaggle. Use the below code to do the same. 
