# Analyzing the Impact of Wealth and Population on Olympic Success using Python

_For a detailed look at the visualizations and insights from this project, you can check out my [blog](https://medium.com/@vpanh/from-medals-to-models-exploring-the-intersection-of-olympic-performance-and-economic-factors-4675f78c936b) on Medium._


<br />

## 1. Introduction

The Olympic Games capture the interest of millions, showcasing the best athletes from around the world. With the growing curiosity about what drives success at the Olympics, this project was started to explore how factors like GDP and population influence a country’s performance. By merging economic and demographic data with Olympic results, I hope to uncover patterns that explain which countries excel and why.

<br />


## 2. Objectives
This project aims to uncover key insights into the dynamics of Olympic success by addressing several important questions. Specifically, the project seeks to:

* Determine the number of medals awarded by year
* Identify the top 10 countries by medal count
* Explore medal distribution by sport
* Analyze the gender distribution of athletes over time
* Examine medal trends over time for selected countries
* Highlight the top 10 most successful athletes
* Investigate medal distribution by season
* Assess the average age of medalists by sport
* Conduct a comparison analysis with countries’ GDP: How does a country’s economic strength, as indicated by GDP, correlate with its success in winning Olympic medals? Are wealthier nations more likely to achieve higher medal counts?
* Develop predictive models using GDP and population to predict medals: Can we build accurate models to predict a country’s medal count based on its GDP and population? How do these factors influence Olympic success, and which model performs best in predicting outcomes?

By exploring these questions, this project aims to provide a comprehensive understanding of the factors that contribute to Olympic success, offering insights that could be valuable for athletes, coaches, policymakers, and sports analysts.


<br />


## 3. Data Documentation

### Data Selection

This project leverages four key datasets: Olympics, NOC Regions, GDP, and Population.

* **Olympics Dataset:** Contains detailed records of Olympic events, including the number of medals won by year and country. This dataset is crucial for analyzing trends in medal achievements across different countries and years (from 1896–2016).
* **NOC Regions Dataset:** Provides mappings of National Olympic Committee (NOC) codes to country names. This dataset is used to align and match NOC codes from the Olympics dataset to their corresponding country names for accurate analysis.
* **GDP Dataset:** Includes Gross Domestic Product (GDP) data for countries over various years (from 1960–2020). This dataset helps in understanding the relationship between a country’s economic performance and its Olympic success.
* **Population Dataset:** Contains historical population data for various countries. Given the missing data for some years, population estimates were calculated using average growth rates to fill in gaps and ensure continuity in the analysis.

### Data Ethics
All datasets used in this project are sourced from publicly available resources with either CC0: Public Domain or Attribution 4.0 International licenses. This ensures that the data can be utilized for research and analysis.


<br />


## 4. Project Steps

**1. Setting Up:** Import libraries

**2. Data Pre-Processing**

**3. Exploratory Data Analysis (EDA):**
   * Distribution of Medals by Year
   * Top Countries by Medal Count
   * Medal Distribution by Sport
   * Gender Distribution of Athletes
   * Medal Trends Over Time for Selected Countries
   * Most Successful Athletes
   * Medal Distribution by Season
   * Average Age of Medalists by Sport
   * Age Distribution of Medalists

**4. Comparative Analysis: Olympic Performance vs. GDP**

**5. Predictive Modeling**


<br />


## 5. Conclusion
This project provided several insights into medal trends and distribution, revealing key patterns in Olympic performance across different sports and countries.

* **Medal Distribution by Season:** The Summer Olympics consistently sees a higher number of medals awarded compared to the Winter Olympics, reflecting the broader range of sports and events.
* **Medal Trends Over Time:** Significant trends were observed in medal counts over the years, with fluctuations tied to different countries’ focus on sports and their changing strategies.
* **Age Distribution of Medalists:** Medalists’ ages vary, with a notable concentration of medals awarded to athletes in their late 20s to early 30s, suggesting a peak performance age in sports.
* **Medal Distribution by Sport:** Analysis shows that certain sports like Athletics, Swimming, and Gymnastics dominate the medal distribution. This possibly suggests a greater global participation in these sports.
* **Economic Influences:** This project also demonstrated that GDP is a more influential predictor of Olympic success compared to population size. This suggests that higher GDP is a better indicator of a country’s ability to achieve medals, reflecting the critical role that economic resources play in supporting and developing athletic programs and infrastructure.

### Project Limitations
* **Population Data Estimates:** Missing population data for certain years required estimation using average growth rates, which may affect the results of analyses involving population.
* **Feature Limitations:** The project was limited by the availability of additional relevant features that could further refine the predictive models.

### Project Extension Ideas
Potential ideas that can be considered to expand this project:

* **Incorporate Additional Data Sources:** Explore additional datasets, such as detailed sports infrastructure or funding data, to potentially improve predictive models.
* **Refine Model Parameters:** Further optimize models by fine-tuning parameters and exploring more advanced techniques, such as ensemble methods or deep learning.
