# json-sever

#Setting up a Server using json-server

#Objectives and Outcomes
The Node module, json-server, provides a very simple way to set up a web server that supports a full-fledged REST API server. It can also serve up static web content from a folder. This lesson will leverage these two features to provide the back-end for your React application. In this exercise, you will configure and start a server using json-server to enable serving your application data to your Angular application. At the end of this exercise, you will be able to:
•	Configure and start a simple server using the json-server module
•	Configure your server to serve up static web content stored in a folder named public.

#Installing json-server
•	json-server is a node module, and hence can be installed globally by typing the following at the command prompt:
  
  npm install json-server -g
  
#If you are using OSX or Linux, use sudo at the front of the command. 
#This will install json-server that can be started from the command line from any folder on your computer.

#Configuring the Server
•	At any convenient location on your computer, create a new folder named json-server, and move to this folder.
•	Download the db.json file provided above to this folder.
•	Move to this folder in your terminal window, and type the following at the command prompt to start the server:

  json-server --watch db.json -p 3001 -d 2000
  
  •	This should start up a server at port number 3001 on your machine. 
  The data from this server can be accessed by typing the following addresses into your browser address bar:
