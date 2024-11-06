<h1>Intrusion Detection Dashboard</h1>

<h3>Description</h3>
<p><strong>Intrusion Detection Dashboard</strong> is a Flask-based web application designed to monitor network traffic for suspicious activity. Using Scapy for packet analysis, this application serves as an educational tool for SOC analysts to detect and log potential intrusions.</p>

<h3>Prerequisites</h3>
<p>To run this project, make sure you have Python, Flask, and Scapy installed on your system.</p>
<ul>
    <li><strong>Install Flask and Scapy</strong>: Run the following command to install both:
        <pre><code>pip install Flask scapy</code></pre>
    </li>
</ul>

<h3>Installation</h3>
<ol>
    <li><strong>Step 1: Clone the Repository</strong>
        <ul>
            <li>Clone the repository to your local machine:</li>
            <pre><code>git clone https://github.com/yourusername/Intrusion-Detection-Dashboard.git</code></pre>
            <li>Navigate into the project directory:</li>
            <pre><code>cd Intrusion-Detection-Dashboard</code></pre>
        </ul>
    </li>
    <li><strong>Step 2: Start the Flask Server</strong>
        <ul>
            <li>Activate the virtual environment:</li>
            <pre><code>source venv/bin/activate</code></pre>
            <li>Run the application with:</li>
            <pre><code>python app.py</code></pre>
            <li>Once the server is running, open your browser and navigate to <a href="http://127.0.0.1:5000/" target="_blank">http://127.0.0.1:5000/</a>.</li>
        </ul>
    </li>
</ol>

<h3>Features</h3>
<ul>
    <li><strong>Real-Time Monitoring</strong>: Tracks network packets to detect suspicious activity.</li>
    <li><strong>Simple Setup</strong>: Easy-to-run Flask server with Scapy integration for packet analysis.</li>
    <li><strong>Modular Design</strong>: Allows for future expansion to include a Vue.js frontend for visualization.</li>
</ul>

<h3>Code Overview</h3>

<h4>Flask Backend</h4>
<p>The Flask backend, defined in <code>app.py</code>, sets up the server and initial route for our dashboard.</p>

<pre><code>from flask import Flask

app = Flask(__name__)

@app.route('/')
def home():
    return "Intrusion Detection Dashboard is Running"

if __name__ == '__main__':
    app.run(debug=True)
</code></pre>

<p><strong>Explanation:</strong></p>
<ul>
    <li><strong>Flask Initialization</strong>: Sets up the Flask app instance to serve requests.</li>
    <li><strong>Route Definition</strong>: Defines the <code>/</code> route, which displays a message confirming the app is running.</li>
    <li><strong>Debug Mode</strong>: Enables <code>debug=True</code> for easier troubleshooting and automatic reloading during development.</li>
</ul>

<h4>Future Frontend</h4>
<p>Planned Vue.js frontend will visualize network traffic data in real time, with interactive charts and alerts.</p>

---

<h3>Usage</h3>
<p>To run the application locally, activate the virtual environment and start the Flask server.</p>

<h4>Example Request</h4>
<pre><code>curl http://127.0.0.1:5000/</code></pre>

<h4>Example Response</h4>
<pre><code>Intrusion Detection Dashboard is Running</code></pre>

---

<h3>What I Learned</h3>
<ul>
    <li><strong>Setting Up Flask</strong>: Initialized a Flask app, created routes, and handled responses.</li>
    <li><strong>Organizing Virtual Environments</strong>: Created and activated a virtual environment to manage dependencies for the project.</li>
    <li><strong>Scapy Basics</strong>: Scapy will allow packet capture and analysis for monitoring network activity.</li>
</ul>

<h3>Future Plans</h3>
<ul>
    <li>Vue.js Frontend: Build an interactive frontend with real-time data visualization.</li>
    <li>Enhanced Packet Analysis: Integrate Scapy to capture and flag suspicious network packets.</li>
    <li>Alert Notifications: Implement alerts for detected intrusions via email or SMS.</li>
</ul>

<h3>Support & Feedback</h3>
<p>If you found this project helpful or have suggestions, please reach out to help support my journey as a Python and Flask developer!</p>

<p><a href="https://x.com/kelvinintech" target="_blank" style="text-decoration: none;">
   <button style="background-color: #1DA1F2; color: white; border: none; padding: 10px 20px; font-size: 16px; border-radius: 5px;">
       Follow Me on X
   </button>
</a></p>
