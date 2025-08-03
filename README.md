# Maternal Health Progress Tracking (SDG 3.1) — IBM Cloud Visualization Project

## 📊 Project Overview
This project focuses on visualizing and tracking India's progress towards Sustainable Development Goal (SDG) 3.1, which aims to reduce the global Maternal Mortality Ratio (MMR) to less than 70 per 100,000 live births by 2030. By leveraging IBM Cloud services, the project builds an end-to-end data visualization workflow that assists policymakers and healthcare stakeholders in identifying improvement areas through clear visual insights.

---

## 📌 Problem Statement (Problem 36 — Edunet Foundation SB4 Academia)
Maternal mortality remains a critical challenge for many developing countries, including India. Monitoring maternal health indicators like antenatal care coverage, skilled birth attendance, and MMR trends is essential for effective policy interventions. However, the lack of accessible and intuitive data visualization tools makes it difficult to track progress and identify gaps in real-time.

---

## 🎯 Objectives
- Analyze and visualize key maternal health indicators using cloud-based tools.
- Provide clear visual insights into trends and progress towards SDG 3.1.
- Enable stakeholders to access and interpret data easily through IBM Cloud.
- Build a scalable and secure workflow that eliminates local dependency.

---

## 🛠️ Tools & Technologies Used
- **IBM Cloud Object Storage (COS)** — for secure storage of maternal health datasets.
- **IBM Watson Studio (Jupyter Notebook)** — for building the data analysis and visualization workflow.
- **Python Libraries:**
  - pandas (Data manipulation)
  - seaborn (Data visualization)
  - matplotlib (Graph plotting)
  - ibm_boto3 & botocore (Cloud Object Storage access)
  - io (Stream decoding for CSV files)
- **Dataset Source:** NITI Aayog — SDG India Index Dataset (Public)

---

## 📈 System Approach & Workflow
1. Upload maternal health datasets to **IBM Cloud Object Storage (COS)**.
2. Access datasets in **Watson Studio Notebook** using **ibm_boto3**.
3. Perform data cleaning, transformation, and extract key indicators:
   - Maternal Mortality Ratio (MMR)
   - Antenatal Care Coverage (4+ Visits)
   - Skilled Birth Attendance.
4. Visualize trends using **Seaborn & Matplotlib** for clear insights.
5. Entire process executed on IBM Cloud — no local system dependency.

---

## 🚀 Deployment
- The project is fully deployed and executed within IBM Cloud.
- All datasets are stored in IBM Cloud Object Storage.
- The Jupyter Notebook is hosted and run inside IBM Watson Studio.
- No external/local hardware resources are used.

---

## 📊 Results & Observations
- The visualizations highlighted declining trends in MMR, indicating positive progress towards SDG 3.1.
- Antenatal Care Coverage and Skilled Birth Attendance showed improvements but highlighted the need for focused interventions in certain regions.
- The solution enables policymakers to easily interpret data trends and take informed decisions.

---

## 🔮 Future Scope & Enhancements
- Integrate additional data sources like real-time surveys and demographic statistics.
- Incorporate predictive analytics to forecast future trends in maternal health.
- Develop interactive dashboards for non-technical stakeholders.
- Expand the system to support region-wise comparisons across different states or countries.
- Leverage AI-driven services (IBM Watson AI) and edge computing for real-time insights.

---

## 📂 Repository Structure
- README.md — Project documentation (this file)
- MaternalHealthProject.ipynb — Jupyter Notebook code file
- MaternalHealthProject.pptx — Final PPT presentation
- Screenshots/ — (Optional) Screenshots of results & outputs


---

## 📜 References
- [IBM Cloud Documentation](https://cloud.ibm.com/docs)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [pandas Documentation](https://pandas.pydata.org/docs/)
- [IBM SkillsBuild Platform](https://skillsbuild.org/)
- [SDG India Index Dataset — NITI Aayog](https://niti.gov.in/sdg-india-index-dashboard)

---

## 🔗 Author
**Piyush Raj**  
Student, [Amity University Jharkhand], [B.Tech (CSE)]  
GitHub: [https://github.com/piyushraj8235]


