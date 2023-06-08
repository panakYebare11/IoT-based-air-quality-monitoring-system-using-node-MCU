# IoT-based-air-quality-monitoring-system-using-node-MCU
This project will help us in monitoring of the surrounding air quality.
We require MQ135 gas sensor which is useful in greenhouse gases detection like CO2 and NO2 and NODE MCU ,2X16 LCD display, breadboard ,jumper cablws.
Node Mcu is a decision taking unit which has inbuilt Wi-Fi module .
Firstly we connect the circuit as shown in circuit diagram.
Then write the code in ArduinoIDE . but before change arduino IDE to node mcu programmabe IDE.
Go to libraries and import esp8266 module packages and files then  go to tools select the node mcu 0.9 model and the arduino IDE is changed according to NODE MCU required form.
Then select port option and if it is  not available install CH340 drivers then you could able to port selection.
compile and run code.
reset the node mcu,then you can see the pollution content on LCD screen like POLLUTION (%)=24.46.
This will be refreshed for 4 seconds and find the IP address of node mcu .
Then click on the IP address in any internet search URL ,you could able to see a  webpage displaying the pollution content and a caution message being displayed to user.  
By this we can able to access the air quality  surrounded by this project ,within local area network or devices connected to a wifi router/mobile hotspot.
