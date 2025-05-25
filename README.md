# Maxwell-Boltzmann-Dateien – Experimentelle Geschwindigkeit von Kugeln

Dieses Repository enthält fünf Datensätze aus einem Experiment zur Untersuchung der Maxwell-Boltzmann-Geschwindigkeitsverteilung bei unterschiedlichen Spannungen und Kugelmaterialien.

## 📁 Dateien

| Datei              | Beschreibung                                 |
|--------------------|----------------------------------------------|
| holz 6v.csv         | Holzkugel bei 6 V Rüttelspannung             |
| Holz 8v.csv         | Holzkugel bei 8 V Rüttelspannung             |
| Holz 10v.csv        | Holzkugel bei 10 V Rüttelspannung            |
| Glas 6v.csv         | Glaskugel bei 6 V Rüttelspannung             |
| Kunststoff 6v.csv   | Kunststoffkugel bei 6 V Rüttelspannung       |

## 📊 Inhalt der CSV-Dateien

Die Dateien enthalten experimentell bestimmte Geschwindigkeiten in zwei Dimensionen:

- `t`: Zeitstempel (ms oder s)
- `v_x`: Geschwindigkeit in x-Richtung (m/s)
- `v_y`: Geschwindigkeit in y-Richtung (m/s)

Die Gesamtgeschwindigkeit kann durch:

```python
v = np.sqrt(v_x**2 + v_y**2)
