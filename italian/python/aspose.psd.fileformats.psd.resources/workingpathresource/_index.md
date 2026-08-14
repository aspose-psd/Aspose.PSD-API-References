---
title: "Classe WorkingPathResource"
type: docs
weight: 320
url: /it/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Summary:** Working path resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.WorkingPathResource

**Inheritance:** IVectorPathData, ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WorkingPathResource(data_bytes)](#WorkingPathResource_data_bytes_1) | Inizializza una nuova istanza della classe [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La firma della risorsa di ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La firma della risorsa Photoshop standard. |
| data_size | int | r | Ottiene la dimensione dei dati della risorsa in byte. |
| id | short | r/w | Ottiene o imposta l'identificatore univoco per la risorsa. |
| is_disabled | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è disabilitata. |
| is_inverted | bool | r/w | Ottiene o imposta un valore che indica se questa istanza è invertita. |
| is_not_linked | bool | r/w | Ottiene o imposta un valore che indica se questa istanza non è collegata. |
| minimal_version | int | r | Ottiene la versione PSD minima richiesta. |
| name | string | r/w | Ottiene o imposta il nome della risorsa. Stringa Pascal, riempita per rendere la dimensione pari (un nome nullo consiste di due byte di 0). |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Ottiene o imposta i record del percorso. |
| signature | int | r | Ottiene la firma della risorsa. Dovrebbe essere sempre '8BIM'. |
| dimensione | int | r | Ottiene la dimensione del blocco risorsa in byte, inclusi i dati. |
| version | int | r/w | Ottiene o imposta la versione. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Salva il blocco risorsa nello stream specificato. |
| validate_values() | Convalida i valori della risorsa. |


### Constructor: WorkingPathResource(data_bytes) {#WorkingPathResource_data_bytes_1}


```
 WorkingPathResource(data_bytes) 
```

Inizializza una nuova istanza della classe [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| data_bytes | byte | I dati del percorso vettoriale. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Salva il blocco risorsa nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Lo stream su cui salvare il blocco risorsa. |

