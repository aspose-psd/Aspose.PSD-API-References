---
title: "PattResourceData Classe"
type: docs
weight: 780
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Summary:** The class to store the pattern data for [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResourceData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PattResourceData()](#PattResourceData__1) | Inizializza una nuova istanza della classe PattResourceData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| altezza | short | r | Restituisce l'altezza. |
| image_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r | Restituisce la modalità immagine. |
| lunghezza | int | r | Restituisce la lunghezza del motivo. |
| name | string | r/w | Ottiene o imposta il nome. |
| pattern_data | int | r | Restituisce i dati del motivo. |
| pattern_id | string | r/w | Ottiene o imposta l'identificatore del pattern. |
| version | int | r | Ottiene la versione. |
| width | short | r | Restituisce la larghezza. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container)](#save_stream_container_1) | Salva i dati del motivo. |
| [set_pattern(pixels, bounds)](#set_pattern_pixels_bounds_2) | Imposta il motivo. |


### Constructor: PattResourceData() {#PattResourceData__1}


```
 PattResourceData() 
```

Inizializza una nuova istanza della classe PattResourceData

### Method: save(stream_container) {#save_stream_container_1}


```
 save(stream_container) 
```

Salva i dati del motivo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare. |

### Method: set_pattern(pixels, bounds) {#set_pattern_pixels_bounds_2}


```
 set_pattern(pixels, bounds) 
```

Imposta il motivo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixels | int | I pixel. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | I limiti. |

