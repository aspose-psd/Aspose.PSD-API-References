---
title: "Classe LyidResource"
type: docs
weight: 660
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/
---

**Summary:** Class LyidResource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LyidResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LyidResource(bytes)](#LyidResource_bytes_1) | Inizializza una nuova istanza della classe [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/).<br/>            Con valore personalizzato o sconosciuto |
| [LyidResource(id)](#LyidResource_id_2) | Inizializza una nuova istanza della classe [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/). |
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
| value | int | r | Restituisce il valore. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Salva nel contenitore di stream specificato. |


### Constructor: LyidResource(bytes) {#LyidResource_bytes_1}


```
 LyidResource(bytes) 
```

Inizializza una nuova istanza della classe [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/).<br/>            Con valore personalizzato o sconosciuto

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| byte | byte | I byte. |

### Constructor: LyidResource(id) {#LyidResource_id_2}


```
 LyidResource(id) 
```

Inizializza una nuova istanza della classe [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| id | int | L'identificatore del livello. |

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

