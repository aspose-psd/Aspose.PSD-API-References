---
title: "Thumbnail4Resource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta la risorsa miniatura per psd 4.0."
type: docs
weight: 34
url: /it/java/com.aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock), [com.aspose.psd.fileformats.psd.resources.ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource)
```
public final class Thumbnail4Resource extends ThumbnailResource
```

Rappresenta la risorsa miniatura per psd 4.0.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Thumbnail4Resource()](#Thumbnail4Resource--) | Inizializza una nuova istanza della classe [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | La firma della risorsa di ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | La firma della risorsa Photoshop standard. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | Ottiene o imposta i bit del pixel. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Ottiene la dimensione dei dati della risorsa in byte. |
| [getFormat()](#getFormat--) | Ottiene o imposta il formato dei dati della miniatura. |
| [getHeight()](#getHeight--) | Ottiene o imposta l'altezza della miniatura in pixel. |
| [getID()](#getID--) | Ottiene o imposta l'identificatore univoco per la risorsa. |
| [getJpegOptions()](#getJpegOptions--) | Ottiene o imposta le opzioni JPEG. |
| [getMinimalVersion()](#getMinimalVersion--) | Ottiene la versione PSD minima richiesta. |
| [getName()](#getName--) | Ottiene o imposta il nome della risorsa. |
| [getPlanesCount()](#getPlanesCount--) | Ottiene o imposta il conteggio dei piani. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa. |
| [getSize()](#getSize--) | Ottiene la dimensione del blocco risorsa in byte, inclusi i dati. |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | Ottiene o imposta la dimensione dopo la compressione. |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | Ottiene o imposta i dati della miniatura ARGB a 32 bit. |
| [getThumbnailData()](#getThumbnailData--) | Ottiene o imposta i dati della miniatura. |
| [getTotalSize()](#getTotalSize--) | Ottiene la dimensione totale dei dati. |
| [getWidth()](#getWidth--) | Ottiene o imposta la larghezza della miniatura in pixel. |
| [getWidthBytes()](#getWidthBytes--) | Ottiene la larghezza della riga in byte. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Salva il blocco risorsa nello stream specificato. |
| [setBitsPixel(short value)](#setBitsPixel-short-) | Ottiene o imposta i bit del pixel. |
| [setFormat(int value)](#setFormat-int-) | Ottiene o imposta il formato dei dati della miniatura. |
| [setHeight(int value)](#setHeight-int-) | Ottiene o imposta l'altezza della miniatura in pixel. |
| [setID(short value)](#setID-short-) | Ottiene o imposta l'identificatore univoco per la risorsa. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Ottiene o imposta le opzioni JPEG. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Ottiene o imposta le informazioni del livello e della maschera. |
| [setName(String value)](#setName-java.lang.String-) | Ottiene o imposta il nome della risorsa. |
| [setPlanesCount(short value)](#setPlanesCount-short-) | Ottiene o imposta il conteggio dei piani. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Ottiene o imposta lo stato del blocco risorsa. |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | Ottiene o imposta i dati della miniatura ARGB a 32 bit. |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | Ottiene o imposta i dati della miniatura. |
| [setWidth(int value)](#setWidth-int-) | Ottiene o imposta la larghezza della miniatura in pixel. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Convalida i valori della risorsa. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Thumbnail4Resource() {#Thumbnail4Resource--}
```
public Thumbnail4Resource()
```


Inizializza una nuova istanza della classe [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


La firma della risorsa di ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


La firma della risorsa Photoshop standard.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


Ottiene o imposta i bit del pixel.

Valore: I bit del pixel della miniatura.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Ottiene la dimensione dei dati della risorsa in byte.

Valore: La dimensione dei dati della risorsa.

**Returns:**
int
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Ottiene o imposta il formato dei dati della miniatura.

Valore: Il formato dei dati della miniatura.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ottiene o imposta l'altezza della miniatura in pixel.

Valore: L'altezza della miniatura.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Ottiene o imposta l'identificatore univoco per la risorsa.

Valore: L'identificatore univoco della risorsa.

**Returns:**
short
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Ottiene o imposta le opzioni JPEG. Idoneo quando la risorsa miniatura viene salvata solo nel formato file JPEG. Questa opzione non ha effetto quando è definito il formato RAW.

Valore: Le opzioni JPEG.

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Ottiene la versione PSD minima richiesta.

Valore: La versione minima psd.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Ottiene o imposta il nome della risorsa. Stringa Pascal, riempita per rendere la dimensione pari (un nome nullo consiste di due byte di 0).

Valore: Il nome della risorsa.

**Returns:**
java.lang.String
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


Ottiene o imposta il conteggio dei piani.

Valore: Il conteggio dei piani della miniatura.

**Returns:**
short
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Ottiene la firma della risorsa. Dovrebbe essere sempre '8BIM'.

Valore: La firma della risorsa.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Ottiene la dimensione del blocco risorsa in byte, inclusi i dati.

Valore: La dimensione del blocco della risorsa.

**Returns:**
int
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


Ottiene o imposta la dimensione dopo la compressione. Utilizzato per il controllo di coerenza.

Valore: La dimensione dopo la compressione.

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


Ottiene o imposta i dati della miniatura ARGB a 32 bit.

Valore: I dati della miniatura ARGB a 32 bit.

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


Ottiene o imposta i dati della miniatura.

Valore: I dati della miniatura.

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


Ottiene la dimensione totale dei dati.

Valore: la dimensione totale dei dati.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ottiene o imposta la larghezza della miniatura in pixel.

Valore: la larghezza della miniatura.

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


Ottiene la larghezza della riga in byte.

Valore: la larghezza della riga in byte.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Salva il blocco risorsa nello stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il flusso su cui salvare il blocco della risorsa. |

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


Ottiene o imposta i bit del pixel.

Valore: I bit del pixel della miniatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


Ottiene o imposta il formato dei dati della miniatura.

Valore: Il formato dei dati della miniatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ottiene o imposta l'altezza della miniatura in pixel.

Valore: L'altezza della miniatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Ottiene o imposta l'identificatore univoco per la risorsa.

Valore: L'identificatore univoco della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Ottiene o imposta le opzioni JPEG. Idoneo quando la risorsa miniatura viene salvata solo nel formato file JPEG. Questa opzione non ha effetto quando è definito il formato RAW.

Valore: Le opzioni JPEG.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Ottiene o imposta le informazioni del livello e della maschera.

Valore: Le informazioni di livello e maschera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ottiene o imposta il nome della risorsa. Stringa Pascal, riempita per rendere la dimensione pari (un nome nullo consiste di due byte di 0).

Valore: Il nome della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


Ottiene o imposta il conteggio dei piani.

Valore: Il conteggio dei piani della miniatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firma | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Ottiene o imposta lo stato del blocco risorsa.

Valore: Lo stato del blocco della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


Ottiene o imposta i dati della miniatura ARGB a 32 bit.

Valore: I dati della miniatura ARGB a 32 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


Ottiene o imposta i dati della miniatura.

Valore: I dati della miniatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ottiene o imposta la larghezza della miniatura in pixel.

Valore: la larghezza della miniatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


Convalida i valori della risorsa.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

