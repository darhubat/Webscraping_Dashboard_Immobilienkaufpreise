## Ausgangslage
<!-- Italics -->
###### Projekt:
Webscraper-Erstellung für die Datengewinnung, ETL-Prozess für eine konsistente Speicherung in ein Date Warehouse (MySQL) und anschliessender Verbindung der Datenbank mit einem interaktiven Python-Dashboard.

###### Art der Arbeit:
Private Entwicklung zur stetigen Weiterbildung in Python und der Anwendung diverser Techniken (Python, SQL, CSS, HTML).
Das ganze Projekt dient nur zu Übungszwecken und hat nicht den Anspruch einer vollständigen und lückenlosen Abbildung,
sowie der stetigen Aktualisierung auf Updates z.B. auf der gescrapten Webseite.

###### Projekt-Team:
darhubat


***

## Installationen & starten des Webscrapers
<!-- Italics -->
Folgende Programme bzw. Python-Pakete müssen installiert sein, um das Dashboard auf dem Entwicklungsserver ansehen zu
können:

* `Python 3.9`
* `PyCharm` oder `Anaconda`
* `dash`
* `dash_core_components`  
* `dash_html_components`
* `dash_dependencies`
* `json`
* `plotly.express`
* `pandas`
* `numpy`
* `mysql.connector`
* `scrapy`
* `MySQL-Workbench`

Mit folgender Python-Datei [`scout_final.py`](app.py "scout_final.py") kann der Webscraper gestartet werden. Der Webscraper holt entsprechend
vordefinierte Werte von veröffentlichten Angeboten auf der Webseite von Immoscout24.

Alternativ kann auch über den folgenden Befehl und den Terminal der Webscraper gestartet werden:
*scrapy runspider webscraping\webscraping\spiders\scout_final.py*

## ETL-Prozess: Daten zwischenspeichern, anreichern, transformieren und endspeichern in MySQL
<!-- Italics -->

Hier folgt noch ein Beschrieb...

## Interaktives Dashboard erstellt mit den Daten aus der MySQL-Datenbank
<!-- Italics -->

Hier folgt noch ein Beschrieb...



***


## Ordner-Struktur in GitHub
<!-- Italics -->
Die Struktur in GitHub setzt sich wie folgt zusammen:

Hier folgt noch ein vollständiger Beschrieb...

* `_archive` *Aufrufen: [hier](_archive) klicken.*
* `assets` *Aufrufen: [hier](assets) klicken.*
* `database` *Aufrufen: [hier](database) klicken.*
* `output` *Aufrufen: [hier](output) klicken.*
* `webscraping` *Aufrufen: [hier](webscraping) klicken.*


***


## Dashboard-Anleitung
<!-- Italics -->
1) Nach korrekter Installation der Programme und Bibliotheken in Ihrer Python-Umgebung, können Sie mit 
[`Dashboard_Immo_Data_SQL.py`](app.py "Dashboard_Immo_Data_SQL.py") 
das Dashboard über den Entwicklungsserver (Port: 8050) aufgerufen werden. Folgendes Dashboard (siehe im Bild untenstehend) 
sollte nun auf Ihrem Bildschirm erscheinen.