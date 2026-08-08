---
title: "Thumbnail4Resource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt de miniatuurresource voor psd 4.0 weer."
type: docs
weight: 34
url: /nl/java/com.aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock), [com.aspose.psd.fileformats.psd.resources.ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource)
```
public final class Thumbnail4Resource extends ThumbnailResource
```

Stelt de miniatuurresource voor psd 4.0 weer.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Thumbnail4Resource()](#Thumbnail4Resource--) | Initialiseert een nieuw exemplaar van de [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource) klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | De resourcesignatuur van ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | De reguliere Photoshop-resourcesignatuur. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | Haalt op of stelt de bits-pixel in. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Haalt de grootte van de resourcegegevens op in bytes. |
| [getFormat()](#getFormat--) | Haalt op of stelt het thumbnail-gegevensformaat in. |
| [getHeight()](#getHeight--) | Haalt op of stelt de hoogte van de thumbnail in pixels in. |
| [getID()](#getID--) | Haalt of stelt de unieke identifier voor de resource in. |
| [getJpegOptions()](#getJpegOptions--) | Haalt op of stelt de JPEG-opties in. |
| [getMinimalVersion()](#getMinimalVersion--) | Haalt de minimaal vereiste PSD-versie op. |
| [getName()](#getName--) | Haalt of stelt de resource‑naam in. |
| [getPlanesCount()](#getPlanesCount--) | Haalt op of stelt het aantal vlakken in. |
| [getSignature()](#getSignature--) | Haalt de resourcesignatuur op. |
| [getSize()](#getSize--) | Haalt de grootte van het resource‑blok op in bytes, inclusief de gegevens. |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | Haalt op of stelt de grootte na compressie in. |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | Haalt op of stelt de 32-bit ARGB-thumbnailgegevens in. |
| [getThumbnailData()](#getThumbnailData--) | Haalt op of stelt de thumbnail-gegevens in. |
| [getTotalSize()](#getTotalSize--) | Haalt de totale gegevensgrootte op. |
| [getWidth()](#getWidth--) | Haalt op of stelt de breedte van de thumbnail in pixels in. |
| [getWidthBytes()](#getWidthBytes--) | Haalt de rijbreedte in bytes op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Slaat het resource‑blok op naar de opgegeven stream. |
| [setBitsPixel(short value)](#setBitsPixel-short-) | Haalt op of stelt de bits-pixel in. |
| [setFormat(int value)](#setFormat-int-) | Haalt op of stelt het thumbnail-gegevensformaat in. |
| [setHeight(int value)](#setHeight-int-) | Haalt op of stelt de hoogte van de thumbnail in pixels in. |
| [setID(short value)](#setID-short-) | Haalt of stelt de unieke identifier voor de resource in. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Haalt op of stelt de JPEG-opties in. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Haalt of stelt de laag‑ en maskerinformatie in. |
| [setName(String value)](#setName-java.lang.String-) | Haalt of stelt de resource‑naam in. |
| [setPlanesCount(short value)](#setPlanesCount-short-) | Haalt op of stelt het aantal vlakken in. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Haalt of stelt de status van het resource‑blok in. |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | Haalt op of stelt de 32-bit ARGB-thumbnailgegevens in. |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | Haalt op of stelt de thumbnail-gegevens in. |
| [setWidth(int value)](#setWidth-int-) | Haalt op of stelt de breedte van de thumbnail in pixels in. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Valideert de resource‑waarden. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Thumbnail4Resource() {#Thumbnail4Resource--}
```
public Thumbnail4Resource()
```


Initialiseert een nieuw exemplaar van de [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource) klasse.

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


De resourcesignatuur van ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


De reguliere Photoshop-resourcesignatuur.

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
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


Haalt op of stelt de bits-pixel in.

Waarde: De thumbnail bits-pixel.

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


Haalt de grootte van de resourcegegevens op in bytes.

Waarde: De grootte van de resourcegegevens.

**Returns:**
int
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Haalt op of stelt het thumbnail-gegevensformaat in.

Waarde: Het thumbnail-gegevensformaat.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Haalt op of stelt de hoogte van de thumbnail in pixels in.

Waarde: De thumbnail-hoogte.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Haalt of stelt de unieke identifier voor de resource in.

Waarde: De unieke identifier voor de resource.

**Returns:**
short
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Haalt op of stelt de JPEG-opties in. Geschikt wanneer de thumbnail-resource alleen wordt opgeslagen in JPEG-bestandsformaat. Deze optie heeft geen effect wanneer RAW-formaat is gedefinieerd.

Waarde: De JPEG-opties.

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Haalt de minimaal vereiste PSD-versie op.

Waarde: De minimale PSD-versie.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Haalt de resource‑naam op of stelt deze in. Pascal‑string, opgevuld om de grootte even te maken (een null‑naam bestaat uit twee bytes van 0).

Waarde: De resource‑naam.

**Returns:**
java.lang.String
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


Haalt op of stelt het aantal vlakken in.

Waarde: Het aantal thumbnail-vlakken.

**Returns:**
short
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Haalt de resourcehandtekening op. Zou altijd '8BIM' moeten zijn.

Waarde: De resourcehandtekening.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Haalt de grootte van het resource‑blok op in bytes, inclusief de gegevens.

Waarde: De grootte van het resourceblok.

**Returns:**
int
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


Haalt op of stelt de grootte na compressie in. Gebruikt voor consistentiecontrole.

Waarde: De grootte na compressie.

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


Haalt op of stelt de 32-bit ARGB-thumbnailgegevens in.

Waarde: De 32-bit ARGB-thumbnailgegevens.

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


Haalt op of stelt de thumbnail-gegevens in.

Waarde: De thumbnail-gegevens.

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


Haalt de totale gegevensgrootte op.

Waarde: de totale gegevensgrootte.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Haalt op of stelt de breedte van de thumbnail in pixels in.

Waarde: de miniatuurbreedte.

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


Haalt de rijbreedte in bytes op.

Waarde: de rijbreedte in bytes.

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


Slaat het resource‑blok op naar de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream om het resourceblok op te slaan. |

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


Haalt op of stelt de bits-pixel in.

Waarde: De thumbnail bits-pixel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


Haalt op of stelt het thumbnail-gegevensformaat in.

Waarde: Het thumbnail-gegevensformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Haalt op of stelt de hoogte van de thumbnail in pixels in.

Waarde: De thumbnail-hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Haalt of stelt de unieke identifier voor de resource in.

Waarde: De unieke identifier voor de resource.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Haalt op of stelt de JPEG-opties in. Geschikt wanneer de thumbnail-resource alleen wordt opgeslagen in JPEG-bestandsformaat. Deze optie heeft geen effect wanneer RAW-formaat is gedefinieerd.

Waarde: De JPEG-opties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Haalt of stelt de laag‑ en maskerinformatie in.

Waarde: De laag‑ en maskerinformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Haalt de resource‑naam op of stelt deze in. Pascal‑string, opgevuld om de grootte even te maken (een null‑naam bestaat uit twee bytes van 0).

Waarde: De resource‑naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


Haalt op of stelt het aantal vlakken in.

Waarde: Het aantal thumbnail-vlakken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| handtekening | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Haalt of stelt de status van het resource‑blok in.

Waarde: De status van het resourceblok.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


Haalt op of stelt de 32-bit ARGB-thumbnailgegevens in.

Waarde: De 32-bit ARGB-thumbnailgegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


Haalt op of stelt de thumbnail-gegevens in.

Waarde: De thumbnail-gegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Haalt op of stelt de breedte van de thumbnail in pixels in.

Waarde: de miniatuurbreedte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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


Valideert de resource‑waarden.

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

