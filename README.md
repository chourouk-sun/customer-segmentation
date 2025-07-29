# customer-segmentation
# dataset link : 
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python 
# Description: 
This analysis aims to segment customers based on their Age, Annual Income, and Spending Score to better understand customer behavior and identify targeted marketing strategies for each customers groups. We used K-Means clustering combined with PCA for dimensionality reduction et we also applied heirarchicale .
# Describe the Methodology Briefly : 
The data was first cleaned normalized and then i did a short visualization of the data, and PCA was applied to reduce dimensionality while preserving variance. K-Means clustering was then performed to segment the customers. After evaluating different values of k, we chose 6 clusters based on the elbow method.
# Summarize Each Segment : 
![Alt text](relative/path/to/image.png)
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
- Interpretation : These are older, moderate-income, average-spending customers.
- Label : Mature Budget-Conscious

 📌 cluster 0 :
- Age : ~40 to 70+ / mean = 56.3
- Spending Score : Medium (mostly around 40–60) / average= 49 
- Income : medium ( ~40k to 80k) /  mean= 49k moderate 
- Number of customer : 45 / 22%
- Gender : 58% female & 42% male 
- Interpretation : These are older, moderate-income, average-spending customers.
- Label : Mature Budget-Conscious

   📌 cluster 0 :
- Age : ~40 to 70+ / mean = 56.3
- Spending Score : Medium (mostly around 40–60) / average= 49 
- Income : medium ( ~40k to 80k) /  mean= 49k moderate 
- Number of customer : 45 / 22%
- Gender : 58% female & 42% male 
- Interpretation : These are older, moderate-income, average-spending customers.
- Label : Mature Budget-Conscious

   📌 cluster 0 :
- Age : ~40 to 70+ / mean = 56.3
- Spending Score : Medium (mostly around 40–60) / average= 49 
- Income : medium ( ~40k to 80k) /  mean= 49k moderate 
- Number of customer : 45 / 22%
- Gender : 58% female & 42% male 
- Interpretation : These are older, moderate-income, average-spending customers.
- Label : Mature Budget-Conscioun

   📌 cluster 0 :
- Age : ~40 to 70+ / mean = 56.3
- Spending Score : Medium (mostly around 40–60) / average= 49 
- Income : medium ( ~40k to 80k) /  mean= 49k moderate 
- Number of customer : 45 / 22%
- Gender : 58% female & 42% male 
- Interpretation : These are older, moderate-income, average-spending customers.
- Label : Mature Budget-Conscious

   📌 cluster 0 :
- Age : ~40 to 70+ / mean = 56.3
- Spending Score : Medium (mostly around 40–60) / average= 49 
- Income : medium ( ~40k to 80k) /  mean= 49k moderate 
- Number of customer : 45 / 22%
- Gender : 58% female & 42% male 
- Interpretation : These are older, moderate-income, average-spending customers.
- Label : Mature Budget-Conscious
# General Insights & Observations :
Cluster 0 :
📌 Interpretation: Older customers with average spending & moderate income. Possibly loyal but not impulsive buyers.
Potential Profile: Possibly retired or near retirement, stable income
Represents

Cluster 1 :
📌 Interpretation: Mid age/ yong and high-spending customers with high income. Ideal for premium offers, exclusive memberships, or new product launches.
Income: Potential Profile: High-earning professionals or entrepreneurs

Cluster 2 :
📌 Interpretation: Also young high-spenders & low income , similar to Cluster 1. Good targets for social media campaigns and limited-time deals.
Income: Potential Profile: Students or early-career professionals

Cluster 3 :
📌 Interpretation: Mixed-age group ( Young to mid-age people) with moderate or unpredictable spending &  moderate income. Might respond to discounts, loyalty programs, or budget options.
Potential Profile: Early to mid-career professionals

Cluster 4 :
📌 Interpretation: Middle-aged or older low spenders & high income . Possibly price-sensitive or infrequent buyers. Might not be the best marketing priority. Older professionals
Potential Profile: Experienced professionals or executives

Cluster 5 :
📌 Interpretation: Mixed age group with low income Low-value segment. Likely not worth targeting heavily.
Potential Profile: Budget-conscious or underserved market segment

# Summary for Business Decision-Making:
🟢 Target Segments (Cluster 1 & 2):
Young adults aged 20–35 with very high spending scores. These are the premium audience. Focus your marketing, new products, offers, and loyalty programs on them.
1/ Target with premium services/products, luxury brands, or high-end financial services. Personalization matters.
2/Promote entry-level offers, student discounts, or installment payment plans. Use social media targeting.

🟠 Medium Opportunity Segment (Cluster 0): Customers aged 40–70 with average spending. They may be loyal and responsive to special offers, discounts, or personalized service.
0/Offer retirement savings plans, travel packages, and health-related products. Emphasize stability and trust.

🔴 Low Priority Segments (Cluster 4 & 5): Customers aged 30–55+ with consistently low spending. These are not ideal for high-cost marketing; you may exclude them from premium campaigns or keep communication minimal.
🟣 Mixed Segment (Cluster 3): A diverse group with variable spending habits. May be worth A/B testing or segmenting further by gender, profession, or location to find smaller actionable subgroups.

#
#
