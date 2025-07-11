# Visual and Predictive Analysis of Brain Tumors from MRI Using Machine Learning

## 📌 Project Overview
This project focuses on building a machine learning-based system that can analyze MRI scans to detect and classify brain tumors. It leverages a combination of image preprocessing, feature extraction, and classification algorithms to assist in early detection and diagnosis of brain tumors such as gliomas, meningiomas, and pituitary adenomas.

## 🗂️ Dataset
The dataset used is the Brain Tumor MRI Scan Dataset, which consists of:
- Positive Class (tumor present): Includes MRI scans labeled with glioma, meningioma, and pituitary tumor images.
- Negative Class (no tumor): Includes healthy brain MRI scans for baseline comparison.
These images are used to train, validate, and test machine learning models for classification tasks.
 
This dataset is available at https://www.kaggle.com/datasets/praneet0327/brain-tumor-dataset

## ⚙️ Technologies Used
- Python
- OpenCV
- NumPy, Pandas
- Scikit-learn
- Matplotlib / Seaborn
-Jupyter Notebook

## 🧪 Methodology
1. Data Preprocessing
- Image resizing and normalization
- Data augmentation (optional)

2. Feature Extraction
- Grayscale conversion
- Histogram analysis
- Edge detection techniques (e.g., Canny)

3. Model Training
- Models: SVM, Random Forest, KNN
- Evaluation: Accuracy, Precision, Recall, F1 Score

4. Visualization
- Tumor highlighting using bounding techniques
- Model performance plots

## 📊 Results
The model achieves high accuracy in differentiating between tumor and non-tumor images. Feature visualization and evaluation metrics are used to validate the model's performance across various scenarios.

## 🧠 Future Work
- Integrate deep learning (e.g., CNNs) for improved accuracy.
- Classify tumor types and severity.
- Build a web interface or diagnostic app for practical usability.

## 🚀 Getting Started
Clone this repo:
<pre><code>git clone https://github.com/yourusername/brain-tumor-mri-analysis.git
cd brain-tumor-mri-analysis</code></pre>
Install dependencies:
<pre><code>pip install -r requirements.txt</code></pre>
Run the notebook or main script to train and test the model.

