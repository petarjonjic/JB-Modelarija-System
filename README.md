# JB Modelarija System – Information System Development Project

This repository contains the full development of an information system designed for the needs of the company **JB Modelarija Blažeka d.o.o.** as part of the university course *Information System Development* (PIS) at the Faculty of Organization and Informatics, University of Zagreb.

The system models real business processes related to **procurement**, **finance**, and **production**, and demonstrates the application of system analysis and design techniques including process modeling, data modeling, and implementation via Oracle APEX.

---

## Project Purpose and Scope

The project was conducted in a team of three students with the objective of analyzing, modeling, and implementing an information system that reflects the operational workflows of a real-world manufacturing company. The system focuses on:

- **Procurement process:** Managing suppliers and incoming orders
- **Production monitoring:** Employees, production tracking, material usage
- **Finance overview:** Cost allocation and tracking (model-level)

---

## Folder Structure Overview

| Folder          | Contents                                                                          |
|-----------------|------------------------------------------------------------------------------------|
| `Documentation` | Full project documentation (PIS - Project.pdf), including description and analysis |
| `Diagrams`      | Visual diagrams: BPMN processes, ER models, decomposition, PK matrices             |
| `ApexExport`    | SQL export of the Oracle APEX application                                          |
| `Screenshots`   | Application screenshots: forms, reports, dashboards                                |

Each folder reflects a specific deliverable or component of the IS development process, from analysis to implementation.

---

## Features and Functionality

- Management of:
  - Customers
  - Suppliers
  - Employees
- RESTful API endpoints using APEX:
  - `/MB/kupci/`
  - `/MB/dobavljaci/`
  - `/MB/zaposlenici/`
- Interactive reports and dashboards via APEX
- Data operations implemented via web services and Oracle SQL

---

## Technologies Used

- **Oracle APEX** – for application logic and UI (forms, reports, dashboards)
- **SQL & ER Modeling** – for relational schema and data management
- **Draw.io** – for BPMN, ER and decomposition diagrams
- **PDF** – for documentation and structured project reporting

---

## Methodology & Artifacts

The project followed core IS development phases:

1. **Requirements gathering**
2. **Process analysis and modeling**
   - BPMN diagrams
   - Decomposition diagrams
3. **Data modeling**
   - ER model
   - Relational schema
4. **Design & Implementation**
   - UI design in Oracle APEX
   - SQL-based logic
   - RESTful API integration
5. **Documentation**
   - Specification of processes, data structures, and system features

---

## Academic Context

- **Course:** Information System Development *(PIS)*
- **Institution:** Faculty of Organization and Informatics (FOI), University of Zagreb
- **Academic Year:** 2024/2025
- **Project Duration:** October 2024 – January 2025
- **Team:** 3 members

---

## ⚠️ Disclaimer

This repository is part of a university coursework assignment.  
All company data and system design are based on publicly shared or fictionalized data.  
The system is not used in production and is for **educational purposes only**.

