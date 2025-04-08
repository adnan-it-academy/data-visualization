# ☕ Zadaci za Analizu i Vizualizaciju Podataka — Cafe Sales Dataset

Dataset: `dirty_cafe_sales.csv`  
Biblioteke: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 🔍 Eksploracija i Čišćenje Podataka

1. **Učitaj dataset i prikaži osnovne informacije.**  
   Ispitaj broj redova, tipove podataka i broj nedostajućih vrijednosti.

2. **Prikaži prvih 10 redova.**  
   Vizuelno procijeni koje kolone izgledaju "prljavo" (npr. tekst umjesto brojeva, greške itd.).

3. **Očisti kolonu `Total Spent`.**  
   Zamijeni sve vrijednosti `"ERROR"` sa `NaN`, a zatim prebaci kolonu u numerički tip.

4. **Konvertuj `Quantity` i `Price Per Unit` u numeričke vrijednosti.**  
   Očisti sve nedosljednosti (npr. stringovi, prazna polja, itd.).

5. **Ispuni nedostajuće vrijednosti u `Payment Method`.**  
   Najprije prikaži broj nedostajućih vrijednosti, pa zamijeni `NaN` sa `"Unknown"`.

6. **Prikaži sve unikatne vrijednosti u `Location`.**  
   Identificiraj sumnjive ili nepravilne vrijednosti (npr. `"UNKNOWN"`) i odluči šta da radiš s njima.

7. **Konvertuj kolonu `Transaction Date` u datetime tip.**  
   I prikaži najraniji i najkasniji datum transakcije.

---

## 📊 Vizualizacija i Statistički Uvidi

8. **Histogram: `Total Spent`**  
   Prikaži distribuciju potrošnje po transakciji.

9. **Boxplot: `Total Spent` po `Payment Method`**  
   Koji način plaćanja ima najviše potrošnje?

10. **Bar grafikon: broj prodatih artikala (`Item`)**  
    Koji artikli su najprodavaniji?

11. **Heatmap: korelacija između `Quantity`, `Price Per Unit` i `Total Spent`**  
    Prvo osiguraj da su sve tri kolone numeričke i bez `NaN`.

12. **Vrijeme i prodaja**  
    Prikaži trend prosječne `Total Spent` po mjesecima koristeći `Transaction Date`.

13. **Analiza dana u sedmici**  
    Prikaži koji dani (ponedjeljak - nedjelja) imaju najviše transakcija.

14. **Bar grafikon: `Payment Method` frekvencija**  
    Vizualizuj koliko često se koristi svaka metoda plaćanja.

15. **Uporedna analiza `In-store` i `Takeaway`**  
    Koji način prodaje ima više prometa (suma `Total Spent`)?

---

## 📈 Linearna Regresija

16. **Priprema podataka za model**  
    Izdvoji `Quantity` i `Price Per Unit` kao ulazne varijable, a `Total Spent` kao ciljnu varijablu.

17. **Treniraj model linearne regresije**  
    Predikcija `Total Spent` na osnovu `Quantity` i `Price Per Unit`.

18. **Evaluacija modela**  
    Izračunaj `R²` i `Mean Squared Error` modela.

19. **Vizualizuj stvarne i predikovane vrijednosti**  
    Scatter plot: stvarne vs. predikcije za `Total Spent`.

20. **Ispitaj koeficijente regresije**  
    Koja varijabla ima veći uticaj na ukupnu potrošnju?