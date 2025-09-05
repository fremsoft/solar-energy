# Impianto Solare Ibrido ☀️🔋

Questo repository raccoglie informazioni, schemi e riferimenti sui componenti utilizzati per un impianto solare **ibrido**.  
L’obiettivo è documentare la configurazione e i materiali impiegati, così da avere una base chiara e condivisa per discussioni tecniche o per chi, da professionista, vuole trarne spunti.  

⚠️ **Nota importante:** l’installazione e la messa in servizio devono essere effettuate esclusivamente da un **elettricista abilitato**, che possa rilasciare la dichiarazione di conformità.  
Questo repository ha solo scopo informativo e non sostituisce in alcun modo le normative vigenti o le buone pratiche di sicurezza.  

---

## 📋 Configurazione dell’impianto
- **Pannelli solari:** 2 o 4 moduli da **400W 50V**  
- **Inverter solare ibrido** con gestione rete/batteria  
- **Batteria LiFePO4:** da **50Ah** o **100Ah**  
- **Bypass switch 1-0-2:**  
  - **1:** alimentazione da solare  
  - **0:** disconnessione  
  - **2:** alimentazione da rete esterna  
- **Protezione:** interruttore magnetotermico a valle dell’inverter  
- **Cavi:**  
  - 30 metri, sezione **6 mm²** dai pannelli all’inverter  
  - 1 metro, sezione **25 mm²** dalla batteria all’inverter  

---

## 🛒 Componenti principali
Elenco dei materiali con link di riferimento (Amazon o altri fornitori):  

- [Pannello solare 400W 50V](https://amzn.to/4lXqm2D)  
- [Inverter solare ibrido](https://amzn.to/3VvV1Jy)  
- [Batteria LiFePO4 100Ah](https://amzn.to/4g0OCiU)  
- [Interruttore bypass 1-0-2](https://amzn.to/4mLcBFD) 
- [Scatola](https://amzn.to/4nwYfbZ)
- [Interruttore magnetotermico](https://amzn.to/41v1FU0)  
- [Scatola](https://amzn.to/45LVo8Y)
- [Cavo solare 6 mm² (30m)](https://amzn.to/42bMNKe)  
- [Cavo batteria 25 mm² (1m)](https://amzn.to/4mNqKCb)  
- [Interruttore stacca batteria](https://amzn.to/47WVwUk)
- [Connettori MC4](https://amzn.to/45YmNmL)  

---

## 📑 Schema
Lo schema elettrico è allegato in formato PDF nella cartella `/schema-kicad-9`.  

- [Schema elettrico impianto (formato PDF)](https://github.com/fremsoft/solar-energy/blob/main/schema-kicad-9/schema-impianto.pdf)

---


## 📑 Manuale di istruzioni 
Il manuale di istruzioni del costruttore è allegato in formato PDF qui di seguito, con le opzioni da configurare ben evidenziate:

- [Manuale di istruzioni (formato PDF)](https://github.com/fremsoft/solar-energy/blob/main/Manuale_impianto_solare.pdf)

---

## 📈 Calcolatore punto di pareggio
Se vuoi fare una stima del punto di pareggio del tuo impianto solare, scarica il seguente foglio di calcolo:  

- [Calcolatore punto di pareggio per impianto solare (formato XLSX)](https://github.com/fremsoft/solar-energy/raw/refs/heads/main/Calcolo_Pareggio_Inverter_Solare.xlsx)

