# Interesse RM

## Description
Attrazione o punto di interesse in una destinazione turistica.
## General Information
- **ID**: 8272700
- **Site ID**: 52189
- **Created**: 17-04-2024 10:06
- **Last Modified**: 17-02-2025 08:56

## Content Structure Fields
### 1. Titolo dell'interesse (`titoloDellInteresseField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Descrizione (`descrizioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. URL contenuto (`urlContenutoField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 4. Template da riempire per la tipologia di  chiamata (`templateDaRiempirePerLaTipologiaDiChiamataField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: select
#### Options
- Article: `opzione13910033`

### 5. Destinazione (`destinazioneWebContent`) ![Required](https://img.shields.io/badge/*Required-red.svg) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 6. Latitudine (`latitudineField`) 
- **Data Type**: double

### 7. Longitudine (`longitudineField`) 
- **Data Type**: integer

### 8. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 8.1. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text

#### 8.2. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text


### 9. Sovratitolo dell'interesse (`sovratitoloDellInteresseField`) 
- **Data Type**: string
- **Input Control**: text

### 10. Sottotitolo dell'interesse (`sottotitoloDellInteresse`) 
- **Data Type**: string
- **Input Control**: text

### 11. Articolo contiene degli eventi (`articoloContieneEventiField`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 12. Articolo (`articoloInteresseFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 12.1. Autore (`autoreArticoloWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent

#### 12.2. Link (`interestArticleHyperLink`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
##### 📁 Nested Fields
##### 12.2.1. Descrizione (`descrizioneLinkArticoloField`) 
- **Data Type**: string

##### 12.2.2. Url esterno link (`urlEsternoArticoloField`) 
- **Data Type**: string
- **Input Control**: text

##### 12.2.3. Nome del link (`nomeDelLinkArticoloField`) 
- **Data Type**: string
- **Input Control**: text


#### 12.3. Testo dell'articolo (`testoDellArticoloField`) 
- **Data Type**: string

#### 12.4. Immagine (`immagineArticoloMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 12.5. Media (`mediaArticoloMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 12.6. Destinazione (`destinazioneArticoloWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**


### 13. Paragrafo (`paragrafoFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 13.1. Link (`linkParagrafoFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
##### 📁 Nested Fields
##### 13.1.1. Descrizione (`descrizioneLinkField`) 
- **Data Type**: string

##### 13.1.2. Url esterno link (`urlEsternoField`) 
- **Data Type**: string
- **Input Control**: text

##### 13.1.3. Nome del link (`nomeDelLinkField`) 
- **Data Type**: string
- **Input Control**: text


#### 13.2. Testo del paragrafo (`testoDelParagrafoField`) 
- **Data Type**: string

#### 13.3. Inserire qui il titolo del paragrafo (`titoloDelParagrafoField`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 13.4. Autore (`autoreParagrafoWebContent`) 
- **Data Type**: structuredContent

#### 13.5. Sottotitolo paragrafo (`sottotitoloDelParagrafoField`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 13.6. Posizione paragrafo (`posizioneDelParagrafoField`) 
- **Data Type**: integer

#### 13.7. Immagine (`immagineParagrafoMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 13.8. Media (`mediaParagrafoMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 13.9. Destinazione (`destinazioneParagrafoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**


### 14. sponsor (`sponsorInteresseFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 14.1. Nome dello sponsor (`nomeDelloSponsorField`) 
- **Data Type**: string
- **Input Control**: text

#### 14.2. Url dello sponsor (`urlDelloSponsorField`) 
- **Data Type**: string
- **Input Control**: text


### 15. Risorsa (`risorsaInteresseFieldset`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 15.1. Nome della risorsa (`nomeDellaRisorsaField`) 
- **Data Type**: string
- **Input Control**: text

#### 15.2. Descrizione (`descrizioneRisorsaField`) 
- **Data Type**: string

#### 15.3. Inserire l'url della risorsa (`urlDellaRisorsaField`) 
- **Data Type**: string
- **Input Control**: text


### 16. Tempo di lettura (`tempoDiLetturaField`) 
- **Data Type**: integer

### 17. Funzionalità (Evolutive) (`funzionalitaEvolutiveFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 17.1. Id funzionalità (`idFunzionalitaField`) 
- **Data Type**: string
- **Input Control**: text

#### 17.2. Attributo della funzionalità (`attributoField`) 
- **Data Type**: string
- **Input Control**: text


### 18. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Categoria Interesse](../../categories/categoria-interesse.md)** (`10346468`) 
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Categoria Interesse RM](../../categories/categoria-interesse-rm.md)** (`11098815`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
## Custom fields
- **[ipa_code contenuto](../../customFields/ipa-code-contenuto.md)**
- **[external ref](../../customFields/external-ref.md)**
- **[credits](../../customFields/credits.md)**
- **[srcId](../../customFields/srcid.md)**
- **[channel](../../customFields/channel.md)**
- **[parentId](../../customFields/parentid.md)**
