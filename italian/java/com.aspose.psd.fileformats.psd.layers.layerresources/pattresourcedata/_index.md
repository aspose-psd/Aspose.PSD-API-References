---
title: "PattResourceData"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La classe per memorizzare i dati del pattern per la risorsa."
type: docs
weight: 67
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Inheritance:**
java.lang.Object
```
public final class PattResourceData
```

La classe per memorizzare i dati del pattern per la risorsa [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PattResourceData()](#PattResourceData--) | Inizializza una nuova istanza della classe [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createNewInstance_internalized()](#createNewInstance-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelsCompressionMode_internalized()](#getChannelsCompressionMode-internalized--) | Restituisce il codice del metodo di compressione ottenuto dai canali del pattern\\u2019s. |
| [getClass()](#getClass--) |  |
| [getDefaultPattern_internalized()](#getDefaultPattern-internalized--) | Crea i dati del pattern predefiniti. |
| [getHeight()](#getHeight--) | Ottiene l'altezza. |
| [getImageMode()](#getImageMode--) | Ottiene la modalità immagine. |
| [getLength()](#getLength--) | Ottiene la lunghezza del pattern. |
| [getName()](#getName--) | Ottiene o imposta il nome. |
| [getPatternData()](#getPatternData--) | Ottiene i dati del pattern. |
| [getPatternDataArrayList_internalized()](#getPatternDataArrayList-internalized--) | L'elenco array di memoria. |
| [getPatternId()](#getPatternId--) | Ottiene o imposta l'identificatore del pattern. |
| [getVersion()](#getVersion--) | Ottiene la versione. |
| [getWidth()](#getWidth--) | Ottiene la larghezza. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Salva i dati del pattern. |
| [setHeight_internalized(short value)](#setHeight-internalized-short-) | Ottiene l'altezza. |
| [setImageMode_internalized(short value)](#setImageMode-internalized-short-) | Ottiene la modalità immagine. |
| [setIndexColorTable_internalized(byte[] value)](#setIndexColorTable-internalized-byte---) | Ottiene o imposta la tabella dei colori indice. |
| [setName(String value)](#setName-java.lang.String-) | Ottiene o imposta il nome. |
| [setPattern(int[] pixels, Rectangle bounds)](#setPattern-int---com.aspose.psd.Rectangle-) | Imposta il buffer dei pixel del pattern e la dimensione di destinazione, aggiorna Larghezza ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Altezza ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), e memorizza i dati per il salvataggio usando la modalità di compressione predefinita (0). |
| [setPatternDataArrayList_internalized(VirtualMemoryArrayList value)](#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-) | L'elenco array di memoria. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Ottiene o imposta l'identificatore del pattern. |
| [setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)](#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-) | Imposta il buffer dei pixel del pattern e la dimensione di destinazione, aggiorna Larghezza ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Altezza ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), e memorizza i dati per il salvataggio usando la modalità di compressione specificata. |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Ottiene la versione. |
| [setWidth_internalized(short value)](#setWidth-internalized-short-) | Ottiene la larghezza. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResourceData() {#PattResourceData--}
```
public PattResourceData()
```


Inizializza una nuova istanza della classe [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata).

### createNewInstance_internalized() {#createNewInstance-internalized--}
```
public static PattResourceData createNewInstance_internalized()
```




**Returns:**
[PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata)
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
### getChannelsCompressionMode_internalized() {#getChannelsCompressionMode-internalized--}
```
public final byte getChannelsCompressionMode_internalized()
```


Restituisce il codice del metodo di compressione ottenuto dai canali del pattern\\u2019s.

**Returns:**
byte - Codice di compressione: 0 \\u2014 raw/non compresso; >= 1 \\u2014 zip.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultPattern_internalized() {#getDefaultPattern-internalized--}
```
public static PixelsData getDefaultPattern_internalized()
```


Crea i dati del pattern predefiniti.

**Returns:**
[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) - The default pattern data.
### getHeight() {#getHeight--}
```
public final short getHeight()
```


Ottiene l'altezza.

Valore: L'altezza.

**Returns:**
short
### getImageMode() {#getImageMode--}
```
public final short getImageMode()
```


Ottiene la modalità immagine.

Valore: La modalità immagine.

**Returns:**
short
### getLength() {#getLength--}
```
public final int getLength()
```


Ottiene la lunghezza del pattern.

Valore: La lunghezza del pattern.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Ottiene o imposta il nome.

Valore: Il nome.

**Returns:**
java.lang.String
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Ottiene i dati del pattern.

Valore: I dati del modello.

**Returns:**
int[]
### getPatternDataArrayList_internalized() {#getPatternDataArrayList-internalized--}
```
public final VirtualMemoryArrayList getPatternDataArrayList_internalized()
```


L'elenco array di memoria.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Ottiene o imposta l'identificatore del pattern.

Valore: L'identificatore del modello.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Ottiene la versione.

Valore: La versione.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final short getWidth()
```


Ottiene la larghezza.

Valore: La larghezza.

**Returns:**
short
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




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Salva i dati del pattern.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare. |

### setHeight_internalized(short value) {#setHeight-internalized-short-}
```
public final void setHeight_internalized(short value)
```


Ottiene l'altezza.

Valore: L'altezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setImageMode_internalized(short value) {#setImageMode-internalized-short-}
```
public final void setImageMode_internalized(short value)
```


Ottiene la modalità immagine.

Valore: La modalità immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setIndexColorTable_internalized(byte[] value) {#setIndexColorTable-internalized-byte---}
```
public final void setIndexColorTable_internalized(byte[] value)
```


Ottiene o imposta la tabella dei colori indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ottiene o imposta il nome.

Valore: Il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setPattern(int[] pixels, Rectangle bounds) {#setPattern-int---com.aspose.psd.Rectangle-}
```
public final void setPattern(int[] pixels, Rectangle bounds)
```


Imposta il buffer dei pixel del pattern e la dimensione di destinazione, aggiorna Larghezza ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Altezza ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), e memorizza i dati per il salvataggio usando la modalità di compressione predefinita (0).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | Pixel a 32 bit nel formato 0xAARRGGBB. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Limiti dei pixel del pattern. |

### setPatternDataArrayList_internalized(VirtualMemoryArrayList value) {#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-}
```
public final void setPatternDataArrayList_internalized(VirtualMemoryArrayList value)
```


L'elenco array di memoria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Ottiene o imposta l'identificatore del pattern.

Valore: L'identificatore del modello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode) {#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-}
```
public final void setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)
```


Imposta il buffer dei pixel del pattern e la dimensione di destinazione, aggiorna Larghezza ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Altezza ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), e memorizza i dati per il salvataggio usando la modalità di compressione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | Pixel a 32 bit nel formato 0xAARRGGBB. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Limiti dei pixel del pattern. |
| compressionMode | byte | La modalità di compressione utilizzata per definire la compressione dei dati del modello al salvataggio del file psd. |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Ottiene la versione.

Valore: La versione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setWidth_internalized(short value) {#setWidth-internalized-short-}
```
public final void setWidth_internalized(short value)
```


Ottiene la larghezza.

Valore: La larghezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

