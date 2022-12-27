## flasher 2.0
# entpackt..

## update datei im "Marauder" ordner 
• esp32_marauder_v0_10_0_20221222_flipper.bin

## Achtung: Halte die "BOOT" Taste am DevBoard gedrückt !!
#### • jetzt das Wifi_DevBoard via USB-C anschließen 

#### • plugin sound am PC abwarten 




#### • flash.bat ausführen
...

###### Befehle und ihre Bedeutung:
> _____
> 1 & Enter = automatischer Flash
> _____
> 2 & Enter = update .bin (speicher in den Marauder Ordner, nochmal 1)
> _____
> 3 & Enter = BackUp wifi einstellungen (blackmagic)
> _____
> 4 & Enter = Wifi_DevBoard zurücksetzen
> _____

#### nutze 2 dann 1 dann 3 für eine volle Installation 

### •Flipper Zer0 abschalten
### •Wifi_DevBoard am Flipper Zer0 via GPIO anschließen
### •DevBoard LED leuchtet (alles hat geklappt)
### ---FlipperDesktop---
### Application > GPIO > [ESP32] Wifi Marauder

###### Penteste deinen Router:

> _____

> scan ___ ap
= auf Zielrouter warten
> _____

> list ___ ap
= RouterName [?]
> _____

> select ___ ap
= Zahl aus der Eckklammer einfügen, klick auf save
> _____

> attack ___ deauth
= Router kickt alle aus dem Netzwerk
> _____








