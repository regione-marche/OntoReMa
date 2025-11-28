# Ristorante

## Description
Struttura ristorativa che offre piatti e bevande al pubblico.
## General Information
- **ID**: 8272952
- **Site ID**: 52189
- **Created**: 17-04-2024 10:48
- **Last Modified**: 01-10-2025 13:57

## Content Structure Fields
### 1. Denominazione (`denominazioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Descrizione (`descrizioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. Indirizzo completo (`indirizzoCompletoField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 4. Contatto - Nominativo (`contattoNominativoField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 5. Telefono (`telefonoField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 6. Cellulare (`cellulareField`) 
- **Data Type**: string
- **Input Control**: text

### 7. Email (`emailField`) 
- **Data Type**: string
- **Input Control**: text

### 8. Sito Web (`sitoWebField`) 
- **Data Type**: string
- **Input Control**: text

### 9. Orario di apertura (`orarioDiAperturaField`) 
- **Data Type**: string
- **Input Control**: text

### 10. Servizi (`serviziField`) 
- **Data Type**: string
- **Input Control**: text

### 11. Menù (`menuWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent

### 12. Immagine Principale (`immaginePrincipaleMedia`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: document

### 13. Altra immagine (`altraImmagineMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 14. Operatore (`operatoreWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Operatore](../../contentStructure/operatore/README.md)**

### 15. Destinazione (`destinazioneWebContent`) 
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 16. Servizio Privato (`servizioPrivatoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Servizio Privato](../../contentStructure/servizio-privato/README.md)**

### 17. Prodotto Tipico (`prodottoTipicoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Prodotto tipico](../../contentStructure/prodotto-tipico/README.md)**

### 18. Vino (`vinoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent

### 19. Birra (`birraWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Birra](../../contentStructure/birra/README.md)**

### 20. Presidio SlowFood (`presidioSlowFoodWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent

### 21. Ricetta (`ricettaWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Ricetta](../../contentStructure/ricetta/README.md)**

### 22. Latitudine (`latitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 23. Longitudine (`longitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: double

### 24. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

### 25. SOCIAL (`socialFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 25.1. Nome social (`nomeSocialField`) 
- **Data Type**: string
- **Input Control**: select
##### Options
- Facebook: `opzione36713368`
- X: `opzione90797153`
- Instagram: `opzione98037736`

#### 25.2. URL (`urlSocialField`) 
- **Data Type**: string
- **Input Control**: text


### 26. Media Collegati (`mediaCollegatiFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 26.1. Titolo (`titoloMediaCollegatiField`) 
- **Data Type**: string
- **Input Control**: text

#### 26.2. URL (`urlMediaCollegatiField`) 
- **Data Type**: string
- **Input Control**: text


### 27. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 27.1. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text

#### 27.2. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text


## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Fascia di prezzo](../../categories/fascia-di-prezzo.md)** (`10338968`) 
- **[Stelle Michelin](../../categories/stelle-michelin.md)** (`10338984`) 
- **[Categoria Ristorante](../../categories/categoria-ristorante.md)** (`10338994`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Esigenze alimentari](../../categories/esigenze-alimentari.md)** (`10346224`) 
- **[Accessibilità](../../categories/accessibilità.md)** (`10346289`) 
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
## Custom fields
- **[ipa_code_contenuto](../../customFields/ipa-code-contenuto.md)**
- **[credits](../../customFields/credits.md)**
- **[external_ref](../../customFields/external-ref.md)**
- **[srcId](../../customFields/srcid.md)**
- **[channel](../../customFields/channel.md)**
- **[parentId](../../customFields/parentid.md)**
