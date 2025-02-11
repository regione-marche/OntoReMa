# Tappa itinerario

## Description

## General Information
- **ID**: 53004
- **Site ID**: 52189
- **Created**: 02-11-2022 14:53
- **Last Modified**: 18-05-2023 12:29

## Content Structure Fields
### 1. Nome della tappa dell'itinerario (`stageParTitle`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Testo (`stageText`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. Posizione paragrafo (`stageOrder`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: integer

### 4. Sottotitolo (`stageSubTitle`) 
- **Data Type**: string
- **Input Control**: text

### 5. Immagine (`stageImage`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 6. Media (`stageMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 7. Evento (`stageLinkedEvents`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Evento](../../contentStructure/evento/README.md)**
  - **[MeW Evento](../../contentStructure/mew-evento/README.md)**
  - **[Evento DVAT](../../contentStructure/evento-dvat/README.md)**
  - **[Evento RM](../../contentStructure/evento-rm/README.md)**

### 8. Destinazione (`stageLinkedDestination`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione](../../contentStructure/destinazione/README.md)**
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 9. LINK (`stageHyperlinks`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 9.1. Nome del link (`stageHyperlinksName`) 
- **Data Type**: string
- **Input Control**: text

#### 9.2. Descrizione (`stageHyperlinksDescription`) 
- **Data Type**: string

#### 9.3. Url esterno del link (`stageHyperlinksExternalUrl`) 
- **Data Type**: string
- **Input Control**: text


### 10. ID Esterno (`stageExternalId`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
