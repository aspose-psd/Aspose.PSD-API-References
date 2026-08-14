---
title: "Classe PhflResourceVersion2"
type: docs
weight: 800
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResourceVersion2

**Inheritance:** PhflResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PhflResourceVersion2()](#PhflResourceVersion2__1) | Inizializza una nuova istanza della classe [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/). |
| [PhflResourceVersion2(data)](#PhflResourceVersion2_data_2) | Inizializza una nuova istanza della classe [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| color_space | short | r | Ottiene lo spazio colore. |
| component_a | short | r/w | Ottiene o imposta il componente A del colore |
| component_b | short | r/w | Ottiene o imposta il componente B |
| component_l | short | r/w | Ottiene o imposta il componente L del colore |
| density | int | r/w | Ottiene o imposta la densità. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| preserve_luminosity | bool | r/w | Ottiene o imposta un valore che indica se [preserve luminosity]. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| signature | int | r | Ottiene la firma. |
| version | short | r | Ottiene la versione. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | Ottiene il colore. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Salva la risorsa nel contenitore di flusso specificato. |
| [set_rgb_color(color)](#set_rgb_color_color_3) | Imposta il colore RGB. |


### Constructor: PhflResourceVersion2() {#PhflResourceVersion2__1}


```
 PhflResourceVersion2() 
```

Inizializza una nuova istanza della classe [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/).

### Constructor: PhflResourceVersion2(data) {#PhflResourceVersion2_data_2}


```
 PhflResourceVersion2(data) 
```

Inizializza una nuova istanza della classe [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | byte | I dati della risorsa. |

### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

Ottiene il colore.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Il colore RGB |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Salva la risorsa nel contenitore di flusso specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare. |
| psd_version | int | La versione PSD. |

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

Imposta il colore RGB.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Il colore. |

