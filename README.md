<h1>About the Project</h1>
<p>
This is an IoT-based Fire Alarm System developed using Arduino and GSM technology.
The system continuously monitors fire using an IR Flame Sensor and provides instant alerts.
When fire is detected, the system activates a buzzer and automatically sends an alert SMS
and makes a phone call to the registered owner number for immediate notification.
</p>

<h1>System Components</h1>
<ul>
    <li><strong>Microcontroller:</strong> Arduino UNO</li>
    <li><strong>Sensor:</strong> IR Flame Sensor</li>
    <li><strong>Communication Module:</strong> SIM800L GSM Module</li>
    <li><strong>Alert Device:</strong> Buzzer</li>
    <li><strong>Power Supply:</strong> 18650 3.7V Rechargeable Battery</li>
    <li><strong>Other Components:</strong> Breadboard, Jumper Wires</li>
</ul>

<h1>Project Functionality</h1>
<ul>
    <li>Continuously monitors fire using an IR Flame Sensor</li>
    <li>Detects fire in real time</li>
    <li>Activates buzzer alert when fire is detected</li>
    <li>Sends SMS alert to the owner’s phone number</li>
    <li>Makes an automatic phone call to the owner</li>
    <li>Provides quick response and improved safety</li>
</ul>

<h1>Alert System</h1>
<ul>
    <li><strong>SMS Alert:</strong> Sends a fire warning message to the registered phone number</li>
    <li><strong>Call Alert:</strong> Automatically dials the owner’s phone number</li>
    <li><strong>Buzzer:</strong> Sounds an alarm locally when fire is detected</li>
</ul>

<h1>Technologies Used</h1>
<ul>
    <li><strong>Programming Language:</strong> Embedded C / C++</li>
    <li><strong>Platform:</strong> Arduino</li>
    <li><strong>Communication:</strong> GSM (SIM800L)</li>
    <li><strong>IDE:</strong> Arduino IDE</li>
</ul>

<h1>What Changes Have Been Made</h1>
<ul>
    <li>Added GSM functionality using the SIM800L module</li>
    <li>Configured phone number inside the Arduino code for SMS and call alerts</li>
    <li>Integrated IR Flame Sensor for fire detection</li>
    <li>Added buzzer for local alarm indication</li>
    <li>Implemented automatic SMS and call functionality</li>
</ul>

<h1>Phone Number Configuration</h1>
<ul>
    <li>Open the Arduino code file (.ino)</li>
    <li>Locate the phone number section in the code</li>
    <li>Enter your mobile number in international format</li>
    <li>Example: <strong>+91XXXXXXXXXX</strong></li>
</ul>

<h1>How to Run the Project</h1>
<ul>
    <li>Download and install <strong>Arduino IDE</strong></li>
    <li>Connect Arduino UNO to the computer using USB cable</li>
    <li>Connect all components as per circuit connections</li>
    <li>Insert an active SIM card into the SIM800L module</li>
    <li>Open the project code in Arduino IDE</li>
    <li>Select board: <strong>Arduino UNO</strong></li>
    <li>Select correct COM port</li>
    <li>Upload the code to Arduino</li>
</ul>

<h1>Required Libraries</h1>
<ul>
    <li>SoftwareSerial Library</li>
    <li>Arduino default core libraries</li>
</ul>

<h1>Requirements</h1>
<ul>
    <li>Arduino UNO</li>
    <li>SIM800L GSM Module</li>
    <li>IR Flame Sensor</li>
    <li>Buzzer</li>
    <li>18650 3.7V Rechargeable Battery</li>
    <li>Breadboard and Jumper Wires</li>
    <li>Arduino IDE</li>
</ul>
