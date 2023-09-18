---
title: ThumbnailResource
second_title: Aspose.PSD for Java API Reference
description: The thumbnail resource block.
type: docs
weight: 36
url: /java/com.aspose.psd.fileformats.psd.resources/thumbnailresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public class ThumbnailResource extends ResourceBlock
```

The thumbnail resource block.
## Constructors

| Constructor | Description |
| --- | --- |
| [ThumbnailResource()](#ThumbnailResource--) | Initializes a new instance of the [ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource) class. |
## Fields

| Field | Description |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | The resource signature of ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | The regular Photoshop resource signature. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | Gets or sets the bits pixel. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Gets the resource data size in bytes. |
| [getFormat()](#getFormat--) | Gets or sets the thumbnail data format. |
| [getHeight()](#getHeight--) | Gets or sets the height of thumbnail in pixels. |
| [getID()](#getID--) | Gets or sets the unique identifier for the resource. |
| [getJpegOptions()](#getJpegOptions--) | Gets or sets the JPEG options. |
| [getMinimalVersion()](#getMinimalVersion--) | Gets the minimal required psd version. |
| [getName()](#getName--) | Gets or sets the resource name. |
| [getPlanesCount()](#getPlanesCount--) | Gets or sets the planes count. |
| [getSignature()](#getSignature--) | Gets the resource signature. |
| [getSize()](#getSize--) | Gets the resource block size in bytes including its data. |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | Gets or sets the size after compression. |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | Gets or sets the 32-bit ARGB thumbnail data. |
| [getThumbnailData()](#getThumbnailData--) | Gets or sets the thumbnail data. |
| [getTotalSize()](#getTotalSize--) | Gets the total data size. |
| [getWidth()](#getWidth--) | Gets or sets the width of thumbnail in pixels. |
| [getWidthBytes()](#getWidthBytes--) | Gets the row width in bytes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Saves the resource block to the specified stream. |
| [setBitsPixel(short value)](#setBitsPixel-short-) | Gets or sets the bits pixel. |
| [setFormat(int value)](#setFormat-int-) | Gets or sets the thumbnail data format. |
| [setHeight(int value)](#setHeight-int-) | Gets or sets the height of thumbnail in pixels. |
| [setID(short value)](#setID-short-) | Gets or sets the unique identifier for the resource. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Gets or sets the JPEG options. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Gets or sets the layer and mask information. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets the resource name. |
| [setPlanesCount(short value)](#setPlanesCount-short-) | Gets or sets the planes count. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Gets or sets the resource block state. |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | Gets or sets the 32-bit ARGB thumbnail data. |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | Gets or sets the thumbnail data. |
| [setWidth(int value)](#setWidth-int-) | Gets or sets the width of thumbnail in pixels. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validates the resource values. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ThumbnailResource() {#ThumbnailResource--}
```
public ThumbnailResource()
```


Initializes a new instance of the [ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource) class.

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


The resource signature of ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


The regular Photoshop resource signature.

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
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


Gets or sets the bits pixel.

Value: The thumbnail bits pixel.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Gets the resource data size in bytes.

Value: The resource data size.

**Returns:**
int
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Gets or sets the thumbnail data format.

Value: The thumbnail data format.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets or sets the height of thumbnail in pixels.

Value: The thumbnail height.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Gets or sets the unique identifier for the resource.

Value: The unique identifier for the resource.

**Returns:**
short
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Gets or sets the JPEG options. Suitable when thumbnail resource is saved into JPEG file format only. This option has no effect when RAW format is defined.

Value: The JPEG options.

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Gets the minimal required psd version.

Value: The minimal psd version.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Gets or sets the resource name. Pascal string, padded to make the size even (a null name consists of two bytes of 0).

Value: The resource name.

**Returns:**
java.lang.String
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


Gets or sets the planes count.

Value: The thumbnail planes count.

**Returns:**
short
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Gets the resource signature. Should be always '8BIM'.

Value: The resource signature.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Gets the resource block size in bytes including its data.

Value: The resource block size.

**Returns:**
int
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


Gets or sets the size after compression. Used for consistency check.

Value: The size after compression.

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


Gets or sets the 32-bit ARGB thumbnail data.

Value: The 32-bit ARGB thumbnail data.

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


Gets or sets the thumbnail data.

Value: The thumbnail data.

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


Gets the total data size.

Value: The total data size.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets or sets the width of thumbnail in pixels.

Value: The thumbnail width.

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


Gets the row width in bytes.

Value: The row width in bytes.

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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Saves the resource block to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream to save the resource block to. |

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


Gets or sets the bits pixel.

Value: The thumbnail bits pixel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


Gets or sets the thumbnail data format.

Value: The thumbnail data format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Gets or sets the height of thumbnail in pixels.

Value: The thumbnail height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Gets or sets the unique identifier for the resource.

Value: The unique identifier for the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Gets or sets the JPEG options. Suitable when thumbnail resource is saved into JPEG file format only. This option has no effect when RAW format is defined.

Value: The JPEG options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Gets or sets the layer and mask information.

Value: The layer and mask information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gets or sets the resource name. Pascal string, padded to make the size even (a null name consists of two bytes of 0).

Value: The resource name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


Gets or sets the planes count.

Value: The thumbnail planes count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Gets or sets the resource block state.

Value: The resource block state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


Gets or sets the 32-bit ARGB thumbnail data.

Value: The 32-bit ARGB thumbnail data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


Gets or sets the thumbnail data.

Value: The thumbnail data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Gets or sets the width of thumbnail in pixels.

Value: The thumbnail width.

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
### validateValues() {#validateValues--}
```
public void validateValues()
```


Validates the resource values.

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

