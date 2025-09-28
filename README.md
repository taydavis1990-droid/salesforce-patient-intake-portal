
🏥 Patient Intake & Scheduling Demo (OmniStudio + Experience Cloud)
📌 Overview

This project demonstrates a Patient Intake & Scheduling solution built in Salesforce using OmniStudio, Experience Cloud, and supporting Salesforce automation.
It simulates how a healthcare provider could streamline the patient journey from registration → insurance validation → appointment scheduling → provider dashboard visibility.

Designed for use as a portfolio demo and case study.

🎯 Business Problem

Healthcare providers often face challenges with:

Manual patient intake forms (paper or PDF).

Delayed insurance validation and eligibility checks.

Scheduling conflicts between patients and providers.

Limited visibility for providers into upcoming appointments.

This project solves these by creating a guided digital intake process, integrating with mock insurance validation, and delivering real-time provider dashboards.

🛠️ Features

✅ Patient Intake OmniScript — collects demographics, insurance, symptoms.
✅ Insurance Validation Integration Procedure — simulates external API call.
✅ Appointment Scheduling OmniScript — patient selects time with doctor.
✅ Provider Dashboard FlexCard — shows upcoming patients + status.
✅ Experience Cloud Site — branded patient portal.
✅ Apex Automation — keeps Appointment objects in sync with OmniStudio data.

⚙️ Technical Architecture

Core Technologies:

OmniStudio (OmniScripts, FlexCards, DataRaptors, Integration Procedures)

Experience Cloud (Patient Portal)

Apex (business logic)

LWC (UI extensions if needed)

Data Model:

Patient__c (custom object)

Appointment__c (custom object)

Standard objects (Account, Contact, User) leveraged for relationships

Flow Diagram (docs/architecture/patient-intake-flow.png)
(Insert screenshot later)

📂 Repository Structure
Patient-Intake-Demo/
│
├── README.md
├── docs/
│   ├── screenshots/        # OmniStudio screen captures
│   ├── architecture/       # Diagrams & flows
│   └── notes.md            # Daily learnings
├── omnistudio/
│   ├── omniscripts/        # Intake & scheduling scripts
│   ├── flexcards/          # Provider dashboards
│   ├── dataraptors/        # Data mappings
│   └── integration/        # Mock API calls
├── lwc/
├── apex/
├── data/
└── video/

🚀 Deployment / Demo Instructions

Clone Repo

git clone https://github.com/<your-username>/Patient-Intake-Demo.git


Import OmniStudio Components

From OmniStudio → Activate OmniScripts & FlexCards.

Use omnistudio/ folder JSON exports.

Create Data

Upload sample CSVs from /data for Patients and Appointments.

Access Demo Portal

Navigate to Experience Cloud site (/patients).

Log in as demo Patient user.

📹 Demo Video

A short walkthrough of:

Patient completing intake → insurance validated → appointment scheduled → provider dashboard updated.

(Link to video will be added in /video folder after recording)

📈 Roadmap (Stretch Goals)

Add SMS/email reminders via Twilio integration.

Integrate actual insurance API (mocked for demo).

Expand to include Prescription & Lab Test workflows.

👨‍💻 Author

Taylor Davis — Salesforce Developer & Consultant
📍 Knoxville, TN
📧 Taydavis1990@gmail.com

🔗 Davistopia Consulting
 (replace with your actual site or portfolio link)