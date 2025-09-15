# TalentTrack – Recruitment & Candidate Management System

## Phase 1: Problem Understanding & Industry Analysis

### 📌 Problem Statement
Companies receive thousands of resumes daily, making manual tracking inefficient. Recruiters face delays in managing candidates across multiple stages, while candidates often experience poor communication and drop-offs. Hiring managers lack real-time visibility into recruitment performance.  
Additionally, candidates frequently raise queries about their application or interview status, which requires proper handling and tracking.

A centralized Salesforce-based solution is needed to streamline recruitment pipelines while also managing candidate support effectively.

---

### 🎯 Why It’s Useful
- Streamlines HR hiring pipelines with end-to-end automation.  
- Improves candidate experience with timely updates and query resolution.  
- Helps hiring managers make data-driven decisions.  
- Combines **Sales Cloud** for recruitment and **Service Cloud** for query management.  

---

### 👥 Stakeholder Analysis
- **Candidates** – Apply for jobs, track application status, raise queries, and get updates.  
- **Recruiters** – Manage candidate records, schedule interviews, resolve queries, and track communication.  
- **Hiring Managers** – Review candidates, provide feedback, and approve offers.  
- **HR Admin** – Monitor recruitment and generate analytics.  

---

### 🔄 Business Process Mapping
1. Candidate applies via portal/form → Captured as **Lead** (Sales Cloud).  
2. Recruiter qualifies Lead → Converted into **Candidate record** (Sales Cloud).  
3. Interview scheduled → Automated **email/SMS notification** (Sales Cloud).  
4. Feedback recorded → Hiring decision (Offer/Reject) (Sales Cloud).  
5. Candidate raises queries → Captured as **Case** (Service Cloud).  
6. Case assigned to recruiters/HR → Resolved and tracked (Service Cloud).  
7. Reports and dashboards → Cover hiring pipeline + candidate query trends.  

---

### 🏢 Industry-Specific Use Case Analysis (HR CRM)
- **Applicant Tracking (Sales Cloud):** Manage hiring pipeline across roles.  
- **Interview Scheduling (Sales Cloud):** Automate scheduling, reminders, and feedback collection.  
- **Offer Management (Sales Cloud):** Manage offer approvals and communication.  
- **Recruitment Analytics (Sales Cloud):** Dashboards for time-to-hire, bottlenecks, source effectiveness.  
- **Candidate Query Management (Service Cloud):** Handle candidate inquiries via Cases, assignment rules, and SLA tracking.  

---

### 🛠️ AppExchange Exploration
- **Bullhorn for Salesforce** – Recruitment pipeline management.  
- **DocuSign** – Offer letter signing.  
- **SMS Magic / Twilio** – Candidate notifications.  
- **Chatbot/Case Automation tools** – Extend Service Cloud for faster query resolution.  

---

📄 **Phase 1 Deliverables**  
- `README.md` (this file)  
- `TalentTrack_Phase1_Sales_Service.pdf` (detailed Phase 1 report)  
