# Tehnici de Învățare Automată (TIA) - Laboratoare 🤖

Acest repository conține portofoliul de laboratoare realizate în cadrul cursului de **Tehnici de Învățare Automată**. Proiectele demonstrează aplicarea practică a algoritmilor de Machine Learning, de la preprocesarea datelor până la antrenarea modelelor supervizate și nesupervizate.

## 🛠️ Tehnologii Utilizate

* **Limbaj:** Python 3.x
* **Mediu:** Jupyter Notebook / Google Colab
* **Biblioteci:**
    * `pandas`, `numpy` (Manipulare date)
    * `matplotlib`, `seaborn` (Vizualizare date)
    * `scikit-learn` (Algoritmi ML, Preprocesare, Metrici)
    * `scipy` (Clustering ierarhic)

---

## 📂 Structura Laboratoarelor

### 📘 Laborator 1: Introducere și Preprocesare
* **Obiectiv:** Familiarizarea cu mediul de lucru și analiza exploratorie a datelor.
* **Dataset:** [Ex: Iris / Titanic / Housing]
* **Concepte Cheie:**
    * Manipularea DataFrame-urilor cu Pandas.
    * Vizualizarea distribuțiilor.
    * Implementarea algoritmului **[Ex: k-Nearest Neighbors (k-NN)]**.

### 📗 Laborator 2: Regresie
* **Obiectiv:** Predicția valorilor continue folosind modele de regresie.
* **Algoritmi:**
    * **Regresie Liniară Simplă & Multiplă**.
    * Evaluarea performanței (MSE, RMSE, R2 Score).
* **Rezultate:** Vizualizarea liniei de regresie peste datele reale.

### 📙 Laborator 3: Clasificare 
* **Obiectiv:** Clasificarea datelor în categorii distincte.
* **Algoritmi:**
    * **[Ex: Support Vector Machines (SVM) / Decision Trees]**.
    * Optimizarea hiperparametrilor.
* **Metrici:** Matricea de confuzie, Acuratețe, Precision, Recall.

### 🔴 Laborator 4: Învățare Nesupervizată (Clustering)
În acest laborator am aplicat tehnici de grupare (clustering) pe setul de date **Iris**, fără a folosi etichetele de clasă în timpul antrenării.

* **Analiza Exploratorie (EDA):**
    * Generarea de histograme pentru a analiza distribuția trăsăturilor (Sepal Length, Petal Width etc.) pe specii.
    * Curățarea datelor (eliminarea coloanelor de index inutile).
* **Preprocesare:**
    * Scalarea datelor folosind `StandardScaler` pentru a normaliza valorile (esențial pentru algoritmii bazați pe distanță).
* **Algoritmul K-Means:**
    * Determinarea numărului optim de clustere ($k$) folosind **Metoda Elbow**.
    * Antrenarea modelului pentru $k=3$.
    * Vizualizarea clusterelor și a centroizilor.
* **Clustering Ierarhic:**
    * Generarea **Dendrogramei** folosind metoda `ward` pentru a vizualiza structura ierarhică a grupărilor.

---
