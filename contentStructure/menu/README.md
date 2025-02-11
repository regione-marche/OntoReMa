# Menu

## Description

## General Information
- **ID**: 52985
- **Site ID**: 52189
- **Created**: 02-11-2022 14:53
- **Last Modified**: 11-07-2023 08:20

## Content Structure Fields
### 1. Menu (`menuMenu`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 1.1. Prezzo (`menuMenuPrice`) 
- **Data Type**: double

#### 1.2. Valuta (`menuMenuCurrency`) 
- **Data Type**: string
- **Input Control**: text

#### 1.3. Sezione (`menuMenuSection`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
##### 📁 Nested Fields
##### 1.3.1. Nome (`menuMenuSectionName`) 
- **Data Type**: string
- **Input Control**: text

##### 1.3.2. Item (`menuMenuSectionItem`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
###### 📁 Nested Fields
###### 1.3.2.1. Prezzo (`menuMenuSectionItemPrice`) 
- **Data Type**: double

###### 1.3.2.2. Nome (`menuMenuSectionItemName`) 
- **Data Type**: string
- **Input Control**: text

###### 1.3.2.3. Descrizione (`menuMenuSectionItemDescription`) 
- **Data Type**: string

###### 1.3.2.4.  Valuta (`menuMenuSectionItemCurrency`) 
- **Data Type**: string
- **Input Control**: text

###### 1.3.2.5. Immagine (`menuMenuSectionItemImage`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document


##### 1.3.3. Immagine (`menuMenuSectionImage`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document


#### 1.4. Descrizione (`menuMenuDescription`) 
- **Data Type**: string

#### 1.5. Url (`menuMenuUrl`) 
- **Data Type**: string
- **Input Control**: text

#### 1.6. Media (`menuMenuMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document


### 2. Destinazione (`menuDestinationID`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione](../../contentStructure/destinazione/README.md)**
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 3. Funzionalità (Evolutive) (`menuFeature`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 3.1. Id funzionalità (`menuFeatureId`) 
- **Data Type**: string
- **Input Control**: text

#### 3.2. Attributo (`menuFeatureValue`) 
- **Data Type**: string
- **Input Control**: text


### 4. ID Esterno (`menuExternalId`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
