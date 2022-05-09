# UltrasonicTankSensor
Fred has another implementation of an ultrasonic tank sensor with him SensESP  and a Wemos D1 mini.
The Ultrasonic sensor DS1603L detects liquid levels in a tank and provides the corresponding measured values via SensESP via WiFi SignalK.
SensESP is a software framework for the Arduino IDE with which different sensors can be easily integrated into SignalK. 
The special thing about SensESP is that sensors can be docked in SignalK without a network configuration. 
A SignalK server is automatically recognized by SensESP and the network configuration for data transmission via WiFi is carried out independently.
The level can be visualized in SignalK.

Due to the properties of the sensor, there is no need to drill a hole in the tank, which is why this sensor can be used as a retrofit solution for existing tanks without a level indicator.
Thanks to the WLAN connection, no further data cables need to be laid; a 12V supply near the tank to which the microcontroller can be connected is sufficient. 
The Wemos D1 mini pro module is a microcontroller based on the ESP 8266 with built-in WLAN module. 
The ultrasonic sensor is connected to the microcontroller. 
The ultrasonic sensor is glued to the outside of the tank bottom. The liquid level in the tank can then be recorded.

Caution: The sensor must be attached to the bottom of the tank, so it must "ping" from bottom to top in order to record the liquid level.
"Pinging" from top to bottom does not work.

From: https://open-boat-projects.org/en/ultraschall-tanksensor-mit-sensesp/
