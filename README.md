<!-- Banner: red to amber to gold gradient wave, matching sathvikkasoju.com -->
<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:ef4444,50:f59e0b,100:fbbf24&height=220&section=header&text=Sathvik%20Kasoju&fontColor=fff8e7&fontSize=52&desc=I%20build%20real%20time%20data%20systems%20at%20scale&descSize=18&descAlignY=60&fontAlignY=38)

<img src="assets/sathvik-fullbody.png" alt="Sathvik mascot in a straw hat, waving" width="190" />

`✦ Open to new adventures ✦`

[![Website](https://img.shields.io/badge/sathvikkasoju.com-0a1a2e?style=for-the-badge&logo=safari&logoColor=fbbf24)](https://sathvikkasoju.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a1a2e?style=for-the-badge&logo=linkedin&logoColor=4ecdc4)](https://linkedin.com/in/sathvikkasoju)
[![Email](https://img.shields.io/badge/Email-0a1a2e?style=for-the-badge&logo=gmail&logoColor=ef4444)](mailto:sathvikkasoju@gmail.com)

</div>

## ⚓ the captain

<table>
<tr>
<td width="210" valign="top" align="center">
<img src="assets/avatar-gold.png" alt="Sathvik avatar" width="180" />
</td>
<td valign="top">

Data Engineer with **4+ years** turning streams of messy, real world data into reliable systems that businesses can trust. For four years I built streaming and batch pipelines at **Jio Platforms**, powering inventory and recommendation experiences for tens of thousands of retail stores.

Now charting the Grand Line of a **M.S. in Business Analytics at the University of New Haven**, leveling up on forecasting, ML, and BI, and looking for the next crew where I can ship streaming infrastructure that actually moves the needle.

> *Engineering data at the speed of business.*

</td>
</tr>
</table>

🧭 **New York, NY** (open to relocation) &nbsp;•&nbsp; 🎯 Streaming, ETL, Big Data, Cloud &nbsp;•&nbsp; 🏴‍☠️ Open to opportunities

## 🗺️ the voyage so far

```python
# stream-pipeline.py
from pyspark.sql import SparkSession
from pyspark.sql.functions import *

spark = SparkSession.builder \
    .appName("inventory-sync") \
    .getOrCreate()

stream = (spark.readStream
    .format("kafka")
    .option("subscribe", "retail.inventory")
    .load())

# 50M+ records / day across 10K+ stores
(stream
    .select(from_json(col("value"), schema).alias("d"))
    .writeStream
    .format("iceberg")
    .outputMode("append")
    .start())
```

<div align="center">

**4+** Years building data systems &nbsp;•&nbsp; **50M+** Daily records processed &nbsp;•&nbsp; **10K+** Retail locations synced &nbsp;•&nbsp; **60%** Faster reporting with Iceberg

</div>

**Software Developer (Big Data)** · Jio Platforms Ltd. · Aug 2020 to Aug 2024 · Mumbai

* Engineered scalable Spark and Flink ETL pipelines processing **50M+ daily inventory records** for 7 Eleven, JioMart, AJIO, and Marks & Spencer, syncing real time stock across **10,000+ store locations**.
* Cut data processing latency by **40%** by optimizing Kafka streaming architecture and parallel processing for high volume retail data.
* Integrated **Apache Iceberg** into the HDP ecosystem, replacing legacy SCD logic and improving data mart reporting speeds by **60%** for JioMart and AJIO.
* Built product recommendation pipelines with **PySpark ML**, increasing user engagement by **25%**.
* Led cross functional teams of **5+ engineers**, mentoring juniors and managing sprint deliverables.

## 🧰 the arsenal

**Languages**

![Python](https://img.shields.io/badge/Python-f59e0b?style=for-the-badge&logo=python&logoColor=fff8e7)
![SQL](https://img.shields.io/badge/SQL-f59e0b?style=for-the-badge&logo=postgresql&logoColor=fff8e7)
![Scala](https://img.shields.io/badge/Scala-f59e0b?style=for-the-badge&logo=scala&logoColor=fff8e7)
![Java](https://img.shields.io/badge/Java-f59e0b?style=for-the-badge&logo=openjdk&logoColor=fff8e7)

**Data & Streaming**

![Spark](https://img.shields.io/badge/Apache_Spark-ef4444?style=for-the-badge&logo=apachespark&logoColor=fff8e7)
![Flink](https://img.shields.io/badge/Apache_Flink-ef4444?style=for-the-badge&logo=apacheflink&logoColor=fff8e7)
![Kafka](https://img.shields.io/badge/Apache_Kafka-ef4444?style=for-the-badge&logo=apachekafka&logoColor=fff8e7)
![Iceberg](https://img.shields.io/badge/Apache_Iceberg-ef4444?style=for-the-badge&logo=apache&logoColor=fff8e7)
![dbt](https://img.shields.io/badge/dbt-ef4444?style=for-the-badge&logo=dbt&logoColor=fff8e7)
![Airflow](https://img.shields.io/badge/Airflow-ef4444?style=for-the-badge&logo=apacheairflow&logoColor=fff8e7)

**Stores & Cloud**

![Snowflake](https://img.shields.io/badge/Snowflake-0891b2?style=for-the-badge&logo=snowflake&logoColor=fff8e7)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0891b2?style=for-the-badge&logo=postgresql&logoColor=fff8e7)
![MongoDB](https://img.shields.io/badge/MongoDB-0891b2?style=for-the-badge&logo=mongodb&logoColor=fff8e7)
![AWS](https://img.shields.io/badge/AWS-0891b2?style=for-the-badge&logo=amazonwebservices&logoColor=fff8e7)
![Azure](https://img.shields.io/badge/Azure-0891b2?style=for-the-badge&logo=microsoftazure&logoColor=fff8e7)

## 💰 the treasure map

* **FleetCor Cross Sell Strategy** — credit risk scoring with PySpark, SQL Server, and Tableau.
* **Port Authority Tunnels & Bridges Analytics** — forecasting with Python, Azure AutoML, and Power BI.
* **auto-apply** — automation tooling that charts the job application seas for me.

## 🐚 the logbook

<div align="center">

[![Followers](https://img.shields.io/github/followers/redshift7?style=for-the-badge&logo=github&logoColor=fff8e7&label=Followers&labelColor=0a1a2e&color=fbbf24)](https://github.com/redshift7?tab=followers)
[![Profile views](https://komarev.com/ghpvc/?username=redshift7&style=for-the-badge&label=Profile+views&color=ef4444)](https://github.com/redshift7)
[![Website](https://img.shields.io/badge/Portfolio-sathvikkasoju.com-0891b2?style=for-the-badge&logo=safari&logoColor=fff8e7&labelColor=0a1a2e)](https://sathvikkasoju.com)

</div>

<div align="center">

`yohoho~ thanks for stopping by ✦`

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:fbbf24,50:f59e0b,100:ef4444&height=120&section=footer)

</div>
