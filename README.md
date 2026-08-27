# 🏨 Hotel Bookings — Anàlisi i visualització de dades

Anàlisi exploratòria i visualització de dades de reserves hoteleres amb l'objectiu d'investigar els factors relacionats amb les cancel·lacions i les diferències entre **City Hotel** i **Resort Hotel**.

🌐 **[Veure l'anàlisi interactiva](https://catimercer.github.io/hotel-bookings-data-analysis/)**

## 🎯 Objectiu

El projecte parteix d'una pregunta principal:

> **Per què el City Hotel cancel·la més que el Resort Hotel?**

A partir d'aquesta pregunta s'analitzen diferents variables relacionades amb les reserves per identificar patrons que puguin ajudar a explicar les diferències en les cancel·lacions entre els dos tipus d'hotel.

## 📊 Dades

El conjunt de dades conté més de **119.000 reserves** corresponents a dos hotels de Portugal, un **City Hotel** i un **Resort Hotel**, entre els anys **2015 i 2017**.

Entre les variables analitzades es troben:

- Estat de cancel·lació de la reserva
- Antelació de la reserva (`lead_time`)
- Preu mitjà diari (`adr`)
- Tipus de dipòsit
- País d'origen dels clients
- Dates i temporalitat de les reserves
- Volum de reserves

## 🔎 Metodologia

El projecte segueix un procés complet d'anàlisi de dades:

1. **Exploració inicial del conjunt de dades**
2. **Neteja i tractament de valors incoherents o absents**
3. **Preparació i transformació de variables**
4. **Anàlisi exploratòria de dades (EDA)**
5. **Anàlisi dels factors relacionats amb les cancel·lacions**
6. **Creació de visualitzacions interactives**
7. **Storytelling i interpretació dels resultats**

## 📈 Visualitzacions

Per explorar les dades s'han desenvolupat diferents visualitzacions, entre elles:

- Comparació de les cancel·lacions entre els dos hotels
- Cancel·lacions segons el tipus de dipòsit
- Evolució temporal de les reserves i cancel·lacions
- Mapa interactiu segons el país d'origen
- Bubble chart relacionant antelació, ADR, volum de reserves i cancel·lacions
- Heatmap de cancel·lacions segons l'antelació i el tipus d'hotel

Les visualitzacions interactives permeten explorar els patrons de les dades de manera més intuïtiva.

## 💡 Principals conclusions

L'anàlisi mostra que les cancel·lacions no depenen d'un únic factor, sinó de la combinació de diferents variables.

Entre els patrons observats destaquen:

- Diferències significatives en el comportament de les cancel·lacions entre **City Hotel** i **Resort Hotel**.
- L'**antelació de la reserva** presenta una relació important amb la probabilitat de cancel·lació, especialment al City Hotel.
- Variables com el **preu**, el **tipus de dipòsit** i el **país d'origen** també permeten identificar patrons diferenciats de cancel·lació.

Aquests resultats mostren la utilitat de l'anàlisi exploratòria i la visualització de dades per detectar patrons de comportament en les reserves hoteleres.

## 🛠️ Tecnologies utilitzades

- **R**
- **R Markdown**
- **ggplot2**
- **Plotly**
- **dplyr**
- **HTML**
- **GitHub Pages**

## 📁 Estructura del repositori

- `exploratory_analysis.Rmd` — neteja, preparació de les dades i anàlisi exploratòria.
- `hotel_bookings_storytelling.Rmd` — codi font de l'anàlisi visual i storytelling.
- `index.html` — informe interactiu publicat mitjançant GitHub Pages.
- `hotel_bookings.csv` — conjunt de dades utilitzat.
- `README.md` — documentació del projecte.

---

📌 Projecte desenvolupat com a part del **Màster Universitari en Ciència de Dades de la Universitat Oberta de Catalunya (UOC)**.
