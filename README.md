# Classification of Diabetic Retinopathy

Let us first know what is Classification before we talk about how we classify the images and so on. To keep it simple Classification is basically grouping the objects by using the known Label information. So, we need to send Label information along with the data for the model to Classify. In this paper we classify Diabetic Retinopathy images with the help of Deeplearning models which takes images and label as input. We provide Diabetic Retinopathi image with label as input for the
model and train it to Classify the Diabetic Retinopathy images. Diabetic Retinopathy (DR), also known as diabetic eye disease, is a medical con-dition in which damage occurs to the retina due to diabetes mellitus.Diabetic Retinopathy (DR) is the leading cause of blindness in the working-age group. 50million Indians sufering from diabetes, the prevalence of those with DR is es-timated between 18percent to 28percent.The classification of the Diabetic Retinopathy at the early stages is very important in order to stop the spreading of the disease.This proposed work, aims to detect the Diabetic Retinopathy at early stages accurately and quickly by using different CNN architectures . The Dataset that is used in this work is from IDRid dataset which consists of 413 training samples and 103 testing samples , the images is of 2848 X 4288 pixel.We can see there is a class imbalance in the dataset so appropriate measure have taken to overcome it. We have used CNN , ResNet-50 , DenseNet-121,Inception v3 for Classification of Diabetic Retinopathy . All the models were trained Individually and took the best model out of these for the final classification of the Diabetic Retinopathy. In this project we achieved an highest accuracy of 68.91 from DenseNet-121.

![Diabetic Retinopathy](https://github.com/Deepak141/Sample_ltts/blob/main/picture%20(1).jpg)
## Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`1_Requirements`   | Documents detailing requirements and research
`2_Design`         | Documents specifying design details
`3_Implementation` | All code and documentation
`4_Test_plan`      | Documents with test plans and procedures

## Contributors List and Summary

SF No. |  Name   |    Features    | Issuess Raised |Issues Resolved|No Test Cases|Test Case Pass
-------|---------|----------------|----------------|---------------|-------------|--------------
## Challenges Faced and How Was It Overcome
1. Class Imbalance
2. less number of samples

we overcome by using the image augmentation.

## Project Enhancements carried out
Variable | Bug | Fix
--- | --- | ----
input_for Macular Edema | miss classification | model hyper tuning
input_for Diabetic Retinopathy Grade  | miss classification | model hyper tuning

Integrating both these models into one model for testing

## Here are some related projects
* [IDRid](https://www.mdpi.com/2306-5729/3/3/25)
* [CANet: Cross-Disease Attention Network for Joint Diabetic Retinopathy and Diabetic Macular Edema Grading](https://github.com/xmengli999/CANet.)
