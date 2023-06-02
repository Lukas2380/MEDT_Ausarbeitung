# MEDT_Ausarbeitung
Matura Ausarbeitung für Medientechnik

##  1) Soundbearbeitung

---
**Frage:**

9.)
Erklären Sie, welche Produkte der Soundbearbeitung Sie kennen und welche
Möglichkeiten der Bearbeitung diese bieten. Nennen Sie auch unterschiedliche SoundFormate sowie deren Vor- und Nachteile und zeigen Sie an Hand von Codebeispielen,
wie Sounddateien in eine Webseite integriert werden können.

---

## 2) Javascript

---
**Frage:**

12.)
Beschreiben Sie den Einsatz von Javascript in der Webentwicklung. Stellen Sie die
Syntax von Javascript jener von C# gegenüber und zeigen Sie wesentliche
Unterschiede und Gemeinsamkeiten auf. Demonstrieren Sie das Zusammenspiel
zwischen dem HTML-Form-Element und Javascript an Hand eines typischen Beispiels.

---

JavaScript ist eine Skriptsprache, die in die HTML-Codezeilen einer Webseite eingefügt wird, um Interaktivität und dynamische Funktionen zu ermöglichen. Im Gegensatz zu serverseitigen Skriptsprachen wie PHP oder Perl wird JavaScript direkt im Browser des Benutzers ausgeführt. Es ermöglicht die Reaktion auf Benutzeraktionen und bietet zahlreiche Funktionen, die mit reinem HTML nicht realisierbar sind.

Der Einsatz von JavaScript in der Webentwicklung umfasst unter anderem:

1. Interaktive Benutzeroberflächen: JavaScript ermöglicht das Hinzufügen von Funktionen wie Dropdown-Menüs, Formularvalidierung, Benutzereingaben und interaktiven Elementen wie Bildwechseln bei Mauszeigerbewegungen.

2. Dynamische Inhalte: Mit JavaScript können Inhalte dynamisch geladen und aktualisiert werden, ohne die gesamte Seite neu laden zu müssen. Dies ermöglicht beispielsweise das Nachladen von zusätzlichen Inhalten beim Scrollen oder das Aktualisieren von Daten in Echtzeit.

3. Event-Handling: JavaScript ermöglicht das Hinzufügen von Event-Handlern zu HTML-Elementen, um auf Benutzeraktionen wie Klicks, Tastatureingaben oder Mausbewegungen zu reagieren. Dadurch können bestimmte Aktionen ausgelöst werden, wie das Validieren von Formulareingaben oder das Auslösen von Animationen.

4. Manipulation des DOM (Document Object Model): JavaScript ermöglicht das dynamische Ändern und Manipulieren des DOM-Baums einer Webseite. Dies umfasst das Hinzufügen, Entfernen oder Ändern von HTML-Elementen und Attributen sowie das Ändern von CSS-Stilen.

## Stellen Sie die Syntax von Javascript jener von C# gegenüber und zeigen Sie wesentliche Unterschiede und Gemeinsamkeiten auf

Gemeinsamkeiten:
- Beide Sprachen sind imperativ und objektorientiert.
- Sie verwenden ähnliche Kontrollstrukturen wie Schleifen (for, while) und bedingte Anweisungen (if, else).
- Beide Sprachen unterstützen Funktionen und ermöglichen die Verwendung von Variablen.

Unterschiede:
- JavaScript ist eine interpretierte Skriptsprache, während C# eine kompilierte Sprache ist.
- JavaScript verwendet das Prototypenerbemodell, während C# das Klassen- und Vererbungsmodell verwendet.
- Die Syntax von JavaScript ist lockerer und flexibler als die von C#, was sich beispielsweise in der Verwendung von Semikolons und geschweiften Klammern zeigt.
- JavaScript hat eine dynamische Typisierung, während C# statisch typisiert ist.
- JavaScript wird meistens im Browser ausgeführt, während C# hauptsächlich für die Entwicklung von Desktop- und Serveranwendungen verwendet wird.

## Beispiel:

#### HTML:
```html
<form>
  <input type="text" id="nameInput">
  <button type="button" onclick="greet()">Greet</button>
</form>
<p id="greeting"></p>
```

#### JavaScript:
```javascript
function greet() {
  var name = document.getElementById("nameInput").value;
  var greetingElement = document.getElementById("greeting");
  greetingElement.innerHTML = "Hello, " + name + "!";
}
```

In diesem Beispiel wird mittels eines Formulars ein Name abgefragt. Der User kann nach dem eingeben eines Namens den "Greet" button betätigen. 
Dann wird im Hintergrund die "greet()" Function aufgerufen. In dieser wird der Text des ```<p></p>``` Tags auf "Hello, " + Name geändert.

## 3) Responsives Webdesign und Flex-Box

---
**Frage:**

18.)\
a. Erklären Sie den Begriff „Responsives Webdesign“\
b. und stellen Sie die Flex-Box-Technik an Hand von Beispielen genauer vor

---
