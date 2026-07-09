<div align="center">

# Yash Raj

### B.Tech · Mathematics & Scientific Computing

<p align="center">
  <a href="https://www.linkedin.com/in/yash-raj-49xe">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://x.com/Yash_49_Xe">
    <img src="https://img.shields.io/badge/Twitter-000000?style=flat&logo=x&logoColor=white" alt="Twitter"/>
  </a>
  <a href="mailto:yashraj4009.xe@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://Yash49-Xe.github.io">
    <img src="https://img.shields.io/badge/Portfolio-6366f1?style=flat&logo=githubpages&logoColor=white" alt="Portfolio"/>
  </a>
</p>

</div>

<br/>

## About

I'm a Mathematics & Scientific Computing student focused on data science and backend engineering. My work centers on building data pipelines, designing REST APIs, and applying statistical methods to extract insight from real-world datasets — with a mathematical background that shapes how I think about model design, data quality, and performance trade-offs.

Currently moving from descriptive analysis toward predictive systems — deepening my work in machine learning and building models that forecast and classify rather than just describe.

<br/>

## Technical Skills

<table>
<tr>
<td valign="top" width="33%">

**Data Science & Analytics**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</td>
<td valign="top" width="33%">

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Uvicorn](https://img.shields.io/badge/Uvicorn-499848?style=flat-square&logo=gunicorn&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

</td>
<td valign="top" width="33%">

**DSA & Tools**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

</td>
</tr>
</table>

<br/>

## Projects

<table>
<tr>
<td width="50%" valign="top">

<h3>Automated Wealth & Portfolio Optimization API</h3>

An asynchronous backend microservice that ingests live market data and computes the mathematically optimal capital allocation across a multi-asset portfolio. An `asyncio` background worker syncs EOD closing prices and the live 10-year US Treasury rate from the **FMP API** into a local SQLite database on a 24-hour cycle, fully decoupling data ingestion from request handling. **SciPy's** SLSQP algorithm minimizes the negative Sharpe Ratio over the Efficient Frontier to produce optimal portfolio weights.

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)

<br/><br/>

**[View Repository →](https://github.com/Yash49-Xe/portfolio-optimization-api)**

</td>
<td width="50%" valign="top">

<h3>Dynamic Pricing Optimization Engine</h3>

A high-performance microservice that computes the mathematically optimal price for products to maximize profit. Uses **SciPy's** `minimize` algorithm to locate the exact peak of a profit parabola, balancing base costs, dynamic demand multipliers, and competitor pricing. **PyArrow** loads a compressed Parquet database directly into RAM on boot, eliminating disk I/O and enabling Pandas Boolean indexing across 100,000+ products in milliseconds.

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![PyArrow](https://img.shields.io/badge/PyArrow-41499D?style=flat-square&logo=apache&logoColor=white)

<br/><br/>

**[View Repository →](https://github.com/Yash49-Xe/dynamic-pricing-engine)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>E-Commerce Customer RFM Segmentation API</h3>

An end-to-end data science pipeline and REST API for customer segmentation. Processes 100,000+ real-world e-commerce transactions to compute **Recency, Frequency, and Monetary** scores and classify customers into actionable business segments in real time.

A key EDA finding — over 95% of customers had made only a single purchase — required custom scoring functions outside standard quantile methods to meaningfully isolate high-value segments from the broader one-time buyer pool.

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square&logo=python&logoColor=white)

<br/><br/>

**[View Repository →](https://github.com/Yash49-Xe/ecommerce-rfm-api)**

</td>
<td width="50%" valign="top">

<h3>More on the way</h3>

Currently building out additional projects in machine learning and applied statistics. New work gets pushed regularly — the full, up-to-date list always lives on my portfolio site.

<br/><br/>

**[Visit Portfolio →](https://Yash49-Xe.github.io)**

</td>
</tr>
</table>

<br/>


## Currently Learning

| Area | Focus |
|---|---|
| **SQL** | Query optimization and large-scale structured datasets |
| **Scikit-Learn** | Supervised and unsupervised learning pipelines |
| **ML Fundamentals** | Regression, classification, and clustering — with emphasis on underlying mathematics |
| **Pipeline Optimization** | Applying scientific computing principles to data processing efficiency |

<br/>

## GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Yash49-Xe&theme=tokyonight" height="165"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Yash49-Xe&theme=tokyonight" height="165"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Yash49-Xe&theme=tokyonight&hide_border=true" height="150"/>
</p>

### Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Yash49-Xe&bg_color=0d1117&color=6366f1&line=6366f1&point=ffffff&area=true&hide_border=true&theme=tokyo-night" />
</p>

<br/>

## Contact

- **LinkedIn:** [linkedin.com/in/yash-raj-49xe](https://www.linkedin.com/in/yash-raj-49xe)
- **Twitter / X:** [@Yash_49_Xe](https://x.com/Yash_49_Xe)
- **LeetCode:** [leetcode.com/u/Yash_xe--49](https://leetcode.com/u/Yash_xe--49)
- **Email:** yashraj4009.xe@gmail.com

---
<br/>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Yash49-Xe&style=flat-square&color=6366f1" alt="Profile views"/>
</p>
