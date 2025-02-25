# Servizio Pubblico

## Description
Servizio offerto da enti pubblici per il supporto e la gestione del turismo.
## General Information
- **ID**: 8273124
- **Site ID**: 52189
- **Created**: 17-04-2024 10:52
- **Last Modified**: 17-02-2025 09:00

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
- **Input Control**: text

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

### 10. Punti di contatto fisico (`puntiDiContattoFisicoField`) 
- **Data Type**: string
- **Input Control**: text

### 11. Punti di contatto online (`puntiDiContattoOnlineField`) 
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

### 18. Normative (`normativeField`) 
- **Data Type**: string

### 19. Telefono (`telefonoField`) 
- **Data Type**: integer

### 20. Cellulare (`cellulareField`) 
- **Data Type**: integer

### 21. Email (`emailField`) 
- **Data Type**: string
- **Input Control**: text

### 22. Sito web (`sitoWebField`) 
- **Data Type**: string
- **Input Control**: text

### 23. SOCIAL (`socialFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 23.1. Nome social (`nomeSocialField`) 
- **Data Type**: string
- **Input Control**: select
##### Options
- Facebook: `opzione98506237`
- Instagram: `opzione66966347`
- X: `opzione01029534`
- Whatsapp: `opzione71040297`
- Youtube: `opzione83327340`

#### 23.2. URL (`urlSocialField`) 
- **Data Type**: string
- **Input Control**: text


### 24. Costo (`costoField`) 
- **Data Type**: string
- **Input Control**: text

### 25. Immagine principale (`immaginePrincipaleMedia`) 
- **Data Type**: document

### 26. Altra immagine (`altraImmagineMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 27. Codice dell'ente erogatore (`codiceDellEnteErogatoreField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
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
- **[Lingua](../../categories/lingua.md)** (`10207136`) 
- **[Livello di interazione](../../categories/livello-di-interazione.md)** (`10207138`) 
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
