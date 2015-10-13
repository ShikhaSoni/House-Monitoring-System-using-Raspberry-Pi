# House-Monitoring-System-using-Raspberry-Pi 
The project contains two files,
1. MyApplication
2. PervasiveCourse_student

The first file is the android client which is an android project. It can be imported into android studio as a project and, installed on any android phone. We have also included the apk file which can be installed on any android phone.

The second file is the server that works on Raspberry pi. Load the PervasiveCourse_student on Raspberry Pi by either rsync or copying the project into pri remotely. 
To start the project 
1. open the console in the directory on the Pi, 'ant build' will compile the files
2. 'sudo ant JSONRPCServer' will bring up the server active.
3. Install the Android application on your android phone and send a request to the server.

The android application UI has one activity. The first part of the activity shows the current temperature and ambient of the room. The history of the room temperatur is also stored at the bottom of the same page. 
The second page of this activity is meant to set and delete rules.