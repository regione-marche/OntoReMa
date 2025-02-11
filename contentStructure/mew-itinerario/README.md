# MeW Itinerario

## Description

## General Information
- **ID**: 5685966
- **Site ID**: 52189
- **Created**: 18-01-2024 11:38
- **Last Modified**: 19-01-2024 09:10

## Content Structure Fields
### 1. Titolo (`title`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Abstract (`abstract`) 
- **Data Type**: string
- **Input Control**: text

### 3. Descrizione (`description`) 
- **Data Type**: string

### 4. Immagini (`imagesSection`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 4.1. Immagine (`image`) 
- **Data Type**: document

#### 4.2. Autore (`author`) 
- **Data Type**: string
- **Input Control**: text

#### 4.3. Didascalia (`caption`) 
- **Data Type**: string
- **Input Control**: text

#### 4.4. Ordine immagine (`imageOrder`) 
- **Data Type**: integer

#### 4.5. Path assoluto (`absolutePath`) 
- **Data Type**: string
- **Input Control**: text

#### 4.6. Path immagine (`imagePath`) 
- **Data Type**: string
- **Input Control**: text

#### 4.7. ID immagine (`imageId`) 
- **Data Type**: integer


### 5. ID Destinatario (`recipientID`) 
- **Data Type**: integer

### 6. Pubblica (`isPublic`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 7. Stato (`status`) 
- **Data Type**: string
- **Input Control**: text

### 8. Ordine (`order`) 
- **Data Type**: integer

### 9. Cod Wifi (`wifiCod`) 
- **Data Type**: string
- **Input Control**: text

### 10. Rilevanza regionale (`isRegionalRelevant`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 11. Giorni durata (`durationDays`) 
- **Data Type**: integer

### 12. Descrizione durata (`durationDescription`) 
- **Data Type**: string
- **Input Control**: text

### 13. Periodo stagionale (`seasonalPeriodSection`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 13.1. Periodo stagione (`seasonPeriod`) 
- **Data Type**: string
- **Input Control**: text

#### 13.2. ID Periodo (`periodId`) 
- **Data Type**: integer


### 14. POI (`poi`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[MeW POI](../../contentStructure/mew-poi/README.md)**

### 15. ID Itinerario (`itineraryId`) 
- **Data Type**: integer

### 16. Data inizio validità (`validityStartDate`) 
- **Data Type**: date

### 17. Data fine validità (`validityEndDate`) 
- **Data Type**: date

### 18. Data inserimento (`entryDate`) 
- **Data Type**: date

### 19. ID Utente inserimento (`entryUserId`) 
- **Data Type**: integer

### 20. Data ultima modifica (`lastModifiedDate`) 
- **Data Type**: date

### 21. ID Utente ultima modifica (`lastModifiedUserId`) 
- **Data Type**: integer

### 22. Campo2 (`field2`) 
- **Data Type**: string
- **Input Control**: text

### 23. Campo5 - Durata (`field5`) 
- **Data Type**: string
- **Input Control**: text

### 24. Campo6 (`field6`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
