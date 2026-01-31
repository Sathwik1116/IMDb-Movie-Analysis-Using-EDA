# IMDb-Movie-Analysis-Using-EDA
IMDb movie analysis using Web Scraping, EDA, and Hypothesis Testing

## Problem Statement
The movie production industry involves high financial risk, where producers must make critical decisions related to genre selection, runtime, and creative direction without guaranteed success. Despite the availability of large-scale audience feedback on platforms like IMDb, many production decisions are still driven by intuition, trends, or past experience rather than data.

Movies with high IMDb ratings do not always achieve high popularity, while some highly popular movies receive only average ratings. This creates uncertainty in understanding what truly drives movie success. There is a lack of clear, data-driven insights on how factors such as genre, runtime, popularity, and director–genre alignment influence audience acceptance.

This project aims to analyze IMDb movie data using web scraping, exploratory data analysis (EDA), and hypothesis testing to uncover audience preference patterns and provide actionable insights that can support safer and more informed movie production decisions.

---

## Project Objectives
- Scrape IMDb movie data using web scraping techniques  
- Create a structured dataset with ratings, votes, genre, runtime, and release year  
- Perform data cleaning and preprocessing  
- Conduct univariate, bivariate, and multivariate exploratory data analysis  
- Apply hypothesis testing to validate observed patterns  
- Provide data-driven insights and business recommendations for movie producers  

---

## Dataset Overview
- Source: IMDb  
- Size: ~2000 movies  
- Nature: Audience-driven data  

### Key Attributes
- **Movie Title:** Name of the movie  
- **Genre:** Category based on storyline or theme  
- **IMDb Rating:** Average audience rating indicating perceived quality  
- **Votes (Popularity):** Number of user votes representing audience reach  
- **Runtime (Minutes):** Duration of the movie  
- **Year of Release:** Release year of the movie  
- **Language:** Primary language of the movie  

---

##  Tools & Technologies
- **Python**
- **Selenium** – Web scraping
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **SciPy** – Hypothesis testing

---

##  Methodology
1. **Web Scraping:** IMDb movie data extracted using Selenium  
2. **Data Cleaning:** Handling missing values, duplicates, and inconsistent formats  
3. **Feature Engineering:** Runtime and popularity categorization, genre normalization  
4. **EDA:** Univariate, bivariate, and multivariate analysis  
5. **Hypothesis Testing:** Statistical validation using Chi-square and ANOVA  
6. **Insights & Recommendations:** Business-oriented conclusions  

---

##  Key Insights
- Most movies receive IMDb ratings between **6 and 8**, indicating average-to-good audience reception  
- **Very high popularity (blockbusters) is rare**  
- Popularity does **not always correspond to high ratings**  
- Audience response varies across runtime categories; ratings are **not linearly related** to runtime  
- Some genres consistently receive higher ratings, while others show greater variability  
- Genres differ significantly in audience reach and popularity  

---

##  Hypothesis Testing
- **Director vs Genre (Chi-square Test):** Director success varies across genres  
- **Runtime vs IMDb Rating (ANOVA):** Ratings differ significantly across runtime categories  
- **Genre vs IMDb Rating (ANOVA):** Audience ratings vary significantly across genres  

---

##  Business Recommendations
- Prioritize genres with **consistent audience ratings**, not just high popularity  
- Focus on runtime ranges that show **stable audience response**  
- Avoid relying solely on popularity metrics for decision-making  
- Medium-popularity films can still deliver **strong audience satisfaction**  
- Align directors with genres where they have demonstrated success  
- Well-crafted films with controlled scope offer a balanced **risk–reward profile**

---

##  Challenges Faced
- Dynamic IMDb webpage structure during scraping  
- Handling missing and inconsistent data  
- Highly skewed popularity distribution  
- Managing multi-genre movie classification  
- Choosing appropriate visualizations and statistical tests  

---

##  Conclusion
Movie success is influenced by a combination of genre selection, runtime stability, and content quality rather than popularity alone. Data-driven analysis of audience behavior can significantly reduce uncertainty and help producers make safer and more informed production decisions.

---

##  Project Files
- `EDA Project Final.pptx` – Final presentation  
- `IMDb_EDA.ipynb` – Complete analysis notebook  
- `imdb_2000_movies.csv` – Dataset  

---

## 👤 Author
Sathwik Reddy Muppa 

