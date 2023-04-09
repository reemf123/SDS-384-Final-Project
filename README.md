# SDS 384 Team 8: Reem Fashho, Amanda Nowacki, Shreya Shukla 

## Abstract
The goal of our project is to conduct a Supervised Chest Cancer Classification Experiment to detect the presence of cancer in human chests from Normal, Adenocarcinoma, Large Cell Carcinoma, and Squamous Cell Carcinoma images. We will train and test at least 4 different models on the images and then assess the models' performance via various visualization methods and statistical analyses. 

## Data Set 

#### 1. Chest CT-Scan Images Dataset (Original Source Unavailable) 
###### Source: https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images
###### Size: 1000 Images Split Into: 70% Train, 20% Test, 10% Validation
###### Variables: Label (Cancer/NonCancer), Image Dimensions, Width, Channel (Unimportant)
###### Limitations: Data comes in various file types (12 .jpg, 988 .png), Small Sample Size - there are roughly 600 training images that is comprised of 4 subsets, thus the strength of the algorithm is limited unless data augmentation is performed. 
###### Contains train, test, and validation directory each containing a subdirectory of different chest cancer types (carcinoma, squamous cell carcinoma) and 1 subdirectory of normal CT-Scan images


## References 
#### https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4419420/
#### https://dl.acm.org/doi/fullHtml/10.1145/3483207.3483215
#### https://ieeexplore.ieee.org/document/9783556
