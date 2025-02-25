# Servizio Privato

## Description
Servizio offerto da privati per supportare i turisti nelle loro esperienze.
## General Information
- **ID**: 8272981
- **Site ID**: 52189
- **Created**: 17-04-2024 10:50
- **Last Modified**: 17-02-2025 08:59

## Content Structure Fields
### 1. Nome (`nomeField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Nome Alternativo (`nomeAlternativoField`) 
- **Data Type**: string
- **Input Control**: text

### 3. Descrizione breve (`descrizioneBreveField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 4. Descrizione (`descrizioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 5. Target (`targetField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 6. Come aderire (`comeAderireField`) 
- **Data Type**: string

### 7. Pre-requisiti (`preRequisitiField`) 
- **Data Type**: string
- **Input Control**: text

### 8. Tempistiche di erogazione (`tempisticheDiErogazioneField`) 
- **Data Type**: integer

### 9. Output (`outputField`) 
- **Data Type**: string

### 10. Punto di contatto fisico (`puntoDiContattoFisicoField`) 
- **Data Type**: string
- **Input Control**: text

### 11. Punto di contatto online (`puntoDiContattoOnlineField`) 
- **Data Type**: string
- **Input Control**: text

### 12. Copertura temporale (`coperturaTemporaleField`) 
- **Data Type**: string
- **Input Control**: text

### 13. Orari di apertura (`orariDiAperturaField`) 
- **Data Type**: string
- **Input Control**: text

### 14. Destinazione (`destinazioneWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 15. Latitudine (`latitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 16. Longitudine (`longitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 17. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

### 18. Telefono (`telefonoField`) 
- **Data Type**: integer

### 19. Cellulare (`cellulareField`) 
- **Data Type**: integer

### 20. Email (`emailField`) 
- **Data Type**: string
- **Input Control**: text

### 21. Sito web (`sitoWebField`) 
- **Data Type**: string
- **Input Control**: text

### 22. SOCIAL (`socialFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 22.1. Nome social (`nomeSocialField`) 
- **Data Type**: string
- **Input Control**: select
##### Options
- Facebook: `opzione00282581`
- X: `opzione38498701`
- Instagram: `opzione10913567`
- Youtube: `opzione06488545`

#### 22.2. URL (`urlSocialField`) 
- **Data Type**: string
- **Input Control**: text


### 23. Costo (`costoField`) 
- **Data Type**: string
- **Input Control**: text

### 24. Immagine Principale (`immaginePrincipaleMedia`) 
- **Data Type**: document

### 25. Altra Immagine (`altraImmagineMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 26. Operatore (`operatoreWebContent`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Operatore](../../contentStructure/operatore/README.md)**

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
- **[Lingua](../../categories/lingua.md)** (`10207136`) 
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Stato del servizio](../../categories/stato-del-servizio.md)** (`10207215`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Categoria Servizio](../../categories/categoria-servizio.md)** (`10207244`) 
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
