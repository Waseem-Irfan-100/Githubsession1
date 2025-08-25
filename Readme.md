🩺 Breast Cancer Classification (UCI Dataset)

This project uses the Breast Cancer Wisconsin (Original) Dataset from the UCI Machine Learning Repository to classify tumors as benign (2) or malignant (4) using machine learning.


---

📂 Dataset

Source: UCI ML Repository

Instances: 699

Features: 9 numeric features (e.g., clump thickness, uniformity of cell size/shape, bare nuclei, mitoses).

Target Classes:

2 → Benign

4 → Malignant


Note: Dataset has missing values, handled with mean imputation.



---

⚙️ Workflow

1. Data Loading

Fetched dataset directly from UCI using ucimlrepo.



2. Preprocessing

Missing values handled with SimpleImputer(strategy="mean").

Split into train (80%) and test (20%).

Standardized features with StandardScaler.



3. Model Training

Algorithm used: Logistic Regression.



4. Evaluation

Performance measured with accuracy, precision, recall, and F1-score.





---

📊 Results

Accuracy: ~97%

Benign (2): Precision = 0.97, Recall = 0.99

Malignant (4): Precision = 0.98, Recall = 0.94



---

🚀 How to Run

1. Clone this repository:

git clone https://github.com/your-username/breast-cancer-classification.git
cd breast-cancer-classification


2. Install dependencies:

pip install -r requirements.txt


3. Run the notebook:

jupyter notebook Breast_cancer.ipynb




---

📦 Dependencies

Listed in requirements.txt:

pandas==1.5.3
numpy==1.24.0
scikit-learn==1.1.3
ucimlrepo


---

📌 Future Work

Compare with other models (Random Forest, SVM, Gradient Boosting).

Hyperparameter tuning (GridSearchCV, RandomizedSearchCV).

Deploy as a web app (Flask/Django).



---

🙌 Acknowledgements

Dataset: UCI ML Repository – Breast Cancer Wisconsin (Original)

Tools: Scikit-learn, Pandas, NumPy



---

Would you like me to also show you the ideal GitHub repo folder structure (how to place README.md, requirements.txt, and your notebook) so it looks professional?

