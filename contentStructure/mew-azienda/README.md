# MeW Azienda

## Description

## General Information
- **ID**: 5678250
- **Site ID**: 52189
- **Created**: 18-01-2024 11:37
- **Last Modified**: 19-01-2024 09:10

## Content Structure Fields
### 1. Ragione sociale (`title`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Descrizione (`description`) 
- **Data Type**: string

### 3. Geolocalizzazione (`geoSection`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 3.1. Indirizzo (`address`) 
- **Data Type**: string
- **Input Control**: text

#### 3.2. N° civico (`houseNumber`) 
- **Data Type**: string
- **Input Control**: text

#### 3.3. Comune (`municipality`) 
- **Data Type**: string
- **Input Control**: text

#### 3.4. Codice Istat Comune (`istatCodeMunicipality`) 
- **Data Type**: string
- **Input Control**: text

#### 3.5. Provincia (`province`) 
- **Data Type**: string
- **Input Control**: text

#### 3.6. Descrizione tipo indirizzo (`addressTypeDescription`) 
- **Data Type**: string
- **Input Control**: text

#### 3.7. Latitudine (`latitude`) 
- **Data Type**: string
- **Input Control**: text

#### 3.8. Longitudine (`longitude`) 
- **Data Type**: string
- **Input Control**: text

#### 3.9. Coordinate verificate (`verifiedCoordinates`) 
- **Data Type**: string
- **Input Control**: radio
##### Options
- Si: `opzione47212794`
- No: `opzione55495510`


### 4. Contatti (`contactSection`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 4.1. Contatto - Nominativo (`contact`) 
- **Data Type**: string
- **Input Control**: text

#### 4.2. Telefono (`phone`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 4.3. Cellulare (`mobile`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 4.4. Fax (`fax`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 4.5. Email (`email`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 4.6. Sito web (`website`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 4.7. Pagina social (`socialPage`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text


### 5. Attività (`activity`) 
- **Data Type**: string
- **Input Control**: text

### 6. Condizione (`condition`) 
- **Data Type**: string
- **Input Control**: text

### 7. Immagini (`imagesSection`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 7.1. Immagine (`image`) 
- **Data Type**: document

#### 7.2. Autore (`author`) 
- **Data Type**: string
- **Input Control**: text

#### 7.3. Didascalia (`caption`) 
- **Data Type**: string
- **Input Control**: text

#### 7.4. Ordine immagine (`imageOrder`) 
- **Data Type**: integer

#### 7.5. Path assoluto (`absolutePath`) 
- **Data Type**: string
- **Input Control**: text

#### 7.6. Path immagine (`imagePath`) 
- **Data Type**: string
- **Input Control**: text

#### 7.7. ID immagine (`imageId`) 
- **Data Type**: integer


### 8. ID Poi (`poiId`) 
- **Data Type**: integer

### 9. Tipologia Poi (`poiType`) 
- **Data Type**: string
- **Input Control**: text

### 10. NUM_CERTIFICATO (`certificateNumber`) 
- **Data Type**: string
- **Input Control**: text

### 11. ID_SIAR (`idSiar`) 
- **Data Type**: string
- **Input Control**: text

### 12. CUAA (`cuaa`) 
- **Data Type**: string
- **Input Control**: text

### 13. Data inserimento (`entryDate`) 
- **Data Type**: date

### 14. ID Utente inserimento (`entryUserId`) 
- **Data Type**: string
- **Input Control**: text

### 15. Data ultima modifica (`lastModifiedDate`) 
- **Data Type**: date

### 16. ID Utente ultima modifica (`lastModifiedUserId`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
