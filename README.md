[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/pAqJXfzR)

05.03.2026: 
-Ich habe erstmal das HTML-Grundgerüst eingefügt. 
-Ich habe den Titel geschrieben.

12.03.2026:
-Ich habe ein Inhaltsverzeichnis für meine Website erstellt.
-Ich habe passende Titel für die verschiedenen Abschnitte über Dinosaurier geschrieben.
-Ich habe das Inhaltsverzeichnis mit einer Liste übersichtlich dargestellt.
-Ich habe das Kapitel „Einführung in die Dinosaurier“ geschrieben und erklärt, was Dinosaurier sind, wann sie lebten und wie sie aufgebaut waren.
-Ich habe das Kapitel „Die Zeit der Dinosaurier“ erstellt und die Erdzeitalter Trias, Jura und Kreidezeit mit den entsprechenden Zeiträumen beschrieben.
-Ich habe das Kapitel „Nahrung der Dinosaurier“ verfasst und die verschiedenen Ernährungsweisen (Pflanzenfresser, Fleischfresser, Allesfresser) erklärt.
-Ich habe das Kapitel „Fossilien und Entdeckungen“ geschrieben, erklärt, wie Fossilien entstehen, was Paläontologen machen und eine wichtige Entdeckung (Ichthyosaurus-Fund) beschrieben.
-Ich habe das Kapitel „Das Aussterben der Dinosaurier“ erstellt, den Meteoriten-Einschlag beim Chicxulub-Kraters und mögliche vulkanische Ursachen beschrieben.
-Ich habe das Kapitel „Spannende Fakten über Dinosaurier“ geschrieben, inklusive Informationen über Vögel als Nachfahren, Federn, Größenunterschiede, Eier/Nester und Farben.
-Ich habe noch einen Abschnitt Namens "Zusammenfassung" in mein Inhaltsverzeichnis eingefügt.

13.03.2026: 
-Zusammenfassung geschrieben
-Arten von Dinosaurier: Steckbriefe erstellt von den typischen Dinosauriern. 
--> Bei diesem Abschnitt habe ich weiter an der Kategorie „Arten von Dinosauriern“ gearbeitet.
Meine Idee war, für jeden Dinosaurier einen Steckbrief in Hochformat zu erstellen, damit die wichtigsten Informationen vo den wichtigsten Dinosauriern übersichtlich dargestellt werden.
Dazu gehören Themen wie Ernährung, Gewicht, Länge, Zeit, Lebensraum, Art, Besonderheiten und spannende Fakten, für die ich rechechieren musste.
Für die Gestaltung der Tabellen habe ich CSS verwendet, --> Dafür habe ich Quellen gebraucht um zu verstehen wie ich diese Tabellen gestalten möchte
-Ich habe den Text bei "Einführung von Dinosauriern" verbessert, da er einwenig komisch geschrieben war und ich es ausführlicher schreiben wollte.
-Ich habe bei „Arten von Dinosauriern“ die einzelnen Dinosaurier als Unterpunkte hinzugefügt. So sieht das Inhaltsverzeichnis übersichtlicher aus und die Untergruppen sind klar erkennbar.
-„Ich habe ein CSS-Grundgerüst erstellt, in dem ich alle Tabellenstile und andere Gestaltungselemente eintragen kann. Zusätzlich habe ich scroll-behavior: smooth; eingefügt, damit das Scrollen zu den Abschnitten flüssig erfolgt.“

Änderung der Untertitel „Arten von Dinosaurier“:
-Die Untertitel wurden von <h3> zu <h4> geändert.
In der CSS-Datei für h4 Folgendes hinzugefügt:
	•	font-family → Schriftart der Untertitel geändert (z. B. „Fredoka One“).
	•	font-size → Schriftgrössr angepasst.
	•	margin-bottom → Abstand gemacht, damit die Tabelle oder der Text nicht zu nah am Titel steht.
Zweck:
	•	Schriftart der Untertitel individuell gestaltet.
	•	Ich habe den Abstand zwischen Titel und Tabelle angepasst.

IDs für Dinosaurier-Unterpunkte
	•	Beispiel: <h4 id="tyrannosaurus">Tyrannosaurus Rex</h4>
	•	Funktionsweise: Sprungziel für das Inhaltsverzeichnis <a href="#tyrannosaurus">Tyrannosaurus Rex</a>
	•	Quelle: MDN id-Attribut￼

Bilder für Steckbriefe
	•	Beispiel:
<img src="https://image.geo.de/35946962/t/gm/v4/w1440/r1.7778/-/trex-g-99311107.jpg" alt="Tyrannosaurus Rex">

16.03.2026: 
Weiterarbeit an der Zeit der Dinosaurier:
Heute habe ich daran gearbeitet, zu den drei Erdzeitaltern Trias, Jura und Kreidezeit passende Videos auf der Website einzufügen.

Schritt 1: Videos recherchieren
	•	Ich habe auf YouTube nach Videos gesucht, die die Zeitperioden erklären.
	•	Herausforderungen:
	•	Viele Videos waren zu lang.
	•	Manche erklärten die Perioden nicht genau.
	•	Quellen / Links:
	•	Trias: YouTube Video Trias￼
	•	Jura: YouTube Video Jura￼
	•	Kreidezeit: YouTube Video Kreidezeit￼

