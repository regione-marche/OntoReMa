# Itinerario

## Description

## General Information
- **ID**: 52939
- **Site ID**: 52189
- **Created**: 02-11-2022 14:52
- **Last Modified**: 18-05-2023 12:27

## Content Structure Fields
### 1. Titolo dell'itinerario (`itineraryTitle`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Descrizione (`itineraryDescription`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. Valido da (`itineraryValidFrom`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: date

### 4. Valido a (`itineraryValidTo`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: date

### 5. Difficoltà itinerario (`itineraryDifficulty`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 6. Tappa itinerario (`itineraryStage`) ![Required](https://img.shields.io/badge/*Required-red.svg) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Tappa itinerario](../../contentStructure/tappa-itinerario/README.md)**
  - **[Tappa itinerario RM](../../contentStructure/tappa-itinerario-rm/README.md)**

### 7. Sovratitolo dell'itinerario (`itineraryOverTitle`) 
- **Data Type**: string
- **Input Control**: text

### 8. Sottotitolo dell'itinerario (`itinerarySubTitle`) 
- **Data Type**: string
- **Input Control**: text

### 9. Immagine (`itineraryImage`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 10. Media (`itineraryMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 11. Tipologia itinerario (`itineraryType`) 
- **Data Type**: string
- **Input Control**: text

### 12. Durata (`itineraryDuration`) 
- **Data Type**: integer

### 13. Periodo migliore per l'itinerario (`itineraryBestPeriod`) 
- **Data Type**: string
- **Input Control**: text

### 14. Offerte (`itineraryOffers`) 
- **Data Type**: string
- **Input Control**: text

### 15. Autore (`itineraryAuthor`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Autore](../../contentStructure/autore/README.md)**

### 16. Sponsor (`itineraySponsor`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 16.1. Url dello sponsor (`itinerarySponsorIcon`) 
- **Data Type**: string
- **Input Control**: text

#### 16.2. Nome dello sponsor (`itinerarySponsorName`) 
- **Data Type**: string
- **Input Control**: text


### 17. Risorsa (`itinerarySource`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 17.1. Nome risorsa (`itinerarySourceName`) 
- **Data Type**: string
- **Input Control**: text

#### 17.2. Descrizione (`itinerarySourceDescription`) 
- **Data Type**: string

#### 17.3. URL esterno della risorsa (`itinerarySourceExternalUrl`) 
- **Data Type**: string
- **Input Control**: text


### 18. Link (`itineraryHyperlink`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 18.1. Nome del link (`itineraryHyperlinkName`) 
- **Data Type**: string
- **Input Control**: text

#### 18.2. Descrizione (`itineraryHyperlinkDescription`) 
- **Data Type**: string

#### 18.3. URL esterno (`itineraryHyperlinkExternalUrl`) 
- **Data Type**: string
- **Input Control**: text


### 19. Url (`itineraryUrl`) 
- **Data Type**: string
- **Input Control**: text

### 20. ID Esterno (`itineraryExternalId`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Additional Tags](../../categories/additional-tags.md)** (`63632`) 
- **[AEM Tags](../../categories/aem-tags.md)** (`63639`) 
- **[Parked AI Tags](../../categories/parked-ai-tags.md)** (`63646`) 
