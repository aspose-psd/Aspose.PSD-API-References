---
title: "LayerMaskDataFull"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Definieert de LayerMaskDataFull-klasse die informatie bevat over de maskergegevens in de PSD-bestandlaag wanneer de laag zowel laag- als vectormaskers heeft."
type: docs
weight: 22
url: /nl/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

Definieert de LayerMaskDataFull‑klasse die informatie bevat over de maskergegevens in de PSD‑bestandslaag wanneer de laag zowel laag‑ als vector‑maskers heeft. Anders wordt een [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) gebruikt. De ImageData bevat het rastermasker en het gerasterde vectormasker gecombineerd. De lengte van de ImageData‑bytes moet gelijk zijn aan de eigenschappen MaskRectangle.Width \* MaskRectangle.Height.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | Initialiseert een nieuw exemplaar van de [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull)‑klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Kloont deze instantie. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Kloont het laagmasker. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Haalt op of stelt de achtergrondkleur in. |
| [getBottom()](#getBottom--) | Haalt of stelt de positie van het onderste laagmasker in. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Haalt de grootte op van de laagmaskergegevens. |
| [getDefaultColor()](#getDefaultColor--) | Haalt of stelt de standaardkleur in. |
| [getEnclosingBottom()](#getEnclosingBottom--) | Haalt op of stelt de omsluitende onderste rastermaskerpositie in de PSD‑afbeeldingslaag in. |
| [getEnclosingLeft()](#getEnclosingLeft--) | Haalt op of stelt de omsluitende linker rastermaskerpositie in de PSD‑bestandslaag in. |
| [getEnclosingRight()](#getEnclosingRight--) | Haalt op of stelt de omsluitende rechter rastermaskerpositie in de PSD‑bestandslaag in. |
| [getEnclosingTop()](#getEnclosingTop--) | Haalt op of stelt de omsluitende bovenste positie van het rastermasker in de PSD‑afbeeldingslaag in. |
| [getFlags()](#getFlags--) | Haalt of stelt de laagmasker‑vlaggen in. |
| [getHeight_internalized()](#getHeight-internalized--) | Haalt de maskhoogte op. |
| [getImageData()](#getImageData--) | Haalt of stelt de laagmaskergegevens (of gecombineerd / definitief masker indien er een vectormasker is) in het PSD‑bestand in. |
| [getLeft()](#getLeft--) | Haalt of stelt de positie van het linker laagmasker in. |
| [getMaskRectangle()](#getMaskRectangle--) | Haalt of stelt de mask  Rectangle  van het laagmasker in het PSD‑bestand in. |
| [getRealFlags()](#getRealFlags--) | Geeft of stelt de laagmasker‑vlaggen in die worden gebruikt voor gebruikers‑/rastermasker. |
| [getRight()](#getRight--) | Haalt of stelt de positie van het rechter laagmasker in. |
| [getTop()](#getTop--) | Haalt of stelt de positie van het bovenste laagmasker in. |
| [getUserMaskData()](#getUserMaskData--) | Geeft of stelt de gebruikers‑(raster)maskergegevens van een laag in het PSD‑bestand in. |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | Geeft of stelt de gebruikersmasker‑(omvattende) rechthoek in de PSD‑afbeeldingslaag in. |
| [getWidth_internalized()](#getWidth-internalized--) | Haalt de maskbreedte op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Slaat [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) op in de opgegeven StreamContainer. |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | Haalt op of stelt de achtergrondkleur in. |
| [setBottom(int value)](#setBottom-int-) | Haalt of stelt de positie van het onderste laagmasker in. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Haalt of stelt de standaardkleur in. |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | Haalt op of stelt de omsluitende onderste rastermaskerpositie in de PSD‑afbeeldingslaag in. |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | Haalt op of stelt de omsluitende linker rastermaskerpositie in de PSD‑bestandslaag in. |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | Haalt op of stelt de omsluitende rechter rastermaskerpositie in de PSD‑bestandslaag in. |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | Haalt op of stelt de omsluitende bovenste positie van het rastermasker in de PSD‑afbeeldingslaag in. |
| [setFlags(byte value)](#setFlags-byte-) | Haalt of stelt de laagmasker‑vlaggen in. |
| [setImageData(byte[] value)](#setImageData-byte---) | Haalt of stelt de laagmaskergegevens (of gecombineerd / definitief masker indien er een vectormasker is) in het PSD‑bestand in. |
| [setLeft(int value)](#setLeft-int-) | Haalt of stelt de positie van het linker laagmasker in. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Haalt of stelt de mask  Rectangle  van het laagmasker in het PSD‑bestand in. |
| [setRealFlags(byte value)](#setRealFlags-byte-) | Geeft of stelt de laagmasker‑vlaggen in die worden gebruikt voor gebruikers‑/rastermasker. |
| [setRight(int value)](#setRight-int-) | Haalt of stelt de positie van het rechter laagmasker in. |
| [setTop(int value)](#setTop-int-) | Haalt of stelt de positie van het bovenste laagmasker in. |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | Geeft of stelt de gebruikers‑(raster)maskergegevens van een laag in het PSD‑bestand in. |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | Geeft of stelt de gebruikersmasker‑(omvattende) rechthoek in de PSD‑afbeeldingslaag in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


Initialiseert een nieuw exemplaar van de [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull)‑klasse.

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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


Haalt op of stelt de achtergrondkleur in.

Waarde: De achtergrondkleur.

**Returns:**
byte
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
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


Haalt op of stelt de omsluitende onderste rastermaskerpositie in de PSD‑afbeeldingslaag in.

Waarde: De positie van het onderste laagmasker.

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


Haalt op of stelt de omsluitende linker rastermaskerpositie in de PSD‑bestandslaag in.

Waarde: De linker laagmaskerpositie.

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


Haalt op of stelt de omsluitende rechter rastermaskerpositie in de PSD‑bestandslaag in.

Waarde: De rechter laagmaskerpositie.

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


Haalt op of stelt de omsluitende bovenste positie van het rastermasker in de PSD‑afbeeldingslaag in.

Waarde: De bovenste laagmaskerpositie.

**Returns:**
int
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
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


Geeft of stelt de laagmasker‑vlaggen in die worden gebruikt voor gebruikers‑/rastermasker. Voor vectormasker wordt de Flags‑eigenschap gebruikt.

Waarde: De werkelijke laagmasker‑vlaggen.

**Returns:**
byte
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
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


Geeft of stelt de gebruikers‑(raster)maskergegevens van een laag in het PSD‑bestand in. (Er is een gerasteriseerd vectormasker in de MaskData‑eigenschap).

Waarde: De laag‑beeldgegevens in de PSD‑afbeelding.

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


Geeft of stelt de gebruikersmasker‑(omvattende) rechthoek in de PSD‑afbeeldingslaag in.

Waarde: De gebruikersmasker‑rechthoek.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


Haalt op of stelt de achtergrondkleur in.

Waarde: De achtergrondkleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

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

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


Haalt op of stelt de omsluitende onderste rastermaskerpositie in de PSD‑afbeeldingslaag in.

Waarde: De positie van het onderste laagmasker.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


Haalt op of stelt de omsluitende linker rastermaskerpositie in de PSD‑bestandslaag in.

Waarde: De linker laagmaskerpositie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


Haalt op of stelt de omsluitende rechter rastermaskerpositie in de PSD‑bestandslaag in.

Waarde: De rechter laagmaskerpositie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


Haalt op of stelt de omsluitende bovenste positie van het rastermasker in de PSD‑afbeeldingslaag in.

Waarde: De bovenste laagmaskerpositie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


Geeft of stelt de laagmasker‑vlaggen in die worden gebruikt voor gebruikers‑/rastermasker. Voor vectormasker wordt de Flags‑eigenschap gebruikt.

Waarde: De werkelijke laagmasker‑vlaggen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

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

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


Geeft of stelt de gebruikers‑(raster)maskergegevens van een laag in het PSD‑bestand in. (Er is een gerasteriseerd vectormasker in de MaskData‑eigenschap).

Waarde: De laag‑beeldgegevens in de PSD‑afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


Geeft of stelt de gebruikersmasker‑(omvattende) rechthoek in de PSD‑afbeeldingslaag in.

Waarde: De gebruikersmasker‑rechthoek.

**Parameters:**
| Parameter | Type | Beschrijving |
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

