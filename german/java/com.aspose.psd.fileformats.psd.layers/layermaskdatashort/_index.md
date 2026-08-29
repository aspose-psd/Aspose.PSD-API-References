---
title: "LayerMaskDataShort"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Definiert die Klasse LayerMaskDataShort, die Informationen über die Maskendaten in der PSD-Dateiebene enthält, wenn die Ebene nur Raster‑ oder Vektormasken, jedoch nicht beide, hat."
type: docs
weight: 23
url: /de/java/com.aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataShort extends LayerMaskData
```

Definiert die LayerMaskDataShort‑Klasse, die Informationen über die Maskendaten im PSD‑Dateilayer enthält, wenn der Layer nur eine Raster‑ oder Vektormaske, jedoch nicht beide, hat. Andernfalls wird ein [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) verwendet. Hat der Layer nur eine Rastermaske, enthält die ImageData die Rastermaskendaten‑Bytes. Hat der Layer nur eine Vektormaske, enthält die ImageData die gerasterten (zwischengespeicherten) Vektormasken‑Bytes. Die Länge der LayerMaskData.ImageData‑Bytes ([LayerMaskData.getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[LayerMaskData.setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) sollte gleich Width \* Height der LayerMaskData.MaskRectangle‑Eigenschaften ([LayerMaskData.getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[LayerMaskData.setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)) sein.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LayerMaskDataShort()](#LayerMaskDataShort--) | Initialisiert eine neue Instanz der [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [create_internalized(PixelsData pixelsData)](#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-) |  |
| [deepClone_internalized()](#deepClone-internalized--) | Klont diese Instanz. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Klont die Ebenenmaske. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | Liest oder setzt die Position der unteren Ebenenmaske. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Gibt die Größe der Ebenenmasken‑Daten zurück. |
| [getDefaultColor()](#getDefaultColor--) | Liest oder setzt die Standardfarbe. |
| [getFlags()](#getFlags--) | Liest oder setzt die Flags der Ebenenmaske. |
| [getHeight_internalized()](#getHeight-internalized--) | Liest die Maskenhöhe. |
| [getImageData()](#getImageData--) | Liest oder setzt die Ebenenmaskendaten (oder kombinierte/abschließende Maske, falls eine Vektormaske vorhanden ist) in der PSD-Datei. |
| [getLeft()](#getLeft--) | Liest oder setzt die linke Position der Ebenenmaske. |
| [getMaskRectangle()](#getMaskRectangle--) | Liest oder setzt das  Rectangle  der Ebenenmaske in der PSD-Datei. |
| [getPadding()](#getPadding--) | Ruft das Layer‑Masken‑Padding ab oder legt es fest. |
| [getRight()](#getRight--) | Liest oder setzt die rechte Position der Ebenenmaske. |
| [getTop()](#getTop--) | Liest oder setzt die obere Position der Ebenenmaske. |
| [getWidth_internalized()](#getWidth-internalized--) | Liest die Maskenbreite. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Speichert [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) in den angegebenen  StreamContainer . |
| [setBottom(int value)](#setBottom-int-) | Liest oder setzt die Position der unteren Ebenenmaske. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Liest oder setzt die Standardfarbe. |
| [setFlags(byte value)](#setFlags-byte-) | Liest oder setzt die Flags der Ebenenmaske. |
| [setImageData(byte[] value)](#setImageData-byte---) | Liest oder setzt die Ebenenmaskendaten (oder kombinierte/abschließende Maske, falls eine Vektormaske vorhanden ist) in der PSD-Datei. |
| [setLeft(int value)](#setLeft-int-) | Liest oder setzt die linke Position der Ebenenmaske. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Liest oder setzt das  Rectangle  der Ebenenmaske in der PSD-Datei. |
| [setPadding(short value)](#setPadding-short-) | Ruft das Layer‑Masken‑Padding ab oder legt es fest. |
| [setRight(int value)](#setRight-int-) | Liest oder setzt die rechte Position der Ebenenmaske. |
| [setTop(int value)](#setTop-int-) | Liest oder setzt die obere Position der Ebenenmaske. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataShort() {#LayerMaskDataShort--}
```
public LayerMaskDataShort()
```


Initialisiert eine neue Instanz der [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) Klasse.

### create_internalized(PixelsData pixelsData) {#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-}
```
public static LayerMaskDataShort create_internalized(PixelsData pixelsData)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixelsData | [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) |  |

