# 4xx8 Ethernet Example
 Ethernet Example suports 4108/4208/4718 ethernet devices
 
 It demonstrate how to use protocol to set up and acquire data then display in a chart. 
 
 For protocol, please refer to  https://www.dataq.com/resources/pdfs/misc/Dataq-Instruments-Protocol.pdf
 
 This example uses Xchart to plot the waveform, which is installed when you install WinDaq addons (https://www.dataq.com/products/windaq/add_ons/index.htm) to your PC. 
  
 For more info regarding the features of XChart, please refer to http://ultimaserial.com/XChart.html
 
 1)Make sure you configure Window's firewall to allow it to access the network first<br/>
 2)Once started, you will see all devices listed in the listbox. If not, issue "QUERY" command<br/>
 3)Click on a device to use it<br/>
 4)Push the button "Connect Setup" to config the device<br/>
 5)Push "Start" to start acquisition then "Stop" to stop acquisition<br/>
 6)Push "Disconnect" to release the device<br/>
 
 ![alt text](https://www.dataq.com/resources/repository/ethernet.gif "ScreenCapture by LICECap")
 
 If you can't start a device, it may be connected to WinDaq running on another PC. Read the protocol to find out more
 
 When you download and build this project for the first time, good chance you will run in an error like "Couldn't process file form1.resx due to its being in the internet or Restricted zone or having the mark of the web on the file. Remove the mark of the web if you want to process these files."

To deal with it, you will need to locate the offending .resx files in solution directory, right click on it, open the properties and check the option "unblock". Repeat this for all offending .resx files before reloading the project

![alt text](https://www.dataq.com/resources/repository/resxunblock.png "how to unblock resx files")

