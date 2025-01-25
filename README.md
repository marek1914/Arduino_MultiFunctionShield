# Arduino_MultiFunctionShield
LED Display driver for Multi Function Shield

**Note:** Timer1 used => Pins 9 and 10 on Uno for PWM and analogWrite() are effected

![multi_function_shield](multi_function_shield.png?raw=true)

Fritzing Part: [Download Multi Function Shield](https://www.heise.de/make/downloads/76/2/4/1/3/8/7/4/Multi_Function_Shield.fzpz)

https://www.blafusel.de/index.html


na podstawie:
Arduino R4 WiFi i Multi Function Shield 
- portujemy bibliotekę na R4, FspTimer 

https://www.elektroda.pl/rtvforum/topic3997354.html

kod biblioteki Multi Function Shield by Florian

jest dla ATmega328 

Zmodyfikować trzeba wpis architectures:

architectures=avr  na architectures=*

użyty też został timer AVR

Do Arduino R4 niezbędne są modyfikacje w plikach:

library.properties

src/MultiFunctionShield.cpp

src/MultiFunctionShield.h

https://github.com/coderfls/Arduino_MultiFunctionShield/pull/2/files




