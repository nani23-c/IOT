# IOT_project
Indoor Navigation Through Bluetooth Beacons
Overview
Indoor Navigation Through Bluetooth Beacons is an IoT project designed to assist users in navigating indoor spaces using their smartphones. The system utilizes Bluetooth beacons, triangulation, voice commands, and cloud services to provide real-time navigation assistance and route optimization.

Features
Voice Input: Users can input their destination using voice commands.
Voice Output: Navigation instructions are provided through voice output.
Triangulation: The app uses triangulation based on RSSI signals from multiple Bluetooth beacons to determine the user's position.
Route Guidance: The app calculates and displays the distance to the next turn and the final destination.
Cloud Integration: Utilizes Amazon API to store current position and route data, and suggest optimized routes through cloud processing.
Technologies Used
Android Studio: Development environment for building the Android application.
Java: Programming language used for app development.
Google Voice API: Used for integrating voice input and output functionalities.
Bluetooth Beacons: Hardware used for determining user location via RSSI signals.
Amazon API: Used for storing data and optimizing routes through cloud services.
Installation
Clone the Repository

bash
Copy code
git clone https://github.com/your-repo/indoor-navigation.git
Open in Android Studio

Open Android Studio.
Select File -> Open and navigate to the cloned repository directory.
Open the project.
Set Up Bluetooth Beacons

Place Bluetooth beacons at fixed known coordinates within the indoor space.
Ensure each beacon is properly configured to broadcast its signal.
Configure the App

Open app/src/main/java/com/yourpackage/MainActivity.java.
Update the beacon coordinates and other configuration parameters as required.
Configure Amazon API credentials and endpoints in the app for cloud integration.
Build and Run the App

Connect your Android device to the computer.
Click on the Run button in Android Studio to build and deploy the app to your device.
Usage
Start the App

Open the app on your Android device.
Input Destination

Tap the microphone icon and speak your destination.
Navigation

Follow the voice instructions provided by the app.
The app will guide you to your destination using real-time updates based on your current location.
Cloud Integration

The app will store your current position and route data in the cloud using Amazon API.
The cloud service will process the data and suggest optimized routes in real-time.
Code Structure
MainActivity.java: Handles the main logic for voice input/output and triangulation.
BeaconManager.java: Manages Bluetooth beacon interactions and RSSI signal processing.
RouteCalculator.java: Calculates the optimal route based on the user's position and destination.
VoiceService.java: Integrates Google Voice API for handling voice commands and responses.
CloudService.java: Handles interactions with Amazon API for data storage and route optimization.
Contributing
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.


Contact
For any questions or issues, please contact us at tejdeepragala@gmail.com.

