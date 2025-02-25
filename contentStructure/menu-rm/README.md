# Menu RM

## Description
Lista di piatti e bevande offerti da un ristorante o agriturismo.
## General Information
- **ID**: 8272763
- **Site ID**: 52189
- **Created**: 17-04-2024 10:22
- **Last Modified**: 17-02-2025 08:57

## Content Structure Fields
### 1. Descrizione (`descrizioneField`) 
- **Data Type**: string

### 2. Media (`mediaMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 3. Prezzo (`prezzoField`) 
- **Data Type**: double

### 4. Valuta (`valutaField`) 
- **Data Type**: string
- **Input Control**: text

### 5. Sezione (`sezioneFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 5.1. Nome (`nomeSezioneField`) 
- **Data Type**: string
- **Input Control**: text

#### 5.2. Item (`itemFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
##### 📁 Nested Fields
##### 5.2.1. Prezzo (`prezzoItemField`) 
- **Data Type**: double

##### 5.2.2. Nome (`nomeItemField`) 
- **Data Type**: string
- **Input Control**: text

##### 5.2.3. Descrizione (`descrizioneItemField`) 
- **Data Type**: string

##### 5.2.4.  Valuta (`valutaItemField`) 
- **Data Type**: string
- **Input Control**: text

##### 5.2.5. Immagine (`immagineItemField`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document


#### 5.3. Immagine (`immagineSezioneMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document


### 6. Url (`urlSezioneField`) 
- **Data Type**: string
- **Input Control**: text

### 7. Destinazione (`destinazioneWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 8. Latitudine (`latitudineField`) 
- **Data Type**: double

### 9. Longitudine (`longitudineField`) 
- **Data Type**: double

### 10. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 10.1. Chiave (`chiaveFieldset`) 
- **Data Type**: string
- **Input Control**: text

#### 10.2. Valore (`valoreFieldset`) 
- **Data Type**: string
- **Input Control**: text


### 11. Funzionalità (Evolutive) (`funzionalitaEvolutiveFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 11.1. Id funzionalità (`idFunzionalitaField`) 
- **Data Type**: string
- **Input Control**: text

#### 11.2. Attributo (`attributoField`) 
- **Data Type**: string
- **Input Control**: text

#### 11.3. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text


## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Categoria Menù RM](../../categories/categoria-menù-rm.md)** (`11098803`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
## Custom fields
- **[ipa_code contenuto](../../customFields/ipa-code-contenuto.md)**
- **[external ref](../../customFields/external-ref.md)**
- **[credits](../../customFields/credits.md)**
- **[srcId](../../customFields/srcid.md)**
- **[channel](../../customFields/channel.md)**
- **[parentId](../../customFields/parentid.md)**
