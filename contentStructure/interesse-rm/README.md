# Interesse RM

## Description
Approfondimento su un contenuto già presente, come una o più destinazioni (es: le 10 migliori destinazioni del comune di XXXX)
## General Information
- **ID**: 8272700
- **Site ID**: 52189
- **Created**: 17-04-2024 10:06
- **Last Modified**: 08-05-2025 15:39

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

### 6. Evento (`eventoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Evento RM](../../contentStructure/evento-rm/README.md)**

### 7. Itinerario (`itinerarioWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Itinerario RM](../../contentStructure/itinerario-rm/README.md)**
  - **[Tappa itinerario RM](../../contentStructure/tappa-itinerario-rm/README.md)**

### 8. Latitudine (`latitudineField`) 
- **Data Type**: double

### 9. Longitudine (`longitudineField`) 
- **Data Type**: integer

### 10. Media Collegati (`mediaCollegatiFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 10.1. Titolo (`titoloMediaCollegatiField`) 
- **Data Type**: string
- **Input Control**: text

#### 10.2. URL (`urlMediaCollegatiField`) 
- **Data Type**: string
- **Input Control**: text


### 11. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 11.1. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text

#### 11.2. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text


### 12. Sovratitolo dell'interesse (`sovratitoloDellInteresseField`) 
- **Data Type**: string
- **Input Control**: text

### 13. Sottotitolo dell'interesse (`sottotitoloDellInteresse`) 
- **Data Type**: string
- **Input Control**: text

### 14. Articolo contiene degli eventi (`articoloContieneEventiField`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 15. Articolo (`articoloInteresseFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 15.1. Autore (`autoreArticoloWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent

#### 15.2. Link (`interestArticleHyperLink`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
##### 📁 Nested Fields
##### 15.2.1. Descrizione (`descrizioneLinkArticoloField`) 
- **Data Type**: string

##### 15.2.2. Url esterno link (`urlEsternoArticoloField`) 
- **Data Type**: string
- **Input Control**: text

##### 15.2.3. Nome del link (`nomeDelLinkArticoloField`) 
- **Data Type**: string
- **Input Control**: text


#### 15.3. Testo dell'articolo (`testoDellArticoloField`) 
- **Data Type**: string

#### 15.4. Immagine (`immagineArticoloMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 15.5. Media (`mediaArticoloMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 15.6. Destinazione (`destinazioneArticoloWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**


### 16. Paragrafo (`paragrafoFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 16.1. Link (`linkParagrafoFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
##### 📁 Nested Fields
##### 16.1.1. Descrizione (`descrizioneLinkField`) 
- **Data Type**: string

##### 16.1.2. Url esterno link (`urlEsternoField`) 
- **Data Type**: string
- **Input Control**: text

##### 16.1.3. Nome del link (`nomeDelLinkField`) 
- **Data Type**: string
- **Input Control**: text


#### 16.2. Testo del paragrafo (`testoDelParagrafoField`) 
- **Data Type**: string

#### 16.3. Inserire qui il titolo del paragrafo (`titoloDelParagrafoField`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 16.4. Autore (`autoreParagrafoWebContent`) 
- **Data Type**: structuredContent

#### 16.5. Sottotitolo paragrafo (`sottotitoloDelParagrafoField`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 16.6. Posizione paragrafo (`posizioneDelParagrafoField`) 
- **Data Type**: integer

#### 16.7. Immagine (`immagineParagrafoMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 16.8. Media (`mediaParagrafoMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 16.9. Destinazione (`destinazioneParagrafoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**


### 17. sponsor (`sponsorInteresseFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 17.1. Nome dello sponsor (`nomeDelloSponsorField`) 
- **Data Type**: string
- **Input Control**: text

#### 17.2. Url dello sponsor (`urlDelloSponsorField`) 
- **Data Type**: string
- **Input Control**: text


### 18. Risorsa (`risorsaInteresseFieldset`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 18.1. Nome della risorsa (`nomeDellaRisorsaField`) 
- **Data Type**: string
- **Input Control**: text

#### 18.2. Descrizione (`descrizioneRisorsaField`) 
- **Data Type**: string

#### 18.3. Inserire l'url della risorsa (`urlDellaRisorsaField`) 
- **Data Type**: string
- **Input Control**: text


### 19. Tempo di lettura (`tempoDiLetturaField`) 
- **Data Type**: integer

### 20. Funzionalità (Evolutive) (`funzionalitaEvolutiveFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 20.1. Id funzionalità (`idFunzionalitaField`) 
- **Data Type**: string
- **Input Control**: text

#### 20.2. Attributo della funzionalità (`attributoField`) 
- **Data Type**: string
- **Input Control**: text


### 21. Area di interesse (`areaDiInteresseField`) 
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
- **[ipa_code_contenuto](../../customFields/ipa-code-contenuto.md)**
- **[credits](../../customFields/credits.md)**
- **[external_ref](../../customFields/external-ref.md)**
- **[srcId](../../customFields/srcid.md)**
- **[channel](../../customFields/channel.md)**
- **[parentId](../../customFields/parentid.md)**
