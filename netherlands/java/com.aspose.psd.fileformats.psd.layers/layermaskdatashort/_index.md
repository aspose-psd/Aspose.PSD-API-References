---
title: "LayerMaskDataShort"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Definieert de LayerMaskDataShort-klasse die informatie bevat over de maskergegevens in de PSD-bestandlaag wanneer de laag alleen een raster- of vectormasker heeft, maar niet beide."
type: docs
weight: 23
url: /nl/java/com.aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataShort extends LayerMaskData
```

Definieert de LayerMaskDataShort‑klasse die informatie bevat over de maskergegevens in de PSD‑bestandslaag wanneer de laag alleen een raster‑ of vectormasker heeft, maar niet beide. Anders wordt een [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) gebruikt. Als de laag alleen een rastermasker heeft, bevat ImageData de bytes van de rastermaskergegevens. Als de laag alleen een vectormasker heeft, bevat ImageData de gerasteriseerde (gecachede) bytes van het vectormasker. De LayerMaskData.ImageData ([LayerMaskData.getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[LayerMaskData.setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) byte‑lengte moet gelijk zijn aan Breedte \* Hoogte van LayerMaskData.MaskRectangle ([LayerMaskData.getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[LayerMaskData.setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)) eigenschappen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [LayerMaskDataShort()](#LayerMaskDataShort--) | Initialiseert een nieuw exemplaar van de [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [create_internalized(PixelsData pixelsData)](#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-) |  |
| [deepClone_internalized()](#deepClone-internalized--) | Kloont deze instantie. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Kloont het laagmasker. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | Haalt of stelt de positie van het onderste laagmasker in. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Haalt de grootte op van de laagmaskergegevens. |
| [getDefaultColor()](#getDefaultColor--) | Haalt of stelt de standaardkleur in. |
| [getFlags()](#getFlags--) | Haalt of stelt de laagmasker‑vlaggen in. |
| [getHeight_internalized()](#getHeight-internalized--) | Haalt de maskhoogte op. |
| [getImageData()](#getImageData--) | Haalt of stelt de laagmaskergegevens (of gecombineerd / definitief masker indien er een vectormasker is) in het PSD‑bestand in. |
| [getLeft()](#getLeft--) | Haalt of stelt de positie van het linker laagmasker in. |
| [getMaskRectangle()](#getMaskRectangle--) | Haalt of stelt de mask  Rectangle  van het laagmasker in het PSD‑bestand in. |
| [getPadding()](#getPadding--) | Geeft of stelt de laagmasker‑opvulling in. |
| [getRight()](#getRight--) | Haalt of stelt de positie van het rechter laagmasker in. |
| [getTop()](#getTop--) | Haalt of stelt de positie van het bovenste laagmasker in. |
| [getWidth_internalized()](#getWidth-internalized--) | Haalt de maskbreedte op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Slaat [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) op in de opgegeven StreamContainer. |
| [setBottom(int value)](#setBottom-int-) | Haalt of stelt de positie van het onderste laagmasker in. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Haalt of stelt de standaardkleur in. |
| [setFlags(byte value)](#setFlags-byte-) | Haalt of stelt de laagmasker‑vlaggen in. |
| [setImageData(byte[] value)](#setImageData-byte---) | Haalt of stelt de laagmaskergegevens (of gecombineerd / definitief masker indien er een vectormasker is) in het PSD‑bestand in. |
| [setLeft(int value)](#setLeft-int-) | Haalt of stelt de positie van het linker laagmasker in. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Haalt of stelt de mask  Rectangle  van het laagmasker in het PSD‑bestand in. |
| [setPadding(short value)](#setPadding-short-) | Geeft of stelt de laagmasker‑opvulling in. |
| [setRight(int value)](#setRight-int-) | Haalt of stelt de positie van het rechter laagmasker in. |
| [setTop(int value)](#setTop-int-) | Haalt of stelt de positie van het bovenste laagmasker in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataShort() {#LayerMaskDataShort--}
```
public LayerMaskDataShort()
```


Initialiseert een nieuw exemplaar van de [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) klasse.

### create_internalized(PixelsData pixelsData) {#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-}
```
public static LayerMaskDataShort create_internalized(PixelsData pixelsData)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixelsData | [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) |  |

**Returns:**
[LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort)
### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


Kloont deze instantie.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


Kloont het laagmasker.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Het masker. |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Haalt of stelt de positie van het onderste laagmasker in.

Waarde: De positie van het onderste laagmasker.

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


Haalt de grootte op van de laagmaskergegevens.

Waarde: De grootte van de laagmasker maskergegevens.

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


Haalt of stelt de standaardkleur in.

Waarde: De standaardkleur.

**Returns:**
byte
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Haalt of stelt de laagmasker‑vlaggen in.

Waarde: De laagmaskervlaggen.

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


Haalt de maskhoogte op.

Waarde: De hoogte.

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Haalt of stelt de laagmaskergegevens (of gecombineerd / definitief masker indien er een vectormasker is) in het PSD‑bestand in.

Waarde: De afbeeldingsgegevens.

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Haalt of stelt de positie van het linker laagmasker in.

Waarde: De linker laagmaskerpositie.

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


Haalt op of stelt de mask Rectangle van het laagmasker in het PSD‑bestand in. Het neemt left, right, top en bottom eigenschappen en maakt een Rectangle.

Waarde: Het mask Rectangle.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getPadding() {#getPadding--}
```
public final short getPadding()
```


Geeft of stelt de laagmasker‑opvulling in.

Waarde: De laagmasker‑opvulling.

**Returns:**
short
### getRight() {#getRight--}
```
public final int getRight()
```


Haalt of stelt de positie van het rechter laagmasker in.

Waarde: De rechter laagmaskerpositie.

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


Haalt of stelt de positie van het bovenste laagmasker in.

Waarde: De bovenste laagmaskerpositie.

**Returns:**
int
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


Haalt de maskbreedte op.

Waarde: De breedte.

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


Slaat [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) op in de opgegeven StreamContainer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container om gegevens in op te slaan. |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Haalt of stelt de positie van het onderste laagmasker in.

Waarde: De positie van het onderste laagmasker.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


Haalt of stelt de standaardkleur in.

Waarde: De standaardkleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Haalt of stelt de laagmasker‑vlaggen in.

Waarde: De laagmaskervlaggen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


Haalt of stelt de laagmaskergegevens (of gecombineerd / definitief masker indien er een vectormasker is) in het PSD‑bestand in.

Waarde: De afbeeldingsgegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Haalt of stelt de positie van het linker laagmasker in.

Waarde: De linker laagmaskerpositie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


Haalt op of stelt de mask Rectangle van het laagmasker in het PSD‑bestand in. Het neemt left, right, top en bottom eigenschappen en maakt een Rectangle.

Waarde: Het mask Rectangle.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPadding(short value) {#setPadding-short-}
```
public final void setPadding(short value)
```


Geeft of stelt de laagmasker‑opvulling in.

Waarde: De laagmasker‑opvulling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Haalt of stelt de positie van het rechter laagmasker in.

Waarde: De rechter laagmaskerpositie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Haalt of stelt de positie van het bovenste laagmasker in.

Waarde: De bovenste laagmaskerpositie.

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

