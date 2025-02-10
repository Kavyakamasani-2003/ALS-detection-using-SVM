# ALS Detection Using SVM

## Overview
This project focuses on detecting Amyotrophic Lateral Sclerosis (ALS) using a Support Vector Machine (SVM) model. It utilizes muscle strength data to classify individuals as ALS-positive or ALS-negative. The dataset used is the PROACT Muscle Strength dataset.

## Features
- Implements machine learning techniques for ALS detection.
- Uses the Support Vector Machine (SVM) classifier.
- Utilizes a predefined muscle strength dataset for training and evaluation.
- Provides insights into the effectiveness of SVM in medical diagnosis.

## Dataset
- **File:** `PROACT_MUSCLESTRENGTH.csv`
- **Description:** Contains muscle strength measurements of individuals, which are used as features for the classification task.

## Requirements
To run this project, ensure you have the following dependencies installed:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Kavyakamasani-2003/ALS-detection-using-SVM.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ALS-detection-using-SVM
   ```
3. Run the Jupyter Notebook or Python script containing the model implementation.

## Project Structure
- `CODE.docx`: Contains the implementation details of the project.
- `Mini1publicationpaper.docx`: Research paper related to the project.
- `PROACT_MUSCLESTRENGTH.csv`: The dataset used for training and evaluation.

## Model Implementation
- Data preprocessing includes handling missing values, normalization, and feature selection.
- The SVM model is trained and evaluated using cross-validation techniques.
- Performance metrics such as accuracy, precision, recall, and F1-score are used to assess model effectiveness.

## Results
- The trained SVM model demonstrates its ability to classify ALS cases based on muscle strength features.
- Visualizations such as confusion matrices and ROC curves are generated to analyze performance.

## Future Work
- Exploring other machine learning models such as Random Forest, Neural Networks, or CNNs.
- Enhancing feature selection and data augmentation techniques.
- Expanding the dataset for better generalization.

## Contributors
- **Kavya Kamasani**  
  [GitHub Profile](https://github.com/Kavyakamasani-2003)

## License
This project is open-source and available under the MIT License.
