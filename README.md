# Mechanisms-of-Action-MoA-Prediction-Tutorial
# **Predicting Drug Mechanisms of Action (MoA) Using Machine Learning**

## **Group Name / Team Members**
- Shirley Xie
- Jingcheng Shao
- Yongxian He

---

## **Tutorial**
In this session, we will walk through the entire pipeline of data preprocessing, feature engineering, training machine learning models, and evaluating performance for predicting drug mechanisms of action (MoA). By the end, you will understand how to apply **multi-label classification** techniques to biological data and optimize models for drug discovery applications.

---

## **Introduction**
Understanding the **mechanism of action (MoA)** of a drug is essential for drug discovery, repurposing, and safety assessment. Traditionally, determining MoA requires extensive **biochemical experiments**, which are costly and time-consuming. **Machine learning (ML)** provides a powerful alternative by analyzing large-scale **gene expression** and **cell viability** data to infer MoAs computationally.

However, MoA prediction presents challenges such as **high-dimensional data**, **multi-label classification**, and **class imbalance**. Kaggle’s MoA competition provides a dataset to explore how ML models can **predict drug effects** more efficiently and accurately.

---

## **Aim**
The goal of this project is to **develop machine learning models** capable of accurately predicting the **mechanism of action (MoA) of compounds** based on their biological response data. This will help identify drug targets, accelerate drug discovery, and improve precision medicine approaches.

---

## **Dataset**
The dataset provided in the **Kaggle MoA competition** consists of high-throughput screening data with gene expression and cell viability features. Each sample corresponds to a drug compound with its known MoA labels.

### **Dataset details:**
- **Features:**
  - Gene expression levels  
  - Cell viability measurements  
- **Labels:**
  - Multi-label MoA annotations  
- **Challenges:**
  - Multi-label classification  
  - High-dimensional data  
  - Class imbalance  
