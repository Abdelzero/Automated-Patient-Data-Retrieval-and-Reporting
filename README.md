# Automated-Patient-Data-Retrieval-and-Reporting
# Overview
This Python-based automation tool is designed to interact with a specific Electronic Medical Records (EMR) system to efficiently manage and process patient appointments and medical data. It automates the retrieval of appointment data two business days ahead, analyzes patient profiles for critical medical information, and generates actionable lists for healthcare agents.

# Features
1. **Appointment Retrieval**: Automatically fetches appointment data from the EMR for a specified future date.
2. **Insurance and Eligibility Check**: Iterates through each appointment to check the patient's insurance status and eligibility.
3. **Medical Record Collection:** Gathers crucial medical history such as biopsies, blood work, and other clinical procedures from the patient’s last visits.
4. **Document Verification:** Checks for the availability of recent medical reports like blood work and biopsy reports.
5. **Medication Checks:** Reviews the patient's medication for any injectables to ensure availability for upcoming appointments.
6. **List Generation:** Produces several categorized lists for healthcare agents to follow up on, including insurance referral requirements, blood work tracking, and injectable medications.
7. **Data Export:** Saves all processed data into a CSV file in a specified directory for easy access and review.
# Outputs 
The program outputs several CSV files categorized by patient needs and actions required:

1. **Referral List:** All patients requiring insurance referrals.
2. **Lab Report Tracking List:** Patients who need follow-up calls to ensure blood work and biopsy reports are received.
3. **Injectable Medications List:** Ensures all injectables are stocked and available for patients’ appointments.
4. **General Appointment List:** A comprehensive list of all upcoming appointments with detailed patient information for review.
These lists are vital for healthcare agents to prepare for upcoming appointments and ensure all necessary medical documentation and supplies are ready.
