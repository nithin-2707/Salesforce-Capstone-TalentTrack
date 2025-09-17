# Phase 2: Solution Design  
**Project:** TalentTrack – Recruitment & Candidate Management System  

---

## 1. Core Objects  

### Standard Objects (Sales Cloud)  
- **Lead** – Candidate Application  
- **Contact** – Candidate (after Lead conversion)  
- **Opportunity** – Job Opening / Hiring Opportunity  
- **Campaign** – Recruitment Drive / Job Fair  

### Standard Objects (Service Cloud)  
- **Case** – Candidate Queries (e.g., "When is my interview?")  

### Custom Objects  
- **Interview__c** – Store interview details (date, round, interviewer, feedback)  
- **Offer__c** – Store offer details (salary, status: Draft/Accepted/Rejected)  

---

## 2. Relationships  

- **Lead → Contact → Opportunity**  
- **Interview__c → Candidate (Contact) + Job Opening (Opportunity)**  
- **Offer__c → Candidate (Contact) + Job Opening (Opportunity)**  
- **Case → Candidate (Contact)**  

---

## 3. Data Flow  

1. Candidate applies → Captured as **Lead**  
2. Recruiter qualifies Lead → Converted into **Contact + Opportunity**  
3. Candidate scheduled for **Interview__c**  
4. Feedback recorded → **Offer__c** created if selected  
5. Candidate raises **Case** (Service Cloud) for queries  
6. Reports & Dashboards (planned) will show:  
   - Time-to-hire  
   - Source effectiveness  
   - Candidate conversion ratio  
   - Common queries  

---

## 4. Automation & Workflows (Planned)  

- **Planned Email Alerts:** To send interview confirmation emails to candidates (Phase 3)  
- **Planned Case Assignment Rules:** Route candidate queries to recruiters automatically (Phase 3)  
- **Planned Validation Rules:** Prevent creating an Offer without Candidate (Phase 3)  
- **Planned Dashboards:** Track hiring funnel, SLA breaches, interview feedback (Phase 3)  

---

## 5. Entity-Relationship Design (ERD)  

Planned schema:  
- Lead → Contact → Opportunity  
- Interview__c → Candidate + Job Opening  
- Offer__c → Candidate + Job Opening  
- Case → Candidate  

(ERD diagram screenshot added as `ERD_Diagram.png`.)  

---

## 6. Reports & Dashboards (Planned)  

- **Candidate Pipeline Report:** Opportunities grouped by stage  
- **Time-to-Hire Report:** Average days to close a candidate  
- **Case Reports:** Candidate queries by type and SLA breach  
- **Recruitment Dashboard:** Combined view of hiring pipeline, interview status, candidate queries  

---

📄 Deliverables in this folder:  
- `TalentTrack-Phase2.pdf` – Detailed Phase 2 documentation  
- `README.md` – Phase 2 summary  
- `ERD_Diagram.png` – Schema diagram screenshot from Salesforce Schema Builder  
