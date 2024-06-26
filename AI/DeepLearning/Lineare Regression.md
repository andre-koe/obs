
### Idee:

Wir ziehen eine Gerade durch unsere Punkte

#### Beispiel: Joggen im Park
- **x-Achse:** Zeit in Stunden
- **y-Achse:** Zurückgelegte Distanz

Versuche auf Basis der Zeit die zurückgelegte Distanz zu schätzen.

### Allgemein

Bei der Linearen Regression geht es darum eine Funktion zu bestimmen, welche den vorliegenden Datensatz möglichst gut beschreibt.

Im Beispiel beim Joggen im Park mit x und y Achse
würden wir eine lineare Funktion vom Typ $f(x) = a x + b y$ 
wählen.

Die Parameter $a$ und $b$ in der obigen Funktion müssen möglichst optimal geschätzt werden, hierfür werden unteranderem folgende Ansätze eingesetzt:

- Least Squares (analytischer Ansatz)
- Gradientenabstiegsverfahren (iterativer Ansatz)

#### Gradientenabstiegsverfahren (Steepest Descent)



### Quadratischer Fehler

$$S = \sum_{i = 1}^n(y_i - \hat{y}_i)^2$$

mit:
- $y_i$ - $y$ Position
- $\hat{y}_i$ - $y$ Position der Vorhersage


