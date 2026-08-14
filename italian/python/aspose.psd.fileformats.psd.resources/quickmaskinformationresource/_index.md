---
title: "QuickMaskInformationResource Classe"
type: docs
weight: 220
url: /it/python-net/aspose.psd.fileformats.psd.resources/quickmaskinformationresource/
---

**Summary:** Quick mask information resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.QuickMaskInformationResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [QuickMaskInformationResource()](#QuickMaskInformationResource__1) | Inizializza una nuova istanza della classe QuickMaskInformationResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La firma della risorsa di ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La firma della risorsa Photoshop standard. |
| channel_id | short | r/w | Ottiene o imposta l'identificatore del canale. |
| data_size | int | r | Ottiene la dimensione dei dati della risorsa in byte. |
| id | short | r/w | Ottiene o imposta l'identificatore univoco per la risorsa. |
| is_mask_empty | bool | r/w | Ottiene o imposta un valore che indica se questa istanza ha la maschera vuota. |
| minimal_version | int | r | Ottiene la versione PSD minima richiesta. |
| name | string | r/w | Ottiene o imposta il nome della risorsa. Stringa Pascal, riempita per rendere la dimensione pari (un nome nullo consiste di due byte di 0). |
| signature | int | r | Ottiene la firma della risorsa. Dovrebbe essere sempre '8BIM'. |
| dimensione | int | r | Ottiene la dimensione del blocco risorsa in byte, inclusi i dati. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Salva il blocco risorsa nello stream specificato. |
| validate_values() | Convalida i valori della risorsa. |


### Constructor: QuickMaskInformationResource() {#QuickMaskInformationResource__1}


```
 QuickMaskInformationResource() 
```

Inizializza una nuova istanza della classe QuickMaskInformationResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Salva il blocco risorsa nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Lo stream su cui salvare il blocco risorsa. |

