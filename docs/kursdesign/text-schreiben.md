#Textabschnitte

##1. Neues Item erstellen

Zu Beginn müssen Sie zur Kursübersicht navigieren, um ein neues Quiz einer Sektion (hier später Link einfügen für Sektion erstellen) hinzuzufügen. Klicken Sie bei der passenden Sektion auf "Neues Item".

![Navigation Kursübersicht](/images/items/Navigation_zur_Kursstruktur.png)
		


##2. Einstellungen

Auf der nächsten Seite haben Sie nun die folgenden Optionen:


**Titel:** 

Am Anfang müssen Sie einen Titel für das Item - in diesem Fall Ihr Quiz - angeben. 


**Erweiterte Einstellungen:** 

Unter den erweiterten Einstellungen können Sie nun noch ein Start- und/oder ein Enddatum angeben. Wenn Sie das Quiz erst ab einem bestimmten Zeitpunkt freischalten möchten, können Sie ein Startdatum angeben. Soll das Quiz nur bis zu einem bestimmten Zeitpunkt verfügbar sein, können Sie ein Enddatum angeben. Diese Einstellungen ist optional. 


**Veröffentlicht:** 

Hier entscheiden Sie, ob das Quiz veröffentlicht werden soll. In diesem Kontext bedeutet das, dass das Quiz direkt, nachdem Sie es angelegt haben, für die Kursteilnehmer sichtbar gemacht wird. Sollten Sie den Schalter auf "aus" stellen, können Sie zu einem späteren Zeitpunkt das Quiz für die Kursteilnehmer sichtbar machen. 


**In der Kursnavigation zeigen:** 

Dieser Button funktioniert nur, wenn das Quiz auch veröffentlicht wurde. Dadurch wird eingestellt, dass das Quiz auch an dem vorgesehenen Punkt sichtbar ist. Diese Einstellung zu **aktivieren** wird **empfohlen**. Andernfalls ist das Quiz nur über einen direkten Link abrufbar.

**Optional:** 

Damit markieren Sie, dass das Bearbeiten des Quiz nur optional ist. Dies zu aktivieren, eignet sich unter anderem, wenn man Hintergrundwissen vermitteln  oder einen tieferen Einblick in ein Thema geben möchte, das nicht notwendig für den Abschluss des Kurses ist. 


##3. Text-Item erstellen

Um ein Text-Item zu erstellen, wählen Sie bitte als Item "Text" aus. Den Subtyp lassen Sie bitte unberührt. 

In das Textfeld können Sie nun Texte schreiben und einfügen. Allerdings können Sie den Text auch so anpassen, dass Sie mit einfachen Befehlen den Text formatieren (Überschriften, fettgedrukt, kursiv etc.) aber auch Tabellen und Bilder einfügen. In diese Textbefehle, genannt Markdown, möchten wir Ihnen nachfolgend einen Einblick geben. 

Auch HTML-Code wird in den Textfeldern unterstützt und darf gerne verwendet werden.

Sie werden bei weiteren Möglichkeiten sonst auch mit der Suchmaschine Ihrer Wahl fündig.

##4.1 Markdown Guide <-- Text ist doppelt

Mit dieser Anleitung möchten wir Ihnen eine kurze Einführung für die Nutzung von Markdown geben, um Schrift in dem Kurs passend zu formatieren. Dafür werden wir eine Übersicht der Befehle/Schreibweisen anzeigen und diese mit einem Kommentar weiter erläutern. 

###4.2 Was ist Markdown?

Markdown ist prinzipiell eine Schreibweise, um Text zu formatieren. Diese wird dann später für die Website passend kombiniert. 

##Überschriften

<h1>Überschrift1  <code># H1</code></h1>

<h2>Überschrift2 <code>## H2</code></h2>

<h3>Überschrift3 <code>### H3</code></h3>

<h4>Überschrift4 <code>#### H4</code></h4>

<h5>Überschrift5 <code>##### H5</code></h5>

<h6>Überschrift6 <code>###### H6</code></h6>



##Absatz- und Zeilenumbrüche

<code></code>

