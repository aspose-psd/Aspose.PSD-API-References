---
title: "ChannelInformation"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De kanaalinformatie."
type: docs
weight: 13
url: /nl/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

De kanaalinformatie.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | De gebruikers (raster) maskerkanaal-ID. |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | De korte (raster of vector) maskerkanaal-ID. |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | De alfa-kanaal-ID |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Het comprimeert kanaalgegevens |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Kloont de opgegeven kanaalinformatie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | Haalt de kanaal-bitdiepte op. |
| [getChannelID()](#getChannelID--) | Haalt op of stelt de kanaal-ID in. |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | Haalt op of stelt de compressiemethode in. |
| [getData_internalized()](#getData-internalized--) | Haalt op of stelt de kanaalgegevens in. |
| [getLength()](#getLength--) | Haalt de kanaallengte op in bytes. |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | Haalt de versie van PSD op |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | Haalt de ongecomprimeerde gegevens op. |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | Haalt op of het kanaal een ShortMask is of niet |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | Slaat de kanaalgegevens op. |
| [setChannelID(short value)](#setChannelID-short-) | Haalt op of stelt de kanaal-ID in. |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | Stelt de gecomprimeerde gegevens in. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Haalt op of stelt de compressiemethode in. |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | Stelt de gecomprimeerde gegevens in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| compressionMethod | short |  |
| bitDepth | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


De gebruikers‑(raster) maskerkanaal‑ID. (als een laag zowel vector‑ als rastermasker heeft).

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


De korte (raster‑ of vector‑) maskerkanaal‑ID. (als een laag slechts één vector‑ of rastermasker heeft, maar niet beide).

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


De alfa-kanaal-ID

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


Het comprimeert kanaalgegevens

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rawData | byte[] | De ruwe gegevens voor compressie |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | De grenzen van de laag |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | De grenzen van het laagmasker |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| compressedData | byte[] |  |
| compressionMethod | short |  |
| breedte | int |  |
| hoogte | int |  |
| koptekst | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| compressionMethod | short |  |
| koptekst | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


Kloont de opgegeven kanaalinformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | De informatie. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - Het gekloonde laagmasker.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


Haalt de kanaal-bitdiepte op.

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


Haalt op of stelt de kanaal-ID in.

Waarde: De kanaal‑ID.

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


Haalt op of stelt de compressiemethode in.

Waarde: De compressiemethode.

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


Haalt op of stelt de kanaalgegevens in.

Waarde: De kanaalgegevens.

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


Haalt de kanaallengte op in bytes.

Waarde: De lengte.

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


Haalt de versie van PSD op

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


Haalt de ongecomprimeerde gegevens op.

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


Haalt op of het kanaal een ShortMask is of niet

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


Slaat de kanaalgegevens op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De streamcontainer om naar op te slaan. |
| is32BitColor | boolean | waar als de kleur in 32‑bit‑modus is |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


Haalt op of stelt de kanaal-ID in.

Waarde: De kanaal‑ID.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


Stelt de gecomprimeerde gegevens in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| compressedData | byte[] | De gecomprimeerde gegevens. |
| channelWidth | int | Breedte van het kanaal. |
| channelHeight | int | Hoogte van het kanaal. |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Haalt op of stelt de compressiemethode in.

Waarde: De compressiemethode.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


Stelt de gecomprimeerde gegevens in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rawData | byte[] | De ruwe gegevens. |
| imageSize | [Size](../../com.aspose.psd/size) | De grootte van de afbeelding |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | De grenzen van de huidige channelData. Als de afbeelding groot is, wordt deze tijdens het proces verdeeld en zijn currentBounds != imageBounds |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

