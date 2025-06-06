# YouTube-Data-Analytics-Pipeline-with-Cloud-Data-Fusion-Airflow-BigQuery

This repository contains code and configuration files for an Extract, Transform, Load (ETL) project using Google Cloud Data Fusion for data extraction, Google BigQuery for data loading.

## Overview
The project aims to perform the following tasks:

Data Extraction: Extract data using python.
Data Masking: Apply data masking & encoding techniques to sensitive information in Cloud Data Fusion before loading it into BigQuery.
Data Loading: Load transformed data into Google BigQuery table.

---

## 📌 Objective

Collect and analyze YouTube channel statistics for top Data Science creators, and build visualizations to explore their performance over time.

---

## Architecture
![Screenshot 2025-06-06 103125](https://github.com/user-attachments/assets/9722fa60-8058-4888-8e92-6f5af1d328dd)


## Python Output 

# Channel_Name,Subscribers,Views,Total_videos,Playlist_id
![Screenshot 2025-06-06 103524](https://github.com/user-attachments/assets/e4af0c74-3d89-48b8-b5cb-8c703d0625c7)
# Channel_Name
![Screenshot 2025-06-06 103544](https://github.com/user-attachments/assets/ff12f0e1-7d53-4b5f-ab3c-1e6df140bbf2)
# dtype
![Screenshot 2025-06-06 103556](https://github.com/user-attachments/assets/da0bd9b0-f72e-4157-9bb5-1961c8e616e2)
# JSON
![Screenshot 2025-06-06 103627](https://github.com/user-attachments/assets/e3398308-524c-4315-89a9-c92361247396)
# Channel_Name, Title,	Published_date, Views,	Like_count,	Comment_Count.
![Screenshot 2025-06-06 103648](https://github.com/user-attachments/assets/5b25ca54-bc68-4455-bba8-60a43990ea27)
# sample
![Screenshot 2025-06-06 103702](https://github.com/user-attachments/assets/ea089a72-93e2-4f7f-a3a4-f9146e459576)
# Info
![Screenshot 2025-06-06 103726](https://github.com/user-attachments/assets/ced44089-b4c1-486c-9462-53523e14456c)
# Channel name and count
![Screenshot 2025-06-06 103803](https://github.com/user-attachments/assets/43b90adf-3389-4fdf-afb5-99aa1fc0b837)

## Data Visualisation

![Screenshot 2025-06-06 103839](https://github.com/user-attachments/assets/fbf5e3be-7498-427a-8d4e-c98134363b74)
![Screenshot 2025-06-06 103858](https://github.com/user-attachments/assets/0a58700c-72b6-427a-bc0e-74a53a064d8a)
![Screenshot 2025-06-06 104024](https://github.com/user-attachments/assets/9b13bc37-0f7d-4d68-b337-097573594af7)
![Screenshot 2025-06-06 104044](https://github.com/user-attachments/assets/6691e1e3-5060-4db9-a9bc-ee9565599dd8)
![Screenshot 2025-06-06 103822](https://github.com/user-attachments/assets/c3e81be3-2d62-42d4-ab88-f23a2d3971ba)
![Screenshot 2025-06-06 104244](https://github.com/user-attachments/assets/21c53a58-34f2-4221-9a84-d4ecf76aa7e1)
![Screenshot 2025-06-06 104102](https://github.com/user-attachments/assets/812bd0a7-cb3b-4721-b75b-bc250248291c)
![Screenshot 2025-06-06 104126](https://github.com/user-attachments/assets/ed66446e-879e-46e6-b868-d92a0c6e1441)
![Screenshot 2025-06-06 104143](https://github.com/user-attachments/assets/8030e145-9d4c-4589-973f-aeb6e4b196e5)
![Screenshot 2025-06-06 104200](https://github.com/user-attachments/assets/bca9e046-8bd9-4c70-a3e0-ffed1af60dfe)

# 🎥 YouTube Data Science Channel Analytics Pipeline (GCP)

This project implements a complete ETL data pipeline to analyze **popular Data Science YouTube channels** using:

- **Python & YouTube Data API**
- **Google Cloud Platform**: Cloud Storage, Cloud Data Fusion, BigQuery
- **Looker Studio** for dashboarding and insights



## 🔧 Tools & Services

- **Python**
- **YouTube Data API v3**
- **Google Cloud Storage (GCS)**
- **Cloud Data Fusion**
- **BigQuery**
- **Looker Studio**
- (Optional) **Cloud Composer / Apache Airflow**

---

## Data Science YouTube Channel
![image](https://github.com/user-attachments/assets/51ee3cae-21e1-48c4-b04f-1a71c18ce3fc)
Upload the files, data science.csv
![image](https://github.com/user-attachments/assets/7fb20430-6ea4-44ef-bf92-ef47d21f07da)
Enable this API, Cloud Data Fusion API and Big Query API then create instance, select the Airflow 3. Type the Instance Name youtube-demo-02 and location US click the button create.
Estimated time is 15-20 minute after success instance. In the Action View Instance.
![image](https://github.com/user-attachments/assets/a46c3869-7f4e-4cd8-a0c4-b57d0e872dff)

Cloud Storage Default, Select Data *youtube-demo-02*, the data science.csv and select all the column button Create a Pipeline, Batch Pipeline.
![image](https://github.com/user-attachments/assets/634a8c5d-e4e3-4fbf-a2b5-a7b2a9385043)

## BigQuery
![image](https://github.com/user-attachments/assets/ea518ac7-7624-48c6-8e63-ac84b19fceb9)

![image](https://github.com/user-attachments/assets/3da01ec6-afc4-4f24-bad3-4326f41b72f6)

## Google Looker
![image](https://github.com/user-attachments/assets/9102627c-ca33-4c70-b307-c20c90511865)

![image](https://github.com/user-attachments/assets/2f652938-1dcb-44b6-9afe-3879f3b23054)

![image](https://github.com/user-attachments/assets/a4a271f0-f4ef-4180-8df9-164732f59137)

![image](https://github.com/user-attachments/assets/76be6e07-280e-4cae-a928-c738ace04498)
