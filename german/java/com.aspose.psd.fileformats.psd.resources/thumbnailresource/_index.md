---
title: "ThumbnailResource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der Thumbnail-Ressourcenblock."
type: docs
weight: 36
url: /de/java/com.aspose.psd.fileformats.psd.resources/thumbnailresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public class ThumbnailResource extends ResourceBlock
```

Der Thumbnail-Ressourcenblock.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ThumbnailResource()](#ThumbnailResource--) | Initialisiert eine neue Instanz der Klasse [ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource). |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Die Ressourcensignatur von ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Die reguläre Photoshop‑Ressourcensignatur. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | Ruft die Bits pro Pixel ab oder legt sie fest. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Liest die Größe der Ressourcendaten in Bytes. |
| [getFormat()](#getFormat--) | Ruft das Thumbnail-Datenformat ab oder legt es fest. |
| [getHeight()](#getHeight--) | Ruft die Höhe des Thumbnails in Pixeln ab oder legt sie fest. |
| [getID()](#getID--) | Liest oder setzt die eindeutige Kennung für die Ressource. |
| [getJpegOptions()](#getJpegOptions--) | Ruft die JPEG-Optionen ab oder legt sie fest. |
| [getMinimalVersion()](#getMinimalVersion--) | Ruft die minimal erforderliche PSD-Version ab. |
| [getName()](#getName--) | Liest oder setzt den Ressourcennamen. |
| [getPlanesCount()](#getPlanesCount--) | Ruft die Anzahl der Ebenen ab oder legt sie fest. |
| [getSignature()](#getSignature--) | Ermittelt die Ressourcensignatur. |
| [getSize()](#getSize--) | Ermittelt die Größe des Ressourcenblocks in Bytes einschließlich seiner Daten. |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | Ruft die Größe nach Komprimierung ab oder legt sie fest. |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | Ruft die 32‑Bit‑ARGB-Thumbnail-Daten ab oder legt sie fest. |
| [getThumbnailData()](#getThumbnailData--) | Ruft die Thumbnail-Daten ab oder legt sie fest. |
| [getTotalSize()](#getTotalSize--) | Ruft die gesamte Datenmenge ab. |
| [getWidth()](#getWidth--) | Ruft die Breite des Thumbnails in Pixeln ab oder legt sie fest. |
| [getWidthBytes()](#getWidthBytes--) | Ruft die Zeilenbreite in Bytes ab. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Speichert den Ressourcenblock in den angegebenen Stream. |
| [setBitsPixel(short value)](#setBitsPixel-short-) | Ruft die Bits pro Pixel ab oder legt sie fest. |
| [setFormat(int value)](#setFormat-int-) | Ruft das Thumbnail-Datenformat ab oder legt es fest. |
| [setHeight(int value)](#setHeight-int-) | Ruft die Höhe des Thumbnails in Pixeln ab oder legt sie fest. |
| [setID(short value)](#setID-short-) | Liest oder setzt die eindeutige Kennung für die Ressource. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Ruft die JPEG-Optionen ab oder legt sie fest. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Liest oder setzt die Ebenen- und Maskeninformationen. |
| [setName(String value)](#setName-java.lang.String-) | Liest oder setzt den Ressourcennamen. |
| [setPlanesCount(short value)](#setPlanesCount-short-) | Ruft die Anzahl der Ebenen ab oder legt sie fest. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Liest oder setzt den Zustand des Ressourcenblocks. |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | Ruft die 32‑Bit‑ARGB-Thumbnail-Daten ab oder legt sie fest. |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | Ruft die Thumbnail-Daten ab oder legt sie fest. |
| [setWidth(int value)](#setWidth-int-) | Ruft die Breite des Thumbnails in Pixeln ab oder legt sie fest. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validiert die Ressourcenwerte. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ThumbnailResource() {#ThumbnailResource--}
```
public ThumbnailResource()
```


Initialisiert eine neue Instanz der Klasse [ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


Die Ressourcensignatur von ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


Die reguläre Photoshop‑Ressourcensignatur.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


Ruft die Bits pro Pixel ab oder legt sie fest.

Wert: Die Thumbnail-Bits pro Pixel.

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


Liest die Größe der Ressourcendaten in Bytes.

Wert: Die Größe der Ressourcendaten.

**Returns:**
int
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Ruft das Thumbnail-Datenformat ab oder legt es fest.

Wert: Das Thumbnail-Datenformat.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ruft die Höhe des Thumbnails in Pixeln ab oder legt sie fest.

Wert: Die Thumbnail-Höhe.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Liest oder setzt die eindeutige Kennung für die Ressource.

Wert: Der eindeutige Bezeichner der Ressource.

**Returns:**
short
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Liest oder setzt die JPEG-Optionen. Geeignet, wenn die Thumbnail-Ressource nur im JPEG-Dateiformat gespeichert wird. Diese Option hat keine Wirkung, wenn das RAW-Format definiert ist.

Wert: Die JPEG-Optionen.

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Ruft die minimal erforderliche PSD-Version ab.

Wert: Die minimale PSD-Version.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Liest oder setzt den Ressourcennamen. Pascal-String, aufgefüllt, um die Größe gerade zu machen (ein Null-Name besteht aus zwei Bytes von 0).

Wert: Der Ressourcename.

**Returns:**
java.lang.String
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


Ruft die Anzahl der Ebenen ab oder legt sie fest.

Wert: Die Anzahl der Thumbnail-Ebenen.

**Returns:**
short
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Ermittelt die Ressourcensignatur. Sollte immer '8BIM' sein.

Wert: Die Ressourcensignatur.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Ermittelt die Größe des Ressourcenblocks in Bytes einschließlich seiner Daten.

Wert: Die Größe des Ressourcenblocks.

**Returns:**
int
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


Liest oder setzt die Größe nach der Kompression. Wird für Konsistenzprüfungen verwendet.

Wert: Die Größe nach der Kompression.

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


Ruft die 32‑Bit‑ARGB-Thumbnail-Daten ab oder legt sie fest.

Wert: Die 32‑Bit‑ARGB‑Thumbnail-Daten.

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


Ruft die Thumbnail-Daten ab oder legt sie fest.

Wert: Die Thumbnail-Daten.

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


Ruft die gesamte Datenmenge ab.

Wert: Die Gesamtdatenmenge.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ruft die Breite des Thumbnails in Pixeln ab oder legt sie fest.

Wert: Die Thumbnail-Breite.

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


Ruft die Zeilenbreite in Bytes ab.

Wert: Die Zeilenbreite in Bytes.

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


Speichert den Ressourcenblock in den angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream, in den der Ressourcenblock gespeichert wird. |

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


Ruft die Bits pro Pixel ab oder legt sie fest.

Wert: Die Thumbnail-Bits pro Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


Ruft das Thumbnail-Datenformat ab oder legt es fest.

Wert: Das Thumbnail-Datenformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ruft die Höhe des Thumbnails in Pixeln ab oder legt sie fest.

Wert: Die Thumbnail-Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Liest oder setzt die eindeutige Kennung für die Ressource.

Wert: Der eindeutige Bezeichner der Ressource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Liest oder setzt die JPEG-Optionen. Geeignet, wenn die Thumbnail-Ressource nur im JPEG-Dateiformat gespeichert wird. Diese Option hat keine Wirkung, wenn das RAW-Format definiert ist.

Wert: Die JPEG-Optionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Liest oder setzt die Ebenen- und Maskeninformationen.

Wert: Die Ebenen- und Maskeninformationen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Liest oder setzt den Ressourcennamen. Pascal-String, aufgefüllt, um die Größe gerade zu machen (ein Null-Name besteht aus zwei Bytes von 0).

Wert: Der Ressourcename.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


Ruft die Anzahl der Ebenen ab oder legt sie fest.

Wert: Die Anzahl der Thumbnail-Ebenen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Signatur | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Liest oder setzt den Zustand des Ressourcenblocks.

Wert: Der Zustand des Ressourcenblocks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


Ruft die 32‑Bit‑ARGB-Thumbnail-Daten ab oder legt sie fest.

Wert: Die 32‑Bit‑ARGB‑Thumbnail-Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


Ruft die Thumbnail-Daten ab oder legt sie fest.

Wert: Die Thumbnail-Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ruft die Breite des Thumbnails in Pixeln ab oder legt sie fest.

Wert: Die Thumbnail-Breite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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


Validiert die Ressourcenwerte.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

