# Destinazione

## Description

## General Information
- **ID**: 52841
- **Site ID**: 52189
- **Created**: 02-11-2022 14:51
- **Last Modified**: 11-07-2023 08:14

## Content Structure Fields
### 1. Nome destinazione (`destinationDestinationName`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Descrizione (`destinationDescription`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. Immagine (`destinationImage`) ![Required](https://img.shields.io/badge/*Required-red.svg) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 4. Template da riempire per la tipologia di chiamata  (`destinationTemplate`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: select
#### Options
- POI: `opzione75328556`
- Destination: `opzione55578459`
-  City: `opzione42832333`
- Region: `opzione06237421`

### 5. Descrizione breve (`destinationShortDescription`) 
- **Data Type**: string

### 6. Descrizione lunga (`destinationLongDescription`) 
- **Data Type**: string

### 7. Media (`destinationMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 8. Proprietario (`destinationOwner`) 
- **Data Type**: string
- **Input Control**: text

### 9. Email (`destinationEmail`) 
- **Data Type**: string
- **Input Control**: text

### 10. Telefono (`destinationPhoneNumber`) 
- **Data Type**: string
- **Input Control**: text

### 11. Sito web (`destinationWebsite`) 
- **Data Type**: string
- **Input Control**: text

### 12. Indirizzo (`destinationAddress`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 12.1. CAP (`destinationAddressZipCode`) 
- **Data Type**: string
- **Input Control**: text

#### 12.2. Nazione (`destinationAddressCountry`) 
- **Data Type**: string
- **Input Control**: text

#### 12.3. Toponimo (`destinationAddressStreetToponym`) 
- **Data Type**: string
- **Input Control**: text

#### 12.4. Provincia (`destinationAddressProvince`) 
- **Data Type**: string
- **Input Control**: text

#### 12.5. Città (`destinationAddressCity`) 
- **Data Type**: string
- **Input Control**: text

#### 12.6. Quartiere (`destinationAddressDistrict`) 
- **Data Type**: string
- **Input Control**: text

#### 12.7. Regione (`destinationAddressRegion`) 
- **Data Type**: string
- **Input Control**: text

#### 12.8. Nome della strada (`destinationAddressStreetName`) 
- **Data Type**: string
- **Input Control**: text

#### 12.9. Numero civico (`destinationAddressStreetNumber`) 
- **Data Type**: string
- **Input Control**: text

#### 12.10. Indirizzo completo (`destinationAddressFullAddress`) 
- **Data Type**: string
- **Input Control**: text


### 13. Designazione geografica (`destinationAddressArea`) 
- **Data Type**: string
- **Input Control**: select
#### Options
- APAC: `opzione65621616`
- LATAM: `opzione92184795`
- EMEA: `opzione17755265`
- SEMEA: `opzione74789223`
- MEMEA: `opzione77589039`
- IMEA: `opzione25651436`

### 14. Area geografica (`destinationGeoDistribution`) 
- **Data Type**: string
- **Input Control**: select
#### Options
- Nordest: `opzione65621616`
- Isole: `opzione30209894`
- Sud: `opzione70178247`
- Nordovest: `opzione52490993`
- Centro: `opzione82511210`
- Nord: `opzione13582609`

### 15. Geo Hook Separatore (`geoHookSeparator`) 
- **Data Type**: 

### 16. Latitudine (`destinationLatitude`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 17. Longitudine (`destinationLongitude`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 18. Altitudine (`destinationAltitude`) 
- **Data Type**: string
- **Input Control**: text

### 19. Tipo di geometria (`destinationGeometryType`) 
- **Data Type**: string
- **Input Control**: select
#### Options
- Poligono: `opzione65621616`
- Punto: `opzione40864765`
- Linea: `opzione63498126`
- Box: `opzione26385764`

### 20. Sistema di riferimento coordinate (`destinationCoordinateSystemRef`) 
- **Data Type**: string
- **Input Control**: text

### 21. Orario di apertura (`destinationOpeningHours`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

### 22. Stato della destinazione (`destinationDestinationStatus`) 
- **Data Type**: string
- **Input Control**: text

### 23. Tema della destinazione (`destinationTheme`) 
- **Data Type**: string
- **Input Control**: text