Schritt 2: Videos auf der Website einbauen
	•	Zuerst wollte ich die Videos direkt einbetten (<iframe>), aber einige Videos konnten nicht eingebettet werden.
	•	Lösung: YouTube-Thumbnails verwenden, die auf das Video verlinken.
	•	Beispiel:
	<a href="https://www.youtube.com/watch?v=wJz2upbA3QA" target="_blank">
  <img src="https://biermann-medizin.de/content/uploads/2025/03/newsimage404428-scaled.jpg" alt="Trias Video">
</a>
	•	Erklärung:
	•	<a> → klickbarer Link
	•	href → URL des Videos
	•	target="_blank" → öffnet Link in neuem Tab
	•	<img src> → Thumbnail-Bild, alt → Beschreibung

Schritt 3: Boxen mit CSS gestalten
	•	Ich habe Boxen für jede Zeitperiode erstellt (<div class="periode-box">) und mit CSS gestaltet.
	•	CSS-Eigenschaften:
	•	display: flex; → Boxen nebeneinander
	•	margin / padding → Abstände innerhalb der Boxen
	•	width / height → Größe der Boxen
	•	Quellen / Referenzen:
	•	MDN Flexbox￼
	•	MDN Box Model￼

Schritt 4: IDs für die Abschnitte
	•	Jede Box hat eine eigene ID, um Sprungziele vom Inhaltsverzeichnis zu ermöglichen:
	•	Trias: id="trias"
	•	Jura: id="jura"
	•	Kreidezeit: id="kreidezeit"
	•	Funktionsweise: <a href="#jura">Jura</a> scrollt direkt zu diesem Abschnitt.


26.03.2026:
Heute habe ich für jeden Dinosaurier eine eigene <div class="dino-box"> angelegt. Innerhalb der Box habe ich den Inhalt in eine <div class="dino-content"> gepackt, damit die Tabelle mit den Informationen und das Bild nebeneinander stehen.
Ich habe CSS geschrieben, um Flexbox für .dino-content zu nutzen. Die Tabellen habe ich mit flex: 1 1 48% und table-layout: fixed gleichmäßig gemacht. Die Bilder habe ich ebenfalls flexibel mit flex: 1 1 48% eingebunden, damit sie sich der Boxgröße anpassen. So sollten Tabelle und Bild nebeneinander stehen und die Abstände einheitlich sein.

Beim Brachiosaurus ist mir dann aufgefallen, dass die Tabelle ein max-width: 800px hatte. Dadurch konnte sie nie die volle Breite der Box nutzen und das Layout wirkte ungleichmäßig – die Tabelle war zu schmal und das Bild daneben zu gross. Ich habe das Problem erkannt und den max-width entfernt, sodass die Tabelle jetzt flexibel ist und zusammen mit dem Bild die Box gleichmässig füllt.

27.03.2026: 
Heute habe ich das Design meiner Website stark verbessert, da die Seite vorher wie ein Word-Dokument aussah und das Inhaltsverzeichnis unübersichtlich war.

Gestaltung des Inhaltsverzeichnisses mit CSS

Ich habe mit CSS eine lange grüne Fläche auf der linken Seite erstellt, die über die ganze Höhe der Website geht. Dort befindet sich jetzt das Inhaltsverzeichnis. Dadurch sieht die Website übersichtlicher und moderner aus.

Am Anfang gab es mehrere Probleme:
	•	Das Inhaltsverzeichnis hatte keine Punkte
	•	Die Liste war nicht richtig positioniert
	•	Einige CSS-Eigenschaften waren falsch geschrieben
	•	Das Layout sah unordentlich aus

Das Problem mit den fehlenden Punkten entstand, weil ich im CSS die Eigenschaft list-style nicht richtig gesetzt hatte. Ohne diese Eigenschaft zeigt der Browser keine Punkte vor den Listenelementen an.

Ich habe das Problem gelöst, indem ich folgende Eigenschaft hinzugefügt habe:
ul{
list-style: disc;
padding-left: 18px;
}
Bedeutung:
	•	list-style: disc; → zeigt normale Punkte vor der Liste an
	•	padding-left → macht Abstand vom Rand, damit die Punkte sichtbar sind

Quelle:
https://developer.mozilla.org/de/docs/Web/CSS/list-style

Linke Seitenleiste erstellen
Damit das Inhaltsverzeichnis immer links sichtbar bleibt, habe ich eine feste Fläche mit CSS erstellt:
body::before{
content:"";
position: fixed;
left:0;
top:0;
width:220px;
height:100vh;
background:#1b5e20;
}
Bedeutung:
	•	position: fixed; → die Fläche bleibt beim Scrollen immer sichtbar
	•	left:0; top:0; → Position ganz links oben
	•	width → Breite der Seitenleiste
	•	height:100vh; → Höhe der ganzen Bildschirmseite
	•	background → Hintergrundfarbe

