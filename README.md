[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/pAqJXfzR)

05.03.2026
Ich habe mit meiner Website begonnen und das HTML-Grundgerüst erstellt. Dafür habe ich die Grundstruktur mit <!DOCTYPE html>, <html>, <head> und <body> erstellt. Danach habe Ich den Titel meiner Website geschrieben.


12.03.2026
Ich habe ein Inhaltsverzeichnis erstellt. Dafür habe ich <ul> (unordered list) und <li> (list item) verwendet.

<ul> erstellt eine Liste ohne Reihenfolge. <li> ist ein einzelner Punkt in der Liste.

Problem: Die Liste wurde zuerst falsch angezeigt, weil ich falsche Tags verwendet habe.

Lösung: Ich habe gelernt, dass <li> immer innerhalb von <ul> stehen muss.

Quelle:
MDN Web Docs – HTML Listen
https://developer.mozilla.org/de/docs/Web/HTML/Element/ul
https://developer.mozilla.org/de/docs/Web/HTML/Reference/Elements/li


-Ich habe passende Titel für die verschiedenen Abschnitte über Dinosaurier geschrieben.
-Ich habe das Kapitel „Einführung in die Dinosaurier“ geschrieben und erklärt, was Dinosaurier sind, wann sie lebten und wie sie aufgebaut waren.
-Ich habe das Kapitel „Die Zeit der Dinosaurier“ erstellt und die Erdzeitalter Trias, Jura und Kreidezeit mit den entsprechenden Zeiträumen beschrieben.
-Ich habe das Kapitel „Nahrung der Dinosaurier“ verfasst und die verschiedenen Ernährungsweisen (Pflanzenfresser, Fleischfresser, Allesfresser) erklärt.
-Ich habe das Kapitel „Fossilien und Entdeckungen“ geschrieben, erklärt, wie Fossilien entstehen, was Paläontologen machen und eine wichtige Entdeckung (Ichthyosaurus-Fund) beschrieben.
-Ich habe das Kapitel „Das Aussterben der Dinosaurier“ erstellt, den Meteoriten-Einschlag beim Chicxulub-Kraters und mögliche vulkanische Ursachen beschrieben.
-Ich habe das Kapitel „Spannende Fakten über Dinosaurier“ geschrieben, inklusive Informationen über Vögel als Nachfahren, Federn, Größenunterschiede, Eier/Nester und Farben.
-Ich habe noch einen Abschnitt Namens "Zusammenfassung" in mein Inhaltsverzeichnis eingefügt.
-Ich habe verschiedene Überschriften verwendet: <h1>, <h2>, <h3> und <h4>.
• <h1> → Hauptüberschrift (Titel der Website)
• <h2> → Unterüberschrift (z.B. Inhaltsverzeichnis)
• <h3> → Kapitelüberschriften
• <h4> → Unterpunkte (z.B. einzelne Dinosaurier)
-Ich habe <p> verwendet, um Textabschnitte zu erstellen.
• <p> steht für "paragraph" (Absatz)
• Es wird genutzt, um längere Texte strukturiert darzustellen

Quelle:
https://developer.mozilla.org/de/docs/Web/HTML/Element/p
Quelle:
https://developer.mozilla.org/de/docs/Web/HTML/Element/Heading_Elements

Quelle: Ich habe für die Infos KI gebraucht, da mir das am einfachsten fiel. --> Ich habe Chat GPT und Google KI genutzt.


13.03.2026 – Tabellen (Dinosaurier Steckbriefe)
-Zusammenfassung geschrieben
-Arten von Dinosaurier: Steckbriefe erstellt von den typischen Dinosauriern. 
--> Bei diesem Abschnitt habe ich weiter an der Kategorie „Arten von Dinosauriern“ gearbeitet
Meine Idee war, für jeden Dinosaurier einen Steckbrief in Hochformat zu erstellen, damit die wichtigsten Informationen vo den wichtigsten Dinosauriern übersichtlich dargestellt werden.
Dazu gehören Themen wie Ernährung, Gewicht, Länge, Zeit, Lebensraum, Art, Besonderheiten und spannende Fakten, für die ich rechechieren musste.
Für die Gestaltung der Tabellen habe ich CSS verwendet, --> Dafür habe ich Quellen gebraucht um zu verstehen wie ich diese Tabellen gestalten möchte
-Ich habe den Text bei "Einführung von Dinosauriern" verbessert, da er einwenig komisch geschrieben war und ich es ausführlicher schreiben wollte.
-Ich habe bei „Arten von Dinosauriern“ die einzelnen Dinosaurier als Unterpunkte hinzugefügt. So sieht das Inhaltsverzeichnis übersichtlicher aus und die Untergruppen sind klar erkennbar.
-„Ich habe ein CSS-Grundgerüst erstellt, in dem ich alle Tabellenstile und andere Gestaltungselemente eintragen kann. Zusätzlich habe ich scroll-behavior: smooth; eingefügt, damit das Scrollen zu den Abschnitten flüssig erfolgt."

