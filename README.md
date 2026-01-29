# Analiza Stresu i Stylu Życia Studentów 📊

### 👉 [ZOBACZ PEŁNY RAPORT Z WYKRESAMI I WNIOSKAMI (Kliknij tutaj)](Projekt.md)

---

## 📌 O projekcie
Celem projektu była analiza Exploratory Data Analysis (EDA) oraz weryfikacja hipotez statystycznych dotyczących wpływu nawyków (sen, sport, nauka) na poziom stresu i wyniki w nauce (GPA) studentów.

## 🔍 Kluczowe wnioski
1.  **Sport wymaga wyrzeczeń (Trade-off):** Potwierdzono silną, ujemną korelację między aktywnością fizyczną a czasem snu.
    * *Test Chi-kwadrat:* p < 0.001 (silna zależność między grupami).
    * *Wniosek:* Studenci bardzo aktywni fizycznie śpią statystycznie krócej.
2.  **Nauka a Oceny:** Model regresji liniowej wykazał, że czas nauki wyjaśnia ponad **50% zmienności GPA** ($R^2 \approx 0.54$).
3.  **🚩 Analiza jakości danych (Data Forensics):**
    * Zidentyfikowano nienaturalnie idealne, liniowe trendy spadkowe.
    * Wykryto synchronizację szumu losowego między zmiennymi niezależnymi.
    * **Konkluzja:** Zbiór danych ma najprawdopodobniej charakter **syntetyczny** i został wygenerowany algorytmicznie.

## 🛠 Technologie
* **Język:** R
* **Biblioteki:** `tidyverse`, `ggplot2`, `dplyr`, `psych`, `corrplot`
* **Metody:** Regresja liniowa, Testy t-Studenta, Test $\chi^2$, Korelacja Pearsona.

---
*Autor: Jan Antoni Kawalerski*
