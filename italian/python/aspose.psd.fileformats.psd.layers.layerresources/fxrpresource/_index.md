---
title: "Classe FxrpResource"
type: docs
weight: 320
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/
---

**Summary:** Class FxrpResource. The reference point of layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FxrpResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FxrpResource()](#FxrpResource__1) | Inizializza una nuova istanza della classe [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/). |
| [FxrpResource(data)](#FxrpResource_data_2) | Inizializza una nuova istanza della classe [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).<br/>            Con valore personalizzato o sconosciuto |
| [FxrpResource(x, y)](#FxrpResource_x_y_3) | Inizializza una nuova istanza della classe [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| signature | int | r | Ottiene la firma. |
| x | double | r/w | Ottiene o imposta l'x del punto di riferimento |
| y | double | r/w | Ottiene o imposta l'y del punto di riferimento |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva nel contenitore di stream specificato. |


### Constructor: FxrpResource() {#FxrpResource__1}


```
 FxrpResource() 
```

Inizializza una nuova istanza della classe [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).

### Constructor: FxrpResource(data) {#FxrpResource_data_2}


```
 FxrpResource(data) 
```

Inizializza una nuova istanza della classe [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).<br/>            Con valore personalizzato o sconosciuto

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | byte | I dati della risorsa. |

### Constructor: FxrpResource(x, y) {#FxrpResource_x_y_3}


```
 FxrpResource(x, y) 
```

Inizializza una nuova istanza della classe [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | double | La coordinata x del punto di riferimento |
| y | double | La coordinata y del punto di riferimento |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Salva nel contenitore di stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di stream. |
| psd_version | int | La versione PSD. |

