# Offerta RM

## Description
Pacchetto o servizio speciale proposto all'interno di una destinazione.
## General Information
- **ID**: 8272818
- **Site ID**: 52189
- **Created**: 17-04-2024 10:28
- **Last Modified**: 17-02-2025 08:57

## Content Structure Fields
### 1. Nome offerta (`nomeDellOffertaField`) 
- **Data Type**: string
- **Input Control**: text

### 2. Descrizione (`descrizioneField`) 
- **Data Type**: string

### 3. Fascia di prezzo (`fasciaDiPrezzoField`) 
- **Data Type**: string
- **Input Control**: text

### 4. Metodi di pagamento (`metodiDiPagamentoField`) 
- **Data Type**: string
- **Input Control**: text

### 5. Validità (`validitaFielset`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 5.1. Valido da (`validoDaField`) 
- **Data Type**: date

#### 5.2. Valido a (`validoAField`) 
- **Data Type**: date


### 6. Categoria (`categoriaField`) 
- **Data Type**: string
- **Input Control**: text

### 7. Dettaglio prezzo (`dettaglioPrezzoFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 7.1. Prezzo (`prezzoField`) 
- **Data Type**: double

#### 7.2. Pax (`paxField`) 
- **Data Type**: string
- **Input Control**: text

#### 7.3. Regioni ammissibili (`regioniAmmissibiliField`) 
- **Data Type**: string
- **Input Control**: text

#### 7.4. Quantità ammissibile (`quantitaAmmisibileFieldset`) 
- **Data Type**: 
##### 📁 Nested Fields
##### 7.4.1. Unità di misura (`unitaDiMisuraField`) 
- **Data Type**: string
- **Input Control**: text

##### 7.4.2. Valore (`valoreQuantitaField`) 
- **Data Type**: integer


#### 7.5. Nome (`nomeField`) 
- **Data Type**: string
- **Input Control**: text

#### 7.6. Durata (`durataFieldset`) 
- **Data Type**: 
##### 📁 Nested Fields
##### 7.6.1. Unità di misura (`unitaDiMisuraDurataField`) 
- **Data Type**: string
- **Input Control**: text

##### 7.6.2. Valore (`valoreDurataField`) 
- **Data Type**: string
- **Input Control**: text


#### 7.7. Valuta (`valutaField`) 
- **Data Type**: string
- **Input Control**: text

#### 7.8. Tipo utente (`tipoUtenteFieldset`) 
- **Data Type**: 
##### 📁 Nested Fields
##### 7.8.1. Qualificato per (`qualificatoPerField`) 
- **Data Type**: string
- **Input Control**: text

##### 7.8.2. Non qualificato per (`nonQualificatoPerField`) 
- **Data Type**: string
- **Input Control**: text



### 8. Destinazione (`destinazioneWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 9. Operatore (`operatoreWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Operatore](../../contentStructure/operatore/README.md)**

### 10. Latitudine (`latitudineField`) 
- **Data Type**: double

### 11. Longitudine (`longitudineField`) 
- **Data Type**: double

### 12. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 12.1. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text

#### 12.2. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text


### 13. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

### 14. Funzionalità (Evolutive) (`funzionalitaEvolutiveFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 14.1. Id funzionalità (`idFunzionalitaField`) 
- **Data Type**: string
- **Input Control**: text

#### 14.2. Attributo (`attributoField`) 
- **Data Type**: string
- **Input Control**: text


## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Categoria Offerta RM](../../categories/categoria-offerta-rm.md)** (`11098822`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
