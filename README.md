
# 🚀 Customer Segmentation & Churn Prediction

Uncover hidden customer patterns 📊 and predict churn 📉 using Machine Learning!  
This project blends clustering and classification to give telecom companies actionable insights for reducing customer attrition and increasing loyalty.

---

## 🎯 Goals

🔹 **Segment customers** into distinct groups based on behavior and demographics  
🔹 **Predict churn** using logistic regression and interpret key features  
🔹 **Visualize insights** to inform strategic retention campaigns

---

## 📁 Dataset Overview

The dataset includes 7,000+ customer records from a telecom provider, featuring:

- 🧑‍💼 `CustomerID`, `Gender`, `SeniorCitizen`, `Partner`, `Dependents`  
- 📡 `PhoneService`, `InternetService`, `StreamingTV`, `OnlineBackup`  
- 💰 `MonthlyCharges`, `TotalCharges`, `Contract`, `PaymentMethod`  
- 🔚 `Churn` – our target variable  

---

## 🧠 Workflow Summary

### 🔹 1. Data Cleaning & Exploration
- Removed missing or invalid `TotalCharges` values
- Converted categorical columns to numeric (Label Encoding / OneHot)
- Conducted EDA using histograms, countplots, and correlation matrix

### 🔹 2. Customer Segmentation (📍K-Means Clustering)
- Scaled numeric data using `StandardScaler`
- Applied **K-Means Clustering**
- Determined optimal clusters with the **Elbow Method**
- Visualized customer groups using PCA for 2D projection

### 🔹 3. Churn Prediction (📈 Logistic Regression)
- Built a logistic regression model to classify churn
- Split data into train/test sets
- Evaluated model using accuracy, confusion matrix, and feature weights

---

## 📸 Visuals Included

- 🔥 Correlation Heatmap
- 💠 PCA Cluster Visualization
- 🎯 Churn Distribution by Segment
- 📊 Feature Importance from Logistic Regression
- 🧩 Confusion Matrix

---

## 🧰 Tech Stack

| Category            | Tools Used                                  |
|---------------------|----------------------------------------------|
| Language            | Python 3.x 🐍                                |
| Data Wrangling      | pandas, numpy                               |
| Clustering          | scikit-learn (KMeans, PCA)                  |
| Classification      | scikit-learn (LogisticRegression)           |
| Visualization       | seaborn, matplotlib                         |
| Notebook Interface  | Jupyter Notebook                            |

---

## ⚙️ How to Run the Project

1. **Clone this repository**
```bash
git clone https://github.com/yourusername/customer-churn-segmentation.git
cd customer-churn-segmentation
```

2. **Create a virtual environment (optional but recommended)**
```bash
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate
```

3. **Install the required dependencies**
```bash
pip install -r requirements.txt
```

4. **Launch the notebook**
```bash
jupyter notebook "Customer Segmentation & Churn Prediction.ipynb"
```

---

## 🧪 Sample Requirements.txt

Here’s a sample of dependencies you can use:

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

## 🔍 Key Business Takeaways

✅ Month-to-month contract customers show **high churn probability**  
✅ Adding **Tech Support, Online Security, and Backup** reduces churn  
✅ Customers with **short tenure and high charges** are at higher risk  
✅ Clustering allows for **custom marketing strategies** for each segment  

---

## 🚧 Future Enhancements

- 🌲 Add more robust classifiers like **Random Forest**, **XGBoost**
- ⚖️ Use **SMOTE** or other techniques to handle class imbalance
- 📊 Build a **Streamlit app** for real-time churn insights
- 🤖 Integrate **AutoML** pipeline for better hyperparameter tuning

---

## 📜 License

This project is licensed under the **MIT License**.  
Feel free to use it, modify it, and share it freely!

---

## 👩‍💻 Author

**Akshita Mishra**  
📫 Email: akshitamishra@example.com  
🌐 Portfolio: [akshitamishra.dev](https://akshitamishra.dev)  
💼 LinkedIn: [linkedin.com/in/akshitamishra](https://linkedin.com/in/akshitamishra)  
📁 GitHub: [github.com/Akshita7844](https://github.com/Akshita7844)

---

## ⭐️ Show Your Support

If you find this project helpful, please consider giving it a ⭐️ on [GitHub](https://github.com/Akshita7844)!
