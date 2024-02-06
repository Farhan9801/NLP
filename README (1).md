
# Project Title

In this project, our objective is to create a supervised learning algorithm aimed at identifying duplicate questions on Quora, a widely-used platform for seeking and providing answers. Given the common occurrence of similar or nearly identical questions on the platform, our goal is to enhance the user experience by swiftly providing answers to questions that have already been addressed. This algorithm will contribute to streamlining the search process and mitigating the challenge of finding the most relevant answers amid duplicated inquiries.

## About Dataset

There are over 400,000 lines of potential question duplicate pairs. Each line contains IDs for each question in the pair, the full text for each question, and a binary value that indicates whether the line truly contains a duplicate pair.
## Model Trained

### Random Forest -
Accuracy - 79.5 %

confusion matrix - 
[3291,  521]
[ 779, 1409]

### XGBoost -

Accuracy - 78.9 %

confusion matrix - [3240,  572]
       [ 654, 1534]

       