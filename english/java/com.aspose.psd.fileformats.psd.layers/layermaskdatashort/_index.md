---
title: LayerMaskDataShort
second_title: Aspose.PSD for Java API Reference
description: Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer when the layer has only raster or vector mask but not both.
type: docs
weight: 23
url: /java/com.aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataShort extends LayerMaskData
```

Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer when the layer has only raster or vector mask but not both. Otherwise, a [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) is used. If the layer has only a raster mask the ImageData contains the raster mask data bytes. If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes. The  LayerMaskData.ImageData ([LayerMaskData.getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[LayerMaskData.setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) bytes length should be equal Width \* Height of  LayerMaskData.MaskRectangle ([LayerMaskData.getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[LayerMaskData.setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)) properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [LayerMaskDataShort()](#LayerMaskDataShort--) | Initializes a new instance of the [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) class. |
## Methods

| Method | Description |
| --- | --- |
| [create_internalized(PixelsData pixelsData)](#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-) |  |
| [deepClone_internalized()](#deepClone-internalized--) | Clones this instance. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Clones the layer mask. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | Gets or sets the bottom layer mask position. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Gets the size of the layer mask mask data. |
| [getDefaultColor()](#getDefaultColor--) | Gets or sets the default color. |
| [getFlags()](#getFlags--) | Gets or sets the layer mask flags. |
| [getHeight_internalized()](#getHeight-internalized--) | Gets the mask height. |
| [getImageData()](#getImageData--) | Gets or sets the layer mask data (or combined / final mask if there is a vector mask) in the PSD file. |
| [getLeft()](#getLeft--) | Gets or sets the left layer mask position. |
| [getMaskRectangle()](#getMaskRectangle--) | Gets or sets the mask  Rectangle  of the layer mask in the PSD file. |
| [getPadding()](#getPadding--) | Gets or sets the layer mask padding. |
| [getRight()](#getRight--) | Gets or sets the right layer mask position. |
| [getTop()](#getTop--) | Gets or sets the top layer mask position. |
| [getWidth_internalized()](#getWidth-internalized--) | Gets the mask width. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Saves [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) to the specified  StreamContainer . |
| [setBottom(int value)](#setBottom-int-) | Gets or sets the bottom layer mask position. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Gets or sets the default color. |
| [setFlags(byte value)](#setFlags-byte-) | Gets or sets the layer mask flags. |
| [setImageData(byte[] value)](#setImageData-byte---) | Gets or sets the layer mask data (or combined / final mask if there is a vector mask) in the PSD file. |
| [setLeft(int value)](#setLeft-int-) | Gets or sets the left layer mask position. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Gets or sets the mask  Rectangle  of the layer mask in the PSD file. |
| [setPadding(short value)](#setPadding-short-) | Gets or sets the layer mask padding. |
| [setRight(int value)](#setRight-int-) | Gets or sets the right layer mask position. |
| [setTop(int value)](#setTop-int-) | Gets or sets the top layer mask position. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataShort() {#LayerMaskDataShort--}
```
public LayerMaskDataShort()
```


Initializes a new instance of the [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) class.

### create_internalized(PixelsData pixelsData) {#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-}
```
public static LayerMaskDataShort create_internalized(PixelsData pixelsData)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelsData | [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) |  |

**Returns:**
[LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort)
### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


Clones this instance.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


Clones the layer mask.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | The mask. |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Gets or sets the bottom layer mask position.

Value: The bottom layer mask position.

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


Gets the size of the layer mask mask data.

Value: The size of the layer mask mask data.

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


Gets or sets the default color.

Value: The default color.

**Returns:**
byte
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Gets or sets the layer mask flags.

Value: The layer mask flags.

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


Gets the mask height.

Value: The height.

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Gets or sets the layer mask data (or combined / final mask if there is a vector mask) in the PSD file.

Value: The image data.

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Gets or sets the left layer mask position.

Value: The left layer mask position.

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


Gets or sets the mask  Rectangle  of the layer mask in the PSD file. It takes left, right, top and bottom properties and creates  Rectangle 

Value: The mask rectangle.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getPadding() {#getPadding--}
```
public final short getPadding()
```


Gets or sets the layer mask padding.

Value: The layer mask padding.

**Returns:**
short
### getRight() {#getRight--}
```
public final int getRight()
```


Gets or sets the right layer mask position.

Value: The right layer mask position.

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


Gets or sets the top layer mask position.

Value: The top layer mask position.

**Returns:**
int
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


Gets the mask width.

Value: The width.

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


Saves [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) to the specified  StreamContainer .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container to save data to. |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Gets or sets the bottom layer mask position.

Value: The bottom layer mask position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


Gets or sets the default color.

Value: The default color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Gets or sets the layer mask flags.

Value: The layer mask flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


Gets or sets the layer mask data (or combined / final mask if there is a vector mask) in the PSD file.

Value: The image data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Gets or sets the left layer mask position.

Value: The left layer mask position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


Gets or sets the mask  Rectangle  of the layer mask in the PSD file. It takes left, right, top and bottom properties and creates  Rectangle 

Value: The mask rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPadding(short value) {#setPadding-short-}
```
public final void setPadding(short value)
```


Gets or sets the layer mask padding.

Value: The layer mask padding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Gets or sets the right layer mask position.

Value: The right layer mask position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Gets or sets the top layer mask position.

Value: The top layer mask position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

