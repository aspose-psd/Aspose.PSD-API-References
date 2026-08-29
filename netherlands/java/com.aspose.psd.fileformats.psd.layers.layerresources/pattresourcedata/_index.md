---
title: "PattResourceData"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De klasse om de patroongegevens voor de bron op te slaan."
type: docs
weight: 67
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Inheritance:**
java.lang.Object
```
public final class PattResourceData
```

De klasse om de patroongegevens voor de [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) bron op te slaan.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PattResourceData()](#PattResourceData--) | Initialiseert een nieuw exemplaar van de klasse [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createNewInstance_internalized()](#createNewInstance-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelsCompressionMode_internalized()](#getChannelsCompressionMode-internalized--) | Retourneert de compressiemethodecode verkregen van pattern\\u2019s kanalen. |
| [getClass()](#getClass--) |  |
| [getDefaultPattern_internalized()](#getDefaultPattern-internalized--) | Maakt de standaard patroongegevens aan. |
| [getHeight()](#getHeight--) | Haalt de hoogte op. |
| [getImageMode()](#getImageMode--) | Haalt de afbeeldingsmodus op. |
| [getLength()](#getLength--) | Haalt de lengte van het patroon op. |
| [getName()](#getName--) | Haalt de naam op of stelt deze in. |
| [getPatternData()](#getPatternData--) | Haalt de patroongegevens op. |
| [getPatternDataArrayList_internalized()](#getPatternDataArrayList-internalized--) | De geheugenarraylijst. |
| [getPatternId()](#getPatternId--) | Haalt de patroon‑identificatie op of stelt deze in. |
| [getVersion()](#getVersion--) | Haalt de versie op. |
| [getWidth()](#getWidth--) | Haalt de breedte op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Slaat de patroongegevens op. |
| [setHeight_internalized(short value)](#setHeight-internalized-short-) | Haalt de hoogte op. |
| [setImageMode_internalized(short value)](#setImageMode-internalized-short-) | Haalt de afbeeldingsmodus op. |
| [setIndexColorTable_internalized(byte[] value)](#setIndexColorTable-internalized-byte---) | Haalt de indexkleurentabel op of stelt deze in. |
| [setName(String value)](#setName-java.lang.String-) | Haalt de naam op of stelt deze in. |
| [setPattern(int[] pixels, Rectangle bounds)](#setPattern-int---com.aspose.psd.Rectangle-) | Stelt de patroon-pixelbuffer en doelgrootte in, werkt Breedte ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Hoogte ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)) bij, en slaat de gegevens op voor opslaan met de standaardcompressiemodus (0). |
| [setPatternDataArrayList_internalized(VirtualMemoryArrayList value)](#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-) | De geheugenarraylijst. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Haalt de patroon‑identificatie op of stelt deze in. |
| [setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)](#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-) | Stelt de patroon-pixelbuffer en doelgrootte in, werkt Breedte ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Hoogte ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)) bij, en slaat de gegevens op voor opslaan met de opgegeven compressiemodus. |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Haalt de versie op. |
| [setWidth_internalized(short value)](#setWidth-internalized-short-) | Haalt de breedte op. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResourceData() {#PattResourceData--}
```
public PattResourceData()
```


Initialiseert een nieuw exemplaar van de klasse [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata).

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getChannelsCompressionMode_internalized() {#getChannelsCompressionMode-internalized--}
```
public final byte getChannelsCompressionMode_internalized()
```


Retourneert de compressiemethodecode verkregen van pattern\\u2019s kanalen.

**Returns:**
byte - Compressiecode: 0 \\u2014 raw/onbewerkt; >= 1 \\u2014 zip.
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


Maakt de standaard patroongegevens aan.

**Returns:**
[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) - The default pattern data.
### getHeight() {#getHeight--}
```
public final short getHeight()
```


Haalt de hoogte op.

Waarde: De hoogte.

**Returns:**
short
### getImageMode() {#getImageMode--}
```
public final short getImageMode()
```


Haalt de afbeeldingsmodus op.

Waarde: De afbeeldingsmodus.

**Returns:**
short
### getLength() {#getLength--}
```
public final int getLength()
```


Haalt de lengte van het patroon op.

Waarde: De lengte van het patroon.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Haalt de naam op of stelt deze in.

Waarde: De naam.

**Returns:**
java.lang.String
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Haalt de patroongegevens op.

Waarde: De patroongegevens.

**Returns:**
int[]
### getPatternDataArrayList_internalized() {#getPatternDataArrayList-internalized--}
```
public final VirtualMemoryArrayList getPatternDataArrayList_internalized()
```


De geheugenarraylijst.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Haalt de patroon‑identificatie op of stelt deze in.

Waarde: De patroonidentificatie.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Haalt de versie op.

Waarde: De versie.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final short getWidth()
```


Haalt de breedte op.

Waarde: De breedte.

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


Slaat de patroongegevens op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De streamcontainer om naar op te slaan. |

### setHeight_internalized(short value) {#setHeight-internalized-short-}
```
public final void setHeight_internalized(short value)
```


Haalt de hoogte op.

Waarde: De hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setImageMode_internalized(short value) {#setImageMode-internalized-short-}
```
public final void setImageMode_internalized(short value)
```


Haalt de afbeeldingsmodus op.

Waarde: De afbeeldingsmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setIndexColorTable_internalized(byte[] value) {#setIndexColorTable-internalized-byte---}
```
public final void setIndexColorTable_internalized(byte[] value)
```


Haalt de indexkleurentabel op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Haalt de naam op of stelt deze in.

Waarde: De naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setPattern(int[] pixels, Rectangle bounds) {#setPattern-int---com.aspose.psd.Rectangle-}
```
public final void setPattern(int[] pixels, Rectangle bounds)
```


Stelt de patroon-pixelbuffer en doelgrootte in, werkt Breedte ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Hoogte ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)) bij, en slaat de gegevens op voor opslaan met de standaardcompressiemodus (0).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixels | int[] | 32-bit pixels in 0xAARRGGBB formaat. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Pixelgrenzen van het patroon. |

### setPatternDataArrayList_internalized(VirtualMemoryArrayList value) {#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-}
```
public final void setPatternDataArrayList_internalized(VirtualMemoryArrayList value)
```


De geheugenarraylijst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Haalt de patroon‑identificatie op of stelt deze in.

Waarde: De patroonidentificatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode) {#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-}
```
public final void setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)
```


Stelt de patroon-pixelbuffer en doelgrootte in, werkt Breedte ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Hoogte ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)) bij, en slaat de gegevens op voor opslaan met de opgegeven compressiemodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixels | int[] | 32-bit pixels in 0xAARRGGBB formaat. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Pixelgrenzen van het patroon. |
| compressionMode | byte | De compressiemodus die wordt gebruikt om de compressie van patroongegevens bij het opslaan van een psd-bestand te definiëren. |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Haalt de versie op.

Waarde: De versie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setWidth_internalized(short value) {#setWidth-internalized-short-}
```
public final void setWidth_internalized(short value)
```


Haalt de breedte op.

Waarde: De breedte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

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

