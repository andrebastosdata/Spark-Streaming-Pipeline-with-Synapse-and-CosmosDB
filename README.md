![Pasted image 20241203144549](https://github.com/user-attachments/assets/6ee0b673-d950-4a33-ae13-9814b0635ec5)



# Real-Time Streaming Pipeline with Azure Synapse and Cosmos DB

## **Project Description**

This project demonstrates building a **real-time Spark streaming pipeline** integrating **Azure Synapse Analytics** and **Azure Cosmos DB**. The pipeline processes streaming data using **tumbling** and **sliding window functions**, joins datasets from multiple sources, and configures automated alerts with **Logic Apps**. This showcases a robust data processing framework for real-time analytics and event-driven scenarios.

---

## **Overview**

**Azure Cosmos DB** is a globally distributed, multi-model database that delivers low-latency, high-availability data solutions. Its compatibility with various APIs and models, along with features like **global distribution**, **scalability**, and **consistency models**, makes it ideal for real-time applications.

**Key Features:**
- **Tumbling and Sliding Window Functions:** Facilitate analytics on fixed or overlapping subsets of data.  
- **Streaming Joins:** Combine data streams from different sources for enriched analysis.  
- **Automated Alerts:** Configure **Logic Apps** to send email alerts for specific events or conditions.  

---

## **Tech Stack**

- **Languages:** Python, SQL  
- **Package:** PySpark  
- **Services:**  
  - Azure Blob Storage (ADLS Gen2)  
  - Azure Synapse Analytics  
  - Azure Cosmos DB  
  - Azure Logic Apps  

---

## **Key Concepts**

### **Window Functions**
1. **Tumbling Window Functions:**
   - Non-overlapping, fixed-size windows.
   - Use case: Sum of sales for each 24-hour period.

2. **Sliding Window Functions:**
   - Overlapping windows that slide over the dataset.
   - Use case: 7-day moving average of sales.

### **Streaming Joins**
- Combine multiple data streams in real time to create enriched datasets for analysis.

### **Logic Apps**
- Automate alerts for specific data events, enabling proactive monitoring.

---

## **Approach**

1. **Data Ingestion:**  
   - Use Azure Synapse to process streaming data from multiple sources stored in Azure Blob Storage.

2. **Real-Time Processing:**  
   - Implement tumbling and sliding window functions for real-time aggregations.  
   - Perform streaming joins to combine relevant datasets.

3. **Automated Alerts:**  
   - Configure Azure Logic Apps to send email alerts for specific triggers.

4. **Data Storage:**  
   - Store processed data in **Azure Cosmos DB** for low-latency querying.

---

## **Key Insights**

- Real-time calculations using tumbling and sliding windows.  
- Enhanced analytics through streaming joins.  
- Automated event-driven alerting with Logic Apps.

---

## **How to Run the Project**

1. **Set Up Azure Services:**
   - Create Azure Synapse, Cosmos DB, Blob Storage, and Logic Apps instances.

2. **Process Data:**  
   - Configure Spark streaming jobs in Synapse Analytics.  
   - Apply window functions and perform streaming joins.

3. **Automate Alerts:**  
   - Configure Logic Apps to trigger email alerts.

4. **Store Data:**  
   - Persist processed data in Azure Cosmos DB.

---

## **Contact**

For questions or feedback, feel free to reach out!
