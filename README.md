
### **Neonatal Health Prediction using Machine Learning 🏥🤖**  

#### **Overview**  
This project applies various machine learning models to predict neonatal health outcomes based on clinical data. The dataset includes features like **birth weight, gestational age, SpO2 levels, Apgar scores, and more** to assess newborn health conditions.  

#### **Models Implemented 🧠📊**  
The following models were trained and evaluated for accuracy:  
-  **XGBoost** (Best performing model)  
-  **LightGBM**  
-  **Random Forest**  
-  **Gradient Boosting**  

#### **Key Features 🛠️**  
✔️ **Feature Correlation Analysis** – Heatmap to visualize relationships between variables  
✔️ **Exploratory Data Analysis (EDA)** – Distribution plots, boxplots, and count plots  
✔️ **Model Accuracy Comparison** – Bar chart to compare the models  
✔️ **Outlier Detection** – Boxplots to identify anomalies in neonatal health indicators  

#### **Why XGBoost? 🚀**  
After evaluating the models, **XGBoost** was chosen due to:  
🔹 **Highest Accuracy** – Outperformed other models in predictive performance  
🔹 **Handling of Imbalanced Data** – Effectively manages rare health conditions  
🔹 **Faster Training & Scalability** – Optimized for large datasets  
🔹 **Robustness & Generalization** – Reduces overfitting and improves reliability  

#### **Installation & Setup ⚙️**  
To run this project in **Google Colab** or locally, follow these steps:  
```bash
# Clone the repository
git clone https://github.com/your-username/neonatal-health-ml.git
cd neonatal-health-ml

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook new_code_toady.ipynb
```

#### **Results & Visualizations 📊**  
The notebook includes multiple **visualizations** to better understand the dataset:  
📌 **Feature Correlation Heatmap**  
📌 **Histograms of Key Features**  
📌 **Boxplots for Outlier Detection**  
📌 **Predicted Disease Distribution**  
📌 **Model Accuracy Comparison**  

#### **Contributing 🤝**  
If you’d like to contribute, feel free to fork the repository, make changes, and submit a **pull request**. Suggestions and improvements are always welcome!  

#### **License 📜**  
This project is **open-source** under the MIT License.  
