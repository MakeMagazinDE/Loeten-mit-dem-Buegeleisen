![GitHub Logo](http://www.heise.de/make/icons/make_logo.png)

Maker Media GmbH und c't, Heise Zeitschriften Verlag

***

# Löten mit dem Bügeleisen

### DIY-Lötstation für SMD-Platinen

![Picture](https://github.com/MakeMagazinDE/Loeten-mit-dem-Buegeleisen/blob/master/aufm.JPG)

Das Steuerungsprogramm *SolderingIron.ino* wurde mit der Arduino-IDE für das Mikrocontroller-Board Wemos Mini D1 (ESP8266) erstellt. Die Arduino-IDE benötigt folgende Erweiterungen:

https://github.com/esp8266/Arduino (ESP8266-Erweiterung, auch über Board-Manager)

https://github.com/adafruit/MAX6675-library (Temperatursensor für Thermoelemente Typ K)

https://github.com/adafruit/Adafruit_SSD1306 (OLED-Monochrom-Display)

    Stückliste
 
    R1 4k7
    POTI Potentiometer 4k7 oder 10k, 4mm-Achse, mit Knopf, ggf. Trimmpotentiometer
    C1 100n
    SSR Solid-State-Relais SSR-10 DA, SSR-25 DA oder ähnlich (min. 250V, 10A)
