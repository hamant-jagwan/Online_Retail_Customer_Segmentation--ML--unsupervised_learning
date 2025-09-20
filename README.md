## Link to Dataset.
   https://docs.google.com/spreadsheets/d/1_W3Jfp1bTWpPFmqyGgGXYJGd0rHIV8dD/edit#gid=501524341
   
<p align="center"> 
<img src=""  width="600" height="400" alt="GIF">
</p>
# Online Retail Customer Segmentation  

## 📌 Project Overview  
This project applies **Unsupervised Machine Learning** techniques to perform **customer segmentation** on an **online retail dataset**. The aim is to group customers into meaningful clusters based on their purchase behavior, enabling businesses to:  
- Identify high-value customers  
- Improve marketing strategies  
- Personalize offers and recommendations  

## 🧾 Dataset  
The dataset contains transactional data from an online retail store, including:  
- **Invoice No.** – Unique identifier for each transaction  
- **Stock Code** – Product code  
- **Description** – Product description  
- **Quantity** – Number of items purchased  
- **Invoice Date** – Date of purchase  
- **Unit Price** – Price per item  
- **Customer ID** – Unique identifier for customers  
- **Country** – Customer location  

## ⚙️ Methodology  
1. **Data Preprocessing**  
   - Handling missing values  
   - Removing invalid transactions  
   - Feature engineering (e.g., Recency, Frequency, Monetary – RFM model)  

2. **Exploratory Data Analysis (EDA)**  
   - Visualization of customer behavior  
   - Distribution of sales across countries  
   - Identification of top customers  

3. **Clustering (Unsupervised Learning)**  
   - Applied **K-Means clustering**  
   - Optimal number of clusters determined using Elbow Method & Silhouette Score  
   - Customer segmentation performed based on RFM features  

4. **Evaluation & Insights**  
   - Cluster interpretation (e.g., high-value vs low-value customers)  
   - Actionable recommendations for business strategy  

## 🛠️ Tech Stack  
- **Programming Language:** Python  
- **Libraries Used:**  
  - pandas, numpy (data processing)  
  - matplotlib, seaborn (visualization)  
  - scikit-learn (clustering, scaling, evaluation)  

## 📊 Results  
- Customers were successfully segmented into distinct groups  
- High-value customer clusters identified for targeted marketing  
- Clear differentiation between frequent buyers, occasional buyers, and one-time buyers  

## 🚀 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/online-retail-customer-segmentation.git
   cd online-retail-customer-segmentation

