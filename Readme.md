[English version](#ssd1306-example)
# Przykład dla SSD1306
To bardzo prosty przykład dla modułów OLED 128x64 z interfejsem I2C.

Stowrzyliśmy kompletny projekt w PlatformIO, ze wskazaniem wersji bibliotek i platform,
tak by za jakiś czas ten projekt kompilował się również bez problemów. Wracając po długim
czasie do jakiegoś modułu, wiele czasu zajmowało ponowne go uruchomienie.

W czasie pisania mieliśmy w ofercie następujące moduły OLED 128x64 z SSD1306:

* https://nettigo.pl/products/wyswietlacz-oled-0-96-i2c-128x64-ssd1306-bialy
* https://nettigo.pl/products/wyswietlacz-oled-0-96-i2c-128x64-niebieski
* https://nettigo.pl/products/ekran-oled-0-91-i2c-ssd1306-128x32px-bialy
* https://nettigo.pl/products/wyswietlacz-oled-0-66-i2c-dedykowany-do-wemos-d1-mini Zasadniczo to shield do Wemosa, i jakiś czas temu wymagał dedykowanej biblioteki by pracować na Wemosie, ale jeśli chcesz podłączyć moduł do jakiegoś Arduino to też zadziała.

# SSD1306 example

This is very simple example project for 128x64 OLED displays based on SSD1306 and
I2C interface.

We have created this project and fixed library and platform versions in hope it
will be working even when new releases will come. When You get back to even simple
project after long time it often takes a lot time to get even simple example up
and running.

At time of writing we had following SSD1306 based modules in our offer:

* https://nettigo.pl/products/wyswietlacz-oled-0-96-i2c-128x64-ssd1306-bialy
* https://nettigo.pl/products/wyswietlacz-oled-0-96-i2c-128x64-niebieski
* https://nettigo.pl/products/ekran-oled-0-91-i2c-ssd1306-128x32px-bialy
* https://nettigo.pl/products/wyswietlacz-oled-0-66-i2c-dedykowany-do-wemos-d1-mini This is shield for Wemos, some time ago You had use other modifed SSD1306 library with Wemos, but in case You want to connect this module to Arduino - no problem it will work with this example.
