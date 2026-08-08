---
title: "PixelsData"
second_title: "Aspose.PSD för Java API-referens"
description: "Klassen för att lagra bildpixeldata och dess gränser."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.pixelsdatamodels/pixelsdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public final class PixelsData implements System.ICloneable
```

Klassen för att lagra bildpixeldata och dess gränser.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PixelsData()](#PixelsData--) | Initierar en ny instans av klassen [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [PixelsData(int[] pixels, Rectangle bounds)](#PixelsData-int---com.aspose.psd.Rectangle-) | Initierar en ny instans av klassen [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createLoader_internalized()](#createLoader-internalized--) | Skapar PixelsDataLoader‑instansen för den aktuella instansen av [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [createSaver_internalized()](#createSaver-internalized--) | Skapar PixelsDataSaver‑instansen för den aktuella instansen av [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [deepClone()](#deepClone--) | Den skapar en fullständig kopia av instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Hämtar eller anger gränserna för pixeldata. |
| [getClass()](#getClass--) |  |
| [getPixels()](#getPixels--) | Hämtar eller anger pixeldata. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Hämtar eller anger gränserna för pixeldata. |
| [setPixels(int[] value)](#setPixels-int---) | Hämtar eller anger pixeldata. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PixelsData() {#PixelsData--}
```
public PixelsData()
```


Initierar en ny instans av klassen [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

### PixelsData(int[] pixels, Rectangle bounds) {#PixelsData-int---com.aspose.psd.Rectangle-}
```
public PixelsData(int[] pixels, Rectangle bounds)
```


Initierar en ny instans av klassen [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | Pixeldata. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln som definierar pixelgränserna. |

### createLoader_internalized() {#createLoader-internalized--}
```
public final IRasterImageArgb32PixelLoader createLoader_internalized()
```


Skapar PixelsDataLoader‑instansen för den aktuella instansen av [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Returns:**
[IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) - The new instance of PixelsDataLoader base on current instance of [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### createSaver_internalized() {#createSaver-internalized--}
```
public final IPixelsSaver createSaver_internalized()
```


Skapar PixelsDataSaver‑instansen för den aktuella instansen av [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Returns:**
com.aspose.internal.IPixelsSaver – Den nya instansen av PixelsDataSaver baserad på den aktuella instansen av [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Den skapar en fullständig kopia av instansen.

**Returns:**
java.lang.Object - Kopian av instansen
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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Hämtar eller anger gränserna för pixeldata.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPixels() {#getPixels--}
```
public final int[] getPixels()
```


Hämtar eller anger pixeldata.

**Returns:**
int[]
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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Hämtar eller anger gränserna för pixeldata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPixels(int[] value) {#setPixels-int---}
```
public final void setPixels(int[] value)
```


Hämtar eller anger pixeldata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

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

