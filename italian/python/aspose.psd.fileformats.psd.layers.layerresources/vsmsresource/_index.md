---
title: "Classe VsmsResource"
type: docs
weight: 1130
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/
---

**Summary:** Class VsmsResource.<br/>            This resource contains information about vector layer mask

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VsmsResource

**Inheritance:** IVectorPathData, VectorPathDataResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VsmsResource()](#VsmsResource__1) | Inizializza una nuova istanza della classe [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/). |
| [VsmsResource(data)](#VsmsResource_data_2) | Inizializza una nuova istanza della classe [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa specifica per PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma della risorsa comune. |
| TYPE_TOOL_KEY [static] | int | r | La chiave delle informazioni dello strumento di tipo. |
| is_disabled | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è disabilitata. |
| is_inverted | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è invertita. |
| is_not_linked | bool | r/w | Ottiene o imposta un valore che indica se questa istanza non è collegata. |
| key | int | r | Ottiene la chiave della risorsa del livello. |
| lunghezza | int | r | Ottiene la lunghezza della risorsa del livello in byte. |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Ottiene o imposta i record del percorso. |
| psd_version | int | r | Ottiene la versione minima di PSD richiesta per la risorsa del livello. 0 indica nessuna restrizione. |
| signature | int | r | Ottiene la firma. |
| version | int | r/w | Ottiene o imposta la versione. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva la risorsa nel contenitore di flusso specificato. |


### Constructor: VsmsResource() {#VsmsResource__1}


```
 VsmsResource() 
```

Inizializza una nuova istanza della classe [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/).

### Constructor: VsmsResource(data) {#VsmsResource_data_2}


```
 VsmsResource(data) 
```

Inizializza una nuova istanza della classe [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | byte | I dati della risorsa. |

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

