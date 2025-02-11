# Offerta

## Description

## General Information
- **ID**: 52995
- **Site ID**: 52189
- **Created**: 02-11-2022 14:53
- **Last Modified**: 11-07-2023 08:21

## Content Structure Fields
### 1. Offerta (`offerOffer`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 1.1. Nome offerta (`offerOfferName`) 
- **Data Type**: string
- **Input Control**: text

#### 1.2. Descrizione (`offerOfferDescription`) 
- **Data Type**: string

#### 1.3. Dettaglio prezzo (`offerOfferPriceDetail`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
##### 📁 Nested Fields
##### 1.3.1. Prezzo (`offerOfferPriceDetailPrice`) 
- **Data Type**: double

##### 1.3.2. Pax (`offerOfferPriceDetailPax`) 
- **Data Type**: string
- **Input Control**: text

##### 1.3.3. Regioni ammissibili (`offerOfferPriceDetailInEligibleRegions`) 
- **Data Type**: string
- **Input Control**: text

##### 1.3.4. Quantità ammissibile (`offerOfferPriceDetailEligibleQuantity`) 
- **Data Type**: 
###### 📁 Nested Fields
###### 1.3.4.1. Unità di misura (`offerOfferPriceDetailEligibleQuantityUnitOfMeasurement`) 
- **Data Type**: string
- **Input Control**: text

###### 1.3.4.2. Valore (`offerOfferPriceDetailEligibleQuantityValue`) 
- **Data Type**: integer


##### 1.3.5. Nome (`offerOfferPriceDetailName`) 
- **Data Type**: string
- **Input Control**: text

##### 1.3.6. Durata (`offerOfferPriceDetailDuration`) 
- **Data Type**: 
###### 📁 Nested Fields
###### 1.3.6.1. Unità di misura (`offerOfferPriceDetailDurationUnitOfMeasurement`) 
- **Data Type**: string
- **Input Control**: text

###### 1.3.6.2. Valore (`offerOfferPriceDetailDurationValue`) 
- **Data Type**: string
- **Input Control**: text


##### 1.3.7. Valuta (`offerOfferPriceDetailPriceCurrency`) 
- **Data Type**: string
- **Input Control**: text

##### 1.3.8. Tipo utente (`offerOfferPriceDetailUserType`) 
- **Data Type**: 
###### 📁 Nested Fields
###### 1.3.8.1. Qualificato per (`offerOfferPriceDetailUserTypeEligibleFor`) 
- **Data Type**: string
- **Input Control**: text

###### 1.3.8.2. Non qualificato per (`offerOfferPriceDetailUserTypeNotEligibleFor`) 
- **Data Type**: string
- **Input Control**: text



#### 1.4. Validità (`offerOfferValidity`) 
- **Data Type**: 
##### 📁 Nested Fields
##### 1.4.1. Valido da (`offerOfferValidityValidFrom`) 
- **Data Type**: date

##### 1.4.2. Valido a (`offerOfferValidityValidTo`) 
- **Data Type**: date


#### 1.5. Fascia di prezzo (`offerOfferPriceRange`) 
- **Data Type**: string
- **Input Control**: text

#### 1.6. Metodi di pagamento (`offerOfferPaymentMethods`) 
- **Data Type**: string
- **Input Control**: text

#### 1.7. Categoria (`offerCategory`) 
- **Data Type**: string
- **Input Control**: text

#### 1.8. Destinazione (`offerOfferDestinationID`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Destinazione](../../contentStructure/destinazione/README.md)**
    - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**


### 2. Funzionalità (Evolutive) (`offerFeature`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 2.1. Id funzionalità (`offerFeatureId`) 
- **Data Type**: string
- **Input Control**: text

#### 2.2. Attributo (`offerFeatureValue`) 
- **Data Type**: string
- **Input Control**: text


### 3. ID Esterno (`offerExternalId`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
