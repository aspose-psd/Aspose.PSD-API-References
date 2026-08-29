---
title: "LayerMaskDataShort"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar LayerMaskDataShort class som innehåller information om maskdata i PSD‑filens lager när lagret endast har raster‑ eller vektormask men inte båda."
type: docs
weight: 23
url: /sv/java/com.aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataShort extends LayerMaskData
```

Definierar klassen LayerMaskDataShort som innehåller information om maskdata i PSD‑filens lager när lagret endast har raster‑ eller vektormask men inte båda. Annars används en [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull). Om lagret endast har en rastermask innehåller ImageData rastermaskens data‑byte. Om lagret endast har en vektormask innehåller ImageData vektormaskens rasteriserade (cachade) data‑byte. LayerMaskData.ImageData ([LayerMaskData.getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[LayerMaskData.setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) byte‑längden bör vara lika med Width \* Height för LayerMaskData.MaskRectangle ([LayerMaskData.getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[LayerMaskData.setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)) egenskaper.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [LayerMaskDataShort()](#LayerMaskDataShort--) | Initierar en ny instans av klassen [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [create_internalized(PixelsData pixelsData)](#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-) |  |
| [deepClone_internalized()](#deepClone-internalized--) | Klonar den här instansen. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Klonar lagermasken. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | Hämtar eller anger den nedre lagermaskens position. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Hämtar storleken på lagermaskens maskdata. |
| [getDefaultColor()](#getDefaultColor--) | Hämtar eller anger standardfärgen. |
| [getFlags()](#getFlags--) | Hämtar eller anger lagermaskens flaggor. |
| [getHeight_internalized()](#getHeight-internalized--) | Hämtar maskens höjd. |
| [getImageData()](#getImageData--) | Hämtar eller anger lagermaskens data (eller kombinerad / slutgiltig mask om det finns en vektormask) i PSD‑filen. |
| [getLeft()](#getLeft--) | Hämtar eller anger den vänstra lagermaskens position. |
| [getMaskRectangle()](#getMaskRectangle--) | Hämtar eller anger maskens rektangel för lagermasken i PSD‑filen. |
| [getPadding()](#getPadding--) | Hämtar eller anger lagermaskens utfyllnad. |
| [getRight()](#getRight--) | Hämtar eller anger den högra lagermaskens position. |
| [getTop()](#getTop--) | Hämtar eller anger den övre lagermaskens position. |
| [getWidth_internalized()](#getWidth-internalized--) | Hämtar maskens bredd. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Sparar [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) till den angivna StreamContainer. |
| [setBottom(int value)](#setBottom-int-) | Hämtar eller anger den nedre lagermaskens position. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Hämtar eller anger standardfärgen. |
| [setFlags(byte value)](#setFlags-byte-) | Hämtar eller anger lagermaskens flaggor. |
| [setImageData(byte[] value)](#setImageData-byte---) | Hämtar eller anger lagermaskens data (eller kombinerad / slutgiltig mask om det finns en vektormask) i PSD‑filen. |
| [setLeft(int value)](#setLeft-int-) | Hämtar eller anger den vänstra lagermaskens position. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Hämtar eller anger maskens rektangel för lagermasken i PSD‑filen. |
| [setPadding(short value)](#setPadding-short-) | Hämtar eller anger lagermaskens utfyllnad. |
| [setRight(int value)](#setRight-int-) | Hämtar eller anger den högra lagermaskens position. |
| [setTop(int value)](#setTop-int-) | Hämtar eller anger den övre lagermaskens position. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataShort() {#LayerMaskDataShort--}
```
public LayerMaskDataShort()
```


Initierar en ny instans av klassen [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort).

### create_internalized(PixelsData pixelsData) {#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-}
```
public static LayerMaskDataShort create_internalized(PixelsData pixelsData)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixelsData | [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) |  |

**Returns:**
[LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort)
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
### getPadding() {#getPadding--}
```
public final short getPadding()
```


Hämtar eller anger lagermaskens utfyllnad.

Värde: Lagermaskens utfyllnad.

**Returns:**
short
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

### setPadding(short value) {#setPadding-short-}
```
public final void setPadding(short value)
```


Hämtar eller anger lagermaskens utfyllnad.

Värde: Lagermaskens utfyllnad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

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

