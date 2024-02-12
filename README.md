# 
**Project Title: Online Retail Store Customer Segmentation By Country**

**Overview:**
The "Online Retail Store Customer Segmentation By Country" project aims to analyze and segment customers of an online retail store based on their purchasing behaviour, specifically focusing on customers from the United Kingdom. The dataset includes features such as InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country. By leveraging recency, frequency, and monetary value metrics, customer segmentation provides valuable insights for targeted marketing and personalized customer engagement.

**Key Features:**

1. **Data Preprocessing:**
   - The dataset is initially explored to understand its structure and contents.
   - Given that more than 90% of customers are from the United Kingdom, the analysis is focused on this specific geography.

2. **RFM Analysis:**
   - Recency, Frequency, and Monetary (RFM) analysis is employed to evaluate customer behaviour.
   - Recency: Measures the time since the last purchase by each customer.
   - Frequency: Represents the number of transactions made by each customer.
   - Monetary Value: Reflects the total monetary value of purchases made by each customer.

3. **Customer Segmentation:**
   - Customers are segmented based on their recency, frequency, and monetary value metrics.
   - The segmentation results are presented as recency quartile, frequency quartile, and monetary value quartile.
   - For example, CustomerID 12346 is assigned recency quartile 4, frequency quartile 4, and monetary value quartile 1.

4. **Interpretation and Examples:**
   - Examples of customer segments are provided, showcasing the recency, frequency, and monetary value metrics.
   - CustomerID 12747 is highlighted with a recency of 2 days, frequency of 103, and monetary value of $4196.01.
   - CustomerID 12346 stands out with a single purchase but a substantial monetary value of $77183.60.

5. **Segmentation Visualization:**
   - Visualizations such as scatter plots or heatmaps may be utilized to visually represent the different customer segments.
   - These visualizations can provide a clear understanding of how customers are distributed across recency, frequency, and monetary value quartiles.

6. **Business Implications:**
   - The project emphasizes the practical implications of customer segmentation, offering insights into customer behaviour and preferences.
   - Marketing strategies, product recommendations, and communication approaches can be tailored based on the identified customer segments.

**Customer Examples:**
```
recency   frequency   monetary_value   r_quartile   f_quartile   m_quartile
CustomerID
12346.0    325           1              77183.60         4            4             1
12747.0      2            103            4196.01           1            1             1
12748.0      0            4596         33719.73         1            1             1
12749.0      3            199           4090.88           1            1             1
12820.0      3            59             942.34           1            2             2
```

The "Online Retail Store Customer Segmentation By Country" project serves as a valuable tool for understanding and categorizing customers based on their purchasing behaviour. By employing RFM analysis and visualizing customer segments, the project equips the retail store with actionable insights for targeted marketing campaigns, customer retention strategies, and personalized customer experiences. The segmentation results provide a foundation for data-driven decision-making in enhancing customer satisfaction and maximizing business value.
