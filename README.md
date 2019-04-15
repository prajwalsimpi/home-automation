# home-automation
Home Automation with Bluetooth and Web Server
Requirements:
1. NodeMCU(esp8266)
2. 5V Relay
3. Jump wires (female to female)
4. Bluetooth HC-05


Connections:
(with Bluetooth HC-05 to NodeMCU)
5V    - - -  Vin
GND   - - -  GND
RX    - - -  TX
TX    - - -  RX
(with 5V relay to NodeMCU)
Vin   - - -  3v3
GND   - - -  GND
IN    - - -  D1
(with relay and Appliances)
NO    - - -  220V INPUT
COM   - - -  TO THE APPLIANCE
