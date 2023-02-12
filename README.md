# SDS 384 Team 8:  - Reem Fashho, Amanda Nowacki, Shreya Shukla 

## Abstract
The goal of our project is to conduct a Supervised Lung Nodule Exploratory Analysis. 
The first aim of our problem setup is to execute a binary classification of the presence or absence of nodules in Lung CT Scans. We will train and test at least 4 different classification algorithms on CT scans provided to us by the LUNA 16 DataSet. We will assess the performance of each classification method via various visualization methods and statistical scores. Then, our hope is to test the strongest binary classification algorithm on Lung CT scans containing tumors rather than nodules. Via our teammate's research laboratory, we have over 30 Lung CT scans, some of which contain tumors. The source of this data set is The Dynamic Medical Image and Computing (DMIC) Lab repository. We would like to determine whether the algorithm we develop to classify the presence of Lung Nodules can be extended to Lung Tumors. The second aim of our project is to perform supervised image segmentation on the nodules.  

## Data Sets: 
#### 1. LUNA 16 from LIDC/IDRI Database
###### Source: https://luna16.grand-challenge.org/Download/
###### Size: 888 CT Scans (Contains 1,186 nodules annotated collected by 4 experienced radiologists)
###### Annotation Process of CT Scans: https://pubmed.ncbi.nlm.nih.gov/21452728/
###### Variables: Candidate ID, x/y/z position of nodule, class label (0 for non-nodule/1 for nodule)
###### Limitations:Data comes in various file types, Differing Voxel lengths

#### 2. Research CT Scans from Team Member’s Laboratory Research 

###### Source: The Dynamic Medical Image and Computing (DMIC) Lab repository
###### Size: 30 CT Scans (8 Annotated Scans)
###### Variables: Class Label (0 for no tumor/1 for tumor), radiation treatment
###### Limitations: Small Data Set, Inconsistent Imaging Artifact in Scans, Differing Voxel lengths, Few Annotations Collected by Non-experts (biomedical engineering undergraduate students)

### References: 
###### https://www.nature.com/articles/s41467-022-30841-3
###### https://rumc-gcorg-p-public.s3.amazonaws.com/f/challenge/71/8ac994bc-9951-420d-a7e5-21050c5b4132/20180102_081812_PAtech_NDET.pdf
###### https://www.mdpi.com/2072-6694/14/21/5457
