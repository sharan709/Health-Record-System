CareVault – Health Record System
📌 Project Overview
CareVault is a web-based Health Record System designed to help healthcare staff manage patient information in one place.

The system provides a simple dashboard where authorized staff can view patient records, manage appointments, check laboratory results, record vital signs, add clinical notes, and view medications.

Note: This project is a demo system and uses fictional patient data. It should not be used to store real patient information.

🎯 Objectives
The main objectives of CareVault are:

To maintain patient information digitally.

To provide quick access to patient health records.

To manage appointments.

To display laboratory results.

To identify abnormal lab results.

To record patient vital signs.

To maintain medication information.

To add and manage clinical notes.

To provide a simple and user-friendly healthcare dashboard.

👥 Users / Stakeholders
The main stakeholders of the system are:

Doctors – View patient records, laboratory results, medications and clinical notes.

Nurses – Record vital signs and assist with patient information.

Receptionists – Manage appointments and patient registration.

Hospital Administrators – Monitor the overall system and patient information.

Patients – Their health records can be maintained securely by authorized staff.

🛠️ Technologies Used
HTML5 – Creates the structure of the website.

CSS3 – Provides styling, layout, colors and responsive design.

JavaScript – Handles login, navigation, patient data, appointments and interactions.

Session Storage – Maintains the login session during the browser session.

Git & GitHub – Used for version control and project hosting.

🔑 Main Features
1. Staff Login
The system provides a staff login page. Authorized personnel must enter their Staff ID and password before accessing patient records.

2. Dashboard
The dashboard displays:

Total number of patients

Today's appointments

Flagged laboratory results

Active medications

Upcoming appointments

Abnormal lab results

Conditions across patients

3. Patient Management
The Patients section allows staff to:

Search patients

View patient information

Register new patients

View age and gender

View blood group

View allergies

View medical conditions

4. Patient Health Record
Each patient has a detailed record containing:

Patient details

Medical conditions

Allergies

Vital signs

Laboratory results

Medications

Clinical notes

5. Vital Signs
Staff can record:

Blood pressure

Heart rate

Weight

The system displays previous vital measurements for comparison.

6. Laboratory Results
The system displays laboratory test results with:

Test date

Patient name

Test name

Result

Reference range

Normal/Abnormal status

Abnormal results are highlighted for easier identification.

7. Appointment Management
Staff can:

Book appointments

Select patients

Select date and time

Enter visit type

Assign a clinician

Check patients in

Complete appointments

Cancel scheduled appointments

8. Clinical Notes
Healthcare staff can add clinical notes to a patient's record to maintain information about visits and follow-ups.

9. Dark Mode
The system includes a theme button that allows the interface to switch between light and dark themes.

🗂️ Project Structure
CareVault/
│
├── index.html
├── README.md
│
├── style.css
└── script.js
If the project is kept as a single file:

CareVault/
│
├── index.html
└── README.md
🔐 Demo Login
The uploaded demo uses:

Staff ID: 2500090031
Password: 2500090031
The credentials are defined directly in the JavaScript code, so this is not a production authentication system.

📊 Sample Data
The application contains fictional sample patients, including information such as:

Name

Age

Blood group

Allergies

Medical conditions

Vital signs

Laboratory results

Medications

Clinical notes

The project explicitly identifies the data as fictional/demo data.

🔄 How the System Works
Staff Login
     ↓
Dashboard
     ↓
 ┌───────────────┬───────────────┬───────────────┐
 ↓               ↓               ↓
Patients     Appointments    Lab Results
 ↓               ↓               ↓
Patient       Schedule       View Results
Record        Visits         & Status
 ↓
 ┌──────────┬──────────┬────────────┐
 ↓          ↓          ↓
Vitals    Medicines   Notes
▶️ How to Run
Download or clone the project.

Open the project folder in Visual Studio Code.

Open index.html.

Use Live Server in VS Code, or open the HTML file directly in a browser.

Login using the demo credentials.

Explore the Dashboard, Patients, Appointments and Lab Results sections.

⚠️ Limitations
This is a front-end demonstration project.

It does not use a real database.

Patient data is stored only in JavaScript memory.

Login credentials are hard-coded.

It does not provide real healthcare security.

Data can be lost when the page/application is refreshed.

It should not be used for real patient information.

🚀 Future Enhancements
The project can be improved by adding:

MySQL/MongoDB database

Node.js/Express backend

Secure user authentication

Role-based access control

Patient login

Doctor login

Blood bank integration

Prescription management

Medical document upload

Email/SMS appointment notifications

Data backup

Audit logs

Encryption

Cloud deployment

📚 Conclusion
CareVault provides a simple digital platform for managing healthcare records. It demonstrates how HTML, CSS and JavaScript can be combined to create a functional health-record management interface.

The project can be further developed into a complete healthcare management system by adding a backend, database, secure authentication and appropriate privacy/security controls.

