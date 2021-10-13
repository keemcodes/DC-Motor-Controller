# Bluetooth Steering Project (Early Prototype)
I used a raspberry pi and an l298n to control a DC motor


This project is a prototype steering controller I am making to turn a shaft.

To controller the device via smartphone, I created a react native application utilizing react-native-ble-plx library to control the GPIO pins on the raspberry pi via Bluetooth.

The device is powered by a raspberry pi using nodejs to control the GPIO pins. Using the GPIO pins, I can turn toggle the motor on/off and change it's direction using L298N. (H Bridge Circuit) Using bleno library for nodeJS, I can create a "bluetooth server" to read write requests from smartphone or other bluetooth enabled devices.


##### Hardware: 
Raspberry Pi, L298N Motor Controller w/ a 24v DC Motor+Gearbox

##### Software:
Javascript: NodeJS (Backend), React and React Native (Frontend)
Libraries Used:
bleno (Bluetooth Server Backend)
react-native-ble-plx (Bluetooth Frontend)

##### Goals:
3D Print gearbox enclosure and mounting brackets for the steering device.
Build steering AI
Create a more practical design using micro controller and custom PCB components.


##### Video Demo
https://www.youtube.com/watch?v=OosS0q6igzM