DIE TABELLEN: Ich habe Tabellen erstellt mit <table>, <tr> (Zeile), <td> (Zelle) und <th> (Überschrift).

border in CSS erstellt Rahmen.
padding erstellt Abstand in der Zelle.
border-collapse verbindet Tabellenlinien.

Problem: Die Tabelle war zuerst unlesbar und ohne Struktur.

Lösung: Ich habe CSS hinzugefügt, um die Tabelle optisch zu strukturieren.

Quelle:
MDN Web Docs – Tabellen
https://developer.mozilla.org/de/docs/Web/HTML/Element/table

MDN Web Docs – CSS Padding
https://developer.mozilla.org/de/docs/Web/CSS/padding

MDN Web Docs – Border
https://developer.mozilla.org/de/docs/Web/CSS/border
Anpassung: Ich habe eigene Kategorien für Dinosaurier erstellt.

Änderung der Untertitel „Arten von Dinosaurier“:
-Die Untertitel wurden von <h3> zu <h4> geändert.
In der CSS-Datei für h4 Folgendes hinzugefügt:
	•	font-family --> Schriftart der Untertitel geändert (z. B. „Fredoka One“).
	•	font-size --> Schriftgrössr angepasst.
	•	margin-bottom --> Abstand gemacht, damit die Tabelle oder der Text nicht zu nah am Titel steht.
Zweck:
	•	Schriftart der Untertitel individuell gestaltet.
	•	Ich habe den Abstand zwischen Titel und Tabelle angepasst.

IDs für Dinosaurier-Unterpunkte
	•	Beispiel: <h4 id="tyrannosaurus">Tyrannosaurus Rex</h4>
	•Funktionsweise: <a> ist ein Hyperlink (Anchor-Tag). href definiert das Ziel des Links. #tyrannosaurus verweist auf die passende id im Dokument und springt direkt zu diesem Abschnitt.
Quellen:
MDN Web Docs – id
https://developer.mozilla.org/de/docs/Web/HTML/Global_attributes/id
MDN Web Docs – a
https://developer.mozilla.org/de/docs/Web/HTML/Element/a

Bilder für Steckbriefe
	•	Beispiel:
<img src="https://image.geo.de/35946962/t/gm/v4/w1440/r1.7778/-/trex-g-99311107.jpg" alt="Tyrannosaurus Rex">
• <img> → HTML-Element zum Einfügen von Bildern
• src → gibt die Bildquelle (URL) an
• alt → alternativer Text für das Bild



16.03.2026: 
Heute habe ich an der Zeit der Dinosaurier gearbeitet und zu den drei Erdzeitaltern Trias, Jura und Kreidezeit passende Videos auf meiner Website eingebunden.

Schritt 1: Videos recherchieren
	•	Ich habe auf YouTube nach Videos gesucht, die die Erdzeitalter erklären.
	•	Dabei gab es Probleme:
	•	Viele Videos waren zu lang.
	•	Einige Videos waren nicht genau genug erklärt.
	•	Quellen (YouTube):
	•	Trias: https://www.youtube.com/watch?v=wJz2upbA3QA
	•	Jura: https://www.youtube.com/watch?v=d4Z-glC0vXg
	•	Kreidezeit: https://www.youtube.com/watch?v=zyd6mgLK6Q0

