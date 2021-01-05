- [Termin 1](#termin-1)
- [HTML](#html)
  - [Listen](#listen)
- [CSS](#css)
  - [Padding/Border/Margin](#paddingbordermargin)
    - [Padding](#padding)
    - [Border](#border)
    - [Margin](#margin)
  - [Schriftformatierung](#schriftformatierung)
    - [styling von Links](#styling-von-links)
  - [ID und Span](#id-und-span)
  - [Klassen](#klassen)
  - [DIV](#div)
  - [child selector](#child-selector)
- [Termin 3: Bootstrap](#termin-3-bootstrap)
  - [Grid System](#grid-system)
  - [Textelemente: Bspw. Headers, mark usw](#textelemente-bspw-headers-mark-usw)
  - [Bootstrap Table](#bootstrap-table)
  - [Bilder](#bilder)
  - [Jumbotron](#jumbotron)
  - [Alertmeldungen](#alertmeldungen)
  - [Knöpfe](#knöpfe)
    - [Knöpfe gruppieren](#knöpfe-gruppieren)
  - [Drop down Menu](#drop-down-menu)
  - [Font Awesome](#font-awesome)
  - [Beschriftungen (Badges)](#beschriftungen-badges)
  - [Fortschrittsbalken (Progress Bars)](#fortschrittsbalken-progress-bars)
  - [Spinners](#spinners)
- [Termin 4 Bootsrap (continued)](#termin-4-bootsrap-continued)
  - [Seitennummerierung (Pagination)](#seitennummerierung-pagination)
  - [Breadcrumbs](#breadcrumbs)
  - [List Groups: Listen von Items (die man auswählen kann)](#list-groups-listen-von-items-die-man-auswählen-kann)
  - [Cards](#cards)
  - [Dropdowns](#dropdowns)
  - [Collapse](#collapse)
  - [Navs (Navigationselemente)](#navs-navigationselemente)
  - [Navigation Bar](#navigation-bar)
  - [Carousel](#carousel)
- [Termin 5: Javascript](#termin-5-javascript)
  - [Platz im Code](#platz-im-code)
  - [Variablen](#variablen)
    - [Variablentypen](#variablentypen)
    - [Lokale und globale variablen](#lokale-und-globale-variablen)
  - [Kommentieren in JS](#kommentieren-in-js)
  - [Funktionen](#funktionen)
    - [HTML `<form>`](#html-form)
    - [Parameter in funktionen](#parameter-in-funktionen)
    - [Funktionen innerhalb von Funktionen](#funktionen-innerhalb-von-funktionen)
    - [Return statement](#return-statement)
  - [Mathematische Operatoren](#mathematische-operatoren)
  - [getElementById()](#getelementbyid)
- [Termin 6 (Loop, For Loop, If Else, switch & case)](#termin-6-loop-for-loop-if-else-switch--case)
  - [Loops](#loops)
    - [Do While](#do-while)
    - [While](#while)
    - [for loop](#for-loop)
  - [If Else & Else if](#if-else--else-if)
    - [Mehrere Bedingungen](#mehrere-bedingungen)
  - [Switch und case](#switch-und-case)
  - [createElement()](#createelement)
  - [appendChild()](#appendchild)
- [Termin 7 (Objekte und Arrays)](#termin-7-objekte-und-arrays)
  - [Objekte](#objekte)
    - [Funktionen von Objekten](#funktionen-von-objekten)
    - [Object initializer](#object-initializer)
    - [Math Objekt (Library)](#math-objekt-library)
    - [Date Objekt (Library)](#date-objekt-library)
  - [Array](#array)
    - [Array Eigenschaften und Funktionen](#array-eigenschaften-und-funktionen)
    - [array und for loop](#array-und-for-loop)
  - [Promts](#promts)
    - [Promt und Array](#promt-und-array)
- [Termin 8 Python `to do`](#termin-8-python-to-do)
  - [work with strings](#work-with-strings)
    - [Einzelne Buchstaben ändern](#einzelne-buchstaben-ändern)
      - [Alle Buchstaben die gleich sind ersetzen](#alle-buchstaben-die-gleich-sind-ersetzen)
  - [While schleife](#while-schleife)
  - [For schleife](#for-schleife)
  - [range()](#range)
  - [break & continue](#break--continue)
    - [break](#break)
    - [continue](#continue)
  - [funktionen](#funktionen-1)
- [Termin 9 Lists and dicts](#termin-9-lists-and-dicts)
  - [Sammel-Datentypen](#sammel-datentypen)
  - [Lists](#lists)
    - [Work with lists](#work-with-lists)
    - [check if item of list is int](#check-if-item-of-list-is-int)
    - [work with strings](#work-with-strings-1)
    - [Einzelne Buchstaben ändern](#einzelne-buchstaben-ändern-1)
      - [Alle Buchstaben die gleich sind ersetzen](#alle-buchstaben-die-gleich-sind-ersetzen-1)
    - [`range()` and `list()`](#range-and-list)
    - [`slice()`](#slice)
  - [.sort() und und sorted() für listen](#sort-und-und-sorted-für-listen)
    - [Listen in Listen](#listen-in-listen)
  - [Dictionaries](#dictionaries)
    - [Einen neuen key mit Value dem Dict hinzufügen:](#einen-neuen-key-mit-value-dem-dict-hinzufügen)
    - [Get a Values, Keys or both from an Dict](#get-a-values-keys-or-both-from-an-dict)
    - [Eine Liste davon bekommen:](#eine-liste-davon-bekommen)
    - [nested Dictionaries](#nested-dictionaries)
    - [Dict aus zwei listen erstellen (mit zip())](#dict-aus-zwei-listen-erstellen-mit-zip)
- [Termin 10](#termin-10)
  - [Eigene Module machen](#eigene-module-machen)
  - [write and read to txt](#write-and-read-to-txt)
    - [write](#write)
    - [read](#read)
  - [Dateien mit JSON lesen und schreiben](#dateien-mit-json-lesen-und-schreiben)

<div style="page-break-after: always;"></div>

# Termin 1
# HTML
* Man braucht für alles einen Tag
* HTML ist widespace insensitive (leerzeichen und Umrbüche werden ignoriert)


Aufbau Standard
```html
<!doctype html>
<html>
<head>
    <title>
        
    </title>
</head>
<body>
</body>
</html>
```
	
Homepage ist aufgeteilt in head: informaitonen die für den browser notwendig sind

verschiedene Tags

Double Tags müssen wieder geschlossen werden
* Beispiel `</h1>` & `</h2>`


Single Tags
* `<br/>` (Das steht für break: Zeilenumbruch)

| Tag                          | Beschreibung                                                 |
| :--------------------------- | :----------------------------------------------------------- |
| `<html>`                     |                                                              |
|                              |                                                              |
| `<p>`                        | Neuer Paragraph                                              |
| `<br/>`                      | Zeilenumbruch (single tag), nicht für layout zwecke brauchen |
| `<strong>`                   | Fett                                                         |
| `<em>`                       | Kursiv (emphasize)                                           |
| `<!-- kommentar -->`         | Kommentar                                                    |
| `<img src="name.png"/>`      | Bildtag (single tag)                                         |
| `<a href = "link" >text</a>` | a = anchor                                                   |
| `<table>`                    | arg.: cellpadding , colspan: tabellenüberschrift             |
| `<tr>`                       | Tablerow                                                     |
| th                           | Tableheader                                                  |
| td                           | Tabledata                                                    |
| cellpadding                  | Abstand zum Rand                                             |
| `</ul>`                      | Unordered List                                               |
| `</ol>`                      | Ordered list                                                 |
| `<meta charset="uft-8">`     | Macht umlaute weniger problematisch                          |
|                              |                                                              |



## Listen

* Gordnete Liste = Nummeriert
* Ungeordnete Liste = Aufzählungszichen


# CSS

Spezieferische Regeln stehen über den anderen. Bspw. Regel für Paragraph > Body

`<style></style>` --> Braucht nicht mehr das `type="text/css"`

## Padding/Border/Margin
### Padding
<img src='../media/border_padding.png' width="400" >

DE: Innenpolster, rand um den Text
```html
<style type="text/css">
<!-- überall 24px -->
h1{
    padding:24px; 
    padding-top: 12px;
    padding-bottom: 30px;
}

h1, h2{
    color: red;
}
</style>
```
### Border

* color
* style
* width

```html
<style type="text/css">
h1{
    border-style: dashed;
    border-color: red;
    border-width: 2px;
    border: 2px dashed red;
}
</style>
```

### Margin
Abstand zwischen zwei Inhalten
0px für keinen Abstand, ein gewisser abstand bleibt aber

## Schriftformatierung

font-weight: dicke der Schrift
font-style: italic -> Kursiv

### styling von Links

```html
<style type="text/css">
    a:link{color:yellow}
    a:visited{color: red}
    a:hover{
        background-color: red; 
        color: green;
        font-wheight: bold;
        }
    a:active{background-color:blue}
</style>
    <body>
        <a href="https://de.wikipedia.org/wiki/Wombats"> Link zu Wiki
    </body>
```


Links können 4 Zustände haben: 
* Noch nie besucht: blau, link
* Klicken: Rot, active
* Drüber Fahren (unterstrichen, z.B. bei google) hover
* Seite Besucht: Violett, visited

## ID und Span

Mit einer ID werden alle anderen Regeln überschrieben.
Mit ID kann man Eigenschaften einzelner Tags/Paragraphen/Überschriften ändern
Span wird direkt beim Text eingefügt. Span kann auch mit einer ID versehen werden.
```html
    <style type="text/css">
        #wombat{
            color:red;
        }
        span{
            font-weight: bold;
        }
        #red {
            color: red;
        }
    </style>
<body>
    <p id ="wombat">Wombats sind <span id="red">cool</span>. Sogar Sehr!</p>
</body>
```

## Klassen
Man kann eine Regel  nicht abhängig von einem Tag erstellen sondern von einer Klasse. Man legt erst die Regeln fest, und geht dann bei den Tags (bspw. `<p>` oder `<h1>`) hin und ordnet das zu.

```html
    <style type="text/css">
        .rotblau{
            background-color: red; color: blue;
        }
    </style>
<body>
    <p class='rotblau'>Wombats sind cool Sogar Sehr!</p>
</body>
```
Wenn man vor der Definition der klasse etwas schreibt, kann man das nur noch für das entsprechende Tag verwenden.

```html
    <style type="text/css">
        h1.rotblau{
            background-color: red; color: blue;
        }
    </style>
<body>
    <h1 class='rotblau'>Wombats</h1>
    <p class='rotblau'>Wombats sind cool Sogar Sehr!</p>
</body>
```

In diesem Beispiel passiert beim `<p>` nichts.

## DIV

herausfinden, warum DIV machen und nicht einfach mit Paragraphen arbeiten?

## child selector

Child = etwas innerhalb eines anderen Tags. Bspw. ist die `<li>` in diesem Fall das Child. Um es auszuwählen siehe unten. Geht beispielsweise, wenn man nur die Links formatieren will, welche in einem Paragraphen sind `p>a{color:red}`
```html
    ul > li {color:red}
    <!--in diesem Fall wird die ordered list nicht rot gefärbt-->
	<ul>
		<li>Kind1</li>
        <li>Kind2</li>
            <ol> <!-- = Enkel von <ul>-->
                <li>urenkel1</li>
                <li>Urenkel2</li>
		<li>Kinde</li>
	</ul>
```

<div style="page-break-after: always;"></div>

# Termin 3: Bootstrap

Webseite: https://getbootstrap.com/

Damit kann man relativ einfach Webseiten gestalten, ohne dass man selbst sehr viel stylen muss.

Es besteht aus CSS und Javascript files.

Keine Ahnung was das macht, aber das muss man glaube ich einfügen im Header Teil:
```html
<head>
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</head>
```

## Grid System

<img src="../media/BS_grid.png">

Beispiel:
```html
 <div class="row">
  <div class="col-sm-4">insert text here</div>
  <div class="col-sm-8" style="background-color: red">insert text here</div>
</div>
```

Es gibt verschiedene klassen (5)

* .col- (extra small devices - screen width less than 576px)
* .col-sm- (small devices - screen width equal to or greater than 576px)
* .col-md- (medium devices - screen width equal to or greater than 768px)
* .col-lg- (large devices - screen width equal to or greater than 992px)
* .col-xl- (xlarge devices - screen width equal to or greater than 1200px)

Small devices, macht dass ab einer gewissen breite, die spalten untereinander kommen

## Textelemente: Bspw. Headers, mark usw

```html
<mark>
 <div class="row">
  <div class="col-sm-4">insert text here</div>
  <div class="col-sm-8" style="background-color: red">insert text here</div>
</div>
```
* Siehe dazu unter w3schools: BS4 Typography, Colors

## Bootstrap Table

* Normaler Aufbau von HTML
* Braucht für BS4 die class `class="table"`
* praktisch ist bspw: (hovering aktivieren)

```html
    <div class"col-sm-8">Text goes here <table class ="tale table-hover"> (usw)
        </div>
```

## Bilder

* Bild klassisch einfügen `<img src="path/path/img.dateienformat>`
* BS4 einbinden. Bspw: `<img src="path/path/img.dateienformat class = "rounded">`
* Dann noch thumbnail dazu: `<img src="path/path/img.dateienformat class = "rounded img-thumbnail">`

Platzieren
* Bilder kommen ohne weiteren Code untereinander. 
* Links oder rechts platzieren: `<img src="path/path/img.dateienformat class="rounded float right">`
## Jumbotron

Braucht man um Text schöner darzustellen. Es kommt einfach oben so eine box

```html
<body>
    <div class = "container">
        <div class = "jumbotron">
            (hier kann text stehen, bspw mit header h1)
        </div>
        das ist wieder normaler text
    </div>
```
## Alertmeldungen

Findet man als "BS4 Alerts". Alerts are created with the .alert class, followed by one of the contextual classes .alert-success, .alert-info, .alert-warning, .alert-danger, .alert-primary, .alert-secondary, .alert-light or .alert-dark


```html
<div class="alert alert-success">
  <strong>Success!</strong> Indicates a successful or positive action.
</div>
```

## Knöpfe
Befehle mit JS machen, oder auf Links springen
* Grundstrukltur `<button type="button" class="btn">Basic</button>`
* `<button type="button" class="btn btn-danger">Basic</button>` (roter knopf)
* Link hinzufügen -> ist dann nicht mehr `<button>`sondern `<a>`, und nicht mehr type sondern role
  * `<a role="button" class="btn" href="link">Basic</a>`

### Knöpfe gruppieren
```html
    <div class"btn-group>
        <a role="button" class="btn" href="link">Basic</a>
        <a role="button" class="btn" href="link">Basic</a>
        <a role="button" class="btn" href="link">Basic</a>
    </div>
```
## Drop down Menu
BS4 Dropdowns
```html
    <div class="dropdown">
        <button type="button" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">
            Dropdown button
        </button>
        <div class="dropdown-menu">
            <a class="dropdown-item" href="#">Link 1</a>
            <a class="dropdown-item" href="#">Link 2</a>
            <a class="dropdown-item" href="#">Link 3</a>
        </div>
    </div>
    </div>
```
The .dropdown class indicates a dropdown menu.

To open the dropdown menu, use a button or a link with a class of .dropdown-toggle and the data-toggle="dropdown" attribute.

Add the .dropdown-menu class to a <div> element to actually build the dropdown menu. Then add the .dropdown-item class to each element (links or buttons) inside the dropdown menu

## Font Awesome
* Einbinden unterhalb der Bootstrap CSS einbindung
* W3schools -> `CSS Icons`, Nicht bei BS4!
* tag: `<i> </i>`

```html
<!DOCTYPE html>
<html>
<head>
<script src="https://kit.fontawesome.com/a076d05399.js"></script>
</head>
<body>

<i class="fas fa-cloud"></i>
<i class="fas fa-heart"></i>
<i class="fas fa-car"></i>
<i class="fas fa-file"></i>
<i class="fas fa-bars"></i>

</body>
</html>
```

Einbinden bei einem Link-knopf: `<a role="button" class="btn" href="link"><i class="fas fa-cloud"></i>Cloud</a>`

## Beschriftungen (Badges)
* BS4 Badges
* Beispiel `<h1> heading <span class="badge badge-danger">Danger</span></h1>`

## Fortschrittsbalken (Progress Bars)
* BS4 Progress Bars
```html
<div class="progress">
  <div class="progress-bar" style="width:70%"></div>
</div>
```

Kombinieren von Progress bars ("Multiple Progress Bars")
## Spinners
* BS 4 Spinners

<div style="page-break-after: always;"></div>

# Termin 4 Bootsrap (continued)

## Seitennummerierung (Pagination)
* BS4 Pagination 
* bspw sehr lange datentabelle
* ist einfach eine unordered list und innerhalb items

```html
<ul class="pagination">
  <li class="page-item"><a class="page-link" href="#">Previous</a></li>
  <li class="page-item"><a class="page-link" href="#">1</a></li>
  <li class="page-item"><a class="page-link" href="#">2</a></li>
  <li class="page-item"><a class="page-link" href="#">3</a></li>
  <li class="page-item"><a class="page-link" href="#">Next</a></li>
</ul>
```


## Breadcrumbs
* BS4 Pagination: ganz unten "bredcrubs"
* oben auf der Seite wird dann ein Pfad angezeigt wie man dazu gekommen ist
* praktisch wenn eine webseite sehr verschachtelt ist


## List Groups: Listen von Items (die man auswählen kann)
* BS4 List Groups
* Könnte auch mit links hinterlegt werden (`<a>` statt `<li>`)

```html
<ul class="list-group">
  <li class="list-group-item">First item</li>
  <li class="list-group-item">Second item</li>
  <li class="list-group-item">Third item</li>
</ul>
```

## Cards
Ist auch zum Formatieren. Bspw ein Produkt mit Foto und Text & Link
* BS4 Cards

Hie ein Bsp. ganz basic, mit Angabe zur Breite
```html
<div class="card" stale="width: 300px">
  <div class="card-body">Basic card</div>
</div>
``` 

Es gibt auch noch die option header und footer, braucht es aber nicht zwingend

## Dropdowns
* BS4 Dropdown
* Ist speziefischer als Button groups
* Man kann das Dropdown menü noch mehr stylen. Mit headers oder dividers

```html
<div class="dropdown">
  <button type="button" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">
    Dropdown button
  </button>
  <div class="dropdown-menu">
    <a class="dropdown-item" href="#">Link 1</a>
    <a class="dropdown-item" href="#">Link 2</a>
    <a class="dropdown-item" href="#">Link 3</a>
  </div>
</div>
```

## Collapse
* BS4 Collapse
* Dinge einklappen, wenn ein Teil von Text collapsed werden soll (erst anzeigen, wenn man drauf geklickt hat)
* Fängt an mit einem Knopf, data-target = man muss dem div eine id geben

```html
<button data-toggle="collapse" data-target="#demo">click here for more info</button>

<div id="demo" class="collapse">
Lorem ipsum dolor text....
</div>
```

## Navs (Navigationselemente)
* BS4 Navs
* Ist ein menu das sich an die device grösse anpasst (automatisch)
* hat auch drop down optionen (bsp class="dropdown-menu")

## Navigation Bar
* BS4 Navbars
* Navigationsbars, wie sie es ganz oft auf webseiten gibt

<img src="../media/nav_bar.png">
  
  
## Carousel
* BS4 Carousel
* Bild oder text bei dem man rechts oder links klicken kann und eine nächste Slide kommt


<div style="page-break-after: always;"></div>

# Termin 5: Javascript
Kurze Übersicht:
- Html = was kommt in die homepage
- css = wie sieht sie aus?
- JS = was kann sie?

## Platz im Code

```html
<!DOCTYPE html>
<head>
</head>
    <body>
        <script type = "text/javascript">
        </script>
    </body>
</html>
```

## Variablen
- variable = speicher
- muss man zunächst anlegen
  - var alter = 25;
- Muss mit einem Buchstaben beginnen 
  - Nur buchstaben, zahlen und underscore (?! usw geht nicht)

```html
<!DOCTYPE html>
<head>
</head>
    <body>
        <script type = "text/javascript">
            var alter = 25;
            var name = "lars";
            document.write(alter);
            // mehrere vars gleichzeitig erstellen:
            var x,y,z;
        </script>
    </body>
</html>
```

### Variablentypen
- var vergeben = false;
- var leer = null; (nicht null, sondern einfach leer)
- var alter = 25;
- var name = "lars";

```html
        <script type = "text/javascript">
            var alter = 25;
            var name = "lars";
            var vergeben = false;
            document.write("name ist " +  name + " er ist" + alter + " alt und vergeben:" + vergeben);
            // mehrere vars gleichzeitig erstellen:
            var x,y,z;
        </script>
```

### Lokale und globale variablen
- lokal = innerhalb einer Funktion
  - Kann nicht ausserhalb der Funktion verwendet werden
- global = ausserhalb einer funktion
- dieselbe notation: `var abc = 5;`


## Kommentieren in JS
- ctrl + § (zeichen unterhalb von Esc)

```html
        <script type = "text/javascript">
            var x,y,z;
            var sehrKomplizeirt = "komplizierte funktion"
// das ist ein kommentar
            var a;
/*
das ist
ein langer kommentar
*/    
        </script>
```

## Funktionen

```html
        <script type = "text/javascript">
            function geklickt(){
                alert("kannst du nicht lesen?");
            }
        </script>
        <form>
            <!-- button der beim klicken die funktion aufruft -->
            <input onclick="geklickt()" type="button" value="Nicht klicken!"/>
        </form>
```


### HTML `<form>`
- Dass der nutzer uns Informationen geben kann
- Aufbau: Kommt innerhalb vom Body, nach `<script>`

Beispiel
```html
    <body>
        <script type = "text/javascript">
        </script>
        <form>
            Benutzername: <input type="text" name="benutzername"/>
        </form>
    </body>
```

### Parameter in funktionen
- Parameter kommt in die runde klammer nach der funktion

```html
        <script type = "text/javascript">
            function liebestest(name1, name2){
                var punktZahl;
                punktZahl= (name1+name2).lenght;
                document.write("Eure Namen haben " + punktzahl + " punkte");
            }
            liebesTest("klara","klaus");
        </script>
```

### Funktionen innerhalb von Funktionen

- Von der Idee her genau gleich wie bei Python
- Beispiel mit dem Käfer der nur gerade aus und nach links drehen kann
  
```html
        <script type = "text/javascript">
            function goSomewhere (steps){
                stepFw(steps);
                turnright();
                stepFW(steps+1);
                turnleft();
            }
            function turnright(){
                turnleft(3);
            }
            goSomewhere(9);
        </script>
```

### Return statement
- sobald return in der funktion steht, wird der rest des codes in der funktion ignoriert
Beispiel
```html
        <script type = "text/javascript">
          function liebestest(name1, name2){
                var punktZahl;
                punktZahl= (name1+name2).lenght;
                return punktZahl;
            }
            liebesTest("klara","klaus");
        </script>

<!-- Ausgabe = 10 -->
```

## Mathematische Operatoren
- Addition: +
  - 1 addieren: variable++ (`result++;`)
  - 3 addieren: variable += 3
- Subtraktion: -
  - 1 reduzieren: variable--
  - 3 reduzieren: variable -=3
- Multiplikation: *
  - altes ergebnis *5: ergebnis *=5;
- Division: / (5/3 = 1.6667 ausugabe in float)
  - altes ergebnis /5: ergebnis /=5;
- Modulo: % (5%3 = 2)

## getElementById()
The getElementById() method returns the element that has the ID attribute with the specified value.

This method is one of the most common methods in the HTML DOM, and is used almost every time you want to manipulate, or get info from, an element on your document.

Returns null if no elements with the specified ID exists.

An ID should be unique within a page. However, if more than one element with the specified ID exists, the getElementById() method returns the first element in the source code.

```html
<!DOCTYPE html>
<html>
    <body>

        <p id="demo">Click the button to change the text in this paragraph.</p>

        <button onclick="myFunction()">Try it</button>

    <script type = "text/javascript">
        function myFunction() {
          document.getElementById("demo").innerHTML = "Hello World";
        }
    </script>

    </body>
</html>
``` 

Erklärung: es erscheint der text, sobald man den Knopf drückt erscheint Hello World

weiteres Beispiel von der übung
```html
<!DOCTYPE html>
<html>
    <body>
            <script type = "text/javascript">
            function myAlert() {
                alert(document.getElementById("content").value);
            }
        </script>
        <input type="text" id="content">
        <input type="button" value="Klick mich" onclick="myAlert()">
    </body>
</html>
```
Erklärung: 
<img src="../media/termin6.png">

<div style="page-break-after: always;"></div>

# Termin 6 (Loop, For Loop, If Else, switch & case)

## Loops
3 While loops
- Do while loop (W3Scools: JS Loop While)
- While loop (W3Scools: JS Loop While)
- For loop (W3Scools: JS Loop For)

### Do While
- The do/while loop is a variant of the while loop. This loop will execute the code block once, `before` checking if the condition is true, then it will repeat the loop as long as the condition is true.

```html
<script type = "text/javascript">
var i = 11;

do {
  document.write("<br>The number is " + i);
  i++;
}
while (i < 10);  
</script>
```
Ausgabe = "The number is 11"
- Ausgabe entsteht also auch, trotzdem die condition falsch ist

### While
```html
<script type = "text/javascript">
var i = 1;

while (i < 10) {
  document.write("<br>The number is " + i);
  i++;
}
  
</script>
```

### for loop

- Aufbau: for(variable;condition;befehl){code}
- Bspw: `for(var i=0;i<15;i+=3){document.write("hello")}`
  
```html
<script type = "text/javascript">
var i = 1;

while (i < 10) {
  document.write("<br>The number is " + i);
  i++;
}
  
</script>
```

## If Else & Else if

Aufbau:
```html
<script type = "text/javascript">
if (condition1) {
  //  block of code to be executed if condition1 is true
} else if (condition2) {
  //  block of code to be executed if the condition1 is false and condition2 is true
} else {
  //  block of code to be executed if the condition1 is false and condition2 is false
}
</script>
```

- Verschiedene Bedingungen
  - <, >, =
  - == ("ist gleich") bspw für text

### Mehrere Bedingungen
- AND: `&&`
- OR: `||` (Taste 7)
- Nicht AND (if not rich and 21) `if(!()&&())`
  - `!`vor erster oder zweiter bedingung
- Nicht OR (If rich or not < 21) `if(()||!())`
```html
<script type = "text/javascript">
    var reich = true;
    var alter = 21;
    if ((reich == true) && (alter>21)){
        document.write("Welcome to the club")
    }
</script>
```

## Switch und case
- Wie if und Else IF, aber schneller bei Browser und Smartphone
- Switch = ein Schalter für eine Variable
- Case = Was ist bei welchem Fall zu machen?
- Break = um aus dem switch herauszuspringen. Ansonsten geht er zum nächsten break
  
```html
<script type = "text/javascript">
    switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
</script>
```
This is how it works:
- The switch expression is evaluated once.
- The value of the expression is compared with the values of each case.
- If there is a match, the associated block of code is executed.
- If there is no match, the default code block is executed.

## createElement() 

- The createElement() method creates an Element Node with the specified name.
- e.g. `document.createElement("BUTTON")` 
- Weitere möglichkeiten
  - `createElement("p")` -> paragraph
  - `createElement("div")`
  - `createElement("LI")`  -> bulletpoint
  - 

- Oft zusammen gebraucht mit appendChild(): After the element is created, use the element.appendChild() or element.insertBefore() method to insert it to the document.


```html
<body>
  <p>Click the button to make a BUTTON element.</p>
  <button onclick="myFunction()">Try it</button>
  <script>
    function myFunction() {
      var btn = document.createElement("BUTTON");
      document.body.appendChild(btn);
    }
  </script>
</body>
```

## appendChild()
- he appendChild() method appends a node as the last child of a node.
- If you want to create a new paragraph, with text, remember to create the text as a Text node which you append to the paragraph, then append the paragraph to the document. (Bspw. Bulletpoint erstellen, text appenden, das [bul] zusammen dem document appenden)

<div style="page-break-after: always;"></div>

# Termin 7 (Objekte und Arrays)

## Objekte
- Ein erstes einfaches objekt kann zbsp eine Variable sein mit dem Wert "Hallo"
```html
<script type = "text/javascript">
  var auto = "golf";
  document.write(auto.length);
</script>
```
Output: 4
- document ist in diesem fall auch ein Objekt, bei dem wir die funktion write verwenden
- Objekte haben aber typischerweise mehrere properties
- Eine library (bspw. Numpy) ist auch ein Objekt. Dort verwenden wir dann die Funktionen mean, max usw.
```html
<head>
      <script type = "text/javascript">
        // Konstuktorfunktion
        function auto(marke, farbe, ps){
        this.marke = marke; // die Parameter werden mit "this" zugewiesen
        this.farbe = farbe;
        this.ps = ps; 
        }
        // Erstellung einer Instanz eines Objekts
        var golf = new auto ("VW", "blau", 120);
        var einerBmw = new auto ("bmw", "grün", 100);
      </script>
</head>
    <body>
        <script type = "text/javascript">
        document.write(golf.marke);
        document.write(einerBmw.marke);
        </script>
    </body>
```

### Funktionen von Objekten

```html
<head>
      <script type = "text/javascript">
        // Konstuktorfunktion
        function auto(marke, farbe, ps){
        this.marke = marke; // die Parameter werden mit "this" zugewiesen
        this.farbe = farbe;
        this.ps = ps;
        this.geschw = geschw; // hier wird die funktion geschw aufgerufen
        }
        //  Funktion eines Objekts
        function geschw(){
          var maxTempo = (this.ps)*1.5;
          return maxTempo;
        }
        // Erstellung einer Instanz eines Objekts
        var golf = new auto ("VW", "blau", 120);
        var einerBmw = new auto ("bmw", "grün", 100);
      </script>
</head>
    <body>
        <script type = "text/javascript">
        document.write(golf.marke);
        document.write(einerBmw.marke);
        </script>
    </body>
```

### Object initializer
- Sehr ähnlich wie ein Dictionary in Python
- Praktisch wenn man schnell ein Objekt erstellen will, wenn man aber ganz viele objekte erstellen will, ist es besser mit einem Konstruktor zu arbeiten
- Achtung: Ist mit curly boys! `{}`

```html
<head>
      <script type = "text/javascript">
        var golf =  {marke:"VW", farbe:"blau", ps:120};
        var audi = {marke:"audi", farbe:"blau", ps:120, antrieb:"4X4"};
      </script>
</head>
    <body>
        <script type = "text/javascript">
        document.write(golf.marke);
        </script>
    </body>
```

### Math Objekt (Library)
- JS Math
- Hat verschedene Funktionen
  - random() random zahl zwischen 0-1
  - round () zum nächsten integer runden
  - floor() abrunden
  - ceil() aufrunden
  - exp() E^x
  - max(x, y, z, ..., n)
  - min(x, y, z, ..., n)
  - trunc(x)	Returns the integer part of a number (x)

### Date Objekt (Library)
- JS Dates
  - .getHours()
  - .getMinutes()
  - .getSeconds()
  

```html
<head>
</head>
    <body>
        <script type = "text/javascript">
        var datum = new Date();
        var stunde = datum.getHours();
        document.write(datum + " " + stunde);
        </script>
    </body>
```


methode = funktion die zu diesem objekt gehört

## Array
- array in JS ist wie Liste in Python
- ist auch ein Objekt
- auswälen: `array[0]` (beginnt bei 0)

Array erstellen:
```html
<head>
</head>
    <body>
        <script type = "text/javascript">
          var zahlen = new Array(0,1,2,3);
          var namen = new Array("klaus","peter","hans");
          document.write(zahlen[1] + namen[2]); // output = 1hans
        </script>
    </body>
```
Array mit 4 Werten erstellen
- `var array = new Array(4);`
  
Wert einem Item zuordnen
- `namen[1] = "Lars";`

Array erstellen und einfach füllen mit Items

```html
<head>
</head>
    <body>
        <script type = "text/javascript">
          var namen = new Array();
          namen[0] = "Lars";
          namen[1] = "Hans";
          namen[2] = "Peter";
        </script>
    </body>
```

### Array Eigenschaften und Funktionen
- JS Arrays, JS Arrays Methods
- array.lenght
- array.concat() Merging (Concatenating Arrays)
- array.slice()
- array.join() -> Wird  zu einem string?!
- array.push() -> adds a new element to an array (at the end)
- array.reverse() -> reihenfolge umkehren
- array.shift() ->löscht erstes element
- array.unshift("hans") -> adds a new element to an array (at the beginning)
- array.pop() -> removes the last element
  - `var x = new Array(1,2,3)`
  - `var z = x.pop()` (output ist z mit 1,2 )


Beispiel für verbinden:
```html
<head>
</head>
    <body>
        <script type = "text/javascript">
          var z1 = new Array(1,2,3);
          var z2 = new Array(5,6,7);
          z1 = z1.concat(z2);
          document.write(z1);
        </script>
    </body>
```

### array und for loop

```html
<head>
</head>
    <body>
        <script type = "text/javascript">
          var z1 = new Array(8);
          for(i=0;1<z1.length;i++){
            document.write(i+100);
          }      
        </script>
    </body>
```

## Promts
- Es erscheint oben ein kleines Fenster mit einer Zeile für Input
  
```html
<head>
</head>
    <body>
        <script type = "text/javascript">
          promt("Wie heisst du?","");
        </script>
    </body>
```

### Promt und Array
- Die Eingabe kann in einer Liste gespeichert werden
```html
<head>
</head>
    <body>
        <script type = "text/javascript">
          var person = new Array();
          person["Name"] = promt("Wie heisst du?","");
          person["alter"] = promt("Wie alt bist du?,"");
          document.write("Dein Name ist: " + person["Name"] + "und   du bist " + person["alter"] + " alt.")
        </script>
    </body>
```
<div style="page-break-after: always;"></div>

# Termin 8 Python `to do`

## work with strings 
### Einzelne Buchstaben ändern
- String ist wie eine liste
  
Achtung: das geht nicht
```py
string = "Banana"
string[0] = "A"
```

Das geht nur so:
```py
string = "Banana"
new = ''

for i in range(len(string)):
    if i == 0:
        new += 'A'
    else:
        new += string[i]
```

#### Alle Buchstaben die gleich sind ersetzen

```py
string = "Banana"
new=''

for i in string:
    if i == 'a':
      new += '4'
    else:
      new += i

#output = 'B4n4n4'
```

Alle 'a' ersetzen:
```py
i = 'Banana'
i = i.replace('a', '4')
i = i.replace('B','')
# output: '4n4n4
```

## While schleife



## For schleife

- For schleife mit Listen, Dicts und Arrays

```py
liste = ['eins', 'zwei', 'drei']
for i in liste:
  print(i)
```

## range()
- range(start, stop, step)
  - range(3) = range(0,3,1)

## break & continue

### break
- Wenn break erreicht wird, springt aus der schleife raus!

Einfaches Beispiel
```py
for i in range(20)
  if i = 19
    break
  print(i)
```
Beispiel mit While und If
```py
zahl = int(input('Gib Zahl \n'))
gewinnerzahl = 12
spielen = 0
while spielen = 0
  if zahl <10:
    print('fall 1')
  elif zahl == gewinnerzahl:
    print('du hast gewonnen')
    break
  else:
      print('Fall 2')
  weiterspielen = int(input('Weiterspielen? 0/1\n'))
```

### continue
- Ähnlich wie continue aber unterbricht den aktuellen schleifendurchlauf

```py
for i in range(20)
  if i%2==1: #wenn i ungerade ist (teile durch zwei, der rest = 1)
    continue
  print(i)
```

## funktionen
```py
def funktionsname(parameter, parameter):
  code
  code
  code

funktionsname()
```
<div style="page-break-after: always;"></div>

# Termin 9 Lists and dicts

## Sammel-Datentypen

In Python existieren vier Datentypen zum Zusammenfassen von Daten:
- `Lists`
- `Tuples`
- `Sets`
- `Dictionaries`

Wir betrachten vorerst nur `Lists` und `Dictionaries`

## Lists
beginnen mit [], Werte darin heissen Items, sind getrennt mit Komma
Einer Variable kann man eine Liste zuordnen

Spam = ['hallo', 'das', 'er']
-->Dann ist spam[0] --> 'hallo'

Der hinterste/letzte Wert einer Liste kann mit [-1] hervorgerufen werden, der zweitletzte mit [-2]

Index entspricht dem Wert der Liste der genommen werden soll

### Work with lists
```py
# abfragen
liste = [0,1,2]
liste[0] # = 0
liste[1] # = 1
liste[-1] # = 2

# index abfragen
liste.index("item")

# hinzufügen
liste = []
liste = liste + [0]
liste = liste + [1,2]
print(liste)
#output
[0, 1, 2]

# dasselbe mit for-loop und range-funktion
liste=[]
for i in range(3):
    liste = liste + [i]
print(liste)
#output
[0, 1, 2]

#hinzufügen mit append()
spam = ['cat', 'dog', 'bat']
spam.append('moose')
spam
['cat', 'dog', 'bat', 'moose']


#ändern
liste2 = [0, 1, 2]
liste2[0] = 'lars'
print(liste2)
#output
['lars', 1, 2]

#löschen
spam = ['cat', 'bat', 'rat', 'elephant']
spam.remove('bat')
spam
['cat', 'rat', 'elephant']

# löschen mit pop()
liste = ['hans',1,2]
liste.pop()
# output = ['hans',1]
liste.pop(0)
# output = [1]

# Augmented assignment operator mit List
bacon = ['Zophie']
bacon *= 3
bacon
['Zophie', 'Zophie', 'Zophie']

# listen zusammenfügen (schlechte art)
liste = [1,2,3]
liste2 = [4,5,6]
liste += liste2
# output: [1,2,3,4,5,6]

# Listen zusammenfügen (effizient)
liste = [1,2,3]
liste2 = [4,5,6]
liste.extend(liste2)
# output: [1,2,3,4,5,6]
```
### check if item of list is int

```py
for j in liste:
    if isinstance(j, int) == True:
```


### work with strings 
### Einzelne Buchstaben ändern
- String ist wie eine liste
  
Achtung: das geht nicht
```py
string = "Banana"
string[0] = "A"
```

Das geht nur so:
```py
string = "Banana"
new = ''

for i in range(len(string)):
    if i == 0:
        new += 'A'
    else:
        new += string[i]
```

#### Alle Buchstaben die gleich sind ersetzen

```py
string = "Banana"
new=''

for i in string:
    if i == 'a':
      new += '4'
    else:
      new += i

#output = 'B4n4n4'
```

Alle 'a' ersetzen:
```py
i = 'Banana'
i = i.replace('a', '4')
i = i.replace('B','')
# output: '4n4n4'
```
### `range()` and `list()`

range(4) kann vier mal ausgeführt werden: 0 1 2 3

Der return value von `range()` ist ähnlich (?) wie eine Liste
```py
for i in range(4):
	print(i)

#output:
#0
#1
#2
#3

#same output with
for i in [0,1,2,3]
	print(i)
```


### `slice()`
Nimmt mehrere Werte einer Liste, in Form einer neuen Liste.

spam[2] ist eine Liste mit einem Index (ein Integer)
spam[1:4] ist eine Liste mit einem Slice (zwei Integers)

In einem Slice ist der erste Integer der Index bei dem der Slice startet und der zweite Integer wo der Slice endet.

```py
spam = ['null', 'eins', 'zwei', 'drei']
spam[1:3]
['eins', 'zwei']
```
## .sort() und und sorted() für listen
- liste.sort() -> die alte liste wird sortiert und überschrieben
  - nur für listen
- sorted(liste) -> neue liste wird erstellt
  - geht auch für dicts oder strings

Beispiel:
```py
data = [2,3,1,4,5]
data.sort() # output = [1,2,3,4,5]

data2 = sorted(data) #output= [1,2,3,4,5]

# umgekehrte reihenfolge
data.sort(reverse=True)

data2 = sorted(data, reverse = True)
```


### Listen in Listen

Bspw.

```py
liste1 = [['haus', 'schnee'], [5, 12, 13]]
liste1[0] --> ['haus', 'schnee']
liste1[0][1] --> 'schnee'


#Listen zusammenfügen
spam = [1, 2, 3]
spam = spam + ['A', 'B', 'C']

Output:

spam --> [1, 2, 3, 'A', 'B', 'C']

```

## Dictionaries

"Indexes for dictionaries are called keys, and a key with its associated value is called a key-value pair"

Anders als Listen haben Dicts geschweifte Klammern: `{}` 

Boy = {'gender': 'male', 'color': 'blue', 'size': 'small'}

Es gibt kein "erstes" item in einem Dictionary: alle Items sind ungeordnet. Deswegen haben sie einen Key


### Einen neuen key mit Value dem Dict hinzufügen:
```py
dic = {'fruit': 'apple', 'color': 'green'}
dic['price'] = '1'
print(dic)
#output
dic = {'fuit': 'apple', 'color': 'green', 'price' : 1}

#Value drucken
print(dic['fruit'])
#output
apple
```

### Get a Values, Keys or both from an Dict

drei Funktionen `values()`,`keys()`, `items()`

```py


# iterate to get values
spam = {'color': 'red', 'age': 42}
for v in spam.values():
    print(v)
#output
red
42

# iterate to get keys
for k in spam.keys():
    print(k)
#output
color
age

# iterate to get all items
for i in spam.items():
    print(i)
#output
('color', 'red')
('age', 42)

```

### Eine Liste davon bekommen:
```py
spam = {'color': 'red', 'age': 42}
list(spam.keys())
```

Ausgehend davon (wenn mit `list()` umgewandelt) kann man abfragen machen wie:
```py
spam = {'name': 'Zophie', 'age': 7}
'name' in spam.keys()
True
'Zophie' in spam.values()
True
```

### nested Dictionaries

Dict in dict, oder auch liste in dict
```py
# dict in dict
dic1={1:{'fruit': 'apple', 'color': 'green'}, 
	2:{'price': '1', 'taste': 'sweet'}}

# liste in dict
dict2= {1:['das','ist','liste','eins'],
        2:['das','ist','liste','zwei'] }
```

Get Values from nested Dicts
```py
dic1={1:{'fruit': 'apple', 'color': 'green'}, 
	2:{'price': '1', 'taste': 'sweet'}}

print(dict1[1]['color']) # output = green
```

### Dict aus zwei listen erstellen (mit zip())

```py
list1 = list(range(3))
list2 = ['null','eins', 'zwei']

for variable1, variable2 in zip(list2, list1):
    dict[variable1]=variable2

print(dict) 

# oder kurze version
dict2 = {key: val for key, val in zip(list1, list2)}
```




<div style="page-break-after: always;"></div>

# Termin 10
  1.Video: Default werte für funktionen
- Parameter ohne default wert zu erst schreiben

Beispiel 
```py
def f(i,j,n=5)
  return i + j + n

f(1,2) # output = 8
f(1,2,3) # output = 6
```

## Eigene Module machen
- eigenes_modul.py erstellen
- dort eine funktion schreiben
- `import eigenes_modul`
- Diese datei muss indemselben Ordner liegen

## write and read to txt

- Mit dieser Methode braucht es kein Modul
```py
# w = write, r = read, a = append

with open(name, modus) as fileObject:
```
### write
```py
# konkretes beispiel
text = 'Das hier ist Text'
text2 = 'Hier folgt noch mehr Text'

with open('filename.txt', 'w') as f:
  f.write(text + '\n')
  f.write(text2 + '\n')


# daten in txt schreiben
data= [1,2,3,4]
with open('filename.txt', 'w') as f:
  for i in data:
    f.write(str(i)+';')
```

### read

- f.readline() -> erste line einlesen
- f.readlines() -> alle lines einlesen

``` py

with open('zumlesen.txt', 'r') as f:
    text_neu = f.readlines()
print(text_neu)


# mit for loop
with open('zumlesen.txt', 'r') as f:
  for line in f
    text_neu += line
```

##  Dateien mit JSON lesen und schreiben
(video 3 in termin 10)
- java script object notation
- `import json`
- ???

beispiel vom video:
```py

person= ['jan','peter', 'horst']
fach={'jan':['ai','its']
      'peter':['de','en']
      'horst':['ma','fr']}
noten={'jan':[1,2]
      'peter':[3,4]
      'horst':[5,6]}

# wird zu touples gezipt.

person_dict={pers:[(fach,note)for fach, note in
                    zip(präferenz[pers], noten[pers])]
                    for pers in personen}
with open('datei.txt,'w') as f:
  jason.dump(person_dict,f, indent=4, seperators=(','.':'))
```
  