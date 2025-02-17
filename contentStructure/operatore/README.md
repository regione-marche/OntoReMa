# Operatore

## Description
Professionista o impresa che offre servizi turistici.
## General Information
- **ID**: 8272780
- **Site ID**: 52189
- **Created**: 17-04-2024 10:25
- **Last Modified**: 17-02-2025 08:57

## Content Structure Fields
### 1. Nome (`nomeField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Nome alternativo (`nomeAlternativoField`) 
- **Data Type**: string
- **Input Control**: text

### 3. Descrizione breve (`descrizioneBreveField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 4. Descrizione (`descrizioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 5. Codice fiscale (`codiceFiscaleField`) 
- **Data Type**: string
- **Input Control**: text

### 6. Partita IVA (`partitaIvaField`) 
- **Data Type**: string
- **Input Control**: text

### 7. Numero REA (`numeroReaField`) 
- **Data Type**: integer

### 8. Data di costituzione (`dataDiCostituzioneField`) 
- **Data Type**: date

### 9. Funzione Principale (`funzionePrincipaleField`) 
- **Data Type**: string
- **Input Control**: text

### 10. Logo (`logoMedia`) 
- **Data Type**: document

### 11. Punti di contatto fisico (`puntiDiContattoFisicoField`) 
- **Data Type**: string
- **Input Control**: text

### 12. Punti di contatto online (`puntiDiContattoOnlineField`) 
- **Data Type**: string
- **Input Control**: text

### 13. Immagine (`immaginePrincipaleMedia`) 
- **Data Type**: document

### 14. Altra immagine (`altraImmagineMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 15. Destinazione (`destinazioneWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 16. Telefono (`telefonoField`) 
- **Data Type**: integer

### 17. Cellulare (`cellulareField`) 
- **Data Type**: integer

### 18. Email (`emailField`) 
- **Data Type**: string
- **Input Control**: text

### 19. Sito web (`sitoWebField`) 
- **Data Type**: string
- **Input Control**: text

### 20. SOCIAL (`socialFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 20.1. Nome social (`nomeSocialField`) 
- **Data Type**: string
- **Input Control**: select
##### Options
- Facebook: `opzione84003406`
- Instagram: `opzione86778525`
- Whatsapp: `opzione24217893`
- Youtube: `opzione65760693`

#### 20.2. URL (`urlSocialField`) 
- **Data Type**: string
- **Input Control**: text


### 21. Tipo di attività (`tipoDiAttivitaField`) 
- **Data Type**: string
- **Input Control**: text

### 22. Oggetto sociale (`oggettoSocialeField`) 
- **Data Type**: string
- **Input Control**: text

### 23. Indirizzo completo (`indirizzoOperatoreField`) 
- **Data Type**: string
- **Input Control**: text

### 24. Comune (`comuneField`) 
- **Data Type**: string
- **Input Control**: text

### 25. Latitudine (`latitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 26. Longitudine (`longitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 27. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

### 28. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 28.1. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text

#### 28.2. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text


## Categories
- **[Forma Giuridica](../../categories/forma-giuridica.md)** (`10207137`) 
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Categoria Operatore](../../categories/categoria-operatore.md)** (`10346296`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Regione](../../categories/regione.md)** (`10346297`) 
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
