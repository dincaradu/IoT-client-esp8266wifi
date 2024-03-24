# IoT client built with ESP8266WiFi

Boilerplate repository for projects built with ESP8266WiFi that require connection to WiFi and to a server through WebSockets.


## Functionalities

- You can upload a new sketch Over The Air
- Acts as a WiFi Access Point for setting up WiFi credentials through a webpage accessible at 10.1.1.1
- Connects to the WiFi network
- Connects through WebSockets and emits a keep_alive event to a server at regular intervals
  (Please note that it uses WebSockets v2 and is not compatible with the more recent versions 3 or 4. Sample server code here: https://github.com/dincaradu/IoT-server-nestjs)


## Board, Sensors, and other attachments

- ESP8266WiFi



## Other required components

- Power source for the ESP board

Hope it helps! Have fun!
