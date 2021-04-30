# Smart-Home-Automation-IOT
In this project uses Arduino Uno and the ESP8266 wifi module to communicate between your arduino board and google assistant.
To communicate ThingSpeak and IFTTT are used to be able to set a command for the equipment to understand and execute the functions.
The Google assistant applet from IFTTT will trigger a web request which will update a field in ThingSpeak cloud.
Then the arduino will read the data from ThingSpeak cloud and will perform the function.
