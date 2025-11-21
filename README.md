# Cybersecurity Threat Analysis dashboard using PowerBi
A Power BI-based Business Intelligence project analyzing worldwide cybersecurity incidents, attack patterns, and response efficiency from 2015–2024 using real-world data.

# 🛡️ Global Cybersecurity Threat Intelligence & Response Dashboard

This project visualizes and analyzes global cybersecurity threats using Power BI.  
It provides key insights into cyberattack trends, vulnerabilities, affected regions, industries, and financial impact.  
The dashboard supports cybersecurity leaders in understanding evolving threats and making data-driven defense decisions.

---

## 📊 Project Overview
- **Goal:** Identify, visualize, and interpret global cyber threat trends and their business impact.  
- **Dataset:** `Global_Cybersecurity_Threats_2015-2024.csv` (sourced from Kaggle)  
- **Tool Used:** Microsoft Power BI Desktop (.pbix)  
- **Scope:** 3,000 incidents | 10 features | 10-year timeline (2015–2024)  
- **Modules Used:** Data Modeling, DAX, Calculated Columns, Measures, Visual Design  
- **Author:** [Rahul Pagar](https://www.linkedin.com/in/rahul-pagar1993)

---

### 🏷️ Keywords
cybersecurity, powerbi, dashboard, data-visualization, business-intelligence, cyber-threats, data-analytics, dax, data-modeling, risk-analysis

---

## ⚙️ Workflow and Methods

### 1️⃣ Project Background and Intended Users
The project was developed for **Cyber Secure Analytics Pvt. Ltd.**, a cybersecurity consulting firm.  
The dashboard is designed for the **Chief Information Security Officer (CISO)** to help visualize:  
- Global cyberattack trends over time  
- Financial and operational impact of incidents  
- Average response and resolution times  
- Countries and industries most at risk  

The CISO uses this dashboard to align cybersecurity actions with organizational goals and to monitor overall digital resilience.

---

### 2️⃣ Dataset Overview and Enhancements
- **Source:** Kaggle — Global Cybersecurity Threat Dataset (2015–2024)  
- **Volume:** ~3,000 incidents with attributes across geography, time, and impact  
- **Key Attributes:**  
  - 🌍 Geographical Info (Country, Region)  
  - ⏱️ Timeline Info (Year, Month)  
  - 💥 Attack Details (Type, Source, Defense Used)  
  - 🏢 Target Information (Industry, Users Affected, Vulnerability)  
  - 💰 Financial Data (Loss in USD)  
  - 🛠️ Response Info (Resolution Time, Countermeasures)

**Created Measures:**
- *Average Incident Resolution Time* — Mean time to resolve incidents  
- *Most Frequent Attack Type* — Identifies the most common attack vector  
- *Slowest Attack Type* — Attack types taking longest to resolve  

**Calculated Columns:**
- *Attack Category* — Groups attack types into Disruption, Infiltration, Espionage, etc.  
- *Severity Score* — Combines financial loss and user impact for composite threat severity  

---

### 3️⃣ Dashboard Components
The **Power BI dashboard** consists of interactive visuals and key performance indicators (KPIs) providing real-time insights.

#### Global Threat Overview
- **Map:** Geographic distribution of attacks  
- **Pie Chart:** Attack type breakdown (DDoS, Malware, Phishing, etc.)  
- **Bar Chart:** Common vulnerabilities exploited  
- **KPI Cards:** Total Loss (USD Million), Average Resolution Time, Top Loss Industry  

#### Risk and Impact Analysis
- **Bar Chart:** Financial loss by industry  
- **Pie Chart:** Industry-wise distribution of weaknesses  
- **Tree Map:** Severity of Cyber Attacks by Country  
- **Slicer (Timeline Filter):** Interactive filter to view trends from 2015–2024  

These visuals allow stakeholders to monitor hotspots, vulnerable sectors, and evolving threat categories.

---

### 4️⃣ Insights and Key Findings
- The **Information Technology** and **Financial** sectors experience the most cyber incidents.  
- **DDoS** and **Phishing** remain the most common global attack types.  
- Average incident resolution time = **36.48 hours**.  
- The **United Kingdom, USA, Russia, and Germany** show the highest total financial losses.  
- Developing economies face slower resolution times and higher severity scores.  
- The **top vulnerabilities** are weak credentials, outdated systems, and unpatched software.  
- The dashboard enables security teams to **prioritize defenses** by country, attack type, and financial impact.

---

### 5️⃣ Benefits and Key Learnings
**Dashboard Benefits:**
- Empowers CISOs with a clear visualization of high-risk regions and industries.  
- Highlights top attack vectors to guide training, prevention, and technology investments.  
- Supports **data-driven cybersecurity strategy** formulation.  
- Simplifies complex datasets into actionable metrics through KPIs and DAX.  

**Learnings from the Project:**
- Designing dashboards that balance clarity and executive relevance.  
- Applying **DAX measures** and **calculated columns** for dynamic interactivity.  
- Enhancing storytelling with meaningful visuals for non-technical decision-makers.  
- Improving data structuring and readability for business intelligence applications.

---

## 📑 Files, Author & Conclusion

### 📁 Files Included
- **`Dashboard.pbix`** — Power BI dashboard containing all KPIs, visuals, and interactivity.  
- **`Cyber security threat dashboard.pdf`** — Project report and detailed explanation of the dashboard.  
- **`Global_Cybersecurity_Threats_2015-2024.csv`** — Source dataset with 3,000 cybersecurity incidents.

### 👨‍💻 Author
**Rahul Pagar**  
🎓 Masters in Business Analytics — Dublin Business School  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/rahul-pagar1993)

### 🏁 Conclusion
The **Global Cybersecurity Threat Intelligence & Response Dashboard** provides a 360° view of global threat activity and its impact on industries and economies.  
It enables CISOs and cybersecurity leaders to:  
- Identify emerging global threat trends  
- Track financial losses and risk severity  
- Prioritize vulnerabilities by geography and industry  
- Evaluate the efficiency of their incident response systems  

By integrating Power BI analytics with real-world cybersecurity data, this project demonstrates how **data visualization and intelligence** can empower organizations to strengthen resilience against modern cyber threats.  


---
