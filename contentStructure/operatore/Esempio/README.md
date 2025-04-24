# Guida all'utilizzo dell'esempio

In questa guida verranno descritti i campi presenti nel body della richiesta di inserimento di uno Structured content.

Per effettuare la richiesta sarà necessario disporre delle credenziali.

**Tipo chiamata**: POST

**Url**: `https://digitalhub.regione.marche.it/o/headless-delivery/v1.0/structured-content-folders/22448419/structured-contents`

Questa chiamata andrà ad inserire il nostro Structured content all'interno di una cartella predefinita.

È possibile trovare esempio di body all'interno di questa in ogni cartella di una struttura.

## Spiegazione campi all'interno del body:

- **contentStructureId**: Id della struttura che si sta inserendo

- **externalReferenceCode**: un codice univoco, si suggerisce l'utilizzo di una sintassi univoca in modo da evitare dei "conflict"

- **title**: il titolo dello Structured content

- **taxonomyCategoryIds**: sono gli ID delle categorie associate a questo Structured content. Possono essere controllati nel README della struttura.

- **customFields**: sono dei campi custom che possono essere valorizzati per dare delle informazioni in più sul contenuto web.

### ContentFields

Per quanto riguarda i contentFields in base alla tipologia del campo sarà necessario impostare un contentFieldValue differente.

- **data**: campo di tipo stringa, la maggior parte delle tipologie

    - `string`: semplice stringa (es. `esempio testo`)

    - `integer`: valore intero (es. `12345`)

    - `double`: valore decimale (es. `123.45`)

    - `date`: valore data (es. `2025-01-01T01:00:00Z`)

    - `boolean`: valore booleano (es. `true`)

    - `radio`: campo opzione singola, dove inserire il valore di una delle opzioni del campo

    - `select`: campo opzione singola, dove inserire il valore di una delle opzioni del campo

- **document**: sono i file o le immagini caricate sul sito. Per poter associare una propria immagine sarà necessario caricarla con una chiamata differente per ottenere l'ID

- **structuredContentLink**: è un campo utilizzato per collegare uno Structured content. In questo caso sarà necessario inserire l'ID del contenuto.

### NestedContentFields

I nestedContentFields sono gruppi di campi che possono essere obbligatori o meno.

I gruppi campi, anche se non obbligatori, dovranno essere inseriti all'interno del JSON con `nestedContentFields` impostato come array vuoto se non si vogliono valorizzare i campi all'interno.

Quando si inserisce un `nestedContentFields` il campo `contentFieldValue` non deve essere valorizzato, saranno i campi al suo interno ad avere il valore.

