# Tappa itinerario RM

## Description
[OntoReMa] Punto o sotto-itinerario significativo all'interno di un itinerario turistico.
## General Information
- **ID**: 8273166
- **Site ID**: 52189
- **Created**: 17-04-2024 10:54
- **Last Modified**: 17-02-2025 09:00

## Content Structure Fields
### 1. Nome della tappa dell'itinerario (`nomeDellaTappaDellItinerarioField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Testo (`testoField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. Posizione paragrafo (`posizioneParagrafoField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: integer

### 4. Sottotitolo (`sottotitoloField`) 
- **Data Type**: string
- **Input Control**: text

### 5. Immagine principale (`immaginePrincipaleMedia`) 
- **Data Type**: document

### 6. Altra immagine (`altraImmagineMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 7. Media (`mediaMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 8. Evento (`eventoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Evento RM](../../contentStructure/evento-rm/README.md)**

### 9. Destinazione (`destinazioneWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

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

### 14. LINK (`linkTappaItinerarioFieldset`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 14.1. Nome del link (`nomeDelLinkField`) 
- **Data Type**: string
- **Input Control**: text

#### 14.2. Descrizione (`descrizioneLinkField`) 
- **Data Type**: string

#### 14.3. Url esterno del link (`urlEsternoDelLikField`) 
- **Data Type**: string
- **Input Control**: text


### 15. Offerta (`offertaWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Offerta RM](../../contentStructure/offerta-rm/README.md)**

### 16. Servizio Privato (`servizioPrivatoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Servizio Privato](../../contentStructure/servizio-privato/README.md)**

### 17. Servizio Pubblico (`servizioPubblicoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Servizio Pubblico](../../contentStructure/servizio-pubblico/README.md)**

### 18. Prodotto Tipico (`prodottoTipicoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Prodotto tipico](../../contentStructure/prodotto-tipico/README.md)**

### 19. Guida (`guidaWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Guida](../../contentStructure/guida/README.md)**

### 20. Operatore (`operatoreWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Operatore](../../contentStructure/operatore/README.md)**

### 21. Punto Vendita (`puntoVenditaWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Punto Vendita](../../contentStructure/punto-vendita/README.md)**

### 22. Ristorante (`ristoranteWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Ristorante](../../contentStructure/ristorante/README.md)**

### 23. Cantina (`cantinaWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Cantina](../../contentStructure/cantina/README.md)**

### 24. Vini e Distillati (`viniEDistillatiWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Vini e distillati](../../contentStructure/vini-e-distillati/README.md)**

### 25. Presidio SlowFood (`presidioSlowfoodWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent

### 26. Ricetta (`ricettaWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Ricetta](../../contentStructure/ricetta/README.md)**

### 27. Agriturismo (`agriturismoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Agriturismo](../../contentStructure/agriturismo/README.md)**

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Categoria Tappa Itinerario RM](../../categories/categoria-tappa-itinerario-rm.md)** (`10346467`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
