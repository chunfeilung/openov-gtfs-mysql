# ovapi-gtfs-mysql

Scriptje om “effe snel” wat testjes uit te voeren met de GTFS-data van gtfs.openov.nl.

## How-to

Clone deze repository:

```bash
git clone https://github.com/overstapp/ovapi-gtfs-mysql
```

Download een versie van de GTFS-bestandjes en plaats die bestanden in de `gtfs`-map.

Zorg ervoor dat je een MySQL-server hebt draaien.

Voer vervolgens vanuit de hoofdmap het volgende uit, met `username` en `password` vervangen door je MySQL-gebruikersnaam en -wachtwoord:

```bash
./import-gtfs username password
```
