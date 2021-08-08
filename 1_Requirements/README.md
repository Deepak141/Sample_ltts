# Requirements

## Introduction
Diabetic Retinopathy (DR), also known as diabetic eye disease, is a medical condition in which damage occurs to the retina due to diabetes mellitus.Diabetic Retinopathy (DR) is the leading cause of blindness in the working-age group. 50 million Indians sufering from diabetes, the prevalence of those with DR is estimated between 18percent to 28percent.Regular eye examination among these vulnerable groups is necessary to diagnose DR at an early stage, when it can be treated with the best prognosis.As show in the Figure, According to the GlobalData, it is predicted to have the increase in the DR cases to 17.8 million in 2029 .Diabetic Retinopathy is the most prevalent cause of avoidable vision impairment, mainly affecting the working-age population in the world. Recent research has given a better understanding of the requirement in clinical eye care practice to identify better and cheaper ways of identification, management, diagnosis and treatment of retinal disease. Currently, detecting DR is a time-consuming and manual process that requires a trained clinician to examine and evaluate digital color fundus photographs of the retina. Automated analysis of retinal color images has such benefits as increased efficiency and coverage of screening programs, reduced barriers to access, and early detection and treatment. Here we used the Indian region based dataset to build our model. In this project we use Deep Learning models to detect referable Diabetic Retinopathy.
![Stats](https://github.com/Deepak141/Sample_ltts/blob/main/1_Requirements/Stats%20(1).png)

## Research
* Indian Diabetic Retinopathy Image Dataset (IDRiD): 
   1 In this paper the authors explained about how they created the IDRiD (Indian Diabetic Retinopathy Image Dataset) the first database representative of an Indian population. 
   2 It constitutes typical diabetic retinopathy lesions and normal retinal structures annotated at a pixel level. The dataset provides information on the disease severity of diabetic retinopathy, and diabetic macular edema for each image.
   3 Dataset consist of 516 images which is splitted into train (413 images) and testing(103 images).
   4 [IDRid Paper](https://www.mdpi.com/2306-5729/3/3/25)

 

* Development and Validation of a Deep Learning Algorithm for Detection of Diabetic Retinopathy in Retinal Fundus Photographs :
  1  In this paper the audthors focused on applying deep learning to create an algorithm for automated detection of diabetic retinopathy and diabetic macular edema in retinal fundus photographs on eye PACs dataset.
  2  The EYEPACS dataset contains 9963 images and the Messidor-2 dataset contains 1748 images. They have achieved the sensitivity of 97 for EYEPACS-1 , 96.1 for Messidor-2 and they achieved the specificity of 93.4 for EYEPACS-1 , 93.9 for Messidor-2 datasets.
  3  [Development and Validation of a Deep Learning Algorithm ](https://doi.org/10.1001/jama.2016.17216)

* CANet: Cross-disease Attention Network for Joint Diabetic Retinopathy and Diabetic Macular Edema Grading \citep{8892667}
  1 Where they have used the IDRid dataset which consists of 413 training samples and 103 testing data ,In the IDRiD dataset, each image contains both DR and DME severity grading labels. DR grade is annotated into five classes according to the severity scale, and we perform 5 class classification for DR. 
  2 Diabetic Macular Edema(DME) is annotated based on the shortest distance d between the hard exudates location and the macula. The annotation criteria of DME grading is the same as that in the IDRiD dataset, and they have made use of the CANet and have achieved the joint accuracy of 65.1.only one or two have worked on the same topic in which they have worked on same dataset and have achieved the Accuracy of 65 which is the current highest who has achieved on this dataset for classifying both Diabetic Macular Edema and Diabetic Retinopathy Grade(DRG).
  3 [DOI](10.1109/TMI.2019.2951844)

## Cost and Features
### *Cost vs Features*
For Diabetic Retinopathy screening, drops placed in your eyes widen (dilate) your pupils to allow your doctor a better view inside your eyes. The drops can cause your close vision to blur until they wear off, several hours later.During the exam, your eye doctor will look for abnormalities in the inside and outside parts of your eyes. 
Using our method Computer-aided disease diagnosis in retinal image analysis could ease mass screening of the population with diabetes mellitus and help clinicians in utilizing their time more efficiently. 
*TBD*

### *Features vs Ageing*
The pervious methods Used for Detecting Diabetic Retinopathy have achieved the Maximum Accuracy of 65.1% where as using our model we have achieved the accuracy of 69%.

## Defining the System
Our propsed method is to analysis could ease mass screening of the population with diabetes mellitus and help clinicians in utilizing their time more efficiently.

# 4W's and 1'H

## Who

This tool is a helping hand for Ophthalmologist in reducing their time for mass screening of the populations with DR.

## What

Gives the Macular Edema(ME) and Retinopathy Grade(RG) value for an given Eye Image

## When

Since there is no software that is currently used to detect this Disease we can use there for automatic detection

## Where

Can be used in the hosplitals and labs for screening the Diabetic Retinopathy.

## How

Pass the eye image to the testing model which gives the result of both ME and RG


# SWOT Analysis

![swot](https://github.com/Deepak141/Sample_ltts/blob/main/1_Requirements/Screenshot%20(375).png)

# Detail requirements
## High Level Requirements

|      ID          |Description                          |Status                         |
|----------------|-------------------------------|-----------------------------|
|ID_01|Classify Mcular Edema |Implemented|
|ID_02|Classify Retinopathy Grade |Implemented|



##  Low level Requirements
|      ID          |Description                          |  HLR_ID  |Status               |
|----------------|-------------------------------|----------|-----------------------------|
|SID_01|Classify lvl0|ID_01|Implemented|
|SID_02|Classify lvl1|ID_01|Implemented|
|SID_03|Classify lvl2|ID_01|Implemented|
|SID_04|Classify lvl0|ID_02|Implemented|
|SID_05|Classify lvl1|ID_02|Implemented|
|SID_06|Classify lvl2|ID_02|Implemented|
|SID_07|Classify lvl3|ID_02|Implemented|
|SID_08|Classify lvl4|ID_02|Implemented|

