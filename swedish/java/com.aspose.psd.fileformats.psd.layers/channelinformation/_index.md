---
title: "ChannelInformation"
second_title: "Aspose.PSD för Java API-referens"
description: "Kanalinformationen."
type: docs
weight: 13
url: /sv/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

Kanalinformationen.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | Användarens (raster) maskkanal‑ID. |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | Kort (raster‑ eller vektor) maskkanal‑ID. |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | Alfakanal‑ID |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Den komprimerar kanaldata |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Klonar den angivna kanalinformationen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | Hämtar kanalens bitdjup. |
| [getChannelID()](#getChannelID--) | Hämtar eller anger kanal‑ID. |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | Hämtar eller anger komprimeringsmetoden. |
| [getData_internalized()](#getData-internalized--) | Hämtar eller anger kanaldata. |
| [getLength()](#getLength--) | Hämtar kanalens längd i byte. |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | Hämtar versionen av PSD |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | Hämtar de okomprimerade data. |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | Hämtar om kanalen är ShortMask eller inte |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | Sparar kanaldata. |
| [setChannelID(short value)](#setChannelID-short-) | Hämtar eller anger kanal‑ID. |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | Ställer in de komprimerade data. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Hämtar eller anger komprimeringsmetoden. |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | Ställer in de komprimerade data. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| compressionMethod | short |  |
| bitDepth | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


Användarens (raster) maskkanal‑ID. (om ett lager har både vektor‑ och rastermask).

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


Den korta (raster‑ eller vektormask) kanal‑ID. (om ett lager bara har en vektor‑ eller rastermask men inte båda).

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


Alfakanal‑ID

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


Den komprimerar kanaldata

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rawData | byte[] | De råa data för komprimering |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Gränserna för lagret |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | Gränserna för lagermasken |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| compressedData | byte[] |  |
| compressionMethod | short |  |
| bredd | int |  |
| höjd | int |  |
| rubrik | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| compressionMethod | short |  |
| rubrik | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


Klonar den angivna kanalinformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | Informationen. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - Den klonade lagermasken.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


Hämtar kanalens bitdjup.

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


Hämtar eller anger kanal‑ID.

Värde: Kanal‑ID.

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


Hämtar eller anger komprimeringsmetoden.

Värde: Komprimeringsmetoden.

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


Hämtar eller anger kanaldata.

Värde: Kanaldata.

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


Hämtar kanalens längd i byte.

Värde: Längden.

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


Hämtar versionen av PSD

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


Hämtar de okomprimerade data.

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


Hämtar om kanalen är ShortMask eller inte

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


Sparar kanaldata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| is32BitColor | boolean | true om färgen är i 32-bitarsläge |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


Hämtar eller anger kanal‑ID.

Värde: Kanal‑ID.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


Ställer in de komprimerade data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| compressedData | byte[] | De komprimerade data. |
| channelWidth | int | Bredd på kanalen. |
| channelHeight | int | Höjd på kanalen. |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Hämtar eller anger komprimeringsmetoden.

Värde: Komprimeringsmetoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


Ställer in de komprimerade data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rawData | byte[] | Rådata. |
| imageSize | [Size](../../com.aspose.psd/size) | Storleken på bilden |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | Gränserna för aktuell channelData. Om bilden är stor kommer den att delas upp under processen och currentBounds != imageBounds |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

