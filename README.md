# Advertisement Campaign Analysis

The goal of the research is campaign efficiency evaluation. To achieve this goal we will explore the provided datasets, identify patterns in how socio-demographics influence media consumption, build a predictive model to understand drivers of purchases, and present actionable insights.

Datasets information:
* **Dataset socio_demos** – socio demographics for each individual from the sample. There is also a weight column representing each individual's share of the total population for the country.
* **Dataset media_contacts** – number of times each individual in the sample was exposed to the advertisement on various media channels. There is also a column indicating if the individual has purchased the advertised product.

Each individual row in the dataset represents a large group of people so we need to try and preserve as much data as possible.

### Conversion Rate Analysis
* Overall CR: 5.11%.
* Top-Performing Channels: Flyers (13.50%), Print (9.20%), and TikTok (5.98%).
* Channels like YouTube and Online were never used as standalone sources, making it impossible to evaluate their individual CR.

### Media Channel Popularity
* TV is the dominant channel, accounting for 63% of all interactions.
* The second most popular channel is print, contributing 7.78% of interactions.
* TikTok, despite having a relatively high conversion rate, is the least utilized channel, representing only 0.47% of all interactions.

### Demographic Insights
* Age groups show varying preferences for media channels, highlighting the need for targeted strategies.
* Although the 51-60 age group generates the most interactions, the odds of purchase decrease by ~3.48% for each additional year of age.

### Customer Profiles
* Organic Customers: Primarily women (65.3%), aged 17-40, without children.
* Acquired Customers: Predominantly men (55.5%), mid-to-elder aged, showing higher purchase likelihood post-advertisement.

### Machine Learning Model
We developed a logistic regression model to predict purchase likelihood. Its simplicity and interpretability make it suitable for business applications.

**Performance:**
* F1 Score = 0.73
* Precision = 0.63
* Recall = 0.86

**Key Findings:**
* Male customers have a higher conversion likelihood.
* TV interactions significantly increase purchase odds (+36.06%).
* Older age correlates with lower purchase likelihood.
  
## KEY POINTS
🚀 Leverage Flyers: High CR (13.50%), especially effective for the 71+ age group. <br>
🚀 Utilize TikTok: High CR (5.98%) but underused (0.47% of interactions). <br>
🚀 Prioritize TV: Dominates interactions (63%) and boosts purchase odds by 36.06%. <br>
🚀 Focus on Male Customers: Data and model indicate higher conversion likelihood for men. <br>
