Foureye: Defensive Deception based on Hypergame Theory Against Advanced Persistent Threats

Steps to Execute the Foureye Project:
Prerequisites:
1. WAMP Server installed and running
2. Python 3.6.2 environment set up
3. MySQL configured and accessible

Execution Steps:
->Start WAMP Server
->Ensure the WAMP server is running on your system.
->Navigate to the Foureye Directory
->Open the foureye folder on your system.
->Inside the folder, locate the manage directory.
->In the manage folder, click the search bar, type cmd, and press Enter to open the Command Prompt in this directory.

Access MySQL Console:
->Click on the WAMP icon in the system tray (bottom-right corner).
->Navigate to MySQL and then click on MySQL console. This will open the MySQL console.

Set Up the Database:
->Go back to the foureye folder and open the database directory.
->Copy the SQL code from the provided file in this directory.
->Paste the copied SQL code into the MySQL console and execute it to set up the database.

Run the Django Server:
->Return to the Command Prompt window in the manage folder.
->Run the following command:
              "python manage.py runserver"

Access the Application:
->Copy the link displayed in the Command Prompt (e.g., http://127.0.0.1:8000/).
->Paste the link into a browser (preferably Google Chrome) and press Enter.

Initial Login:
->On the login page, use the following credentials to log in as the first user:
              Username: Admin
              Password: Admin

Register a New User and Login:
->After the initial login, register a new user.
->Use the newly created credentials to log in again.

You can now proceed to predict and analyze threats.
