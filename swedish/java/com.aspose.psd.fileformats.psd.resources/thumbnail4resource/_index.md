---
title: "Thumbnail4Resource"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar miniatyrresursen för psd 4.0."
type: docs
weight: 34
url: /sv/java/com.aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock), [com.aspose.psd.fileformats.psd.resources.ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource)
```
public final class Thumbnail4Resource extends ThumbnailResource
```

Representerar miniatyrresursen för psd 4.0.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Thumbnail4Resource()](#Thumbnail4Resource--) | Initierar en ny instans av klassen [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Resurssignaturen för ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Den vanliga Photoshop-resurssignaturen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | Hämtar eller anger bitpixlarna. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Hämtar resursens datastorlek i byte. |
| [getFormat()](#getFormat--) | Hämtar eller anger miniatyrbildens dataformat. |
| [getHeight()](#getHeight--) | Hämtar eller anger miniatyrbildens höjd i pixlar. |
| [getID()](#getID--) | Hämtar eller anger den unika identifieraren för resursen. |
| [getJpegOptions()](#getJpegOptions--) | Hämtar eller anger JPEG-alternativen. |
| [getMinimalVersion()](#getMinimalVersion--) | Hämtar den minsta erforderliga PSD-versionen. |
| [getName()](#getName--) | Hämtar eller anger resursnamnet. |
| [getPlanesCount()](#getPlanesCount--) | Hämtar eller anger antalet plan. |
| [getSignature()](#getSignature--) | Hämtar resurssignaturen. |
| [getSize()](#getSize--) | Hämtar resursblockets storlek i byte inklusive dess data. |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | Hämtar eller anger storleken efter komprimering. |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | Hämtar eller anger 32-bitars ARGB-miniatyrdata. |
| [getThumbnailData()](#getThumbnailData--) | Hämtar eller anger miniatyrdata. |
| [getTotalSize()](#getTotalSize--) | Hämtar den totala datastorleken. |
| [getWidth()](#getWidth--) | Hämtar eller anger miniatyrbildens bredd i pixlar. |
| [getWidthBytes()](#getWidthBytes--) | Hämtar radbredden i byte. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Sparar resursblocket till den angivna strömmen. |
| [setBitsPixel(short value)](#setBitsPixel-short-) | Hämtar eller anger bitpixlarna. |
| [setFormat(int value)](#setFormat-int-) | Hämtar eller anger miniatyrbildens dataformat. |
| [setHeight(int value)](#setHeight-int-) | Hämtar eller anger miniatyrbildens höjd i pixlar. |
| [setID(short value)](#setID-short-) | Hämtar eller anger den unika identifieraren för resursen. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Hämtar eller anger JPEG-alternativen. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Hämtar eller anger lager- och maskinformation. |
| [setName(String value)](#setName-java.lang.String-) | Hämtar eller anger resursnamnet. |
| [setPlanesCount(short value)](#setPlanesCount-short-) | Hämtar eller anger antalet plan. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Hämtar eller anger resursblockets tillstånd. |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | Hämtar eller anger 32-bitars ARGB-miniatyrdata. |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | Hämtar eller anger miniatyrdata. |
| [setWidth(int value)](#setWidth-int-) | Hämtar eller anger miniatyrbildens bredd i pixlar. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validerar resursvärdena. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Thumbnail4Resource() {#Thumbnail4Resource--}
```
public Thumbnail4Resource()
```


Initierar en ny instans av klassen [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


Resurssignaturen för ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


Den vanliga Photoshop-resurssignaturen.

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
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


Hämtar eller anger bitpixlarna.

Värde: Miniatyrbildens bitpixel.

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


Hämtar resursens datastorlek i byte.

Värde: Resursens datastorlek.

**Returns:**
int
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Hämtar eller anger miniatyrbildens dataformat.

Värde: Miniatyrbildens dataformat.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar eller anger miniatyrbildens höjd i pixlar.

Värde: Miniatyrbildens höjd.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Hämtar eller anger den unika identifieraren för resursen.

Värde: Den unika identifieraren för resursen.

**Returns:**
short
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Hämtar eller anger JPEG-alternativen. Lämplig när miniatyrresursen endast sparas i JPEG-filformat. Detta alternativ har ingen effekt när RAW-format är definierat.

Värde: JPEG-alternativen.

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Hämtar den minsta erforderliga PSD-versionen.

Värde: Den minsta psd-versionen.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två byte med 0).

Värde: Resursnamnet.

**Returns:**
java.lang.String
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


Hämtar eller anger antalet plan.

Värde: Antalet plan för miniatyrbild.

**Returns:**
short
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Hämtar resursens signatur. Ska alltid vara '8BIM'.

Värde: Resursens signatur.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Hämtar resursblockets storlek i byte inklusive dess data.

Värde: Storleken på resursblocket.

**Returns:**
int
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


Hämtar eller anger storleken efter komprimering. Används för konsistenskontroll.

Värde: Storleken efter komprimering.

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


Hämtar eller anger 32-bitars ARGB-miniatyrdata.

Värde: 32-bitars ARGB-miniatyrdata.

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


Hämtar eller anger miniatyrdata.

Värde: Miniatyrdata.

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


Hämtar den totala datastorleken.

Värde: Den totala datastorleken.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar eller anger miniatyrbildens bredd i pixlar.

Värde: Miniatyrbildens bredd.

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


Hämtar radbredden i byte.

Värde: Radbredden i byte.

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


Sparar resursblocket till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömmen att spara resursblocket till. |

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


Hämtar eller anger bitpixlarna.

Värde: Miniatyrbildens bitpixel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


Hämtar eller anger miniatyrbildens dataformat.

Värde: Miniatyrbildens dataformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Hämtar eller anger miniatyrbildens höjd i pixlar.

Värde: Miniatyrbildens höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Hämtar eller anger den unika identifieraren för resursen.

Värde: Den unika identifieraren för resursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Hämtar eller anger JPEG-alternativen. Lämplig när miniatyrresursen endast sparas i JPEG-filformat. Detta alternativ har ingen effekt när RAW-format är definierat.

Värde: JPEG-alternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Hämtar eller anger lager- och maskinformation.

Värde: Lager- och maskinformation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två byte med 0).

Värde: Resursnamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


Hämtar eller anger antalet plan.

Värde: Antalet plan för miniatyrbild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatur | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Hämtar eller anger resursblockets tillstånd.

Värde: Resursblockets tillstånd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


Hämtar eller anger 32-bitars ARGB-miniatyrdata.

Värde: 32-bitars ARGB-miniatyrdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


Hämtar eller anger miniatyrdata.

Värde: Miniatyrdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Hämtar eller anger miniatyrbildens bredd i pixlar.

Värde: Miniatyrbildens bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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


Validerar resursvärdena.

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

