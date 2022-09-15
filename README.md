COVID-19 Detection and Lung & Infection Mask Segmentation Using U-NET


Coronavirus disease 2019 (COVID-19) is a contagious disease caused by severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). 
The first known case was identified in Wuhan, China, in December 2019. The disease has since spread worldwide, leading to an ongoing pandemic


Description

A CNN model was trained to detect COVID-19 in CT scans of lung. UNET models have been developed to detect the infected region in the CT scans and to perform lung segmenation as well. Contrast Limited Adaptive Histogram Equalisation (CLAHE) has been used to preprocess the images.


Dataset

COVID-19 CT scans which consists of 20 CT scans and expert segmentations of patients with COVID-19 which is nifti format has been used for training.
Link to the dataset : https://www.kaggle.com/andrewmvd/covid19-ct-scans


Output and Results

The COVID-19 detection CNN model has achieved an accuracy of 98.26%. A DICE score of 0.9802 has been achieved using the lung segmentation UNET model and a DICE score of 0.8710 has been attained using the infection region segmentation UNET model

The infection mask predicted compared against the actual mask : 

<img width="887" alt="Screen Shot 2022-01-20 at 7 35 02 PM" src="https://user-images.githubusercontent.com/40431641/150485324-4c17ba0b-1835-4fac-9a22-a52c882a1047.png">
