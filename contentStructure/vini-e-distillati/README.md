# Vini e distillati

## Description
Prodotti alcolici legati alla tradizione enologica di una regione.
## General Information
- **ID**: 8273202
- **Site ID**: 52189
- **Created**: 17-04-2024 10:57
- **Last Modified**: 17-02-2025 09:01

## Content Structure Fields
### 1. Denominazione (`denominazioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Presentazione (`presentazioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. Contatto - Nominativo (`contattoNominativoField`) 
- **Data Type**: string
- **Input Control**: text

### 4. Telefono (`telefonoField`) 
- **Data Type**: string
- **Input Control**: text

### 5. Cellulare (`cellulareField`) 
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
- Facebook: `opzione60158112`
- X: `opzione15335967`
- Instagram: `opzione73137063`

#### 8.2. URL (`urlSocialField`) 
- **Data Type**: string
- **Input Control**: text


### 9. Prezzo (`prezzoField`) 
- **Data Type**: string
- **Input Control**: text

### 10. Immagine Principale (`immaginePrincipaleMedia`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: document

### 11. Altra immagine (`altraImmagineMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 12. Latitudine (`latitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 13. Longitudine (`longitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 14. Operatore (`operatoreWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Operatore](../../contentStructure/operatore/README.md)**

### 15. Destinazione (`destinazioneWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 16. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 16.1. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text

#### 16.2. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text


### 17. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Categoria Vini e Distillati](../../categories/categoria-vini-e-distillati.md)** (`10339849`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Certificazioni e Qualità](../../categories/certificazioni-e-qualità.md)** (`10346792`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
