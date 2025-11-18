# media-queries-crash-cours

Erste Schritte in CSS mit MediaQueries

## Terminal wichtigste Befehle
|Befehl|Bedeutung|
|---|---|
|`dir`, `ls` | Inhaltsverzeichnis anzeigen|
|`cd` | Verzeichnis wechseln|

### GIT
|Befehl|Bedeutung|
|---|---|
|`git clone` | Klont ein Git-Repo|
|`git add`| Alle Dateien ins Repo übernehmen|
|`git commit -m "Text zum Commit"`| Commit erstellen|
|`git push`| Commit ins Remote Repo übernehmen|
|`git pull`| Daten vom Remote Repo ziehen|

## Einführung

```css

@media (Bedingung){
    /* Hier kommen die CSS Anweisungen hin,
        die interpretiert werden,
        wenn die Bedingung erfüllt ist*/
}

```


### Typische Bedingungen

|Bedingung|Bedeutung|
|---|---|
|`max-width`|Stile gelten bis zu dieser Größe|
|`min-width`|Stile gelten ab dieser Größe|
|`orientation`| Bildschirmausrichtung `landscape` oder `portrait` |
|`screen`| Für Bildschirme gültig|
|`print`| Für Drucken gültig|
|`not`| Invertiert die Bedingung|

### Einfaches Beispiel
```html


```

## Aufgaben

### 1. Breakpoints nach Bootstrap

Setze die Breakpoints nach Bootstrap so, um das die jeweilige Bildschirmgröße ausgegeben wird.

### 2. Horizontal, Vertikal

Zeige an, ob der Bildschirm Querformat oder Hochformat ist.

### 3. Ausdrucken

Wenn die Seite ausgedruckt wird, soll der `large`-Inhalte ausgegeben werden und das Aussehen angepasst werden:

- Hintergrund Weiß
- Schriftfarbe Schwarz
- Bilder weg