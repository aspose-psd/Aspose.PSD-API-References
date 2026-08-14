---
title: "Classe LayerGroupsEnabledResource"
type: docs
weight: 160
url: /it/python-net/aspose.psd.fileformats.psd.resources/layergroupsenabledresource/
---

**Summary:** Layer groups enabled resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.LayerGroupsEnabledResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LayerGroupsEnabledResource()](#LayerGroupsEnabledResource__1) | Inizializza una nuova istanza della classe LayerGroupsEnabledResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La firma della risorsa di ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La firma della risorsa Photoshop standard. |
| data_size | int | r | Ottiene la dimensione dei dati della risorsa in byte. |
| ds | byte | r/w | Ottiene o imposta gli i ds. |
| id | short | r/w | Ottiene o imposta l'identificatore univoco per la risorsa. |
| minimal_version | int | r | Ottiene la versione PSD minima richiesta. |
| name | string | r/w | Ottiene o imposta il nome della risorsa. Stringa Pascal, riempita per rendere la dimensione pari (un nome nullo consiste di due byte di 0). |
| signature | int | r | Ottiene la firma della risorsa. Dovrebbe essere sempre '8BIM'. |
| dimensione | int | r | Ottiene la dimensione del blocco risorsa in byte, inclusi i dati. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Salva il blocco risorsa nello stream specificato. |
| validate_values() | Convalida i valori della risorsa. |


### Constructor: LayerGroupsEnabledResource() {#LayerGroupsEnabledResource__1}


```
 LayerGroupsEnabledResource() 
```

Inizializza una nuova istanza della classe LayerGroupsEnabledResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Salva il blocco risorsa nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Lo stream su cui salvare il blocco risorsa. |

