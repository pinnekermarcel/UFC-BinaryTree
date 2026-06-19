# UFC-BinaryTree
UFC Binary Decision Tree
Dieses Projekt erstellt einen Entscheidungsbaum-Klassifikator, der vorhersagt, ob ein UFC-Fighter einen positiven Kampfrekord hat (mehr Siege als Niederlagen).
Der Workflow basiert auf einem öffentlichen Datensatz von Kaggle und wurde in Google Colab umgesetzt.

Inhalt
Laden und Anzeigen des UFC-Datensatzes

Erstellen einer Zielvariable (is_positive_record)

Auswahl relevanter Features

Datenbereinigung

Train/Test-Split

Training eines DecisionTreeClassifier

Visualisierung des Entscheidungsbaums

Berechnung der Modellgenauigkeit

Ziel des Projekts
Das Ziel ist es, einen einfachen, interpretierbaren Machine-Learning-Ansatz zu zeigen, der anhand von Basisstatistiken eines Fighters eine Klassifikation trifft.
Der Fokus liegt auf Verständlichkeit, Reproduzierbarkeit und einem klaren ML-Workflow.

Verwendete Features
wins

losses

draws

height_cm

weight_in_kg

Zielvariable:

is_positive_record (1 = mehr Siege als Niederlagen)

Technologien
Python

Pandas

NumPy

Scikit-Learn

Matplotlib

Google Colab

Datensatz
UFC Fighters’ Statistics Dataset
Quelle: https://www.kaggle.com/datasets/asaniczka/ufc-fighters-statistics
