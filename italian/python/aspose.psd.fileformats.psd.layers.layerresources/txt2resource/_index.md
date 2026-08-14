---
title: "Txt2Resource Classe"
type: docs
weight: 970
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | Inizializza una nuova istanza della classe Txt2Resource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| dati | byte | r/w | Ottiene o imposta i dati. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| signature | int | r | Ottiene la firma. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | Aggiunge il record di testo a Resource e restituisce l'id del record di testo. |
| [get_text_data()](#get_text_data__2) | Ottiene il record di testo dai dati della risorsa. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | Salva il contenitore di flusso specificato. |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

Inizializza una nuova istanza della classe Txt2Resource

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

Aggiunge il record di testo a Resource e restituisce l'id del record di testo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | string | Il testo del record. |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | I limiti. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Restituisce l'Id del record di testo per la risorsa |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

Ottiene il record di testo dai dati della risorsa.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Array di record di testo |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

Salva il contenitore di flusso specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di stream. |
| psd_version | int | La versione PSD. |

