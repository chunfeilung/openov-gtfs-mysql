# openov-gtfs-mysql

De General Transit Feed Specification (GTFS) is een formaat waarmee informatie over het openbaar vervoer mee vastgelegd kan worden. Uiteraard niet alles – dat zou een beetje te veel van het goede zijn – maar wél genoeg om bijvoorbeeld een haltevertrekstaat, lijnnetkaart, of digitale reisplanner mee te maken. Hartstikke leuk dus!

Bij [OpenOV](http://gtfs.openov.nl/gtfs/) kun je de GTFS-data voor heel Nederland vinden. Deze worden aangeboden in de vorm van CSV’s. Handig, want dan kun je ze makkelijk inlezen en verwerken.

Voor de écht luie mensen (die toevallig ook Linux of OS X en MySQL of MariaDB gebruiken) maakt `openov-gtfs-mysql` dat nog een stukje makkelijker: deze leest namelijk direct de GTFS-data voor je in in de database, zodat je er direct mee aan de slag kan gaan!

Oh ja, mocht je helemaal niet bekend zijn met GTFS, dan kun je het beste een kijkje nemen op de [website van Google](https://developers.google.com/transit/gtfs/).


## How-to

Clone deze repository:

```bash
git clone https://github.com/overstapp/openov-gtfs-mysql
```

Zorg ervoor dat je een MySQL-server hebt draaien.

Voer vervolgens vanuit de hoofdmap het volgende uit:

```bash
sudo ./import-gtfs
```
