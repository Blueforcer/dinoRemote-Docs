# Communicatie

Alle op dinotecNET+ gebaseerde apparaten van dinotec met een touchscreen zijn in staat, op **dinoRemote** te worden aangesloten.
De communicatie met de dinoRemote-server volgt via een gecodeerde VPN-tunnel via het **OpenVPN**-protocol.
Voor de opbouw van de VPN-tunnel is de **dinoRemote Box** nodig. Deze gebruikt de plaatselijke internettoegang om alle datapakketten van het dinotecNET+ apparaat, gecodeerd, naar de dinoRemote-server over te dragen.

De aansluiting van de dinoRemote Box (hierna **dRB**) is eenvoudig:
Sluit de netwerkkabel, welke van de DSL-router komt, aan op de **WAN**-poort van de dRB. Het bedieningspaneel (OP57 enz.) van de dinotecNET+ installatie wordt op de **LAN**-poort aangesloten.

![image alt text](../assets/cable.png)
  
***

Zodra de dRB wordt gevoed met spanning en op het internet is aangesloten, gaat kort daarna het VPN-lampje op de box branden. Dit is het signaal, dat de verbinding met onze dinoRemote-server succesvol is.
Wanneer dit niet het geval is, kunt u het het hoofdstuk Fouten verhelpen naar de oplossing zoeken. 
![image alt text](../assets/vpn.jpg)  
***

# UMTS-koppeling

De dRB kan ook radiografisch op de dinoRemote worden aangesloten. Wij adviseren echter altijd de stabiele variant via DSL te gebruiken. 
Voor het verbinden via UMTS is het optionele UMTS-modem en een SIM-kaart met datatarief (min. 1 GB/maand) nodig. De SIM-kaart moet door de exploitant beschikbaar worden gesteld. 
Het modem kan al voor de uitlevering door dinotec worden ingesteld. Hiervoor is het voldoende, de APN en provider door te geven. U kunt ons de al geactiveerde kaart ook toezenden en uw dinoRemote Box wordt geheel ingesteld aan u uitgeleverd. 
**Belangrijk:** Het is absoluut noodzakelijk, dat de PIN van de SIM-kaart is gedeactiveerd!


***

# Fouten verhelpen

** De VPN-lamp brandt niet **

+ De DSL router moet een IP-adres per DHCP kunnen toekennen (indien dit uit technische overwegingen niet mogelijk is, neem dan contact op met onze support).
+ De VPN-tunnel wordt via de standaard OpenVPN poort 1194 gerealiseerd. Waarborg dat deze niet door een firewall wordt geblokkeerd.
+ Gebruik geen zeer lange onafgeschermde netwerkkabel
+ Gebruik geen wlan-adapter of Powerline-adapter
+ Controleer de correcte bekabeling
+ De data-overdracht is te langzaam (vooral bij UMTS)
