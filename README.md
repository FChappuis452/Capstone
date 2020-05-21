# Capstone
Weeping Angels Capstone Project <br/>
This project is my 2020 final SET capstone project. It consist of a set of software application (toolkit) that enables a user 
to create a VR world based on an open street map selection and placing points of interest along with 3D buildings. This project was done in collaboration with three other team members. The idea behind this project was to be able to give virtual guided historical tours of cities.

Mapping<br/>
This is the main application of our toolkit.  This allows you to select a section of a map using the Open Street Map API.  From there it will save the information to a database and allow you to launch other applications to over imposed a map and place points of interest and 3D models. It will also allow you to place points of interests on top of the map.

Historical Map Config Tool<br/>
This Unity application allows the user to position a map on top of the selected open street map selection.

ModelConfigTool<br/>
This Unity application allows the user to place 3D models on top of the map selection.

Paris VR Wiki<br/>
This is our wiki website code.  It is a basic HTML/CSS/Javascript static pages

VR2-2018<br/>
This is the main VR application.  This application will reach out to the database and retrieved all the information previously entered
in the Mapping app.  It will then generate the 3D world with all the added models and points of interests.

api<br/>
This is a Flask/SQLAlchemy REST API to handle the communication between the database and various apps in the toolkit. 
