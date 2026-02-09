# 🛍️ Mall Customer Clustering – Streamlit Application

This project demonstrates **customer segmentation using K-Means clustering**, followed by **cluster prediction using a KNN model**, deployed through an interactive **Streamlit web application**.

The workflow follows a real-world machine learning pipeline:
**Unsupervised Learning → Labeled Data → Supervised Prediction → Deployment**

---

## 📌 Project Workflow

### 1️⃣ K-Means Clustering (Training Phase)
- Implemented in `kmeans.ipynb`
- Customer segmentation performed using:
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)
- Optimal number of clusters selected
- Cluster labels generated and saved

### 2️⃣ KNN Model Training
- Used clustered dataset as labeled data
- Trained a KNN model to predict customer cluster
- Model saved as `knn_model.pkl`

### 3️⃣ Streamlit Deployment
- User inputs customer details
- Features scaled using `StandardScaler`
- KNN predicts the customer cluster
- Results displayed with visual insights and recommendations

---

## 🚀 Features

- K-Means clustering implementation
- KNN-based cluster prediction
- Interactive Streamlit dashboard
- Real-time predictions
- 3D cluster visualization using Plotly
- Cluster distribution pie chart
- Cluster descriptions & business recommendations
- Custom UI styling with CSS

---

## 🧠 Machine Learning Techniques Used

- K-Means Clustering (Unsupervised Learning)
- K-Nearest Neighbors (Supervised Learning)
- Feature Scaling
- Model Serialization using Joblib
- Data Visualization

---

## 📊 Dataset

**Mall_Customers.csv**

**Features Used:**
- Age  
- Annual Income (k$)  
- Spending Score (1–100)

**Generated File:**
- `Mall_customer_cluster.csv` – dataset with cluster labels

---

## 📂 Project Structure

📁 Mall-Customer-Clustering
│
├── app.py                    # Streamlit application
├── kmeans.ipynb              # K-Means clustering notebook
├── Mall_Customers.csv        # Original dataset
├── Mall_customer_cluster.csv # Dataset with cluster labels
├── knn_model.pkl             # Trained KNN model
├── requirements.txt
└── README.md

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/mall-customer-clustering.git

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Run the Streamlit application

streamlit run app.py

```
## 📈 Output

The Streamlit application provides the following outputs:

- Predicted customer cluster based on user input  
- Cluster name with descriptive characteristics  
- Customer distribution across all clusters  
- Interactive 3D cluster visualization  
- Business recommendations tailored to each cluster  

---

## 💼 Use Cases

This project can be applied in real-world scenarios such as:

- Retail customer segmentation  
- Targeted and personalized marketing strategies  
- Customer behavior analysis  
- Business decision-making and strategy planning  

