# Birra

## Description

## General Information
- **ID**: 8272522
- **Site ID**: 52189
- **Created**: 17-04-2024 09:50
- **Last Modified**: 02-10-2024 07:43

## Content Structure Fields
### 1. Denominazione (`denominazioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Presentazione (`presentazioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. Senza Glutine (`senzaGlutineField`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 4. Contatto - Nominativo (`contattoNominativoField`) 
- **Data Type**: string
- **Input Control**: text

### 5. Telefono (`telefonoField`) 
- **Data Type**: string
- **Input Control**: text

### 6. Cellulare (`cellulareField`) 
- **Data Type**: string
- **Input Control**: text

### 7. Email (`emailField`) 
- **Data Type**: string
- **Input Control**: text

### 8. Sito web (`sitoWebField`) 
- **Data Type**: string
- **Input Control**: text

### 9. SOCIAL (`socialFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 9.1. Nome social (`nomeSocialField`) 
- **Data Type**: string
- **Input Control**: select
- **Predefined Value**: []
##### Options
- Facebook: `opzione41861997`
- X: `opzione17698618`
- Youtube: `opzione97997370`

#### 9.2. URL (`urlSocialField`) 
- **Data Type**: string
- **Input Control**: text


### 10. Prezzo (`prezzoField`) 
- **Data Type**: string
- **Input Control**: text

### 11. Immagine principale (`immaginePrincipaleMedia`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: document

### 12. Altra immagine (`altraImmagineMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 13. Operatore (`operatoreWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Operatore](../../contentStructure/operatore/README.md)**

### 14. Destinazione (`destinazioneWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione](../../contentStructure/destinazione/README.md)**
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 15. Latitudine (`latitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 16. Longitudine (`longitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 17. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 17.1. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text

#### 17.2. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text


### 18. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Fermentazione](../../categories/fermentazione.md)** (`10339983`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Stile Birra](../../categories/stile-birra.md)** (`10339995`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Categoria Birra](../../categories/categoria-birra.md)** (`10346223`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
