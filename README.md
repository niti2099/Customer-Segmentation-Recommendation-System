# Customer-Segmentation-Recommendation-System
I developed a complete customer segmentation and recommendation system using transactional retail data in this project. Here’s a breakdown of key insights and outcomes:

**1. Data Cleaning & Transformation:**
   
 We began by cleaning the dataset — removing duplicates, handling missing values, and filtering out negative transactions. This ensured high data quality and reliability for downstream analysis.

**2. RFM Feature Engineering:**

Using Recency, Frequency, and Monetary metrics, we transformed raw transaction data into a customer-centric format. These features allowed us to quantify customer engagement, loyalty, and value.

**3. Data Preprocessing:**

We standardized the features to ensure equal weight during clustering and applied PCA to reduce dimensionality. This made clustering more efficient and interpretable while preserving core information.

**4. K-Means Clustering:**

We used the Elbow Method to identify the optimal number of clusters and performed customer segmentation using K-Means. The PCA-based visualization clearly illustrated distinct customer groups.

**5. Cluster Analysis:**

Each cluster revealed different customer behaviors:

Some were loyal, high-spending customers, Others were occasional or low-value buyers, And a few had recent but limited activity, representing potential growth segments.
This segmentation is invaluable for personalized marketing strategies.

**6. Recommendation System:**

Finally, we built a recommendation engine that suggests top-selling products in a customer’s cluster that they haven't purchased yet. This enhances upselling opportunities and drives customer engagement through targeted recommendations.
