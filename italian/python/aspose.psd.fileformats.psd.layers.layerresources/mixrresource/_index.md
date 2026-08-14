---
title: "Classe MixrResource"
type: docs
weight: 680
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | Inizializza una nuova istanza della classe [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            La specifica del formato PSD contiene la seguente descrizione:<br/>            2 Versione ( = 1)<br/>            2 Monocromatico<br/>            20 colore RGB o CMYK più costante per le impostazioni del mixer. 4 * 2 byte di colore con 2 byte di costante. |
| [MixrResource(data)](#MixrResource_data_2) | Inizializza una nuova istanza della classe [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            La specifica del formato PSD contiene la seguente descrizione:<br/>            2 Versione ( = 1)<br/>            2 Monocromatico<br/>            20 colore RGB o CMYK più costante per le impostazioni del mixer. 4 * 2 byte di colore con 2 byte di costante. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| monochrome | bool | r/w | Ottiene o imposta un valore che indica se questo [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) è monocromatico. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| signature | int | r | Ottiene la firma. |
| version | short | r/w | Ottiene o imposta la versione. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | Ottiene i dati grezzi delle informazioni del canale |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Salva la risorsa nel contenitore di flusso specificato. |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | Imposta le informazioni del canale. |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

Inizializza una nuova istanza della classe [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            La specifica del formato PSD contiene la seguente descrizione:<br/>            2 Versione ( = 1)<br/>            2 Monocromatico<br/>            20 colore RGB o CMYK più costante per le impostazioni del mixer. 4 * 2 byte di colore con 2 byte di costante.

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

Inizializza una nuova istanza della classe [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            La specifica del formato PSD contiene la seguente descrizione:<br/>            2 Versione ( = 1)<br/>            2 Monocromatico<br/>            20 colore RGB o CMYK più costante per le impostazioni del mixer. 4 * 2 byte di colore con 2 byte di costante.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | byte | I dati della risorsa. |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

Ottiene i dati grezzi delle informazioni del canale

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| channel_index | int | Indice del canale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| byte | Array di byte grezzo delle informazioni del canale. |


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

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

Imposta le informazioni del canale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| channel_index | int | Indice del canale. |
| value | byte | Il valore. |

