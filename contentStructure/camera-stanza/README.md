# Camera (stanza)

## Description

## General Information
- **ID**: 52819
- **Site ID**: 52189
- **Created**: 02-11-2022 14:51
- **Last Modified**: 18-05-2023 12:27

## Content Structure Fields
### 1. Tipologia di camera (`roomRoomType`) 
- **Data Type**: string
- **Input Control**: text

### 2. Occupazione (stato) della camera (`roomOccupacy`) 
- **Data Type**: string
- **Input Control**: text

### 3. Sistemazione della camera (`roomAccomodationRoom`) 
- **Data Type**: string
- **Input Control**: text

### 4. Disponibilità dal (`roomAvailableFrom`) 
- **Data Type**: date

### 5. Disponibilità al (`roomAvailableTo`) 
- **Data Type**: date

### 6. Numero di camere (`roomNumberOfRooms`) 
- **Data Type**: integer

### 7. Tipologia di letto (`roomTipeOfBed`) 
- **Data Type**: string
- **Input Control**: text

### 8. Aria Condizionata (`roomAirConditioning`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 9. Cassetta di sicurezza (`roomSafeDepositBox`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 10. Angolo cottura (`roomKitchenette`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 11. Jacuzzi (`roomJacuzzi`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 12. ID hotel (`roomHotelId`) 
- **Data Type**: string
- **Input Control**: text

### 13. Destinazione (`roomDestinationID`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione](../../contentStructure/destinazione/README.md)**
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 14. Funzionalità (evolutive) (`roomFeature`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 14.1. Id funzionalità (`roomFeatureId`) 
- **Data Type**: string
- **Input Control**: text

#### 14.2. Attributo (`roomFeatureValue`) 
- **Data Type**: string
- **Input Control**: text


### 15. ID Esterno (`roomExternalId`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
