---
title: "ChannelInformation"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Le informazioni del canale."
type: docs
weight: 13
url: /it/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

Le informazioni del canale.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | L'ID del canale maschera (raster) dell'utente. |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | L'ID del canale maschera breve (raster o vettoriale). |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | L'ID del canale alfa |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Comprende i dati del canale |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Clona le informazioni del canale specificato. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | Ottiene la profondità di bit del canale. |
| [getChannelID()](#getChannelID--) | Ottiene o imposta l'ID del canale. |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | Ottiene o imposta il metodo di compressione. |
| [getData_internalized()](#getData-internalized--) | Ottiene o imposta i dati del canale. |
| [getLength()](#getLength--) | Ottiene la lunghezza del canale in byte. |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | Ottiene la versione del PSD |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | Ottiene i dati non compressi. |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | Verifica se il canale è ShortMask o meno |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | Salva i dati del canale. |
| [setChannelID(short value)](#setChannelID-short-) | Ottiene o imposta l'ID del canale. |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | Imposta i dati compressi. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Ottiene o imposta il metodo di compressione. |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | Imposta i dati compressi. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| compressionMethod | short |  |
| bitDepth | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


L'ID del canale maschera dell'utente (raster). (se un livello ha sia maschera vettoriale che raster).

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


L'ID del canale maschera breve (raster o vettoriale). (se un livello ha solo una maschera vettoriale o raster ma non entrambe).

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


L'ID del canale alfa

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


Comprende i dati del canale

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rawData | byte[] | I dati grezzi per la compressione |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | I limiti del livello |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | I limiti della maschera del livello |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| compressedData | byte[] |  |
| compressionMethod | short |  |
| larghezza | int |  |
| altezza | int |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| compressionMethod | short |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


Clona le informazioni del canale specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | Le informazioni. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - La maschera del livello clonata.
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
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


Ottiene la profondità di bit del canale.

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


Ottiene o imposta l'ID del canale.

Valore: L'ID del canale.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


Ottiene o imposta il metodo di compressione.

Valore: Il metodo di compressione.

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


Ottiene o imposta i dati del canale.

Valore: I dati del canale.

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


Ottiene la lunghezza del canale in byte.

Valore: La lunghezza.

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


Ottiene la versione del PSD

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


Ottiene i dati non compressi.

**Returns:**
byte[] -
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isShortMaskChannel_internalized() {#isShortMaskChannel-internalized--}
```
public final boolean isShortMaskChannel_internalized()
```


Verifica se il canale è ShortMask o meno

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveChannelData_internalized(StreamContainer streamContainer) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


Salva i dati del canale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare. |
| is32BitColor | boolean | true se il colore è in modalità a 32 bit |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


Ottiene o imposta l'ID del canale.

Valore: L'ID del canale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


Imposta i dati compressi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| compressedData | byte[] | I dati compressi. |
| channelWidth | int | Larghezza del canale. |
| channelHeight | int | Altezza del canale. |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Ottiene o imposta il metodo di compressione.

Valore: Il metodo di compressione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


Imposta i dati compressi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rawData | byte[] | I dati grezzi. |
| imageSize | [Size](../../com.aspose.psd/size) | La dimensione dell'immagine |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | I limiti dei dati del canale corrente. Se l'immagine è grande verrà divisa durante il processo e currentBounds != imageBounds |

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

