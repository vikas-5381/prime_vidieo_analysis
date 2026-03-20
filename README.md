# 🧾 Prime Vidieo Analysis
_A dashboard is a visual representation of data that displays key metrics, charts, and summaries in one place.
It helps users monitor performance, track important trends, and make informed decisions quickly and efficiently._

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

The project focuses on analyzing data to uncover meaningful insights and trends that support bussiness decision making.It involves data cleaning,transformation and visualization through an interactive dashboard.The final output provides clear performance metrics and actionable insights for better strategic planning.

---

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

- 1.Lack of Performance Visibility – Provides real-time tracking of key KPIs and overall business performance.
- 2.Difficulty in Identifying Trends – Visual charts help detect sales patterns, growth trends, and seasonal changes.
- 3.Poor Decision-Making Due to Raw Data – Converts complex data into clear visual insights for faster decisions.
- 4.Revenue & Profit Tracking Issues – Monitors revenue, profit margins, and cost performance efficiently.
- 5.Inefficient Reporting Process – Automates reporting and reduces manual work with interactive filters and summaries.

---

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- 1.The dataset contains structured records including key fields such as date, category, revenue/sales, and performance metrics.
- 2.It includes multiple variables that help analyze trends, patterns, and business performance.
- 3.The data may come from different sources and is cleaned and transformed before analysis.
- 4.It is used to create visualizations and dashboards for generating actionable business insights.
  
---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Power Bi 
- Dax Function
- Charts & Graphs
- GitHub

---

<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
vrinda-store-analysis/
│
├── README.md
├── .gitignore
├── requirements.txt
├── Prime Vidieo Analysis.pdf
│
├── dashboard/                  # POWER BI File
│   └── sales_store_dashboard.pbi

```

<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

1.Removed Missing & Null Values - Handled blank fields in columns like rating, director, and release year.
2.Removed Duplicates – Eliminated duplicate movie/show records to ensure accurate analysis.
3.Standardized Data Formats – Converted date columns (release year, added date) into proper date format and corrected text inconsistencies.
4.Categorized Content Type – Separated Movies and TV Shows for better comparison and analysis.
5.Handled Outliers – Checked unusual values in duration, ratings, or year to maintain data accuracy.
6.Created New Columns – Extracted features like release year, genre count, or content age for deeper insights.


<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Negative or Zero Values Detected:**
- Some records contained zero or missing values in columns like duration or rating.
- These values were checked and corrected or removed to maintain data accuracy.
**Outliers Identified:**
- A few records had unusually high or low values compared to the overall dataset.
- These outliers were analyzed to ensure they did not affect the overall insights.
**Correlation Analysis:**
- Relationships between variables such as release year and number of titles were examined.
- The analysis helped identify patterns and trends within the dataset.


<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1.Which type of content is more available on the platform?
Insight: Movies are more common than TV shows in the dataset.
2.Which genre has the highest number of titles?
Insight: Drama and Comedy are among the most popular genres.
3.How has content production changed over the years?
Insight: The number of titles released has increased significantly in recent years.
4.Which countries produce the most content?
Insight: The United States contributes the highest number of titles.
5.What are the most common content ratings?
Insight: Ratings like 13+ and 16+ appear most frequently in the dataset.


<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

Power BI Dashboard Shows:
- Total Number of Movies and TV Shows
- Content Distribution by Gender
- Release Year Trends
- Country-wise Content Production
- Content Ratings Distribution
- Type of Content Comparison

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone the repository:
```bash
git clone https:[//github.com/yourusername/](https://github.com/vikas-5381/prime_vidieo_analysis)
```
3. Load the CSVs and ingest into database:
```bash
prime_vidieo_analysis.xlsx  
```
4. Create sales summary table:
```bash
power bi scripts/get_vidieo_summary.xlsx
```
5. Open Power Bi Dashboard:
 ```bash
   - `Prime video Dashboard.pbix`
```

---

<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- Focus on producing more content in popular genres like Drama and Comedy to attract a larger audience.
- Increase regional and international content to expand the global audience base.
- Regularly update the platform with new movies and TV shows to maintain user engagement.
- Use data insights to understand viewer preferences and improve content strategy.
- Monitor content ratings and trends to provide suitable recommendations for different audience groups.

---

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Vikas Siddheshware**  
Data Analyst      
📧 Email: vikassiddheshware2001@gmail.com 
🔗 [LinkedIn](www.linkedin.com/in/vikas-siddheshware) 
