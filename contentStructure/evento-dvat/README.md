# Evento DVAT

## Description

## General Information
- **ID**: 7370500
- **Site ID**: 52189
- **Created**: 13-02-2024 17:06
- **Last Modified**: 13-02-2024 17:06

## Content Structure Fields
### 1. Titolo (`title`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Sottotitolo (`subtitle`) 
- **Data Type**: string
- **Input Control**: text

### 3. Abstract (`abstract`) 
- **Data Type**: string
- **Input Control**: text

### 4. Descrizione (`description`) 
- **Data Type**: string

### 5. Immagine (`image`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 6. Data inizio evento (`startDate`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: date

### 7. Data fine evento (`endDate`) 
- **Data Type**: date

### 8. Orari (`timetables`) 
- **Data Type**: string
- **Input Control**: text

### 9. Prezzi (`prices`) 
- **Data Type**: string
- **Input Control**: text

### 10. Link prenotazione (`bookingLink`) 
- **Data Type**: string
- **Input Control**: text

### 11. Ristorante (`restaurantSection`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 11.1. Denominazione (`restaurantName`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

#### 11.2. Immagine (`restaurantImage`) 
- **Data Type**: document

#### 11.3. Contatto - Nominativo (`restaurantContactName`) 
- **Data Type**: string
- **Input Control**: text

#### 11.4. Telefono (`restaurantPhone`) 
- **Data Type**: string
- **Input Control**: text

#### 11.5. Email (`restaurantEmail`) 
- **Data Type**: string
- **Input Control**: text

#### 11.6. Sito web (`restaurantWebsite`) 
- **Data Type**: string
- **Input Control**: text

#### 11.7. Menu (`restaurantMenuSection`) 
- **Data Type**: 
##### 📁 Nested Fields
##### 11.7.1. Prezzo (`restaurantMenuPrice`) 
- **Data Type**: string
- **Input Control**: text

##### 11.7.2. Sezione (`restaurantMenuSubsection`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
###### 📁 Nested Fields
###### 11.7.2.1. Nome sezione (`restaurantMenuSubsectionTitle`) 
- **Data Type**: string
- **Input Control**: text

###### 11.7.2.2. Descrizione (`restaurantMenuSubsectionDescription`) 
- **Data Type**: string



#### 11.8. Indirizzo (`restaurantAddress`) 
- **Data Type**: string
- **Input Control**: text

#### 11.9. Latitudine (`latitude`) 
- **Data Type**: string
- **Input Control**: text

#### 11.10. Longitudine (`longitude`) 
- **Data Type**: string
- **Input Control**: text

#### 11.11. Descrizione (`restaurantDescription`) 
- **Data Type**: string
- **Input Control**: text


### 12. Cantina (`winerySection`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 12.1. Denominazione (`wineryTitle`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

#### 12.2. Immagine (`wineryImage`) 
- **Data Type**: document

#### 12.3. Contatto - Nominativo (`wineryContactName`) 
- **Data Type**: string
- **Input Control**: text

#### 12.4. Telefono (`wineryPhone`) 
- **Data Type**: string
- **Input Control**: text

#### 12.5. Email (`wineryEmail`) 
- **Data Type**: string
- **Input Control**: text

#### 12.6. Sito web (`wineryWebsite`) 
- **Data Type**: string
- **Input Control**: text

#### 12.7. Indirizzo (`wineryAddress`) 
- **Data Type**: string
- **Input Control**: text

#### 12.8. Latitudine (`wineryLatitude`) 
- **Data Type**: string
- **Input Control**: text

#### 12.9. Longitudine (`wineryLongitude`) 
- **Data Type**: string
- **Input Control**: text

#### 12.10. Descrizione (`wineryDescription`) 
- **Data Type**: string
- **Input Control**: text

#### 12.11. Partita IVA (`wineryVATNumber`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text


## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
