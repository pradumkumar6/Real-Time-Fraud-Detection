# 🚀 Real-Time Fraud Detection in Financial Transactions

### 🔹 **Project Overview**
- **Objective:** Detect fraudulent financial transactions in real-time using **Confluent Kafka** and **Spark Streaming**.  
- **Technologies Used:**  
  - **Data Processing:** Confluent Kafka, Spark Streaming  
  - **Database:** MongoDB  
  - **Alert System:** Email notifications  

---

### 🔹 **Key Features**
- **Real-Time Streaming:** Processes financial transactions in real-time with **low latency** using **Confluent Kafka**.  
- **Fraud Detection Logic:** Applies rule-based filtering to identify suspicious activities.  
- **Email Alerts:** Sends instant email notifications for flagged transactions.  
- **Data Storage:** Stores transaction logs in **MongoDB** for persistence.  

---

### 🔹 **Architecture Flow**
1️⃣ **Confluent Kafka Producer:** Streams incoming transaction data.  
2️⃣ **Spark Streaming:** Consumes and processes data in real-time.  
3️⃣ **MongoDB:** Stores transaction logs.  
4️⃣ **Email Alerts:** Sends alerts for suspicious transactions.  
