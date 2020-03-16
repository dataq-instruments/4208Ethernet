# 4208Ethernet
 Ethernet Example suports 4108/4208/4718 ethernet devices
 
 It demonstrate how to use commands to set up and acquire data then display in a chart.
 
 1)Make sure you configure Window's firewall to allow it to access the network first<br/>
 2)Once started, you will see all devices listed in the listbox, if not issue "QUERY" command<br/>
 3)Click on a device to use it<br/>
 4)Push the button "Connect Setup" to config the device<br/>
 5)Push "Start" to start acquisition then "Stop" to stop acquisition<br/>
 6)Push "Disconnect" to release the device<br/>
 
 ![alt text](https://www.dataq.com/resources/repository/ethernet.gif "ScreenCapture by LICECap")
 
 If you can't start a device, it may be connected to WinDaq running on another PC. Read the protocol of "QUERY" to figure out which one is available 
 
 This example uses Xchart to plot the waveform, which is installed if you install WinDaq addon to your PC. For more info regarding the features of XChart, please refer to http://ultimaserial.com/XChart.html
