---
title: "PattResourceData"
second_title: "Aspose.PSD för Java API-referens"
description: "Klassen för att lagra mönsterdata för resursen."
type: docs
weight: 67
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Inheritance:**
java.lang.Object
```
public final class PattResourceData
```

Klassen för att lagra mönsterdata för resursen [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource).
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PattResourceData()](#PattResourceData--) | Initierar en ny instans av klassen [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createNewInstance_internalized()](#createNewInstance-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelsCompressionMode_internalized()](#getChannelsCompressionMode-internalized--) | Returnerar komprimeringsmetodkoden som erhållits från mönstrets kanaler. |
| [getClass()](#getClass--) |  |
| [getDefaultPattern_internalized()](#getDefaultPattern-internalized--) | Skapar standardmönsterdata. |
| [getHeight()](#getHeight--) | Hämtar höjden. |
| [getImageMode()](#getImageMode--) | Hämtar bildläget. |
| [getLength()](#getLength--) | Hämtar längden på mönstret. |
| [getName()](#getName--) | Hämtar eller anger namnet. |
| [getPatternData()](#getPatternData--) | Hämtar mönsterdata. |
| [getPatternDataArrayList_internalized()](#getPatternDataArrayList-internalized--) | Minnesarraylistan. |
| [getPatternId()](#getPatternId--) | Hämtar eller anger mönsteridentifieraren. |
| [getVersion()](#getVersion--) | Hämtar versionen. |
| [getWidth()](#getWidth--) | Hämtar bredden. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Sparar mönsterdata. |
| [setHeight_internalized(short value)](#setHeight-internalized-short-) | Hämtar höjden. |
| [setImageMode_internalized(short value)](#setImageMode-internalized-short-) | Hämtar bildläget. |
| [setIndexColorTable_internalized(byte[] value)](#setIndexColorTable-internalized-byte---) | Hämtar eller anger indexfärgtabellen. |
| [setName(String value)](#setName-java.lang.String-) | Hämtar eller anger namnet. |
| [setPattern(int[] pixels, Rectangle bounds)](#setPattern-int---com.aspose.psd.Rectangle-) | Ställer in mönsterpixelbufferten och målstorleken, uppdaterar  Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) /  Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), och lagrar data för sparande med standardkomprimeringsläget (0). |
| [setPatternDataArrayList_internalized(VirtualMemoryArrayList value)](#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-) | Minnesarraylistan. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Hämtar eller anger mönsteridentifieraren. |
| [setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)](#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-) | Ställer in mönsterpixelbufferten och målstorleken, uppdaterar  Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) /  Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), och lagrar data för sparande med det angivna komprimeringsläget. |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Hämtar versionen. |
| [setWidth_internalized(short value)](#setWidth-internalized-short-) | Hämtar bredden. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResourceData() {#PattResourceData--}
```
public PattResourceData()
```


Initierar en ny instans av klassen [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata).

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getChannelsCompressionMode_internalized() {#getChannelsCompressionMode-internalized--}
```
public final byte getChannelsCompressionMode_internalized()
```


Returnerar komprimeringsmetodkoden som erhållits från mönstrets kanaler.

**Returns:**
byte - Komprimeringskod: 0 \\u2014 raw/okomprimerad; >= 1 \\u2014 zip.
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


Skapar standardmönsterdata.

**Returns:**
[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) - The default pattern data.
### getHeight() {#getHeight--}
```
public final short getHeight()
```


Hämtar höjden.

Värde: Höjden.

**Returns:**
short
### getImageMode() {#getImageMode--}
```
public final short getImageMode()
```


Hämtar bildläget.

Värde: Bildläget.

**Returns:**
short
### getLength() {#getLength--}
```
public final int getLength()
```


Hämtar längden på mönstret.

Värde: Mönstrets längd.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Hämtar eller anger namnet.

Värde: Namnet.

**Returns:**
java.lang.String
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Hämtar mönsterdata.

Värde: Mönsterdata.

**Returns:**
int[]
### getPatternDataArrayList_internalized() {#getPatternDataArrayList-internalized--}
```
public final VirtualMemoryArrayList getPatternDataArrayList_internalized()
```


Minnesarraylistan.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Hämtar eller anger mönsteridentifieraren.

Värde: Mönsteridentifieraren.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Hämtar versionen.

Värde: Versionen.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final short getWidth()
```


Hämtar bredden.

Värde: Bredden.

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


Sparar mönsterdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren att spara till. |

### setHeight_internalized(short value) {#setHeight-internalized-short-}
```
public final void setHeight_internalized(short value)
```


Hämtar höjden.

Värde: Höjden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setImageMode_internalized(short value) {#setImageMode-internalized-short-}
```
public final void setImageMode_internalized(short value)
```


Hämtar bildläget.

Värde: Bildläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setIndexColorTable_internalized(byte[] value) {#setIndexColorTable-internalized-byte---}
```
public final void setIndexColorTable_internalized(byte[] value)
```


Hämtar eller anger indexfärgtabellen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Hämtar eller anger namnet.

Värde: Namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPattern(int[] pixels, Rectangle bounds) {#setPattern-int---com.aspose.psd.Rectangle-}
```
public final void setPattern(int[] pixels, Rectangle bounds)
```


Ställer in mönsterpixelbufferten och målstorleken, uppdaterar  Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) /  Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), och lagrar data för sparande med standardkomprimeringsläget (0).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | 32-bit pixlar i  0xAARRGGBB  format. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Pixelgränser för mönstret. |

### setPatternDataArrayList_internalized(VirtualMemoryArrayList value) {#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-}
```
public final void setPatternDataArrayList_internalized(VirtualMemoryArrayList value)
```


Minnesarraylistan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Hämtar eller anger mönsteridentifieraren.

Värde: Mönsteridentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode) {#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-}
```
public final void setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)
```


Ställer in mönsterpixelbufferten och målstorleken, uppdaterar  Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) /  Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), och lagrar data för sparande med det angivna komprimeringsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | 32-bit pixlar i  0xAARRGGBB  format. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Pixelgränser för mönstret. |
| compressionMode | byte | Komprimeringsläget som används för att definiera komprimeringen av mönsterdata vid sparning av psd‑fil. |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Hämtar versionen.

Värde: Versionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setWidth_internalized(short value) {#setWidth-internalized-short-}
```
public final void setWidth_internalized(short value)
```


Hämtar bredden.

Värde: Bredden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

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

