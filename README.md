<h1>RFID-Based Tracking System</h1>

<p><strong>Project Overview:</strong> <br>
The <strong>RFID-Based Tracking System</strong> is designed to monitor employee attendance and track clothing production in a manufacturing environment. Employees use RFID tags to log their attendance, while RFID-tagged clothing items are tracked through different stages of production. The system provides real-time data on employee working hours and production efficiency.
</p>

<h2>Features</h2>
<ul>
  <li><strong>Employee Attendance Tracking</strong> – Employees scan RFID tags to log <em>login</em> and <em>logout</em> times.</li>
  <li><strong>Clothing Production Monitoring</strong> – Each clothing item has an RFID tag to track its progress.</li>
  <li><strong>Work Assignment</strong> – Employees scan clothing RFID tags to record completed steps in the production process.</li>
  <li><strong>Role-Based Access</strong> – Admins can manage employees and view production data.</li>
  <li><strong>Data Storage</strong> – Uses <strong>MySQL</strong> for efficient record-keeping.</li>
</ul>

<h2>Technology Stack</h2>
<ul>
  <li><strong>Frontend:</strong> React.js</li>
  <li><strong>Backend:</strong> Node.js with Express</li>
  <li><strong>Database:</strong> MySQL</li>
  <li><strong>Hardware:</strong> ESP32/ESP8266 with RFID Scanner</li>
</ul>

<h2>Installation Guide</h2>
<h3>Backend Setup (Node.js)</h3>
<ol>
  <li><strong>Clone the Repository:</strong> 
    <pre><code>git clone https://github.com/PNSSVARDHAN/RFID-Tracking-System.git
cd RFID-Tracking-System/backend</code></pre>
  </li>
  <li><strong>Install Dependencies:</strong> 
    <pre><code>npm install</code></pre>
  </li>
  <li><strong>Set Up Environment Variables:</strong> (Create a <code>.env</code> file and add your MySQL credentials)
    <pre><code>DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=mes</code></pre>
  </li>
  <li><strong>Start the Server:</strong> 
    <pre><code>node server.js</code></pre>
  </li>
</ol>

<h3>Frontend Setup (React.js)</h3>
<ol>
  <li><strong>Navigate to Frontend Folder:</strong> 
    <pre><code>cd ../frontend</code></pre>
  </li>
  <li><strong>Install Dependencies:</strong> 
    <pre><code>npm install</code></pre>
  </li>
  <li><strong>Start React App:</strong> 
    <pre><code>npm start</code></pre>
  </li>
</ol>

<h3>ESP32/ESP8266 Setup</h3>
<ol>
  <li>Connect RFID scanner to ESP32.</li>
  <li>Upload firmware to ESP using Arduino IDE.</li>
  <li>Ensure the device sends RFID data to the Node.js backend.</li>
</ol>

<h2>Usage Instructions</h2>
<ul>
  <li><strong>Employee Panel:</strong> Employees scan RFID tags for login/logout.</li>
  <li><strong>Production Tracking:</strong> Workers scan clothing RFID tags to update step completion.</li>
  <li><strong>Admin Dashboard:</strong> Monitor attendance and production status in real time.</li>
</ul>

<h2>Future Enhancements</h2>
<ul>
  <li>Integration with a Mobile App</li>
  <li>Advanced Production Analytics</li>
  <li>Automated Payroll Calculation</li>
</ul>

<h2>Contributing</h2>
<p>If you’d like to contribute, feel free to fork the repository and submit a pull request.</p>

<h2>License</h2>
<p>This project is open-source under the <strong>MIT License</strong>.</p>
