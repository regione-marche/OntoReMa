# Prodotto tipico

## Description
Elemento enogastronomico rappresentativo del territorio.
## General Information
- **ID**: 8272864
- **Site ID**: 52189
- **Created**: 17-04-2024 10:33
- **Last Modified**: 12-05-2025 12:17

## Content Structure Fields
### 1. Denominazione (`denominazioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Descrizione (`descrizioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. Indirizzo completo (`indirizzoCompletoField`) 
- **Data Type**: string
- **Input Control**: text

### 4. Latitudine (`latitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: integer

### 5. Longitudine (`longitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 6. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

### 7. Operatore (`operatoreWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Operatore](../../contentStructure/operatore/README.md)**

### 8. Contatto - Nominativo (`contattoNominativoField`) 
- **Data Type**: string
- **Input Control**: text

### 9. Telefono (`telefonoField`) 
- **Data Type**: string
- **Input Control**: text

### 10. Cellulare (`cellulareField`) 
- **Data Type**: string
- **Input Control**: text

### 11. Email (`emailField`) 
- **Data Type**: string
- **Input Control**: text

### 12. Sito web (`sitoWebField`) 
- **Data Type**: string
- **Input Control**: text

### 13. SOCIAL (`socialFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 13.1. Nome social (`nomeSocialField`) 
- **Data Type**: string
- **Input Control**: select
##### Options
- Facebook: `opzione96984220`
- X: `opzione08405189`
- Instagram: `opzione09229741`

#### 13.2. URL (`urlSocialField`) 
- **Data Type**: string
- **Input Control**: text


### 14. Fascia di Prezzo (`fasciaDiPrezzoField`) 
- **Data Type**: string
- **Input Control**: text

### 15. Immagine principale (`immaginePrincipaleMedia`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: document

### 16. Altra immagine (`altraImmagineMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: image

### 17. Materie prime (`materiePrimeField`) 
- **Data Type**: string
- **Input Control**: text

### 18. Luogo di produzione (`luogoDiProduzioneField`) 
- **Data Type**: string
- **Input Control**: text

### 19. Destinazione (`destinazioneWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 20. Media Collegati (`mediaCollegatiFieldset`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 20.1. Titolo (`titoloMediaCollegatiField`) 
- **Data Type**: string
- **Input Control**: text

#### 20.2. URL (`urlMediaCollegatiField`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text


### 21. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 21.1. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text

#### 21.2. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text


## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Categoria Prodotto Tipico](../../categories/categoria-prodotto-tipico.md)** (`10207264`) ![Required](https://img.shields.io/badge/*Required-red.svg)
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
