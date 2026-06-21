# FD900A-metal-case---help-and-firmware
Help modifying, operating and updating the Metal case version of the RFD900A.

The RFD900A in a metal case is 1 watt 900mhz capable of extremely long range line of sight data stream. 
 Finding support as been rather difficult thus i decided to create this place for anyone intrested. 
  any suggestion for improvement are welcomed, i am rather busy to commit a perfectly readable instructions. 

Contents: 
  x Std compiled firmwares 
  x Best software win32/64 with working firmware update lookup sourced from ardu pilot mission planner website. "newest to date p2p point to point v2.2"
  X stl models for 3D printing case etc. 
  x Settings i find works well

Interface: 
  x 6 pins 1-6 from the left to right. 
    . 1 VCC 5v "red"
    . 2 RX data flow rate "baud speed" needs to match device reiceving. 
    . 3 TX data . . "Baud" match device transmitting. 
    . 4 ch1 optional data channel configured with terminal AT commands they are described in manual and can either send or reiceve not both. 
    . 5 ch2 . . . . see above
    . 6 Ground "black" helpful to note that ground is a reference factor in data exhange between devices the ones and zeros and both radio and device need to share.
    . 2x leds, green blinking - not connected / solid green - connected. Red light flashing randomly shows data data is readable on tx or rx and baud correct.

 nice option is the programmable pins 4 and 5 and lets you for example use a remote controller tx and your remote vehicle rx side by side with telemetry. 
or additional sensors etc. fun stuff

    
    
