# ADF-E2E-Pipeline


## 📌 Project Overview  
This project demonstrates the use of **Azure Data Factory (ADF)** to build an **end-to-end ETL pipeline**.  
The pipeline ingests data from multiple sources, applies transformations, and outputs consolidated, business-ready results.  

---

## 🔧 Key Features  
- Data ingestion from **HTTP → ADLS Gen2 → Azure SQL DB**  
- **Data Flow transformations**: join, filter, select, sort, aggregate  
- Export of clean, consolidated **JSON** to ADLS Gen2  
- Configured **Linked Services, Datasets, and Copy Activities**  
- Debugged, published, and monitored pipelines for end-to-end validation  

---

## 🏗️ Architecture Flow  
1. **HTTP Source** → Orders data ingestion  
2. **ADLS Gen2** → Staging & intermediate storage  
3. **Azure SQL DB** → Customer data integration  
4. **ADF Data Flow** → Transformations (joins, filters, aggregates)  
5. **ADLS Gen2 Output** → Final JSON export  

---

## 📚 Learning Outcomes  
- Hands-on with **Azure Data Factory pipelines and data flows**  
- Experience with **Linked Services, Datasets, Copy Activities**  
- Understanding how to **orchestrate cloud-based ETL** efficiently  
- Improved skills in **debugging, publishing, and monitoring ADF pipelines**  

---

## 🏷️ Technologies Used  
- Azure Data Factory  
- Azure Data Lake Storage Gen2  
- Azure SQL Database  
- JSON  

---
