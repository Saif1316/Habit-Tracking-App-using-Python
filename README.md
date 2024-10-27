# Habit-Tracking-App-using-Python
"Automated cycling distance tracking using Pixela API with options for daily logging, updating, and deletion of data points."

This project automates tracking of daily cycling distances using the Pixela API. It allows users to create, update, and delete daily cycling data points on a visually interactive graph.

Table of Contents
About
Getting Started
Prerequisites
Installation
Usage
Creating a User
Creating a Graph
Logging Daily Data
Updating a Data Point
Deleting a Data Point
Acknowledgments
About
This Cycling Distance Tracker project leverages the Pixela API to log and visualize daily cycling distances. Users can input their daily distance, see it displayed on a graph, and update or delete entries as needed. This setup is ideal for tracking cycling goals and progress over time.

Getting Started
Prerequisites
Python 3.x
requests library (install with pip install requests)
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/USERNAME/REPOSITORY_NAME.git
Navigate into the project directory:
bash
Copy code
cd REPOSITORY_NAME
Usage
Creating a User
To register a new Pixela user, configure the USERNAME and TOKEN variables and then uncomment the code section under User Creation in the script:

python
Copy code
USERNAME = "your_username"
TOKEN = "your_secret_token"
Run the code to send a POST request to Pixela and create your user.

Creating a Graph
Once the user is registered, create a new graph by uncommenting the Graph Creation section in the script. Update the graph configuration as needed (e.g., name, unit, and color). Running this section will create a new graph to display your cycling data.

Logging Daily Data
To log your daily cycling distance:

Run the script.
Enter the number of kilometers you cycled when prompted.
The data will be sent to Pixela and added to your graph.
Updating a Data Point
To update a specific day’s data:

Uncomment the Pixel Update section in the script.
Set the desired quantity for the new cycling distance.
Run the script to update the data point.
Deleting a Data Point
To delete a specific day’s data:

Uncomment the Pixel Deletion section in the script.
Run the script to delete the entry for today’s date.
Acknowledgments
Pixela API: For providing the API used to track and visualize daily progress.
