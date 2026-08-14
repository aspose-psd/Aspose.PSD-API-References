---
title: "Classe BlwhResource"
type: docs
weight: 90
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | Inizializza una nuova istanza della classe BlwhResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| black_and_white_preset_file_name | string | r/w | Ottiene o imposta il nome file del preset in bianco e nero. |
| blu | int | r/w | Ottiene o imposta il valore del blu. |
| bw_preset_kind | int | r/w | Ottiene o imposta il valore del tipo di preset in bianco e nero. |
| ciano | int | r/w | Ottiene o imposta il valore del ciano. |
| verde | int | r/w | Ottiene o imposta il valore del verde. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| magenta | int | r/w | Ottiene o imposta il valore del magenta. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| rosso | int | r/w | Ottiene o imposta il valore dei rossi. |
| signature | int | r | Ottiene la firma. |
| tint_color | int | r/w | Ottiene o imposta il valore ARGB del Tint Color. |
| use_tint | bool | r/w | Ottiene o imposta un valore che indica se [tint color] è usato. |
| yellows | int | r/w | Ottiene o imposta il valore dei gialli. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva la risorsa nel contenitore di flusso specificato. |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

Inizializza una nuova istanza della classe BlwhResource

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

