🏙️ Airbnb Bangkok Data Analysis – Capstone Project
📌 Project Overview

This project is a data analysis capstone project focused on Airbnb listings in Bangkok.
The goal is to understand the factors influencing availability, pricing, reviews, and profitability of Airbnb properties, and to provide actionable business recommendations.

🎯 Objectives

Explore and clean Airbnb Bangkok dataset

Perform exploratory data analysis (EDA) and visualization

Identify correlations between property characteristics and profitability

Provide business insights and recommendations for Airbnb hosts and stakeholders

🛠️ Tools & Libraries

Python 3

Pandas, NumPy – data manipulation

Matplotlib, Seaborn – data visualization

Scikit-learn / Statsmodels – statistical analysis & correlation testing

Jupyter Notebook

📊 Key Insights
Room Type

Entire home/apt has the highest quantity and demand

Price variability is very high → requires better pricing standardization

Highest estimated profit comes from entire home/apt

Neighbourhoods

Vadhana, Huai Khwan, and Khlong Toei show high profitability but inconsistent pricing

Sampanthawong shows potential: frequent bookings, competitive pricing, and solid profit estimation

Price & Minimum Nights

Most properties priced between 700–1,600 Baht

Budget-friendly customers: 700–1,000 Baht

Premium customers: 1,000–1,600 Baht

Average minimum stay: 6 nights, most common at 1 night

Reviews

Properties with more reviews attract more bookings

Khlong Toei has the most reviewed properties

📈 Statistical Findings

Chi-Square Tests show strong associations between price variability and availability

Correlation Analysis:

Price ↔ Profit: strong positive correlation (0.76)

Reviews ↔ Profit: moderate positive correlation (0.57)

Location (lat/long) has weak correlation with availability

💡 Business Recommendations

Dynamic Pricing: Adjust based on seasonal demand and neighbourhood competition

Minimum Nights Optimization: Lower thresholds can increase booking rates

Review Management: Encourage reviews to boost visibility and bookings

Neighbourhood Focus:

Vadhana, Huai Khwan, Khlong Toei → monitor and optimize pricing

Sampanthawong → opportunity for growth

📂 Project Structure
CAPSTONE 2.ipynb   # Jupyter Notebook with full analysis
data/              # (if included) dataset files

🚀 How to Run

Clone the repository

git clone https://github.com/username/airbnb-bangkok-analysis.git
cd airbnb-bangkok-analysis


Install dependencies

pip install -r requirements.txt


Open Jupyter Notebook

jupyter notebook CAPSTONE\ 2.ipynb

📌 Impact

Provides data-driven recommendations for Airbnb hosts in Bangkok

Identifies profitable segments (room types, neighbourhoods, price ranges)

Supports decision-making on pricing, reviews, and availability optimization
