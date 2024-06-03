# Lehrertagung "Praktisches Maschinelles Lernen am Beispiel des Gradientenverfahrens"
Dies ist ein Repository für eine Lehrertagung, bei der praktisches maschinelles Lernen am Beispiel des Gradientenabstiegsverfahrens gezeigt wird.

## Requirements
- Python 3.11
- numpy
- matplotlib
- jupyter
- notebook

## Installation
Zuerst benötigt ihr eine Python-Installation, die ihr per Kommandozeile benutzen könnt. Mit `python --version` in der Kommandozeile könnt ihr testen, ob das klappt. Falls als Resultat `Python 3.11.X` oder eine neuere Version angezeigt wird, dann ist alles in Ordnung. Falls ihr eine ältere Version habt, sollte es zwar auch funktionieren, es könnten jedoch unerwartete Probleme auftreten. Daher empfehle ich, eine aktuelle Version zu installieren. Den passenden Python-Installer für euer System findet ihr hier: [https://www.python.org/downloads/].

Dieser Schritt kann übersprungen werden: Ich würde an dieser Stelle empfehlen ein Virtualenvironment aufzusetzen mit `python -m venv LTGD`, LTGD für diese Lehrertagung mit GradientDescent. Nun wechselt ihr in dieses environment bzw aktiviert es mit `LTGD\Scripts\activate` auf Windows oder `source LTGD/bin/activate` auf macOS und Linux. Hiernach sollte vor eurer Kommandozeile `(LTGD)` stehen.

Nachdem ihr Python auf eurem System per Kommandozeile benutzen könnt, benötigt ihr die oben genannten Pakete. Mit python -m pip freeze könnt ihr euch eine Liste der bereits installierten Pakete anzeigen lassen und überprüfen, ob ihr schon alle benötigten Pakete habt. Alternativ könnt ihr sie einfach installieren mit `python -m pip install numpy matplotlib jupyter notebook`. Jetzt sollten alle benötigten Pakete installiert sein.

## Quickstart
Mit dem Befehl `python -m jupyter notebook` startet ihr lokal einen Jupyter Notebook-Server. Außerdem sollte automatisch euer favorisierter Browser gestartet werden. Navigiert nun in dem im Browser geöffneten Fenster zu der Datei `Teacher.ipynb`, oder ladet sie herunter falls dies noch nicht geschehen ist, und öffnet sie. Jetzt könnt ihr loslegen.
