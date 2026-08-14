---
title: "Classe BlncResource"
type: docs
weight: 80
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Summary:** BlncResource class is a resource of Color Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlncResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BlncResource()](#BlncResource__1) | Inizializza una nuova istanza della classe [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| highlights_cyan_red_balance | short | r/w | Ottiene o imposta il Highlights Cyan Red Balance. |
| highlights_magenta_green_balance | short | r/w | Ottiene o imposta il Highlights Magenta Green Balance. |
| highlights_yellow_blue_balance | short | r/w | Ottiene o imposta il Highlights Yellow Blue Balance. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| midtones_cyan_red_balance | short | r/w | Ottiene o imposta il Midtones Cyan Red Balance. |
| midtones_magenta_green_balance | short | r/w | Ottiene o imposta il Midtones Magenta Green Balance. |
| midtones_yellow_blue_balance | short | r/w | Ottiene o imposta il Midtones Yellow Blue Balance. |
| preserve_luminosity | bool | r/w | Ottiene o imposta un valore che indica se questo [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) preserva la luminosità. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| shadows_cyan_red_balance | short | r/w | Ottiene o imposta il Shadows Cyan Red Balance. |
| shadows_magenta_green_balance | short | r/w | Ottiene o imposta il Shadows Magenta Green Balance. |
| shadows_yellow_blue_balance | short | r/w | Ottiene o imposta il Shadows Yellow Blue Balance. |
| signature | int | r | Ottiene la firma. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva la risorsa nel contenitore di flusso specificato. |


### Constructor: BlncResource() {#BlncResource__1}


```
 BlncResource() 
```

Inizializza una nuova istanza della classe [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/).

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

