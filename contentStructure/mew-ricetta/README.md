# MeW Ricetta

## Description

## General Information
- **ID**: 5687104
- **Site ID**: 52189
- **Created**: 18-01-2024 11:41
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

### 4. Difficoltà (`difficulty`) 
- **Data Type**: string
- **Input Control**: text

### 5. Preparazione (`preparation`) 
- **Data Type**: string

### 6. Cottura (`cooking`) 
- **Data Type**: string
- **Input Control**: text

### 7. Dosi (`doses`) 
- **Data Type**: string
- **Input Control**: text

### 8. Costo (`cost`) 
- **Data Type**: string
- **Input Control**: text

### 9. Ingredienti (`ingredients`) 
- **Data Type**: string
- **Input Control**: text

### 10. Geolocalizzazione (`geoSection`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 10.1. Indirizzo (`address`) 
- **Data Type**: string
- **Input Control**: text

#### 10.2. N° civico (`houseNumber`) 
- **Data Type**: string
- **Input Control**: text

#### 10.3. Comune (`municipality`) 
- **Data Type**: string
- **Input Control**: text

#### 10.4. Codice Istat Comune (`istatCodeMunicipality`) 
- **Data Type**: string
- **Input Control**: text

#### 10.5. Provincia (`province`) 
- **Data Type**: string
- **Input Control**: text

#### 10.6. Descrizione tipo indirizzo (`addressTypeDescription`) 
- **Data Type**: string
- **Input Control**: text

#### 10.7. Latitudine (`latitude`) 
- **Data Type**: string
- **Input Control**: text

#### 10.8. Longitudine (`longitude`) 
- **Data Type**: string
- **Input Control**: text

#### 10.9. Coordinate verificate (`verifiedCoordinates`) 
- **Data Type**: string
- **Input Control**: radio
##### Options
- Si: `opzione47212794`
- No: `opzione55495510`


### 11. Contatti (`contactSection`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 11.1. Contatto - Nominativo (`contact`) 
- **Data Type**: string
- **Input Control**: text

#### 11.2. Telefono (`phone`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 11.3. Cellulare (`mobile`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 11.4. Fax (`fax`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 11.5. Email (`email`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 11.6. Sito web (`website`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 11.7. Pagina social (`socialPage`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text


### 12. Prezzo (`price`) 
- **Data Type**: string
- **Input Control**: text

### 13. Orario di apertura (`openingHours`) 
- **Data Type**: string
- **Input Control**: text

### 14. Servizi (`services`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

### 15. Immagini (`imagesSection`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 15.1. Immagine (`image`) 
- **Data Type**: document

#### 15.2. Autore (`author`) 
- **Data Type**: string
- **Input Control**: text

#### 15.3. Didascalia (`caption`) 
- **Data Type**: string
- **Input Control**: text

#### 15.4. Ordine immagine (`imageOrder`) 
- **Data Type**: integer

#### 15.5. Path assoluto (`absolutePath`) 
- **Data Type**: string
- **Input Control**: text

#### 15.6. Path immagine (`imagePath`) 
- **Data Type**: string
- **Input Control**: text

#### 15.7. ID immagine (`imageId`) 
- **Data Type**: integer


### 16. Pubblica (`isPublic`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 17. Link pagina (`pageLink`) 
- **Data Type**: string
- **Input Control**: text

### 18. Ordine (`order`) 
- **Data Type**: integer

### 19. Da non perdere (`doNotMiss`) 
- **Data Type**: string
- **Input Control**: text

### 20. Rilevanza regionale (`isRegionalRelevant`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 21. Giorni durata (`daysDuration`) 
- **Data Type**: integer

### 22. Data di scadenza (`expirationDate`) 
- **Data Type**: date

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
