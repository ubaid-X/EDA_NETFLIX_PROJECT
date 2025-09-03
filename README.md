# Netflix Data Analysis

## Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on Netflix's content dataset containing approximately 9,827 rows. The analysis aims to uncover patterns, trends, and insights about Netflix's content library, including popularity metrics, genre distribution, release trends, and viewer engagement patterns.

## Dataset Information
- **Source**: [Netflix Dataset on GitHub](https://github.com/ubaid-X/EDA_NETFLIX_PROJECT/data/)
- **Size**: 9,827 rows
- **Features**:
  - Release_Date
  - Title
  - Overview
  - Popularity
  - Vote_Count
  - Vote_Average
  - Original_Language
  - Genre
  - Poster_Url

## Objectives
1. Perform comprehensive data cleaning and preprocessing
2. Handle missing values and outliers
3. Analyze content distribution across genres and years
4. Investigate popularity patterns and voting trends
5. Answer key business questions through visualizations

## Technical Stack
- **Python Version**: 3.13.2
- **Libraries Used**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Plotly

## Key Steps

### Data Preprocessing
1. Removed unnecessary columns ('Overview', 'Poster_Url')
2. Converted Release_Date to datetime format and extracted year
3. Handled missing values (1.02% in Vote_Average)
4. Categorized Vote_Average into popularity levels:
   - Popular
   - Average
   - Below_Avg
   - Not_Popular
5. Split and exploded Genre column for better analysis
6. Converted Genre to categorical data type

### Key Insights

#### 1. Genre Distribution
Drama is the most frequent genre (3,715 entries), followed by:
- Comedy (3,006)
- Action (2,652)
- Thriller (2,473)
- Adventure (1,829)

#### 2. Popularity Patterns
- Most content falls in the medium popularity range
- Some outliers exist with exceptionally high popularity scores
- Popularity and vote counts show positive correlation

#### 3. Temporal Trends
Content release frequency has increased significantly in recent years, with 2021 being the year with most releases.

## 📈 Visualizations
The analysis includes various visualizations:
- Box plots for outlier detection
- Scatter plots showing popularity vs vote count relationships
- Bar charts for genre distribution
- Temporal trends analysis


## 📋 Future Work
- Implement machine learning models for popularity prediction
- Add sentiment analysis on overview text
- Incorporate additional data sources for richer insights
- Create interactive dashboard for real-time analysis

##  Author

- __Author name:__ UBAIDULLAH

- __Email:__ [ai.bussiness.student0@gmail.com](mailto:ai.bussiness.student0@gmail.com)

- __GitHub:__ [github.com/ubaid-X/](https://github.com/ubaid-X/)

- __LinkedIn Profile:__ [linkedin.com/in/ubaid-ullah-634563373/](https://www.linkedin.com/in/ubaid-ullah-634563373/)

- __Kaggle:__ [kaggle.com/ubaidullah01](https://www.kaggle.com/ubaidullah01)

---
*This analysis provides valuable insights for content strategists and data enthusiasts interested in streaming media trends and patterns.*
