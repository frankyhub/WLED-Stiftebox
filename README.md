<a name="oben"></a>

<div align="center">

|[:skull:ISSUE](https://github.com/frankyhub/WLED-Stiftebox/issues?q=is%3Aissue)|[:speech_balloon: Forum /Discussion](https://github.com/frankyhub/WLED-Stiftebox/discussions)|[:grey_question:WiKi](https://github.com/frankyhub/WLED-Stiftebox/wiki)||
|--|--|--|--|
| | | | |
<a href="https://github.com/frankyhub/WLED-Stiftebox/issues">![GitHub issues](https://img.shields.io/github/issues/frankyhub/WLED-Stiftebox)![GitHub closed issues](https://img.shields.io/github/issues-closed/frankyhub/WLED-Stiftebox)|<a href="https://github.com/frankyhub/WLED-Stiftebox/discussions">![GitHub Discussions](https://img.shields.io/github/discussions/frankyhub/WLED-Stiftebox)|<a href="https://github.com/frankyhub/WLED-Stiftebox/releases">![GitHub release (with filter)](https://img.shields.io/github/v/release/frankyhub/WLED-Stiftebox)|![Static Badge](https://img.shields.io/badge/RepoNr.:-%20024-blue)|
|![GitHub Created At](https://img.shields.io/github/created-at/frankyhub/WLED-Stiftebox)| <a href="https://github.com/frankyhub/WLED-Stiftebox/pulse" alt="Activity"><img src="https://img.shields.io/github/commit-activity/m/badges/shields" />| <a href="https://github.com/frankyhub/WLED-Stiftebox/graphs/traffic"><img alt="ViewCount" src="https://views.whatilearened.today/views/github/frankyhub/github-clone-count-badge.svg">  |<a href="https://github.com/frankyhub?tab=stars"> ![GitHub User's stars](https://img.shields.io/github/stars/frankyhub)||

<img src="pic/01wled.png" width="500"> 
<br> <br>

</div>

# Story

Diese Anleitung beschreibt die Montage einer WLED-Stiftebox. Das Stiftebox Gehäuse wird mit dem Lasercutter erstellt. Die Frontseite könnt ihr selbst designen, die Vorlage steht zum Download bereit. Anschließend verlöten wir den WLED-Stripe mit dem ESP8266. Die Inbetriebnahme erfolgt über install.wled.me.

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

[Inkscape Vorlage](https://github.com/frankyhub/WLED-Stiftebox/tree/main/svg)


<img src="pic/02wled.png" width="500"> 
<br> <br>

#### Schritt 2: Die Verbindungen löten

Löte die drei Litzen an den WLED-Stripe
ESP8266 > WLED
5V > 5V, (D4) GPIO2 > Din, GND > GND

<img src="pic/03wled.png" width="500"> 
<br> <br>
<img src="pic/04wled.png" width="500"> 
<br> <br>

#### Schritt 3: Die WLED Inbetrieb nehmen
Schließe den ESP8266 an den Laptop an und öffne im Browser die Seite https://install.wled.me/.
Starte mit "Installieren"

<img src="pic/05wled.png" width="500"> 
<br> <br>

### Stelle die USB-Verbindung her

<img src="pic/06wled.png" width="500"> 
<br> <br>

### Installiere die WLED

<img src="pic/07wled.png" width="500"> 
<br> <br>
<img src="pic/08wled.png" width="500"> 
<br> <br>
<img src="pic/09wled.png" width="500"> 
<br> <br>
<img src="pic/10wled.png" width="500"> 
<br> <br>

### Gib die WLAN Zugangsdaten ein

<img src="pic/11wled.png" width="500"> 
<br> <br>

<img src="pic/12wled.png" width="500"> 
<br> <br>

### Öffne die Verbindung zum ESP8266

<img src="pic/13wled.png" width="500"> 
<br> <br>

### Öffne die Konfigurations-Seite

<img src="pic/14wled.png" width="500"> 
<br> <br>

### Öffne die LED-Einstellungen

<img src="pic/15wled.png" width="500"> 
<br> <br>


### Editiere die WLED-Einstellungen

<img src="pic/16wled.png" width="500"> 
<br> <br>

### Teste die Funktionen

<img src="pic/17wled.png" width="500"> 
<br> <br>



#### Schritt 4: Die Stiftebox montieren
Nach dem Funktionstest und dem designen der Frontansicht wird die Stiftebox ausgelasert und montiert.
Montiere den ESP8266 in die Stiftebox und führe die Kabel durch die Boden-Öffnung.
Klebe den WLED-Stripe auf die Unterseite der Stiftebox.

<img src="pic/18wled.png" width="500"> 
<br> <br>

#### Schritt 5: Spannung anschließen
Nach der Montage und dem Funktionstest wird der ESP8266 über ein USB-C Kabel und einem Steckernetzteil oder einem Akkupack mit Spannung versorgt.

<img src="pic/19wled.png" width="500"> 
<br> <br>

Die WLED-Stiftebox



Nach der Installation ist die WLED-Stiftebox mit dem Handy/Tabled/PC steuerbar.
Im WiFi setup kann eine feste mDNS Adresse gespeichert werden, z.B. mywled.local.

<img src="pic/20wled.png" width="500"> 
<br> <br>

Aufruf der WLED-Steuerseite mit: mywled.local

<img src="pic/21wled.png" width="500"> 
<br> <br>

Alternativ zur WLED-Stiftebox könnt ihr auch eine WLED-Lampe bauen

<img src="pic/22wled.png" width="500"> 
<br> <br>

Fertig!


---

<div style="position:absolute; left:2cm; ">   
<ol class="breadcrumb" style="border-top: 2px solid black;border-bottom:2px solid black; height: 45px; width: 900px;"> <p align="center"><a href="#oben">nach oben</a></p></ol>
</div>  

---
