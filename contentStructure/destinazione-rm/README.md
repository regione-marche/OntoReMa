# Destinazione RM

## Description
Località di interesse turistico che offre una serie di servizi ed esperienze per i visitatori.
## General Information
- **ID**: 8272607
- **Site ID**: 52189
- **Created**: 17-04-2024 09:57
- **Last Modified**: 17-02-2025 08:54

## Content Structure Fields
### 1. Nome destinazione (`nomeDestinazioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Descrizione (`descrizioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. Immagine principale (`immaginePrincipaleMedia`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: document

### 4. Altra immagine (`altraImmagineMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 5. Template da riempire per la tipologia di chiamata  (`templateDaRiempirePerLaTipologiaDiChiamataField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: select
#### Options
- POI: `opzione75328556`
- Destination: `opzione55578459`
-  City: `opzione42832333`
- Region: `opzione06237421`

### 6. Descrizione breve (`descrizioneBreveField`) 
- **Data Type**: string

### 7. Descrizione lunga (`descrizioneLungaField`) 
- **Data Type**: string

### 8. Media (`mediaMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 9. Proprietario (`proprietarioField`) 
- **Data Type**: string
- **Input Control**: text

### 10. Email (`emailField`) 
- **Data Type**: string
- **Input Control**: text

### 11. Telefono (`telefonoField`) 
- **Data Type**: string
- **Input Control**: text

### 12. Sito web (`sitoWebField`) 
- **Data Type**: string
- **Input Control**: text

### 13. Social (`socialFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 13.1. Nome social (`nomeSocialField`) 
- **Data Type**: string
- **Input Control**: select
##### Options
- X: `opzione24730734`
- Facebook: `opzione03042080`
- Youtube: `opzione95247048`
- Instagram: `opzione65763479`

#### 13.2. URL (`urlSocialField`) 
- **Data Type**: string
- **Input Control**: text


### 14. Indirizzo (`indirizzoFieldset`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 14.1. CAP (`capField`) 
- **Data Type**: string
- **Input Control**: text

#### 14.2. Nazione (`nazioneField`) 
- **Data Type**: string
- **Input Control**: text

#### 14.3. Toponimo (`toponimoField`) 
- **Data Type**: string
- **Input Control**: text

#### 14.4. Provincia (`provinciaField`) 
- **Data Type**: string
- **Input Control**: text

#### 14.5. Città (`cittaField`) 
- **Data Type**: string
- **Input Control**: text

#### 14.6. Quartiere (`quartiereField`) 
- **Data Type**: string
- **Input Control**: text

#### 14.7. Regione (`regioneField`) 
- **Data Type**: string
- **Input Control**: text

#### 14.8. Nome della strada (`nomeDellaStradaField`) 
- **Data Type**: string
- **Input Control**: text

#### 14.9. Numero civico (`numeroCivicoField`) 
- **Data Type**: string
- **Input Control**: text

#### 14.10. Indirizzo completo (`indirizzoCompletoField`) 
- **Data Type**: string
- **Input Control**: text

#### 14.11. Codice ISTAT (`codiceIstatField`) 
- **Data Type**: string
- **Input Control**: text


### 15. Designazione geografica (`designazioneGeograficaField`) 
- **Data Type**: string
- **Input Control**: select
#### Options
- APAC: `opzione65621616`
- LATAM: `opzione92184795`
- EMEA: `opzione17755265`
- SEMEA: `opzione74789223`
- MEMEA: `opzione77589039`
- IMEA: `opzione25651436`

### 16. Area geografica (`areaGeograficaField`) 
- **Data Type**: string
- **Input Control**: select
#### Options
- Nordest: `opzione65621616`
- Isole: `opzione30209894`
- Sud: `opzione70178247`
- Nordovest: `opzione52490993`
- Centro: `opzione82511210`
- Nord: `opzione13582609`

### 17. Latitudine (`latitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 18. Longitudine (`longitudineField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 19. Altitudine (`altitudineField`) 
- **Data Type**: string
- **Input Control**: text

### 20. Tipo di geometria (`tipoDiGeometriaField`) 
- **Data Type**: string
- **Input Control**: select
#### Options
- Poligono: `opzione65621616`
- Punto: `opzione40864765`
- Linea: `opzione63498126`
- Box: `opzione26385764`

### 21. Sistema di riferimento coordinate (`sistemaDiRiferimentoCoordinateField`) 
- **Data Type**: string
- **Input Control**: text

