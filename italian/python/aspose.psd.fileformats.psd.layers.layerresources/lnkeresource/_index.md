---
title: "Classe LnkeResource"
type: docs
weight: 590
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/
---

**Summary:** Defines the LnkeResource class that contains information about external linked files or assets in the PSD format image.<br/>            The link resource may contain several [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) instances which can be accessed by indexer.<br/>            This is a part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files programmatically

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LnkeResource

**Inheritance:** LinkResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LnkeResource()](#LnkeResource__1) | Inizializza una nuova istanza della classe [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/). |
| [LnkeResource(data_sources)](#LnkeResource_data_sources_2) | Inizializza una nuova istanza della classe [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| data_source_count | int | r | Ottiene il conteggio delle sorgenti dati di collegamento che possono essere accessibili tramite l'indicizzatore. |
| is_empty | bool | r | Ottiene un valore che indica se questa istanza della risorsa di collegamento è vuota. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lunghezza | int | r | Ottiene la lunghezza globale della risorsa di collegamento PSD in byte. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| signature | int | r | Ottiene la firma. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva i dati del blocco di risorsa. |


### Constructor: LnkeResource() {#LnkeResource__1}


```
 LnkeResource() 
```

Inizializza una nuova istanza della classe [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/).

### Constructor: LnkeResource(data_sources) {#LnkeResource_data_sources_2}


```
 LnkeResource(data_sources) 
```

Inizializza una nuova istanza della classe [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| data_sources | [LinkDataSource[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource) | Le fonti di dati. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Salva i dati del blocco di risorsa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare. |
| psd_version | int | La versione PSD. |

