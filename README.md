Weil ich es im Markdown als **Codeblock** formatiert habe (die drei Backticks ``` am Anfang/Ende). Wenn du beim Kopieren **nicht alles** erwischst oder GitHub den Block nicht sauber übernimmt, wirkt es so, als ob „nach der Tabelle nichts mehr“ kommt – dabei liegt der Rest dann oft **ausserhalb** des Codeblocks oder wird „verschluckt“.

Hier ist die README **ohne** den äusseren Codeblock, damit GitHub sie sicher korrekt rendert:

# Der Mathe-Notausgang (log-Sandbox)

Willkommen in deinem persönlichen Log-Breaker Platinum.
Hier ist die Anleitung, wie du das „Gedöns“ in die Sandbox eintippst, damit der Händchenmodus dich retten kann.

## Die goldene Regel

**Klammern retten Leben.**
Im Zweifel: **Mach eine Klammer mehr.**

* **Falsch:** `log(x^2n)` (Der Computer denkt: (x^2) mal (n))
* **Richtig:** `log(x^(2n))` (Der Computer checkt: Alles da oben gehört zusammen)

## Befehls-Liste (Cheat Sheet)

Hier ist die Übersetzung von „Mathe-Buch“ zu „Tastatur“:

| Was du willst       | Was du tippst | Erklärung                                                           |
| ------------------- | ------------- | ------------------------------------------------------------------- |
| Logarithmus         | `log(x)`      | Egal welche Basis ((log_a), (log_{10}) ...). Tipp einfach `log`.    |
| Natürlicher Log     | `ln(x)`       | Für die Aufgaben mit (e).                                           |
| Mal rechnen         | `*`           | **WICHTIG:** Schreib immer den Stern! `2*x` statt `2x`.             |
| Geteilt / Bruch     | `/`           | `x/y` macht einen Bruch daraus.                                     |
| Hochzahl (Rucksack) | `^`           | Das Dach-Zeichen (links neben der 1). Beispiel: `x^2`               |
| Wurzel (Quadrat)    | `sqrt(x)`     | „Square Root“. Der Simulator macht daraus (\sqrt{x}).               |
| Dritte Wurzel       | `x^(1/3)`     | Profi-Trick: Keine Taste für (\sqrt[3]{}), also „hoch ein Drittel“. |
| Der Turm            | `a^(log(x))`  | Wenn die Basis unten und im Log gleich sind.                        |

## Copy & Paste Beispiele (Level 1 bis Boss)

### Level 1: Der Rucksack

```text
2*log(x)
```

(Die 2 steht davor und will reinspringen)

### Level 2: Produkte & Brüche

```text
log(a * b / c)
```

(Alles gemischt. Der Simulator sortiert das)

### Level 3: Die Wurzel-Tarnung

```text
log(sqrt(x))
```

(Klick die Wurzel an, um sie in 1/2 zu verwandeln)

### Level 4: Fiese Hochzahlen

```text
log(x^(2n))
```

(Wichtig: Klammer um das `2n` nicht vergessen!)

### Level 5: Der Endgegner (Aufgabe 3c)

```text
1/2 * log(x^(2n)) + (n+2) * log(x)
```

(Sieht übel aus, aber der Simulator frisst das)

### Level 6: Der Turm (Alles löst sich auf)

```text
a^(log_a(x^2 * y))
```

(Beobachte, wie das Dachgeschoss einstürzt)

## Tipps für den Notfall

### 1) „Er macht nichts?“

Checke, ob du Leerzeichen drin hast, die da nicht hingehören, oder ob du eine Klammer `)` vergessen hast.

### 2) „log_2 oder log_a?“

Dem Simulator ist die kleine Zahl unten egal. Du kannst `log_a(x)` tippen oder einfach `log(x)`. Er ignoriert den Unterstrich und konzentriert sich auf die Logik.

### 3) Wurzel-Hack

Merk dir: **Wurzel ist Rucksack.**

* (\sqrt{x} \rightarrow) Tippe `x^(1/2)`
* (\sqrt[3]{x} \rightarrow) Tippe `x^(1/3)`
* (\sqrt[4]{x} \rightarrow) Tippe `x^(1/4)`

Viel Erfolg beim Klicken!
