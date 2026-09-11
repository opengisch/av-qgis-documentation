# Geometrische Bearbeitung

## Geometrie erstellen

### 199 - Parallelität

|  |  |
|----|----|
| <img src="../../assets/images/geometrische-bearbeitung/media/image34.png" style="width:3.10417in;height:2.27778in" /> | <img src="../../assets/images/geometrische-bearbeitung/media/image44.png" style="width:1.94271in;height:0.99368in" /> |
| <img src="../../assets/images/geometrische-bearbeitung/media/image5.png" style="width:3.10417in;height:0.61111in" /><img src="../../assets/images/geometrische-bearbeitung/media/image62.png" style="width:0.31771in;height:0.31771in" /> | <img src="../../assets/images/geometrische-bearbeitung/media/image41.png" style="width:2.76563in;height:1.69888in" /> |

Werkzeugleisten “Erweiterte Digitalisierungswerkzeugleiste” und “Einrastwerkzeuge” aktivieren.

Im Editiermodus das Werkzeug “Objekt hinzufügen” auswählen und die erweiterten Digitalisierungswerkzeuge einschalten.

Snapping aktivieren, damit ein Segment ausgewählt werden kann, zu welchem parallel gezeichnet wird. Parallel zeichnen auswählen.

[<u>https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#parallel-and-perpendicular-lines</u>](https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#parallel-and-perpendicular-lines)

### 200 - Frei gewählte Punkte

Auf Punktlayer den Editiermodus einschalten. Das Werkzeug “Punktobjekt hinzufügen” auswählen. Auf der Karte mit einem Klick einen neuen Punkt erstellen.

<img src="../../assets/images/geometrische-bearbeitung/media/image43.png" style="width:3.07813in;height:1.24118in" />

### 201 - Richtung

In den erweiterten Digitalisierungswerkzeugen kann ein Winkel (Richtung) vorgegeben werden. Fürs direkte Zeichnen oder als Konstruktionslinie.

<img src="../../assets/images/geometrische-bearbeitung/media/image36.png" style="width:4.30483in;height:2.23256in" />

### 202 - Abstandsangaben

In den erweiterten Digitalisierungswerkzeugen kann ein Abstand vorgegeben werden. Fürs direkte Zeichnen oder als Konstruktionslinie.

<img src="../../assets/images/geometrische-bearbeitung/media/image42.png" style="width:4.30729in;height:2.40905in" />

### 203 - Richtung und Abstand

Eine Kombination aus Richtung und Abstand ist möglich - fürs direkte Zeichnen oder als Konstruktionslinie.

<img src="../../assets/images/geometrische-bearbeitung/media/image20.png" style="width:4.27604in;height:2.23375in" />

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr>
<td><p>Für 201-203: <a href="https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#absolute-reference-digitizing"><u>https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#absolute-reference-digitizing</u></a></p>
<p>Und <a href="https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#construction-mode"><u>https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#construction-mode</u></a></p></td>
</tr>
</tbody>
</table>

### 204 - Kreisbogen über Radius/Mittelpunkt oder zwei Bogenpunkte

Mit der “Werkzeugleiste für Formen” können Kreise über Radius und Mittelpunkt oder zwei Bogenpunkte erstellt werden. Die gleiche Funktion ist für Kreisbögen nicht verfügbar.

<img src="../../assets/images/geometrische-bearbeitung/media/image32.png" style="width:3.38854in;height:1.3867in" />

Kreisbögen können in der “Werkzeugleiste für Formen” mit zwei Bogenpunkten und der Angabe des Radius erstellt werden.

<img src="../../assets/images/geometrische-bearbeitung/media/image6.png" style="width:2.95373in;height:1.64677in" /><img src="../../assets/images/geometrische-bearbeitung/media/image40.png" style="width:2.35524in;height:0.43179in" />

### 205 - Kreisbogen über drei Punkte

Mit der Standard “Digitalisierungswerkzeugleiste” und der Einstellung “mit Kurven digitalisieren” wird der Kreisbogen wird über 3 Punkte gezeichnet.

<img src="../../assets/images/geometrische-bearbeitung/media/image18.png" style="width:2.78646in;height:1.59359in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image49.png" style="width:1.74479in;height:1.60123in" />

### 209 - Bestehende Geometrien kopieren

Zu kopierendes Feature in der Attributtabelle des Layers selektieren und **Ctrl-C**.

Ziellayer in Editiermodus schalten und die entsprechende Attributtabelle öffnen. Anschliessend **Ctrl-V** und die nötigen Attributwerte anpassen \> Speichern.

### 211 - Punktimport (Geometrie)

<img src="../../assets/images/geometrische-bearbeitung/media/image15.png" style="width:6.5in;height:1.34722in" />

Menu **Layer \> Layer hinzufügen** und Typ auswählen:

Vektorlayer, Getrennte Textdatei, PostgreSQL-Layer, GPX-Layer, … hinzufügen.

Ein Layer kann auch über Drag&Drop ins QGIS-Projekt gezogen werden.

### 211.1 - Überlappung automatisch vermeiden

In der Einrastwerkzeugleiste das “topologische Editieren” aktivieren und die Überlappungsregeln festlegen.

<img src="../../assets/images/geometrische-bearbeitung/media/image31.png" style="width:3.91146in;height:1.09696in" />

Bei der erweiterten Konfiguration können die Überlappungsregeln pro Layer individuell festgelegt werden.

### 215 - Verlängerung: frei

Mit dem Stützpunktwerkzeug kann eine Geometrie frei verlängert werden.

<img src="../../assets/images/geometrische-bearbeitung/media/image21.png" style="width:1.83142in;height:1.03344in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image3.png" style="width:1.77452in;height:1.03259in" />

### 216 - Verlängerung nach Abstandsangabe

Mit Stützpunktwerkzeug und den erweiterten Digitalisierungswerkzeugen kann eine Geometrie um einen bestimmten Abstand verlängert werden.

<img src="../../assets/images/geometrische-bearbeitung/media/image1.png" style="width:3.70313in;height:1.40433in" />

### 217 - Verlängerung bis zu Schnittpunkt

“Objekt abschneiden/verlängern Werkzeug” aktivieren. Wichtig: Einrasten muss auf alle Layer und Segmente aktiviert sein.

<img src="../../assets/images/geometrische-bearbeitung/media/image22.png" style="width:4.05729in;height:1.71655in" />

[<u>https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#trim-extend-feature</u>](https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#trim-extend-feature)

**Oder**

In der Einrastwerkzeugleiste das Einrasten auf Schnittpunkte aktivieren.

<img src="../../assets/images/geometrische-bearbeitung/media/image4.png" style="width:1.89063in;height:0.86271in" />

Mit den erweiterten Digitalisierungswerkzeugen den Parallelmodus aktivieren und auf der bestehenden Linie anwenden um den letzten Knotenpunkt bis zum Schnittpunkt zu verlängern oder verkürzen.

<img src="../../assets/images/geometrische-bearbeitung/media/image33.png" style="width:2.59896in;height:2.11016in" />

### 218 - Trimmung: frei

“Objekt abschneiden/verlängern Werkzeug” aktivieren.

<img src="../../assets/images/geometrische-bearbeitung/media/image22.png" style="width:4.05729in;height:1.71655in" />

[<u>https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#trim-extend-feature</u>](https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#trim-extend-feature)

### 219 - Trimmung nach Abstandsangabe

Mit dem Stützpunktwerkzeug und den erweiterten Digitalisierungswerkzeuge kann eine Geometrie um einen bestimmten Abstand getrimmt werden.

<img src="../../assets/images/geometrische-bearbeitung/media/image39.png" style="width:2.65625in;height:1.71875in" />

### 220 - Trimmung bis zu Schnittpunkt

“Objekt abschneiden/verlängern Werkzeug” aktivieren. Wichtig: Einrasten muss auf alle Layer und Segmente aktiviert sein.

<img src="../../assets/images/geometrische-bearbeitung/media/image22.png" style="width:4.05729in;height:1.71655in" />

### 221 - Drehen<img src="../../assets/images/geometrische-bearbeitung/media/image62.png" style="width:0.38021in;height:0.38021in" />

<img src="../../assets/images/geometrische-bearbeitung/media/image53.png" style="width:6.5in;height:2.08333in" />

**Erweiterte Digitalisierungswerkzeuge \> Drehen**.

### 222 - Verschieben<img src="../../assets/images/geometrische-bearbeitung/media/image62.png" style="width:0.38021in;height:0.38021in" />

<img src="../../assets/images/geometrische-bearbeitung/media/image48.png" style="width:3.70313in;height:1.9685in" />

Erweiterte Digitalisierungswerkzeuge \> Verschieben.

### 223 - Fortsetzen

Gerade beliebig fortsetzen. Mit dem Stützpunktwerkzeug ans Ende einer Linie, auf das “+” klicken und Linie fortsetzen.

<img src="../../assets/images/geometrische-bearbeitung/media/image38.png" style="width:1.23958in;height:2.42708in" />

### 224 - Stützpunkt löschen

<img src="../../assets/images/geometrische-bearbeitung/media/image29.png" style="width:1.86458in;height:1.33333in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image55.png" style="width:3.04743in;height:1.94859in" />

Mit dem Stützpunktwerkzeug können ausgewählte Stützpunkte gelöscht werden. Über die Pfeiltasten der Tastatur (oder direkt über Mausklick) können die verschiedenen Stützpunkte angewählt und mit **Delete** gelöscht werden.

### 225 - Stützpunkt einfügen

Mit dem Stützpunktwerkzeug können neue Stützpunkte hinzugefügt werden (über Doppelklick, oder über das "+"-Zeichen auf der Geometrie)

<img src="../../assets/images/geometrische-bearbeitung/media/image26.png" style="width:2.33371in;height:1.92188in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image8.png" style="width:3.21354in;height:1.15134in" />

### 226 - Kopieren

Kopie der bestehenden Geometrie inkl. Attribute.

Entweder mit **Aktionswerkzeug** aus der Attributwerkzeugleiste. Falls “Objekt duplizieren und digitalisieren” ausgewählt wird, muss die Geometrie neu gezeichnet werden, nur die Attribute werden von der Ursprungsgeometrie übernommen. Bei “Objekt duplizieren” wird das Objekt exakt am selben Ort dupliziert wie die Ursprungsgeometrie. Das kopierte Objekt muss anschliessend verschoben werden (siehe unten).

<img src="../../assets/images/geometrische-bearbeitung/media/image35.png" style="width:2.86979in;height:1.03082in" /><img src="../../assets/images/geometrische-bearbeitung/media/image62.png" style="width:0.54688in;height:0.38542in" />

Oder über die Digitalisierungswerkzeugleiste und die Funktionen “Objekte kopieren”, “Objekte einfügen”. Anschliessend kann über die erweiterte Digitalisierungswerkzeugleiste das eingefügte Objekt verschoben werden.<img src="../../assets/images/geometrische-bearbeitung/media/image62.png" style="width:0.38021in;height:0.38021in" /><img src="../../assets/images/geometrische-bearbeitung/media/image62.png" style="width:0.38542in;height:0.38542in" />

<img src="../../assets/images/geometrische-bearbeitung/media/image23.png" style="width:3.58854in;height:0.83414in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image10.png" style="width:1.71202in;height:0.85106in" />

### 227 - Parallel kopieren

Wie unter 209 im Aktionswerkzeug “Objekt duplizieren” das gewählte Objekt duplizieren. In den erweiterten Digitalisierungswerkzeugen “Objekt verschieben” auswählen, den Parallelmodus aktivieren (siehe 199) und das Segment, zu welchem parallel eingefügt werden soll, anwählen.

<img src="../../assets/images/geometrische-bearbeitung/media/image12.png" style="width:2.15376in;height:2.86323in" />

### 231 - Teilen: Gerade-Gerade

Erweiterte Digitalisierungswerkzeuge \> Objekte zerteilen

<img src="../../assets/images/geometrische-bearbeitung/media/image47.png" style="width:1.77604in;height:1.0683in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image13.png" style="width:1.71504in;height:1.44508in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image9.png" style="width:1.44353in;height:1.07575in" />

Oder, falls ein ganzes Layer durch ein anderes Layer zerteilt werden soll: Werkzeugkiste \> Mit Linien teilen.

### 234 - Teilen: Gerade-Fläche

Wie 231.

### 236 - Teilen: Fläche-Fläche

Kann durch eine Polylinie gelöst werden (ausreichend laut interner Diskussion). Siehe 231.

### 237 - Löschen von Geometrien<img src="../../assets/images/geometrische-bearbeitung/media/image62.png" style="width:0.38021in;height:0.38021in" />

<img src="../../assets/images/geometrische-bearbeitung/media/image17.png" style="width:3.67849in;height:2.55711in" />

Im Editiermodus mit dem Selektierwerkzeug die zu löschende-n Geometrie-n auswählen und das Werkzeug “Ausgewähltes löschen” verwenden.

### 240-242 Messen

240 - Messen von Entfernung

241 - Messen von Winkel

242 - Messen von Fläche

<img src="../../assets/images/geometrische-bearbeitung/media/image30.png" style="width:1.97326in;height:1.41383in" />

### 244-246, 250 Fangfunktionen

Einrastwerkzeugleiste aktivieren.

244 - Fangfunktion: Endpunkt

245 - Fangfunktion: Stützpunkt

246 - Fangfunktion: Schnittpunkt

250 - Fangfunktion: Zentrumspunkt

<img src="../../assets/images/geometrische-bearbeitung/media/image25.png" style="width:2.89483in;height:1.94271in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image46.png" style="width:1.41959in;height:1.1847in" />

### 247 Fangfunktion: Erweiterter Schnittpunkt

Zwei Konstruktionslinien (parallel) zu den Geraden ziehen, für welche der erweiterte Schnittpunkt angezeigt werden soll. Auf den Schnittpunkt kann gesnappt werden.

<img src="../../assets/images/geometrische-bearbeitung/media/image37.png" style="width:2.58854in;height:2.4677in" />

### 251 - Fangfunktion: Rechtwinkel/Quadrant

In der erweiterten Digitalisierung das Einrasten auf übliche Winkel aktivieren. Oder mit entsprechenden Konstruktionslinien arbeiten.

<img src="../../assets/images/geometrische-bearbeitung/media/image14.png" style="width:5.01042in;height:3.89583in" />

### 

### 252 - Fangfunktion: Kante/nächstgelegener Punkt

Snapping an Segment und Vertex aktivieren.

<img src="../../assets/images/geometrische-bearbeitung/media/image7.png" style="width:3.125in;height:1.93056in" />

Um den nächstgelegenen Punkt an der Kante zu finden, in der erweiterten Digitalisierung den senkrechten Modus einschalten.

<img src="../../assets/images/geometrische-bearbeitung/media/image19.png" style="width:2.84294in;height:1.47531in" />

### 253 - Fangfunktion: Lotfusspunkt

Snapping an Segment und Vertex aktivieren.

<img src="../../assets/images/geometrische-bearbeitung/media/image7.png" style="width:3.125in;height:1.93056in" />

Um den Lotfusspunkt zu finden, in der erweiterten Digitalisierung den senkrechten Modus einschalten.

<img src="../../assets/images/geometrische-bearbeitung/media/image19.png" style="width:2.84294in;height:1.47531in" />

### 254 - Fangfunktion: Schwerpunkt 

Siehe 250.

### 255 - Fangfunktion für Punkte (z.B. Grenzpunkt)

Punkte gelten als Stützpunkte, man kann also darauf snappen. In den erweiterten Optionen können die Einstellungen für jedes Layer individuell vorgenommen werden. Es könnte also z.B. nur auf das Grenzpunktlayer gesnappt werden.

<img src="../../assets/images/geometrische-bearbeitung/media/image31.png" style="width:3.91146in;height:1.09696in" />

<img src="../../assets/images/geometrische-bearbeitung/media/image45.png" style="width:6.5in;height:1.50449in" />

### 258 - Auswahl in Tabelle markiert Geometrie in Karte

Karte und Tabelle sind verknüpft.

<img src="../../assets/images/geometrische-bearbeitung/media/image52.png" style="width:2.65698in;height:2.38021in" />

Auswahlwerkzeuge in der Tabelle: <img src="../../assets/images/geometrische-bearbeitung/media/image28.png" style="width:2.26847in;height:0.38989in" />

### 259 - Auswahl in Karte markiert in Tabelle

Siehe 258

Auswahlwerkzeuge in der Karte: <img src="../../assets/images/geometrische-bearbeitung/media/image54.png" style="width:1.78324in;height:0.39923in" />

### 264 - Orientiertes Symbol: Parallel zu Gerade

Symbole sind sehr flexibel. Offsets parallel der Linie sind klar möglich. Symbole können auch rotiert werden.

Über das Layer Styling Panel (oder über die Eigenschaften des Layers \> Symbologie) auf die Einstellungen zugreifen.

<img src="../../assets/images/geometrische-bearbeitung/media/image51.png" style="width:4.4865in;height:2.79688in" />

<img src="../../assets/images/geometrische-bearbeitung/media/image16.png" style="width:2.83854in;height:1.97504in" />

Wenn nötig können bei Markierungslinien und gestrichelten Linien einzelne Markierungen noch manuell justiert werden.

Zusätzlich sind über den Geometriegenerator sind fast keine Grenzen gesetzt.

### 265 - Orientiertes Symbol: Frei

Symbole sind sehr flexibel. Über den Geometriegenerator sind fast keine Grenzen gesetzt.

Falls Symbole komplett frei gesetzt werden sollen, kann man auf Annotations/Labels/zusätzliche Punktgeometrien zurückgreifen.

### 266 - Orientiertes Symbol: Drehwinkel eingeben

Symbole sind sehr flexibel. Symbole können auch rotiert werden. <img src="../../assets/images/geometrische-bearbeitung/media/image2.png" style="width:2.45703in;height:3.45313in" />

### 268 - Orientierter Text: Parallel zu Gerade

Per default wird Text parallel der Linien gesetzt.

<img src="../../assets/images/geometrische-bearbeitung/media/image11.png" style="width:2.26246in;height:1.78683in" />

### 269 - Orientierter Text: Frei

Labels können zusätzlich über die Label Toolbar individuell platziert, rotiert, etc. werden.

<img src="../../assets/images/geometrische-bearbeitung/media/image24.png" style="width:3.46875in;height:0.44792in" />

### 270 - Orientierter Text: Drehwinkel eingeben

Rotation kann geometrieabhängig gemacht werden (Polygons), oder vertikal/horizontal. Bei Linien zusätzlich parallel der Linie, curved oder horizontal.

<img src="../../assets/images/geometrische-bearbeitung/media/image27.png" style="width:6.5in;height:2.11111in" />

Oder wenn "Abstand vom Zentrum" als Modus ausgewählt wird:

<img src="../../assets/images/geometrische-bearbeitung/media/image50.png" style="width:4.1513in;height:4.07813in" />
