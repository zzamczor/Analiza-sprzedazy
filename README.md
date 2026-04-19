# Analiza-sprzedazy-Sklepu
Projekt analizujący dane sprzedażowe różnych produktów, stworzony w języku R.
Celem tej analizy jest identyfikacja segmentu klientów, analiza trendów oraz szukanie zależności pomiędzy danymi w celu optymalizacji działań marketingowych.
 Link do raportu w formacie html: **[Analiza Sprzedaży](http://rpubs.com/Kuba_Zamczyk/1416914)**

Projekt w całości został zrealizowany w **R** i wygenerowany jako raport **R Markdown**.
Wykorzystałem w nim pakiety:
* `dplyr` / `tidyr` (Tidyverse) - czyszczenie, transformacje danych i agregacje (m.in. zmiana formatu za pomocą `pivot_wider`).
* `ggplot2` - zaawansowana wizualizacja danych.
* `lubridate` - praca z formatami dat i wyciąganie trendów miesięcznych.
* `plotly` - dodanie interaktywności do wykresów.

## Główne wnioski
1. **Dominacja kobiet w segmencie Fashion & Beauty:** Kobiety generują znacznie większe przychody w kategoriach Odzież i Kosmetyki, co czyni je głównym targetem dla kampanii promocyjnych w tych działach.
2. **Potencjał w Elektronice:** To jedyna kategoria, w której mężczyźni przewyższają kobiety pod kątem wydatków. Otwiera to pole do działań typu cross-selling.
3. **Analiza Grup Wiekowych:** Od 25 do 40 lat to przedział wieku u osób, które generują najwyższe przychody.
4. **Sezonowość:** Dominującymi miesiącami sprzedaży były luty, maj, październik oraz grudzień, spośród których najbardziej dochodowym był maj.

"Projekt zrealizowany z wykorzystaniem Gemini jako wsparcia programistycznego. Sztuczna inteligencja pomogła mi w szybszym generowaniu składni oraz zrozumieniu dobrych praktyk z dokumentacji, podczas gdy ja skupiłem się na logice analizy danych, architekturze rozwiązania i wyciąganiu wniosków biznesowych."
