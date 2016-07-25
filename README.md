# omega_garage

A node js application that can control your garage door(s).

This app uses a configuration file to define pins, the name of the garage door that the pin corresponds with, and a sensor pin for the magnetic proximity sensor.

Mainly designed for use with two wire garage door openers.

#To Run:
1.Install node
'''
opkg update
opkg install node
'''
2. You must get a copy of express for node. Follow the instructions in the guide here: https://community.onion.io/topic/855/nodejs-express-http-server/2

3.Get to the root directory of this project and type node omega_garageServer.js 
