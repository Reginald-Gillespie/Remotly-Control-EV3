# Remote-Control-EV3-JAVA
## WIP: Control Lego Mindstorms EV3 remotely. 

Once I am done (and who knows when that will be) I plan to upload my code to this repository. 

The basic concept is I am running a micropython webserver on the EV3, since python is the esiest thing to get on it, and I am building a java wrapper which connects and talks to the python server. You tell the EV3 where to go via java, and the python moves it there. This allows all the hard processing to be done on your computer, allowing for much more power than the EV3 has to offer. For example you could get a remote camera, put it on the EV3, and have the computer run an AI to process where you are. 
