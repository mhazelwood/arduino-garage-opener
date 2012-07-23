arduino-garage-opener
=====================

My [Arduino](http://www.arduino.cc/)-based garage door opener allows me to control my garage door from my iPhone and to check whether the garage doors are open or closed.  It makes use of the [Teleduino](http://www.teleduino.org/) service which allows me to control my garage doors from anywhere in the world as long as I have internet access.  

For security reasons the Teleduino API key is not included in the source.  Instead it is prompted for and stored in a cookie. 

More information to come. For now, here are some pictures.

I created an [iPhone web app](http://www.apple.com/webapps/whatarewebapps.html) to control the garage doors using [jQuery](http://jquery.com/).  The images change to show whether each door is open or closed.  The top one is for the large (2 car) garage door, and the bottom one is for the small (1 car) garage.
![Screenshot](https://github.com/downloads/mhazelwood/arduino-garage-opener/iPhoneScreenshot.png)

Top view of the protoboard.  Two blue relays are used to activate the garage door openers.  Two push buttons also activate the openers and were used to test the wiring.  The green wires go to a reset switch on the outside of the box.
![Screenshot](https://github.com/downloads/mhazelwood/arduino-garage-opener/InsideBox.JPG)

Protoboard on an [Arduino Ethernet Shield](http://arduino.cc/en/Main/ArduinoEthernetShield) on an [Arduino Uno](http://arduino.cc/en/Main/ArduinoBoardUno).
![Screenshot](https://github.com/downloads/mhazelwood/arduino-garage-opener/SideView.JPG)

Reset button, green LED (for Teleduino status), yellow LED (shows closed switch for large garage door) and red LED (shows closed switch for small garage door). Also a buzzer on the side which for now is just for fun, but I plan to have it buzz as a warning that the door is about to be remotely activated.
![Screenshot](https://github.com/downloads/mhazelwood/arduino-garage-opener/OutsideBox.JPG)

Finished installation mounted on top of one of the garage door openers using two sided tape.
![Screenshot](https://github.com/downloads/mhazelwood/arduino-garage-opener/FinishedInstall.JPG)

Schematic diagram of this project created using [OmniGraffle](http://www.omnigroup.com/products/omnigraffle/).
![Screenshot](https://github.com/downloads/mhazelwood/arduino-garage-opener/Schematic.png)

