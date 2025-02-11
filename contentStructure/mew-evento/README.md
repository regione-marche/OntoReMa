# MeW Evento

## Description

## General Information
- **ID**: 5685921
- **Site ID**: 52189
- **Created**: 18-01-2024 11:38
- **Last Modified**: 19-01-2024 09:10

## Content Structure Fields
### 1. Titolo (`title`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Sottotitolo (`subtitle`) 
- **Data Type**: string
- **Input Control**: text

### 3. Abstract (`abstract`) 
- **Data Type**: string

### 4. Descrizione (`description`) 
- **Data Type**: string

### 5. Evento genitore (`parentEvent`) 
- **Data Type**: structuredContent

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

### 10. URL evento (`eventUrl`) 
- **Data Type**: string
- **Input Control**: text

### 11. Descrizione luogo (`placeDescription`) 
- **Data Type**: string
- **Input Control**: text

### 12. Accessibilità (`accessibilityInfo`) 
- **Data Type**: string
- **Input Control**: text

### 13. Immagini (`imagesSection`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 13.1. Immagine (`image`) 
- **Data Type**: document

#### 13.2. Autore (`author`) 
- **Data Type**: string
- **Input Control**: text

#### 13.3. Didascalia (`caption`) 
- **Data Type**: string
- **Input Control**: text

#### 13.4. Ordine immagine (`imageOrder`) 
- **Data Type**: integer

#### 13.5. Path assoluto (`absolutePath`) 
- **Data Type**: string
- **Input Control**: text

#### 13.6. Path immagine (`imagePath`) 
- **Data Type**: string
- **Input Control**: text

#### 13.7. ID immagine (`imageId`) 
- **Data Type**: integer


### 14. Video Youtube (`youtubeVideosSection`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 14.1. Video youtube (ID) (`youtubeVideoId`) 
- **Data Type**: string
- **Input Control**: text

#### 14.2. Didascalia (`youtubeVideoCaption`) 
- **Data Type**: string
- **Input Control**: text


### 15. Luogo (`placeSection`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 15.1. Denominazione (`naming`) 
- **Data Type**: string
- **Input Control**: text

#### 15.2. Codice Istat Comune (`istatCodeMunicipality`) 
- **Data Type**: string
- **Input Control**: text

#### 15.3. Città (`city`) 
- **Data Type**: string
- **Input Control**: text

#### 15.4. Latitudine (`latitude`) 
- **Data Type**: string
- **Input Control**: text

#### 15.5. Longitudine (`longitude`) 
- **Data Type**: string
- **Input Control**: text


### 16. A chi è rivolto (`recipients`) 
- **Data Type**: string

### 17. Patrocinato da (`sponsorship`) 
- **Data Type**: string

### 18. Sponsor (`sponsor`) 
- **Data Type**: string

### 19. Rilevanza regionale (`isRegionalRelevant`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 20. Performers (`performers`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

### 21. Appuntamenti (`childrenEvents`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent

### 22. Allegati (`attachmentSection`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 22.1. Allegato (`attachment`) 
- **Data Type**: document

#### 22.2. Titolo (`attachmentTitle`) 
- **Data Type**: string
- **Input Control**: text

#### 22.3. Breve descrizione (`attachmentDescription`) 
- **Data Type**: string
- **Input Control**: text


### 23. Contatti (`contactSection`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 23.1. Contatto - Nominativo (`contact`) 
- **Data Type**: string
- **Input Control**: text

#### 23.2. Telefono (`phone`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 23.3. Cellulare (`mobile`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 23.4. Fax (`fax`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 23.5. Email (`email`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 23.6. Sito web (`website`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 23.7. Pagina social (`socialPage`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text


### 24. Informazioni turistiche (`touristInformationSection`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 24.1. Nominativo (`touristInformationName`) 
- **Data Type**: string
- **Input Control**: text

#### 24.2. Telefono (`touristInformationPhone`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 24.3. Fax (`touristInformationFax`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 24.4. Email (`touristInformationEmail`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 24.5. Sito web (`touristInformationWebsite`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text


### 25. Attrattore (`poi`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent

### 26. Stato (`status`) 
- **Data Type**: string
- **Input Control**: text

### 27. ID Evento (`eventId`) 
- **Data Type**: integer

### 28. URL evento sito Turismo Marche (`tourismSiteEventUrl`) 
- **Data Type**: string
- **Input Control**: text

### 29. URL immagine sito Turismo Marche (`tourismSiteImageUrl`) 
- **Data Type**: string
- **Input Control**: text

### 30. Data ultima modifica (`lastModifiedDate`) 
- **Data Type**: date

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
