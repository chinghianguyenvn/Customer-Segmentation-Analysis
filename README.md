# Customer Segmentation using K-means Clustering and PCA

👉 **Click here to view the full Interactive HTML Report:** [(https://github.com/chinghianguyenvn/Customer-Segmentation-Analysis/blob/main/Analysis_Customer_Segmentation.html)]

## 1. Research Question
How can companies effectively segment the e-commerce customers based on demographic profiles, purchasing power and lifestyle behaviors to tailor personalized marketing strategies?

## 2. Methodology
To answer the research question, this study employs an unsupervised Machine Learning approach. Specifically, **K-means Clustering** is utilized to segment the users, and **Principal Component Analysis (PCA)** is applied to evaluate and visualize these distinct segments in a 2D feature space. 

This quantitative method is chosen because it allows for the discovery of hidden behavioral patterns and personas within multivariate continuous data without pre-labeled outcomes. The underlying objective function for K-means is to minimize the within-cluster sum of squares (WCSS) to ensure cohesive and robust grouping.

## 3. 2D Customer Segmentation Map

![2D Customer Segmentation Map](pca_segmentation_map)

## 4. Findings & Implications

**1. Findings (Behavioral Insights):**
By using the K-means clustering algorithm, the study discovered four distinctive customer segments based on their behavioral and demographic profiles:
- **Wealthy Switchers (High Income - Low Loyalty):** Although this group of customers possesses the highest purchasing power (average income of approximately $157k), they exhibit the lowest brand loyalty score (2.4), suggesting a high propensity to switch brands if more attractive options emerge.
- **Young Loyal Advocates (Young Demographic - Brand Ambassadors):** While this group represents the youngest group (average age of 31.8), they display the highest brand loyalty (7.59). In addition, they also show a significant tendency for impulse buying, making them a core future customer base.
- **Senior Loyalists (Senior Demographic - Traditional Mainstays):** While they are the oldest demographic with an average age of 66.3, they maintain a high and stable level of brand loyalty (7.58), reflecting consistent consumption habits.
- **Budget-Conscious Explorers (Price-Sensitive Segment):** This group has the lowest average income ($52k) and limited brand loyalty. This means their purchasing decisions are primarily driven by economic factors, leading them to constantly seek cheaper alternatives.

**2. Implications (Strategic & Academic Contributions):**
To optimize Return on Investment (ROI), management should transition from mass marketing to targeted interventions for each specific cluster:
- **For Wealthy Switchers:** Rather than emphasizing on price, they should shift their focus to exclusive privileges (VIP clubs) and high-end personalized services to create "psychological switching costs" that deter them from moving to competitors.
- **For Young Loyal Advocates:** Capitalize on their high impulse buying behavior by optimizing the UI/UX for 1-click checkouts and deploying aggressive flash sale notifications via mobile channels in order to encourage them to make immediate purchase decisions.
- **For Senior Loyalists:** Prioritize accessibility and simplicity in the user interface (UI/UX) while maintaining high-quality traditional customer support to reinforce long-term trust.
- **For Budget-Conscious Explorers:** As this group of customers are price-sensitive, they should allocate the bulk of the promotional budget, discount coupons, and bundle deals to this segment, as price is the primary driver for conversion here.
