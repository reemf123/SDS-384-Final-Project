# SDS 384 Team 8: Reem Fashho, Amanda Nowacki, Shreya Shukla 

## Abstract
The goal of our project is to conduct a Supervised Chest Cancer Classification Experiment to detect the presence of cancer in human chests from Normal, Adenocarcinoma, Large Cell Carcinoma, and Squamous Cell Carcinoma images. We will train and test at least 4 different models on the images and then assess the models' performance via various visualization methods and statistical analyses. 

## Data Set 

#### 1. Chest CT-Scan Images Dataset (Original Source Unavailable) 
##### Source: https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images
##### Size: 1000 Images Split Into: 70% Train, 20% Test, 10% Validation
##### Variables: Label (Cancer/NonCancer), Image Dimensions, Width, Channel (Unimportant)
##### Limitations: Data comes in various file types (12 .jpg, 988 .png), Small Sample Size - there are roughly 613 training images which comprised of 4 subsets, thus the strength of the algorithm is limited unless data augmentation is performed. 
##### Contains train, test, and validation directory each containing a subdirectory of different chest cancer types (carcinoma, squamous cell carcinoma) and 1 subdirectory of normal CT-Scan images


## References 

#### [1] Causes of death - Our World in Data. (n.d.). Retrieved April 21, 2023, from https://ourworldindata.org/causes-of-death

#### [2] Lung cancer statistics | World Cancer Research Fund International. (n.d.). Retrieved April 21, 2023, from https://www.wcrf.org/cancer-trends/lung-cancer-statistics/

#### [3] Mackintosh, J. A., Marshall, H. M., Yang, I. A., Bowman, R. v., & Fong, K. M. (2014). A retrospective study of volume doubling time in surgically resected non-small cell lung cancer. Respirology, 19(5), 755–762. https://doi.org/10.1111/resp.12311

#### [4] del Ciello, A., Franchi, P., Contegiacomo, A., Cicchetti, G., Bonomo, L., & Larici, A. R. (2017). Missed lung cancer: When, where, and why? In Diagnostic and Interventional Radiology (Vol. 23, Issue 2, pp. 118–126). AVES Ibrahim Kara. https://doi.org/10.5152/dir.2016.16187

#### [5] Doi, K. (2007). Computer-aided diagnosis in medical imaging: Historical review, current status and future potential. Computerized Medical Imaging and Graphics, 31(4–5), 198–211. https://doi.org/10.1016/j.compmedimag.2007.02.002

#### [6] Chest CT-Scan images Dataset | Kaggle. (n.d.). Retrieved April 21, 2023, from https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images

#### [7] Image Classification Techniques. Image classification refers to a… | by Kavish Sanghvi | Analytics Vidhya | Medium. (n.d.). Retrieved April 21, 2023, from https://medium.com/analytics-vidhya/image-classification-techniques-83fd87011cac

#### [8] Chest Cancer Classification With VVG 16 | Kaggle. (n.d.). Retrieved April 21, 2023, from https://www.kaggle.com/code/yasserhessein/chest-cancer-classification-with-vvg-16

#### [9] Ramanjaneyulu, K., Kumar, K. H., Snehith, K., Jyothirmai, G., & Venkata Krishna, K. (2022). Detection and Classification of Lung Cancer Using VGG-16. Proceedings of the 2022 International Conference on Electronic Systems and Intelligent Computing, ICESIC 2022, 69–72. https://doi.org/10.1109/ICESIC53714.2022.9783556

#### [10] Song, Q. Z., Zhao, L., Luo, X. K., & Dou, X. C. (2017). Using Deep Learning for Classification of Lung Nodules on Computed Tomography Images. Journal of Healthcare Engineering, 2017. https://doi.org/10.1155/2017/8314740

#### [11] How Much Data Is Required for Machine Learning? – PostIndustria. (n.d.). Retrieved April 21, 2023, from https://postindustria.com/how-much-data-is-required-for-machine-learning/

#### [12] Data - Grand Challenge. (n.d.). Retrieved April 21, 2023, from https://luna16.grand-challenge.org/Data/

#### [13] Data From LIDC-IDRI. (n.d.). https://doi.org/10.7937/K9/TCIA.2015.LO9QL9SX

#### [14] Lin, C.-J., Jeng, S.-Y., & Chen, M.-K. (2020). Using 2D CNN with Taguchi Parametric Optimization for Lung Cancer Recognition from CT Images. Applied Sciences, 10(7), 2591. https://doi.org/10.3390/app10072591

#### [15] COPD - Symptoms and causes - Mayo Clinic. (n.d.). Retrieved April 21, 2023, from https://www.mayoclinic.org/diseases-conditions/copd/symptoms-causes/syc-20353679

#### [16] Purandare, N. C., & Rangarajan, V. (2015). Imaging of lung cancer: Implications on staging and management. Indian Journal of Radiology and Imaging, 25(2), 109–120. https://doi.org/10.4103/0971-3026.155831

#### [17] Lu, Y., Liang, H., Shi, S., & Fu, X. (2021). Lung Cancer Detection using a Dilated CNN with VGG16. ACM International Conference Proceeding Series, 45–51. https://doi.org/10.1145/3483207.3483215
