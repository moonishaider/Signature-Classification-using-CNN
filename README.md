# Signature-Classification-using-CNN
This project implements and evaluates three models for signature recognition:

	1.	HOG-ANN: Manual feature extraction with Histogram of Oriented Gradients (HOG) and an Artificial Neural Network.
	2.	SIFT-ANN: Manual feature extraction with Scale-Invariant Feature Transform (SIFT) and an Artificial Neural Network.
	3.	CNN: A Convolutional Neural Network trained directly on image data.

Steps for Metrics Calculation

	1.	Load Data: Use ImageDataGenerator for data augmentation and normalization.
	2.	Feature Extraction:
	•	HOG: Extracts features using HOG from skimage.
	•	SIFT: Extracts features using SIFT from OpenCV.
	3.	Model Training:
	•	Train ANN models for HOG and SIFT features.
	•	Train CNN model directly on image data.
	4.	Evaluation:
	•	Calculate Precision, Recall, F1-Score, and Accuracy.
	•	Generate Confusion Matrices, ROC Curves, and Accuracy/Loss plots.

Visualizations

	•	Includes Confusion Matrices, ROC Curves, and Accuracy/Error plots to demonstrate model performance.

Dependencies

	•	Python
	•	TensorFlow
	•	Keras
	•	OpenCV
	•	scikit-learn
	•	matplotlib
	•	scikit-image
