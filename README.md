![SpaceX Logo](/client/src/logo.PNG)

# Installation
Begin by installing [Node.js](https://nodejs.org/en/download/)
Once installed, download the project.

# Quick Start
After the project is downloaded, begin opening your terminal and changing your
directory to the project directory

`cd /SpaceX_launch_app-master`

Next, install all the dependencies listed in package.json to the server.

`npm install`

After that, change directory into the client folder and install all the 
dependencies listed in package.json to the client

`cd /client`
`npm install`

Due to an error in the concurrently script, you must run **two terminals** to 
run this application. One for the server, and one for the client. On one terminal enter: 

`npm start`

This will iniate the server on port 5000. To iniate the client, on the other terminal enter:

`npm run client`

This will iniate the client on port 3000.

# Viewing the Application
Once you are all up and running, visit the [localhost:3000 port.](https://localhost:3000)
This will redirect to the front page of the application and
all launch data queried from SpaceX will be displayed.