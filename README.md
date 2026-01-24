# 🕵️‍♂️ Fraud-Prediction-Model für Bank- und Versicherungsdaten

## 📌 Abstract

Diese wissenschaftliche Übersicht beschreibt die Konzeption, Methodik und Zielsetzung eines **Fraud-Prediction-Models** zur Identifikation betrügerischer Aktivitäten in Bank- und Versicherungsdatensätzen. Ziel ist die Entwicklung eines numerischen Modells, das bekannte Fraud-Muster aus historischen Daten extrahiert und diese Muster auf neue, unbekannte Datensätze anwendet. Der Ansatz kombiniert **klassisch-analytische Regelmodelle** mit **maschinellen Lernverfahren** (Logistische Regression und Support Vector Machines), um sowohl regelbasierte Verdachtsfälle als auch probabilistische Fraud-Vorhersagen zu ermöglichen.

---

## 🎯 Zielsetzung der Studie

Das primäre Ziel der Studie ist die Entwicklung eines softwaregestützten Analysemodells zur:

* Identifikation **bekannter Fraud-Muster** in strukturierten Transaktions- und Kontodaten 
* Klassifikation neuer Transaktionen als *Fraud*, *Nicht-Fraud* oder *potentieller Fraud* 
* Unterstützung von Nutzern (z. B. Analysten oder Prüfern) durch **Hinweise und Verdachtskennzeichnungen** 

Die Studie ist didaktisch ausgelegt und dient der praktischen Anwendung von in der Vorlesung behandelten Modellen und Algorithmen durch Studierende.

---

## 🗂️ Datenbasis

Die Modellierung basiert auf **heterogenen Datensätzen** aus dem Banken- und Versicherungsumfeld, u. a.:

* Kontodaten (z. B. bekannte Fraud-Konten) 
* Transaktionsdaten (Zeit, Betrag, Empfänger, Herkunft) 
* Schadens- und Versicherungsfalldaten 

Diese Datensätze enthalten sowohl **labelled data** (bekannte Fraud-Fälle) als auch reguläre Transaktionen.

---

## 🔍 Methodischer Ansatz

### 1️⃣ Klassisch-analytischer Ansatz (Rule-Based Fraud Detection)

Der erste Modellierungsansatz folgt einem **deterministischen, regelbasierten Verfahren**:

* Extraktion bekannter Fraud-Parameter (z. B. betrügerische Konten, IBANs, Schadensnummern) 
* Abgleich neuer Transaktionen mit einer **Fraud-Referenzliste** 
* Markierung übereinstimmender Transaktionen als *Verdachtsfall* 

📌 Vorteil:

* Hohe Transparenz 
* Einfach interpretierbar 

⚠️ Nachteil:

* Keine Generalisierung auf neue, unbekannte Fraud-Muster

---

### 2️⃣ Maschinelle Lernverfahren (Predictive Fraud Modeling)

Zur Erweiterung des Modells werden **überwachte Lernverfahren** eingesetzt, die eine **Vorhersagewahrscheinlichkeit für Fraud** liefern.

#### 🔹 Logistische Regression

* Binäres Klassifikationsmodell (Fraud / Nicht-Fraud) 
* Schätzung von Modellparametern über Maximum-Likelihood 
* Gut interpretierbar durch Koeffizienten 

#### 🔹 Support Vector Machine (SVM)

* Trennlinien-basierter Klassifikator 
* Besonders geeignet für hochdimensionale Daten 
* Nutzung von Kernel-Funktionen zur Modellierung nichtlinearer Zusammenhänge 

📌 Beide Modelle werden mit den in der Vorlesung entwickelten Source Codes implementiert und von den Studierenden praktisch angewendet.

---

## ⚙️ Systemarchitektur (konzeptionell)

1. **Datenimport** (Bank- und Versicherungsdaten) 
2. **Feature Engineering** (Extraktion relevanter Fraud-Merkmale) 
3. **Rule-Based Screening** 
4. **ML-basierte Klassifikation** 
5. **Ausgabe von Fraud-Hinweisen** an den Nutzer 

---

## 📊 Evaluation und Anwendung

Die Modelle können anhand klassischer Metriken evaluiert werden:

* Accuracy 
* Precision / Recall 
* ROC-AUC 

Im Rahmen der Klausur sollen die Studierenden:

* Modelle installieren 
* Parameter schätzen 
* Fraud-Wahrscheinlichkeiten interpretieren 

---

## 🧩 Didaktischer Mehrwert

✔ Verbindung von Theorie und Praxis 
✔ Vergleich von regelbasierten und ML-Ansätzen 
✔ Förderung von Modellverständnis und Interpretierbarkeit 

---

## 📚 Referenz

Projekt-Repository und Aufgabenstellung:

🔗 *Fraud-Detection-Model* (GitHub, README.md) 

---

## 🎨 Icons & Favicons (optional)

Für eine spätere Software- oder Web-Integration können folgende Icons genutzt werden:

* 🕵️‍♀️ Fraud Detection 
* ⚠️ Verdachtsfall 
* 📊 Analyse / Statistik 
* 🏦 Bank / 🛡️ Versicherung 

Diese unterstützen die visuelle Nutzerführung und erhöhen die Usability des Systems.

---

Gerne 🙂 Hier ist die **englische Übersetzung** in sachlich-technischem Stil:

---

# Installation on Linux and macOS Operating Systems

---

```
git clone https://github.com/alexej-schelle/TextmailEncryption.git
```

and start the software using the corresponding Python files.

---

# Installation on Windows Operating Systems

---

Download the files from
[https://github.com/alexej-schelle/TextmailEncryption/](https://github.com/alexej-schelle/TextmailEncryption/)
and start the software using the corresponding Python files.

---

# Documentation for Linux, macOS, and Windows Operating Systems

---

```
git clone https://github.com/alexej-schelle/TextmailEncryption/
```

and read `docs/README.txt`.

---

# Documented Application Scenarios

---

Please visit [https://www.iu.org/](https://www.iu.org/) or contact
[alexej.schelle.ext@iu.org](mailto:alexej.schelle.ext@iu.org).

---

# Author

---

* FH Lecturer Dr. A. Schelle

---

---
