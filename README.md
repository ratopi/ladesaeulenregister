# Ladesäulenregister als JSON

Dieses Repo enthält das nach JSON konvertierte Ladensäulenverzeichnis der Bundesnetzagentur.

## Struktur

`info`: enthält Metainformationen aus der Originaldatei.

`data`: enthält die gewandelten Einträge als Liste.

### Einträge

`addr`: enthält Adressinformationen
`geo`: enthält `lat` und `lon`
`charging`.`points`: enthält eine Liste der Ladepunkte

