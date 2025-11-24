# IVF Operations Optimization

This repository hosts the end-to-end solution for optimizing operations at one of India’s leading IVF clinics. The solution focuses on appointment scheduling, staff allocation, and equipment utilization through predictive analytics and optimization modelling.

---

## 🎯 Business Context

### Client
A premier IVF clinic in India facing operational inefficiencies:
- Long patient wait times  
- Imbalanced staff workloads (overload vs idle)  
- Sub-optimal equipment utilisation  
- Higher operational costs and lower throughput  

### Objective
Maximise patient satisfaction and clinic throughput by improving:
- Appointment scheduling  
- Staff allocation  
- Equipment utilisation  

### Constraints
- Minimise patient waiting time  
- Reduce staff overload / idle time  
- Keep operational costs under control  

### Success Criteria
**Business Success:** Improved patient satisfaction, increased throughput, better resource utilisation  
**Economic Success:** Reduced operational costs, increased revenue via efficient resource allocation  

---

## 🧠 Solution Approach

- **Predictive Analytics:** Forecast patient arrivals, service durations, staff demand  
- **Optimization Models:** Use scheduling and allocation algorithms (e.g., LP/MIP) to allocate resources efficiently  
- **Real-time Dashboards & Monitoring:** Provide continual operational insights and enable adaptive decision making  

---

## 📁 Repository Structure

ivf-operations-optimization/
│
├── data/ # Raw and processed data
├── notebooks/ # Exploratory Data Analysis & modelling notebooks
├── models/ # Predictive & optimization model code
├── dashboards/ # Dashboard files (Power BI, Tableau, Streamlit etc)
├── assets/ # Architecture diagrams, images
├── PowerBi_Dashboard_images/ # Visuals for dashboards
├── Project_Arc.docx # Architecture document
├── project_Presentation.pdf # Final presentation
└── README.md # This file

---

## 🏗️ System Architecture

See the full architecture diagram in `Project_Arc.docx`.  
To embed the architecture diagram in this README, follow these steps:

1. Extract the diagram from the `Project_Arc.docx` (save as e.g. `assets/architecture.png`).  
2. Add to this README:

```markdown
## Architecture Diagram

![System Architecture](assets/architecture.png)
🚀 Tech Stack & Key Components

Python: Pandas, NumPy, Scikit-learn, Pyomo / OR-Tools (for optimisation)

SQL / Databases: For historical clinic data storage

Dashboarding: Power BI, Tableau or Streamlit for realtime monitoring

Models: Forecasting (e.g., time-series, regression), Scheduling optimisation

Deployment: (To be defined) – could include scheduled jobs, live dashboards
