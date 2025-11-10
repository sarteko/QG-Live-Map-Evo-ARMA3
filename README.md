# 🗺️ QC-Live Map Evo for Arma 3

### Premessa  
Questo script permette di **visualizzare in tempo reale** su un oggetto 3D (lavagna, laptop, schermo, mappa tattica ecc.) la **posizione e lo stato degli operatori** direttamente in gioco.  
È pensato per missioni con **HQ**, **ricognizione**, **unità undercover** o **gestione medica avanzata (ACE)**.

Il sistema genera un **display dinamico** che aggiorna automaticamente la mappa mostrando:
- Posizioni e direzioni delle unità BLUFOR/CIVILI  
- Stato medico (ferito/incosciente)  (BUG sul sulla perdita di sague)
- Laser target e bersagli designati  
- Informazioni mediche e coordinate precise  

---


📸 Screenshot

![p1](https://github.com/user-attachments/assets/454fc345-eb5a-4dda-8099-1ceb431b9485)

![p2](https://github.com/user-attachments/assets/b3c731c3-5460-4751-914b-1776678aaffa)

![p3](https://github.com/user-attachments/assets/6325b028-4a7a-4c41-beac-cc050d44487d)

<img width="960" height="540" alt="p4" src="https://github.com/user-attachments/assets/10ee907a-6a55-4934-906c-f021f23454c2" />

<img width="1920" height="1080" alt="screen1" src="https://github.com/user-attachments/assets/6265375d-ffc9-496e-b40d-9d4e212815f6" />

<img width="1920" height="1080" alt="screen2" src="https://github.com/user-attachments/assets/da46d231-5a42-44e2-b3ca-121c5e9d3cdf" />


---


## 🧩 Mod richieste

- [CBA_A3](https://steamcommunity.com/workshop/filedetails/?id=450814997)  
- [ACE](https://steamcommunity.com/workshop/filedetails/?id=463939057)  
- [cTab NSWDG Edition](https://steamcommunity.com/sharedfiles/filedetails/?id=2511318948)  
- [BLUFORCE to CIVILIAN for Undercover](https://steamcommunity.com/sharedfiles/filedetails/?id=3595437256)  

---

## ⚙️ Come funziona
 Per poter essere visualizzati sulla mappa live, i player o IA devono avere nell'inventario il tablet della mod cTab ("ItemcTab"), lo script genera una mappa viva sincronizzata con il mondo di gioco.
 È possibile interagire con la mappa tramite il menu a rotella per accedere per spostare la visuale, bloccare la mappa o aggiornarla.
 Le icone delle unità si aggiornano dinamicamente ogni pochi secondi.
 
 
---


##🎛️ Funzionalità principali

Visualizza in tempo reale tutte le unità BLUFOR e CIVILI con:
Indicazione del nome e direzione

Colori dinamici:

🔵 Blu → Unità BLUFOR

🟣 Viola → Unità CIVILI / Undercover

🔴 Rosso/Rosso Lampeggiante → Operatore Ferito/Incosciente

- **Indicazione del nome e direzione** — il nome dell'unità/giocatore viene mostrato e tra parentesi graffe `{}` viene visualizzato l'azimut (la direzione in gradi verso cui guarda il player/IA).  
  > Esempio: `John Doe {270°}
- **Laser designator (croce rossa)**: se un veicolo o unità ha un bersaglio laser attivo, viene visualizzata **una croce rossa pre-attivata** sulla posizione del bersaglio e **sotto alla croce** viene mostrato il **nome della sorgente** (chi sta puntando il laser).
  > Esempio di visuale: croce rossa su posizione bersaglio + sotto la scritta `NomeOperatore` che indica chi sta puntando.
  
- Reload Map → ricarica la texture
- Retry Map Creation → rigenera la mappa


---


💡 Conclusioni

Lo ARTEK Live Map Display System è pensato per missioni tattiche complesse e briefing realistici.
Permette una gestione visiva chiara, aggiornata e interattiva del campo di battaglia.

💬 Se vuoi contribuire con bugfix o idee, sei più che benvenuto!
Ogni miglioramento rende il sistema ancora più immersivo 🚀

📅 Ultimo aggiornamento: 10 Novembre 2025
