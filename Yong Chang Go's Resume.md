# Yong Chang Go — Resume

<img src="profile.jpg" alt="Profile Photo" width="120" style="border-radius: 50%;" />

📧 ycgo711@icloud.com | 📱 +65 8881 7114 | 📍 Singapore  
[LinkedIn](https://www.linkedin.com/in/yong-chang-go711) | [GitHub](https://github.com/Go-Go7)

## Profile

Software engineer with 3+ years of experience building production automation systems in semiconductor manufacturing — from real-time SPC watchdogs and defect management platforms to MES-integrated lot tracking tools. Focused on reducing manual engineering effort through end-to-end system delivery.

---

## Employment History

### Software Engineer, Data Analysis Platform — VisionPower Semiconductor Manufacturing Company (VSMC)
**June 2025 — Present**

- Build and maintain a **KLA Map-to-Map Data Watchdog** in Python — an automated SPC pipeline that monitors active lots, calculates DC values via formula-driven SQL against KLA inspection data, and submits results to MES with Oracle audit logging and automated retry on failure
  - **Impact:** Processing ~10 lots/hour autonomously, saving an estimated 1.5–2 engineering hours per hour of operation
- Maintain and enhance **VEDA**, a semiconductor engineering data analysis platform in C# (.NET WinForms + ASP.NET Web Services) with a 3-tier architecture, featuring cross-data-source correlation analysis (LQC, WAT, CP, SP, Lot History, FDC) with dynamic field mapping, and an interactive charting engine (trend, box plot, histogram, scatter, matrix) built on MS Chart Controls
  - **Impact:** Enabling engineers to identify yield-impacting equipment and process parameters across fab sites
- Maintain and enhance a full-stack **Defect Management System (DMS)** in C# (.NET/WinForms) — a config UI (SetupUI) with RBAC, a defect review UI with real-time Oracle WIP queries for lot hold/track-out/highlight operations, and an automated background service (Spec Check AP) triggering highlight actions via NATS messaging
  - **Impact:** Reducing manual review effort and improving defect response consistency across KLA, OM, SEMV, and ADC inspection equipment types

### Software Developer, Manufacturing Execution Systems — United Microelectronics Corporation (UMC), Singapore Branch
**February 2023 — June 2025**

- Migrated and enhanced the **eRack Management System** from a legacy ASP.NET web application to C#/.NET Windows Forms with Oracle SQL and multi-threading for real-time MES sync via transaction calling
  - **Impact:** Reduced FOUP check-in/check-out time by ~50% and improved overall usability
- Built an **Automated WAT Rework and Backup System** in C# integrated with Aegis and ADO.NET, automating lot verification, hold code management, and parameter modifications
  - **Impact:** Processing up to 50 lots/hour (vs ~30 min/lot manually), reducing issue-checking time by 80% through automated alarm email notifications
- Migrated the **Reticle Management System** from VB to C#/ASP.NET Web Forms, implementing AJAX partial updates and session management
  - **Impact:** Improved application performance and boosted daily operation efficiency by ~30%
- Maintained and enhanced existing MES applications, collaborating with production staff to diagnose issues and deploy fixes with minimal downtime

---

## Technical Skills

**Languages:** C#, Python, SQL, HTML/CSS/JavaScript, VB.NET, SAS  
**Frameworks:** .NET Framework, ASP.NET Web Forms, Windows Forms, ADO.NET  
**Tools & Platforms:** Git, Gitea, Microsoft Azure DevOps, DBeaver, Oracle SQL Developer, NATS  
**Databases:** Oracle  
**Domain Expertise:** Semiconductor Manufacturing, MES Integration, Engineering Data Analysis, SPC Data Pipelines, Process Automation

---

## Education

### Bachelor of Information Technology (Honours) — Artificial Intelligence
**Multimedia University (Malacca Campus), Malacca**  
June 2018 — September 2022 | CGPA: 3.36
