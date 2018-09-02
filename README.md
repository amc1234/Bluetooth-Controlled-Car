# Bluetooth-Controlled-Car
A small 6 inch x 3 inch x 2.5 inch car controlled through a bluetooth module and a phone application.

Uses an Arduino Uno as well as an HC-05 bluetooth module.
Had a manual switch to reverse the direction of motion however, that has since been removed and now contains a self implemented H-bridge.
The gears and mechanical side of the car were all hand-built including the steering mechanism. 

Bluetooth and application implementation are fully functioning. It uses the analog pins on the Arduino Uno board so the car can move forwards and backwards at varying speeds. All of which are controlled by the HC-05 and Ardroid phone application.

Currently working on being able to crontrol the steering mechanism using bluetooth.

Phone application and template code by: Anurag Goel
