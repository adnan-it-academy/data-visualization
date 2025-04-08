# ❤️ Zadaci za Analizu i Vizualizaciju Podataka — Heart Disease Dataset

Dataset: `heart_disease.csv`  
Biblioteke: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 🔍 Eksploracija i Čišćenje Podataka

1. **Učitaj dataset i prikaži osnovne informacije.**  
   Prikaži broj redova, tipove podataka i broj nedostajućih vrijednosti.

2. **Prikaži prvih 10 redova dataset-a.**  
   Vizuelno procijeni potencijalne probleme u podacima.

3. **Ispitaj broj nedostajućih vrijednosti po kolonama.**  
   Koje kolone najčešće imaju `NaN` vrijednosti?

4. **Očisti kolonu `Fasting Blood Sugar`.**  
   Pronađi i zamijeni sve nedostajuće vrijednosti sa srednjom vrijednošću.

5. **Provjeri i konvertuj sve numeričke kolone u odgovarajući tip.**  
   (Ako treba, obradi i stringove koji izgledaju kao brojevi.)

6. **Koliko je ukupno osoba koje imaju dijabetes?**  
   Prikaži broj osoba po kategoriji u koloni `Diabetes`.

7. **Koliko je osoba sa srčanim oboljenjem (`Heart Disease Status`) koje su također pušači (`Smoking`)?**

---

## 📊 Vizualizacija

8. **Histogram: distribucija godina (`Age`)**  
   Kako su godine raspoređene u ovom skupu podataka?

9. **Bar grafikon: broj osoba sa i bez srčanog oboljenja**  
   Koliko ih ima u obje grupe?

10. **Boxplot: `Cholesterol Level` po `Heart Disease Status`**  
    Postoji li razlika u nivou holesterola između zdravih i bolesnih?

11. **Bar grafikon: `Exercise Habits` po `Heart Disease Status`**  
    Da li fizička aktivnost ima veze sa srčanim oboljenjem?

12. **Boxplot: `BMI` po `Gender`**  
    Kako se indeks tjelesne mase razlikuje među spolovima?

13. **Scatter plot: `Cholesterol Level` vs `Triglyceride Level`**  
    Vizualizuj odnos između ove dvije varijable.

14. **Heatmap: korelacija numeričkih kolona**  
    Prikaži korelaciju između: `Age`, `BMI`, `Blood Pressure`, `CRP Level`, `Triglyceride Level`, `Fasting Blood Sugar`.

15. **Distribucija nivoa stresa (`Stress Level`) kod osoba sa srčanim oboljenjem**  
    Koristi bar grafikon da prikažeš koliko ih je po kategorijama `Low`, `Medium`, `High`.

---

## 📈 Linearna Regresija

16. **Model: Predikcija `CRP Level` na osnovu `BMI`, `Cholesterol Level`, `Age`**  
    Treniraj model koristeći `LinearRegression`.

17. **Evaluacija modela: R² i MSE**  
    Izračunaj performanse regresijskog modela.

18. **Vizualizacija: scatter plot stvarnih vs. predikovanih vrijednosti za `CRP Level`**

19. **Ispitaj koeficijente regresijskog modela**  
    Koje varijable najviše utiču na `CRP Level`?

20. **Model klasifikacije (bonus): Kreiraj binarnu kolonu `Heart_Disease_Binary` (1 ako "Yes", 0 ako "No") i treniraj `LogisticRegression` model da predvidi prisustvo srčanog oboljenja.**