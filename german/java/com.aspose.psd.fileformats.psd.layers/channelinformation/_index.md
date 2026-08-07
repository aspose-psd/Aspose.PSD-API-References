---
title: "ChannelInformation"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Kanalinformationen."
type: docs
weight: 13
url: /de/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

Die Kanalinformationen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | Die Benutzer-(Raster)-Maskenkanal-ID. |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | Die kurze (Raster- oder Vektor-)Maskenkanal-ID. |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | Die Alpha-Kanal-ID |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Sie komprimiert Kanaldaten |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Dupliziert die angegebene Kanalinformation. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | Ermittelt die Kanal-Bit-Tiefe. |
| [getChannelID()](#getChannelID--) | Ermittelt oder setzt die Kanal-ID. |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | Ermittelt oder setzt die Komprimierungsmethode. |
| [getData_internalized()](#getData-internalized--) | Ermittelt oder setzt die Kanaldaten. |
| [getLength()](#getLength--) | Ermittelt die Kanal-Länge in Bytes. |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | Ermittelt die Version von PSD |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | Ermittelt die unkomprimierten Daten. |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | Ermittelt, ob der Kanal ein ShortMask ist oder nicht |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | Speichert die Kanaldaten. |
| [setChannelID(short value)](#setChannelID-short-) | Ermittelt oder setzt die Kanal-ID. |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | Setzt die komprimierten Daten. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Ermittelt oder setzt die Komprimierungsmethode. |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | Setzt die komprimierten Daten. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| compressionMethod | short |  |
| BitTiefe | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


Die Benutzer-(Raster)-Maskenkanal-ID. (wenn eine Ebene sowohl Vektor- als auch Rastermasken hat).

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


Die kurze (Raster- oder Vektor-)Maskenkanal-ID. (wenn eine Ebene nur eine Vektor- oder Rastermaske hat, aber nicht beide).

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


Die Alpha-Kanal-ID

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


Sie komprimiert Kanaldaten

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rawData | byte[] | Die Rohdaten für die Komprimierung |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Die Grenzen der Ebene |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | Die Grenzen der Ebenenmaske |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| compressedData | byte[] |  |
| compressionMethod | short |  |
| Breite | int |  |
| Höhe | int |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| compressionMethod | short |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


Dupliziert die angegebene Kanalinformation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | Die Information. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - Die geklonte Ebenenmaske.
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
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


Ermittelt die Kanal-Bit-Tiefe.

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


Ermittelt oder setzt die Kanal-ID.

Wert: Die Kanal-ID.

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


Ermittelt oder setzt die Komprimierungsmethode.

Wert: Die Komprimierungsmethode.

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


Ermittelt oder setzt die Kanaldaten.

Wert: Die Kanaldaten.

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


Ermittelt die Kanal-Länge in Bytes.

Wert: Die Länge.

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


Ermittelt die Version von PSD

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


Ermittelt die unkomprimierten Daten.

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


Ermittelt, ob der Kanal ein ShortMask ist oder nicht

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


Speichert die Kanaldaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert wird. |
| is32BitColor | boolean | true, wenn die Farbe im 32‑Bit‑Modus ist |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


Ermittelt oder setzt die Kanal-ID.

Wert: Die Kanal-ID.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


Setzt die komprimierten Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| compressedData | byte[] | Die komprimierten Daten. |
| channelWidth | int | Breite des Kanals. |
| channelHeight | int | Höhe des Kanals. |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Ermittelt oder setzt die Komprimierungsmethode.

Wert: Die Komprimierungsmethode.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


Setzt die komprimierten Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rawData | byte[] | Die Rohdaten. |
| imageSize | [Size](../../com.aspose.psd/size) | Die Größe des Bildes |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | Die Grenzen der aktuellen channelData. Wenn das Bild groß ist, wird es im Prozess aufgeteilt und currentBounds != imageBounds |

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

