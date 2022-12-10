# Hochwasser Challange DIVABRE

## Erster Termin 27.11.2022

### Beschlüsse
* Precipation,  Barmen Wupperverband Hauptverwaltung wird nicht als Feature verwendet. 
    * Begründung: Zu wenig Datenpunkte - Daten zu spät gemessen

* Feature Engineering
     * Generieren von Zusätzlichen Features: 
        * Ableitung - Wie stark sind die Veränderungen der Pegel
    
* Durch die wenigen Datenpunkte zuerst einfache ML Methoden ausprobieren
    * ARIMA/SAMIRA 
    * MLP
    * RNN (Jan)

### Erste Ergebnisse

MLP auf 10 Epochen und einem Hiddenlayer mit RELU liefert 5% bessere Ergebnisse

