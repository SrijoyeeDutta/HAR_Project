# Human Action Recognition

This project implements a Human Action Recognition system using computer vision and deep learning techniques. The system identifies and classifies various human activities from video input by leveraging pose estimation and temporal feature analysis.

📌 Project Objectives

- Recognize and classify human actions from video clips.
- Use pose estimation (MediaPipe) to extract skeletal keypoints.
- Train a deep learning model to predict actions based on pose sequences.

🧠 Methodology

1. Pose Detection: MediaPipe Pose is used to extract 33 body keypoints per frame.
2. Feature Engineering: Keypoints are represented using X, Y, Z coordinates and visibility.
3. Data Preparation: Sequences of 30 frames per video are used to create training samples.
4. Model Architecture: A neural network (LSTM/Conv1D) built with TensorFlow/Keras processes these sequences to classify actions.
5. Training and Evaluation: The model is trained on labeled data and evaluated using metrics like accuracy and confusion matrix.

🛠️ Technologies Used

- Python
- Jupyter Notebook
- MediaPipe
- OpenCV
- NumPy
- TensorFlow / Keras
- scikit-learn
- Matplotlib

📊 Results
Validation Accuracy: XX%

📌 Future Enhancements
Add real-time webcam-based action recognition.
Expand the dataset to include more action classes.
Use hybrid models (CNN + LSTM) to improve accuracy.

👩‍💻 Author
Srijoyee Dutta
MCA Student, University of Calcutta


