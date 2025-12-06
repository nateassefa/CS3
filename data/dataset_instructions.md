# RealWaster Dataset Instructions 

## Overview 
This case study uses the **RealWaster** datset from the UC Irvine Machine Learning Repository. The dataset contains 4,752 JPEG images of common waste items orgnaized into subfolders by waste type. You will regroup these categories into three broader classes for the classification task. 

Because of GitHub's file-size limitations, the dataset is *not included* directly in this repository. Follow the steps below to download and prepare it. 

## 1. Download the Dataset

You can access the dataset at the link below: 
https://archive.ics.uci.edu/dataset/908/realwaste

Click **Download** to btain the zipped dataset. 

The file is typically around 250-300 MB zipped* and **450-600MB** unzipped**. 

--

## 2. Extract The Files 

After downloading: 
1. Unzip the folder
2. You should see multiple subdirectories, each representing one of the original nine waste categories.

Typical folder names include: 
Cardboard, Food Organics, Glass, Metal, Miscellaneous Trash, Paper, Plastic, Textile Trash, and Vegetation

Your system may show slightly different names depending on the version. 

## 3 Place the Dataset in the Correct Location

Inside your cloned repo, create the following folder structure: 

your-repo/
data/
RealWaster/
[subfolder of images here]

Ensure that all of the category folders remain inside 'RealWaster/'

## 4. About the Dataset License 

RealWaster is released under: 
** Creative Commons Attribution 4.0 (CC BY 4.0)**

This means you may use and modify the dataset for academic purpose** as your provide appropriate attribution.**

---
## 5. Additional Notes for this Case Study 
- You will regroup the 9 original categories into **3 classes**
  - **Recyclable**
  - **Compostable**
  - **Trash**
- This regrouping is implemented in the starter code
- You must not upload the dataset itself to the Github repo.
