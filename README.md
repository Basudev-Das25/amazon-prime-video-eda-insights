# Amazon Prime Video EDA Insights

## Overview

This project presents an exploratory data analysis of the Amazon Prime Video content dataset. The goal is to examine the structure of the platform’s catalog and identify meaningful patterns related to content type, genre distribution, ratings, release trends, and geographical production.

Rather than focusing only on visualization, the analysis emphasizes interpretation and business relevance. Each step of the analysis is designed to answer practical questions about how content is distributed and how a streaming platform might use this information to guide decisions.

---

## Objectives

- Understand the distribution of movies and TV shows on the platform  
- Identify the most common genres and audience ratings  
- Analyze trends in content production over time  
- Examine country-wise contribution to the content library  
- Explore relationships between variables such as type, rating, genre, and duration  
- Derive insights that can support content strategy and user engagement  

---

## Dataset

The dataset contains metadata of titles available on Amazon Prime Video. Key attributes include:

- Content type (Movie or TV Show)  
- Title and description  
- Director and cast  
- Country of production  
- Date added to the platform  
- Release year  
- Rating classification  
- Duration  
- Genre categories  

---

## Methodology

The analysis follows a structured approach:

1. Data loading and initial inspection  
2. Data cleaning and preprocessing  
   - Handling missing values  
   - Converting date formats  
   - Extracting useful features such as year added and numeric duration  
3. Exploratory analysis through visualization  
   - Univariate analysis to understand individual variables  
   - Bivariate analysis to study relationships between variables  
   - Multivariate analysis to uncover deeper patterns  
4. Interpretation of results with business context  

A total of 20 visualizations were created to ensure comprehensive coverage of the dataset.

---

## Key Findings

- The platform contains a higher proportion of movies compared to TV shows, although TV shows have grown significantly in recent years  
- Most content has been released after the year 2000, indicating a focus on relatively recent productions  
- Drama, Comedy, and Action are the most common genres across the platform  
- The majority of content is targeted toward mature audiences, with ratings such as TV-14 and TV-MA appearing frequently  
- The United States and India are the largest contributors to the content library  
- Content additions increased rapidly after the mid-2010s, reflecting the expansion of streaming services  
- TV shows show stronger growth trends, suggesting their importance in long-term user engagement  

---

## Business Insights

- Expanding the TV show catalog can improve user retention due to episodic engagement  
- Investing in high-performing genres can increase viewer satisfaction and watch time  
- Regional content production should be strengthened to capture diverse audiences  
- Rating distribution indicates an opportunity to balance content for different age groups  
- Data-driven content acquisition strategies can optimize platform growth  

---

## Tools and Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Project Structure

```
amazon-prime-video-eda-insights/
│
├── data/
│   └── amazon_prime_titles.csv
│
├── notebook/
│   └── eda_amazon_prime.ipynb
│
├── images/
│   └── visualizations (optional)
│
└── README.md
```

---

## How to Run

1. Clone the repository  
2. Install required libraries  
   ```
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the notebook using Jupyter  
4. Run all cells sequentially  

---

## Conclusion

This analysis highlights how structured exploration of content data can reveal actionable insights for streaming platforms. By understanding content distribution, audience targeting, and growth trends, platforms like Amazon Prime Video can refine their strategies to remain competitive and relevant.

---

## Author

Basudev Das  
BTech AIML Student  