- Ein Absatz entsteht durch **2** Zeilenumbrüche
- Einen Zeilenumbruch kann man erzwingen, wenn man 2 Leerzeichen vor dem Zeilenende einfügt und danach einmal ENTER drückt.

##Horizontale Linien

<hr>

Eine Linie kann über drei aufeinander folgende Bindestriche erzeugt werden, also <code>---</code> :
---


##Listen

Für Listen gibt es zwei verschiedene Möglichkeiten: Ungeordnete Listen (Stichpunkte) und geordnete Listen (nummeriert)

###Stichpunkte / ungeordnete Liste

Eine ungeordnete Liste - also Stichpunkte - schreibt man mit einem Bindestrich, Leerzeichen und dann dem Text: <code>- Dies ist ein Stichpunkt</code>

Das sieht dann so aus:
- Dies ist ein Stichpunkt


Stichpunkte kann man auch einrücken. Dazu müssen Sie ein Tabulator-Taste vorher nutzen, damit die Einrückung erkannt wird.

Beispiel:

<code>- Stichpunkt</code>

&nbsp;&nbsp;&nbsp;<code>- Eingerückter Stichpunkt</code>

<code>- Wieder ein normaler Stichpunkt</code>

- Stichpunkt
	- Eingerückter Stichpunkt
- Wieder ein normaler Stichpunkt


<ul>
<li>Ich </li>
<li>bin 

<ul>
<li>eine </li>
<li>ungeordnete</li>
</ul></li>
<li>Liste </li>
</ul>

<p><code>- Ich</code> (Leerzeichen + Bindestrich)<br>
<code>- bin</code> (Leerzeichen + Bindestrich)<br>
&nbsp;&nbsp;&nbsp;<code>- eine</code>  (Für Hierarchieebenen zusätzliche Leerzeichen)<br>
&nbsp;&nbsp;&nbsp;<code>- ungeordnete</code>(einfügen)<br>
<code>- Liste</code> (bzw. wieder wegnehmen) </p>

<ol>
<li>Ich </li>
<li>bin<br>
a. eine<br>
b. geordnete </li>
<li>Liste </li>
</ol>

<p><code>1. Ich</code> (Leerzeichen + 1.)<br>
<code>2. bin</code> (Leerzeichen + 2.)<br>
&nbsp;&nbsp;&nbsp;<code>a. eine</code>  (Für Hierarchieebenen zusätzliche Leerzeichen)<br>
&nbsp;&nbsp;&nbsp;<code>b. geordnete</code>(einfügen)<br>
<code>3. Liste</code> (bzw. wieder wegnehmen) </p>

<p>Gerade verschachtelte Listen können etwas tricky sein. Im Zweifel muss man etwas mit den Leerzeichen experimentieren. Es empfiehlt sich auch vor der Liste einen Absatz einzufügen. </p>

<h2>Links</h2>

<p>Links werden am besten mittels des Link Tools in der Tool-Leiste eingefügt. Komplette URLs werden in der Regel zwar auch automatisch in Links konvertiert, verhalten sich aber nicht immer identisch zu explizit angelegten Links.</p>

<p>Hier ist das <a target="_blank" rel="noopener" href="https://mooc.house/go/link?url=https%3A%2F%2Fwww.google.de%2Fmaps%2Fplace%2FHasso%2BPlattner%2BInstitute%2F%4052.3939998%2C13.1311717%2C17z%2Fdata%3D%213m1%214b1%214m5%213m4%211s0x47a85f365d286349%3A0x1da4e14975e45e72%218m2%213d52.3939965%214d13.1333657&checksum=aad0f93&tracking_type=rich_text_item_link&tracking_id=39c63dff-abf9-4157-81f3-0b7b50fa8856&tracking_course_id=bbd72c9c-e830-4029-8459-21913f553ab4">HPI</a>.</p>

<p>Explizit angelegte Links bestehen aus zwei Komponenten:  </p>