Schritt 2: Videos auf der Website einbauen
	•	Zuerst wollte ich die Videos mit <iframe> einbinden.
	•	<iframe> ist ein HTML-Element, mit dem man externe Inhalte (z. B. YouTube Videos) direkt in eine Website einbetten kann.
	•	Problem: Einige YouTube Videos erlauben kein Einbetten.
	•	Lösung: Ich habe Bilder (Thumbnails) verwendet und sie mit Links versehen.
	•	Beispiel:<a href="https://www.youtube.com/watch?v=wJz2upbA3QA" target="_blank">
  <img src="https://biermann-medizin.de/content/uploads/2025/03/newsimage404428-scaled.jpg" alt="Trias Video">
</a>
	•	Erklärung:
	•	<a> = Anchor-Tag, erstellt einen klickbaren Link (Hyperlink)
	•	href = Zieladresse des Links (URL)
	•	target="_blank" = öffnet den Link in einem neuen Tab
	•	<img> = zeigt ein Bild an (Thumbnail)
	•	alt = Alternativtext, falls Bild nicht geladen wird
	•	Quelle:
https://developer.mozilla.org/de/docs/Web/HTML/Element/a

Schritt 3: Boxen mit CSS gestalten
Ich habe für jede Zeitperiode eine Box erstellt (.periode-box).
Diese Boxen habe ich mit CSS gestaltet.

Verwendete CSS Eigenschaften:
• display: flex → ordnet Elemente nebeneinander an (Flexbox Layout)
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/display

• margin → Abstand ausserhalb eines Elements (Aussenabstand)
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/margin

• padding → Abstand innerhalb eines Elements (Innenabstand)
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/padding

• width → bestimmt die Breite eines Elements
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/width

• height → bestimmt die Höhe eines Elements
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/height

Schritt 4: IDs für Abschnitte
	•	Jede Zeitperiode hat eine eigene ID bekommen:
	•	id="trias"
	•	id="jura"
	•	id="kreidezeit"
	•	Eine ID ist ein eindeutiger Name für ein HTML-Element.
	•	Sie wird benutzt, damit man einen bestimmten Abschnitt direkt ansteuern kann.
	•	Beispiel: <a href="#jura">Jura</a>
•	Erklärung:
	•	<a> erstellt einen Link (Hyperlink)
	•	href="#jura" bedeutet: springe zu dem Element mit der ID „jura“
	•	So kann man im Inhaltsverzeichnis direkt zu einem bestimmten Abschnitt auf der Seite springen.
	•	Quelle:
https://developer.mozilla.org/de/docs/Web/HTML/Global_attributes/id


26.03.2026 – Layout Problem (Dino Boxen)

Heute habe ich für jeden Dinosaurier eine eigene Box erstellt.
	•	Ich habe <div> verwendet.
<div> ist ein Container-Element in HTML, das Inhalte gruppiert.
Quelle: https://developer.mozilla.org/de/docs/Web/HTML/Element/div
	•	Beispiel: <div class="dino-box">

	•	class gibt einem Element einen Namen, damit man es mit CSS gestalten kann.
Quelle: https://developer.mozilla.org/de/docs/Web/HTML/Global_attributes/class
	•	Innerhalb habe ich eine zweite Box erstellt: <div class="dino-content"> 

Layout mit Flexbox
	•	Ich habe CSS Flexbox verwendet:

• display: flex → ordnet Elemente nebeneinander an
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/display

• flex → steuert, wie Elemente wachsen und sich anpassen
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/flex
	•	Ich habe verwendet: flex: 1 1 48%; 
	•	Erklärung von flex:
	•	erstes 1 → Element darf wachsen
	•	zweites 1 → Element darf schrumpfen
	•	48% → Basisbreite des Elements
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/flex

• flex-wrap → bestimmt, ob Elemente umbrechen dürfen
Ich habe flex-wrap: wrap verwendet, damit Elemente auf kleineren Bildschirmen untereinander angezeigt werden.
Quelle:
https://developer.mozilla.org/de/docs/Web/CSS/flex-wrap

• gap → bestimmt den Abstand zwischen Elementen in einem Flexbox-Layout
Quelle:
https://developer.mozilla.org/de/docs/Web/CSS/gap

Tabellen & Bilder anpassen
	•	table-layout: fixed → sorgt dafür, dass Spalten gleichmässig verteilt werden
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/table-layout
	•	max-width → begrenzt die maximale Breite eines Elements
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/max-width
• object-fit → bestimmt, wie ein Bild in seinen Container passt
Ich habe object-fit: contain verwendet, damit das ganze Bild sichtbar ist und nicht abgeschnitten wird.
Quelle:
https://developer.mozilla.org/de/docs/Web/CSS/object-fit

