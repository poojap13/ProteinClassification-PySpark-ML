# 🧬 Exploratory Data Analysis and Predicting Protein Classification

## 📌 Project Overview

This project explores predicting the family type of proteins based on their sequences using machine learning techniques. Proteins are essential macromolecules with diverse functions in biological systems. Classifying them by family types provides insights into their structure, function, and role in biological processes.

This notebook was originally part of an academic group project and has been adapted and included in my personal portfolio.

---

##  Dataset

The dataset contains a range of biologically significant macromolecules, primarily proteins. Each record includes the protein sequence, its classification, and other related attributes.

---

##  Methodology

1. **Data Preprocessing**  
   - Filtered out non-protein molecules  
   - Handled missing values and removed duplicates

2. **Exploratory Data Analysis (EDA)**  
   - Analyzed classification distribution  
   - Visualized insights using Seaborn & Matplotlib

3. **Feature Extraction**  
   - Tokenized protein sequences  
   - Converted features using regex tokenization and count vectorization

4. **Model Training**  
   - Trained Naive Bayes classifier using PySpark MLlib  
   - Tested multiple classifiers including SVM, Random Forest, etc.

5. **Evaluation**  
   - Evaluated performance using accuracy, confusion matrix, classification report

---

## 🛠️ Tools & Technologies

- **Languages**: Python  
- **Libraries**: PySpark, Scikit-learn, Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Other**: MongoDB, Tkinter (GUI integration)

---

## 🚀 How to Run

1. **Environment Setup**  
   - Requires Python 3.x, PySpark, MongoDB, and listed libraries

2. **Data Access**  
   - Use the provided dataset (protein sequences & classifications)

3. **Run Notebook**  
   - Open the notebook in Jupyter/Colab and run all cells

4. **Review Outputs**  
   - Analyze results, graphs, and model metrics

---

## 👩‍💻 Author

**Pooja Pathare**  
_MSc Computer Science graduate with a focus on Data Science and AI._  

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).
