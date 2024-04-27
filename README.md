![image](https://github.com/Abdelzero/Automated-Patient-Data-Retrieval-and-Reporting/assets/118099029/4a05d716-cb46-433a-8df1-18b5178d0bf3)# Automated-Patient-Data-Retrieval-and-Reporting
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

# Installation
Install required Python packages:

    pip install -r requirements.txt
# Usage:
To ensure the proper functioning of this script, you will need to configure several key components. Here are the steps to set up the necessary configurations:

1. **Email Credentials:** The script sends all generated lists to a designated email address. You need to set up your email credentials securely within the script. This involves specifying the sender's email address and password. Ensure these credentials are stored securely, and consider using environment variables or a configuration file that is not tracked in your version control system.
2. **EMR System Link:** For security reasons, the link to the EMR (Electronic Medical Records) system is not included in the script. You will need to manually enter the URL of your EMR system in the designated place in the script to enable data fetching.
3. **Website Credentials:** The script accesses an external website that requires authentication. Like your email credentials, you must securely configure the credentials for this website in the script. Use secure storage methods to protect these credentials from unauthorized access.

# Outputs 
The program outputs several CSV files categorized by patient needs and actions required:

1. **Referral List:** All patients requiring insurance referrals.
2. **Lab Report Tracking List:** Patients who need follow-up calls to ensure blood work and biopsy reports are received.
3. **Injectable Medications List:** Ensures all injectables are stocked and available for patients’ appointments.
4. **General Appointment List:** A comprehensive list of all upcoming appointments with detailed patient information for review.
These lists are vital for healthcare agents to prepare for upcoming appointments and ensure all necessary medical documentation and supplies are ready.

# Get Involved
If you are interested in using this script with your own EMR system or if you would like to adapt it for a different setup, we welcome your collaboration. Whether it's extending the current functionalities, adapting to different medical record systems, or improving the security features, your contributions are highly valuable. Please feel free to reach out by creating an issue on our GitHub repository or by contacting us directly via your email. We are excited to see how you implement this system in your environment and look forward to collaborating with you to enhance its capabilities.
