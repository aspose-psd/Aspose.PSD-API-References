---
title: "PattResourceData"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Klasse zum Speichern der Musterdaten für die Ressource."
type: docs
weight: 67
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Inheritance:**
java.lang.Object
```
public final class PattResourceData
```

Die Klasse zum Speichern der Musterdaten für die [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) Ressource.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PattResourceData()](#PattResourceData--) | Initialisiert eine neue Instanz der [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createNewInstance_internalized()](#createNewInstance-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelsCompressionMode_internalized()](#getChannelsCompressionMode-internalized--) | Gibt den Komprimierungsmethoden-Code zurück, der aus den Kanälen des Musters erhalten wurde. |
| [getClass()](#getClass--) |  |
| [getDefaultPattern_internalized()](#getDefaultPattern-internalized--) | Erstellt die Standard-Musterdaten. |
| [getHeight()](#getHeight--) | Liest die Höhe. |
| [getImageMode()](#getImageMode--) | Liest den Bildmodus. |
| [getLength()](#getLength--) | Liest die Länge des Musters. |
| [getName()](#getName--) | Liest oder setzt den Namen. |
| [getPatternData()](#getPatternData--) | Liest die Musterdaten. |
| [getPatternDataArrayList_internalized()](#getPatternDataArrayList-internalized--) | Die Speicher-Array-Liste. |
| [getPatternId()](#getPatternId--) | Liest oder setzt die Musterkennung. |
| [getVersion()](#getVersion--) | Liefert die Version. |
| [getWidth()](#getWidth--) | Liefert die Breite. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Speichert die Musterdaten. |
| [setHeight_internalized(short value)](#setHeight-internalized-short-) | Liest die Höhe. |
| [setImageMode_internalized(short value)](#setImageMode-internalized-short-) | Liest den Bildmodus. |
| [setIndexColorTable_internalized(byte[] value)](#setIndexColorTable-internalized-byte---) | Liest oder setzt die Indexfarbtabelle. |
| [setName(String value)](#setName-java.lang.String-) | Liest oder setzt den Namen. |
| [setPattern(int[] pixels, Rectangle bounds)](#setPattern-int---com.aspose.psd.Rectangle-) | Legt den Pixelpuffer des Musters und die Zielgröße fest, aktualisiert die Breite ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Höhe ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), und speichert die Daten zum Speichern unter Verwendung des Standardkomprimierungsmodus (0). |
| [setPatternDataArrayList_internalized(VirtualMemoryArrayList value)](#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-) | Die Speicher-Array-Liste. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Liest oder setzt die Musterkennung. |
| [setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)](#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-) | Legt den Pixelpuffer des Musters und die Zielgröße fest, aktualisiert die Breite ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Höhe ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), und speichert die Daten zum Speichern unter Verwendung des angegebenen Komprimierungsmodus. |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Liefert die Version. |
| [setWidth_internalized(short value)](#setWidth-internalized-short-) | Liefert die Breite. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResourceData() {#PattResourceData--}
```
public PattResourceData()
```


Initialisiert eine neue Instanz der [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) Klasse.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getChannelsCompressionMode_internalized() {#getChannelsCompressionMode-internalized--}
```
public final byte getChannelsCompressionMode_internalized()
```


Gibt den Komprimierungsmethoden-Code zurück, der aus den Kanälen des Musters erhalten wurde.

**Returns:**
byte - Komprimierungscode: 0 \\u2014 roh/unkomprimiert; >= 1 \\u2014 zip.
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


Erstellt die Standard-Musterdaten.

**Returns:**
[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) - The default pattern data.
### getHeight() {#getHeight--}
```
public final short getHeight()
```


Liest die Höhe.

Wert: Die Höhe.

**Returns:**
short
### getImageMode() {#getImageMode--}
```
public final short getImageMode()
```


Liest den Bildmodus.

Wert: Der Bildmodus.

**Returns:**
short
### getLength() {#getLength--}
```
public final int getLength()
```


Liest die Länge des Musters.

Wert: Die Länge des Musters.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Liest oder setzt den Namen.

Wert: Der Name.

**Returns:**
java.lang.String
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Liest die Musterdaten.

Wert: Die Musterdaten.

**Returns:**
int[]
### getPatternDataArrayList_internalized() {#getPatternDataArrayList-internalized--}
```
public final VirtualMemoryArrayList getPatternDataArrayList_internalized()
```


Die Speicher-Array-Liste.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Liest oder setzt die Musterkennung.

Wert: Der Musterbezeichner.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Liefert die Version.

Wert: Die Version.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final short getWidth()
```


Liefert die Breite.

Wert: Die Breite.

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


Speichert die Musterdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert wird. |

### setHeight_internalized(short value) {#setHeight-internalized-short-}
```
public final void setHeight_internalized(short value)
```


Liest die Höhe.

Wert: Die Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setImageMode_internalized(short value) {#setImageMode-internalized-short-}
```
public final void setImageMode_internalized(short value)
```


Liest den Bildmodus.

Wert: Der Bildmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setIndexColorTable_internalized(byte[] value) {#setIndexColorTable-internalized-byte---}
```
public final void setIndexColorTable_internalized(byte[] value)
```


Liest oder setzt die Indexfarbtabelle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Liest oder setzt den Namen.

Wert: Der Name.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPattern(int[] pixels, Rectangle bounds) {#setPattern-int---com.aspose.psd.Rectangle-}
```
public final void setPattern(int[] pixels, Rectangle bounds)
```


Legt den Pixelpuffer des Musters und die Zielgröße fest, aktualisiert die Breite ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Höhe ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), und speichert die Daten zum Speichern unter Verwendung des Standardkomprimierungsmodus (0).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] | 32‑Bit‑Pixel im 0xAARRGGBB‑Format. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Pixelgrenzen des Musters. |

### setPatternDataArrayList_internalized(VirtualMemoryArrayList value) {#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-}
```
public final void setPatternDataArrayList_internalized(VirtualMemoryArrayList value)
```


Die Speicher-Array-Liste.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Liest oder setzt die Musterkennung.

Wert: Der Musterbezeichner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode) {#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-}
```
public final void setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)
```


Legt den Pixelpuffer des Musters und die Zielgröße fest, aktualisiert die Breite ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Höhe ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), und speichert die Daten zum Speichern unter Verwendung des angegebenen Komprimierungsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] | 32‑Bit‑Pixel im 0xAARRGGBB‑Format. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Pixelgrenzen des Musters. |
| compressionMode | byte | Der Komprimierungsmodus, der verwendet wird, um die Komprimierung von Musterdaten beim Speichern einer PSD-Datei zu definieren. |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Liefert die Version.

Wert: Die Version.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setWidth_internalized(short value) {#setWidth-internalized-short-}
```
public final void setWidth_internalized(short value)
```


Liefert die Breite.

Wert: Die Breite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

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

