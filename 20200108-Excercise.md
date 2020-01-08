# 2020-01-08, Excercise

### Wann aside innerhalb von article, wann außerhalb?
Wenn die Inhalte des *aside* thematisch zum *article* dazugehören, schreibt man sie in den *article*.

### Was kommt in main rein? Wie oft darf man main pro Seite verwenden?
Innerhalb des *main*-Elements kommen die Hauptbestandteile bzw. inhaltlich wichtigsten Elemente der jeweiligen Seite. *main* verwendet man lediglich einmal pro Seite.

### Wann ist div geeigneter als section?
*div* ist für den Fall besser geeignet, dass die Inhalte nicht zwingend zusammengehören, also kein in sich geschlossenes Kapitel bilden, das man mit einer Überschrift zusammenfassen könnte.

### Wann verwendet man b und wann strong? Wann i und wann em?
Bei Verwendung von *strong* oder auch *em* geht es nicht allein um die optische Darstellung – in diesem Fall *Fettdruck* und *Kursivschreibung*, sondern auch um die semantische Hervorhebung. *b* und *i* hingegen sind lediglich für die optische Gestaltung vorgesehen.

### Wie baut man eine figure mit einem Bild und Text auf?
<figure>
<img src="image.img" alt="Fotobeschreibung">
<figcaption>Ergänzender Text für das Bild</figcaption>
<figure>

### Wofür steht dl, dd und dt
Das Element *dl* steht für Description list. Man verwendet es z.B. für ein Glossar oder die Darstellung von Metadaten. *dd* steht für die Beschreibung eines Begriffes innerhalb der Description list. *dt* steht für Definition Term und zeigt einen Begriff in der Liste. Ihm kann ein *dd* folgen.

### Was sind 3 void Elemente, die du kennst?
1. img
2. br
3. input

### Wofür wird small verwendet?
Zum Beispiel für Fußnoten oder Quellen-Angaben.

### Was ist der Unterschied zwischen dem img- und dem picture-Element?
Das picture-Element ist lediglich ein Container, der ein oder mehrere img-Dateien enthalten kann. Innerhalb des Containers können auch mehrere Bildversionen eines Images enthalten sein. So kann ein Browser das passende Bild wählen, z.B. nach Auflösung.

### Welche 5 input-types kennst du neben <input type="text">?
1. date
2. color
3. email
4. url
5. range

### Was macht man mit select und option?
Man kreiert eine Drop-Down-Liste mit verschiedenen Optionnen. Z.B.:
<select>
<option value="one">One</option>
<option value="two">Two</option>
<option value="three">Three</option>
</select>