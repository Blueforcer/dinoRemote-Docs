# Communication

All dinotec Net+ based devices with a touch screen are able to be connected to the **dinoRemote**.
The communication to the dinoRemote server takes place via a highly encrypted VPN tunnel via the **OpenVPN** protocol.
The **dinoRemote Box** is required for setting up the VPN tunnel. This uses the local Internet access to transmit all data packets from the dinotec Net+ device, encrypted, to the dinoRemote server.

The connection of the dinoRemote Box is simple:
Connect the network cable coming from the DSL router to the **WAN** port of the dinoRemote Box. The operation panel (OP57 etc.) of the Net+ system is connected to the **LAN** port.

![image alt text](../assets/cable.png)
  
***

As soon as the dRB is powered and connected to the Internet, the VPN lamp on the box will light up. This is the indicator that the connection to our dinoRemote server is successful.
If this is not the case, you can search for the solution in the Troubleshooting section below.  
 <div align=center>
  <img width="400" src="assets/vpn.jpg"/> 
  </div>
***

# Connection with other external gateways

If other dinotecNet+ systems or gateways (such as DMX, KNX) are required in addition to the dinoRemote Box, a network switch must be used. All devices are connected to the switch, the switch itself to the **LAN port** of the dinoRemote Box. For safety reasons, no foreign network devices may be connected to the switch.

![image alt text](../assets/switch.png)  

**UMTS connection**

There is a separate VPN-LTE modem for connection via the mobile phone network. The device described above is not necessary. The connection to a dinotecNet+ system is made in the same way as the dinoRemote Box for DSL connection, except that here the connection to the customer router on the WAN side is not necessary.

 <div align=center>
  <img width="400" src="assets/scr200.png"/> 
  </div>

A SIM card with data tariff (min. 1GB/month) is required for connection via UMTS. The SIM card must be provided by the operator.  
You can also send us the already activated card and your dinoRemote Box will be delivered to you fully set up.  

!> It is absolutely necessary that the PIN of the SIM card is deactivated!

!> We always recommend to use the stable version via cable.  


***

# Troubleshooting

**The VPN light is not lit**

+ The DSL router must be able to assign an IP address via DHCP (if this is not possible for technical reasons, please contact our support).
+ The VPN tunnel is established via the standard OpenVPN port 1194 Please make sure that it is not blocked by a firewall.
+ The customer network also uses the **192.168.0.X** as IP range. If this is the case, please contact our support.
+ Do not use a very long unshielded network cable
+ Do not use Wifi bridges or Powerline adapters
+ Check the correct cabling
+ Data transmission is too slow or no reception (mainly with UMTS)
  
   
**No access to remote maintenance**  
    
+ The connection to the dinotecNET+ is interrupted. A restart of the dinotecNET+ can help here. 