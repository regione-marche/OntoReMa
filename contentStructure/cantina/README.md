# Cantina

## Description
Struttura dedicata alla produzione, degustazione e vendita di vini e distillati.
## General Information
- **ID**: 8272580
- **Site ID**: 52189
- **Created**: 17-04-2024 09:54
- **Last Modified**: 17-02-2025 08:54

## Content Structure Fields
### 1. Denominazione (`denominazioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Partita IVA (`partitaIvaField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 3. Descrizione (`descrizioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 4. Contatto - Nominativo (`contattoNominativoField`) 
- **Data Type**: string
- **Input Control**: text

### 5. Telefono (`telefonoField`) 
- **Data Type**: string
- **Input Control**: text

### 6. Email (`emailField`) 
- **Data Type**: string
- **Input Control**: text

### 7. Sito web (`sitoWebField`) 
- **Data Type**: string
- **Input Control**: text

### 8. SOCIAL (`socialFieldset`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 8.1. Nome social (`nomeSocialField`) 
- **Data Type**: string
- **Input Control**: select
##### Options
- Facebook: `opzione03146027`
- X: `opzione91777445`
- Instagram: `opzione21891651`

#### 8.2. URL (`urlSocialField`) 
- **Data Type**: string
- **Input Control**: text


### 9. Vini e distillati (`viniEDistillatiWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Vini e distillati](../../contentStructure/vini-e-distillati/README.md)**

### 10. Servizio Privato (`servizioPrivatoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Servizio Privato](../../contentStructure/servizio-privato/README.md)**

### 11. Servizio Pubblico (`servizioPubblicoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Servizio Pubblico](../../contentStructure/servizio-pubblico/README.md)**

### 12. Prodotto Tipico (`prodottoTipicoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 13. Vino (`vinoWebcontent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 14. Presidio Slow Food (`presidioSlowFoodWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 15. Ricetta (`ricettaWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 16. Immagine principale (`immaginePrincipaleMedia`) 
- **Data Type**: document

### 17. Altra immagine (`altraImmagineMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 18. Operatore (`operatoreWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Operatore](../../contentStructure/operatore/README.md)**

### 19. Destinazione (`destinazioneWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 20. Latitudine (`latitudineField`) 
- **Data Type**: double

### 21. Longitudine (`longitudineField`) 
- **Data Type**: double

### 22. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 22.1. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text

#### 22.2. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text


### 23. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Categoria Cantina](../../categories/categoria-cantina.md)** (`10339982`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
## Custom fields
- **[ipa_code contenuto](../../customFields/ipa-code-contenuto.md)**
- **[external ref](../../customFields/external-ref.md)**
- **[credits](../../customFields/credits.md)**
- **[srcId](../../customFields/srcid.md)**
- **[channel](../../customFields/channel.md)**
- **[parentId](../../customFields/parentid.md)**
