# 🏙️ Robust Crowd Density Estimation Using Wi-Fi RSSI and Machine Learning

## 📌 Project Overview
This project focuses on developing a **scalable, privacy-preserving**, and **cost-effective** method for **crowd density estimation** using **Wi-Fi Received Signal Strength Indicator (RSSI) values**. By leveraging machine learning, this approach eliminates the need for **cameras or additional sensors**, making it a practical solution for **smart cities, retail spaces, and public safety applications**.

##  Motivation
Traditional crowd monitoring systems rely on **camera-based surveillance, sensor networks, or mobile app tracking**, all of which have significant drawbacks such as **privacy concerns, high costs, and dependency on user participation**. This project overcomes these limitations by using **Wi-Fi RSSI values** collected from existing wireless infrastructure, ensuring an **efficient and non-intrusive solution** for crowd estimation.

## 📊 Dataset Collection & Preprocessing
The dataset was collected from **two urban locations**, capturing **real-time Wi-Fi RSSI values** associated with crowd density. Each collection session lasted **one hour**, resulting in a dataset with **over 15,000 samples**. Key preprocessing steps included:
- **Outlier removal and signal smoothing** to reduce noise.
- **Normalization and feature engineering** for enhanced model performance.
- **Timestamp alignment and manual crowd counts** for ground truth validation.

## 🛠️ Methodology
Several machine learning models were implemented and compared to determine the most effective approach for **RSSI-based crowd density estimation**:
- **Random Forest (RF)** - Performed best due to its ability to handle noise and nonlinear relationships.
- **Convolutional Neural Network (CNN)** - Showed potential but required a larger dataset for generalization.
- **XGBoost Regressor** - Delivered strong results but required extensive hyperparameter tuning.
- **K-Nearest Neighbors (KNN)** - Struggled with noisy data and signal fluctuations.

## 📈 Model Evaluation
To assess model effectiveness, various **evaluation metrics** were utilized, including **Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE)**. The **Random Forest model outperformed other approaches**, making it the most suitable choice for real-world deployment.

## 🎯 Results & Business Impact
This project successfully demonstrates that **Wi-Fi RSSI signals can be leveraged for accurate and real-time crowd density estimation**. The proposed solution is:
- **Privacy-preserving**, as it does not rely on image-based tracking.
- **Cost-effective**, utilizing existing Wi-Fi infrastructure without additional hardware.
- **Scalable**, allowing seamless deployment in **airports, malls, train stations, and public venues**.

## 🔮 Future Enhancements
Several improvements can further refine the system:
- **Integration of Reinforcement Learning (RL)** for adaptive crowd estimation.
- **Utilization of Channel State Information (CSI)** alongside RSSI for improved accuracy.
- **Implementation of Federated Learning** to ensure data privacy while enhancing model performance.
- **Deployment on edge devices** for real-time, low-latency crowd estimation.



