# SimpleDriveInterface

This is a little google drive interface I built a while ago. 

The focus in this software lies in the utilization of AJAX and the Google drive V3 REST API. I tried to stay modern and implement all the backend process into the fronted. 

The software basically enables you to create, delete, copy and download files from your google drive. 
The login process is done by OAuth2. 

The easiest way to start the interface is by running a local HTTPServer. 
For systems resting upon unix, you could simply head to the folder containing the index.html and type the command:

"python -m SimpleHTTPServer 8000"

Then just open a browser of you choice and visit http://localhost:8000/

