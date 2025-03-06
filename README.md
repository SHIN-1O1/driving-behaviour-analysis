# driving-behaviour-analysis
📌 Objective:
This project aims to analyze driving patterns using machine learning by detecting behaviors such as harsh acceleration, sudden braking, half clutch usage, and transmission-threatening riding styles.

📊 Key Steps:
Data Collection & Preprocessing

Loaded the dataset (driving_behavior test case.csv)
Handled missing values
Encoded categorical variables (Event Labels)
Scaled numerical features for better model performance
Feature Engineering

Considered factors like speed, acceleration, brake pressure, throttle position, RPM, clutch engagement, steering angle, lateral acceleration, and yaw rate
Machine Learning Model

Random Forest Classifier trained to classify driving events
Train-test split: 80% training, 20% testing
Feature Scaling improved model performance
Evaluation & Performance Metrics

Accuracy Score: Measures overall correctness
Classification Report: Precision, recall, F1-score for event classification
Confusion Matrix: Visual representation of model predictions
🔎 Insights & Applications:
✅ Can be used to detect dangerous driving patterns 🚨
✅ Helps in driver behavior monitoring for insurance companies
✅ Useful for fleet management & traffic safety analysis
✅ Can be integrated into IoT-based vehicle tracking systems

🔹 Next Steps:

Try advanced models like XGBoost, LSTMs for sequential pattern detection
Use real-time data from vehicle sensors for real-world applications
🚀 This project is a strong foundation for intelligent driver monitoring systems!
