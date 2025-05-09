# Presidio Slow Food

## Description
Prodotto riconosciuto e tutelato per il suo valore culturale e gastronomico.
## General Information
- **ID**: 8272834
- **Site ID**: 52189
- **Created**: 17-04-2024 10:31
- **Last Modified**: 08-05-2025 12:48

## Content Structure Fields
### 1. Denominazione (`denominazioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Presentazione (`presentazioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. Operatore (`operatoreWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Operatore](../../contentStructure/operatore/README.md)**

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

### 8. Sito Web (`sitoWebField`) 
- **Data Type**: string
- **Input Control**: text

### 9. SOCIAL (`socialFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 9.1. Nome social (`nomeSocialField`) 
- **Data Type**: string
- **Input Control**: select
##### Options
- Instagram: `opzione42267009`
- Facebook: `opzione83270620`

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

### 13. Destinazione (`destinazioneWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 14. Latitudine (`latitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 15. Longitudine (`longitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 16. Media Collegati (`mediaCollegatiFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 16.1. Titolo (`titoloMediaCollegatiField`) 
- **Data Type**: string
- **Input Control**: text

#### 16.2. URL (`urlMediaCollegatiField`) 
- **Data Type**: string
- **Input Control**: text


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
- **[Categoria Presidio Slow Food](../../categories/categoria-presidio-slow-food.md)** (`10346261`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Certificazioni e Qualità](../../categories/certificazioni-e-qualità.md)** (`10346792`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
## Custom fields
- **[ipa_code_contenuto](../../customFields/ipa-code-contenuto.md)**
- **[credits](../../customFields/credits.md)**
- **[external_ref](../../customFields/external-ref.md)**
- **[srcId](../../customFields/srcid.md)**
- **[channel](../../customFields/channel.md)**
- **[parentId](../../customFields/parentid.md)**
