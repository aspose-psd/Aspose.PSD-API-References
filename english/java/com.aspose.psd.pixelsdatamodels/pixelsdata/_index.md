---
title: PixelsData
second_title: Aspose.PSD for Java API Reference
description: The class to store image pixels data and its bounds.
type: docs
weight: 10
url: /java/com.aspose.psd.pixelsdatamodels/pixelsdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public final class PixelsData implements System.ICloneable
```

The class to store image pixels data and its bounds.
## Constructors

| Constructor | Description |
| --- | --- |
| [PixelsData()](#PixelsData--) | Initializes a new instance of the [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) class. |
| [PixelsData(int[] pixels, Rectangle bounds)](#PixelsData-int---com.aspose.psd.Rectangle-) | Initializes a new instance of the [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) class. |
## Methods

| Method | Description |
| --- | --- |
| [createLoader_internalized()](#createLoader-internalized--) | Creates the PixelsDataLoader instance for current instance of [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [createSaver_internalized()](#createSaver-internalized--) | Creates the PixelsDataSaver instance for current instance of [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [deepClone()](#deepClone--) | It creates full copy of instance |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Gets or sets the bounds of pixels data. |
| [getClass()](#getClass--) |  |
| [getPixels()](#getPixels--) | Gets or sets the pixels data. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Gets or sets the bounds of pixels data. |
| [setPixels(int[] value)](#setPixels-int---) | Gets or sets the pixels data. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PixelsData() {#PixelsData--}
```
public PixelsData()
```


Initializes a new instance of the [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) class.

### PixelsData(int[] pixels, Rectangle bounds) {#PixelsData-int---com.aspose.psd.Rectangle-}
```
public PixelsData(int[] pixels, Rectangle bounds)
```


Initializes a new instance of the [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | int[] | The pixels data. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | The pixels bounds rectangle. |

### createLoader_internalized() {#createLoader-internalized--}
```
public final IRasterImageArgb32PixelLoader createLoader_internalized()
```


Creates the PixelsDataLoader instance for current instance of [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Returns:**
[IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) - The new instance of PixelsDataLoader base on current instance of [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### createSaver_internalized() {#createSaver-internalized--}
```
public final IPixelsSaver createSaver_internalized()
```


Creates the PixelsDataSaver instance for current instance of [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Returns:**
com.aspose.internal.IPixelsSaver - The new instance of PixelsDataSaver base on current instance of [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


It creates full copy of instance

**Returns:**
java.lang.Object - The copy of instance
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Gets or sets the bounds of pixels data.

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


Gets or sets the pixels data.

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


Gets or sets the bounds of pixels data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPixels(int[] value) {#setPixels-int---}
```
public final void setPixels(int[] value)
```


Gets or sets the pixels data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

