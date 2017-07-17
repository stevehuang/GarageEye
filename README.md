GarageEye
=========

Yes! Another raspberry-pi project to control a garage door using machine learning, webcam, and python2.7

Need following packages/apps
============================
1. py-dev (sudo apt-get install python-dev)
2. scipy  (see www.scipy.org/install.html)
3. numpy  (see www.scipy.org/install.html)
4. fswebcam
5. eventlet (pip install eventlet)

Getting Started 
=============== 
1. clone git repository 
2. in the working folder, fill in the parameters listed in the comments of
garageCam.conf 
3. to launch, go to your working folder, then run
python garage_eye.py --config_file <full working directory>/garageCam.conf
