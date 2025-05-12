## **NETWORK MONITORING TOOL -**

Python tool used to capture, display, and visualise network packets, using raw sockets to inspect traffic, with pandas and matplotlib to present insights.


### **FEATURES -**

Packet capture: Grabs ipv4 packets from a network interface

CSV logging: Logs source and destination ips to packet_log.csv

Data display: Prints captured packet data in a tabular format

Data visualisation: Bar charts of source ip distribution using matplotlib

Command line interface: Simple text based menu for interaction


### **INSTALLATION -**

Make sure the latest version of python is installed, along with the required libraries. Python can be downloaded by following this link. https://www.python.org/downloads/ Pandas and matplotlib can be added using pip by typing "cmd" into the Windows search bar, and issuing the following commands.
```
pip install pandas 
```
```
pip install matplotlib
```
Now, open a new command prompt by typing "cmd" into the Windows search bar. Make sure to run it as administrator or the script will not run, this can be done by right clicking "cmd" when it appears and selecting "run as administrator" before opening.

Next use the change directories command and find the folder where the script is located, for example: 
```
cd downloads
```
Which can then be followed by the command:
```
python networking_monitoring.py
```
Which will then run the script.

### **COMMAND LINE INTERFACE -**

Following this, a menu popup will appear, with four different options. Entering the corrosponding number into the input box below will select the function requested. 

Inputting the number 1 will prompt the user to enter the number of packets they want capturing by the script. After this has been entered, the packets are captured, and an output file named packet_log.csv is created, which tables this information.

Inputting the number 2 will display the contents of the packet_log.csv file, aslong as the user has previously created this. If the user has not done this, an error message will display.

Inputting the number 3 will visualise the packet disribution of packet_log.csv in a bar chart, aslong as the user has previously created this. If the user has not done this, and error message will display.

Inputting the number 4 will exit the tool.



