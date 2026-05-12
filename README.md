# Instagram-Reel-Virality-Prediction-Using-CHAID-Decision-Tree-in-IBM-SPSS-Modeler
Instagram Reel Virality Prediction using the CHAID algorithm in IBM SPSS Modeler. The project analyzes likes, comments, shares, saves, watch time, hashtags, and followers to predict whether a reel will become viral or non-viral. Includes preprocessing, prediction, and accuracy analysis.
# Instagram Reel Virality Prediction Using CHAID Decision Tree in IBM SPSS Modeler

## Overview

This project predicts Instagram reel virality using the CHAID (Chi-squared Automatic Interaction Detection) decision tree algorithm in IBM SPSS Modeler. The system analyzes engagement metrics such as likes, comments, shares, saves, watch time, hashtags, and creator followers to predict whether a reel is likely to become viral or non-viral.

---

## Problem Statement

Instagram reels generate large amounts of engagement data every day. Predicting reel virality can help content creators and marketers understand audience behavior and improve content strategies. This project uses machine learning techniques to analyze reel performance and classify reels as Viral or Non-Viral.

---

## Objective

The main objectives of this project are:

- Predict whether an Instagram reel will become viral.
- Analyze engagement factors affecting reel performance.
- Build a CHAID classification model using IBM SPSS Modeler.
- Generate predictions using user input data.
- Evaluate model accuracy and performance.

---

## Dataset

### Source
Custom dataset created for machine learning analysis.

### Dataset Size
- 650 Records
- 12 Fields

### Key Attributes

- Duration_sec
- Likes
- Comments
- Shares
- Saves
- Hashtag_Count
- Posting_Hour
- Audio_Trend
- Watch_Time_Percent
- Creator_Followers
- Viral (Target Variable)

---

## Tools and Technologies

- IBM SPSS Modeler 18.6
- CHAID Decision Tree Algorithm
- CSV Dataset
- Machine Learning Classification
- Data Audit and Visualization

---

## Methodology

1. Imported dataset into IBM SPSS Modeler.
2. Configured field roles using Type Node.
3. Performed preprocessing using Filler Node.
4. Conducted data analysis using Data Audit Node.
5. Split dataset into training and testing data using Partition Node.
6. Built CHAID decision tree classification model.
7. Generated predictions using User Input Node.
8. Evaluated model accuracy using Analysis Node.
9. Visualized results and workflow.

---

## Workflow

The machine learning workflow includes:

- Data Import
- Type Configuration
- Data Preprocessing
- Data Audit
- Partitioning
- CHAID Model Training
- Prediction System
- Accuracy Analysis

---

## Results

- CHAID model successfully predicted reel virality.
- Model Accuracy Achieved: **92.31%**
- User input prediction system was implemented successfully.
- Important engagement metrics influencing virality were identified.

---

## IBM SPSS Modeler Workflow Preview

<img width="938" height="488" alt="image" src="https://github.com/user-attachments/assets/8f1a3291-7e62-417c-8699-7eb6eb72f7c3" />


---

## Prediction Output

![Prediction](asset/prediction_output.png)

---

## Analysis Output

![Analysis](asset/analysis.png)

---

## CHAID Tree

![CHAID Tree](asset/chaid_tree.png)

---

## Conclusion

This project successfully demonstrated an end-to-end machine learning workflow using IBM SPSS Modeler. The CHAID algorithm effectively analyzed Instagram engagement data and predicted reel virality with high accuracy. The project also included a user input prediction system for real-time testing.

---

## Future Work

- Compare CHAID with Random Forest and Neural Networks.
- Add real-time Instagram API integration.
- Improve prediction accuracy using larger datasets.
- Create dashboard visualization for reel analytics.

---

## Project Structure

```text
instagram-reel-virality-prediction-chaid/
│
├── asset/
│   ├── workflow.png
│   ├── analysis.png
│   ├── prediction_output.png
│   ├── chaid_tree.png
│
├── instagram_reel_prediction_dataset_650.csv
├── instagram_reel_prediction.str
├── README.md
├── project_report.pdf
