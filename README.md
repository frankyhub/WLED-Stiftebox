<a name="oben"></a>

## WLED-Stiftebox

### Story

Diese Anleitung beschreibt die Montage einer WLED-Stiftebox. Das Stiftebox Gehäuse wird mit dem Lasercutter erstellt. Die Frontseite könnt ihr selbst designen, die Vorlage steht zum Download bereit. Anschließend verlöten wir den WLED-Stripe mit dem ESP8266. Die Inbetriebnahme erfolgt über install.wled.me.



![Bild](pic/01wled.png)

### Die WLED-Stiftebox



### Hardware

Die Stückliste für die WLED-Stiftebox:

| Anzahl | Bezeichnung | 
| -------- | -------- | 
|  1 |  Sperrholz 300x600 x 3mm  |
|  1 | ESP8266  |
|  1 | WLED-Stripe WS2812B   |
|  1 |  USB-C Kabel mit Ladestecker  |
|  1 | Litze, Holzleim   |



### Aufbau und Montage

Der Aufbau und die Montage der WLED-Stiftebox ist in mehrere Schritte unterteilt.

#### Schritt 1: Die Frontansicht designen

Verwende die Inkscape Vorlage:

Inkscape Vorlage


![Bild](pic/02wled.png)


#### Schritt 2: Die Verbindungen löten

Löte die drei Litzen an den WLED-Stripe
ESP8266 > WLED
5V > 5V, (D4) GPIO2 > Din, GND > GND


![Bild](pic/03wled.png)

![Bild](pic/04wled.png)



#### Schritt 3: Die WLED Inbetrieb nehmen
Schließe den ESP8266 an den Laptop an und öffne im Browser die Seite https://install.wled.me/.
Starte mit "Installieren"


![Bild](pic/05wled.png)

### Stelle die USB-Verbindung her


![Bild](pic/06wled.png)

### Installiere die WLED


![Bild](pic/07wled.png)

![Bild](pic/08wled.png)

![Bild](pic/09wled.png)

![Bild](pic/10wled.png)

### Gib die WLAN Zugangsdaten ein


![Bild](pic/11wled.png)

![Bild](pic/12wled.png)

### Öffne die Verbindung zum ESP8266


![Bild](pic/13wled.png)

### Öffne die Konfigurations-Seite


![Bild](pic/14wled.png)

### Öffne die LED-Einstellungen


![Bild](pic/15wled.png)

### Editiere die WLED-Einstellungen


![Bild](pic/16wled.png)

### Teste die Funktionen


![Bild](pic/17wled.png)



#### Schritt 4: Die Stiftebox montieren
Nach dem Funktionstest und dem designen der Frontansicht wird die Stiftebox ausgelasert und montiert.
Montiere den ESP8266 in die Stiftebox und führe die Kabel durch die Boden-Öffnung.
Klebe den WLED-Stripe auf die Unterseite der Stiftebox.


![Bild](pic/18wled.png)



#### Schritt 5: Spannung anschließen
Nach der Montage und dem Funktionstest wird der ESP8266 über ein USB-C Kabel und einem Steckernetzteil oder einem Akkupack mit Spannung versorgt.


![Bild](pic/19wled.png)

Die WLED-Stiftebox



Nach der Installation ist die WLED-Stiftebox mit dem Handy/Tabled/PC steuerbar.
Im WiFi setup kann eine feste mDNS Adresse gespeichert werden, z.B. mywled.local.


![Bild](pic/20wled.png)

Aufruf der WLED-Steuerseite mit: mywled.local

![Bild](pic/21wled.png)


Alternativ zur WLED-Stiftebox könnt ihr auch eine WLED-Lampe bauen


![Bild](pic/22wled.png)

Fertig!


---

<div style="position:absolute; left:2cm; ">   
<ol class="breadcrumb" style="border-top: 2px solid black;border-bottom:2px solid black; height: 45px; width: 900px;"> <p align="center"><a href="#oben">nach oben</a></p></ol>
</div>  

---
