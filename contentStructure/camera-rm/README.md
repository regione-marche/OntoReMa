# Camera RM

## Description
Unità abitativa all'interno di una struttura ricettiva.
## General Information
- **ID**: 8272552
- **Site ID**: 52189
- **Created**: 17-04-2024 09:52
- **Last Modified**: 13-03-2025 09:44

## Content Structure Fields
### 1. Tipologia di camera (`tipologiaDiCameraField`) 
- **Data Type**: string
- **Input Control**: text

### 2. Occupazione (stato) della camera (`occupazioneDellCameraField`) 
- **Data Type**: string
- **Input Control**: text

### 3. Sistemazione della camera (`sistemazioneDellaCameraField`) 
- **Data Type**: string
- **Input Control**: text

### 4. Disponibilità dal (`disponibilitaDalField`) 
- **Data Type**: date

### 5. Disponibilità al (`disponibilitaAlField`) 
- **Data Type**: date

### 6. Numero di camere (`numeroDiCamereField`) 
- **Data Type**: integer

### 7. Tipologia di letto (`tipologiaDiLettoField`) 
- **Data Type**: string
- **Input Control**: text

### 8. Aria Condizionata (`ariaCondizionataField`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 9. Cassetta di sicurezza (`cassettaDiSicurezzaField`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 10. Angolo cottura (`angoloCotturaField`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 11. Jacuzzi (`jacuzziField`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 12. ID hotel (`idHotelField`) 
- **Data Type**: string
- **Input Control**: text

### 13. Destinazione (`destinazioneWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 14. Latitudine (`latitudineField`) 
- **Data Type**: double

### 15. Longitudine (`longitudineField`) 
- **Data Type**: double

### 16. Media Collegati (`mediaCollegatiFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 16.1. Titolo (`titoloMediaCollegatiField`) 
- **Data Type**: string
- **Input Control**: text

#### 16.2. URL (`urlMediaCollegatiField`) 
- **Data Type**: string
- **Input Control**: text


### 17. META (`metaFieldset`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 17.1. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text

#### 17.2. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text


### 18. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

### 19. Funzionalità (evolutive) (`funzionalitaEvolutiveFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 19.1. Id funzionalità (`idFunzionalitaField`) 
- **Data Type**: string
- **Input Control**: text

#### 19.2. Attributo (`attributoField`) 
- **Data Type**: string
- **Input Control**: text


## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Categoria Camera RM](../../categories/categoria-camera-rm.md)** (`11098823`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
## Custom fields
- **[ipa_code contenuto](../../customFields/ipa-code-contenuto.md)**
- **[external ref](../../customFields/external-ref.md)**
- **[credits](../../customFields/credits.md)**
- **[srcId](../../customFields/srcid.md)**
- **[channel](../../customFields/channel.md)**
- **[parentId](../../customFields/parentid.md)**
