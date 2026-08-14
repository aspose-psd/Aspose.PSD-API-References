---
title: "Classe LevlResource"
type: docs
weight: 490
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | Inizializza una nuova istanza della classe [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/). |
| [LevlResource(bytes)](#LevlResource_bytes_2) | Inizializza una nuova istanza della classe [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).<br/>            Supportato nei modi colore GrayScale, Duotone, RGB, CMYK, Lab<br/>            2 byte - Versione (=2)<br/>            29 * 10 byte - Set di record di livello con 5 interi brevi<br/>            4 byte - Intestazione Lvls (Inizia all'indice 292)<br/>            2 byte - Versione (=3)<br/>            2 byte - Conteggio totale dei record di livello<br/>    10 * (Conteggio Totale - 29)<br/>            La terminazione zero della risorsa Lvls dovrebbe essere piegata per quattro anche |
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
| version | short | r | Restituisce la versione. Il valore predefinito è 2 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | Ottiene il canale. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Salva la risorsa nel contenitore di flusso specificato. |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

Inizializza una nuova istanza della classe [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

Inizializza una nuova istanza della classe [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).<br/>            Supportato nei modi colore GrayScale, Duotone, RGB, CMYK, Lab<br/>            2 byte - Versione (=2)<br/>            29 * 10 byte - Set di record di livello con 5 interi brevi<br/>            4 byte - Intestazione Lvls (Inizia all'indice 292)<br/>            2 byte - Versione (=3)<br/>            2 byte - Conteggio totale dei record di livello<br/>    10 * (Conteggio Totale - 29)<br/>            La terminazione zero della risorsa Lvls dovrebbe essere piegata per quattro anche

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| byte | byte | I byte. |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

Ottiene il canale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| channel_index | int | Indice del canale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | Dati di livello del canale |


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

