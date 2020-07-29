DMS : disaster management team



Access_point_upload_in_ESP32_  : it is the code which has to be uploaded in the wifi module (ESP32 developent board)

node__upload_in_arduino__  : it the code which has to be uploaded in all nodes.

node__upload_in_arduino__  : it the code which has to uploaded in Disaster management team's node. The diffrence between the privious code and this code is that, it sends distance vector in the begining.

GPSmap.py : it communicates with the DMS node via serial port and recives messages from DMS node, and extracts GPS info from each message and plots the location in a html file (scatter.html).