Problem & Lösung
	•	Problem:
Die Tabelle war zu schmal und das Bild zu gross (besonders beim Brachiosaurus).
	•	Ursache:
max-width: 800px hat verhindert, dass die Tabelle die volle Breite nutzt.
	•	Lösung:
Ich habe max-width entfernt und stattdessen flex: 1 1 48% verwendet.
	•	Ergebnis:
Tabelle und Bild sind jetzt gleichmässig nebeneinander und passen sich der Box an.

Anpassung:
Ich habe so ein einheitliches Layout für alle Dinosaurier erstellt, damit jede Box gleich aussieht und übersichtlich ist.



27.03.2026 - Allgemeiner Design meiner Website
Ich habe das Design meiner Website verbessert, damit sie nicht mehr wie ein Word-Dokument aussieht, sondern wie eine richtige Website.
	•	Ich habe Farben, Abstände und Layout mit CSS angepasst.


Verwendete CSS Begriffe:

• background → legt die Hintergrundfarbe eines Elements fest (z. B. grünlicher Hintergrund der Seite)
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/background

• color → bestimmt die Textfarbe
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/color

• font-family → legt die Schriftart fest (z. B. Arial oder spezielle Fonts)
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/font-family

• font-size → bestimmt die Schriftgrösse
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/font-size

• margin → Abstand ausserhalb eines Elements (z. B. Abstand zwischen Abschnitten)
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/margin

• padding → Abstand innerhalb eines Elements (z. B. Abstand zwischen Text und Rand)
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/padding

• border → erstellt einen Rahmen um ein Element
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/border

• border-radius → macht Ecken rund
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/border-radius

• box-shadow → fügt Schatten hinzu (macht Boxen moderner)
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/box-shadow

• :hover → wird aktiviert, wenn man mit der Maus über ein Element fährt
Ich habe :hover verwendet, um visuelle Effekte zu erzeugen, z. B. bei Bildern oder Links.
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/:hover

• transition → sorgt für weiche Übergänge bei Veränderungen (z. B. beim Hover-Effekt)
Ich habe transition verwendet, damit sich Elemente beim Hover nicht abrupt verändern, sondern sanft animiert werden (z. B. Vergrösserung von Bildern).
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/transition

• position: fixed → Element bleibt beim Scrollen an einer festen Stelle (z. B. Seitenleiste)
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/position

• position: absolute → positioniert ein Element relativ zum nächsten übergeordneten Element
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/position

• left, top → bestimmen die genaue Position eines Elements
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/left
https://developer.mozilla.org/de/docs/Web/CSS/top

• width → Breite eines Elements
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/width

• height → Höhe eines Elements
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/height

• max-width → maximale Breite eines Elements
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/max-width

• text-align → richtet Text aus (z. B. links oder zentriert)
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/text-align

• text-decoration → verändert Text (z. B. entfernt Unterstreichung bei Links)
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/text-decoration

• ::before → erstellt ein Pseudo-Element vor einem Element (Balken) (z. B. für die linke grüne Leiste)
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/::before

• scroll-behavior: smooth → sorgt für smoothes Scrollen
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/scroll-behavior

Problem:
Die Website sah am Anfang aus wie ein Word-Dokument (kein klares Design, alles untereinander, keine Struktur).

Lösung:
Ich habe CSS verwendet, um:
	•	Farben festzulegen (grünes Design)
	•	Abstände zu verbessern (margin, padding)
	•	Boxen zu gestalten (border, shadow, radius)
	•	Layout zu strukturieren (Flexbox, Positionierung)


Anpassung:
Ich habe ein grünes Farbschema gewählt, damit die Website zum Thema Natur/Dinosaurier passt und insgesamt moderner wirkt.


15.04.2026 – JavaScript Scroll Button, einpaar Bilder eingefügt und <strong> eingefügt.

Bilder eingefügt (Zeit der Dinosaurier & Aussterben)

Ich habe zwei neue Bilder in meine Website eingefügt:
	•	bei „Zeit der Dinosaurier“
	•	bei „Aussterben der Dinosaurier“
	•	Dafür habe ich <img> verwendet.
