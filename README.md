# AI/ML Portfolio by Sector – Raghavendra S.

This repository demonstrates how I design and reason about **production-oriented ML systems** across multiple domains.

The focus is not on models alone, but on **end-to-end system design**:
- data pipelines
- training and evaluation workflows
- deployment strategies
- monitoring, drift detection, and operational reliability

These projects reflect how ML behaves in **real-world environments**, not just offline notebooks.

### How to Read This Portfolio

Each project highlights:
- the **problem framing**
- the **modeling choice**
- and most importantly, the **system implications** (scalability, monitoring, failure modes)

Some projects are marked WIP intentionally to reflect real production constraints.


📄 **[Download Full PDF Portfolio](./pdf/AI_Portfolio_RaghavendraS.pdf)**

---

## Project Highlights by Domain

### 🛒 Retail – [Sales Forecasting](https://github.com/coolhead/sales-forecasting)
- **Models:** XGBoost, SARIMA, LSTM
- **Outcome:** MAPE ~12%, sales trend insights
- **Tools:** MLflow, Streamlit, GitHub Actions
- System focus: model versioning, experiment tracking, CI for retraining
- [Retail – Sales Forecasting](./sections/sales_forecasting.md)
---

### Automotive – [Car Damage Detection](https://github.com/coolhead/car-damage-mlops-pipeline)
- **Models:** YOLOv8 (Object Detection)
- **Outcome:** Real-time image classification for insurance automation
- **Tools:** Roboflow, Ultralytics, AWS SageMaker
- System focus: inference latency, image pipeline consistency, deployment on managed ML platforms
- [Automotive – Car Damage Detection](./sections/car_damage_detection.md)

---

### Transport – [Bike Sharing Demand Prediction](https://github.com/coolhead/Predict-Bike-Sharing)
- **Models:** Linear Regression with VIF, Feature Selection
- **Outcome:** R² ~0.83, hourly demand forecasting
- **Tools:** Statsmodels, Seaborn, Sklearn
- 
- [Transport – Bike Sharing Demand Prediction](./sections/bike_sharing.md)
---

### Healthcare – [Melanoma Cancer Detection](https://github.com/coolhead/CNNAssignment)
- **Models:** CNN (Binary Classification)
- **Outcome:** Detects Melanoma from skin lesion images
- **Tools:** Keras, TensorFlow, Image Augmentation
- System focus: data leakage prevention, reproducibility, and clinical-risk sensitivity
- [Healthcare – Melanoma Detection](./sections/melanoma_detection.md)
---

### Ecology – [Bird Species Classification](https://github.com/coolhead/bird-classification)
- **Models:** Transfer Learning (ResNet-based CNN)
- **Outcome:** Species-level identification (WIP)
- **Tools:** SageMaker, PyTorch
- [Ecology – Bird Species Classification](./sections/bird_classification.md)
---

### 💳 Finance – [Credit Card Fraud Detection](https://github.com/coolhead/credit-card-fraud-detection) *(WIP)*
- **Models:** XGBoost, SMOTE, Logistic Regression
- **Outcome:** Classification of fraudulent transactions
- **Tools:** Imbalanced ML techniques (In Progress)

---

### Human-Computer Interaction – [Hand Gesture Recognition](https://github.com/coolhead/Python_Hand-Gesture-Recognition)
- **Models:** CNN for image classification, OpenCV + Mediapipe for gesture tracking
- **Outcome:** Real-time webcam-based gesture detection (e.g., thumbs up, peace)
- **Tools:** OpenCV, Mediapipe, TensorFlow/Keras, Python  
- [Hand Gesture Recognition – HCI](./sections/hand_gesture_recognition.md)

---

## Other Notable Projects

- [IRIS Classification + Streamlit + GitHub Actions](https://github.com/coolhead/IRIS_Classification_Streamlit_Pipeline_Project)
- [Hand Gesture Recognition](https://github.com/coolhead/Python_Hand-Gesture-Recognition)
- [NLP Complaint Ticket Classifier](https://github.com/coolhead/Complaint-Ticket-Classification-NLP)
- [MNIST CNN Classifier in PyTorch](https://github.com/coolhead/mnist-cnn-pytorch)

---

### About Me

I’m an AI Infrastructure & MLOps Architect with 18+ years of experience across DevOps, platform engineering, and production ML systems.

I focus on building **reliable, observable, and cost-aware ML platforms** across regulated and high-availability environments (AWS / Azure / Kubernetes).

This portfolio complements my architecture-led work by showing how models and systems behave together.


📫 [LinkedIn Profile](https://www.linkedin.com/in/raghavendra-s-380445214/)  
🔗 [GitHub Projects](https://github.com/coolhead)

---

