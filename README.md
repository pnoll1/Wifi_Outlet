# Wifi_Outlet
Plug-in wifi outlet that ensures security by communicating via your router using it's built in encryption and by only communicating with the server of your choice.  The server could be a Raspberry pi running apache in your home or a VPS etc.
Outlets are controlled via a responsive website hosted on your server.  
## Hardware
- ESP8266(ESP) microcontroller
- 5VDC/1W min powersupply
- NEMA 1-15P plug
- NEMA 5-15 receptacle
- 3.3VDC voltage regulator
- Relay, PCB, 3VDC activation, 10A,110VAC
- PCB Protoboard
- 3D printed PLA case
## Software
### Option A
- server written using ESP8266WiFi library hosted on ESP
- webpage written using BASE framework with google analytics removed hosted on computer with server software installed
### Option B
- use openHAB
