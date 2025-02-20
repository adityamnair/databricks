# databricks

# 🚀 Delta Lake Streaming with Databricks Community Edition

This repository demonstrates how to implement **incremental data processing** using **Delta Lake and Structured Streaming** in **Databricks Community Edition**, as an alternative to **Delta Live Tables (DLT)**, which is not available in the free tier.

## 📌 Features
- ✅ **Create and manage Delta Tables**  
- ✅ **Perform incremental updates using MERGE**  
- ✅ **Implement structured streaming for real-time data processing**  
- ✅ **Simulate an ETL pipeline for batch and streaming workloads**  

## 📂 Project Structure

📁 delta-lake-streaming/ │── 📄 create_delta_table.py # Create initial Delta Table
│── 📄 incremental_updates.py # Perform MERGE operations
│── 📄 streaming_pipeline.py # Process streaming data using Delta Lake
│── 📄 README.md # Documentation


## 🛠️ Prerequisites
Before running the scripts, ensure you have:
- **Databricks Community Edition** account ([Sign up here](https://community.cloud.databricks.com/))
- **Apache Spark 3.0+**
- **Delta Lake libraries** installed (`pip install delta-spark`)
- **Python 3.8+**


## 🛠️ Prerequisites
Before running the notebooks, ensure you have:
- ✅ **Databricks Community Edition** account ([Sign up here](https://community.cloud.databricks.com/))
- ✅ **Apache Spark 3.0+**
- ✅ **Delta Lake Libraries** (Pre-installed in Databricks Community Edition)
- ✅ **Python 3.8+**

## 🚀 Getting Started

### **1️⃣ Upload Notebooks to Databricks**
1. Log in to **Databricks Community Edition**  
2. Go to **Workspace** → Click **Import**  
3. Upload the `.ipynb` files from this repository  

### **2️⃣ Run the Notebooks in Order**
#### **Step 1: Create Delta Table**

#### **Step 2: Perform Incremental Updates**

#### **Step 3: Stream Data into Delta Table**

## 📢 Limitations
🚫 **Delta Live Tables (DLT) is not available in Databricks Community Edition**  
🚫 **No built-in data quality enforcement like DLT Expectations**  
✅ **Works as a manual alternative for incremental processing!**  

## 📜 License
This project is open-source and available under the **MIT License**.  

---

**📬 Need help?** Open an **issue** or contribute to improve this project! 🚀  

