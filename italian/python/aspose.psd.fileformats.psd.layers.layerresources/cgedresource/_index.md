---
title: "Classe CgEdResource"
type: docs
weight: 130
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | Inizializza una nuova istanza della classe CgEdResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| auto | bool | r/w | Ottiene o imposta un valore che indica se questo [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) è automatico. |
| luminosità | int | r/w | Ottiene o imposta la luminosità. |
| contrasto | int | r/w | Ottiene o imposta il contrasto. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lab_color | bool | r/w | Ottiene o imposta un valore che indica se [lab color] è utilizzato. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| mean_value_for_brightness_and_contrast | int | r/w | Ottiene o imposta il valore medio per la luminosità e il contrasto. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| signature | int | r | Ottiene la firma. |
| use_legacy | bool | r/w | Ottiene o imposta un valore che indica se [use legacy] è attivo. |
| version | int | r/w | Ottiene o imposta la versione. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva la risorsa nel contenitore di flusso specificato. |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

Inizializza una nuova istanza della classe CgEdResource

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

