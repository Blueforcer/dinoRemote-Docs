# LiveView

Mit LiveView können Sie sich Ihren individuellen Informations-Bildschirm zusammenstellen und müssen nicht durch mehrere Bildschirme auf der Anlage navigieren.
Dieser Bildschirm wird alle 5 Minuten automatisch aktualisiert.

![image alt text](../assets/live.png)

Bei der ersten Verwendung des LiveViews sind keine Module vorhanden.
Durch ein klick auf "EDITIERMODUS BEGINNEN" können Sie sich Ihren LiveView konfigurieren.


---

<img align="right" width="393" height="848" src="assets/edit.png">

Das LiveView besteht aus "Modulen".  
dinotec hat für den einfachen Zugriff einige wichtige Parameter vorgefertigt.  
  
**Bitte beachten Sie:**  
LiveView dient ausschließlich zur Anzeige verschiedener Werte. Eine Steuerung ist nicht möglich.

Die Module können aus verschiedenen Anzeigen bestehen:  
+ **Kanister**  
    Zeigt den Füllstand des Kanisters grafisch an  
+ **Hygieneparameter**  
    Zeigt einen Parameter auf einer Farbskala an  
+ **Bitstatus**  
    Zeigt einzelne Zustände an  
+ **Register**  
    Zeigt einzelne Werte an  

Zudem wird bei jedem Modul angezeigt, zu welchem Kreislauf diese Information gehört.  

Im oberen Bereich können Sie nach vorhanden Modulen suchen.  

Sie haben auch über den Expertenmodus die Möglichkeit ihre eigenen Module zu konfigurieren.
    
**ACHTUNG:**  
Diese Funktion ist in der Lage jede Informationen der Anlage abzubilden und ist nur Benutzern empfohlen, die sich mit dem internen Aufbau der Anlagensoftware sehr gut auskennen. 
Im Abschnitt **Experten Modus** wird die Konfiguration eines Moduls erklärt.   
  
    


## Modul bearbeiten

Einige Module bieten Einstellungen die Sie ändern können.

![image alt text](../assets/modul.png)

Mit <i class="fa fa-cog fa-lg"></i> rufen Sie die Einstellungen des Moduls auf und können damit z.B die Skala anpassen.  
<i class="fa fa-times fa-lg" style="color:red"></i> löscht das aktuelle Modul aus dem LiveScreen.


## Namen  ändern
Sie können den Namen (Unterschrift) des Moduls beliebig ändern. Markieren Sie den aktuellen Namen und tippen Sie einen neuen ein.
Wenn Sie den eigenen Namen komplett löschen, so wird wieder der Standardname verwendet. 

![image alt text](../assets/name.gif)  


## Anordnung ändern

Durch Klicken auf die Pfleile die sich am Rand jedes Moduls befinden, können die die Anordnung im LiveView ändern.  
  
![image alt text](../assets/order.gif)

## Expertenmodus

Im Expertenmodus werden alle verfügbaren Register aus dem dinotecNET+ System aufgelistet.
Wählen Sie ein beliebiges Register aus und klicken Sie anschließend auf das <i class="fa fa-cog fa-lg"></i>.
hier haben Sie die Möglichkeit die Anzeige zu konfigurieren:
+ Reguläres Register
Zeigt nur den Wert des Registers an (falls vorhanden, mit Einheit)
+ Hygieneparameter
Zeigt den Wert als farbigen Tachometer an
+ Bit-Status
Zeigt den Zustand eines einzelnen Bits im Register an.