### 22. Orario di apertura (`orarioDiAperturaField`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

### 23. Stato della destinazione (`statoDellaDestinazioneField`) 
- **Data Type**: string
- **Input Control**: text

### 24. Tema della destinazione (`temaDellaDestinazioneField`) 
- **Data Type**: string
- **Input Control**: text

### 25. Servizi (`serviziFieldset`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 25.1. Eventuali altri servizi (`eventualiAltriServiziField`) 
- **Data Type**: string
- **Input Control**: text

#### 25.2. Lista di servizi (`listaDiServiziField`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: select
##### Options
- Disabilità fisiche: `opzione79773620`
- Ascensore: `opzione28517561`
- Audioguide: `opzione14160672`
- Baby area: `opzione36800979`
- Bus: `opzione12523350`
- Deposito bagagli: `opzione06509574`
- Disabilità cognitive: `opzione71637851`
- Disabilità uditive: `opzione94625448`
- Disabilità visive: `opzione80769587`
- Guardaroba: `opzione95594494`
- Info: `opzione25263045`
- Noleggio bici: `opzione34362636`
- Parcheggio: `opzione40987858`
- Pet: `opzione54115878`
- Ristoro: `opzione72117612`
- Servizi igienici: `opzione07437600`
- Shop: `opzione97973292`
- Visite guidate: `opzione22728168`
- Wifi: `opzione86972735`
- Camere non fumatori: `opzione20402169`
- Disponibilità di camere familiari: `opzione73916444`
- Reception 24 ore su 24: `opzione13083734`
- Animali ammessi: `opzione03414068`
- Palestra: `opzione32727657`
- Navetta aeroportuale: `opzione44737570`
- Servizio in camera: `opzione74198689`
- Camere strutture per ospiti disabili: `opzione37718899`
- Ristorante: `opzione24857305`
- Spa: `opzione17184322`
- Piscina: `opzione80074988`
- Stazione di ricarica per veicoli elettrici: `opzione26055039`
- Menu bambini: `opzione54441972`
- Lingue parlate tedesco: `opzione77161131`
- Lingue parlate francese: `opzione06799139`
- Lingue parlate spagnolo: `opzione09554468`
- Lingue parlate inglese: `opzione29361812`
- Lingue parlate russo: `opzione49787984`
- Lingue parlate italiano: `opzione85182277`
- Lingue parlate cinese: `opzione11810510`
- Bagno per disabili: `opzione97532778`
- Area fumatori: `opzione90438301`


### 26. Servizio Privato (`servizioPrivatoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Servizio Privato](../../contentStructure/servizio-privato/README.md)**

### 27. Servizio Pubblico (`servizioPubblicoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Servizio Pubblico](../../contentStructure/servizio-pubblico/README.md)**

### 28. Destinazione (`destinazioneWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 29. Paragrafo (`paragrafoFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 29.1. Posizione (`posizioneDelParagrafoField`) 
- **Data Type**: integer

#### 29.2. Link (`linkParagrafoFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
##### 📁 Nested Fields
##### 29.2.1. Nome link (`nomeDelLinkField`) 
- **Data Type**: string
- **Input Control**: text

##### 29.2.2. Descrizione (`descrizioneLinkField`) 
- **Data Type**: string

##### 29.2.3. Url esterno link (`urlEsternoField`) 
- **Data Type**: string
- **Input Control**: text


#### 29.3. Testo paragrafo (`testoDelParagrafoField`) 
- **Data Type**: string

#### 29.4. Titolo paragrafo (`titoloDelParagrafoField`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 29.5. Sottotitolo paragrafo (`sottotitoloDelParagrafoField`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 29.6. Autore (`autoreParagrafoWebContent`) 
- **Data Type**: structuredContent

#### 29.7. Immagine (`immagineParagrafoMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 29.8. Media (`mediaParagrafoMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 29.9. Destinazione (`destinazioneParagrafoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**


### 30. Funzionalità (Evolutive) (`funzionalitaEvolutiveFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 30.1. Id funzionalità (`idFunzionalitaField`) 
- **Data Type**: string
- **Input Control**: text

#### 30.2. Attributo funzionalità (`attributoField`) 
- **Data Type**: string
- **Input Control**: text


### 31. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 31.1. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text

#### 31.2. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text


### 32. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Categoria Destinazione](../../categories/categoria-destinazione.md)** (`10346466`) 
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Categoria Destinazione RM](../../categories/categoria-destinazione-rm.md)** (`11098811`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
