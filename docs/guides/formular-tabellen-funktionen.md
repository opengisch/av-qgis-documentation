# Geometrische Bearbeitung

## Geometrie erstellen

### 169  - Parallelität

|  |  |
|----|----|
| <img src="../../assets/images/formular-tabellen-funktionen/media/ft1.png"/> | <img src="../../assets/images/formular-tabellen-funktionen/media/ft2.png"/> |
| <img src="../../assets/images/formular-tabellen-funktionen/media/ft3.png"/> |  |

Layereigenschaften > Felder > Feldrechner > virtuelles Feld anlegen.

Ein virtuelles Feld mit Ausdruck (Funktion) erstellen und ins Formular ziehen.

Layereigenschaften > Attributformular > Drag-and-Drop-Designer > zuvor angelegtes Feld hinzufügen.
Formular eines Objekts öffnen.

### 278 - Defaultwerte setzen, bearbeiten und löschen

|  |  |
|----|----|
| <img src="../../assets/images/formular-tabellen-funktionen/media/ft4.png"/> | <img src="../../assets/images/formular-tabellen-funktionen/media/ft5.png"/> |


Layereigenschaften > Felder > Feldrechner > virtuelles Feld anlegen.

Layereigenschaften > Attributformular öffnen und ein Feld auswählen.

Unter "Vorgaben" einen Defaultwert setzen.


### 279 - Defaultwerte dynamisch setzen (Datenmodell, Benutzer)

|  |  |
|----|----|
| <img src="../../assets/images/formular-tabellen-funktionen/media/ft4.png"/> | <img src="../../assets/images/formular-tabellen-funktionen/media/ft6.png"/> |
| <img src="../../assets/images/formular-tabellen-funktionen/media/ft7.png"/> |  |

Layereigenschaften > Attributformular öffnen.
Für ein Feld den Defaultwert-Ausdruck @user_account_name (bzw. @user_full_name) setzen.
Für ein Datumsfeld den Ausdruck now() setzen.


### 280 - Einzelne Datenwerte bearbeiten

|  |  |
|----|----|
| <img src="../../assets/images/formular-tabellen-funktionen/media/ft8.png"/> |  |


Editiermodus einschalten und mehrere Objekte selektieren.

Attributtabelle öffnen und in die Formularansicht wechseln.

"Mehrere Objekte gleichzeitig bearbeiten" aktivieren.

Einen Attributwert ändern und übernehmen.

Alternativ mit dem Feldrechner einen Wert für die Selektion setzen.

Änderungen speichern


[<u>https://docs.qgis.org/3.44/en/docs/user_manual/working_with_vector/attribute_table.html#multi-edit-fields </u>](https://docs.qgis.org/3.44/en/docs/user_manual/working_with_vector/attribute_table.html#multi-edit-fields)


### 285 - Mehrere Datenwerte löschen

|  |  |
|----|----|
| <img src="../../assets/images/formular-tabellen-funktionen/media/ft9.png"/> |  |


Editiermodus einschalten und mehrere Objekte selektieren.

Tabellenansicht öffnen.

Attribut wählen.

Text-, Boolean- und Auswahllistenfeld auf NULL setzen.

"Alle aktualisieren" oder "Gewählte Objekte aktualisieren" ausführen.

Speichern und Werte in der Datenbank prüfen.


[<u>https://docs.qgis.org/3.44/en/docs/user_manual/working_with_vector/attribute_table.html#multi-edit-fields </u>](https://docs.qgis.org/3.44/en/docs/user_manual/working_with_vector/attribute_table.html#multi-edit-fields)