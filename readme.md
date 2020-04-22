## Audio Alarm Monitoring Raspberry Pi Hat
### Overview
This add-on circuit board (Pi Hat) provides a 2.5mm audio input jack to allow a Soundear audio monitoring device to interface with a raspberry pi configured to work with the [Open Ventilator Remote Monitoring Software](https://github.com/Open-Ventilator-Remote-Monitoring/remote-ventilator-monitor-pi). An indicator LED is illuminated when at 5V digital signal is received from the Soundear audio monitor. This PCB contains a voltage divider circuit which reduces the 5V digital output from the soundear monitor to 3.3v digital logic suitable for the raspberry pi.
![](https://docs.google.com/drawings/d/e/2PACX-1vSqtXpAg8cTxO62BlzSZp-YU2qj7c7WRKmolW69Ne3nnTKPIehSarcs4z8h3bnfYR2UP_W_7z12q-0D/pub?w=480&h=360)
### Inputs & Outputs
#### Inputs
* 2.5mm audio jack from cable connected to soundear (5V digital input)
* 5V power from raspberry pi
* Ground on raspberry pi

#### Outputs
* GPIO 4 pin on raspberry pi (3.3V digital output)

#### Bill Of Materials
The Bill of Materials is in the [Audio Alarm Monitoring Pi Hat.csv](https://github.com/Open-Ventilator-Remote-Monitoring/Audio-Alarm-Monitoring-Pi-Hat/blob/master/Audio%20Alarm%20Monitoring%20Pi%20Hat.csv) file

#### Manufacturing Notes
* This board has slotted holes for all the J1 pads. 
* Milling data is in Audio Alarm Monitoring Pi Hat.GML

#### Assembly Notes
* XA1 is an optional connector for an external LED. Do not populate D1 if you plan to use it.
* This hat connects to a Raspberry Pi using two 10mm tall standoffs. A third 10mm standoff can be connected to the hat and will sit ontop of the Raspberry Pi to add additional support.
