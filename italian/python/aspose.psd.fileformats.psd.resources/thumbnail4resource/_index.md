---
title: "Classe Thumbnail4Resource"
type: docs
weight: 240
url: /it/python-net/aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Summary:** Represents the thumbnail resource for psd 4.0.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.Thumbnail4Resource

**Inheritance:** ThumbnailResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Thumbnail4Resource()](#Thumbnail4Resource__1) | Inizializza una nuova istanza della classe Thumbnail4Resource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La firma della risorsa di ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La firma della risorsa Photoshop standard. |
| bits_pixel | short | r/w | Ottiene o imposta i bit per pixel. |
| data_size | int | r | Ottiene la dimensione dei dati della risorsa in byte. |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | Ottiene o imposta il formato dei dati della miniatura. |
| altezza | int | r/w | Ottiene o imposta l'altezza della miniatura in pixel. |
| id | short | r/w | Ottiene o imposta l'identificatore univoco per la risorsa. |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | Ottiene o imposta le opzioni JPEG. Idoneo quando la risorsa miniatura viene salvata solo in formato file JPEG. Questa opzione non ha effetto quando è definito il formato RAW. |
| minimal_version | int | r | Ottiene la versione minima richiesta di psd. |
| name | string | r/w | Ottiene o imposta il nome della risorsa. Stringa Pascal, riempita per rendere la dimensione pari (un nome nullo consiste di due byte di 0). |
| planes_count | short | r/w | Ottiene o imposta il conteggio dei piani. |
| signature | int | r | Ottiene la firma della risorsa. Dovrebbe essere sempre '8BIM'. |
| dimensione | int | r | Ottiene la dimensione del blocco risorsa in byte, inclusi i dati. |
| size_after_compression | int | r | Ottiene o imposta la dimensione dopo la compressione. Utilizzato per il controllo di coerenza. |
| thumbnail_argb_32_data | int | r/w | Ottiene o imposta i dati della miniatura ARGB a 32 bit. |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Ottiene o imposta i dati della miniatura. |
| total_size | int | r | Ottiene la dimensione totale dei dati. |
| width | int | r/w | Ottiene o imposta la larghezza della miniatura in pixel. |
| width_bytes | int | r | Ottiene la larghezza della riga in byte. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Salva i dati del blocco di risorsa. |
| validate_values() | Convalida i valori della risorsa. |


### Constructor: Thumbnail4Resource() {#Thumbnail4Resource__1}


```
 Thumbnail4Resource() 
```

Inizializza una nuova istanza della classe Thumbnail4Resource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Salva i dati del blocco di risorsa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

