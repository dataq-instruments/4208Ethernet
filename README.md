# 4xx8 Ethernet Example
 Ethernet Example suports DI-4108/4208/4718/4730 ethernet devices
 
 It demonstrate how to use protocol to set up and acquire data then display in a chart. 
 
 **Prerequisites**:
 
 1) Understand the protocol, please refer to  https://www.dataq.com/resources/pdfs/misc/Dataq-Instruments-Protocol.pdf
 
 2) This example uses Xchart to plot the waveform, which is installed when you install WinDaq addons (https://www.dataq.com/products/windaq/add_ons/index.htm) to your PC. 
  
  **Run**:
 
 1) Make sure you configure Window's firewall to allow it to access the network first
 
 2) Once started, you will see all devices listed in the listbox. If not, issue "QUERY" command
 
 3) Click on a device to use it
 
 4) Push the button "Connect Setup" to config the device
 
 5) Push "Start" to start acquisition then "Stop" to stop acquisition
 
 6) You can drag the waveform up and down, and use the mouse wheel to zoom in and out
 
 7) Push "Disconnect" to release the device<br/>
  ![alt text](https://www.dataq.com/resources/repository/ethernet.gif "ScreenCapture by LICECap")
  
 8) If you can't start a device, it may be connected to WinDaq running on another PC. 

 
 **Note**:
 
- When you download and build this project for the first time, good chance you will run in an error like "Couldn't process file form1.resx due to its being in the internet or Restricted zone or having the mark of the web on the file. Remove the mark of the web if you want to process these files."

- To deal with it, you will need to locate the offending .resx files in solution directory, right click on it, open the properties and check the option "unblock". Repeat this for all offending .resx files before reloading the project <br/>
![alt text](https://www.dataq.com/resources/repository/resxunblock.png "how to unblock resx files")

**Extra**:

1) For more info regarding the features of XChart, please refer to http://ultimaserial.com/XChart.html
 
2) A good tool to understand/debug the protocol communication is the network protocol analyzer WireShark https://www.wireshark.org/

3) If you want to see all communication packets between PC and 4108(E), check out this Wireshark capture:  https://github.com/dataq-instruments/Ethernet_Protocol_Demo/blob/master/capture.pcapng

