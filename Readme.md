# ESP8266 Remote Control with WebSocket

This is a fork of m1cr0lab's excellent [tutorial] on ESP32 and Webockets, don't miss it!
It also explains mandatory steps that are not obvious and not covered here (e.g. uploading HTML resources to ESP flash memory).

The fork adapts the project for ESP8266 NodeMCU boards. These boards have an additional LED and button and don't require a breadboard or other hardware to run the example.
It is intended for people who have a ESP8266 NodeMCU board and just want to play with the software part of the project.


Please ignore the `'SPIFFS' is deprecated`message. The example should still work. PlatformIO does not directly support LittleFS at the time of this writing.



[tutorial]: https://m1cr0lab-esp32.github.io/remote-control-with-websocket/