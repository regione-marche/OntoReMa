# Presidio Slow Food

## Description
Prodotto riconosciuto e tutelato per il suo valore culturale e gastronomico.
## General Information
- **ID**: 8272834
- **Site ID**: 52189
- **Created**: 17-04-2024 10:31
- **Last Modified**: 17-02-2025 08:58

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

### 7. Sito Web (`sitoWebField`) 
- **Data Type**: string
- **Input Control**: text

### 8. SOCIAL (`socialFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 8.1. Nome social (`nomeSocialField`) 
- **Data Type**: string
- **Input Control**: select
##### Options
- Instagram: `opzione42267009`
- Facebook: `opzione83270620`

#### 8.2. URL (`urlSocialField`) 
- **Data Type**: string
- **Input Control**: text


### 9. Prezzo (`prezzoField`) 
- **Data Type**: string
- **Input Control**: text

### 10. Immagine principale (`immaginePrincipaleMedia`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: document

### 11. Altra immagine (`altraImmagineMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 12. Destinazione (`destinazioneWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 13. Latitudine (`latitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 14. Longitudine (`longitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 15. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 15.1. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text

#### 15.2. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text


### 16. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Categoria Presidio Slow Food](../../categories/categoria-presidio-slow-food.md)** (`10346261`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Certificazioni e Qualità](../../categories/certificazioni-e-qualità.md)** (`10346792`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
