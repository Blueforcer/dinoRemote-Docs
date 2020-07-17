dinoAccess is a smartphone app for control and visualization of the PC Dynamics and CF Control 100. dinoAccess is intended for the device owner and is required to configure the device.

After successfully setting up PC Dynamics via the app, it can also be controlled and managed in dinoRemote (PC Dynamics only).
It is also possible to release PC Dynamics for the dealer or other dinoRemote users, similar to dinotecNET+ systems.  A customer overview and its attachment is not possible for the dealer via the dinoAccess App.

### Requirements
- Apple iPhone from iOS9 or Android Smartphone from Android 6.0 (Marshmallow)
- Internet capable 2.4 Ghz access point near the PC Dynamics or CF Control 100
- Activated DHCP in the customer network
- Port 1883 and 3006 are not blocked by a firewall

### App Download
 <div align=center>
  <img width="200" src="assets/appstore.svg"/> 
  <p>
  
  [Apple](https://apps.apple.com/de/app/dinoaccess/id1474266309) oder [Android](https://play.google.com/store/apps/details?id=de.dinotec.dinoaccess)
   </p>
  </div>

### First Start

If you already have a dinoRemote account, you can login with the same login data. This also works the other way around, since the same user database is used.

The app guides you intuitively through the setup process. Please read it carefully.


- Click on the yellow plus in the bottom right corner ![image alt text](../assets/plus.png) to set up a new device.

- Select the device type you want to set up and complete the device name and location address. Then click on **Next**.
<div align=center>
  <img width="200" src="assets/deviceinfo.png"/> 
</div>

- Enter the login data for the desired WLan access point to which your device should connect. Then click on **Next**.

<div align=center>
  <img width="200" src="assets/wifi1.png"/> 
</div>

- Now open the WiFi setting on your smartphone and search for the open hotspot (starting with **PCD4** or **CF100**, depending on the device type).
<div align=center>
<div class="row">
  <div class="column">
    <img width="200" src="assets/search.png" alt="Snow"> <img width="200" src="assets/wifi3.png" alt="Forest">
  </div>
</div>
</div>

- The app now sends the information directly to the device, which then connects to the registered WLAN and sends its first data to the dinoRemote server. This process can take about 2-3 minutes. Do not close the app during this time. When the device has sent its first data, the app automatically switches to the parameter screen of the system.
  
<div align=center>
  <img width="200" src="assets/overviewapp.png"/> 
</div>

- **The setup is complete**



### Troubleshooting

**No hotspot with the name "PCD4" or "CF100" is found**  
Enter the code **800** in the device to reset the Wifi settings.

**During setup, the app will stop at "Waiting for connection "**  
Select the appropriate WLan hotspot in your WLan settings of your smartphone.

**During setup the app will stop at "Wait for first data "**
- You may have entered your Wifi access data incorrectly. Reset the device with code **800**.
 Go to the device overview in the app, select your device, click "Continue configuration" and go through the steps again carefully.

- The WLan connection to the customer router is too weak. Try to bring the access point closer to your device. Use a WLan repeater if necessary. The WiFi antenna of PC Dynamics is not comparable to that of a smartphone or laptop!

- The network is secured by a firewall. Make sure that the following ports are open for the device:
  - 1883 (TCP)
  - 3006 (web socket)
