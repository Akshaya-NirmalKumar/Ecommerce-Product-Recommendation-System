# 🛍️ E-commerce Product Recommendation System

This project is a machine learning-based recommendation engine designed for an e-commerce platform. It utilizes customer behavior data to provide personalized product suggestions, enhancing user experience and driving sales. This work was developed as part of my internship under the **Data Analytics Track** at **Next24tech Technology & Services**.

---

# 📂 Dataset

We used a publicly available dataset from Kaggle that contains transactions from a UK-based online retail store.
We used a publicly available dataset containing historical transactional data from an online retail store.

📊 Dataset Title: E-Commerce Dataset - Online Retail

📥 Download Link: https://www.kaggle.com/datasets/vijayuv/onlineretail

📄 File Used: archive.zip → data.csv
The dataset includes:
- Invoice information
- Product descriptions
- Quantity and pricing
- Customer IDs
- Country and date of transaction

---

# 💻 Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn** (Collaborative Filtering, K-Nearest Neighbors)

---

# 🔧 Project Workflow

# 1. Data Preprocessing
- Removed duplicates and null entries
- Handled missing CustomerIDs
- Filtered valid transactions (positive quantity and price)

# 2. Exploratory Data Analysis (EDA)
- Identified top-selling products and countries
- Analyzed customer buying patterns
- Visualized sales frequency and product interactions

# 3. Feature Engineering
- Built user-item interaction matrix
- Applied normalization techniques
- Filtered sparse user/product activity

# 4. Model Building
- Implemented **KNN-based Collaborative Filtering**
- Trained using cosine similarity to recommend products
- Evaluated recommendations for accuracy and relevance

---

# 📌 Key Highlights

- 🔍 Recommender system based on **real-world behavioral data**
- 📉 Reduced noise and improved relevance via filtering
- ⚙️ Lightweight, scalable, and adaptable to new data
- 🚀 Enhances customer experience by showing products they’re likely to buy

---

# ✅ Final Output

The model recommends **top N products** for each customer based on purchase similarity with others. It can be extended for:
- Cart-based suggestions
- Similar product discovery
- Targeted promotions

---

## 📁 Repository Structure
📦Ecommerce-Product-Recommendation-System/
┣ 📄 Ecomm_Recommender.ipynb
┣ 📄 data.csv
┗ 📄 README.md

---

# 📬 Contact

If you’d like to know more about the system or collaborate:

**Akshaya Nirmal Kumar**  
[GitHub](https://github.com/Akshaya-NirmalKumar) | [LinkedIn](https://www.linkedin.com/in/akshaya-nirmalkumar)  

---

> 💡 *“The best marketing doesn't feel like marketing – it feels like personalized value.”*  


