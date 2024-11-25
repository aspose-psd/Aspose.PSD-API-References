---
title: LayerMaskDataFull
second_title: Aspose.PSD for Java API Reference
description: Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer when the layer has both layer and vector masks.
type: docs
weight: 22
url: /java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) is used. The ImageData contains the raster mask and the rasterized vector mask combined. The ImageData bytes length should be equal MaskRectangle.Width \* MaskRectangle.Height properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | Initializes a new instance of the [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) class. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Clones the layer mask. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Gets or sets the background color. |
| [getBottom()](#getBottom--) | Gets or sets the bottom layer mask position. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Gets the size of the layer mask mask data. |
| [getDefaultColor()](#getDefaultColor--) | Gets or sets the default color. |
| [getEnclosingBottom()](#getEnclosingBottom--) | Gets or sets the enclosing bottom raster mask position in the PSD image layer. |
| [getEnclosingLeft()](#getEnclosingLeft--) | Gets or sets the enclosing left raster mask position in the PSD file layer. |
| [getEnclosingRight()](#getEnclosingRight--) | Gets or sets the enclosing right raster mask position in the PSD file layer. |
| [getEnclosingTop()](#getEnclosingTop--) | Gets or sets the enclosing top position of the raster mask in the PSD image layer. |
| [getFlags()](#getFlags--) | Gets or sets the layer mask flags. |
| [getHeight_internalized()](#getHeight-internalized--) | Gets the mask height. |
| [getImageData()](#getImageData--) | Gets or sets the layer mask data (or combined / final mask if there is a vector mask) in the PSD file. |
| [getLeft()](#getLeft--) | Gets or sets the left layer mask position. |
| [getMaskRectangle()](#getMaskRectangle--) | Gets or sets the mask  Rectangle  of the layer mask in the PSD file. |
| [getRealFlags()](#getRealFlags--) | Gets or sets the layer mask flags that is used for user / raster mask. |
| [getRight()](#getRight--) | Gets or sets the right layer mask position. |
| [getTop()](#getTop--) | Gets or sets the top layer mask position. |
| [getUserMaskData()](#getUserMaskData--) | Gets or sets the user (raster) mask data of a layer in the PSD file. |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | Gets or sets the user mask (enclosing) rectangle in the PSD image layer. |
| [getWidth_internalized()](#getWidth-internalized--) | Gets the mask width. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Saves [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) to the specified  StreamContainer . |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | Gets or sets the background color. |
| [setBottom(int value)](#setBottom-int-) | Gets or sets the bottom layer mask position. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Gets or sets the default color. |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | Gets or sets the enclosing bottom raster mask position in the PSD image layer. |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | Gets or sets the enclosing left raster mask position in the PSD file layer. |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | Gets or sets the enclosing right raster mask position in the PSD file layer. |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | Gets or sets the enclosing top position of the raster mask in the PSD image layer. |
| [setFlags(byte value)](#setFlags-byte-) | Gets or sets the layer mask flags. |
| [setImageData(byte[] value)](#setImageData-byte---) | Gets or sets the layer mask data (or combined / final mask if there is a vector mask) in the PSD file. |
| [setLeft(int value)](#setLeft-int-) | Gets or sets the left layer mask position. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Gets or sets the mask  Rectangle  of the layer mask in the PSD file. |
| [setRealFlags(byte value)](#setRealFlags-byte-) | Gets or sets the layer mask flags that is used for user / raster mask. |
| [setRight(int value)](#setRight-int-) | Gets or sets the right layer mask position. |
| [setTop(int value)](#setTop-int-) | Gets or sets the top layer mask position. |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | Gets or sets the user (raster) mask data of a layer in the PSD file. |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | Gets or sets the user mask (enclosing) rectangle in the PSD image layer. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


Initializes a new instance of the [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) class.

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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


Gets or sets the background color.

Value: The background color.

**Returns:**
byte
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
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


Gets or sets the enclosing bottom raster mask position in the PSD image layer.

Value: The bottom layer mask position.

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


Gets or sets the enclosing left raster mask position in the PSD file layer.

Value: The left layer mask position.

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


Gets or sets the enclosing right raster mask position in the PSD file layer.

Value: The right layer mask position.

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


Gets or sets the enclosing top position of the raster mask in the PSD image layer.

Value: The top layer mask position.

**Returns:**
int
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
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


Gets or sets the layer mask flags that is used for user / raster mask. For vector mask the Flags property is used.

Value: The real layer mask flags.

**Returns:**
byte
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
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


Gets or sets the user (raster) mask data of a layer in the PSD file. (There is a raterized vector mask in the MaskData property).

Value: The layer image data in the PSD image.

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


Gets or sets the user mask (enclosing) rectangle in the PSD image layer.

Value: The user mask  Rectangle .

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


Gets or sets the background color.

Value: The background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

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

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


Gets or sets the enclosing bottom raster mask position in the PSD image layer.

Value: The bottom layer mask position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


Gets or sets the enclosing left raster mask position in the PSD file layer.

Value: The left layer mask position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


Gets or sets the enclosing right raster mask position in the PSD file layer.

Value: The right layer mask position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


Gets or sets the enclosing top position of the raster mask in the PSD image layer.

Value: The top layer mask position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


Gets or sets the layer mask flags that is used for user / raster mask. For vector mask the Flags property is used.

Value: The real layer mask flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

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

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


Gets or sets the user (raster) mask data of a layer in the PSD file. (There is a raterized vector mask in the MaskData property).

Value: The layer image data in the PSD image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


Gets or sets the user mask (enclosing) rectangle in the PSD image layer.

Value: The user mask  Rectangle .

**Parameters:**
| Parameter | Type | Description |
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

