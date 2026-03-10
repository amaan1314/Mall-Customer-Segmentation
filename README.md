# 🛍️ Mall Customer Segmentation & Analytics Dashboard

An end-to-end Machine Learning project that utilizes **Unsupervised Learning** to group retail customers into distinct segments based on their demographics and spending patterns. The project includes a trained **K-Means Clustering** model and an interactive **Streamlit dashboard** for real-time business insights.

## 🚀 Project Overview
In the retail industry, a "one-size-fits-all" marketing strategy is rarely effective. This project aims to solve this by identifying hidden patterns in customer data. By grouping customers with similar behaviors, businesses can:
* **Targeted Marketing:** Send specific ads to the right people.
* **Customer Retention:** Identify high-value customers at risk of leaving.
* **Strategic Planning:** Optimize store inventory based on cluster demographics.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Data Analysis:** Pandas, NumPy
* **Visualization:** Plotly, Seaborn, Matplotlib
* **Machine Learning:** Scikit-Learn (K-Means, StandardScaler)
* **Model Deployment:** Joblib
* **Web Framework:** Streamlit

## 📊 Dataset
The project uses the **Mall Customers Dataset**, which includes:
* **Age:** Age of the customer.
* **Annual Income (k$):** Yearly income of the customer.
* **Spending Score (1-100):** A score assigned by the mall based on customer behavior and spending nature.

## 🧠 Machine Learning Workflow
1.  **Exploratory Data Analysis (EDA):** Visualizing distributions and correlations.
2.  **Data Preprocessing:** Feature scaling using `StandardScaler` to ensure all features contribute equally to the distance calculations.
3.  **Optimal Clusters:** Using the **Elbow Method** to determine that 5 clusters provide the best segmentation.
4.  **Clustering:** Implementing **K-Means** to group the data points.
5.  **Classification:** Training a model to predict the cluster for new data entries.

## 💻 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/Mall-Customer-Segmentation.git](https://github.com/YOUR_USERNAME/Mall-Customer-Segmentation.git)
    cd Mall-Customer-Segmentation
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the Streamlit App:**
    ```bash
    streamlit run streamlit_app.py
    ```

## 🔍 Identified Segments
* **Cluster 0: Premium Targets** (High Income, High Spending)
* **Cluster 1: Growth Opportunities** (Average Income, Average Spending)
* **Cluster 2: Budget Seekers** (Low Income, High Spending)
* **Cluster 3: Relationship Building** (High Income, Low Spending)
* **Cluster 4: Exclusive/Frugal** (Low Income, Low Spending)

## 👤 Author
**Mohammed**
* Data Science Student & Engineering Fresher
* [LinkedIn](YOUR_LINKEDIN_URL) | [Portfolio](YOUR_PORTFOLIO_URL)

---
*This project was developed as part of my professional development in Data Science and Machine Learning.*
