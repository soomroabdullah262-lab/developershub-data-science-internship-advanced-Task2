# Customer Segmentation Using Unsupervised Learning

## Objective

The objective of this project is to group customers into meaningful segments based on purchasing behavior and demographics.

Customer segmentation helps businesses personalize marketing strategies and improve customer engagement.

---

## Dataset

**Mall Customers Dataset**

Features:

* Gender
* Age
* Annual Income
* Spending Score

No target variable (unsupervised learning problem).

---

## Approach

### 1. Exploratory Data Analysis

Visualized distributions and relationships between income and spending score to detect natural groupings.

### 2. Data Preprocessing

* Encoded categorical variables
* Standardized features for clustering

### 3. Clustering Algorithm

Applied **K-Means clustering**

Optimal number of clusters determined using:

* Elbow Method

### 4. Visualization

Used **PCA dimensionality reduction** to visualize customer segments in 2D space.

---

## Identified Customer Segments

| Segment Type              | Business Meaning  | Strategy               |
| ------------------------- | ----------------- | ---------------------- |
| High Income High Spending | Premium customers | Loyalty rewards        |
| High Income Low Spending  | Potential buyers  | Personalized offers    |
| Low Income High Spending  | Deal seekers      | Discounts              |
| Low Income Low Spending   | Low value group   | Minimal marketing      |
| Young Medium Income       | Trend buyers      | Social media campaigns |

---

## Results

Clustering successfully separated customers into five behavioral groups.

---

## Conclusion

Unsupervised learning provides actionable insights for targeted marketing and customer retention strategies.

---

## Repository Structure

* notebook.ipynb
* cluster_plots.png
* README.md
