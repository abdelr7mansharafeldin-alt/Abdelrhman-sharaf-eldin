<div align="center">
  <img src="Team%20Logo.png" alt="DATA NOVA Logo" width="220" />

  <h1>🌍 Atmos-X: Egyptian Governorates Air Quality Analytics</h1>

  <!-- شريط طقس متحرك تفاعلي -->
  <a href="#">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=18&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=⚡+Live+AQI+Monitoring+Across+Egyptian+Governorates;☀️+Tracking+Solar%2C+Climate+%26+Weather+Metrics;🌬️+Analyzing+PM2.5%2C+PM10%2C+CO+%26+NO2+Hotspots;📊+End-to-End+Pipeline+by+DATA+NOVA+Team+%7C+DEPI" alt="Live Weather Ticker" />
  </a>

  <br/><br/>

  <!-- Tools Badges -->
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/UI%2FUX-Glassmorphism-8B5CF6?style=for-the-badge" alt="Glassmorphism" />
</div>

<!-- فاصل متحرك لأمواج الهواء والطاقة -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## 🌤️ Project Idea & Concept

**Atmos-X** is an end-to-end data analytics project aimed at monitoring and analyzing air quality and environmental metrics across various Egyptian governorates. 

The project provides actionable insights through interactive, dark-themed **Glassmorphism Dashboards**, enabling users to track pollution levels, weather conditions, and climate trends effectively.

<div align="center">
  <table width="100%">
    <tr>
      <td align="center" width="33%"><b>☀️ Solar & Climate</b><br/>Tracking ambient temperatures, UV, and pressure shifts.</td>
      <td align="center" width="33%"><b>💨 Wind & Diffusion</b><br/>Analyzing wind speed & direction impact on pollution dispersion.</td>
      <td align="center" width="33%"><b>🌫️ Air Quality Safety</b><br/>Real-time AQI categorization & hazardous gas mapping.</td>
    </tr>
  </table>
</div>

---

## 🔄 End-to-End Architecture & Pipeline

```mermaid
graph LR
    A[🐍 Python<br/>Data Extraction] --> B[🗄️ SQL<br/>Cleaning & Unions]
    B --> C[⚡ Power Query<br/>M-Code Transformations]
    C --> D[📐 Data Modeling<br/>Star Schema & DAX]
    D --> E[📊 Power BI & Excel<br/>Glassmorphism Dashboards]
    
    style A fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#fff
    style B fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#fff
    style C fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#fff
    style D fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#fff
    style E fill:#0f172a,stroke:#facc15,stroke-width:2px,color:#fff
