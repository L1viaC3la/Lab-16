Emri: [Vendos Emrin dhe Mbiemrin]
Klasa: 12
Lab 16 — Funksione brenda funksioneve

Ky laborator përmban 4 skripte që demonstrojnë kompozimin e funksioneve:

1. A_bmi.py
   - Funksioni llogarit_bmi thërret valido_pozitiv për të kontrolluar inputet.
   - kategorizo_bmi kategorizon BMI sipas vlerës.
   - Rastet kufi: (68,1.7) → 23.53 'Normal'; (70,0) → Gabim; (50,1.9) → 13.85 'Nën peshë'.

2. B_cmimi_total.py
   - cmimi_total thërret valido_interval, cmimi_me_tatim dhe rumbullakos_dy_shifra.
   - Validimi i tatimit është i domosdoshëm.
   - Rastet kufi: (1000,20,150) → 1350.00; (1000,-5,100) → Gabim; (1000,0,0) → 1000.00.

3. C_nota.py
   - nota_finale përdor pesho_notat dhe etiketa.
   - Validimi bëhet me ne_interval_0_10 për çdo notë.
   - Rastet kufi: (4,4,4) → 4.00 'Dobët'; (9,9,9) → 9.00 'Shkëlqyeshëm'; (-1,5,6) → Gabim.

4. D_teksti.py
   - format_card_title thërret trim dhe normalizo_hapesirat.
   - normalizo_hapesirat përdor një akumulator string pa lista.
   - Rastet kufi: " python lab " → "Python lab"; "" → ""; " a " → "A".
