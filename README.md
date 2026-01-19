# 🤖 AI Powered Customer Segmentation

An unsupervised machine learning project that segments customers into meaningful groups based on purchasing behavior. This enables targeted marketing, customer personalization, and improved business insights.

---

## 🚀 Features

* K-means clustering for segmentation
* Clean EDA & visualization workflow
* Model exported for reuse
* Optional prediction script for new customers
* Business-friendly interpretations

---

🌍 Live Deployment : https://aipoweredcustomersegmentation-01.streamlit.app

## 📂 Project Structure

```
📁 AI_Powered_Customer_Segmentation
│── customer-segmentation.ipynb      # Training + EDA notebook
│── customer_app.py                  # Prediction script/app
│── customer_segmentation_model.pkl  # Saved clustering model
│── Mall_Customers.csv               # Dataset
│── requirements.txt                 # Dependencies
└── README.md
```

---

## 🧠 Model Details

* Algorithm: **K-Means Clustering**
* Type: **Unsupervised Learning**
* Libraries used:

  * pandas
  * numpy
  * scikit-learn
  * matplotlib
  * seaborn

Dataset used: **Mall Customers Dataset**

---

## 🏗️ Installation & Setup

Clone the repository:

```bash
git clone https://github.com/your-username/AI_Powered_Customer_Segmentation.git
cd AI_Powered_Customer_Segmentation
```

---

### 1️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

---

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🧾 Training the Model

Training is done inside the Jupyter notebook:

```bash
jupyter notebook customer-segmentation.ipynb
```

Running all cells generates:

```
customer_segmentation_model.pkl
```

---

## 🌐 Run the App (Optional)

If `customer_app.py` is included:

```bash
python customer_app.py
```

Enter new customer values to get a predicted segment.

---

## 📊 Input Features

This model uses:

* Annual Income (k$)
* Spending Score (1–100)

---

## 📦 Requirements

Included in `requirements.txt`:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
```

Install via:

```bash
pip install -r requirements.txt
```

---

## 📈 Visualizations Included

* Elbow method
* Cluster scatter plots
* Centroid visualization
* Data distribution plots

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Acknowledgements

Dataset: Mall Customers Dataset (Kaggle)
Technologies: Python, Scikit-Learn, Jupyter

---

Made with ❤️ by **Parivesh Tiwari**

