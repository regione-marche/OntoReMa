# Evento

## Description

## General Information
- **ID**: 52875
- **Site ID**: 52189
- **Created**: 02-11-2022 14:51
- **Last Modified**: 11-07-2023 08:17

## Content Structure Fields
### 1. Titolo (`eventTitle`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Descrizione (`eventDescription`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. Immagine (`eventImage`) ![Required](https://img.shields.io/badge/*Required-red.svg) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 4. Data di inizio dell'evento (`eventStartDate`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: date

### 5. Data di fine dell'evento (`eventEndDate`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: date

### 6. Template (`eventTemplate`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: select
#### Options
- Event: `opzione18969576`

### 7. Sottotitolo (`eventSubtitle`) 
- **Data Type**: string
- **Input Control**: text

### 8. Media (`eventMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 9. Evento virtuale (`eventIsVirtual`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 10. Organizzatore dell'evento (`eventAgent`) 
- **Data Type**: string
- **Input Control**: text

### 11. Orario di apertura (`eventOpeningHours`) 
- **Data Type**: string
- **Input Control**: text

### 12. Prezzo (`eventPrice`) 
- **Data Type**: double

### 13. Servizi (`eventServices`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 13.1. Altri servizi (`eventServicesOtherServices`) 
- **Data Type**: string
- **Input Control**: text

#### 13.2. Lista di servizi (`eventServicesListOfServices`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: select
##### Options
- Disabilità fisiche: `opzione37046438`
- Ascensore: `opzione58157855`
- Audioguide: `opzione48776225`
- Baby area: `opzione55758046`
- Bus: `opzione65565544`
- Deposito bagagli: `opzione48917920`
- Disabilità cognitive: `opzione12953512`
- Disabilità uditive: `opzione95861322`
- Disabilità visive: `opzione31187046`
- Guardaroba: `opzione41519624`
- Info: `opzione35272954`
- Noleggio bici: `opzione72146457`
- Parcheggio: `opzione53812191`
- Pet: `opzione85487753`
- Ristoro: `opzione73000195`
- Servizi igienici: `opzione08187094`
- Shop: `opzione61081120`
- Visite guidate: `opzione69525989`
- Wifi: `opzione87748755`
- Camere non fumatori: `opzione93257164`
- Disponibilità di camere familiari: `opzione65793009`
- Reception 24 ore su 24: `opzione39866954`
- Animali ammessi: `opzione59893611`
- Palestra: `opzione77696520`
- Navetta aeroportuale: `opzione52236012`
- Servizio in camera: `opzione31210060`
- Camere strutture per ospiti disabili: `opzione76005015`
- Ristorante: `opzione48871742`
- Spa: `opzione19869346`
- Piscina: `opzione47336506`
- Stazione di ricarica per veicoli elettrici: `opzione58029908`
- Menu bambini: `opzione74900438`
- Lingue parlate tedesco: `opzione87985804`
- Lingue parlate francese: `opzione71382562`
- Lingue parlate spagnolo: `opzione14957714`
- Lingue parlate inglese: `opzione18064740`
- Lingue parlate russo: `opzione00197673`
- Lingue parlate italiano: `opzione95542842`
- Lingue parlate cinese: `opzione04967507`
- Bagno per disabili: `opzione15471550`
- Area fumatori: `opzione44104646`


### 14. Sponsor (`eventSponsor`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 14.1. Nome dello sponsor (`eventSponsorName`) 
- **Data Type**: string
- **Input Control**: text

#### 14.2. Url dello sponsor (`eventSponsorIcon`) 
- **Data Type**: string
- **Input Control**: text


### 15. Destinazione (`eventLinkedDestination`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione](../../contentStructure/destinazione/README.md)**
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 16. Url (`eventUrl`) 
- **Data Type**: string
- **Input Control**: text

### 17. Paragrafo (`eventParagraph`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 17.1. Posizione del paragrafo (`eventParagraphParagraphOrder`) 
- **Data Type**: integer

#### 17.2. link (`eventParagraphHyperlink`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
##### 📁 Nested Fields
##### 17.2.1. Descrizione (`eventParagraphHyperlinkDescription`) 
- **Data Type**: string

##### 17.2.2. Url esterno (`eventParagraphHyperlinkExternalUrl`) 
- **Data Type**: string
- **Input Control**: text

##### 17.2.3. Nome del link (`eventParagraphHyperlinkName`) 
- **Data Type**: string
- **Input Control**: text


#### 17.3. Titolo del paragrafo (`eventParagraphParagraphTitle`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 17.4. Sottotitolo del paragrafo (`eventParagraphParagraphSubtitle`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 17.5. Testo del paragrafo (`eventParagraphParagraphText`) 
- **Data Type**: string

#### 17.6. Autore (`eventParagraphAuthor`) 
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Autore](../../contentStructure/autore/README.md)**

#### 17.7. Immagine (`eventParagraphImage`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 17.8. Media (`eventParagraphMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 17.9. Evento (`eventParagraphEventID`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Evento](../../contentStructure/evento/README.md)**
    - **[MeW Evento](../../contentStructure/mew-evento/README.md)**
    - **[Evento DVAT](../../contentStructure/evento-dvat/README.md)**
    - **[Evento RM](../../contentStructure/evento-rm/README.md)**


### 18. Funzionalità (evolutive) (`eventFeature`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 18.1. Id funzionalità (`eventFeatureId`) 
- **Data Type**: string
- **Input Control**: text

#### 18.2. Attributo (`eventFeatureValue`) 
- **Data Type**: string
- **Input Control**: text


### 19. ID Esterno (`eventExternalId`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Evento](../../categories/evento.md)** (`54317`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
