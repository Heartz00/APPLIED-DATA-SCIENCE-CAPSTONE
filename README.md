# **SpaceX Launch Dashboard 🚀**

The **SpaceX Launch Dashboard** is a **real-time data science dashboard** built using **Streamlit**. This project visualizes insights about SpaceX launches, such as payload mass, launch success rates, and orbital outcomes. The tool uses interactive visualizations to help analyze and predict trends in rocket launches, aiding in decision-making for future launches.

---

Dashboard link - https://heartz00-streamlit-dashboard-app-depl-reallife-dashboard-q3oskq.streamlit.app/

![image](https://github.com/user-attachments/assets/77d004e4-fb02-4faf-b98b-ff2fadfb4651)



## **Project Overview**
SpaceX's ability to reuse the first stage of their Falcon 9 rockets has revolutionized the space industry. This project aims to:
- Analyze key factors that influence the success of rocket launches.
- Visualize payload mass across launch sites.
- Provide insights into success rates by orbit and launch site.
- Enable informed decision-making regarding launch costs and conditions for successful launches.

### **Key Features**
- **Interactive Charts**: Scatter plots, pie charts, and bar charts to visualize trends and insights.
- **Real-Time Data**: Utilizes real-time datasets for dynamic insights.
- **Detailed Data View**: Explore the underlying dataset directly in the dashboard.

---

![image](https://github.com/user-attachments/assets/7b0f70c3-a936-4069-98fc-15e1f998aa48)


## **Dashboard Highlights**
### 1️⃣ **Payload Mass vs. Launch Site**
- Visualizes the relationship between payload mass and launch site.
- Observations:
  - The **VAFB-SLC launch site** doesn't launch rockets with heavy payloads (>10,000 kg).

### 2️⃣ **Launch Site Success Rate**
- Pie chart showcasing the launch site with the highest success rate.
- Insights:
  - **KSC LC 39A** has the highest success rate among all launch sites.

### 3️⃣ **Orbit Success Rates**
- Bar chart visualizing success outcomes based on orbit type.
- Insights:
  - Orbits like **ES-L1**, **GEO**, **HEO**, and **SSO** exhibit higher success rates.

### 4️⃣ **Detailed Data View**
- Provides a tabular view of the raw dataset for a deeper analysis.

---

## **Dataset**
- Source: [IBM Skills Network Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DS0321EN-SkillsNetwork/datasets/dataset_part_2.csv)
- Columns:
  - **PayloadMass**: The payload mass in kilograms.
  - **LaunchSite**: The launch site name.
  - **Class**: Binary indicator (1: Success, 0: Failure).
  - **Orbit**: Type of orbit for the launch.

---

## **Technologies Used**
- **Python Libraries**:  
  - `Streamlit`: For building the interactive web application.  
  - `pandas`: For data manipulation and analysis.  
  - `numpy`: For numerical computations.  
  - `plotly`: For creating interactive charts.  
  - `PIL`: For image processing.  

- **Data Source**: CSV file hosted online.

---

## **How to Run Locally**
### Prerequisites
Ensure you have Python 3.7+ installed along with the required libraries:
```bash
pip install streamlit pandas numpy plotly pillow
