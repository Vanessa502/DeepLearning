# Vorhersage solarer Flares mittels Deep-Learning-Architekturen

**Ein Vergleich von LSTM, GRU und Transformer**

> Master-Projekt zum Modul *Deep Learning* im Wintersemester 2025/2026

---

## Projektstruktur

```
├── Data/
│   ├── daily_geomagnetic_data.csv
│   └── daily_solar_data.csv
├── Notebooks/
│   └── SolarFlarePredictionFinal.ipynb
├── requirements.txt
└── README.md
```

## Erste Schritte

1. **Virtuelle Umgebung anlegen**
   ```bash
   python -m venv venv
   ```

2. **Umgebung aktivieren**
   ```bash
   # Windows
   venv\Scripts\activate

   # macOS / Linux
   source venv/bin/activate
   ```

3. **Abhängigkeiten installieren**
   ```bash
   pip install -r requirements.txt
   ```

4. **Notebook starten** und den entsprechenden Kernel (`venv`) auswählen.