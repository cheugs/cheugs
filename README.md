# Hi, I'm Marie Louise Chengho Fongang

**Data engineer and data scientist in training, with a full-stack background (Angular, Spring Boot).**

I am a fourth-year computer science student. I build data platforms end to end: streaming pipelines, data warehouses, forecasting models and the dashboards that make the results usable. The data projects below are documented in French and English, the pipelines are tested in CI, and most have a live demo.

**Open to:** Data Engineering · Data Science · AI Engineering · Data Analysis · Full-Stack Development (Angular / Spring Boot)

---

## Featured projects

### Data engineering

| Project | What it does | Stack | Demo |
|---|---|---|---|
| [Retail Inventory & Supply Chain Warehouse](https://github.com/cheugs/Retail-Inventory-or-and-Supply-Chain-Warehouse) | Star-schema warehouse answering where stock is missing, which suppliers deliver on time and how fast inventory turns. Refreshed every morning by GitHub Actions; 14 of 14 reconciliation checks pass. | dbt · PostgreSQL · Airflow · Docker · GitHub Actions | [Live dashboard](https://cheugs.github.io/Retail-Inventory-or-and-Supply-Chain-Warehouse/) |
| [Smart City Mobility Data Platform](https://github.com/cheugs/Smart-City-Mobility-Data-Platform) | Streaming platform for traffic sensors and public transport events with geospatial joins. 1,000,000 events processed with 0 lost and 0 duplicated. | Kafka · PySpark Structured Streaming · PostGIS · Airflow · Grafana | [Live demo](https://smart-city-mobility-data-platform-1.onrender.com) |
| [Real-Time Financial Transaction Platform](https://github.com/cheugs/Real-Time-Financial-Transaction-Data-Platform) | Payment monitoring pipeline with a live dashboard. About 3,000 events/s end to end on a laptop, 2.5 s median latency, no loss under a 1M-event burst. | Kafka · PySpark · PostgreSQL · dbt · Streamlit | [Live dashboard](https://cheugs-txn-monitor.streamlit.app/) |

### Data science and analysis

| Project | What it shows | Stack | Demo |
|---|---|---|---|
| [Electricity Demand & Renewable Energy Forecasting](https://github.com/cheugs/Electricity-Demand-Renewable-Energy-Forecasting) | Day-ahead demand forecast for Germany with 1.9% error, against 4.3% for the seasonal naive baseline and 2.6% for SARIMA. Errors translated into reserve requirements. | Python · XGBoost · SARIMA · pandas | [Notebook](https://github.com/cheugs/Electricity-Demand-Renewable-Energy-Forecasting/blob/main/forecasting_project.ipynb) |
| [Credit Risk & Financial Inclusion Study](https://github.com/cheugs/credit-risk-financial-inclusion) | Explainable default model on 1,000 real bank loans, with a cost-based decision threshold, SHAP explanations and a fairness audit by age group. | Python · scikit-learn · SQL · SHAP | [Report (PDF)](https://github.com/cheugs/credit-risk-financial-inclusion/blob/main/report/report_en.pdf) |
| [Climate Risk & Human Development Observatory](https://github.com/cheugs/climate-risk-observatory) | Tests whether the most climate-exposed regions are also the least developed, across 105 regions in France, India and the USA, using public data. | Python · statistics · data visualisation | [Live dashboard](https://climate-risk-observatory.onrender.com) |

### Full-stack

| Project | What it is | Stack |
|---|---|---|
| Logistics Tracking Frontend | Parcel tracking application with separate dashboards for customers, delivery agents and administrators. | Angular · TypeScript |
| E-Quiz Admin Dashboard | Administration dashboard for an online quiz platform. | Angular · TypeScript |

---

## Team projects

Projects owned by teammates or team organisations, where I was one of the contributors. My part is stated for each.

| Project | What it is | My contribution | Stack |
|---|---|---|---|
| Logistics Tracking System (team of 5) | Parcel delivery platform built as Java microservices: parcel, delivery, payment, notification and user services behind an API gateway, run with Docker Compose. | Built the web frontend, including the administrator and delivery-agent dashboards, and contributed backend features. | Angular · Java microservices · Docker |
| Gestion Immobilière | Property rental management application for three roles: super administrator, owner and tenant. | Built the Angular frontend (feature-based architecture, authentication, owner pages for room occupancy, arrears and reminders, tenant pages, contract and rent-receipt PDFs) and contributed backend features. | Angular · Java (Maven) · SQL |
| MeetIn (team organisation) | Meeting-room booking system for companies. | Designed and built the admin side of the frontend (dashboard, user, room and booking management pages) and contributed backend features. | Angular · TypeScript · Java |
| Online Reservation System (team of 4) | Web reservation application built with Spring Boot. | Worked on the page designs and user interface, and contributed backend features. | Spring Boot · Java · HTML |
| EQuiz (team organisation) | Online quiz platform with a web admin dashboard, a mobile app and a backend. | Built the web admin dashboard and contributed backend features. | Angular · TypeScript · JavaScript |
| Smart City web application (private repository) | University group project: a Java web application for a smart city. | Contributed to the tourist section. | Java |

---

## Tech stack

**Data engineering**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white)
![Apache Spark](https://img.shields.io/badge/PySpark-E25A1C?logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?logo=dbt&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

**Data science and AI**

![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5B2D)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)

**Full-stack**

![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)

---

## How I work

- **Results first:** each project states the question, the answer and the numbers before the code.
- **Tested and reproducible:** the data platforms run CI on every push, start locally with Docker Compose, and ship benchmarks you can rerun.
- **Honest about limits:** synthetic data is labelled as synthetic, and each README lists what the project does not prove.
- **Bilingual:** documentation in French and English.
