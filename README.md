###  Publishing the Color Sensor data to the IBM Bluemix from the Arduino Uno Microcontroller

This blog is about connecting the Color Sensor (TCS3200) to the Arduino IDE and publishing the data to the IBM Bluemix IoT Watson platform.

The Color sensor is a small hardware programmable device capable of detecting Red, Green, Blue color and other shades as well.

This device can be programmed from the Arduino IDE or any other microcontroller.

To connect the device to the Arduino IDE:

###### Pin connections from Color Sensor to Arduino:
Connect the
S0,S1, S2 and S3 of Color sensor to Pin 4, 5,6 and 7.
OUT pin to Pin 8
LED and Vcc to Vcc of the Arduino.


At this point, I have assumed that the Arduino Uno is registered with the IBM Bluemix IoT platform, without which the publishing of the data cannot happen.

The Arduino Uno has to be connected to the Ethernet shield in order to publish the data.

The data Visualization can be thru a Node.js Visualization code and can be launched both on the Bluemix, and your laptop.

   https://console.ng.bluemix.net/docs/services/IoT/visualizingdata_sample.html

To start the visualization app :  node app.js


![alt tag](https://cloud.githubusercontent.com/assets/14288989/18639732/ae4d80d8-7eb2-11e6-8a44-e092f57fc7aa.png)

![alt tag](https://cloud.githubusercontent.com/assets/14288989/18639747/ba24fb7a-7eb2-11e6-9675-dba745eb2128.png)
![alt tag](https://cloud.githubusercontent.com/assets/14288989/18658837/db967a1a-7f23-11e6-8bff-104dfcdd7fe6.jpg)
![alt tag](https://cloud.githubusercontent.com/assets/14288989/18658841/e5c46fa6-7f23-11e6-8856-7a4b7c3be972.jpg)

