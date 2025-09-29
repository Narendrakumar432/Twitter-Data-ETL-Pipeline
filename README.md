# 📊 Twitter ETL Pipeline

## 📌 About
This project is an **ETL (Extract, Transform, Load) pipeline for Twitter data**.  
It fetches tweets using the Twitter API, transforms them into clean structured data, and loads them into a database for analysis.  
The pipeline is automated with **Apache Airflow** for scheduling and monitoring.

---

## ⚙️ Tech Stack
- **Python** → Core scripting language  
- **Tweepy** → Extract tweets from Twitter API  
- **Pandas** → Data cleaning & transformation  
- **Airflow** → Workflow orchestration  
- **PostgreSQL / SQLite** → Storage  
- **Docker (optional)** → Containerization  

---

## 🚀 Features
- Extract tweets using hashtags/keywords  
- Transform JSON into structured format (text, user, timestamp, metrics)  
- Load cleaned data into a relational DB  
- Orchestrate pipeline using Airflow DAGs  
- Scalable & modular design  

---

## 📂 Project Structure
