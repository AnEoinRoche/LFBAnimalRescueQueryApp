# LFBAnimalRescueQueryApp

To run this application:

-Assuming you have JAVA_HOME defined.

-In CMD, navigate to the directory "apache-jena-fuseki-3.13.1"

-Run "fuseki-server --file ../Application/output.ttl"

-The server should be located at localhost:3030/LFB, but depending on your port settings in may be different

-Open the Frontend html file in a browser

To change where the app is sending queries:

-Open the frontend html file in a text editor

-Under the 'script' tag which defines the variable 'yasqe', change the option endpoint to whatever URL is listed in the terminal 