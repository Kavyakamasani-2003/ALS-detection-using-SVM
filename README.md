ALS Detection Using SVM

Overview

This project focuses on detecting Amyotrophic Lateral Sclerosis (ALS) using a Support Vector Machine (SVM) classifier. It leverages a dataset containing muscle strength measurements to classify individuals as ALS-positive or ALS-negative.

Dataset

PROACT_MUSCLESTRENGTH.csv: Contains muscle strength data used for training and testing the model.

Files in Repository

CODE.docx: Document containing code implementation details.

Mini1publicationpaper.docx: Research paper related to the project.

PROACT_MUSCLESTRENGTH.csv: Dataset used for ALS detection.

Approach

Data Preprocessing: The dataset is cleaned and normalized for better accuracy.

Feature Selection: Key features related to muscle strength are selected.

Model Training: The SVM classifier is trained on the dataset.

Evaluation: The model is tested on unseen data and performance metrics are calculated.

Installation & Usage

Clone the repository:

git clone https://github.com/Kavyakamasani-2003/ALS-detection-using-SVM.git

Install required dependencies:

pip install numpy pandas scikit-learn

Run the SVM model:

python als_detection.py

Results

The SVM model provides a reliable classification of ALS patients based on muscle strength features. The results can be further improved by incorporating deep learning techniques.

Future Enhancements

Implementing CNNs for speech-based ALS detection.

Expanding the dataset with additional biomarkers.

Improving accuracy with hyperparameter tuning.

Contributors

Kavyakamasani-2003

License

This project is open-source and available under the MIT License.

