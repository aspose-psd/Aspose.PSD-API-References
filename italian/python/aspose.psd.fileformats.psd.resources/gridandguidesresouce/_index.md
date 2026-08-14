---
title: "Classe GridAndGuidesResouce"
type: docs
weight: 110
url: /it/python-net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---

**Summary:** Represents the grid and guides resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GridAndGuidesResouce

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GridAndGuidesResouce()](#GridAndGuidesResouce__1) | Inizializza una nuova istanza della classe GridAndGuidesResouce |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La firma della risorsa di ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La firma della risorsa Photoshop standard. |
| data_size | int | r | Ottiene la dimensione dei dati della risorsa in byte. |
| grid_cycle_x | int | r/w | Ottiene o imposta il ciclo della griglia orizzontale. Il valore predefinito è 576. |
| grid_cycle_y | int | r/w | Ottiene o imposta il ciclo della griglia verticale. Il valore predefinito è 576. |
| guide_count | int | r | Ottiene il conteggio dei blocchi risorsa della guida. |
| guides | [GuideResource[]](/psd/python-net/aspose.psd.fileformats.psd.resources/guideresource) | r/w | Ottiene o imposta le guide. |
| header_version | int | r/w | Ottiene o imposta la versione dell'intestazione. Questo valore dovrebbe essere sempre 1. |
| id | short | r/w | Ottiene o imposta l'identificatore univoco per la risorsa. |
| minimal_version | int | r | Ottiene la versione minima richiesta di psd. |
| name | string | r/w | Ottiene o imposta il nome della risorsa. Stringa Pascal, riempita per rendere la dimensione pari (un nome nullo consiste di due byte di 0). |
| signature | int | r | Ottiene la firma della risorsa. Dovrebbe essere sempre '8BIM'. |
| dimensione | int | r | Ottiene la dimensione del blocco risorsa in byte, inclusi i dati. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Salva il blocco risorsa nello stream specificato. |
| validate_values() | Convalida i valori della risorsa. |


### Constructor: GridAndGuidesResouce() {#GridAndGuidesResouce__1}


```
 GridAndGuidesResouce() 
```

Inizializza una nuova istanza della classe GridAndGuidesResouce

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Salva il blocco risorsa nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Lo stream su cui salvare il blocco risorsa. |

