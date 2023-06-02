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

### a. Erklären Sie den Begriff „Responsives Webdesign“

Responsives Webdesign bezieht sich auf die Gestaltung und Entwicklung von Websites, die sich automatisch an verschiedene Bildschirmgrößen und Geräte anpassen. 
Das Ziel des responsiven Webdesigns besteht darin, sicherzustellen, dass eine Website unabhängig vom verwendeten Gerät oder der Bildschirmgröße optimal dargestellt
wird, indem das Layout und die Elemente der Website flexibel und dynamisch angepasst werden.

Durch den Einsatz von responsivem Webdesign wird sichergestellt, dass Benutzer die Website auf Desktop-Computern, Laptops, Tablets oder Smartphones gleichermaßen
gut betrachten und bedienen können, ohne dass sie horizontal scrollen oder unleserlich kleine Elemente sehen müssen.
Das responsive Design ermöglicht eine optimierte Benutzererfahrung und verbessert die Zugänglichkeit der Website auf verschiedenen Geräten.

Um eine responsive Website zu erstellen, werden verschiedene Techniken eingesetzt, wie z.B. flexible Rasterlayouts, Media Queries und mobile Navigation. 
Durch den Einsatz dieser Techniken kann die Website auf Basis der Bildschirmgröße, des Seitenverhältnisses und der Ausrichtung des Geräts unterschiedliche 
CSS-Regeln anwenden und so das Erscheinungsbild und die Anordnung der Elemente anpassen.


### b. und stellen Sie die Flex-Box-Technik an Hand von Beispielen genauer vor

Die Flexbox-Technik ist eine CSS-Layout-Methode, die es ermöglicht, flexible und dynamische Layouts zu erstellen. Mit Flexbox können Elemente in einem 
Container entweder horizontal oder vertikal ausgerichtet und in Reihen und Spalten angeordnet werden, um auf unterschiedliche 
Bildschirmgrößen und -ausrichtungen zu reagieren.

Beispiel:

```css
.container {
  display: flex;
  justify-content: space-between;
}

.item {
  flex: 1;
  margin: 10px;
  padding: 20px;
  background-color: lightgray;
}
```

---
