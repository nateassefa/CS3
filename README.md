# Sorting the Future: Waste Classification with Convlutional Neural Networks
* A DS 4002 Case Study for 2nd Year UVA Students *

---

## Overview 
This case study places you in the role of a data scientist working with a sustainability task force at UVA. Your mission is to build a simplified image-classification pipeline that distinguishes between Recyclable, Compostable, and Trash waste using a real dataset from the UC Irvine Machine Learning Repository. 

You will explore the dataset, reorganize its labels, train a small convolutional neural network (CNN), evaluate its performance, and reflect on uncertainty and bias. 

This repository contains all materials required to complete the case study: the hook document, rubric, supplemental resources, and starter code. 

---
## Repository Structure 
```text
repo/
| README.md
| hook.pdf
| rubric.pdf
|
|--- data/
|    |--- dataset_instructions.md
|--- scripts/
|    |--- wastetypemodel.py
|   
|
|___ supplemental/
    |--- blog_explainer.pdf
    |--- technical_article.pdf

```
Dataset: RealWaster
The dataset used in this case study is RealWaster, hosting by UC Irvine Machine learning Repository. 
- About 4700 images
- JPEG format
- Originally organized into 9 waste categories

How to Access the Dataset
Instructions are provided in data/dataset_instructions.md

Because of the file size limits, the dataset may need to be downloaded externally rather than stored directly in this repository. 

# Learning Objectives 
By completing this case study, you will: 
- Understand how to restructure real-world labels into meaningful groups (9 classes to 3 classes)
- Build and train a basic CNN for image classification
- Evaluate model performance using accuracy, precision, recall, F1 score, and a confusion matrix
- Identify sources of uncertainity and bias in classification problems
- Communicate your results clearly in a short, structured report

# Getting Started
1. Clone this repository
2. Install required Python Packages
 - Tensorflow or torch
 - numpy
 - matplotlib
 - scikit-learn
 - pandas

# Running the Starter Code 
1. Download the RealWaster dataset by following the instructions in 'data/dataset_instructions.md
2. Make sure the dataset is placed in the following folder structure:
data/
RealWaster/
carton/
glass/
metal/
paper/
plastic/
trash/
vegetation/
3. Open the 'scripts/wastetypemodel.py notebook in Jupyter Lab, VS Code, or Google Colab.
4. Run the cells. This notebook will load and preprocess images, regroup the original nine classes into three, train a simple CNN model, print accuracy, recall, precision, and F1 score, and generate a 3x3 confusion matrix 

The evaluation should include overall accuracy, per-class precision/recall/F1, and a 3x3 confusion matrix for the three waste categories. 

# Expected Student Deliverable 
Your final deliverable for this case study consists of: 
1. A reproducible notebook or script that:
- Implements the 3-class grouping of the RealWaster dataset
- Trains a basic CNN classifier
- Outputs evaluation metrics and a confusion matrix

2. A written summary (max 2 pages) that:
- Describes your data regrouping strategy
- Explains your model architecture at a high level
- Reports and interprets accuracy, precision, recall, F1 score, and the confusion matrix
- Reflects on uncertainity, misclassifications, and any limitations of your approach

  See rubric.pdf for full grading criteria.

# Supplemental Materials
The supplemental/ folder includes:
- blog_explainer.pdf -> a high level, student-friendly explainer on waste classification and CNNs
- technical_article.pdf -> a more technical resource on a key concept used in the case study (for example, CNNs or class imbalance)
- Any optional resources that may help you better understand the problem or methods.

These documents are also included the printed hard-copy submission.

# Author
Case study created by by:
Nate Assefa
University of Virginia - DS 4002 
