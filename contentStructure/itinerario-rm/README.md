# Itinerario RM

## Description
Percorso turistico che collega varie tappe significative all'interno di una destinazione.
## General Information
- **ID**: 8272728
- **Site ID**: 52189
- **Created**: 17-04-2024 10:10
- **Last Modified**: 13-03-2025 09:24

## Content Structure Fields
### 1. Titolo dell'itinerario (`titoloDellItinerarioField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Descrizione (`descrizioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. Valido da (`validoDaField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: date

### 4. Valido a (`validoAField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: date

### 5. Difficoltà itinerario (`difficoltaItinerarioField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 6. Tappa itinerario (`tappaItinerarioWebContent`) ![Required](https://img.shields.io/badge/*Required-red.svg) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Tappa itinerario RM](../../contentStructure/tappa-itinerario-rm/README.md)**

### 7. Sovratitolo dell'itinerario (`sovratitoloDellItinerario`) 
- **Data Type**: string
- **Input Control**: text

### 8. Sottotitolo dell'itinerario (`sottotitoloDellItinerario`) 
- **Data Type**: string
- **Input Control**: text

### 9. Immagine principale (`immaginePrincipaleMedia`) 
- **Data Type**: image

### 10. Altra immagine (`altraImmagineMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 11. Media (`mediaMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 12. Tipologia itinerario (`tipologiaItinerarioField`) 
- **Data Type**: string
- **Input Control**: text

### 13. Durata (`durataField`) 
- **Data Type**: integer

### 14. Periodo migliore per l'itinerario (`periodoMigliorePerLItinerarioField`) 
- **Data Type**: string
- **Input Control**: text

### 15. Offerte (`offerteField`) 
- **Data Type**: string
- **Input Control**: text

### 16. Autore (`autoreWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent

### 17. Latitudine (`latitudineField`) 
- **Data Type**: double

### 18. Longitudine (`longitudineField`) 
- **Data Type**: integer

### 19. Media Collegati (`mediaCollegatiFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 19.1. Titolo (`titoloMediaCollegatiField`) 
- **Data Type**: string
- **Input Control**: text

#### 19.2. URL (`urlMediaCollegatiField`) 
- **Data Type**: string
- **Input Control**: text


### 20. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 20.1. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text

#### 20.2. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text


### 21. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

### 22. Sponsor (`sponsorItinerarioFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 22.1. Url dello sponsor (`urlDelloSponsorField`) 
- **Data Type**: string
- **Input Control**: text

#### 22.2. Nome dello sponsor (`nomeDelloSponsorField`) 
- **Data Type**: string
- **Input Control**: text


### 23. Risorsa (`risorsaItinerarioFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 23.1. Nome risorsa (`nomeDellaRisorsaField`) 
- **Data Type**: string
- **Input Control**: text

#### 23.2. Descrizione (`descrizioneRisorsaField`) 
- **Data Type**: string

#### 23.3. URL esterno della risorsa (`urlDellaRisorsaField`) 
- **Data Type**: string
- **Input Control**: text


### 24. Link (`linkItinerarioFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 24.1. Nome del link (`nomeDelLinkField`) 
- **Data Type**: string
- **Input Control**: text

#### 24.2. Descrizione (`descrizioneLinkField`) 
- **Data Type**: string

#### 24.3. URL esterno (`urlEsternoField`) 
- **Data Type**: string
- **Input Control**: text


### 25. Url (`urlField`) 
- **Data Type**: string
- **Input Control**: text

### 26. File GPX itinerario (`fileGpxItinerarioMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 27. File KML itinerario (`fileKmlItinerarioMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Categoria Itinerario RM](../../categories/categoria-itinerario-rm.md)** (`10346469`) ![Required](https://img.shields.io/badge/*Required-red.svg)
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
