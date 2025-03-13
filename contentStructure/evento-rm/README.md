# Evento RM

## Description
Occasione particolare organizzata in una determinata destinazione per promuovere cultura, intrattenimento o tradizione.
## General Information
- **ID**: 8272644
- **Site ID**: 52189
- **Created**: 17-04-2024 10:00
- **Last Modified**: 13-03-2025 09:37

## Content Structure Fields
### 1. Titolo (`titoloField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: text

### 2. Descrizione (`descrizioneField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string

### 3. Immagine Principale (`immaginePrincipaleMedia`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: document

### 4. Altra immagine (`altraImmagineMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 5. Data di inizio dell'evento (`dataDiInizioDellEventoField`) 
- **Data Type**: date

### 6. Data di fine dell'evento (`dataDiIFineDellEventoField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: date

### 7. Template (`templateField`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **Data Type**: string
- **Input Control**: select
#### Options
- Event: `opzione18969576`

### 8. Sottotitolo (`sottotitoloField`) 
- **Data Type**: string
- **Input Control**: text

### 9. Media (`mediaMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 10. Evento virtuale (`eventoVirtualeField`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 11. Evento ricorrente (`eventoRicorrenteField`) 
- **Data Type**: boolean
- **Input Control**: checkbox

### 12. Ricorrenza (`ricorrenzaField`) 
- **Data Type**: string
- **Input Control**: text

### 13. Organizzatore dell'evento (`organizzazioneDellEventoField`) 
- **Data Type**: string
- **Input Control**: text

### 14. Orario di apertura (`orarioDiAperturaField`) 
- **Data Type**: string
- **Input Control**: text

### 15. Stato dell'evento (`statoDellEventoField`) 
- **Data Type**: string
- **Input Control**: text

### 16. Prezzo (`prezzoField`) 
- **Data Type**: double

### 17. Info accessibilità (`infoAccessibilitaField`) 
- **Data Type**: string
- **Input Control**: text

### 18. Capacità massima (`capacitaMassimaField`) 
- **Data Type**: string
- **Input Control**: text

### 19. Modalità di partecipazione (`modalitaDiPartecipazioneField`) 
- **Data Type**: string
- **Input Control**: text

### 20. Link di registrazione (`linkDiRegistrazioneField`) 
- **Data Type**: string
- **Input Control**: text

### 21. Risorse scaricabili (`risorseScaricabiliMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

### 22. Eventi associati (`eventiAssociatiWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent

### 23. Macro evento (`macroEventoWebContent`) 
- **Data Type**: structuredContent

### 24. Area di interesse (`areaDiInteresseField`) 
- **Data Type**: string
- **Input Control**: text

### 25. Latitudine (`latitudineField`) 
- **Data Type**: double

### 26. Longitudine (`longitudineField`) 
- **Data Type**: double

### 27. Media Collegati (`mediaCollegatiFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 27.1. Titolo (`titoloMediaCollegatiField`) 
- **Data Type**: string
- **Input Control**: text

#### 27.2. URL (`urlMediaCollegatiField`) 
- **Data Type**: string
- **Input Control**: text


### 28. META (`metaFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 28.1. Chiave (`chiaveField`) 
- **Data Type**: string
- **Input Control**: text

#### 28.2. Valore (`valoreField`) 
- **Data Type**: string
- **Input Control**: text


### 29. Servizi (`serviziEventoFieldset`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 29.1. Altri servizi (`altriServiziField`) 
- **Data Type**: string
- **Input Control**: text

#### 29.2. Lista di servizi (`listaDiServiziField`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
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


### 30. Codice ISTAT (`codiceIstatField`) 
- **Data Type**: string
- **Input Control**: text

### 31. CAP (`capField`) 
- **Data Type**: string
- **Input Control**: text

### 32. Nazione (`nazioneField`) 
- **Data Type**: string
- **Input Control**: text

### 33. Toponimo (`toponimoField`) 
- **Data Type**: string
- **Input Control**: text

### 34. Regione (`regioneField`) 
- **Data Type**: string
- **Input Control**: text

### 35. Provincia (`provinciaField`) 
- **Data Type**: string
- **Input Control**: text

