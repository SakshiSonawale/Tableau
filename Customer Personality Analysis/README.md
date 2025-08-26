## Customer Personality Analysis – Tableau Dashboard


Customer Personality Analysis is a detailed analysis of a company’s ideal customers.  
It helps businesses better understand their customers and makes it easier to modify products according to the specific needs, behaviors, and concerns of different customer types.  

For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which segment is most likely to buy the product and market the product only to that segment.  

---

## Content

### People
- **ID**: Customer's unique identifier  
- **Year_Birth**: Customer's birth year  
- **Education**: Customer's education level  
- **Marital_Status**: Customer's marital status  
- **Income**: Customer's yearly household income  
- **Kidhome**: Number of children in customer's household  
- **Teenhome**: Number of teenagers in customer's household  
- **Dt_Customer**: Date of customer's enrollment with the company  
- **Recency**: Number of days since customer's last purchase  
- **Complain**: 1 if customer complained in the last 2 years, 0 otherwise  

### Products
- **MntWines**: Amount spent on wine in last 2 years  
- **MntFruits**: Amount spent on fruits in last 2 years  
- **MntMeatProducts**: Amount spent on meat in last 2 years  
- **MntFishProducts**: Amount spent on fish in last 2 years  
- **MntSweetProducts**: Amount spent on sweets in last 2 years  
- **MntGoldProds**: Amount spent on gold in last 2 years  

### Promotion
- **NumDealsPurchases**: Number of purchases made with a discount  
- **AcceptedCmp1**: 1 if customer accepted the offer in the 1st campaign, 0 otherwise  
- **AcceptedCmp2**: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise  
- **AcceptedCmp3**: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise  
- **AcceptedCmp4**: 1 if customer accepted the offer in the 4th campaign, 0 otherwise  
- **AcceptedCmp5**: 1 if customer accepted the offer in the 5th campaign, 0 otherwise  
- **Response**: 1 if customer accepted the offer in the last campaign, 0 otherwise  

### Place
- **NumWebPurchases**: Number of purchases made through the company’s website  
- **NumCatalogPurchases**: Number of purchases made using a catalogue  
- **NumStorePurchases**: Number of purchases made directly in stores  
- **NumWebVisitsMonth**: Number of visits to company’s website in the last month  

---

## Target
The goal is to **perform clustering to summarize customer segments**.  

# 📝 Report – Customer Segmentation

Based on clustering analysis, customers were divided into **3 segments**:  
- **Cluster 1 → Highly Active Customers**  
- **Cluster 2 → Moderately Active Customers**  
- **Cluster 3 → Least Active Customers**  

---

## 🔹 Characteristics of Highly Active Customers (Cluster 1)
- **Education**: Mostly Postgraduate background  
- **Marital Status**: People in a relationship ≈ 2× single people  
- **Income**: Slightly lower than moderately active customers  
- **Kids**: More children compared to other clusters (avg. ~1 child)  
- **Expenses**: Spend on average **100–200 units**  
- **Age**: Range 25–75; most between 40–50 years  
- **Engagement**: Loyal, enrolled with company for longer period of time  

---

## 🔹 Characteristics of Moderately Active Customers (Cluster 2)
- **Education**: Mostly Postgraduate background  
- **Marital Status**: Slightly more in relationship than single  
- **Income**: Higher compared to other clusters  
- **Kids**: Fewer children (majority have none)  
- **Expenses**: Spend on average **500–2000 units**  
- **Age**: Range 25–75; most between 35–60 years  
- **Engagement**: Slightly less loyal compared to highly active customers  

---

## 🔹 Characteristics of Least Active Customers (Cluster 3)
- **Education**: Mostly Undergraduate background  
- **Marital Status**: Relationship ≈ Single (almost equal)  
- **Income**: Very low or negligible  
- **Kids**: Only a few have children  
- **Expenses**: Very low or negligible  
- **Age**: Range 15–30 years  
- **Engagement**: Not engaged with company for long duration  

---

### ⭐ If you found this project insightful, don’t forget to star the repo!
