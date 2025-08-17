# 💧 Water Consumption Forecasting

Projekt w Pythonie i Jupyter Notebook dotyczący **prognozowania zużycia wody** na podstawie danych historycznych.  
Repozytorium zawiera kompletny pipeline analizy danych, trenowania modeli ML oraz generowania raportów.  

---

## 📂 Zawartość repozytorium
- `water-consumption-forecast.ipynb` — główny notebook z implementacją (sekcje 1–13)  
- `data.csv` — dane historyczne o zużyciu wody (20 krajów)  
- `requirements.txt` — lista bibliotek potrzebnych do uruchomienia projektu  
- `/reports` — przykładowe raporty i wizualizacje generowane automatycznie  
- wykresy i pliki wynikowe (`confusion_matrix.png`, `reg*_actual_vs_pred.png`)  

---

## 🧩 Sekcje notebooka
1. **Importy i konfiguracja środowiska** – ładowanie bibliotek, ustawienia globalne.  
2. **Wczytanie i wstępna analiza danych** – ładowanie `data.csv`, sprawdzenie braków i struktury.  
3. **Czyszczenie i przygotowanie danych** – normalizacja nazw, brakujące wartości, typy kolumn.  
4. **Eksploracyjna analiza danych (EDA)** – wizualizacje trendów, rozkładów i korelacji.  
5. **Przygotowanie cech i etykiet** – budowa zbiorów treningowych i testowych.  
6. **Model klasyfikacyjny** – predykcja poziomu deficytu wody (Low / Moderate / High).  
7. **Utils (strict mode)** – pomocnicze funkcje do wyboru krajów tylko z listy CSV.  
8. **Widżety interaktywne** – wybór kraju/roku/horyzontu prognozy w notebooku.  
9. **Model regresyjny (zużycie całkowite)** – przewidywanie wartości liczbowych.  
10. **Model regresyjny (zużycie per capita)** – prognoza na osobę.  
11. **Ocena i walidacja modeli** – metryki, macierz pomyłek, raporty klasyfikacji.  
12. **Generowanie raportów** – eksport wyników do CSV, HTML i PNG.  
13. **Podsumowanie i wnioski** – kluczowe obserwacje, wnioski końcowe.  

---

## 🚀 Uruchomienie projektu

### 1. Klonowanie repozytorium
```bash
git clone https://github.com/Marksio90/water-consumption-forecast.git
cd water-consumption-forecast
