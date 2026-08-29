---
title: "ChannelInformation"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La información del canal."
type: docs
weight: 13
url: /es/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

La información del canal.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | El Id del canal de máscara (raster) del usuario. |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | El Id del canal de máscara corto (raster o vector). |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | El Id del canal alfa |
## Métodos

| Método | Descripción |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Comprime los datos del canal |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Clona la información del canal especificada. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | Obtiene la profundidad de bits del canal. |
| [getChannelID()](#getChannelID--) | Obtiene o establece el ID del canal. |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | Obtiene o establece el método de compresión. |
| [getData_internalized()](#getData-internalized--) | Obtiene o establece los datos del canal. |
| [getLength()](#getLength--) | Obtiene la longitud del canal en bytes. |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | Obtiene la versión del PSD |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | Obtiene los datos descomprimidos. |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | Obtiene si el canal es ShortMask o no |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | Guarda los datos del canal. |
| [setChannelID(short value)](#setChannelID-short-) | Obtiene o establece el ID del canal. |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | Establece los datos comprimidos. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Obtiene o establece el método de compresión. |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | Establece los datos comprimidos. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| compressionMethod | short |  |
| bitDepth | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


El Id del canal de máscara de usuario (raster). (si una capa tiene tanto máscara vectorial como raster).

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


El Id del canal de máscara corta (raster o vector). (si una capa tiene solo una máscara vectorial o raster pero no ambas).

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


El Id del canal alfa

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


Comprime los datos del canal

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rawData | byte[] | Los datos sin comprimir para la compresión. |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Los límites de la capa |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | Los límites de la máscara de capa |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| compressedData | byte[] |  |
| compressionMethod | short |  |
| ancho | int |  |
| alto | int |  |
| encabezado | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| compressionMethod | short |  |
| encabezado | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


Clona la información del canal especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | La información. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - La máscara de capa clonada.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


Obtiene la profundidad de bits del canal.

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


Obtiene o establece el ID del canal.

Valor: El ID del canal.

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


Obtiene o establece el método de compresión.

Valor: El método de compresión.

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


Obtiene o establece los datos del canal.

Valor: Los datos del canal.

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


Obtiene la longitud del canal en bytes.

Valor: La longitud.

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


Obtiene la versión del PSD

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


Obtiene los datos descomprimidos.

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


Obtiene si el canal es ShortMask o no

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


Guarda los datos del canal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |
| is32BitColor | boolean | true si el color está en modo de 32 bits |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


Obtiene o establece el ID del canal.

Valor: El ID del canal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


Establece los datos comprimidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| compressedData | byte[] | Los datos comprimidos. |
| channelWidth | int | Ancho del canal. |
| channelHeight | int | Altura del canal. |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Obtiene o establece el método de compresión.

Valor: El método de compresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


Establece los datos comprimidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rawData | byte[] | Los datos sin procesar. |
| imageSize | [Size](../../com.aspose.psd/size) | El tamaño de la imagen |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | Los límites de los datos del canal actual. Si la imagen es grande se dividirá durante el proceso y los límites actuales != los límites de la imagen |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

