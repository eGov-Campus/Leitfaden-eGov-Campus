#Textabschnitte

##1. Neues Item erstellen

Zu Beginn müssen Sie zur Kursübersicht navigieren, um ein neues Quiz einer Sektion (hier später Link einfügen für Sektion erstellen) hinzuzufügen. Klicken Sie bei der passenden Sektion auf "Neues Item".

![Navigation Kursübersicht](/images/items/Navigation_zur_Kursstruktur.png)
		


##2. Einstellungen

Auf der nächsten Seite haben Sie nun die folgenden Optionen:


**Titel:** 


**Erweiterte Einstellungen:** 

Unter den erweiterten Einstellungen können Sie nun noch ein Start- und/oder ein Enddatum angeben. Wenn Sie das Quiz erst ab einem bestimmten Zeitpunkt freischalten möchten, können Sie ein Startdatum angeben. Soll das Quiz nur bis zu einem bestimmten Zeitpunkt verfügbar sein, können Sie ein Enddatum angeben. Diese Einstellungen ist optional. 


**Veröffentlicht:** 

Hier entscheiden Sie, ob das Quiz veröffentlicht werden soll. In diesem Kontext bedeutet das, dass das Quiz direkt, nachdem Sie es angelegt haben, für die Kursteilnehmer sichtbar gemacht wird. Sollten Sie den Schalter auf "aus" stellen, können Sie zu einem späteren Zeitpunkt das Quiz für die Kursteilnehmer sichtbar machen. 


**In der Kursnavigation zeigen:** 

Dieser Button funktioniert nur, wenn das Quiz auch veröffentlicht wurde. Dadurch wird eingestellt, dass das Quiz auch an dem vorgesehenen Punkt sichtbar ist. Diese Einstellung zu **aktivieren** wird **empfohlen**. Andernfalls ist das Quiz nur über einen direkten Link abrufbar.

**Optional:** 

Damit markieren Sie, dass das Bearbeiten des Quiz nur optional ist. Dies zu aktivieren, eignet sich unter anderem, wenn man Hintergrundwissen vermitteln  oder einen tieferen Einblick in ein Thema geben möchte, das nicht notwendig für den Abschluss des Kurses ist. 


## 3. Text-Item erstellen

Um ein Text-Item zu erstellen, wählen Sie bitte als Item "Text" aus. Den Icon-Typ lassen Sie bitte unberührt. 

In das Textfeld können Sie nun Texte schreiben und einfügen. Allerdings können Sie den Text auch so anpassen, dass Sie mit einfachen Befehlen den Text formatieren (Überschriften, fettgedrukt, kursiv etc.) aber auch Tabellen und Bilder einfügen. In diese Textbefehle, genannt Markdown, möchten wir Ihnen nachfolgend einen Einblick geben. 

Auch HTML-Code wird in den Textfeldern unterstützt und darf gerne verwendet werden.

Sie werden bei weiteren Möglichkeiten sonst auch mit der Suchmaschine Ihrer Wahl fündig.

## 4. Markdown Guide <-- Text ist doppelt

Mit dieser Anleitung möchten wir Ihnen eine kurze Einführung für die Nutzung von Markdown geben, um Schrift in dem Kurs passend zu formatieren. Dafür werden wir eine Übersicht der Befehle/Schreibweisen anzeigen und diese mit einem Kommentar weiter erläutern. 

**Was ist Markdown?**

Markdown ist prinzipiell eine Schreibweise, um Text zu formatieren. Diese wird dann später für die Website passend kombiniert. 

## 4.1 Überschriften

---

<h1>Überschrift1  <code># H1</code></h1>

<h2>Überschrift2 <code>## H2</code></h2>

<h3>Überschrift3 <code>### H3</code></h3>

<h4>Überschrift4 <code>#### H4</code></h4>

<h5>Überschrift5 <code>##### H5</code></h5>

<h6>Überschrift6 <code>###### H6</code></h6>


## 4.2 Absatz- und Zeilenumbrüche

- Ein Absatz entsteht durch **2** Zeilenumbrüche
- Einen Zeilenumbruch kann man erzwingen, wenn man 2 Leerzeichen vor dem Zeilenende einfügt und danach einmal ENTER drückt.

## 4.3 Horizontale Linien


Eine Linie kann über drei aufeinander folgende Bindestriche erzeugt werden, also <code>---</code> :

---


## 4.4 Listen

Für Listen gibt es zwei verschiedene Möglichkeiten: Ungeordnete Listen (Stichpunkte) und geordnete Listen (nummeriert)

### 4.4.1 Stichpunkte / ungeordnete Liste

Eine ungeordnete Liste - also Stichpunkte - schreibt man mit einem Bindestrich, Leerzeichen und dann dem Text:

<code>- Dies ist ein Stichpunkt</code>

Das sieht dann so aus:

- Dies ist ein Stichpunkt


Stichpunkte kann man auch einrücken. Dazu müssen Sie ein Tabulator-Taste vorher nutzen, damit die Einrückung erkannt wird.

**Beispiel:**

<code>- Stichpunkt</code>

&nbsp;&nbsp;&nbsp;<code>- Eingerückter Stichpunkt</code>

<code>- Wieder ein normaler Stichpunkt</code>

---

Das sieht dann so aus:

- Stichpunkt
	- Eingerückter Stichpunkt
- Wieder ein normaler Stichpunkt


### 4.4.2 Nummerierte Liste / geordnete Liste

<ol>
<li>Ich </li>
<li>bin<br>
a. eine<br>
b. geordnete </li>
<li>Liste </li>
</ol>

