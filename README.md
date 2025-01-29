# Market Segmentation for a Chain Restaurant Using Cluster Analysis

## Introduction
Market segmentation has been a crucial tool for improving business revenue and efficiency. By leveraging data on customer characteristics and behaviors, businesses can create homogeneous customer groups to implement targeted marketing strategies. This project uses cluster analysis to segment customers for a chain restaurant planning to open a new location.

## Literature Review
While traditional descriptive methods provide valuable data, they are often insufficient in revealing patterns between customer groups. Cluster analysis, a multivariate technique, has proven valuable for market segmentation. However, challenges remain, including subjective decisions during implementation and ensuring segment stability across datasets.
## Methodology
### Data Preparation
- Combined multiple occupation-related columns into a single column to reduce complexity.
- Standardized numerical values to a range of 0-1.
- Created a calculated variable: `Average Revenue = Average Order Size × Average Order Frequency`.

### Cluster Analysis
- Used hierarchical clustering to determine the optimal number of clusters.
- Implemented K-means clustering with five segments.

### Visualization
![Psychographic Dashboard](https://github.com/kartik981/Market-Segmentation-Project/blob/1da761ae09a17f44b58492fc59d4ae0c949ddcb2/Psychographic%20Dashboard.png)

## Results
### Cluster Profiles
1. **Cluster 1:** Practical, brand-loyal families.
2. **Cluster 2:** Quality-focused, social media-savvy customers.
3. **Cluster 3:** Trend-following, socially responsible consumers.
4. **Cluster 4:** Education-sector professionals valuing quality dining.
5. **Cluster 5:** Career-driven individuals prioritizing convenience.

### Targeting & Positioning
- **Cluster 1:** Family-oriented advertising, community involvement.
- **Cluster 2:** High-quality, trend-focused social media campaigns.
- **Optimal Store Location:** High customer density areas like Washington or Philadelphia.

## Conclusion
Cluster analysis aids in identifying meaningful customer segments for targeted marketing. Limitations include data overlap and variable selection biases. Future research should enhance segment stability across different datasets.

## References
- Kotler, P., & Keller, K. L. (1983). *Principles of Marketing.*
- Dolnicar, S. (2002). *Market segmentation in tourism.*
- Wedel, M., & Kamakura, W. (2000). *Market Segmentation: Conceptual and Methodological Foundations.*
