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
    OLED 0,96"-OLED-Display mit SSD1306 
    MAX6675 Temperatursensor-IC auf Breakout-Board
    
    
[Passendes OLED-Display von Reichelt](https://www.reichelt.de/entwicklerboards-display-0-96-oled-display-ssd1306-debo-oled2-0-96-p266107.html)

[Passendes Mikrocontrollermodul von Reichelt](https://www.reichelt.de/d1-mini-esp8266-v3-0-d1-mini-p253978.html)

[Passendes OLED-Display von AZ Delivery](https://www.az-delivery.de/products/0-96zolldisplay)

[Passendes Mikrocontrollermodul von AZ Delivery](https://www.az-delivery.de/products/d1-mini)

[Thermoelement mit MAX6675 Breakout-Board (Amazon, als Beispiel)](https://www.amazon.de/Interface-Thermocouple-Temperature-0%C2%B0C-1024%C2%B0C-Compatible/dp/B073FNJDXW/ref=sr_1_1)
