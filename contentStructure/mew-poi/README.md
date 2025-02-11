# MeW POI

## Description

## General Information
- **ID**: 5686441
- **Site ID**: 52189
- **Created**: 18-01-2024 11:39
- **Last Modified**: 19-01-2024 09:10

## Content Structure Fields
### 1. Denominazione (`title`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Denominazione alternativa (`alternativeTitle`) 
- **Data Type**: string
- **Input Control**: text

### 3. Immagine principale (`mainImageSection`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 3.1. Immagine principale (`mainImage`) 
- **Data Type**: document

#### 3.2. Didascalia (`mainImageCaption`) 
- **Data Type**: string
- **Input Control**: text

#### 3.3. Autore (`mainImageAuthor`) 
- **Data Type**: string
- **Input Control**: text


### 4. Abstract (`abstract`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 5. Presentazione (`description`) 
- **Data Type**: string

### 6. Metatag (`metatag`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

### 7. Poi collegato (`relatedPoi`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent

### 8. Geolocalizzazione (`geoSection`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 8.1. Indirizzo (`address`) 
- **Data Type**: string
- **Input Control**: text

#### 8.2. N° civico (`houseNumber`) 
- **Data Type**: string
- **Input Control**: text

#### 8.3. Comune (`municipality`) 
- **Data Type**: string
- **Input Control**: text

#### 8.4. Codice Istat Comune (`istatCodeMunicipality`) 
- **Data Type**: string
- **Input Control**: text

#### 8.5. Provincia (`province`) 
- **Data Type**: string
- **Input Control**: text

#### 8.6. Descrizione tipo indirizzo (`addressTypeDescription`) 
- **Data Type**: string
- **Input Control**: text

#### 8.7. Latitudine (`latitude`) 
- **Data Type**: string
- **Input Control**: text

#### 8.8. Longitudine (`longitude`) 
- **Data Type**: string
- **Input Control**: text

#### 8.9. Coordinate verificate (`verifiedCoordinates`) 
- **Data Type**: string
- **Input Control**: radio
##### Options
- Si: `opzione47212794`
- No: `opzione55495510`


### 9. Contatti (`contactSection`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 9.1. Contatto - Nominativo (`contact`) 
- **Data Type**: string
- **Input Control**: text

#### 9.2. Telefono (`phone`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 9.3. Cellulare (`mobile`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 9.4. Fax (`fax`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 9.5. Email (`email`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 9.6. Sito web (`website`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 9.7. Pagina social (`socialPage`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text


### 10. Prezzo (`price`) 
- **Data Type**: string
- **Input Control**: text

### 11. Orario di apertura (`openingHours`) 
- **Data Type**: string
- **Input Control**: text

### 12. Servizi (`services`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

### 13. Modalità di accesso (`methodsOfAccess`) 
- **Data Type**: string
- **Input Control**: text

### 14. Immagini (`imagesSection`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 14.1. Immagine (`image`) 
- **Data Type**: document

#### 14.2. Autore (`author`) 
- **Data Type**: string
- **Input Control**: text

#### 14.3. Didascalia (`caption`) 
- **Data Type**: string
- **Input Control**: text

#### 14.4. Ordine immagine (`imageOrder`) 
- **Data Type**: integer

#### 14.5. Path assoluto (`absolutePath`) 
- **Data Type**: string
- **Input Control**: text

#### 14.6. Path immagine (`imagePath`) 
- **Data Type**: string
- **Input Control**: text

#### 14.7. ID immagine (`imageId`) 
- **Data Type**: integer


### 15. Video Youtube (`youtubeVideosSection`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 15.1. Video youtube (ID) (`youtubeVideoId`) 
- **Data Type**: string
- **Input Control**: text

#### 15.2. Didascalia (`youtubeVideoCaption`) 
- **Data Type**: string
- **Input Control**: text


### 16. Identificativo (`identifier`) 
- **Data Type**: string
- **Input Control**: text

### 17. Pubblica (`isPublic`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 18. Link pagina (`pageLink`) 
- **Data Type**: string
- **Input Control**: text

### 19. Ordine (`order`) 
- **Data Type**: integer

### 20. Da non perdere (`doNotMiss`) 
- **Data Type**: string
- **Input Control**: text

### 21. Rilevanza regionale (`isRegionalRelevant`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 22. Giorni durata (`daysDuration`) 
- **Data Type**: integer

### 23. Snippet titolo (`titleSnippet`) 
- **Data Type**: string
- **Input Control**: text

### 24. Snippet descrizione (`descriptionSnippet`) 
- **Data Type**: string
- **Input Control**: text

### 25. Snippet didascalia (`captionSnippet`) 
- **Data Type**: string
- **Input Control**: text

### 26. Snippet foto (`imageSnippet`) 
- **Data Type**: string
- **Input Control**: text

### 27. ID Poi (`poiId`) 
- **Data Type**: integer

### 28. ID Tipo (`typeId`) 
- **Data Type**: integer

### 29. Descrizione Tipo (`typeDescription`) 
- **Data Type**: string
- **Input Control**: text

### 30. ID Sottotipo (`subtypeId`) 
- **Data Type**: integer

### 31. Descrizione Sottotipo (`subtypeDescription`) 
- **Data Type**: string
- **Input Control**: text

### 32. Data inserimento (`entryDate`) 
- **Data Type**: date

### 33. ID Utente inserimento (`entryUserId`) 
- **Data Type**: string
- **Input Control**: text

### 34. Data ultima modifica (`lastModifiedDate`) 
- **Data Type**: date

### 35. ID Utente ultima modifica (`lastModifiedUserId`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
