---
title: "LayerMaskDataFull"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar LayerMaskDataFull class som innehåller information om maskdata i PSD‑filens lager när lagret har både lager‑ och vektormasker."
type: docs
weight: 22
url: /sv/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

Definierar klassen LayerMaskDataFull som innehåller information om maskdata i PSD-fils lager när lagret har både lager- och vektormasker. Annars används en [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort). ImageData innehåller den rastermask och den rasteriserade vektormasken kombinerade. Längden på ImageData-byterna bör vara lika med egenskaperna MaskRectangle.Width \* MaskRectangle.Height.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | Initierar en ny instans av klassen [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Klonar den här instansen. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Klonar lagermasken. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar eller anger bakgrundsfärgen. |
| [getBottom()](#getBottom--) | Hämtar eller anger den nedre lagermaskens position. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Hämtar storleken på lagermaskens maskdata. |
| [getDefaultColor()](#getDefaultColor--) | Hämtar eller anger standardfärgen. |
| [getEnclosingBottom()](#getEnclosingBottom--) | Hämtar eller anger den omgivande nedre rastermaskens position i PSD-bildlagret. |
| [getEnclosingLeft()](#getEnclosingLeft--) | Hämtar eller anger den omgivande vänstra rastermaskens position i PSD-fils lagret. |
| [getEnclosingRight()](#getEnclosingRight--) | Hämtar eller anger den omgivande högra rastermaskens position i PSD-fils lagret. |
| [getEnclosingTop()](#getEnclosingTop--) | Hämtar eller anger den omgivande övre positionen för rastermasken i PSD-bildlagret. |
| [getFlags()](#getFlags--) | Hämtar eller anger lagermaskens flaggor. |
| [getHeight_internalized()](#getHeight-internalized--) | Hämtar maskens höjd. |
| [getImageData()](#getImageData--) | Hämtar eller anger lagermaskens data (eller kombinerad / slutgiltig mask om det finns en vektormask) i PSD‑filen. |
| [getLeft()](#getLeft--) | Hämtar eller anger den vänstra lagermaskens position. |
| [getMaskRectangle()](#getMaskRectangle--) | Hämtar eller anger maskens rektangel för lagermasken i PSD‑filen. |
| [getRealFlags()](#getRealFlags--) | Hämtar eller anger lagermaskflaggorna som används för användar‑/rastermask. |
| [getRight()](#getRight--) | Hämtar eller anger den högra lagermaskens position. |
| [getTop()](#getTop--) | Hämtar eller anger den övre lagermaskens position. |
| [getUserMaskData()](#getUserMaskData--) | Hämtar eller anger användar‑(raster) maskdata för ett lager i PSD‑filen. |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | Hämtar eller anger användarmaskens (omslutande) rektangel i PSD‑bildlagret. |
| [getWidth_internalized()](#getWidth-internalized--) | Hämtar maskens bredd. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Sparar [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) till den angivna StreamContainer. |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | Hämtar eller anger bakgrundsfärgen. |
| [setBottom(int value)](#setBottom-int-) | Hämtar eller anger den nedre lagermaskens position. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Hämtar eller anger standardfärgen. |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | Hämtar eller anger den omgivande nedre rastermaskens position i PSD-bildlagret. |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | Hämtar eller anger den omgivande vänstra rastermaskens position i PSD-fils lagret. |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | Hämtar eller anger den omgivande högra rastermaskens position i PSD-fils lagret. |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | Hämtar eller anger den omgivande övre positionen för rastermasken i PSD-bildlagret. |
| [setFlags(byte value)](#setFlags-byte-) | Hämtar eller anger lagermaskens flaggor. |
| [setImageData(byte[] value)](#setImageData-byte---) | Hämtar eller anger lagermaskens data (eller kombinerad / slutgiltig mask om det finns en vektormask) i PSD‑filen. |
| [setLeft(int value)](#setLeft-int-) | Hämtar eller anger den vänstra lagermaskens position. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Hämtar eller anger maskens rektangel för lagermasken i PSD‑filen. |
| [setRealFlags(byte value)](#setRealFlags-byte-) | Hämtar eller anger lagermaskflaggorna som används för användar‑/rastermask. |
| [setRight(int value)](#setRight-int-) | Hämtar eller anger den högra lagermaskens position. |
| [setTop(int value)](#setTop-int-) | Hämtar eller anger den övre lagermaskens position. |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | Hämtar eller anger användar‑(raster) maskdata för ett lager i PSD‑filen. |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | Hämtar eller anger användarmaskens (omslutande) rektangel i PSD‑bildlagret. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


Initierar en ny instans av klassen [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull).

### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


Klonar den här instansen.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


Klonar lagermasken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Masken. |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


Hämtar eller anger bakgrundsfärgen.

Värde: Bakgrundsfärgen.

**Returns:**
byte
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Hämtar eller anger den nedre lagermaskens position.

Värde: Den nedre lagermaskens position.

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


Hämtar storleken på lagermaskens maskdata.

Värde: Storleken på lagermaskens maskdata.

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


Hämtar eller anger standardfärgen.

Värde: Standardfärgen.

**Returns:**
byte
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


Hämtar eller anger den omgivande nedre rastermaskens position i PSD-bildlagret.

Värde: Den nedre lagermaskens position.

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


Hämtar eller anger den omgivande vänstra rastermaskens position i PSD-fils lagret.

Värde: Vänstra lagermaskens position.

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


Hämtar eller anger den omgivande högra rastermaskens position i PSD-fils lagret.

Värde: Högra lagermaskens position.

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


Hämtar eller anger den omgivande övre positionen för rastermasken i PSD-bildlagret.

Värde: Övre lagermaskens position.

**Returns:**
int
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Hämtar eller anger lagermaskens flaggor.

Värde: Lagermaskens flaggor.

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


Hämtar maskens höjd.

Värde: Höjden.

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Hämtar eller anger lagermaskens data (eller kombinerad / slutgiltig mask om det finns en vektormask) i PSD‑filen.

Värde: Bilddata.

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Hämtar eller anger den vänstra lagermaskens position.

Värde: Vänstra lagermaskens position.

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


Hämtar eller anger maskens Rectangle för lagermasken i PSD-filen. Den tar left, right, top och bottom-egenskaperna och skapar Rectangle

Värde: Maskens rektangel.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


Hämtar eller anger lagermaskflaggorna som används för användar‑/rastermask. För vektormask används egenskapen Flags.

Värde: De faktiska lagermaskflaggorna.

**Returns:**
byte
### getRight() {#getRight--}
```
public final int getRight()
```


Hämtar eller anger den högra lagermaskens position.

Värde: Högra lagermaskens position.

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


Hämtar eller anger den övre lagermaskens position.

Värde: Övre lagermaskens position.

**Returns:**
int
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


Hämtar eller anger användar‑(raster) maskdata för ett lager i PSD‑filen. (Det finns en rasteriserad vektormask i egenskapen MaskData).

Värde: Lagerbilddata i PSD‑bilden.

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


Hämtar eller anger användarmaskens (omslutande) rektangel i PSD‑bildlagret.

Värde: Användarmaskens rektangel.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


Hämtar maskens bredd.

Värde: Bredden.

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


Sparar [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) till den angivna StreamContainer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren att spara data i. |

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


Hämtar eller anger bakgrundsfärgen.

Värde: Bakgrundsfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Hämtar eller anger den nedre lagermaskens position.

Värde: Den nedre lagermaskens position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


Hämtar eller anger standardfärgen.

Värde: Standardfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


Hämtar eller anger den omgivande nedre rastermaskens position i PSD-bildlagret.

Värde: Den nedre lagermaskens position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


Hämtar eller anger den omgivande vänstra rastermaskens position i PSD-fils lagret.

Värde: Vänstra lagermaskens position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


Hämtar eller anger den omgivande högra rastermaskens position i PSD-fils lagret.

Värde: Högra lagermaskens position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


Hämtar eller anger den omgivande övre positionen för rastermasken i PSD-bildlagret.

Värde: Övre lagermaskens position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Hämtar eller anger lagermaskens flaggor.

Värde: Lagermaskens flaggor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


Hämtar eller anger lagermaskens data (eller kombinerad / slutgiltig mask om det finns en vektormask) i PSD‑filen.

Värde: Bilddata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Hämtar eller anger den vänstra lagermaskens position.

Värde: Vänstra lagermaskens position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


Hämtar eller anger maskens Rectangle för lagermasken i PSD-filen. Den tar left, right, top och bottom-egenskaperna och skapar Rectangle

Värde: Maskens rektangel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


Hämtar eller anger lagermaskflaggorna som används för användar‑/rastermask. För vektormask används egenskapen Flags.

Värde: De faktiska lagermaskflaggorna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Hämtar eller anger den högra lagermaskens position.

Värde: Högra lagermaskens position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Hämtar eller anger den övre lagermaskens position.

Värde: Övre lagermaskens position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


Hämtar eller anger användar‑(raster) maskdata för ett lager i PSD‑filen. (Det finns en rasteriserad vektormask i egenskapen MaskData).

Värde: Lagerbilddata i PSD‑bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


Hämtar eller anger användarmaskens (omslutande) rektangel i PSD‑bildlagret.

Värde: Användarmaskens rektangel.

**Parameters:**
| Parameter | Typ | Beskrivning |
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

