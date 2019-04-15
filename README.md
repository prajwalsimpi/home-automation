# home-automation
Home Automation with Bluetooth and Web Server
Requirements:
1. NodeMCU(esp8266)
2. 5V Relay
3. Jump wires (female to female)
4. Bluetooth HC-05


Connections:
(with Bluetooth HC-05 to NodeMCU)
1.5V    - - -  Vin
2.GND   - - -  GND
3.RX    - - -  TX
4.TX    - - -  RX
(with 5V relay to NodeMCU)
1.Vin   - - -  3v3
2.GND   - - -  GND
3.IN    - - -  D1
(with relay and Appliances)
1.NO    - - -  220V INPUT
2.COM   - - -  TO THE APPLIANCE
