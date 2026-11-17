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
