# Final-Project

## Washington State Democratic Turnout ML Project

**Author:** Isaac Stiepleman  
**Date:** 2025-05-10  

### Project Summary  
I use county-level demographic and electoral data to cluster Washington counties, reduce dimensionality via PCA, and predict Democratic vote share. This helps the Washington State Democratic Party prioritize outreach by identifying high-potential turnout areas.

### Problem & Audience  
- **Problem:** Analyze which counties delivered strong Democratic turnout by ethnicity in 2024
- **Audience:** Field organizers and data team for the Washington State Democratic Party


Washington State Democratic Turnout: Machine Learning Analysis

Abstract
This project analyzes county-level demographic and electoral data from Washington State to predict Democratic vote share. Using K-means clustering, Principal Component Analysis (PCA), and regression modeling, I demonstrate that demographic age distributions significantly inform electoral outcomes. The PCA-based regression model achieved an in-sample R^2 of approximately 0.85 and a cross-validated R^2 of about 0.49, clearly outperforming a simple mean predictor baseline.

This analysis demonstrates that demographic features, especially age-group proportions, substantially inform predictions of Democratic vote share across Washington counties. Utilizing unsupervised clustering, PCA, and supervised regression modeling, I have provided actionable insights for campaign resource allocation. While highly predictive, further refinements through finer geographic data and additional voter-level information could result in even greater precision and impact.

