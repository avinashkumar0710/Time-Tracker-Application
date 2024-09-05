# Time-Tracker-Application
Time Tracker Application

Time Tracker Application
This Time Tracker application helps users track their work hours efficiently, providing a user-friendly interface to log in and out times, and automate the process of locking the system at the end of work hours. Designed with flexibility, the app allows users to set specific work periods, and the in-time can only be selected within a predefined range, ensuring accurate time tracking.

The app runs in the background and offers features like time selection, automatic system locking, and a confirmation mechanism to lock the PC when the work period ends.

Key Features
Automated Time Tracking: Set your in-time between 9 AM and 10 AM and let the system track your work hours automatically.
Automatic PC Locking: Ensures that the PC is locked automatically when the work period ends if the user opts for it.
User-Friendly Interface: Simple time selector and confirmation mechanism for locking the PC, reducing manual intervention.
Real-Time Updates: Continuously updates the remaining work time and ensures accurate out-time reflection.
Background Operation: Runs seamlessly in the background without disrupting ongoing tasks.
Technologies Used
Languages: Python, PowerShell
Database: SQL Server
Other Tools: Windows Scheduler, Git
How It Works
The app initiates a timer when the user sets the in-time. The system tracks this period, and when the out-time is reached, the PC automatically locks if the user has opted for this feature. The system leverages Windows PowerShell scripts running in the background to execute the automatic locking process without manual intervention.

#Installation and Setup
1. Download the Project.
2. Run the application: python3 widget.py


   Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

This description reflects the key components of your time tracker app, focusing on automation and background execution. Let me know if you need further adjustments!



NOTE: * install in terminal: pip install pyinstaller and pip install pytz * 
