IoT Biometric Attendance System & Alcohol Detector:

Overview:

This project integrates IoT technology with biometric fingerprint sensors to create an attendance system that stores records in Google Drive. Additionally, the project includes an alcohol detection sensor to monitor and log alcohol levels for safety purposes.

Features

Fingerprint Attendance System: Uses a biometric fingerprint sensor to record attendance.

Google Drive Integration: Stores attendance data securely in Google Drive.

Alcohol Detection System: Monitors alcohol levels using a dedicated sensor.

IoT-Based: Enables remote monitoring and data storage.

Components Used

Microcontroller: ESP8266/ESP32/Arduino (as per project requirement)

Fingerprint Sensor: R305/GT511C3 (or similar)

Alcohol Sensor: MQ-3/MQ-135

Cloud Storage: Google Drive API integration

Other Components: Jumper wires, power supply, resistors, etc.

How It Works

Biometric Attendance System:

A user places their finger on the biometric fingerprint sensor.

The microcontroller verifies the fingerprint.

If authenticated, the attendance is recorded.

The attendance data is uploaded to Google Drive.

Alcohol Detector System:

The alcohol sensor detects alcohol levels in the surrounding environment.

If the alcohol concentration exceeds a predefined threshold, an alert is triggered.

The data can be logged for further analysis.

Installation & Setup

Hardware Setup:

Connect the fingerprint sensor to the microcontroller.

Connect the alcohol sensor to the microcontroller.

Ensure proper power supply and connections.

Software Setup:

Install the required libraries:

Arduino IDE: Install Fingerprint Sensor Library, Google Drive API Library

Configure the Google Drive API for data storage.

Upload the firmware to the microcontroller.

Test the system by registering fingerprints and detecting alcohol levels.

Usage

Attendance Management: Place your finger on the sensor to mark attendance.

Alcohol Monitoring: The sensor continuously monitors alcohol levels and triggers an alert if needed.

Future Enhancements

Adding facial recognition for additional authentication.

Integrating an SMS alert system for alcohol detection.

Expanding cloud storage options beyond Google Drive.

Contributing

Feel free to contribute by submitting issues or pull requests.

License

This project is open-source and available under the MIT License.
