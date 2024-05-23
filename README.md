# Learning To Rank Humans' Emotional States

## Files Access 

This repository contains the code and results corresponding to my Final Year Project to make use of different Machine Learning algorithms to Learn to Rank Humans' Emotional States. Due to GitHub's file size limitations, some folders are hosted externally.

You can access the complete repository, including all code and results that are included in this GitHub repository, through this [Google Drive link](https://drive.google.com/drive/folders/1S0E4BdghJJOV_DX-pt_TmptJNzv7pvZR?usp=sharing).

The link provides access to all resources and the following folders that are not included here:
- The `Random Forest` folder within the `RECOLA Ranking Algorithms` directory.
- The `Random Forest Results` folder within the `AGAIN Ranking Algorithms` directory.

---

## Overview

Human emotions are pivotal in shaping cognitive processes and social interactions, influencing individual behavior and group dynamics. In affective computing, accurately modelling these emotions is essential for humanised computer interactions. Traditional methods, which categorise emotions into discrete states or quantify them along a continuous scale, often oversimplify the complex spectrum of human emotions. This oversimplification introduces subjective biases, resulting in inaccuracies and misinterpretations that undermine the robustness of emotion recognition technologies.

### Objectives

This study aims to develop more reliable affective computing systems by addressing these challenges. We model human emotions as ordinal variables using various machine learning algorithms, moving away from traditional categorical or continuous interpretations.

### Methods

We employed five machine learning algorithms for ranking:
- **Random Forest Preference Learner**
- **Ordinal Logistic Regression**
- **Ordinal Neural Network**
- **RankNet**
- **LambdaMART**

Additionally, three regression algorithms were implemented for comparison:
- **Linear Regression**
- **Random Forest Regression**
- **Multi-Layer Perceptron Regression**

### Evaluation

The performance of our models was assessed using robust statistical metrics:
- **Pearson Correlation Coefficient**
- **Kendall's Tau**

### Results

Our ranking models demonstrated a substantial reduction in subjectivity bias and aligned better with the ordinal nature of emotions. They also outperformed baseline models in predictive accuracy, suggesting a significant advancement in affective computing.

### Conclusion

This study marks a crucial development in enhancing affective computing systems, advocating for the use of ordinal models to improve AI applications' ability to understand human emotions accurately and without bias.
