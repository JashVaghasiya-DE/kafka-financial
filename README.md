# 🚀 Cloud-Native Data Platform with Real-Time Streaming and Automated Deployments

## 📌 Overview
This project provisions and manages Azure cloud resources using **Infrastructure-as-Code (IaC)** and implements end-to-end **data engineering workflows**. It includes **ETL pipelines, real-time data streaming, and CI/CD automation**.

---

## 🔥 Features
- **🏗 Infrastructure-as-Code (IaC):** Provisioned and managed **Azure resources** (*VNet, Subnets, Databricks, Data Factory, ADLS Gen2, Key Vault*) using **Terraform**.
- **🔄 ETL Pipelines:** Developed in **Azure Data Factory (ADF)** to ingest **MySQL data** into **ADLS Gen2** (*Parquet format*) with **parameterized workflows**.
- **⚡ Real-Time Data Streaming:** Integrated **Confluent Kafka** with **Azure** for **low-latency data ingestion** using **PySpark**.
- **🛠 CI/CD Automation:** Implemented in **Azure DevOps** for **ADF pipeline** and **Databricks workflow** deployments.
- **📊 Monitoring & Observability:** Designed **proactive monitoring solutions** using **Logic Apps** for **data lineage and pipeline stability**.

---

## 🏗 Architecture

<img width="1145" alt="model" src="https://github.com/user-attachments/assets/909ce441-f00e-4030-9534-32ba33b23ddd" />

## 🔷 Azure Data Factory Pipeline

![Screenshot 2025-03-04 121042](https://github.com/user-attachments/assets/850d0424-5c52-49c4-a450-26b8e13727cf)

## 🔶 Delta Live Table Pipeline

![Screenshot 2025-03-04 121250](https://github.com/user-attachments/assets/bc236d07-42b7-4b05-9dc5-e5492cdd6dff)


## ⚙ CI/CD Implementation

- 🔹 **ADF Pipelines:** Automated deployments using Azure DevOps YAML pipelines.
- 🔹 **Databricks Notebooks:** Synced via Databricks Repos and deployed using DevOps.

---

## 📝 Summary
This project is designed to streamline data engineering workflows on **Azure** by leveraging **Terraform/Bicep for IaC**, **Azure Data Factory for ETL**, **Confluent Kafka for real-time streaming**, and **Azure DevOps for CI/CD automation**. With proactive monitoring using **Logic Apps**, the system ensures high availability, scalability, and reliability of data pipelines. The project is ideal for organizations seeking efficient, automated, and robust data solutions in the cloud.

---
