# VARS-NLP-Project

## Quality Control Report Analysis  
**Course:** NLP (Semester 6) - Pillai College of Engineering  

---

## Project Overview  
This project focuses on classifying manufacturing quality reports into predefined categories such as **compliant, minor defects,** or **major issues**. By leveraging machine learning and deep learning models, the system enables quality assurance teams to prioritize product batches, identify critical defects faster, and enhance overall production efficiency.

---

## Acknowledgements  
We would like to express our sincere gratitude to the following individuals:

### **Theory Faculty:**  
- Dhiraj Amin  
- Sharvari Govilkar  

### **Lab Faculty:**  
- Dhiraj Amin  
- Neha Ashok  
- Shubhangi Chavan  

Their guidance and support have been invaluable throughout this project.

---

## Project Abstract  
Quality assurance plays a vital role in maintaining product standards and reducing production defects in the manufacturing industry. This project leverages **natural language processing (NLP)** to analyze textual data from quality reports and classify them into categories: **compliant, minor defects, and major issues**.  

The dataset consists of two key columns:
- **Report Text** - The content of the quality report.  
- **Category** - The assigned quality status.  

Through preprocessing techniques such as **tokenization, stopword removal, and lemmatization**, raw text is transformed into a structured format. The classification is performed using **machine learning, deep learning, and large language models (LLMs)** to enhance automation, improve defect detection efficiency, and minimize production waste.

---

## Algorithms Used  
### **Machine Learning Algorithms**  
- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest Classifier  

### **Deep Learning Algorithms**  
- Convolutional Neural Networks (CNN)  
- Bidirectional Long Short-Term Memory (BILSTM)  
- Long Short-Term Memory (LSTM)  
- Gated Recurrent Unit (GRU)  
- Multilayer Perceptron (MLP)  

### **Language Models**  
- ROBERTA (Robustly Optimized BERT Approach)  
- BERT (Bidirectional Encoder Representations from Transformers)  

---

## Comparative Analysis  
Below is a comparative analysis of the different models used in the project:

| Model | Notes/Predictions |
|--------|-----------------|
| **Logistic Regression** | High accuracy for TF-IDF, struggles with imbalanced data. |
| **SVM** | Performs well with TF-IDF, sensitive to feature scaling. |
| **Random Forest** | High accuracy, handles imbalanced data better. |
| **CNN** | Strong with word embeddings but overfits on small datasets. |
| **BILSTM** | Slightly better with embeddings, but still weak. |
| **GRU** | Performs similarly to LSTM but slightly better in efficiency. |
| **MLP** | Works well on structured data but lacks deep contextual understanding. |
| **Transformer** | Struggles with small datasets, requires large training data. |
| **BERT** | Predictions: (Rejected, Approved, Rejected) for three input texts. |
| **ROBERTA** | Predictions: (Rejected, Rejected, Approved) for three input texts. |

---

## Conclusion  
This project effectively utilizes **machine learning and NLP** techniques to classify manufacturing quality reports into predefined categories. The application of **tokenization, stopword removal, and lemmatization** improves the model's accuracy by converting raw textual data into a structured format. 

By automating the classification process, this system allows **quality assurance teams to prioritize product batches, quickly identify major defects, and improve overall production quality**. This approach not only minimizes manual effort but also helps reduce waste and inefficiencies, leading to a more streamlined and optimized manufacturing process.

---

## Learn More  
[Pillai College of Engineering](https://www.pce.ac.in/)
