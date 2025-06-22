# 🚀 End-to-End Data Pipeline: Exporting Local MySQL Data to Azure Blob Storage using Azure Data Factory

## 📌 Project Overview

This project demonstrates how to build an automated, scalable, and hybrid data pipeline using **Azure Data Factory (ADF)** to extract data from a **local MySQL database** and export it to **Azure Blob Storage** in **multiple formats**: CSV, Parquet, and Avro. It includes the use of a **Self-hosted Integration Runtime (SHIR)** for secure on-premises database connectivity and demonstrates schema handling, transformation, and automation.

---

## 🎥 Project Video

▶️ [Watch Project Walkthrough](https://drive.google.com/file/d/1eWaXNmcabg1t5yjmY3QHND0gV7kGX1o1/view?usp=sharing)

---

## 🧰 Technologies Used

| Category              | Tools / Services                      |
|-----------------------|----------------------------------------|
| Cloud Platform        | Azure                                  |
| Data Pipeline Tool    | Azure Data Factory (ADF)               |
| Data Storage          | Azure Blob Storage                     |
| Source Database       | MySQL (local/on-premise)               |
| Integration Runtime   | Self-hosted Integration Runtime (SHIR) |
| File Formats          | CSV, Parquet, Avro                     |
| Query Language        | SQL                                    |
| Runtime Requirement   | Java Development Kit (JDK 11)          |
| OS/Utility            | Windows Services (`services.msc`)      |

---

## 🛠️ Features

- ✅ Connects on-premise MySQL database to Azure
- ✅ Uses Self-hosted Integration Runtime for hybrid data movement
- ✅ Exports data in **CSV**, **Parquet**, and **Avro** formats
- ✅ Handles schema issues and renames unsupported columns
- ✅ Automates pipeline execution via trigger (optional)
- ✅ Easily extendable for multiple tables or scheduled jobs

---

## 📁 Project Structure

```bash
.
├── README.md                # Project overview and instructions
├── SQL_Query.sql            # Query used to rename columns for export
└── Pipeline Setup           # Created inside Azure Data Factory
