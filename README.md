# Intrusion Detection Dashboard

This project is an **Intrusion Detection Dashboard** that uses **Flask** for the backend and **Scapy** for network packet analysis. We’re also building a **Vue.js** frontend (to be added later) to display real-time alerts and network traffic data. This project demonstrates essential skills for a SOC (Security Operations Center) analyst and a full-stack web developer.

## Project Setup

### 1. Setting Up the Project Folder
```bash
mkdir intrusion_detection_dashboard
cd intrusion_detection_dashboard
mkdir intrusion_detection_dashboard: Creates a folder named intrusion_detection_dashboard.
cd intrusion_detection_dashboard: Changes the directory to the project folder.
2. Creating a Virtual Environment
A virtual environment isolates our dependencies for this project.

bash
Copy code
python3 -m venv venv
python3 -m venv venv: Creates a virtual environment named venv.
3. Activating the Virtual Environment
macOS/Linux:
bash
Copy code
source venv/bin/activate
Windows:
bash
Copy code
venv\Scripts\activate
Once activated, your terminal will show (venv) before each prompt.

4. Installing Dependencies
We’re using Flask for the backend and Scapy for network packet analysis.

bash
Copy code
