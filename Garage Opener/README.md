# Garage Door Opener via athom-relay board x1 


![f83f1a_52973368535d408a9207a5c6cdf81c9b~mv2](https://github.com/user-attachments/assets/f042d8f2-c5ff-4d9a-be03-9ead95403f9b)


| Name  | Description                                                                                | PIN    | Use in ESPHome            |
| ----- |:------------------------------------------------------------------------------------------:| :------:| ------------------------- |
| GND   | Ground                                                                                     | GND    |                           |
| Relay | Default IO5,if want use <br>other I/O please remove R14 ,<br> then connect I/O to this pin | GPIO5  | Relay                     |
| IO2   | UART1_TX                                                                                   | GPIO2  |                           |
| IO4   | GPIO4                                                                                      | GPIO4  | Garage Closed Reed Switch |
| RX    | UART0_RXD                                                                                  | GPIO3  |                           |
| 3V3   | POWER                                                                                      | 3.3V   |                           |
| SCLK  | Timer                                                                                      | SCLK   |                           |
| IO15  | MTDO:HSPICS:UART0_RTS                                                                      | GPIO15 |                           |
| IO0   |                                                                                            | GPIO0  |                           |
| TX    | UART0_TXD                                                                                  | GPIO1  |                           |
| 5V    | POWER                                                                                      | 5V     |                           |
| IO10  |                                                                                            | GPIO10 |                           |
| IO13  | HSPI_MOSI:ART0_CTS                                                                         | GPIO13 |                           |
| IO14  | HSPI_CLK                                                                                   | GPIO14 | Garage Open Reed Switch   |
| ADC   | Input Voltage 0.0~1.0V = 0~1024                                                            | ADC0   |                           |
| IO9   |                                                                                            | GPIO9  |                           |
| CS0   |                                                                                            | CS0    |                           |
| IO12  | HSPI_MISO                                                                                  | GPIO12 |                           |
| IO16  |                                                                                            | GPIO16 |                           |

DC 5V/DC 8-80V input 10A relay

 

All IOs on board,  Tasmota user can connect anything for example : motion sensor/ temperature sensor etc to the board, IO description as picture show.

 

Self-Locking:

 

The default setting of the relay is self-locking 

 

Inching Mode:

 

To change self-locking mode to Inching mode, please follow the instruction below :

 

Use commandline input : PulseTime 1

   

 

Operating voltage: 5V/8-80V DC
relay on/off status respectively
Two input interfaces
Supports to control different voltage ranges
USB port power supply more convenient
Board consumption: <1W
Standby current: 80mA
Max input current: 10A
Max Wattage: 2200W
Relay lifespan: ≥one million times
100M electrical insulation resistance
Electric shock voltage: 1000V
Relay maximum pull time: 15ms
Relay maximum release time: 5ms
Working mode: inching / self-locking
Wireless Standard: 2.4GHz, 802.11 b/g/n
Application: access control, turn on PC, garage door, etc.
Computer application: Remote control computer boot
Operating temperature: -40 degrees to +70 degrees
Operating Humidity 40%-80% RH

## Install 

First should know the USB port Not possible to flashing 
USB for power only

USB to TTL converter UART module CH340G CH340 3.3V 5V
![usb-to-ttl-converter](https://github.com/user-attachments/assets/40975051-cfde-437d-906c-b68e2a68bb2b)
