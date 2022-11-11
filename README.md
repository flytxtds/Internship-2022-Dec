## Data Science Internship Opportunities at Flytxt R&D (December 2022 - January 2023)
We are looking for self-motivated individuals with a passion to solve real-world problems in emerging areas of machine learning/AI including federated privacy preserving machine learning and explainable AI. You will be responsible to design, code, test and deploy PoCs which demonstrate the value in applying these advanced techniques on usecases in customer experience management. You would be working in a fast-paced environment, and would need to pick up concepts through a combination of self-learning and your assigned mentor's guidance. Please note that this will be a remote internship program.

## Who can apply?
1. Students in 3rd/4th year B.Tech program in Computer Science or a related discipline (Applied Mathematics, Statistics, Electrical and/or Computer Engineering) with a focus on Artificial Intelligence / Machine Learning. Final year M.Tech/MS/Ph.D students from the above disciplines are also eligible.
2. Should be passionate about advanced machine learning/AI.
3. Should be able to devote a minimum of 2 months, starting December 2022

## Problem Description
This year, we have two problems from which you can choose **one**


### Problem 1: Explainable AI based on causal reasoning
#### Backdrop:
Churn models predict customers who are likely to leave, but do not generally answer why. This limits actionability and reduces marketer’s trust on the model’s predictions due to lack of explanations.

#### Goal:
Create an explainable churn prediction model which: 
1. Visualizes causal structure in observed data along with strength of each causal factor towards churn. The visualization should convey which factors contribute to customer churn and to what extent, at an overall level. 

2. Predicts if a specific user will churn along with the top-3 contributing factors for that user to churn. A visual explanation for the model’s specific prediction should be provided.

Model for the overall causal structure visualization should be built using CausalNex, an open-source project from McKinsey (https://github.com/quantumblacklabs/causalnex). The learned causal model should be used to predict if a specific user is likely to churn. To identify top-3 contributing factors and to generate the visual explanation for each prediction, SHAP (https://github.com/slundberg/shap) should be used.

#### Success Criteria:
1. Prediction accuracy of the causal model should be comparable to that of a baseline model based on Random Forest.
2. Domain expert's validation of the learned causal structure; subjective evaluation of causes for churn on a random subset of cases

Brownie points for setting up an interactive demo of the model on a public cloud, covering the following functionality:
1. User uploads a churn dataset
2. Gets a causal structure visualization which he/she can edit.
3. KPI values for a particular user are entered to get a prediction along with top-3 contributing factors and a visual explanation for the predicted outcome

#### Dataset:
https://www.kaggle.com/jpacse/datasets-for-churn-telecom (71047 instances, 58 features)

---
### Problem 2: Federated Recommender System
#### Backdrop:
Personalized recommendations help customers to easily discover relevant items/content, thereby increasing their engagement. As user preferences are fragmented across businesses,  federated privacy preserving recommender systems will be mutually beneficial for customers and businesses. For instance, an OTT media streaming service could improve its recommendations by securely combining a user’s content preferences with her profile and mobility patterns that are available with a Telco partner.

#### Goal:
Create a federated recommender system to recommend movies to users by securely combining the user’s movie rating data, movie attributes, and user attributes which are split across two parties, without requiring data sharing in plain. Both parties have overlapping users but different sets of features. Party 1 maintains the user profiles (age, gender, occupation, etc.), while Party 2 maintains movie attributes (name, release date, genre, etc.) and user’s movie rating. Recommender model is trained on overlapping users. Inference should be possible for all users (users with a profile but no rating history as well as users with a rating history but no profile should get recommendations)

The model should be built using PySyft, an open-source project from OpenMined. (https://github.com/OpenMined/PySyft)

#### Success Criteria:
The federated recommender model should give better predictive performance (Precision, Recall, F1, and Normalized Discounted Cumulative Gain) than a model trained only on ratings data and movie attributes.

Brownie points for setting up an interactive demo of the model on a public cloud, covering the following functionality:
1. User uploads datasets to different parties.
2. Secure federated learning of the model
3. Generate recommendations at Party 2 for users without any rating history (cold start)

#### Dataset:
https://grouplens.org/datasets/movielens/100k/ (100,000 ratings from 1000 users on 1700 movies). 

---
## Application Process
1. Interested candidates should choose <ins>**one**</ins> problem from the above list of problems and prepare a <ins>**1 page**</ins> proposal describing their approach and key milestones. Please note that the proposal should clearly state how <ins>**you**</ins> would approach the problem and the <ins>**corresponding work breakdown structure along with a timeline.**</ins> **Proposals exceeding 1 page and/or which are very generic will not be considered.**
2. You can submit your proposal, latest resume and other relevant details using this form till **November 30th 2022**: [Apply Now](https://forms.gle/29EvS4rzDPh1j7nB8)
3. Shortlisted candidates will be notified by **December 1st, 2022**, followed by an online interview.
4. Selected candidates will be notified by **December 4th, 2022**; Internship would start from **12th of December 2022.**

## Perks
1. Work experience in cutting edge areas of machine learning/AI on real-world customer experience management problems
2. Stipend

## Queries
You can submit your queries [here](https://forms.gle/brxCAic84pCj3thR6). We will get in touch with you.
