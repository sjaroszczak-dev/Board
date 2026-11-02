# Dashboard

Strona GitHub Pages (`index.html`):
- **Czasy realizacji** – scatterplot S/M/L, P50/P85/P95, filtrowanie, usuwanie/przywracanie outlierów (>P95), ręczne rekordy (localStorage). Dane: `data/lead_times.xlsx` (kolumny: rozmiar, czas realizacji, data zakończenia) lub wczytanie pliku w UI.
- **Tempo dostarczania (XmR)** – tygodnie od 7 stycznia, dane: `data/Throughput Daily.xlsx` (kolumna daty + kolumna liczby dostarczonych; bez niej liczone są wiersze). X: średnia ± 2,66·śr.MR; MR: śr.MR ± 3,27·śr.MR.

Włącz Pages: Settings → Pages → Deploy from branch → `main` / root.