<img> zeigt ein Bild auf der Website an.
Quelle: https://developer.mozilla.org/de/docs/Web/HTML/Element/img
	•	src → gibt die Bildquelle (URL) an
Quelle: https://developer.mozilla.org/de/docs/Web/HTML/Element/img#attr-src
	•	alt → beschreibt das Bild (wichtig für Barrierefreiheit)
Quelle: https://developer.mozilla.org/de/docs/Web/HTML/Element/img#attr-alt
	•	Beispiel: <img src="BILD-LINK" alt="Dinosaurier Zeit">

JavaScript Scroll Button
Ich habe einen Button erstellt, der nach oben scrollt.
const topBtn = document.getElementById("topBtn"); 
	•	document → steht für das gesamte HTML-Dokument
Quelle: https://developer.mozilla.org/de/docs/Web/API/Document
	•	getElementById() → wählt ein Element anhand seiner ID aus
Quelle: https://developer.mozilla.org/de/docs/Web/API/Document/getElementById

window.addEventListener("scroll", () => {
	•	window → das Browserfenster
Quelle: https://developer.mozilla.org/de/docs/Web/API/Window
	•	addEventListener() → wartet auf ein Ereignis (Event)
Quelle: https://developer.mozilla.org/de/docs/Web/API/EventTarget/addEventListener
	•	"scroll" → Event, das ausgelöst wird, wenn man scrollt
Quelle: https://developer.mozilla.org/de/docs/Web/API/Document/scroll_event

if (window.scrollY > 300)
	•	scrollY → gibt an, wie weit nach unten gescrollt wurde
Quelle: https://developer.mozilla.org/de/docs/Web/API/Window/scrollY

topBtn.style.display = "block";
topBtn.style.display = "none";
	•	style → greift auf CSS eines Elements zu
Quelle: https://developer.mozilla.org/de/docs/Web/API/HTMLElement/style
	•	display → bestimmt, ob ein Element sichtbar ist
Quelle: https://developer.mozilla.org/de/docs/Web/CSS/display
	•	"none" → Element wird versteckt
	•	"block" → Element wird angezeigt

	topBtn.addEventListener("click", () => {
	•	"click" → Event, wenn man klickt
Quelle: https://developer.mozilla.org/de/docs/Web/API/Element/click_event

window.scrollTo({
  top: 0,
  behavior: "smooth"
}); 
	•	scrollTo() → bewegt die Seite an eine bestimmte Position
Quelle: https://developer.mozilla.org/de/docs/Web/API/Window/scrollTo
	•	top: 0 → scrollt ganz nach oben
	•	behavior: "smooth" → weiches Scrollen
Quelle: https://developer.mozilla.org/de/docs/Web/API/ScrollToOptions
• z-index → bestimmt, welches Element im Vordergrund ist
Ich habe z-index verwendet, damit der Button immer über anderen Elementen angezeigt wird.

Quelle:
https://developer.mozilla.org/de/docs/Web/CSS/z-index
Problem & Lösung
	•	Problem:
Der Button war immer sichtbar.
	•	Lösung:
Ich habe ihn mit display: none versteckt und nur angezeigt, wenn scrollY > 300 ist.

Ich habe noch 2 Bilder in meine Website eingefügt:
• Bild bei „Zeit der Dinosaurier“: https://tubestatic.orf.at/static/images/site/tube/20180416/dino-aufstieg_big_n.5739022.jpg
• Bild bei „Aussterben der Dinosaurier“ QUELLE: https://static01.nyt.com/images/2016/11/18/science/18TB-CRATER-1479408746987xx 18TB-CRATER-1479408746987-superJumbo.jpg


KI Nutzung (wichtig für Auftrag)

Ich habe ChatGPT als Lernhilfe verwendet.

Ich habe ChatGPT genutzt um:
	•	Inhalte über Dinosaurier besser zu verstehen
	•	CSS und JavaScript besser zu erklären
	•	Probleme im Code zu analysieren
	•	Formulierungen für Texte zu verbessern

Fazit
Ich habe gelernt, wie man eine komplette Website mit HTML, CSS und JavaScript erstellt. Ich verstehe jetzt die Struktur, das Design und die Interaktivität sehr viel besser.