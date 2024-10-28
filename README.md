# Amazon Movie Review Rating Prediction
This project aims to predict Amazon movie review star ratings using metadata and user-centered features. The final model uses a K-Nearest Neighbors (KNN) classifier to capture user rating patterns. This repository includes the code, data processing steps, and model evaluation metrics for the prediction task.

## Project Overview
Objective: Predict star ratings for Amazon movie reviews based on user behavior.
Model: K-Nearest Neighbors (KNN) classifier with n_neighbors=3.
Features:
User_Avg_Score: Average star rating given by each user.
User_Negative_Count: Number of 1-star ratings given by each user.
Multiple_Negative_Reviews: Binary feature indicating if a user has given more than one 1-star review.

## Key Files
506_Midterm_Report.pdf: Final report detailing the methodology, features, and model performance.
README.md: Project overview and setup instructions.
Setup and Usage
Clone the repository:

bash
Copy code
git clone https://github.com/username/repo-name.git
cd repo-name

## Results and Limitations
Local Accuracy: The model achieved 81.5% accuracy on the local test set.
Competition Accuracy: The accuracy dropped to around 20% in the Kaggle competition, likely due to overreliance on average score and possible data drift.
For more details, refer to the full report in 506_Midterm_Report.pdf.
