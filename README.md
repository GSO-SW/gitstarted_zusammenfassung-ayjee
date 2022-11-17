# gitStarted Zusammenfassung
In diesem Repo soll zusammengefasst werden, was man für die Arbeit mit git und gitHub kennen sollte.
- In [diesem cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) finden Sie Hinweise, wie man .md-Dateien formatiert.
- Mit diesen [Generator](https://www.tablesgenerator.com/markdown_tables) können Sie Tabellen für Markdown erzeugen

:dart: Ziele:
1. Die Arbeit soll nicht im Browser stattfinden. Clonen Sie das Repo und arbeiten Sie lokal.
1. Hier gehts um Teamwork: Ich erwarte häufige Commits (+ häufiges pushen/pullen )

## TODO
- Begriffe definieren und erklären (z.B. repository, branch etc.)






- git Befehle für die Arbeit mit lokalen Repositories (inkl. Erläuterungen)

git config --global user.name  (Namen angeben)  

git config --global user.email  (email angeben)

git init (erstellt die Responsry)

git add (fügt eine datei hinzu)

git commit -m "Titel" (erfasst ein Dateistand und speichert diesen )

git Branch (Ein Unabhängiger Entwicklungszweig )

git log (Zeigt alle commits des Projektsverlauf) 

git status (gibt den Status des Arbeitsverzeichnisses zurück)

git merge (Setzt zwei oder mehrere commits zusammen)

git cherry pick (eizelne commits einer Referenz auswählen und bei Head anhängen )

git rebase (Verschieben ofer Kombinieren einer Squenz von Commits zu einem Basis Commit ) 

git checkout ( Das Wechseln zwischen Branches oder auf ältere Commits zugreiffen)

git clone (Kopiert vom Webserver die Git datei auf den Lokalen Ordner )

git push (Schiebt bearbeitete oder hinzugefügte dateien auf den Webserver wo nun jeder den neusten Stand sieht)

git fetch (Holt veränderte dateien auf den Lokalen Ordner)

git pull (Holt veränderte dateien auf den Lokalen Ordner + Mergt diese )








- git Befehle für die Arbeit mit entfernten Repositories (inkl. Erläuterungen)

   Es gibt drei Befehle :
   
   git fetch 
   
   git merge 
   
   git pull 



## TODO2
- Fachbegriffe OOP erklären (mit Beispielen)

  - abstract (Klassen) 
Als Abstrakte Klasse wird eine Klasse bezeichnet, von der keine Objekte erzeugt werden können

  - abstract (Methoden)
Abstrakte Methoden legen lediglich die Signatur der Methode fest, ohne sie zu implementieren

  - virtual
Kinderklassen können methoden überschreiben müssen aber nicht

  - override
methoden aus  mutterklassen müssen überschrieben werden

  - Polymorphie
Bedeutet z.B. das eine Liste objekte mehrerer Klassen verwalten kann

- Wie überschreibt man die Methode `virtual string ToString()`?

mit: Override string ToString(){}; 

