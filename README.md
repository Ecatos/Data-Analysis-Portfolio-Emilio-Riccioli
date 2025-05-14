# Portfolio Emilio Riccioli

## Istruzioni
### Per visualizzare i progetti su GitHub fare click direttamente sui file .ipynb nel box qui sopra

### NB: Le celle di codice possono essere eseguite solamente su Google Colab, il reindirizzamento è possibile:
  - facendo click sui link forniti sotto (Lista progetti) 
  - facendo click sul seguente bottone nei file su GitHub ![image](https://github.com/user-attachments/assets/8ff9816e-5aba-400d-9b7e-a722ed91509f)
  
## Lista progetti
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)

---

### 1. Analisi KPI azienda Retail con Power BI e DAX
Questo progetto simula la creazione di un report interattivo per visualizzare e monitorare le performance aziendali

-#### Trasformazione dei Dati
Utilizzo di Power Query per importare, pulire e trasformare i dati grezzi prima di caricarli nel modello dati

-#### Creazione del Data Model
Costruzione di un modello dati relazionale che rappresenta la struttura dei dati aziendali

-#### Calcolo dei KPI con DAX
Definizione di calcoli e misure Dax per analizzare i Kpi come vendite totali, profitto e margini

-####Sviluppo del Report Power BI
Creazione di un report interattivo con grafici, tabelle e altri elementi visivi in Power BI Desktop

-#### Personalizzazione dell'UI: 
Aggiunta di filtri, segmentazioni dati e altri elementi per rendere l'interfaccia utente del report più intuitiva

PER INSERIRE UN IMMAGINE BASTA TRASCINARLA DA FILE WINDOWS QUI DENTRO oppure DIRETTAMENTE CTRL-C + CTRL-V:
![1](https://github.com/user-attachments/assets/00cdb764-b082-4978-a19c-a044b8e9fb11)


### Data Cleaning
In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection
2. Handling missing values
3. Data cleaning and formatting

### Data Analysis
Include some interesting code/features worked with

```sql
SELECT * FROM table1
WHERE cond = 2;
```

💻
🖱️
![image](https://github.com/user-attachments/assets/a383db4a-084b-49d4-b39e-06e2a384066e)

per andare a capo di una riga col contenuto lasciare una riga vuota in mezzo:
💻

🖱️



|Heading1|Heading2|
|--------|--------|
|Content|Content2|
|Python|SQL|
|6/10|8/10|

`Column1`

**GRASSETTO**
*Corsivo*


```sql
```

```sql
UODATE HR
SET birthdate = CASE
  WHEN birthdate LIKE '%/%' THEN date_format(str_to_date(birthdate, '%m/%d/%Y'), '%Y-%m-%d')
  WHEN birthdate LIKE '%-%' THEN date_format(str_to_date(birthdate, '%m-%d-%Y'), '%Y-%m-%d')
  ELSE NULL
END;
```

```sql

```
