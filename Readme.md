Clariyo 🚨
Your personal emergency alert and rescue assistant.

📝 Overview
Clariyo is a lifesaving application designed for individuals who frequently experience medical emergencies such as fainting, epilepsy episodes, anemia-related collapses, or other similar conditions. It ensures timely assistance by instantly alerting guardians or emergency contacts with critical information. With features like real-time fall detection, medical condition tracking, and location-based notifications, Clariyo offers peace of mind and safety.

🎯 Features
User Registration: Securely store user and guardian information using SQLite.
Emergency Alerts: Trigger alerts to guardians via SMS using the Twilio API.
Location Sharing: Automatically send the user’s location during emergencies.
Keyboard Shortcut: Quickly trigger an alert with a Ctrl + P shortcut for rapid assistance.
🛠️ Tech Stack
Framework: Kivy (Python)
Database: SQLite
API Integration: Twilio API
Geolocation: Geocoder
🚀 Getting Started
Prerequisites
Python 3.8 or higher
Twilio API credentials (Account SID, Auth Token, and Phone Number)
Installation
Clone the repository:
git clone https://github.com/YourUsername/Clariyo.git  
Navigate to the project directory:
cd Clariyo  
Install dependencies:
pip install kivy twilio geocoder  
Database Setup
The SQLite database will be automatically created and initialized when the app runs for the first time.

Environment Variables
Update the Twilio configuration in the code:

TWILIO_SID = '<Your Twilio SID>'  
TWILIO_AUTH_TOKEN = '<Your Twilio Auth Token>'  
TWILIO_PHONE_NUMBER = '<Your Twilio Phone Number>'  
Run the Application
Start the app by running:

python main.py  
🎮 Usage
Sign Up: Enter user details, including guardian contact information.
Profile View: See user information and trigger alerts manually.
Trigger Emergency Alert: Use the button in the app or press Ctrl + P to send an emergency SMS with location details to the registered guardian.
🙌 Acknowledgments
Kivy Framework for providing an intuitive user interface.
Twilio API for reliable SMS alerts.
Geocoder for location tracking.
About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 1 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
Python
100.0%
Footer
© 