<ol>
<li><p>Der Aufruf des Links im Text<br>
[HPI][1]</p></li>
<li><p>Die Definition des Links am Ende des Texts (für den Nutzer nicht sichtbar)<br>
[1]: <a href="https://www.google.de/maps/place/Hasso+Plattner+Institute/@52.3939998,13.1311717,17z/data=!3m1!4b1!4m5!3m4!1s0x47a85f365d286349:0x1da4e14975e45e72!8m2!3d52.3939965!4d13.1333657">https://www.google.de/maps/place/Hasso+Plattner+Institute/@52.3939998,13.1311717,17z/data=!3m1!4b1!4m5!3m4!1s0x47a85f365d286349:0x1da4e14975e45e72!8m2!3d52.3939965!4d13.1333657</a></p></li>
</ol>

<h2>Bilder</h2>

<p>Bilder werden mittels der Drop-Area rechts zunächst hochgeladen und stehen dann im Kontext der aktuellen Textseite über den &quot;Bild einfügen&quot; Button zur Verfügung. hochgeladene Bilder werden erst dann persistiert wenn das Bild tatsächlich in den Text eingebunden wurde. Nicht verwendete Bilder werden früher oder später wieder vom Server gelöscht.</p>

<p>Bilder werden mittels des Image-Selectors in der Tool-Leiste der Text-Area eingebunden.</p>

<p>Das eingefügte Bild wird im Text folgendermaßen dargestellt:<br>
![enter image description here][1]</p>

<p>Hier muss der Text in den vorderen eckigen Klammern:<br>
&quot;enter image description here&quot;<br>
durch einen dem Bild entsprechenden Alt-Text getauscht werden.<br>
![Plastikschaf auf Rasenmähroboter][1]</p>

<p><img src="https://s3.xopic.de/moochouse-public/courses/5IrTNQ46jTgyCZkhYpzOYI/rtfiles/7mIXt6yWtw4ILOvNdnVATS/dolly.png" alt="Plastikschaf auf Rasenmähroboter"></p>

<h2>Downloads</h2>

<p>Andere Dateiformate die zum Download bereitgestellt werden sollen, werden identisch zu den Bildern eingebunden. </p>

<p><img src="https://s3.xopic.de/moochouse-public/courses/5IrTNQ46jTgyCZkhYpzOYI/rtfiles/5uEwOdjFkmM3VheUmEYUCH/1_UploadTest-Ludwigshafen.pdf" alt="enter image description here"><br>
![enter image description here][2]</p>

<p>Im Nachgang muss das <code>!</code> vor den eckigen Klammern entfernt werden und ein vernünftiger Text zur Beschriftung des Download-Links eingefügt werden.</p>

<p><a target="_blank" rel="noopener" href="https://mooc.house/go/link?url=https%3A%2F%2Fs3.xopic.de%2Fmoochouse-public%2Fcourses%2F5IrTNQ46jTgyCZkhYpzOYI%2Frtfiles%2F5uEwOdjFkmM3VheUmEYUCH%2F1_UploadTest-Ludwigshafen.pdf&checksum=cf5a772&tracking_type=rich_text_item_link&tracking_id=39c63dff-abf9-4157-81f3-0b7b50fa8856&tracking_course_id=bbd72c9c-e830-4029-8459-21913f553ab4">Download</a><br>
[Download][2]</p>

<h2>Tabellen</h2>

<table><thead>
<tr>
<th>Month</th>
<th>Savings</th>
<th>Spending</th>
</tr>
</thead><tbody>
<tr>
<td>January</td>
<td>$100</td>
<td>$900</td>
</tr>
<tr>
<td>July</td>
<td>$750</td>
<td>$1000</td>
</tr>
<tr>
<td>December</td>
<td>$250</td>
<td>$300</td>
</tr>
<tr>
<td>April</td>
<td>$400</td>
<td>$700</td>
</tr>
</tbody></table>

<p>|Month|Savings|Spending|<br>
|- - - |- - - |- - - |  (Leerzeichen sind nur zur besseren Lesbarkeit eingefügt)<br>
|January|$100|$900|<br>
|July|$750|$1000|<br>
|December|$250|$300|<br>
|April|$400|$700|  </p>
