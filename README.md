# Fast-Arduino-Local-WiFi-LED-Control
Very fast arduino LED control through local wifi and the capacitive portal.

# WifiLEDRemote
This is a piece of arduino code which will control the typical RGB LED strand through a WiFi capable board. My prefered board is the Esp8266 nodemcu. 

## What makes this different?
Most WiFi hosted code on arduino involves the same few steps. Arduino board hosts a WiFi network, user connects to network with their phone or laptop, user navigates to a local webpage. In my experience many devices have trouble connecting to the local WiFi network. This LED controller uses the Capacitive Portal instead of a webpage. A capacitive portal is the place where you accept terms and services for starbucks or most other free wifi networks. I have found the capacitive portal is very fast and works on most devices. 

## Hardware
My tried and true board is the ESP8266, however this should also work with the ESP32. FASTLed is a library available on anyboard. If you found a substitute for the WiFi library then any arduino should work. 

