# Customer-Segmentation
# Dataset Link : 
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python 
# Description: 
 This analysis aims to segment customers based on their Age, Annual Income, and Spending Score to better understand customer behavior and identify targeted marketing strategies for each customers groups. We used K-Means clustering combined with PCA for dimensionality reduction et we also applied heirarchicale .
# Describe the Methodology Briefly : 
The data was first cleaned normalized and then i did a short visualization of the data, and PCA was applied to reduce dimensionality while preserving variance. K-Means clustering was then performed to segment the customers. After evaluating different values of k, we chose 6 clusters based on the elbow method.
# Summarize Each Segment : 
![Alt text](relative/path/to/table.png)

![Alt text](images/table.png)


📌 cluster 0 :
- Age : ~40 to 70+ / mean = 56.3
- Spending Score : Medium (mostly around 40–60) / average= 49 
- Income : medium ( ~40k to 80k) /  mean= 49k moderate 
- Number of customer : 45 / 22%
- Gender : 58% female & 42% male 
- Interpretation : These are older, moderate-income, average-spending customers.
- Label : Mature Budget-Conscious

 📌 cluster 1:
- Age : ~25 to 35 / mean = 32.7
- Spending Score : High (70–100) average = 83
- Income : ~70k to 140k hight 82.1%
- Number of customer : 19%  39 costomers
- Gender : 58% female & 42% male 
- Interpretation : These are young, wealthy, and high-spending individuals.
- Label : "Luxury Lovers" or "Affluent Spenders"

 📌 cluster 2 :
- Age : ~20 to 30 mean=25.6
- Spending Score : High (70–100) 76.2
- Income : ~15k to 45k ( low to med) 33k
- Number of customer : 12% 25 customers
- Gender : 58% female & 42% male  56%F
44M
- Interpretation : Young people with low income but high spending behavior — possibly students or early-career impulsive spenders.
- Label : "Aspirational Spenders" or "Young Spontaneous Buyers"

   📌 cluster 3 :
- Age : 18–40 ~20 to 40 26.1
- Spending Score :Low to medium (5–60) 44.4 moderate 
- Income : ~40k to 80k
44..4k
- Number of customer : 20% (40 customers)
- Gender : 60% female & 40% male 
- Interpretation : Young males, average income, average spending — balanced customers
- Label :Young Professionals" or "Stable Spenders"

   📌 cluster 4 :
- Age : ~30 to 55+
44
- Spending Score :Low (mostly 0–40)
- Income : ~70k to 130k

low = 17.9
17.9%

- Number of customer : 15% ( 30 customers)
- Gender : 47% female & 53% male 
- Interpretation : Older customers with very low income and low spending — likely price-sensitive.
- Label : "Low-Income Conservative" or "Thrifty Seniors"

   📌 cluster 5:
- Age : 30-65 , mean = 45.5  
- Spending Score : Very low (0–30) low=19.3
- Income : medium (~15k to 40k) , mean= 19.3k moderate 
- Number of customer : 10% (21 customer ) 
- Gender : 62% female & 38% male 
- Interpretation : Similar to Cluster 4 but slightly older and more male-dominated.
- Label :Older Low Spenders" or "Budget-Conscious Men"
- 
# General Insights & Observations :
Cluster 0 :
📌 Interpretation: Older customers with average spending & moderate income. Possibly loyal but not impulsive buyers.
Potential Profile: Possibly retired or near retirement, stable income
Represents

Cluster 1 :
📌 Interpretation: Mid age/ yong and high-spending customers with high income. Ideal for premium offers, exclusive memberships, or new product launches. Potential Profile: High-earning professionals or entrepreneurs

Cluster 2 :
📌 Interpretation: Also young high-spenders & low income , similar to Cluster 1. Good targets for social media campaigns and limited-time deals.Potential Profile: Students or early-career professionals

Cluster 3 :
📌 Interpretation: Mixed-age group ( Young to mid-age people) with moderate or unpredictable spending & moderate income. Might respond to discounts, loyalty programs, or budget options.
Potential Profile: Early to mid-career professionals

Cluster 4 :
📌 Interpretation: Middle-aged or older with low spenders & high income . Possibly price-sensitive or infrequent buyers. Might not be the best marketing priority. Potential Profile: Experienced professionals or executives

Cluster 5 :
📌 Interpretation: Mixed age group with low income Low-value segment. Likely not worth targeting heavily. Potential Profile: Budget-conscious or underserved market segment

# Summary for Business Decision-Making:
🟢 Target Segments (Cluster 1 & 2):
Young adults aged 20–35 with very high spending scores. These are the premium audience. Focus your marketing, new products, offers, and loyalty reward programs on them. Target them with premium services or products, luxury brands, or high-end financial services or personalization matters. Promote entry-level offers, student discounts, or installment payment plans. Use social media targeting.target customer in cluster 2 with discounts or installment plans — they spend despite low income.

🟠 Medium Opportunity Segment (Cluster 0): Customers aged 40–70 with average spending. They may be loyal and responsive to special offers, discounts, or personalized service. Offer retirement savings plans, travel packages, and health-related products. Emphasize stability and trust.

🔴 Low Priority Segments (Cluster 4 & 5): Customers aged 30–55+ with consistently low spending. These are not ideal for high-cost marketing; you may exclude them from premium campaigns or keep communication minimal.

🟣 Mixed Segment (Cluster 3): A diverse group with variable spending habits. May be worth A/B testing or segmenting further by gender, profession, or location to find smaller actionable subgroups.

# 📬 Communication : 
Use age-appropriate channels:
 -Social media for young groups.
 -Email/phone for older groups.

# 🧪 A/B Testing:
Test promotions tailored to each group, then analyze ROI. 
   - Cluster 1 & 2: Offer exclusive new products to retain high-spending young customers.
   - Cluster 0 & 3: Launch awareness campaigns and email follow-ups to encourage engagement.
   - Cluster 5 & 4: These are low-income, low-spending customers. Limit marketing budget here.