### 36. Provincia Estesa (`provinciaEstesaField`) 
- **Data Type**: string
- **Input Control**: text

### 37. Città (`cittaField`) 
- **Data Type**: string
- **Input Control**: text

### 38. Nome della strada (`nomeDellaStradaField`) 
- **Data Type**: string
- **Input Control**: text

### 39. Numero civico (`numeroCivicoField`) 
- **Data Type**: string
- **Input Control**: text

### 40. Indirizzo completo (`indirizzoCompletoField`) 
- **Data Type**: string
- **Input Control**: text

### 41. Denominazione (`denominazioneField`) 
- **Data Type**: string
- **Input Control**: text

### 42. Quartiere (`quartiereField`) 
- **Data Type**: string
- **Input Control**: text

### 43. Sponsor (`sponsorEventoFieldset`) 
- **Data Type**: 
#### 📁 Nested Fields
#### 43.1. Nome dello sponsor (`nomeDelloSponsorField`) 
- **Data Type**: string
- **Input Control**: text

#### 43.2. Url dello sponsor (`urlDelloSponsorField`) 
- **Data Type**: string
- **Input Control**: text


### 44. Destinazione (`destinazioneWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
  - **[Destinazione RM](../../contentStructure/destinazione-rm/README.md)**

### 45. Url (`urlField`) 
- **Data Type**: string
- **Input Control**: text

### 46. Paragrafo (`paragrafoFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 46.1. Posizione del paragrafo (`posizioneDelParagrafoField`) 
- **Data Type**: integer

#### 46.2. link (`linkParagrafoFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
##### 📁 Nested Fields
##### 46.2.1. Descrizione (`descrizioneLinkField`) 
- **Data Type**: string

##### 46.2.2. Url esterno (`urlEsternoField`) 
- **Data Type**: string
- **Input Control**: text

##### 46.2.3. Nome del link (`nomeDelLinkField`) 
- **Data Type**: string
- **Input Control**: text


#### 46.3. Titolo del paragrafo (`titoloDelParagrafoField`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 46.4. Sottotitolo del paragrafo (`sottotitoloDelParagrafoField`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: string
- **Input Control**: text

#### 46.5. Testo del paragrafo (`testoDelParagrafoField`) 
- **Data Type**: string

#### 46.6. Autore (`autoreParagrafoWebContent`) 
- **Data Type**: structuredContent

#### 46.7. Immagine (`immagineParagrafoMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 46.8. Media (`mediaParagrafoMedia`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: document

#### 46.9. Evento (`eventoParagrafoWebContent`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: structuredContent
- **Possible structures**:
    - **[Evento RM](../../contentStructure/evento-rm/README.md)**


### 47. Funzionalità (evolutive) (`funzionalitaEvolutiveFieldset`) ![Repeatable](https://img.shields.io/badge/🔄Repeatable-blue.svg)
- **Data Type**: 
#### 📁 Nested Fields
#### 47.1. Id funzionalità (`idFunzionalitaField`) 
- **Data Type**: string
- **Input Control**: text

#### 47.2. Attributo (`attributoField`) 
- **Data Type**: string
- **Input Control**: text


### 48. ID Esterno (`idEsternoField`) 
- **Data Type**: string
- **Input Control**: text

## Categories
- **[Stagionalità](../../categories/stagionalità.md)** (`10207163`) 
- **[Tema](../../categories/tema.md)** (`10346791`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Categoria Evento RM](../../categories/categoria-evento-rm.md)** (`11098787`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Riferimento geografico](../../categories/riferimento-geografico.md)** (`5697889`) ![Required](https://img.shields.io/badge/*Required-red.svg)
- **[Licenza](../../categories/licenza.md)** (`5698589`) ![Required](https://img.shields.io/badge/*Required-red.svg)
## Custom fields
- **[ipa_code contenuto](../../customFields/ipa-code-contenuto.md)**
- **[external ref](../../customFields/external-ref.md)**
- **[credits](../../customFields/credits.md)**
- **[srcId](../../customFields/srcid.md)**
- **[channel](../../customFields/channel.md)**
- **[parentId](../../customFields/parentid.md)**
