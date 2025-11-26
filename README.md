# Algonive_Data_Analytics_Projects
# 🧠 Customer Segmentation Using K-Means Clustering

## 📌 Project Overview
This project performs customer segmentation using machine learning to group customers based on behavior and spending patterns. This enables businesses to personalize marketing, improve customer experience, and increase revenue.

## 🎯 Objective
- Analyze purchasing behavior of customers
- Apply clustering to identify customer segments
- Visualize patterns between spending score and income

## 📁 Dataset Description
Dataset: Mall Customer Segmentation Dataset  
Columns included:
| Column | Description |
|--------|-------------|
| CustomerID | Unique ID for each customer |
| Gender | Male/Female |
| Age | Age of the customer |
| Annual Income (k$) | Income level |
| Spending Score | Score assigned based on spending behavior |

## 🛠 Data Processing Steps
- Handling missing values & duplicates
- Exploratory Data Analysis (EDA)
- Feature selection & scaling using StandardScaler
- Elbow Method to select optimal cluster count
- K-Means clustering

## 📊 Visualizations
- Age Distribution Plot
- Gender Distribution Plot
- Income vs Spending Score Scatter plot
- Cluster visualization based on K-Means

## 🤖 Model & Techniques Used
- **K-Means Clustering**
- **Elbow Method**
- **Standard Scaling**
- **Seaborn / Matplotlib** visualizations

## 🧾 Key Insights
- Customers grouped into 5 unique clusters
- Identified high-value customers with high spending power
- Useful for targeted marketing strategies

## 📦 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 👤 Author
**Supriya Suryawanshi**

# 📈 Retail Sales Data Analysis & Forecasting (ARIMA)

## 📌 Project Overview
This project analyzes historical retail sales data to extract business insights and predict future revenue using time-series forecasting.

## 🎯 Objective
- Understand revenue patterns and trends
- Analyze category-wise and demographic-wise sales
- Forecast future sales to support business decisions using ARIMA

## 📁 Dataset Description
Retail sales dataset including:
| Column | Description |
|--------|-------------|
| Transaction ID | Unique transaction number |
| Date | Date of purchase |
| Customer ID | Customer identifier |
| Gender | Male/Female |
| Age | Customer age |
| Product Category | Purchased item category |
| Quantity | Units purchased |
| Price per Unit | Price per item |
| Total Amount / Revenue | Total revenue (calculated) |

## 🧠 Data Analysis Performed
- Data Cleaning & preprocessing
- Revenue trend visualization
- Product category sales comparison
- Gender & age-based revenue analysis
- Creation of daily aggregated sales

## 🔮 Forecasting Model
- Train/test split (80–20)
- ARIMA forecasting model using `auto_arima`
- Predicted revenue values for test period
- Actual vs Predicted comparison plot

## 📊 Visual Outputs
- Daily Revenue Trend Graph
- Revenue by Product Category Bar Chart
- Age vs Revenue Scatter Plot
- Predicted vs Actual Sales Chart

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- pmdarima (ARIMA)
- Google Colab

## 🧾 Key Insights
- Identified demand trends & seasonality in sales
- Defined peak sales periods and product categories
- Forecasting enables better inventory & marketing planning

## 👤 Author
**Supriya Suryawanshi**
