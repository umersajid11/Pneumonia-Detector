🩺 Chest X-Ray Pneumonia Detector: https://huggingface.co/spaces/UmerSajid/Chest_X_Ray_Pneumonia_Detector
🚀 A Machine Learning-powered web application that detects Pneumonia from Chest X-Ray images using a Random Forest Classifier. The model is trained using Scikit-Learn, and the application is deployed using Gradio on Hugging Face Spaces.

🌟 Features
✔️ Upload a chest X-ray image.
✔️ Automatic diagnosis: Predicts Pneumonia or Normal.
✔️ User-friendly UI: Interactive interface using Gradio.
✔️ Fast & Efficient: Optimized Random Forest Classifier.
✔️ Deployed on Hugging Face for easy access.

📌 Project Overview
1️⃣ Dataset
The dataset consists of chest X-ray images categorized as:
Pneumonia (Labeled as 1)
Normal (Labeled as 0)
Images are preprocessed and fed into a Random Forest model.
2️⃣ Model Training
Used RandomForestClassifier from Scikit-Learn.
Hyperparameter tuning done using GridSearchCV.
Trained model is saved as optimized_rf_model.pkl.
📊 Results
The Random Forest model achieved high accuracy on test images.
The app correctly identifies Pneumonia vs. Normal cases.

3️⃣ Deployment
Gradio is used for the user interface.
The model is hosted on Hugging Face Spaces.
Users can upload an X-ray image to get a real-time diagnosis.


🛠 Future Improvements
🔹 Improve model accuracy using Deep Learning (CNNs)
🔹 Add Explainability (Grad-CAM Visualization)
🔹 Deploy on Cloud (AWS, Google Cloud)

