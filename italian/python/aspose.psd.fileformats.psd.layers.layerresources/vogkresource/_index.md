---
title: "Classe VogkResource"
type: docs
weight: 1110
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/
---

**Summary:** The Vector Origination Data resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VogkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VogkResource()](#VogkResource__1) | Inizializza una nuova istanza della classe [VogkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| shape_origin_settings | [VectorShapeOriginSettings[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/) | r/w | Ottiene o imposta le impostazioni dell'origine della forma. |
| signature | int | r | Ottiene la firma. |
| version | int | r/w | Ottiene o imposta la versione. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva la risorsa nel contenitore di flusso specificato. |


### Constructor: VogkResource() {#VogkResource__1}


```
 VogkResource() 
```

Inizializza una nuova istanza della classe [VogkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/).

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Salva la risorsa nel contenitore di flusso specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare. |
| psd_version | int | La versione PSD. |

