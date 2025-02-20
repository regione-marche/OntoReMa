# Agriturismo

## Description
Forma di turismo collegata in origine alla permanenza per un determinato periodo di tempo in aziende agricole.
## General Information
- **ID**: 8272118
- **Site ID**: 52189
- **Created**: 17-04-2024 08:31
- **Last Modified**: 19-02-2025 15:10

## Content Structure Fields
### 1. Denominazione (`denominazioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Descrizione (`descrizioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. Indirizzo completo (`indirizzoCompletoField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 4. Contatto - Nominativo (`contattoNominativoField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 5. Telefono (`telefonoField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 6. Cellulare (`cellulareField`) 
- **Data Type**: string
- **Input Control**: text

### 7. Email (`emailField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 8. Sito web (`sitoWebField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 9. SOCIAL (`socialFieldset`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 9.1. Nome social (`nomeSocialField`) 
- **Data Type**: string
- **Input Control**: select
##### Options
- Facebook: `opzione60512415`
- X: `opzione99402187`
- Instagram: `opzione81876675`

#### 9.2. URL (`urlSocialField`) 
- **Data Type**: string
- **Input Control**: text


### 10. Orario di apertura (`orarioDiAperturaField`) 
- **Data Type**: string
- **Input Control**: text

### 11. Servizi Collegati (`serviziCollegatiWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent

### 12. Alloggi (`alloggiWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Alloggio RM](../../contentStructure/alloggio-rm/README.md)**

### 13. Punti Vendita (`puntiVenditaWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent

### 14. Prodotto Tipico (`prodottoTipicoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 15. Vino (`vinoWebcontent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 16. Presidio Slow Food (`presidioSlowFoodWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 17. Ricetta (`ricettaWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 18. Attività (`attivitaField`) 
- **Data Type**: string
- **Input Control**: text

### 19. Condizione (`condizioneField`) 
- **Data Type**: string
- **Input Control**: text

### 20. Immagine principale (`immaginePrincipaleMedia`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: document

### 21. Altra immagine (`altraImmagineMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 22. Destinazione (`destinazioneWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 23. Ristorante (`ristoranteWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Ristorante](../../contentStructure/ristorante/README.md)**

### 24. Latitudine (`latitudineField`) 
- **Data Type**: integer

### 25. Longitudine (`longitudineField`) 
- **Data Type**: double

### 26. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

### 27. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 27.1. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text

#### 27.2. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text


## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Fascia di prezzo](../../categories/fascia-di-prezzo.md)** (`10338968`) 
- **[Esigenze alimentari](../../categories/esigenze-alimentari.md)** (`10346224`) 
- **[Accessibilità](../../categories/accessibilità.md)** (`10346289`) 
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Categoria Agriturismo](../../categories/categoria-agriturismo.md)** (`11098779`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
