# AI
# Netflix Popularity Prediction

Dieses Repository enthält die Dateien zur Hausarbeit **„Vorhersage der Filmpopularität mithilfe von Machine Learning“**. Ziel des Projekts ist es, anhand ausgewählter Filmmerkmale die Popularität von Filmen mithilfe von Machine-Learning-Modellen vorherzusagen.

## Dateistruktur

```text
.
├── tmdb_5000_movies.csv
├── tmdb_5000_cleaned neu.csv
└── Netflix_Popularity_Prediction 21.06.2026.ipynb
```

## Dateien

### `tmdb_5000_movies.csv`

Dies ist der ursprüngliche Datensatz aus Kaggle. Er enthält die Rohdaten des **TMDB 5000 Movie Dataset** mit verschiedenen Informationen zu Filmen, zum Beispiel Budget, Genres, Popularität, Veröffentlichungsdatum, Umsatz, Laufzeit und Bewertungen.

### `tmdb_5000_cleaned neu.csv`

Dies ist der bereinigte Datensatz, der für die Modellbildung verwendet wurde. In diesem Datensatz wurden unter anderem fehlende oder ungeeignete Werte entfernt, relevante Merkmale ausgewählt und bestimmte Informationen für die Machine-Learning-Modelle aufbereitet.

### `Netflix_Popularity_Prediction.ipynb`

Dies ist die Jupyter-Notebook-Datei mit dem vollständigen Code. Das Notebook enthält die Datenanalyse, die Datenaufbereitung, das Modelltraining, den Deployment-Prototyp sowie die Evaluation der Modelle.

## Verwendete Modelle

Im Projekt werden zwei Regressionsmodelle miteinander verglichen:

* Multiple Lineare Regression
* Random Forest Regressor

## Zielvariable

Die Zielvariable des Projekts ist `popularity`. Sie beschreibt den Popularitätswert eines Films auf Basis des TMDB-Datensatzes.

## Hinweis

Der TMDB-Datensatz dient als öffentlich verfügbare Datengrundlage für den Prototyp. Es handelt sich nicht um interne Netflix-Daten.