Quelle:
https://developer.mozilla.org/de/docs/Web/CSS/position

Pseudo-Element Erklärung:
https://developer.mozilla.org/de/docs/Web/CSS/::before

Abstände für die Website anpassen
Damit der Text nicht unter der linken Leiste steht, habe ich beim body einen Abstand gemacht:
body{
padding-left:260px;
}
Bedeutung:
	•	padding-left → verschiebt den ganzen Inhalt nach rechts
Quelle:
https://developer.mozilla.org/de/docs/Web/CSS/padding

Problem mit den Untergruppen bei „Arten von Dinosauriern“

Ein weiteres Problem war das Inhaltsverzeichnis bei den Untergruppen der Dinosaurier (z. B. T-Rex, Triceratops usw.).

Am Anfang hatte ich ul statt li verwendet, wodurch die Liste nicht richtig funktioniert hat.

Falsch:
<ul>
<ul>T-Rex</ul>
<ul>Triceratops</ul>
</ul>
Richtig: 
<ul>
<li>T-Rex</li>
<li>Triceratops</li>
</ul>
Bedeutung:
	•	ul → erstellt eine ungeordnete Liste
	•	li → definiert ein einzelnes Listenelement
	•	li muss immer innerhalb von ul stehen

Quelle:
https://developer.mozilla.org/de/docs/Web/HTML/Element/ul

https://developer.mozilla.org/de/docs/Web/HTML/Element/li

Links im Inhaltsverzeichnis gestalten

Ich habe auch die Links schöner gemacht:
ul a{
display:block;
text-decoration:none;
color:white;
}
Bedeutung:
	•	display:block → der Link nimmt die ganze Breite ein
	•	text-decoration:none → entfernt die Unterstreichung
	•	color → Farbe des Textes

Quelle:
https://developer.mozilla.org/de/docs/Web/CSS/display
https://developer.mozilla.org/de/docs/Web/CSS/text-decoration

Hover Effekt hinzufügen
Wenn man mit der Maus über einen Link fährt, ändert sich die Farbe:
Bedeutung:
	•	:hover → Effekt wenn man mit der Maus über ein Element fährt
	•	color → ändert die Textfarbe

Ergebnis
Durch diese Änderungen:
	•	sieht die Website nicht mehr wie ein Word-Dokument aus
	•	das Inhaltsverzeichnis ist übersichtlich
	•	die Untergruppen funktionieren korrekt
	•	die Navigation ist einfacher
	•	das Design wirkt moderner

Quelle:
https://developer.mozilla.org/de/docs/Web/CSS/:hover




Quellen
Dinosaurier Informationen
National Geographic Kids:
https://kids.nationalgeographic.com/animals/prehistoric/dinosaurs
Britannica – Dinosaur:
https://www.britannica.com/animal/dinosaur
Smithsonian National Museum of Natural History:
https://naturalhistory.si.edu

Videos
Trias:
https://www.youtube.com/watch?v=wJz2upbA3QA
Jura:
https://www.youtube.com/watch?v=d4Z-glC0vXg
Kreidezeit:
https://www.youtube.com/watch?v=zyd6mgLK6Q0

HTML und CSS Programmierung

HTML Grundlagen:
https://developer.mozilla.org/de/docs/Web/HTML

CSS Grundlagen:
https://developer.mozilla.org/de/docs/Web/CSS

Tabellen:
https://developer.mozilla.org/de/docs/Web/HTML/Element/table

text-align:
https://developer.mozilla.org/de/docs/Web/CSS/text-align

padding:
https://developer.mozilla.org/de/docs/Web/CSS/padding

border:
https://developer.mozilla.org/de/docs/Web/CSS/border

border-collapse:
https://developer.mozilla.org/de/docs/Web/CSS/border-collapse

border-radius:
https://developer.mozilla.org/de/docs/Web/CSS/border-radius

box-shadow:
https://developer.mozilla.org/de/docs/Web/CSS/box-shadow

display:
https://developer.mozilla.org/de/docs/Web/CSS/display

Flexbox Layout:
https://developer.mozilla.org/de/docs/Web/CSS/CSS_flexible_box_layout

justify-content:
https://developer.mozilla.org/de/docs/Web/CSS/justify-content

gap:
https://developer.mozilla.org/de/docs/Web/CSS/gap

scroll-behavior:
https://developer.mozilla.org/de/docs/Web/CSS/Reference/Properties/scroll-behavior


MEINE QUELLEN: 
CSS FÜR DIE TABELLE MEINER DINOSAURIER: 
text-align:
https://developer.mozilla.org/de/docs/Web/CSS/text-align
padding:
https://developer.mozilla.org/de/docs/Web/CSS/padding
border-collapse:
https://developer.mozilla.org/de/docs/Web/CSS/border-collapse
Tabellen‑CSS allgemein:
https://developer.mozilla.org/de/docs/Web/HTML/Element/table

INTERAKTIVES INHALTSVERZEICHNIS:
Wie ich das scrollen smooth gemacht habe: 
https://developer.mozilla.org/de/docs/Web/CSS/Reference/Properties/scroll-behavior 

