# city-codes

&nbsp; [![goodtables.io](https://goodtables.io/badge/github/datasets-br/city-codes.svg)](https://goodtables.io/github/datasets-br/city-codes) <!-- &nbsp; [![](https://upload.wikimedia.org/wikipedia/commons/e/eb/PICOL_icon_View.svg) datapackage preview](http://data.okfn.org/tools/view?url=https%3A%2F%2Fraw.githubusercontent.com%2Fdatasets-br%2Fcity-codes%2Fmaster%2Fdatapackage.json)-->

Comprehensive Brazilian city code information, including IBGE codes, wikidata IDs and URN LEX labels. 
Provided as a Simple Data Format Data Package (see datapackage.json visualization).

![](assets/Brazil_Municipalities-400px.png)

Brazilian city names and official codes of 5570 municipalities.

## Collaborative updating

See [Collaborative spreadsheet editor](https://docs.google.com/spreadsheets/d/1A4WzBTH26YMtp62CCaOjS30WwlubauSmOnpecZQ-fpI/) and Wikidata references.

Periodic dumps: please, to update dumps run
* `php src/etc/dumpWikidata.php` to update [data/dump_wikidata](data/dump_wikidata), `*.json` files at each state-folder.
* `php src/dumpOsm.php geo` to update [data/dump_osm](data/dump_osm), `*.geojson` files at each state-folder.

## Stable versions

See homologation process after each cicle of update.

## Sources

* IBGE data in bulk of "Organizaçao do Território Brasileiro/Divisão Territorial", ftp://geoftp.ibge.gov.br/organizacao_do_territorio/estrutura_territorial/divisao_territorial

* [List of all municipalities](https://pt.wikipedia.org/wiki/Lista_de_munic%C3%ADpios_do_Brasil) (Wikipedia and source of Wikidata links)

* CEP

## Other links

* this repo: http://datasets.OK.org.br/state-codes
* Datapackage standard: http://frictionLessData.io
