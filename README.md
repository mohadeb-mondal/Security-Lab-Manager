# CTF-scoreboard
This is my senior project at the University of Evansville.  This application is meant to be easily run by educators and enthusiasts to learn security.  Users can launch security exercises.  If they complete the exercise, they can submit their unique value to the application.  Administrators can login to see if users completed their exercises.

# How can I run this?
This system can be run on both Centos7(ubuntu coming soon) and Windows because of docker!  If you run on windows, make sure docker for windows is installed: https://docs.docker.com/docker-for-windows/install/ . Also make sure that you meet all requirements.  If you run on linux, you are all good to go!  My build script installs docker for you.

1. run "git clone https://github.com/so87/Security-Lab-Manager.git"
2. run "build-windows.bat" or "build-linux.sh" depending on whether you are linux or windows
3. if you need to stop or stop run "start-stop-windows.bat" or "start-stop-linux.sh" and that's it!
