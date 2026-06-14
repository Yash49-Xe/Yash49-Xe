<h1 align="center">Yash Raj</h1>
<p align="center">
  B.Tech · Mathematics & Scientific Computing
</p>
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
</p>

---

## About

Mathematics & Scientific Computing student with a focus on data science and backend engineering. I work on building data pipelines, designing REST APIs, and applying statistical methods to extract insight from real-world datasets. My mathematical background shapes how I approach model design, data quality, and performance trade-offs.

Currently deepening my work in predictive analytics and machine learning — moving from descriptive analysis toward building systems that forecast and classify.

---

## Technical Skills

**Data Science & Analytics**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Uvicorn](https://img.shields.io/badge/Uvicorn-499848?style=flat&logo=gunicorn&logoColor=white)

**Data Structures & Algorithms**

![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white)

---

## Projects

### [Automated Wealth & Portfolio Optimization API](https://github.com/Yash49-Xe/portfolio-optimization-api)

An asynchronous backend microservice that ingests live market data and computes the mathematically optimal capital allocation across a multi-asset portfolio. An `asyncio` background worker syncs EOD closing prices and the live 10-year US Treasury rate from the **FMP API** into a local SQLite database on a 24-hour cycle, fully decoupling data ingestion from request handling. **SciPy's** SLSQP algorithm then minimizes the negative Sharpe Ratio over the Efficient Frontier to produce optimal portfolio weights.

`Python` · `FastAPI` · `SciPy` · `Pandas` · `NumPy` · `SQLite` · `httpx`

---

### [Dynamic Pricing Optimization Engine](https://github.com/Yash49-Xe/dynamic-pricing-engine)

A high-performance microservice that computes the mathematically optimal price for products to maximize profit. Uses **SciPy's** `minimize` algorithm to locate the exact peak of a profit parabola by balancing base costs, dynamic demand multipliers, and competitor pricing. **PyArrow** loads a compressed Parquet database directly into RAM on boot, eliminating disk I/O bottlenecks and enabling Pandas Boolean indexing across 100,000+ synthetic products in milliseconds.

`Python` · `FastAPI` · `SciPy` · `Pandas` · `PyArrow` · `NumPy`

---

### [E-Commerce Customer RFM Segmentation API](https://github.com/Yash49-Xe/ecommerce-rfm-api)

An end-to-end data science pipeline and REST API for customer segmentation. Processes 100,000+ real-world e-commerce transactions to compute **Recency, Frequency, and Monetary** scores and classify customers into actionable business segments in real time.

A key finding during EDA — over 95% of customers had made only a single purchase — required designing custom scoring functions outside standard quantile methods to meaningfully isolate high-value segments from the broader one-time buyer pool.

`Python` · `FastAPI` · `Pandas` · `Seaborn` · `RFM Analysis`

---

## Currently Learning

- **SQL** — query optimization and working with large-scale structured datasets
- **Scikit-Learn** — supervised and unsupervised learning pipelines
- **Machine learning fundamentals** — regression, classification, and clustering with emphasis on the underlying mathematics
- **Pipeline optimization** — applying scientific computing principles to improve data processing efficiency

---

## GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Yash49-Xe&hide_border=true" height="150"/>
</p>

---

## Contact

- **LinkedIn:** [linkedin.com/in/yash-raj-49xe](https://www.linkedin.com/in/yash-raj-49xe)
- **Twitter / X:** [@Yash_49_Xe](https://x.com/Yash_49_Xe)
- **LeetCode:** [leetcode.com/u/Yash_xe--49](https://leetcode.com/u/Yash_xe--49)
- **Email:** yashraj4009.xe@gmail.com

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Yash49-Xe&style=flat&color=6366f1" alt="Profile views"/>
</p>