**Returns:**
[LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort)
### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


Klont diese Instanz.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


Klont die Ebenenmaske.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Die Maske. |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Liest oder setzt die Position der unteren Ebenenmaske.

Wert: Die untere Position der Ebenenmaske.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public final int getDataSize()
```


Gibt die Größe der Ebenenmasken‑Daten zurück.

Wert: Die Größe der Ebenenmaskendaten.

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


Liest oder setzt die Standardfarbe.

Wert: Die Standardfarbe.

**Returns:**
byte
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Liest oder setzt die Flags der Ebenenmaske.

Wert: Die Ebenenmasken-Flags.

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


Liest die Maskenhöhe.

Wert: Die Höhe.

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Liest oder setzt die Ebenenmaskendaten (oder kombinierte/abschließende Maske, falls eine Vektormaske vorhanden ist) in der PSD-Datei.

Wert: Die Bilddaten.

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Liest oder setzt die linke Position der Ebenenmaske.

Wert: Die linke Position der Ebenenmaske.

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


Liest oder setzt das  Rectangle  der Ebenenmaske in der PSD-Datei. Es nimmt die Eigenschaften links, rechts, oben und unten und erstellt ein  Rectangle.

Wert: Das Masken‑Rectangle.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getPadding() {#getPadding--}
```
public final short getPadding()
```


Ruft das Layer‑Masken‑Padding ab oder legt es fest.

Wert: Das Layer‑Masken‑Padding.

**Returns:**
short
### getRight() {#getRight--}
```
public final int getRight()
```


Liest oder setzt die rechte Position der Ebenenmaske.

Wert: Die rechte Position der Ebenenmaske.

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


Liest oder setzt die obere Position der Ebenenmaske.

Wert: Die obere Position der Ebenenmaske.

**Returns:**
int
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


Liest die Maskenbreite.

Wert: Die Breite.

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public void save_internalized(StreamContainer streamContainer)
```


Speichert [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) in den angegebenen  StreamContainer .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der StreamContainer, in dem die Daten gespeichert werden sollen. |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Liest oder setzt die Position der unteren Ebenenmaske.

Wert: Die untere Position der Ebenenmaske.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


Liest oder setzt die Standardfarbe.

Wert: Die Standardfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Liest oder setzt die Flags der Ebenenmaske.

Wert: Die Ebenenmasken-Flags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


Liest oder setzt die Ebenenmaskendaten (oder kombinierte/abschließende Maske, falls eine Vektormaske vorhanden ist) in der PSD-Datei.

Wert: Die Bilddaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Liest oder setzt die linke Position der Ebenenmaske.

Wert: Die linke Position der Ebenenmaske.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


Liest oder setzt das  Rectangle  der Ebenenmaske in der PSD-Datei. Es nimmt die Eigenschaften links, rechts, oben und unten und erstellt ein  Rectangle.

Wert: Das Masken‑Rectangle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPadding(short value) {#setPadding-short-}
```
public final void setPadding(short value)
```


Ruft das Layer‑Masken‑Padding ab oder legt es fest.

Wert: Das Layer‑Masken‑Padding.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Liest oder setzt die rechte Position der Ebenenmaske.

Wert: Die rechte Position der Ebenenmaske.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Liest oder setzt die obere Position der Ebenenmaske.

Wert: Die obere Position der Ebenenmaske.

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

