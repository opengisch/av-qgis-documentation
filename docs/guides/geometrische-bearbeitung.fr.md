# Édition géométrique

## Créer une géométrie

### 199 - Parallélisme

|  |  |
|----|----|
| <img src="../../assets/images/geometrische-bearbeitung/media/image34.png" style="width:3.10417in;height:2.27778in" /> | <img src="../../assets/images/geometrische-bearbeitung/media/image44.png" style="width:1.94271in;height:0.99368in" /> |
| <img src="../../assets/images/geometrische-bearbeitung/media/image5.png" style="width:3.10417in;height:0.61111in" /><img src="../../assets/images/geometrische-bearbeitung/media/image62.png" style="width:0.31771in;height:0.31771in" /> | <img src="../../assets/images/geometrische-bearbeitung/media/image41.png" style="width:2.76563in;height:1.69888in" /> |

Activer les barres d'outils « Barre d'outils de numérisation avancée » et « Outils d'accrochage ».

En mode édition, sélectionner l'outil « Ajouter un objet » et activer les outils de numérisation avancée.

Activer l'accrochage afin de pouvoir sélectionner un segment parallèlement auquel dessiner. Sélectionner « Dessiner en parallèle ».

[<u>https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#parallel-and-perpendicular-lines</u>](https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#parallel-and-perpendicular-lines)

### 200 - Points choisis librement

Activer le mode édition sur la couche de points. Sélectionner l'outil « Ajouter un objet ponctuel ». Créer un nouveau point d'un clic sur la carte.

<img src="../../assets/images/geometrische-bearbeitung/media/image43.png" style="width:3.07813in;height:1.24118in" />

### 201 - Direction

Dans les outils de numérisation avancée, il est possible d'imposer un angle (direction), pour le dessin direct ou comme ligne de construction.

<img src="../../assets/images/geometrische-bearbeitung/media/image36.png" style="width:4.30483in;height:2.23256in" />

### 202 - Indication de distance

Dans les outils de numérisation avancée, il est possible d'imposer une distance, pour le dessin direct ou comme ligne de construction.

<img src="../../assets/images/geometrische-bearbeitung/media/image42.png" style="width:4.30729in;height:2.40905in" />

### 203 - Direction et distance

Une combinaison de direction et de distance est possible — pour le dessin direct ou comme ligne de construction.

<img src="../../assets/images/geometrische-bearbeitung/media/image20.png" style="width:4.27604in;height:2.23375in" />

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr>
<td><p>Pour 201-203 : <a href="https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#absolute-reference-digitizing"><u>https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#absolute-reference-digitizing</u></a></p>
<p>Et <a href="https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#construction-mode"><u>https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#construction-mode</u></a></p></td>
</tr>
</tbody>
</table>

### 204 - Arc de cercle via rayon/centre ou deux points de l'arc

Avec la « Barre d'outils de formes », il est possible de créer des cercles via rayon et centre ou via deux points de l'arc. La même fonction n'est pas disponible pour les arcs de cercle.

<img src="../../assets/images/geometrische-bearbeitung/media/image32.png" style="width:3.38854in;height:1.3867in" />

Les arcs de cercle peuvent être créés dans la « Barre d'outils de formes » à l'aide de deux points d'arc et de l'indication du rayon.

<img src="../../assets/images/geometrische-bearbeitung/media/image6.png" style="width:2.95373in;height:1.64677in" /><img src="../../assets/images/geometrische-bearbeitung/media/image40.png" style="width:2.35524in;height:0.43179in" />

### 205 - Arc de cercle via trois points

Avec la « Barre d'outils de numérisation » standard et le paramètre « Numériser avec des courbes », l'arc de cercle est dessiné à partir de 3 points.

<img src="../../assets/images/geometrische-bearbeitung/media/image18.png" style="width:2.78646in;height:1.59359in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image49.png" style="width:1.74479in;height:1.60123in" />

### 209 - Copier des géométries existantes

Sélectionner l'entité à copier dans la table d'attributs de la couche et **Ctrl-C**.

Passer la couche cible en mode édition et ouvrir la table d'attributs correspondante. Ensuite **Ctrl-V** et adapter les valeurs d'attributs nécessaires \> Enregistrer.

### 211 - Import de points (géométrie)

<img src="../../assets/images/geometrische-bearbeitung/media/image15.png" style="width:6.5in;height:1.34722in" />

Menu **Couche \> Ajouter une couche** et sélectionner le type :

Ajouter une couche vecteur, un fichier texte délimité, une couche PostgreSQL, une couche GPX, …

Une couche peut aussi être glissée-déposée dans le projet QGIS.

### 211.1 - Éviter automatiquement les recouvrements

Dans la barre d'outils d'accrochage, activer l'« édition topologique » et définir les règles de recouvrement.

<img src="../../assets/images/geometrische-bearbeitung/media/image31.png" style="width:3.91146in;height:1.09696in" />

Dans la configuration avancée, les règles de recouvrement peuvent être définies individuellement par couche.

### 215 - Prolongation : libre

Avec l'outil de nœud, une géométrie peut être prolongée librement.

<img src="../../assets/images/geometrische-bearbeitung/media/image21.png" style="width:1.83142in;height:1.03344in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image3.png" style="width:1.77452in;height:1.03259in" />

### 216 - Prolongation par indication de distance

Avec l'outil de nœud et les outils de numérisation avancée, une géométrie peut être prolongée d'une distance déterminée.

<img src="../../assets/images/geometrische-bearbeitung/media/image1.png" style="width:3.70313in;height:1.40433in" />

### 217 - Prolongation jusqu'à l'intersection

Activer l'outil « Rogner/prolonger un objet ». Important : l'accrochage doit être activé sur toutes les couches et tous les segments.

<img src="../../assets/images/geometrische-bearbeitung/media/image22.png" style="width:4.05729in;height:1.71655in" />

[<u>https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#trim-extend-feature</u>](https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#trim-extend-feature)

**Ou**

Dans la barre d'outils d'accrochage, activer l'accrochage aux intersections.

<img src="../../assets/images/geometrische-bearbeitung/media/image4.png" style="width:1.89063in;height:0.86271in" />

Activer le mode parallèle avec les outils de numérisation avancée et l'appliquer sur la ligne existante afin de prolonger ou raccourcir le dernier nœud jusqu'à l'intersection.

<img src="../../assets/images/geometrische-bearbeitung/media/image33.png" style="width:2.59896in;height:2.11016in" />

### 218 - Rognage : libre

Activer l'outil « Rogner/prolonger un objet ».

<img src="../../assets/images/geometrische-bearbeitung/media/image22.png" style="width:4.05729in;height:1.71655in" />

[<u>https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#trim-extend-feature</u>](https://docs.qgis.org/4.2/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#trim-extend-feature)

### 219 - Rognage par indication de distance

Avec l'outil de nœud et les outils de numérisation avancée, une géométrie peut être rognée d'une distance déterminée.

<img src="../../assets/images/geometrische-bearbeitung/media/image39.png" style="width:2.65625in;height:1.71875in" />

### 220 - Rognage jusqu'à l'intersection

Activer l'outil « Rogner/prolonger un objet ». Important : l'accrochage doit être activé sur toutes les couches et tous les segments.

<img src="../../assets/images/geometrische-bearbeitung/media/image22.png" style="width:4.05729in;height:1.71655in" />

### 221 - Rotation<img src="../../assets/images/geometrische-bearbeitung/media/image62.png" style="width:0.38021in;height:0.38021in" />

<img src="../../assets/images/geometrische-bearbeitung/media/image53.png" style="width:6.5in;height:2.08333in" />

**Outils de numérisation avancée \> Rotation**.

### 222 - Déplacement<img src="../../assets/images/geometrische-bearbeitung/media/image62.png" style="width:0.38021in;height:0.38021in" />

<img src="../../assets/images/geometrische-bearbeitung/media/image48.png" style="width:3.70313in;height:1.9685in" />

Outils de numérisation avancée \> Déplacer.

### 223 - Continuer

Continuer une ligne librement. Avec l'outil de nœud, cliquer sur le « + » à l'extrémité d'une ligne et poursuivre la ligne.

<img src="../../assets/images/geometrische-bearbeitung/media/image38.png" style="width:1.23958in;height:2.42708in" />

### 224 - Supprimer un nœud

<img src="../../assets/images/geometrische-bearbeitung/media/image29.png" style="width:1.86458in;height:1.33333in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image55.png" style="width:3.04743in;height:1.94859in" />

Avec l'outil de nœud, les nœuds sélectionnés peuvent être supprimés. Il est possible de sélectionner les différents nœuds avec les flèches du clavier (ou directement par clic de souris) et de les supprimer avec **Delete**.

### 225 - Insérer un nœud

Avec l'outil de nœud, de nouveaux nœuds peuvent être ajoutés (par double-clic ou via le signe « + » sur la géométrie).

<img src="../../assets/images/geometrische-bearbeitung/media/image26.png" style="width:2.33371in;height:1.92188in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image8.png" style="width:3.21354in;height:1.15134in" />

### 226 - Copier

Copie de la géométrie existante, y compris les attributs.

Soit avec l'**outil d'action** de la barre d'outils des attributs. Si « Dupliquer l'objet et le numériser » est sélectionné, la géométrie doit être redessinée, seuls les attributs sont repris de la géométrie d'origine. Avec « Dupliquer l'objet », l'objet est dupliqué exactement au même endroit que la géométrie d'origine. L'objet copié doit ensuite être déplacé (voir ci-dessous).

<img src="../../assets/images/geometrische-bearbeitung/media/image35.png" style="width:2.86979in;height:1.03082in" /><img src="../../assets/images/geometrische-bearbeitung/media/image62.png" style="width:0.54688in;height:0.38542in" />

Ou via la barre d'outils de numérisation et les fonctions « Copier les objets », « Coller les objets ». Ensuite, l'objet inséré peut être déplacé via la barre d'outils de numérisation avancée.<img src="../../assets/images/geometrische-bearbeitung/media/image62.png" style="width:0.38021in;height:0.38021in" /><img src="../../assets/images/geometrische-bearbeitung/media/image62.png" style="width:0.38542in;height:0.38542in" />

<img src="../../assets/images/geometrische-bearbeitung/media/image23.png" style="width:3.58854in;height:0.83414in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image10.png" style="width:1.71202in;height:0.85106in" />

### 227 - Copier parallèlement

Comme au 209, dupliquer l'objet choisi avec l'outil d'action « Dupliquer l'objet ». Dans les outils de numérisation avancée, sélectionner « Déplacer l'objet », activer le mode parallèle (voir 199) et sélectionner le segment auquel l'objet doit être inséré parallèlement.

<img src="../../assets/images/geometrische-bearbeitung/media/image12.png" style="width:2.15376in;height:2.86323in" />

### 231 - Séparer : ligne-ligne

Outils de numérisation avancée \> Séparer des objets

<img src="../../assets/images/geometrische-bearbeitung/media/image47.png" style="width:1.77604in;height:1.0683in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image13.png" style="width:1.71504in;height:1.44508in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image9.png" style="width:1.44353in;height:1.07575in" />

Ou, si une couche entière doit être séparée par une autre couche : Boîte à outils \> Diviser avec des lignes.

### 234 - Séparer : ligne-surface

Comme 231.

### 236 - Séparer : surface-surface

Peut être résolu par une polyligne (suffisant selon la discussion interne). Voir 231.

### 237 - Suppression de géométries<img src="../../assets/images/geometrische-bearbeitung/media/image62.png" style="width:0.38021in;height:0.38021in" />

<img src="../../assets/images/geometrische-bearbeitung/media/image17.png" style="width:3.67849in;height:2.55711in" />

En mode édition, sélectionner la ou les géométries à supprimer avec l'outil de sélection et utiliser l'outil « Supprimer la sélection ».

### 240-242 Mesurer

240 - Mesurer une distance

241 - Mesurer un angle

242 - Mesurer une surface

<img src="../../assets/images/geometrische-bearbeitung/media/image30.png" style="width:1.97326in;height:1.41383in" />

### 244-246, 250 Fonctions d'accrochage

Activer la barre d'outils d'accrochage.

244 - Fonction d'accrochage : point d'extrémité

245 - Fonction d'accrochage : nœud

246 - Fonction d'accrochage : point d'intersection

250 - Fonction d'accrochage : point central

<img src="../../assets/images/geometrische-bearbeitung/media/image25.png" style="width:2.89483in;height:1.94271in" /> <img src="../../assets/images/geometrische-bearbeitung/media/image46.png" style="width:1.41959in;height:1.1847in" />

### 247 Fonction d'accrochage : intersection étendue

Tracer deux lignes de construction (parallèles) aux droites pour lesquelles l'intersection étendue doit être affichée. L'intersection peut alors être accrochée.

<img src="../../assets/images/geometrische-bearbeitung/media/image37.png" style="width:2.58854in;height:2.4677in" />

### 251 - Fonction d'accrochage : angle droit/quadrant

Dans la numérisation avancée, activer l'accrochage aux angles usuels. Ou utiliser des lignes de construction adaptées.

<img src="../../assets/images/geometrische-bearbeitung/media/image14.png" style="width:5.01042in;height:3.89583in" />

### 

### 252 - Fonction d'accrochage : arête/point le plus proche

Activer l'accrochage aux segments et aux nœuds.

<img src="../../assets/images/geometrische-bearbeitung/media/image7.png" style="width:3.125in;height:1.93056in" />

Pour trouver le point le plus proche de l'arête, activer le mode perpendiculaire dans la numérisation avancée.

<img src="../../assets/images/geometrische-bearbeitung/media/image19.png" style="width:2.84294in;height:1.47531in" />

### 253 - Fonction d'accrochage : pied de la perpendiculaire

Activer l'accrochage aux segments et aux nœuds.

<img src="../../assets/images/geometrische-bearbeitung/media/image7.png" style="width:3.125in;height:1.93056in" />

Pour trouver le pied de la perpendiculaire, activer le mode perpendiculaire dans la numérisation avancée.

<img src="../../assets/images/geometrische-bearbeitung/media/image19.png" style="width:2.84294in;height:1.47531in" />

### 254 - Fonction d'accrochage : centroïde 

Voir 250.

### 255 - Fonction d'accrochage pour les points (p. ex. point limite)

Les points sont considérés comme des nœuds ; on peut donc s'y accrocher. Dans les options avancées, les paramètres peuvent être définis individuellement pour chaque couche. Il est donc possible, par exemple, de ne s'accrocher qu'à la couche des points limites.

<img src="../../assets/images/geometrische-bearbeitung/media/image31.png" style="width:3.91146in;height:1.09696in" />

<img src="../../assets/images/geometrische-bearbeitung/media/image45.png" style="width:6.5in;height:1.50449in" />

### 258 - La sélection dans la table met en évidence la géométrie sur la carte

La carte et la table sont liées.

<img src="../../assets/images/geometrische-bearbeitung/media/image52.png" style="width:2.65698in;height:2.38021in" />

Outils de sélection dans la table : <img src="../../assets/images/geometrische-bearbeitung/media/image28.png" style="width:2.26847in;height:0.38989in" />

### 259 - La sélection sur la carte met en évidence dans la table

Voir 258

Outils de sélection sur la carte : <img src="../../assets/images/geometrische-bearbeitung/media/image54.png" style="width:1.78324in;height:0.39923in" />

### 264 - Symbole orienté : parallèle à la ligne

Les symboles sont très flexibles. Les décalages parallèles à la ligne sont clairement possibles. Les symboles peuvent aussi être tournés.

Accéder aux paramètres via le panneau de mise en forme des couches (ou via les propriétés de la couche \> Symbologie).

<img src="../../assets/images/geometrische-bearbeitung/media/image51.png" style="width:4.4865in;height:2.79688in" />

<img src="../../assets/images/geometrische-bearbeitung/media/image16.png" style="width:2.83854in;height:1.97504in" />

Si nécessaire, pour les lignes de marques et les lignes en pointillés, chaque marque peut être ajustée manuellement.

De plus, via le générateur de géométries, il n'y a quasiment aucune limite.

### 265 - Symbole orienté : libre

Les symboles sont très flexibles. Via le générateur de géométries, il n'y a quasiment aucune limite.

Si les symboles doivent être positionnés totalement librement, on peut recourir aux annotations/étiquettes/géométries de points supplémentaires.

### 266 - Symbole orienté : saisir l'angle de rotation

Les symboles sont très flexibles. Les symboles peuvent aussi être tournés. <img src="../../assets/images/geometrische-bearbeitung/media/image2.png" style="width:2.45703in;height:3.45313in" />

### 268 - Texte orienté : parallèle à la ligne

Par défaut, le texte est placé parallèlement à la ligne.

<img src="../../assets/images/geometrische-bearbeitung/media/image11.png" style="width:2.26246in;height:1.78683in" />

### 269 - Texte orienté : libre

Les étiquettes peuvent en outre être placées, tournées, etc. individuellement via la barre d'outils d'étiquetage.

<img src="../../assets/images/geometrische-bearbeitung/media/image24.png" style="width:3.46875in;height:0.44792in" />

### 270 - Texte orienté : saisir l'angle de rotation

La rotation peut dépendre de la géométrie (polygones), ou être verticale/horizontale. Pour les lignes, il y a aussi parallèle à la ligne, curved ou horizontal.

<img src="../../assets/images/geometrische-bearbeitung/media/image27.png" style="width:6.5in;height:2.11111in" />

Ou lorsque le mode « Distance depuis le centre » est sélectionné :

<img src="../../assets/images/geometrische-bearbeitung/media/image50.png" style="width:4.1513in;height:4.07813in" />
