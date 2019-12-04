# klassifizierung-news-artikel
Text-Klassifizierung ist eine Standard-Anwendung von ML. Hier zeige ich beispielhaft solch eine Klassifizierung anhand von Nachrichten-Meldung in deutscher Sprache.
Als Datenquelle kommt der "10k German News Articles Dataset (10kGNAD)" zum Einsatz. Entnommen wurde er von Kaggle: https://www.kaggle.com/tblock/10kgnad
Die vorgefertigte Aufteilung in Trainings- und Testdaten wurde rückgängig gemacht und selbst neu angefertigt.
Für die Auswertung kam Tensorboard zum Einsatz. Mit diesem Tool kann der Verlauf des Lernprozesses sehr schön visualisiert werden. Dafür muss Tensorboard installiert sein (pip install Tensorboard)
