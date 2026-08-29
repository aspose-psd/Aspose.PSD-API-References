---
title: "LayerMaskData"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Definiert die Basisklasse LayerMaskData, die Informationen über die Ebenenmaskendaten in der PSD-Datei enthält."
type: docs
weight: 21
url: /de/java/com.aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public abstract class LayerMaskData implements Cloneable
```

Definiert die Basisklasse LayerMaskData, die Informationen über die Ebenenmaskendaten in der PSD\-Datei enthält. Sie kann dabei helfen, Adobe\ufffd Photoshop\ufffd\-Dateien programmgesteuert zu ändern und die Bearbeitung des PSD\-Formats zu automatisieren. Wenn die Ebene nur eine Rastermaske hat, enthält ImageData die Bytes der Rastermaskendaten. Wenn die Ebene nur eine Vektormaske hat, enthält ImageData die rasterisierten (zwischengespeicherten) Vektormaskendaten. Wenn die Ebene sowohl Raster\- als auch Vektormasken hat, enthält ImageData die kombinierte Rastermaske und die rasterisierte Vektormaske. Die ImageData ([getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) Byte\-Länge sollte gleich Breite \* Höhe des MaskRectangle ([getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)) Eigenschaften sein. Beachten Sie, dass das bloße Entfernen/Hinzufügen/Aktualisieren von LayerMaskData nicht ausreicht, um korrekt zu speichern, weil die Kanäle nicht aktualisiert werden; es kann jedoch eine korrekte Darstellung ermöglichen. Die Methode [Layer.addLayerMask(LayerMaskData)](../../com.aspose.psd.fileformats.psd.layers/layer\#addLayerMask-LayerMaskData-) sollte dafür verwendet werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
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
| [setRight(int value)](#setRight-int-) | Liest oder setzt die rechte Position der Ebenenmaske. |
| [setTop(int value)](#setTop-int-) | Liest oder setzt die obere Position der Ebenenmaske. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
public abstract void save_internalized(StreamContainer streamContainer)
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

