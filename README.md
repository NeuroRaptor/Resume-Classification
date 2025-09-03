# Resume Classification

## 📌 Overview
The **Resume Classification** is a machine learning project that automates the classification of resumes, reducing manual effort, increasing accuracy, and enabling faster handling of large volumes of applications.  
The system uses models such as **Decision Tree**, **Random Forest**, **Support Vector Machine (SVM)**, and **XGBoost** to achieve high accuracy in categorizing resumes with minimal human intervention.

## 👥 Authors
- Amit Rangane (38915109)  
- Arpit Amborkar (47483065)  
- Thilak Raju Sampath Kumar (40359170)  

Group: DSC-C-07  

## 🎯 Objectives
- **Reduce Manual Effort**: Free HR professionals from repetitive screening tasks.  
- **Increase Accuracy**: Improve classification precision and reduce miscategorization.  
- **Promote Automation**: Enable scalable and efficient resume categorization.  

## 🗂 Dataset
- **Source:** Collected resumes in different formats  
- **Formats:** `.pdf`, `.doc`, `.docx`  
- **Preparation Steps:**  
  - Conversion to `.docx`  
  - Text extraction with dedicated libraries  
  - Organization into a structured dataframe with file metadata  

## 🔬 Methodology
1. **Data Collection & Preparation**  
   - Gather resumes in multiple formats.  
   - Convert files and extract text.  
   - Store structured data in a dataframe.  

2. **Exploratory Data Analysis (EDA)**  
   - Clean text (remove stopwords, special characters).  
   - Generate visualizations (word clouds, bigrams, trigrams, pie charts).  
   - Refine dataset by removing irrelevant columns.  

3. **Modeling**  
   - Logistic Regression  
   - Naive Bayes  
   - Support Vector Machine (SVM)  
   - Decision Tree  
   - Random Forest  
   - XGBoost  

4. **Evaluation**  
   - Accuracy comparison across models  
   - Decision Tree achieved the highest accuracy among simpler models  
   - **XGBoost selected as final model** due to superior performance and robustness  

## 📊 Results
- **Decision Tree**: High accuracy among classical models  
- **SVM**: Moderate accuracy, dataset dependent  
- **XGBoost**: Best performance overall, robust and scalable  

**Final Model: XGBoost**  

## 💡 Discussion
- Automated resume classification reduces HR workload.  
- Improves efficiency in candidate shortlisting.  
- Ensemble methods (like XGBoost) outperform traditional models in accuracy and generalization.  

## ⚠️ Limitations
- Dependent on quality of text extraction from resumes.  
- Model performance may vary with unstructured or unconventional resume formats.  

## 🚀 Future Work
- Extend system to handle **multi-language resumes**.  
- Incorporate **deep learning models** for richer feature extraction.  
- Integrate into an **HR management system (HRMS)** for real-time deployment.  

## 🏁 Conclusion
The Resume Classification System demonstrates how **machine learning and automation** can streamline HR processes, improve classification accuracy, and reduce manual intervention, ultimately making recruitment more efficient.  

---
