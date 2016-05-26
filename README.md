todo-ng-pouchdb
==========================
to run after clone the repo

sudo npm install -g bower
sudo bower --allow-root  install
cd www/
sudo npm install http-server -g
sudo http-server -p 8080


Android version

However, to run this as a mobile application in Android emulator, do the following to setup :

cd todo-ng-pouchdb

sudo npm install -g cordova ionic gulp

To run in the Android Simulator:

ionic platform add android
ionic build android
ionic emulate android
