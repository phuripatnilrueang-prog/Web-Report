# Terminal Automation System (TAS) - Engineering Implementation Report

![Project Status](https://img.shields.io/badge/Status-Active-success)
![Institution](https://img.shields.io/badge/Institution-KOSEN_KMUTT-orange)
![Field](https://img.shields.io/badge/Field-Automation_Engineering-blue)

## 📌 Project Overview
This repository contains the engineering design review and implementation report for a comprehensive **Terminal Automation System (TAS)** designed for a fuel distribution terminal. The project successfully bridges Operational Technology (OT) and Information Technology (IT) to manage fuel distribution logistics. 

The implementation was executed across conceptual design, engineering execution, and intelligent data automation phases, incorporating a robust Cloud-native backend, MES-to-ERP pricing synchronization, and an advanced Digital Twin environment.

## 🏗️ 5-Layer System Architecture
The TAS employs a robust 5-layer architecture designed to ensure secure, efficient, and scalable management of fuel distribution logistics, separating control networks from enterprise applications:

* **Layer 1 (The Edge & OT):** WAGO PFC200 Master PLC, AccuLoad IV controllers, load sensors, and barcode scanners.
* **Layer 2 & 3 (DMZ & Integration):** Secure routing via OPC UA/MQTT through a DMZ containing Kepware and OPC UA Servers.
* **Layer 4 & 5 (Cloud-Native IT):** Azure IoT Hub, Azure Data Factory (ETL), and Azure SQL Data Warehouse.
* **Business & Analytics:** Power BI for KPI tracking and Odoo ERP for MES-synchronized dynamic pricing.
* **Layer 6 (Digital Twin):** LLMs and Vector Databases for semantic querying of technical manuals and fault codes.

## 📂 Repository Contents
The project is deployed as a single-page interactive engineering report, supported by underlying technical documentation:

* `index.html`: The core engineering report and web view (originally `tas-report.html`).
* `IDEF0.pdf`: Full functional logic and sequential flow models for TAS Operations.
* `data-architecture.pdf`: High-level topology of the 5-Layer Azure Cloud data pipeline.
* `IO-database.xlsx`: Comprehensive I/O instrument mapping for field devices.
* Supporting architecture, operational, and dashboard image assets.

## 🌐 Live Report Deployment
The full engineering report is hosted interactively via GitHub Pages. 
👉 **[View the Live TAS Engineering Report Here](https://phuripatnilrueang-prog.github.io/Web-Report/)** ## 👥 Project Team (Group 7)
* **Phuripat Nilrueang:** Project Manager & Automation Engineer (OT)
* **Phop Keseesang:** Data / Cloud Engineer (IT)
* **Pharun Ngamcharoen:** Data / Cloud Engineer (IT)
* **Wiwan Wijitworawong:** Data Scientist (Analytics & Costing)
* **Praravee Treepattarachayakorn:** Data Scientist (ERP Integration)
* **Thepparux Ruxpakawong:** AI Engineer

---
*King Mongkut's University of Technology Thonburi (KMUTT) | KOSEN*
