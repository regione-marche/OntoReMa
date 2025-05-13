# Guida

## Description
Professionista o materiale informativo per supportare i visitatori nell'esplorazione delle destinazioni.
## General Information
- **ID**: 8272678
- **Site ID**: 52189
- **Created**: 17-04-2024 10:03
- **Last Modified**: 12-05-2025 06:52

## Content Structure Fields
### 1. Nome (`nomeField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Cognome (`cognomeField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 3. Codice Fiscale (`codiceFiscaleField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 4. Partita Iva (`partitaIvaField`) 
- **Data Type**: string
- **Input Control**: text

### 5. Latitudine (`latitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 6. Longitudine (`longitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 7. Area di Interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

### 8. Telefono (`telefonoField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 9. Email (`emailField`) 
- **Data Type**: string
- **Input Control**: text

### 10. Sito Web (`sitoWebField`) 
- **Data Type**: string
- **Input Control**: text

### 11. Immagine principale (`immaginePrincipaleMedia`) 
- **Data Type**: document

### 12. Servizio Privato (`servizioPrivatoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Servizio Privato](../../contentStructure/servizio-privato/README.md)**

### 13. Servizio Pubblico (`servizioPubblicoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Servizio Pubblico](../../contentStructure/servizio-pubblico/README.md)**

### 14. Destinazione (`destinazioneWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 15. SOCIAL (`socialFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 15.1. Nome social (`nomeSocialField`) 
- **Data Type**: string
- **Input Control**: select
##### Options
- Facebook: `opzione32032491`
- X: `opzione81692394`
- Youtube: `opzione32493251`

#### 15.2. URL (`urlSocialField`) 
- **Data Type**: string
- **Input Control**: text


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


## Categories
- **[Lingua](../../categories/lingua.md)** (`10207136`) 
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Categoria Guida](../../categories/categoria-guida.md)** (`10207319`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
## Custom fields
- **[ipa_code_contenuto](../../customFields/ipa-code-contenuto.md)**
- **[credits](../../customFields/credits.md)**
- **[external_ref](../../customFields/external-ref.md)**
- **[srcId](../../customFields/srcid.md)**
- **[channel](../../customFields/channel.md)**
- **[parentId](../../customFields/parentid.md)**
