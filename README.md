# Natural-Language-Processing

#Projektname: Natural Language Processing

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Lara-167/Natural-Language-Processing/HEAD)

#Projektbeschreibung: In diesem Projekt werden Yelp Reviews in 1 Stern oder 5 Sterne Kategorien klassifiziert. Datengrundlage bieten Yelp Review Daten von Kaggle.

#Der Datensatz beinhaltet folgende Eigenschaften:

Jede Beobachtung in dem Datensatz ist eine bestimmte Bewertung eines bestimmten Geschäfts durch einen bestimmten Nutzer.

Die "stars" Spalte beinhaltet die Anzahl der Sterne (1 bis 5) die der Bewerter dem Geschäft verliehen hat. In anderne Worten: Die Bewertung des Geschäfts durch den Autor.

Die "cool" Spalte beinhaltet die Anzahl der "Cool"-Votes der Bewertung durch andere Nutzer.

Alle Bewertungen starten mit 0 "Cool"-Votes und es gibt nach oben kein Limit. Je mehr Leute die Bewertung "Cool" finden und sie so voten, desto höhere die Anzahl.

Für die "useful" (dt. nützlich) und "funny" (dt. witzig) Spalten gilt das gleiche.

#Code-Ausführung: 
1. GitHub URL des Repository "Natural-Language-Processing" in https://mybinder.org/ einfügen und launchen
2. Notebook öffnen
3. Code-Zeilen nacheinander ausführen lassen

#Code-Abfolge: 
1. Libraries importieren (nachdem sie vorab durch binder installiert wurden)
2. Daten einlesen aus der Datei Yelp.csv
3. Visualisierungs-Libraries imporieren und mithilfe von seaborn Diagramme erstellen (Explorative Datenanalyse)
5. NLP Klassifizierungsaufgabe, bei der ein neues Data-Frame erstellt wird
6. Train Test Split; Die Daten werden in Test- und Trainingsdaten aufgeteilt
7. Das Modell trainieren
8. Vorhersagen und Auswertung vornehmen mithilfe einer Confusion Matrix und einem Klassifizierungsreports
9. Text Processing verwenden und den TF-IDF Transformer integrieren. Dieser soll die Ergebnisse beeinflussen.
10. Train Test Split; Die Daten werden erneut verarbeitet und das Modell trainiert
11. Vorhersagen und Auswertung vornehmen mithilfe einer Confusion Matrix und einem Klassifizierungsreports


#Projektergebnis: Die Confusion Matrix gibt Aufschluss, wie gut ein Modell Klassen in einem Klassifikationsproblem vorhersagt. Für Kategorie 5 erhalten wir mit 96% eine bessere Modellleistung als für Kategorie 1 mit 78%. Mit dem Einbezug von TF-IDF haben sich die Werte verschlechtert. Statt 96& sind es nun 90% für Kategorie 5.

