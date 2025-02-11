# Interesse

## Description

## General Information
- **ID**: 52918
- **Site ID**: 52189
- **Created**: 02-11-2022 14:52
- **Last Modified**: 17-05-2024 14:32

## Content Structure Fields
### 1. Titolo dell'interesse (`interestTitle`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Descrizione (`interestDescription`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. URL contenuto (`interestContentURL`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 4. Template da riempire per la tipologia di  chiamata (`interestTemplate`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: select
#### Options
- Article: `opzione13910033`

### 5. Destinazione (`interestDestinationId`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione](../../contentStructure/destinazione/README.md)**
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 6. Sovratitolo dell'interesse (`interestOvertitle`) 
- **Data Type**: string
- **Input Control**: text

### 7. Sottotitolo dell'interesse (`interestSubtitle`) 
- **Data Type**: string
- **Input Control**: text

### 8. Articolo contiene degli eventi (`interestThematicArticleEvents`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 9. Articolo (`interestArticle`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 9.1. Autore (`interestArticleAuthors`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Autore](../../contentStructure/autore/README.md)**

#### 9.2. Link (`interestArticleHyperLink`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
##### 📁 Nested Fields
##### 9.2.1. Descrizione (`interestArticleHyperLinkDescription`) 
- **Data Type**: string

##### 9.2.2. Url esterno link (`interestArticleHyperLinkExternalUrl`) 
- **Data Type**: string
- **Input Control**: text

##### 9.2.3. Nome del link (`interestArticleHyperLinkName`) 
- **Data Type**: string
- **Input Control**: text


#### 9.3. Testo dell'articolo (`interestArticleText`) 
- **Data Type**: string

#### 9.4. Immagine (`interestArticleImage`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 9.5. Media (`interestArticleMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 9.6. Destinazione (`interestArticleDestinationID`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Destinazione](../../contentStructure/destinazione/README.md)**
    - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**


### 10. Paragrafo (`interestParagraph`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 10.1. Posizione paragrafo (`interestParagraphParagraphOrder`) 
- **Data Type**: integer

#### 10.2. Link (`interestParagraphHyperLink`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
##### 📁 Nested Fields
##### 10.2.1. Descrizione (`interestParagraphHyperLinkDescription`) 
- **Data Type**: string

##### 10.2.2. Url esterno link (`interestParagraphHyperLinkExternalUrl`) 
- **Data Type**: string
- **Input Control**: text

##### 10.2.3. Nome del link (`interestParagraphHyperLinkName`) 
- **Data Type**: string
- **Input Control**: text


#### 10.3. Testo paragrafo (`interestParagraphParagraphText`) 
- **Data Type**: string

#### 10.4. Titolo paragrafo (`interestParagraphParagraphTitle`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 10.5. Autore (`interestParagraphAuthor`) 
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Autore](../../contentStructure/autore/README.md)**

#### 10.6. Sottotitolo paragrafo (`interestParagraphParagraphSubtitle`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 10.7. Immagine (`interestParagraphImage`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 10.8. Media (`interestParagraphMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 10.9. Destinazione (`interestParagraphDestinationID`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Destinazione](../../contentStructure/destinazione/README.md)**
    - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**


### 11. sponsor (`interestSponsor`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 11.1. Nome dello sponsor (`interestSponsorName`) 
- **Data Type**: string
- **Input Control**: text

#### 11.2. Url dello sponsor (`interestSponsorIcon`) 
- **Data Type**: string
- **Input Control**: text


### 12. Risorsa (`interestSource`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 12.1. Nome della risorsa (`interestSourceName`) 
- **Data Type**: string
- **Input Control**: text

#### 12.2. Descrizione (`interestSourceDescription`) 
- **Data Type**: string

#### 12.3. Inserire l'url della risorsa (`interestSourceUrl`) 
- **Data Type**: string
- **Input Control**: text


### 13. Tempo di lettura (`interestReadingTime`) 
- **Data Type**: integer

### 14. Funzionalità (Evolutive) (`interestFeature`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 14.1. Id funzionalità (`interestFeatureId`) 
- **Data Type**: string
- **Input Control**: text

#### 14.2. Attributo della funzionalità (`interestFeatureValue`) 
- **Data Type**: string
- **Input Control**: text


### 15. ID Esterno (`interestExternalId`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
