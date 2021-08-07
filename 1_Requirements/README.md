# Requirements

## Introduction
Diabetic Retinopathy (DR), also known as diabetic eye disease, is a medical condition in which damage occurs to the retina due to diabetes mellitus.Diabetic Retinopathy (DR) is the leading cause of blindness in the working-age group. 50 million Indians sufering from diabetes, the prevalence of those with DR is estimated between 18percent to 28percent.Regular eye examination among these vulnerable groups is necessary to diagnose DR at an early stage, when it can be treated with the best prognosis.As show in the Figure, According to the GlobalData, it is predicted to have the increase in the DR cases to 17.8 million in 2029 .Diabetic Retinopathy is the most prevalent cause of avoidable vision impairment, mainly affecting the working-age population in the world. Recent research has given a better understanding of the requirement in clinical eye care practice to identify better and cheaper ways of identification, management, diagnosis and treatment of retinal disease. Currently, detecting DR is a time-consuming and manual process that requires a trained clinician to examine and evaluate digital color fundus photographs of the retina. Automated analysis of retinal color images has such benefits as increased efficiency and coverage of screening programs, reduced barriers to access, and early detection and treatment. In this project we use Deep Learning models to detect referable Diabetic Retinopathy.

## Research
* Indian Diabetic Retinopathy Image Dataset (IDRiD): A Database for Diabetic Retinopathy Screening Research by Prasanna Porwal  , Samiksha Pachade 1, Ravi Kamble 1, Manesh Kokare 1, Girish Deshmukh , Vivek Sahasrabuddhe  and Fabrice Meriaudeau in this paper the authors explained about ho they created the IDRiD (Indian Diabetic Retinopathy Image Dataset) the first database representative of an Indian population. It constitutes typical diabetic retinopathy lesions and normal retinal structures annotated at a pixel level. The dataset provides information on the disease severity of diabetic retinopathy, and diabetic macular edema for each image.

 

* Development and Validation of a Deep Learning Algorithm for Detection of Diabetic Retinopathy in Retinal Fundus Photographs by Varun Gulshan, PhD; Lily Peng,MD, PhD; Marc Coram, PhD; Martin C. Stumpe, PhD; DerekWu, BS; Arunachalam Narayanaswamy, PhD; Subhashini Venugopalan, MS; Kasumi Widner, MS; TomMadams, MEng; Jorge Cuadros, OD, PhD; Ramasamy Kim, OD, DNB; Rajiv Raman, MS, DNB; Philip C. Nelson, BS; Jessica L. Mega, MD, MPH; Dale R.Webster, PhD In this paper the audthors focused on applying deep learning to create an algorithm for automated detection of diabetic retinopathy and diabetic macular edema in retinal fundus photographs on eye PACs dataset.


* Diabetic Retinopathy detection through integration of Deep Learning classification framework Alexander Rakhlin in this paper they created the deeplearning  CNN model for Kaggle data and messidor-2 data set

* CANet: Cross-disease Attention Network for Joint Diabetic Retinopathy and Diabetic Macular Edema Grading \citep{8892667}where they have used the IDRid dataset which consists of 413 training samples and 103 testing data ,In the IDRiD dataset, each image contains both DR and DME severity grading labels. DR grade is annotated into five classes according to the severity scale, and we perform 5 class classification for DR. DME is annotated based on the shortest distance d between the hard exudates location and the macula. The annotation criteria of DME grading is the same as that in the IDRiD dataset, and they have made use of the CANet and have achieved the joint accuracy of 65.1.only one or two have worked on the same topic in which they have worked on same dataset and have achieved the Accuracy of 65 which is the current highest who has achieved on this dataset for classifying both Diabetic Macular Edema and Diabetic Retinopathy Grade.

## Cost and Features
### *Cost*
Since the system uses only open source software, it is free of cost..!!

*TBD*

### *Features*
Since we are using Deeplearning we dont explicity give any features for the model . we just pass the image(.png)

## Defining the System
![Flow chart](https://github.com/Deepak141/Sample_ltts/blob/main/1_Requirements/Final%20(1).png)

# 4W&#39;s and 1&#39;H

## Who:

The tool is a helping hand for Doctors who are working in this field.

## What:

Giives the ME and RG value for an given Eye Image

## When:

Since there is no software that is currently used to detect this Disease we can use there for automatic detection

## Where:

Can be used in the hosplitals and labs of the concern field.

## How:

Pass the eye image to the testing model which gives the result of both ME and RG

# Detail requirements
## High Level Requirements:

|      ID          |Description                          |Status                         |
|----------------|-------------------------------|-----------------------------|
|ID_01|Classify DR |Implemented|



##  Low level Requirements:
|      ID          |Description                          |  HLR_ID  |Status               |
|----------------|-------------------------------|----------|-----------------------------|
|SID_01|Classify ME|ID_01|Implemented|
|SID_02|Classify RG|ID_01|Implemented|

