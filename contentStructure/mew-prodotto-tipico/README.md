# MeW Prodotto tipico

## Description

## General Information
- **ID**: 5686633
- **Site ID**: 52189
- **Created**: 18-01-2024 11:40
- **Last Modified**: 19-01-2024 09:09

## Content Structure Fields
### 1. Denominazione (`title`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Presentazione (`description`) 
- **Data Type**: string

### 3. Metatag (`metatag`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

### 4. Geolocalizzazione (`geoSection`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 4.1. Indirizzo (`address`) 
- **Data Type**: string
- **Input Control**: text

#### 4.2. N° civico (`houseNumber`) 
- **Data Type**: string
- **Input Control**: text

#### 4.3. Comune (`municipality`) 
- **Data Type**: string
- **Input Control**: text

#### 4.4. Codice Istat Comune (`istatCodeMunicipality`) 
- **Data Type**: string
- **Input Control**: text

#### 4.5. Provincia (`province`) 
- **Data Type**: string
- **Input Control**: text

#### 4.6. Descrizione tipo indirizzo (`addressTypeDescription`) 
- **Data Type**: string
- **Input Control**: text

#### 4.7. Latitudine (`latitude`) 
- **Data Type**: string
- **Input Control**: text

#### 4.8. Longitudine (`longitude`) 
- **Data Type**: string
- **Input Control**: text

#### 4.9. Coordinate verificate (`verifiedCoordinates`) 
- **Data Type**: string
- **Input Control**: radio
##### Options
- Si: `opzione47212794`
- No: `opzione55495510`


### 5. Contatti (`contactSection`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 5.1. Contatto - Nominativo (`contact`) 
- **Data Type**: string
- **Input Control**: text

#### 5.2. Telefono (`phone`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 5.3. Cellulare (`mobile`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 5.4. Fax (`fax`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 5.5. Email (`email`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 5.6. Sito web (`website`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 5.7. Pagina social (`socialPage`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text


### 6. Prezzo (`price`) 
- **Data Type**: string
- **Input Control**: text

### 7. Orario di apertura (`openingHours`) 
- **Data Type**: string
- **Input Control**: text

### 8. Servizi (`services`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

### 9. Immagini (`imagesSection`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 9.1. Immagine (`image`) 
- **Data Type**: document

#### 9.2. Autore (`author`) 
- **Data Type**: string
- **Input Control**: text

#### 9.3. Didascalia (`caption`) 
- **Data Type**: string
- **Input Control**: text

#### 9.4. Ordine immagine (`imageOrder`) 
- **Data Type**: integer

#### 9.5. Path assoluto (`absolutePath`) 
- **Data Type**: string
- **Input Control**: text

#### 9.6. Path immagine (`imagePath`) 
- **Data Type**: string
- **Input Control**: text

#### 9.7. ID immagine (`imageId`) 
- **Data Type**: integer


### 10. Pubblica (`isPublic`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 11. Link pagina (`pageLink`) 
- **Data Type**: string
- **Input Control**: text

### 12. Ordine (`order`) 
- **Data Type**: integer

### 13. Da non perdere (`doNotMiss`) 
- **Data Type**: string
- **Input Control**: text

### 14. Rilevanza regionale (`isRegionalRelevant`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 15. Giorni durata (`daysDuration`) 
- **Data Type**: integer

### 16. Data di scadenza (`expirationDate`) 
- **Data Type**: date

### 17. Snippet titolo (`titleSnippet`) 
- **Data Type**: string
- **Input Control**: text

### 18. Snippet descrizione (`descriptionSnippet`) 
- **Data Type**: string
- **Input Control**: text

### 19. Snippet didascalia (`captionSnippet`) 
- **Data Type**: string
- **Input Control**: text

### 20. Snippet foto (`imageSnippet`) 
- **Data Type**: string
- **Input Control**: text

### 21. ID Poi (`poiId`) 
- **Data Type**: integer

### 22. ID Tipo (`typeId`) 
- **Data Type**: integer

### 23. Descrizione Tipo (`typeDescription`) 
- **Data Type**: string
- **Input Control**: text

### 24. ID Sottotipo (`subtypeId`) 
- **Data Type**: integer

### 25. Descrizione Sottotipo (`subtypeDescription`) 
- **Data Type**: string
- **Input Control**: text

### 26. Data inserimento (`entryDate`) 
- **Data Type**: date

### 27. ID Utente inserimento (`entryUserId`) 
- **Data Type**: string
- **Input Control**: text

### 28. Data ultima modifica (`lastModifiedDate`) 
- **Data Type**: date

### 29. ID Utente ultima modifica (`lastModifiedUserId`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
