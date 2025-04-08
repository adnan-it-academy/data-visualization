# 🛒 Zadaci za Analizu i Vizualizaciju Podataka — Customer Purchasing Behaviors

Dataset: `Customer Purchasing Behaviors.csv`  
Biblioteke: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 🔍 Eksploracija i Osnovna Statistika

1. **Učitaj dataset i prikaži osnovne informacije.**  
   Ispitaj broj redova i kolona, tipove podataka i eventualne nedostajuće vrijednosti.

2. **Prikaži prvih 10 redova dataset-a.**  
   Vizuelno provjeri ima li nelogičnosti u podacima.

3. **Ispitaj raspodjelu korisnika po regijama (`region`).**  
   Prikaži broj korisnika iz svake regije.

4. **Kolika je prosječna godišnja zarada (`annual_income`) korisnika?**  
   Prikaži i medijanu.

5. **Koliki je prosječan broj kupovina godišnje (`purchase_frequency`)?**  
   Uporedi između regija.

6. **Koje su minimalne i maksimalne vrijednosti za `purchase_amount` i `loyalty_score`?**

7. **Koliki je prosječan `purchase_amount` za korisnike starije od 40 godina?**

---

## 📊 Vizualizacija

8. **Histogram: distribucija `age` korisnika**  
   Prikaži raspodjelu godina korisnika.

9. **Bar grafikon: broj korisnika po regijama (`region`)**

10. **Boxplot: `purchase_amount` po regijama**  
    Postoje li razlike među regijama?

11. **Scatter plot: `annual_income` vs `purchase_amount`**  
    Vizualizuj moguću povezanost.

12. **Boxplot: `loyalty_score` po regijama**

13. **Heatmap: korelacija između numeričkih varijabli**  
    (`age`, `annual_income`, `purchase_amount`, `loyalty_score`, `purchase_frequency`)

14. **Distribucija `purchase_frequency` po regijama**  
    Prikaži boxplot.

15. **Vizualizuj odnos između `age` i `loyalty_score` koristeći scatter plot**

---

## 📈 Linearna Regresija

16. **Treniraj regresijski model za predikciju `purchase_amount`**  
    Ulazi: `annual_income`, `loyalty_score`, `purchase_frequency`

17. **Evaluacija modela**  
    Izračunaj `R²` i `Mean Squared Error`.

18. **Vizualizuj stvarne vs. predikovane vrijednosti `purchase_amount`**

19. **Prikaži koeficijente regresije**  
    Koja varijabla ima najveći uticaj?

20. **Bonus zadatak: napravi novi feature `income_per_purchase`**  
    Definiši ga kao `annual_income / purchase_frequency`.  
    Vizualizuj njegov odnos sa `purchase_amount`.