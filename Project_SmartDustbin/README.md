# Project Smart Dustbin
In order to find out if the dustin is filled or not, we can use various sort of sensors such as IR sensor, Ultrasonic Sensor and Weight sensors. In the project, the sensor used is Ultrasonic sensor.

Some of the other instrumentation utilized in the project is Arduino, Jumper wires(male and female), GSM/ESP 8266(Wi-Fi module), Battery*, Dust Bin, Arduino holder, etc.

We have placed the ultrasonic sensor on the top of dustbin where the ultrasonic waves can interact to the garbage inside the dustbin.

The ultrasonic sensor will send data and tell the Arduino regarding the amount oof garbage in the dustbin.

And the Arduino will upload the data captured by Ultrasonic Sensor to Firebase which is an Data storage for our Android application.

Android application will fetch the data uploaded by ultrasonic sensor from our data storage that is Firebase.

The concern person would be having the application to see the data sent by ultrasonic sensor.

Though the person would know when to change or clear the dustbin.


