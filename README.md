Intrusion Detection Dashboard
Project Overview
The Intrusion Detection Dashboard is an interactive system for monitoring and analyzing network traffic, specifically designed to detect potential intrusions in real-time. This project is part of a comprehensive SOC Analyst Projects Directory aimed at building hands-on skills in security operations, network monitoring, and incident response.

Table of Contents
Description
Prerequisites
Installation
Technologies Used
Project Setup
Folder Structure
What I Learned
Support & Feedback
Follow Me
Description
SOC Analyst Projects Directory is a curated collection of 15 projects designed to develop key skills in network monitoring, threat detection, and incident response. Each project uses Python and security-focused technologies alongside Vue.js for frontend interactivity.

This Intrusion Detection Dashboard leverages:

Flask for the backend API
Scapy for real-time packet analysis
Vue.js for a user-friendly dashboard displaying network alerts and statistics.
Prerequisites
Ensure the following dependencies are installed:

Python (3.7 or higher)
Flask for the backend API
Vue.js for the frontend interface
Scapy for packet analysis
Node.js and npm to handle frontend dependencies
You can install Flask and Scapy with:

bash
Copy code
pip install Flask scapy
For Vue.js, install via npm:

bash
Copy code
npm install vue
Or follow the Vue.js official installation guide.

Installation
1. Clone the Repository
Clone the project repository to your local machine:

bash
Copy code
git clone https://github.com/yourusername/Intrusion-Detection-Dashboard.git
cd Intrusion-Detection-Dashboard
2. Set Up a Virtual Environment
Set up a virtual environment to manage Python dependencies locally:

bash
Copy code
python3 -m venv venv
Activate the virtual environment:

macOS/Linux:
bash
Copy code
source venv/bin/activate
Windows:
bash
Copy code
venv\Scripts\activate
3. Install Backend Dependencies
With the virtual environment activated, install the necessary packages:

bash
Copy code
pip install -r requirements.txt
4. Install Frontend Dependencies
Navigate to the frontend directory and install Vue dependencies:

bash
Copy code
cd frontend
npm install
5. Run the Application
Start the backend Flask server (inside the virtual environment):

bash
Copy code
python app.py
Then, start the Vue.js development server in the frontend directory:

bash
Copy code
npm run serve
Technologies Used
Flask: A lightweight web framework for building the backend API.
Why Flask? Flask is fast and easy to set up, ideal for handling backend API requests in smaller projects.
Scapy: A Python library for network packet manipulation and analysis.
Why Scapy? It enables real-time packet analysis, essential for detecting unusual network traffic patterns.
Vue.js: A JavaScript framework for creating responsive user interfaces.
Why Vue.js? Vue is beginner-friendly and ideal for building dynamic, interactive dashboards.
Project Setup
To get started, create the main project folder and navigate into it:

bash
Copy code
mkdir intrusion_detection_dashboard
cd intrusion_detection_dashboard
Follow the steps in the Installation section to complete setup.

Folder Structure
This project’s structure is as follows:

plaintext
Copy code
intrusion_detection_dashboard/
├── frontend/              # Vue.js files for the dashboard interface
├── backend/               # Flask app for handling requests
├── venv/                  # Virtual environment files
├── README.md              # Project README file
└── requirements.txt       # Dependencies for Flask and Scapy
What I Learned
This project provided valuable experience with:

Data Analysis: Analyzing network traffic for detecting threats.
Real-Time Alerts: Setting up alerts to notify of potential intrusions.
Frontend-Backend Integration: Combining Flask with Vue.js for a responsive, interactive dashboard.
Support & Feedback
If you found this project helpful, please consider providing feedback to support my journey as a SOC analyst and full-stack developer.

Follow Me
Stay updated on my projects by following me on:

LinkedIn
Twitter