### 24. Servizi (`destinationServices`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 24.1. Eventuali altri servizi (`destinationServicesOtherServices`) 
- **Data Type**: string
- **Input Control**: text

#### 24.2. Lista di servizi (`destinationServicesListOfServices`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: select
##### Options
- Disabilità fisiche: `opzione75346294`
- Ascensore: `opzione76584600`
- Audioguide: `opzione55894399`
- Baby area: `opzione04812774`
- Bus: `opzione96645690`
- Deposito bagagli: `opzione33054212`
- Disabilità cognitive: `opzione18093837`
- Disabilità uditive: `opzione88651635`
- Disabilità visive: `opzione34754544`
- Guardaroba: `opzione16133400`
- Info: `opzione01170149`
- Noleggio bici: `opzione97944923`
- Parcheggio: `opzione57087998`
- Pet: `opzione86262060`
- Ristoro: `opzione57848070`
- Servizi igienici: `opzione24548590`
- Shop: `opzione59497429`
- Visite guidate: `opzione95234328`
- Wifi: `opzione01490206`
- Camere non fumatori: `opzione07493143`
- Disponibilità di camere familiari: `opzione08631567`
- Reception 24 ore su 24: `opzione27611412`
- Animali ammessi: `opzione43312089`
- Palestra: `opzione94224065`
- Navetta aeroportuale: `opzione68180274`
- Servizio in camera: `opzione91230379`
- Camere strutture per ospiti disabili: `opzione90064268`
- Ristorante: `opzione14367426`
- Spa: `opzione64383820`
- Piscina: `opzione59644202`
- Stazione di ricarica per veicoli elettrici: `opzione82355966`
- Menu bambini: `opzione71652211`
- Lingue parlate tedesco: `opzione85712298`
- Lingue parlate francese: `opzione36522479`
- Lingue parlate spagnolo: `opzione73828264`
- Lingue parlate inglese: `opzione54466288`
- Lingue parlate russo: `opzione99177810`
- Lingue parlate italiano: `opzione53763482`
- Lingue parlate cinese: `opzione93969322`
- Bagno per disabili: `opzione80988610`
- Area fumatori: `opzione52400658`


### 25. Destinazione (`destinationLinkedDestination`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione](../../contentStructure/destinazione/README.md)**
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 26. Paragrafo (`destinationParagraph`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 26.1. Posizione (`destinationParagraphParagraphOrder`) 
- **Data Type**: integer

#### 26.2. Link (`destinationParagraphHyperLink`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
##### 📁 Nested Fields
##### 26.2.1. Nome link (`destinationParagraphHyperLinkName`) 
- **Data Type**: string
- **Input Control**: text

##### 26.2.2. Descrizione (`destinationParagraphHyperLinkDescription`) 
- **Data Type**: string

##### 26.2.3. Url esterno link (`destinationParagraphHyperLinkExternalUrl`) 
- **Data Type**: string
- **Input Control**: text


#### 26.3. Testo paragrafo (`destinationParagraphParagraphText`) 
- **Data Type**: string

#### 26.4. Titolo paragrafo (`destinationParagraphParagraphTitle`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 26.5. Sottotitolo paragrafo (`destinationParagraphParagraphSubtitle`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 26.6. Autore (`destinationParagraphAuthor`) 
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Autore](../../contentStructure/autore/README.md)**

#### 26.7. Immagine (`destinationParagraphImage`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 26.8. Media (`destinationParagraphMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 26.9. Destinazione (`destinationParagraphDestinationID`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Destinazione](../../contentStructure/destinazione/README.md)**
    - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**


### 27. Funzionalità (Evolutive) (`destinationFeature`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 27.1. Id funzionalità (`destinationFeatureId`) 
- **Data Type**: string
- **Input Control**: text

#### 27.2. Attributo funzionalità (`destinationFeatureValue`) 
- **Data Type**: string
- **Input Control**: text


### 28. ID Esterno (`destinationExternalId`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Classificazione POI](../../categories/classificazione-poi.md)** (`56416`) 
- **[Luoghi di interesse culturale](../../categories/luoghi-di-interesse-culturale.md)** (`56441`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
