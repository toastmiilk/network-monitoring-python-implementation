### **network monitoring tool -**

a simple python tool used to capture, display, and visualise network packets, using raw sockets to inspect traffic, with pandas and matplotlib to present insights.


### **features -**

packet capture: grabs ipv4 packets from a network interface

csv logging: logs source and destination ips to packet_log.csv

data display: prints captured packet data in a tabular format

data visualisation: bar charts of source ip distribution using matplotlib

command line interface: simple text based menu for interaction


### **installation -**

make sure the latest version of python is installed, along with the required libraries. pandas and matplotlib can be added using pip by issuing the following commands in command prompt.
```
pip install pandas 

pip install matplotlib
```
### **usage -**

open command prompt by typing cmd into the windows search bar. make sure to run it as administrator or the script will not run, this can be done by right clicking cmd when it appears and selecting run as administrator.

next use the change directories command and find the folder where the script is located, for example 
```
cd downloads
```
which can then be followed by the command
```
python networking_monitoring.py
```
which will then run the script.

following this, a menu popup will appear, with four different options. entering the corrosponding number into the input box below will select the function requested. 

inputting the number 1 will prompt the user to enter the number of packets they want capturing by the script. after this has been entered, the packets are captured, and an output file named packet_log.csv is created, which tables this information.

inputting the number 2 will display the contents of the packet_log.csv file, aslong as the user has previously created this. if the user has not done this, an error message will display.

inputting the number 3 will visualise the packet disribution of packet_log.csv in a bar chart, aslong as the user has previously created this. if the user has not done this, and error message will display.

inputting the number 4 will exit the tool.



