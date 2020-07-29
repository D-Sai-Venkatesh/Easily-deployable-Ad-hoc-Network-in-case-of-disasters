Contributers are:
  Dasari Surya Sai Venkatesh 
  Srishti Adil
=============================================================================================================================================

DMS : disaster management team

Access_point_upload_in_ESP32_  : it is the code which has to be uploaded in the wifi module (ESP32 developent board)

node__upload_in_arduino__  : it the code which has to be uploaded in all nodes.

node__upload_in_arduino__  : it the code which has to uploaded in Disaster management team's node. The diffrence between the privious code and this code is that, it sends distance vector in the begining.

GPSmap.py : it communicates with the DMS node via serial port and recives messages from DMS node, and extracts GPS info from each message and plots the location in a html file (scatter.html).

=============================================================================================================================================

When you start the LoRa-GPS node, it may happen that node is not reciveing GPS data. This happens due to hard shutdown (leaving GPS module for long amount of time in shut down mode). Then leave the node in powern on mode for about 20-30 mins. 
