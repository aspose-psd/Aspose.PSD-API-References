---
title: "Classe ExpaResource"
type: docs
weight: 280
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/
---

**Summary:** Class ExpaResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ExpaResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ExpaResource()](#ExpaResource__1) | Inizializza una nuova istanza della classe [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
| [ExpaResource(bytes)](#ExpaResource_bytes_2) | Inizializza una nuova istanza della classe [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
| [ExpaResource(exposure, offset, gamma)](#ExpaResource_exposure_offset_gamma_3) | Inizializza una nuova istanza della classe [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| esposizione | float | r/w | Ottiene o imposta l'esposizione. |
| gamma_correction | float | r/w | Ottiene o imposta la gamma. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| offset | float | r/w | Ottiene o imposta lo spostamento. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| signature | int | r | Ottiene la firma. |
| version | short | r | Ottiene la versione. Il valore predefinito è 1 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva la risorsa nel contenitore di flusso specificato. |


### Constructor: ExpaResource() {#ExpaResource__1}


```
 ExpaResource() 
```

Inizializza una nuova istanza della classe [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

### Constructor: ExpaResource(bytes) {#ExpaResource_bytes_2}


```
 ExpaResource(bytes) 
```

Inizializza una nuova istanza della classe [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| byte | byte | I byte. |

### Constructor: ExpaResource(exposure, offset, gamma) {#ExpaResource_exposure_offset_gamma_3}


```
 ExpaResource(exposure, offset, gamma) 
```

Inizializza una nuova istanza della classe [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| esposizione | float | L'esposizione. |
| offset | float | Lo spostamento. |
| gamma | float | La gamma. |

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

