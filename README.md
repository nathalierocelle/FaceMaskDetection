# FaceMaskDetection

### Introduction
As of this year 2021, we are facing a surge of covid cases due to the new variant, the Delta or B.1.617.2. According to Center of Disease Control and Prevention or CDC, the Delta variant is more infectious and contagious that leads to increase transmissibility as compared with other variants. Patients infected with this variant are high risk to be hospitalized than patients infected with the other strains of COVID-19.

### Problem and Objectives
In order to prevent and lessen the transmission of delta variant, we are required by the World Health Organization (WHO) and Department of Health (DOH) to wear mask and maintain a 6 feet distancing.

As delta variant spread rapidly, we need to limit the number of people on a certain area. Instead of assigning multiple personnel, the best solution is to apply automated technology that can detect if a person is wearing a face mask.

Due to this problem, the main objective of this project is to develop an object detection model that can able to predict whether a person is wearing a face mask or not and if the mask is not worn properly. In this way we can able to lessen the spread of the virus by immediate identification of the people not wearing their masks and by limiting the number of people present in an area.

Other objectives are:

1. To apply deep learning concepts in creating the object detection model
2. To build and train the model
3. To evaluate the performance of the model
4. To test the model by using unseen images and video

### Dataset
The dataset used in this project composed of 853 images of people wearing and not wearing a facemask. The data are retrieved at Kaggle and uploaded at Roboflow to apply respective annotations of each images.

The following are the classes present in the dataset: 'with_mask', 'without_mask', and 'mask_weared_incorrect'

**Kaggle Data link:** https://www.kaggle.com/datasets/andrewmvd/face-mask-detection?select=images
