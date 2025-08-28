# Google Play Store App Analytics Project

An end-to-end data analysis case study focused on the Google Play Store mobile app market, providing comprehensive insights into user behavior, app ratings, and market trends to deliver actionable business recommendations.

## Table of Contents
- [Project Overview](#project-overview)
- [Key Research Questions](#key-research-questions)
- [Findings & Insights](#findings--insights)
- [Actionable Recommendations](#actionable-recommendations)
- [Technical Implementation](#technical-implementation)
- [Project Files](#project-files)
- [Live Dashboard](#live-dashboard)
- [Skills](#skills)
- [Usage](#usage)

## Project Overview

This project represents a case study analyzing the Google Play Store ecosystem. The analysis combines statistical testing, exploratory data analysis, sentiment analysis, and interactive visualization to uncover meaningful patterns in mobile app market dynamics.

### Objectives
- Analyze user behavior patterns across different app categories
- Investigate relationships between app ratings, installs, and pricing models
- Perform sentiment analysis on user reviews
- Provide data driven business recommendations
- Create interactive dashboards for stakeholder consumption

## Key Research Questions

### 1. Market Saturation Analysis
 What are the most saturated app categories?

### 2. Rating vs. Install 
 Is there a correlation between an app's rating and its number of installs?

### 3. Paid vs. Free App Performance
 Do paid apps have different ratings compared to free apps?

### 4. Sentiment Impact Analysis
 Does user sentiment in reviews impact an app's rating?

## Findings & Insights

### Market Saturation
- FAMILY and GAME categories emerged as the most populated categories
- These categories represent highly competitive markets with  barriers to entry
- New app developers should consider these saturation levels when choosing target categories

### Rating vs. Install 
- No clear correlation found between app ratings and number of installs
- This counterintuitive finding suggests that **product quality alone doesn't drive success**
- High quality apps may struggle without proper marketing strategy

### Paid vs. Free App Analysis
- **Statistical significance confirmed** through two sample t-test (p-value: 0.000)
- Paid apps demonstrate higher average ratings than free apps
- This suggests higher user satisfaction with premium products
- Users who invest money in apps may have higher engagement 

### Sentiment Analysis Results
- **Strong positive correlation** identified between review sentiment and app ratings
- Positive user reviews directly correlate with higher overall app ratings
- This shows the importance of user experience and customer satisfaction
- Review sentiment serves as a leading indicator of app success

## Actionable Recommendations

### Monetization Strategy
**Recommendation**: Explore premium paid versions for high performing free apps

**Rationale**: 
- Statistical evidence shows paid apps achieve higher user satisfaction ratings
- Converting successful free apps to premium models could increase both revenue and user satisfaction
- Consider freemium models to capture both market segments

**Rationale**:
- Strong correlation between sentiment and ratings validates review importance
- Proactive review management can improve app ratings and user loyalty
- Addressing negative feedback quickly can prevent rating deterioration
- Positive review encouragement can amplify success

## Technical Implementation

### Data Processing 
- **Data Cleaning**: Preprocessing of raw Google Play Store data
- **Statistical Analysis**: Formal hypothesis testing using scipy
- **Sentiment Analysis**: Natural language processing using TextBlob
- **Visualization**: Interactive dashboard creation using Tableau

### Analytics Techniques
- **Exploratory Data Analysis (EDA)**: Pattern discovery and data understanding
- **Statistical Hypothesis Testing**: Two sample t-tests for rating comparisons
- **Correlation Analysis**: Relationship identification between variables
- **Sentiment Analysis**: Text mining and opinion extraction from reviews

## Project Files

| File | Description |
|------|-------------|
| `Google_Play_Store_Analysis.ipynb` | Main Jupyter Notebook containing all Python analysis code |
| `final_dataset.csv` | Cleaned dataset used for visualization |
| `googleplaystore.csv` | Original dataset of app information |
| `googleplaystore_user_reviews.csv` | Original dataset of user reviews |

## Live Dashboard

**Interactive Tableau Dashboard**: [View Live Dashboard](https://public.tableau.com/app/profile/shritin.shetty/viz/GooglePlayStoreAppAnalytics_17563512386840/Dashboard2?publish=yes)

The dashboard provides:
- Interactive filtering by app category and rating
- Visual correlation analysis between key metrics
- Sentiment distribution visualizations

## Technology 

### Programming & Analysis
- **Python**: Advanced data manipulation and analysis
  - `Pandas`: Data cleaning and transformation
  - `Matplotlib` & `Seaborn`: Statistical visualization
  - `Scipy`: Statistical hypothesis testing
  - `TextBlob`: Natural language processing and sentiment analysis

### Database & Data Management
- **SQL Concepts**: Advanced data aggregation and joining operations through Pandas
- **Data Pipeline Management**: End-to-end data processing workflows

### Statistical Analysis
- **Hypothesis Testing**: Formal statistical validation of findings
- **Correlation Analysis**: Relationship identification and quantification
- **Descriptive Statistics**: Comprehensive data summarization

### Data Visualization
- **Tableau**: Interactive dashboard development
- **Statistical Plotting**: Advanced visualization for business insights

## Usage

### Running the Analysis
1. Clone the repository
2. Install required dependencies:
   ```python
   pip install pandas matplotlib seaborn scipy textblob jupyter
   ```
3. Open `Google_Play_Store_Analysis.ipynb` in Jupyter Notebook
4. Run all cells to reproduce the analysis

### Dashboard Access
- Access the live Tableau dashboard via the provided public link
- No Tableau installation required for viewing
- Interactive filtering and exploration available
--- 
**Project**: Google Play Store Data Analysis