<p><code>1. Ich</code> (Leerzeichen + 1.)<br>
<code>2. bin</code> (Leerzeichen + 2.)<br>
&nbsp;&nbsp;&nbsp;<code>a. eine</code>  (Für untergeordnete Ebenen zusätzliche Leerzeichen)<br>
&nbsp;&nbsp;&nbsp;<code>b. geordnete</code>  (einfügen)<br>
<code>3. Liste</code> (bzw. wieder wegnehmen) </p>

Gerade verschachtelte Listen können etwas tricky sein. Im Zweifel muss man etwas mit den Leerzeichen experimentieren. Es empfiehlt sich auch vor der Liste einen Absatz einzufügen.

## 4.5 Links

Links werden am einfachsten mit dem **Link Tool** in der Tool-Leiste eingefügt. Klicken Sie dafür auf das Linksymbol und geben Sie nach dem angezeigten Schema die Adresse und die Bezeichnung an.
Sie können aber auch das, was Ihnen ausgegeben wird, selbst nach dem folgenden Schema einfügen:

<p><code> [Anzeigename](Link) </code></p>

Beispiel:
<p><code> Hier finden Sie die [eGov Campus Homepage](https://egov-campus.org/) </code></p>

Das wird dann wie folgt angezeigt:

Hier finden Sie die [eGov Campus Homepage](https://egov-campus.org/).



## 4.6 Bilder

Bilder werden mit der Drop-Area rechts zunächst hochgeladen und stehen dann in der aktuellen Textseite über den Bild-einfügen-Button zur Verfügung. Hochgeladene Bilder werden erst dann gespeichert wenn das Bild tatsächlich in den Text eingebunden wurde. Nicht verwendete Bilder werden wieder vom Server gelöscht.

Um das Bild dann an der passenden Stelle einzufügen, klicken Sie bitte auf das Bild-Symbol in der Tool-Leiste. 

Es wird dann wie folgt dargestellt:

<code>![enter image description here][1]</code>

Hier werden Sie mit einer Zahl anstatt eines Links angezeigt. Der Anzeigetext (wenn man mit der Maus auf dem Bild ist) sollte dann in die ersten Klammern eingefügt werden.

Alternativ können Sie auch Bilder einfügen, indem Sie die **Grafikadresse** eines Bildes einfügen, dass bereits auf einer anderen Homepage besteht. 

Das funktioniert dann ähnlich wie zuvor gezeigt. Bitte beachten Sie, dass hier nun aber "()"-Klammern verwendet werden:

<p><code> ![Weiterbildung Symbolbild](https://egov-campus.org/sites/default/files/kic_front/category_header/junger_mann_an_laptop.jpg)</code></p>


Darstellung:

![Weiterbildung Symbolbild](https://egov-campus.org/sites/default/files/kic_front/category_header/junger_mann_an_laptop.jpg)

## 4.7 Downloads

Andere Dateiformate die zum Download bereitgestellt werden sollen, werden sehr ähnlich wie die Bilder eingebunden (das "!" fehlt im Gegensatz zu Bildern).

Um das Downloads dann an der passenden Stelle einzufügen, klicken Sie bitte auf das Bild-Symbol in der Tool-Leiste. 

Es wird dann wie folgt dargestellt:

<code>[enter file description here][1]</code>

Hier werden Sie mit einer Zahl anstatt eines Links angezeigt. Der Anzeigetext (also der blau dargestellte Text) sollte dann in die ersten Klammern eingefügt werden.

Alternativ können Sie auch Downloads einfügen, indem Sie die **Adresse** einer Datei einfügen, dass bereits auf einer anderen Homepage besteht. 

<p><code> [Beispiel Download](/images/items/Test.pdf)</code></p>

Darstellung: [Beispiel Download](/images/items/Test.pdf)



## 4.8 Tabellen

Tabellen werden etwas komplizierter dargestellt. 

Vor der eigentlichen Erklärung möchte ich auf das Online-Tool [Tableconvert.com](https://tableconvert.com/) hinweisen. Hier können Sie die automatisch generieren lassen, was für viele etwas einfacher ist. Nachfolgend finden Sie die Code-Erklärung.

### 4.8.1 Online Tool nutzen
Besuchen Sie bitte die Website [Tableconvert.com](https://tableconvert.com/)

1. Stellen Sie bitte erst die Größe der Tabelle ein
2. Tragen Sie dann die Inhalte ein. Die erste Zeile wird automatisch als Überschriftenzeile eingestellt. Alternativ können Sie auch CSV-Dateien (Exel: Speichern unter -> als CSV) hochladen.
3. IN den Feld unten wird Ihnen die Tabelle im Markdown-Format angezeigt. 
4. Kopieren Sie den Text in die Zwischenablage und fügen Sie diesen in das Textfeld der eGov-Campus-Seite.

![Beispiel Table Editor](/images/items/table_editor2.png)


### 4.8.2 Mit Markdown-Code erstellen


Die Markdown-Tabellen werden zeilenweise aufgeschrieben, also zum Beispiel 
<code>|Tag|Monat|Jahr|</code>. 

Danach müssen Sie die erste Zeile noch als Überschrit kennzeichnen, indem Sie darunter Linien einfügen: <code>|-----|-------|------|</code>. Danach tragen Sie die Zeilen entsprechend wie wie erste Zeile unereinander ein, zum Beispiel: 
<code>| 04  | 05    | 2000 |</code>

In Gänze können Sie das auf dem oben gezeigten Screenshot sehen. 

Ansicht für die Nutzer:

| Tag | Monat | Jahr |
|-----|-------|------|
| 04  | 05    | 2000 |
| 05  | 11    | 2000 |



Hinweis: Der Strich wird über die Tastenkombination  <code>[AltGr]</code> + <code>[< > |]</code> (neben der <code>[SHIFT]</code>-Taste) erzeugt. 