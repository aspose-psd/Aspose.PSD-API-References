---
title: "Classe BritResource"
type: docs
weight: 120
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BritResource()](#BritResource__1) | Inizializza una nuova istanza della classe [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | Inizializza una nuova istanza della classe [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(bytes)](#BritResource_bytes_3) | Inizializza una nuova istanza della classe [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).<br/>            La specifica del formato PSD contiene la seguente descrizione:<br/>            2 Luminosità<br/>            2 Contrasto<br/>            2 Valore medio per luminosità e contrasto<br/>            1 Solo colore Lab<br/>            Non è utilizzato nei PSD moderni (CS5 e successive) dove è presente CgEd. CgEd memorizza le proprietà delle informazioni |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| luminosità | short | r/w | Ottiene o imposta la luminosità. |
| contrasto | short | r/w | Ottiene o imposta il contrasto. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lab_color | bool | r/w | Ottiene o imposta un valore che indica se [lab color]. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| mean_value_for_brightness_and_contrast | short | r/w | Ottiene o imposta il valore medio per la luminosità e il contrasto. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| signature | int | r | Ottiene la firma. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva la risorsa nel contenitore di flusso specificato. |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

Inizializza una nuova istanza della classe [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

Inizializza una nuova istanza della classe [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| luminosità | short | La luminosità. |
| contrasto | short | Il contrasto. |
| mean_value_for_brightness_and_contrast | short | Il valore medio per luminosità e contrasto. |
| lab_color | bool | se impostato su <c>true</c> [lab color]. |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

Inizializza una nuova istanza della classe [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).<br/>            La specifica del formato PSD contiene la seguente descrizione:<br/>            2 Luminosità<br/>            2 Contrasto<br/>            2 Valore medio per luminosità e contrasto<br/>            1 Solo colore Lab<br/>            Non è utilizzato nei PSD moderni (CS5 e successive) dove è presente CgEd. CgEd memorizza le proprietà delle informazioni

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| byte | byte | I byte. |

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

