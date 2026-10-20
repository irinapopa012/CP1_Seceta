# Data Cards - CP1 (Seceta: satelit vs. meteo)

## 1. Sursa Satelit: MODIS NDVI
* **Proveniență:** MOD13Q1.061 Terra Vegetation Indices (Google Earth Engine).
* **Perioadă:** 2001 - 2022.
* **Rezoluție spațială:** 250 m (agregat la nivel de județ folosind masca de teren arabil CORINE).
* **Rezoluție temporală:** 16 zile (agregat lunar).
* **Unități:** Indice de vegetație normalizat (-1 la 1), scalat nativ cu 0.0001, transformat prin standardizare Z-score.
* **Goluri / Lipsuri:** Erorile cauzate de nori și aerosoli sunt filtrate (mascate) folosind banda de calitate `SummaryQA`.
* **Licență:** Open Data (NASA LP DAAC).

## 2. Sursa Meteo/Climă: SPEIbase
* **Proveniență:** SPEIbase v2.10 (Global Drought Monitor).
* **Perioadă:** 2001 - 2022.
* **Rezoluție spațială:** 0.5 grade (~55 km) (agregat ponderat la nivel de UAT județ).
* **Rezoluție temporală:** Lunar.
* **Unități:** Anomalie climatică standardizată (deviații standard față de medie).
* **Goluri / Lipsuri:** Set de date continuu, nu prezintă goluri spațio-temporale majore pentru regiunea României.
* **Licență:** Open Data pentru cercetare.

## 3. Sursa Statistică: INS Tempo
* **Proveniență:** Institutul Național de Statistică, tabelul AGR110A (Producția agricolă vegetală).
* **Perioadă:** 2001 - 2022.
* **Rezoluție spațială:** Nivel administrativ județean (UAT județ).
* **Rezoluție temporală:** Anual.
* **Unități:** Randament agricol (kg/hectar), transformat prin standardizare Z-score.
* **Goluri / Lipsuri:** Posibile valori lipsă în anii cu raportări incomplete; datele anuale sunt replicate/difuzate pe lunile de sezon agricol (aprilie-septembrie).
* **Licență:** Open Data (Guvernul României).
