# Notebooks für das Buch Machine Learning - kurz &amp; gut

Es gibt zwei Versionen des Buchs:
1. Machine Learning mit **PyTorch** - kurz &amp; gut: https://dpunkt.de/produkt/machine-learning-mit-pytorch-kurz-gut/
2. Machine Learning mit **TensforFlow** - kurz &amp; gut https://dpunkt.de/produkt/machine-learning-kurz-gut-3/

Du kannst dieses Repository entweder clonen und die Notebooks bei dir lokal ausführen oder diese mit den Colab Links direkt auf Google Colab (https://colab.research.google.com/) ausführen:

# *Pytorch* Version

## Abhängigkeiten für lokale Nutzung installieren

Die Notebooks ohne spezielle Nutzung von Pytorch sind im Root-Verzeichnis, die anderen im Verzeichnis ```pytorch```.

1. Eine aktuelle 3.x Python Version installieren
   * https://www.python.org/downloads/
   * Auf den Mac auch mit Homebrew möglich
     1. Anleitung zur Installation von homebrew: https://docs.brew.sh/Homebrew-and-Python
     1. Anleitung zur Installation von Python: https://formulae.brew.sh/formula/python@3.14
1. virtuelles Environment erzeugen: `python3 -m venv .venv`
1. Environment aktivieren `source .venv/bin/activate`
1. Abhängigkeiten installieren `pip install -r pytorch/requirements.txt`


## Direkte Links auf Colab-Notebooks
* Kapitel 2 (Quick-Start): https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap2.ipynb
* Kapitel 3 (Datenimport und -vorbereitung): https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap3.ipynb
* Kapitel 4 (Supervised Learning): https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap4.ipynb
* Kapitel 5 (Feature-Auswahl): https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap5.ipynb
* Kapitel 6 (Modellvalidierung): https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap6.ipynb
* Kapitel 7 (Neuronale Netze und Deep Learning):
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/pytorch/kap7-iris.ipynb
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/pytorch/kap7-cnn.ipynb
* Kapitel 8 (Unsupervised Learning mit Autoencodern): https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/pytorch/kap8.ipynb
* Kapitel 9 (Moderne Sprachmodelle):
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/openai-api-basics.ipynb
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/openai-api-embeddings.ipynb
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/openai-api-function-calling.ipynb
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/pytorch/kap9-bert-tasks.ipynb
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/pytorch/kap9-bert-fine-tuning.ipynb
* Kapitel 10 (MLOps - Machine Learning im Betrieb): 
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/pytorch/kap10-train.ipynb
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/pytorch/kap10-drift.ipynb

# *TensorFlow* Version

## Abhängigkeiten für lokale Nutzung installieren

1. Eine aktuelle 3.x Python Version installieren
   * https://www.python.org/downloads/
   * Auf den Mac auch mit Homebrew möglich
     1. Anleitung zur Installation von homebrew: https://docs.brew.sh/Homebrew-and-Python
     1. Anleitung zur Installation von Python: https://formulae.brew.sh/formula/python@3.14
1. virtuelles Environment erzeugen: `python3 -m venv .venv`
1. Environment aktivieren `source .venv/bin/activate`
1. Abhängigkeiten installieren `pip install -r requirements.txt`
   * Enthält nicht die Abhängigkeiten für Kapitel 9, dies läuft ohne weiteres nur auf Colab

## Direkte Links auf Colab-Notebooks
* Kapitel 2 (Quick-Start): https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap2.ipynb
* Kapitel 3 (Datenimport und -vorbereitung): https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap3.ipynb
* Kapitel 4 (Supervised Learning): https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap4.ipynb
* Kapitel 5 (Feature-Auswahl): https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap5.ipynb
* Kapitel 6 (Modellvalidierung): https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap6.ipynb
* Kapitel 7 (Neuronale Netze und Deep Learning):
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap7-iris.ipynb
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap7-cnn.ipynb
* Kapitel 8 (Unsupervised Learning mit Autoencodern): https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap8.ipynb
* Kapitel 9 (Deep Reinforcement Learning): https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap9.ipynb (funktioniert ohne weiteres nur auf Colab)
* Kapitel 10 (Moderne Sprachmodelle):
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/openai-api.ipynb
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/openai-api-embeddings.ipynb
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/openai-api-function-calling.ipynb
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap10-bert-tasks.ipynb
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap10-bert-fine-tuning.ipynb
* Kapitel 11 (MLOps - Machine Learning im Betrieb): 
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap11-train.ipynb
  * https://colab.research.google.com/github/djcordhose/buch-machine-learning-notebooks/blob/master/kap11-drift.ipynb

## Änderungen zur Auflage 1
* Kapitel 4: Abbruchsbedingungen für SGDRegressor sind in aktuellen Sklearn-Versionen verändert, der Code ist daraufhin angepasst
* Kapitel 7: migriert auf die aktuellste TensorFlow- und Keras-Version
* Kapitel 8: neu in Auflage 2
* Kapitel 9: neu in Auflage 2

## Errata Auflage 2 (bereits korrigiert im ersten Nachdruck)
* Kapitel 6
  * 118: Sensitivity müsste tp / (tp+fn) sein (Dank an Stefan Ollinger)
  * 119 in den Gleichungen: "Mean Squared Error" sollte "Mean Absolute Error" und "Mean Absolute Error" sollte "Median Absolute Error" sein  (Dank an Stefan Ollinger)
* Kapitel 7
  * 138 im Listing unten: Model Parameter "inputs" und "outputs" (Dank an Stefan Ollinger)

## Errata Auflage 2 (bereits korrigiert im zweiten Nachdruck)
* Kapitel 4
  * 77 oben: die Ebenen 4 und 5 werden nicht in der Abbildung 4-29 und 4-30, sondern in 4-30 und 4-31 gezeigt
  * 79 oben: die maximale Anzahl der Ebenen ist hier nicht 5, sondern 2, wie auch richtig im Plot 4-32 dargestellt

## Zusätzliche Erklärungen zu Auflage 2

### Erklärung zu Abbildung 6-1 und 6-2 (bereits hinzugefügt im ersten Nachdruck)

Precision-Recall- und ROC-Kurven sind gute Indikatoren fuer das Potential deines Modells.
Wie du sicherlich schon erkannt hast muss man immer einen Kompromiss zwischen verschiedenen 
Metriken machen, die man optimieren will.
In unserem Beispiel erkauft man sich eine sehr hohe True-Positive-Rate (tpr) auch mit 
einer relativ hohen False-Positiv-Rate (fpr).

Um die entsprechenden Metriken für deine jeweilige Anwendung zu optimieren, solltest du 
zunaechst den Arbeitspunkt (z.B. welchen gewünschten tpr-fpr-Punkt aus der ROC-Kurve) anhand der Performance-Kurven (6-1 und 6-2) definieren.
Dementsprechend kannst du dann den Schwellenwert für den Ausgabe-Score (y_score) deines Modells anpassen.

Sehr praktische Tools dafuer gibt es in z. B. auch in Sklearn:

```
fpr, tpr, thresholds = sklearn.metrics.roc_curve(y_true, y_scores)
precision, recall, thresholds = sklearn.metrics.precision_recall_curve(y_true, y_scores)
```

## Änderungen zur Auflage 2
* Kapitel 10: neu in Auflage 3
* Kapitel 11: neu in Auflage 3


## Errata Auflage 3 (vielen Dank an https://github.com/chandlerNick)
* Kapitel 4
  * 75: "C ist umgekehrt proportional zu \lambda: C ~ 1/\lambda" soll "C ist umgekehrt proportional zu \lambda: C \propto 1/\lambda" sein.
* Kapitel 6
  * 123: In der Tabelle soll "tc    Anzahl der Beispiele mit dem Label `versicolor` und die vom Modell richtig als `versicolor` vorausgesagt wurden." sein.
* Kapitel 7
  * 143: "w_0 + w_1 \cdot x_1 + w_2 \cdot x_2" ist keine mathematische Gleichung sondern ein mathematischer Ausdruck. "w_0 + w_1 \cdot x_1 + w_2 \cdot x_2 = 0" ist eine mathematische Gleichung. 
  * 162: Es soll: "Abbildung 7-14: Verlauf der Accuracy der Trainingsdaten" sein. Jetzt sagt es, "Verlauf der Accuracy der Testdaten".
  * 166: Man soll nicht die Accuracy der Testdaten während Training kalkulieren. Daher ist "Zuerst schauen wir uns die Kurve für die Accuracy der Trainingsdaten in Abbildung 7-16." gemeint. Außerdem soll die Bildunterschrift wahrscheinlich: "Verlauf der Accuracy der Trainingsdaten bei dem kompletten Datensatz" sein.

## Errata Auflage 3 Stand 06-2026
* Kapitel 5
  * Code 106 + 107 oben:
    Dieses Codebeispiel fehlt in der Voraussage im Notebook
    Es ist nun unterhalb der Erzeugung von Abb. 5-10 eingefügt

* Kapitel 6
  * Seite 123, Formel oben:
    unten links muss fn statt fp stehen, also:
    tp fp
    fn tn

* Kapitel 7
  * 143:
    x2 = y, x1 = x, -w1 ∙ w2 = a, -w0 ∙ w2 = b muss heißen:
    x2 = y, x1 = x, -w1 / w2 = a, -w0 / w2 = b
 
    Die angegebenen Koeffizienten müssen durch das Gewicht der zweiten
    Variablen geteilt werden; mit einer Multiplikation ergibt sich nicht
    die behauptete Geradengleichung.

  * 158: Die in der Flatten-Schicht flachgeklopften Bilder haben nach drei Mal MaxPooling die Dimensionen 256 x 8 x 8. 

