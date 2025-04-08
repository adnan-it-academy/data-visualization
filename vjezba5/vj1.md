# 🎯 Zadaci za Analizu i Vizualizaciju Podataka

Dataset: `freelancer_earnings_bd.csv`  
Alati: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 🔍 Eksploracija i Čišćenje Podataka

1. **Učitaj dataset i prikaži osnovne informacije.**  
   Ispitaj tipove kolona, broj nedostajućih vrijednosti i osnovne statistike.

2. **Provjeri duplikate.**  
   Da li dataset sadrži duplikate? Ako da, ukloni ih.

3. **Istraži `Job_Category`.**  
   Koliko različitih kategorija posla postoji? Prikaži ih uz broj ponavljanja.

4. **Tri najčešće freelancing platforme.**  
   Prikaži tri najzastupljenije platforme po broju unosa.

5. **Distribucija nivoa iskustva.**  
   Prikaži koliko freelancera pripada svakoj kategoriji iskustva (`Beginner`, `Intermediate`, `Expert`) koristeći bar grafikon.

---

## 📊 Vizualizacija Podataka

6. **Prosječne zarade po `Job_Category`.**  
   Napravi bar grafikon sa prosječnim `Earnings_USD` po kategoriji posla.

7. **Boxplot: `Hourly_Rate` po `Experience_Level`.**  
   Prikaži kako se satnica razlikuje među početnicima, srednje iskusnim i ekspertima.

8. **Histogram `Job_Success_Rate`.**  
   Prikaži raspodjelu stope uspješnosti poslova.

9. **Scatter plot: `Marketing_Spend` vs `Earnings_USD`.**  
   Da li postoji povezanost između marketinškog budžeta i zarade?

10. **Korelacija između numeričkih kolona.**  
    Prikaži `heatmap` korelacije između:  
    `Earnings_USD`, `Hourly_Rate`, `Job_Success_Rate`, `Client_Rating`, `Rehire_Rate`, `Marketing_Spend`.

---

## 📈 Grupisanje i Agregacije

11. **Prosječna zarada po nivou iskustva.**  
    Istraži kako se `Earnings_USD` mijenja s iskustvom freelancera.

12. **Ocjene klijenata po `Project_Type`.**  
    Koji tip projekta (`Fixed` ili `Hourly`) ima bolje ocjene?

13. **Trajanje posla po regionima.**  
    Pronađi prosječno `Job_Duration_Days` po `Client_Region`.

14. **Top 5 freelancera po zaradi.**  
    Prikaži freelnacere sa najvišom `Earnings_USD`.

15. **Uporedi prosječnu zaradu po platformama.**  
    Fokusiraj se na `Upwork` i `Fiverr`.

---

## 🤖 Linearna Regresija

16. **Model: `Earnings_USD` ~ `Hourly_Rate`.**  
    Treniraj jednostavan regresijski model.

17. **Model: `Earnings_USD` ~ više ulaza.**  
    Koristi `Hourly_Rate`, `Job_Success_Rate` i `Marketing_Spend`.

18. **Evaluacija modela.**  
    Izračunaj R² vrijednost za oba modela.

19. **Vizualizacija predikcija.**  
    Prikaži scatter plot stvarnih i predikovanih zarada.

20. **Koeficijenti regresije.**  
    Prikaži koje varijable najviše utiču na `Earnings_USD`.