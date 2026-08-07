---
title: "LayerMaskDataFull"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Definiert die Klasse LayerMaskDataFull, die Informationen über die Maskendaten in der PSD-Dateiebene enthält, wenn die Ebene sowohl Ebenen‑ als auch Vektormasken hat."
type: docs
weight: 22
url: /de/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

Definiert die LayerMaskDataFull‑Klasse, die Informationen über die Maskendaten im PSD‑Dateilayer enthält, wenn der Layer sowohl Ebenen‑ als auch Vektormasken hat. Andernfalls wird ein [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) verwendet. Die ImageData enthält die Rastermaske und die gerasterte Vektormaske kombiniert. Die Länge der ImageData‑Bytes sollte den Eigenschaften MaskRectangle.Width \* MaskRectangle.Height entsprechen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | Initialisiert eine neue Instanz der [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Klont diese Instanz. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Klont die Ebenenmaske. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Liest oder setzt die Hintergrundfarbe. |
| [getBottom()](#getBottom--) | Liest oder setzt die Position der unteren Ebenenmaske. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Gibt die Größe der Ebenenmasken‑Daten zurück. |
| [getDefaultColor()](#getDefaultColor--) | Liest oder setzt die Standardfarbe. |
| [getEnclosingBottom()](#getEnclosingBottom--) | Ruft die umschließende untere Rastermaskenposition im PSD‑Bildebene ab oder legt sie fest. |
| [getEnclosingLeft()](#getEnclosingLeft--) | Ruft die umschließende linke Rastermaskenposition im PSD‑Dateilayer ab oder legt sie fest. |
| [getEnclosingRight()](#getEnclosingRight--) | Ruft die umschließende rechte Rastermaskenposition im PSD‑Dateilayer ab oder legt sie fest. |
| [getEnclosingTop()](#getEnclosingTop--) | Ruft die umschließende obere Position der Rastermaske im PSD‑Bildebene ab oder legt sie fest. |
| [getFlags()](#getFlags--) | Liest oder setzt die Flags der Ebenenmaske. |
| [getHeight_internalized()](#getHeight-internalized--) | Liest die Maskenhöhe. |
| [getImageData()](#getImageData--) | Liest oder setzt die Ebenenmaskendaten (oder kombinierte/abschließende Maske, falls eine Vektormaske vorhanden ist) in der PSD-Datei. |
| [getLeft()](#getLeft--) | Liest oder setzt die linke Position der Ebenenmaske. |
| [getMaskRectangle()](#getMaskRectangle--) | Liest oder setzt das  Rectangle  der Ebenenmaske in der PSD-Datei. |
| [getRealFlags()](#getRealFlags--) | Ruft die Layer‑Masken‑Flags ab, die für die Benutzer‑/Rastermaske verwendet werden, oder legt sie fest. |
| [getRight()](#getRight--) | Liest oder setzt die rechte Position der Ebenenmaske. |
| [getTop()](#getTop--) | Liest oder setzt die obere Position der Ebenenmaske. |
| [getUserMaskData()](#getUserMaskData--) | Ruft die Benutzermaskendaten (Raster) eines Layers in der PSD‑Datei ab oder legt sie fest. |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | Ruft das umschließende Rechteck der Benutzermaske im PSD‑Bildebene ab oder legt es fest. |
| [getWidth_internalized()](#getWidth-internalized--) | Liest die Maskenbreite. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Speichert [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) in den angegebenen  StreamContainer . |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | Liest oder setzt die Hintergrundfarbe. |
| [setBottom(int value)](#setBottom-int-) | Liest oder setzt die Position der unteren Ebenenmaske. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Liest oder setzt die Standardfarbe. |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | Ruft die umschließende untere Rastermaskenposition im PSD‑Bildebene ab oder legt sie fest. |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | Ruft die umschließende linke Rastermaskenposition im PSD‑Dateilayer ab oder legt sie fest. |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | Ruft die umschließende rechte Rastermaskenposition im PSD‑Dateilayer ab oder legt sie fest. |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | Ruft die umschließende obere Position der Rastermaske im PSD‑Bildebene ab oder legt sie fest. |
| [setFlags(byte value)](#setFlags-byte-) | Liest oder setzt die Flags der Ebenenmaske. |
| [setImageData(byte[] value)](#setImageData-byte---) | Liest oder setzt die Ebenenmaskendaten (oder kombinierte/abschließende Maske, falls eine Vektormaske vorhanden ist) in der PSD-Datei. |
| [setLeft(int value)](#setLeft-int-) | Liest oder setzt die linke Position der Ebenenmaske. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Liest oder setzt das  Rectangle  der Ebenenmaske in der PSD-Datei. |
| [setRealFlags(byte value)](#setRealFlags-byte-) | Ruft die Layer‑Masken‑Flags ab, die für die Benutzer‑/Rastermaske verwendet werden, oder legt sie fest. |
| [setRight(int value)](#setRight-int-) | Liest oder setzt die rechte Position der Ebenenmaske. |
| [setTop(int value)](#setTop-int-) | Liest oder setzt die obere Position der Ebenenmaske. |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | Ruft die Benutzermaskendaten (Raster) eines Layers in der PSD‑Datei ab oder legt sie fest. |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | Ruft das umschließende Rechteck der Benutzermaske im PSD‑Bildebene ab oder legt es fest. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


Initialisiert eine neue Instanz der [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) Klasse.

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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


Liest oder setzt die Hintergrundfarbe.

Wert: Die Hintergrundfarbe.

**Returns:**
byte
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
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


Ruft die umschließende untere Rastermaskenposition im PSD‑Bildebene ab oder legt sie fest.

Wert: Die untere Position der Ebenenmaske.

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


Ruft die umschließende linke Rastermaskenposition im PSD‑Dateilayer ab oder legt sie fest.

Wert: Die linke Position der Ebenenmaske.

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


Ruft die umschließende rechte Rastermaskenposition im PSD‑Dateilayer ab oder legt sie fest.

Wert: Die rechte Position der Ebenenmaske.

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


Ruft die umschließende obere Position der Rastermaske im PSD‑Bildebene ab oder legt sie fest.

Wert: Die obere Position der Ebenenmaske.

**Returns:**
int
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
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


Ruft die Layer‑Masken‑Flags ab, die für die Benutzer‑/Rastermaske verwendet werden, oder legt sie fest. Für Vektormasken wird die Eigenschaft Flags verwendet.

Wert: Die tatsächlichen Layer‑Masken‑Flags.

**Returns:**
byte
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
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


Ruft die Benutzermaskendaten (Raster) eines Layers in der PSD‑Datei ab oder legt sie fest. (Im MaskData‑Property befindet sich eine gerasterte Vektormaske).

Wert: Die Layer‑Bilddaten im PSD‑Bild.

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


Ruft das umschließende Rechteck der Benutzermaske im PSD‑Bildebene ab oder legt es fest.

Wert: Das Benutzermasken‑Rechteck.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


Liest oder setzt die Hintergrundfarbe.

Wert: Die Hintergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

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

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


Ruft die umschließende untere Rastermaskenposition im PSD‑Bildebene ab oder legt sie fest.

Wert: Die untere Position der Ebenenmaske.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


Ruft die umschließende linke Rastermaskenposition im PSD‑Dateilayer ab oder legt sie fest.

Wert: Die linke Position der Ebenenmaske.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


Ruft die umschließende rechte Rastermaskenposition im PSD‑Dateilayer ab oder legt sie fest.

Wert: Die rechte Position der Ebenenmaske.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


Ruft die umschließende obere Position der Rastermaske im PSD‑Bildebene ab oder legt sie fest.

Wert: Die obere Position der Ebenenmaske.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


Ruft die Layer‑Masken‑Flags ab, die für die Benutzer‑/Rastermaske verwendet werden, oder legt sie fest. Für Vektormasken wird die Eigenschaft Flags verwendet.

Wert: Die tatsächlichen Layer‑Masken‑Flags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

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

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


Ruft die Benutzermaskendaten (Raster) eines Layers in der PSD‑Datei ab oder legt sie fest. (Im MaskData‑Property befindet sich eine gerasterte Vektormaske).

Wert: Die Layer‑Bilddaten im PSD‑Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


Ruft das umschließende Rechteck der Benutzermaske im PSD‑Bildebene ab oder legt es fest.

Wert: Das Benutzermasken‑Rechteck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

