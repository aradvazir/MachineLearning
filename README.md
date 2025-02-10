# Audio Processing
In this project, sound data of students is **preprocessed**, and **features are extracted**. These features are mapped to the space **spanned by PCs** of data, keeping **95% of variance**. Next, these features are used for **clustering** and **classification** tasks. Clustering algorithms include **sequential clustering** and **Kmeans**. Data is well-clustered based on gender of individuals, but not based on indentity of each individual. The potential reasons are discussed in the report. Besides, 3 algorithms are provided for clustering data for gender and identity.

## **Classification**  
- **Gender Classification**:
  - **Logistic Regression**: **99% accuracy**  
  - **SVM**: **99% accuracy**  
  - **MLP (Neural Network)**: **97% accuracy**  
  - **K-Nearest Neighbors (KNN)**: **86% accuracy**  

- **Closed-set Speaker Authentication** (10-class classification):  
  - **Logistic Regression**: **100% accuracy**  
  - **SVM**: **96%-99% accuracy**  
  - **MLP**: **Promising performance, improving over training epochs**  
  - **KNN**: **64%-83% accuracy (struggled with misclassifications)**  

### **Results & Analysis**
- **Gender classification was highly accurate** across different models.  
- **Speaker authentication** was **more challenging**, with **SVM and MLP performing best**.  
- **KNN struggled with misclassifications**, indicating a need for better feature selection.  
- The **report discusses possible reasons** for difficulties in speaker authentication, such as **overlapping speaker features**.

Code of the project is also provided in this repo.
