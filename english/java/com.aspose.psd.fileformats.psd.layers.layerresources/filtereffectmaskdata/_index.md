---
title: FilterEffectMaskData
second_title: Aspose.PSD for Java API Reference
description: The filter mask data class.
type: docs
weight: 30
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Inheritance:**
java.lang.Object
```
public final class FilterEffectMaskData
```

The filter mask data class.
## Constructors

| Constructor | Description |
| --- | --- |
| [FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask)](#FilterEffectMaskData-java.lang.String-com.aspose.psd.Rectangle-int-int-com.aspose.psd.fileformats.psd.layers.ChannelInformation---com.aspose.psd.fileformats.psd.layers.ChannelInformation-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.ChannelInformation-) | Initializes a new instance of the [FilterEffectMaskData](../../com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannels()](#getChannels--) | Gets the channels. |
| [getClass()](#getClass--) |  |
| [getGUID()](#getGUID--) | Gets the GUID. |
| [getLength()](#getLength--) | Gets the filter mask data length in bytes. |
| [getMaskRectangle()](#getMaskRectangle--) | Gets the sheet mask rectangle. |
| [getMaxChannels()](#getMaxChannels--) | Gets the max of channels count. |
| [getPixelsDepth()](#getPixelsDepth--) | Gets the pixels depth. |
| [getRectangle()](#getRectangle--) | Gets the channels rectangle. |
| [getSheetMask()](#getSheetMask--) | Gets the sheet mask. |
| [getUserMask()](#getUserMask--) | Gets the user mask. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveData(StreamContainer streamContainer)](#saveData-com.aspose.psd.StreamContainer-) | Saves the resource to the specified stream container. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask) {#FilterEffectMaskData-java.lang.String-com.aspose.psd.Rectangle-int-int-com.aspose.psd.fileformats.psd.layers.ChannelInformation---com.aspose.psd.fileformats.psd.layers.ChannelInformation-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.ChannelInformation-}
```
public FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask)
```


Initializes a new instance of the [FilterEffectMaskData](../../com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| guid | java.lang.String | The resource guid. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The channels rectangle. |
| pixelsDepth | int | The pixels depth. |
| maxChannels | int | The max channels value. |
| channels | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | The channels. |
| userMask | [ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | The user mask. |
| maskRectangle | [Rectangle](../../com.aspose.psd/rectangle) | The sheet mask rectangle. |
| sheetMask | [ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | The sheet mask. |

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
### getChannels() {#getChannels--}
```
public final ChannelInformation[] getChannels()
```


Gets the channels.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGUID() {#getGUID--}
```
public final String getGUID()
```


Gets the GUID.

**Returns:**
java.lang.String
### getLength() {#getLength--}
```
public final long getLength()
```


Gets the filter mask data length in bytes.

**Returns:**
long
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


Gets the sheet mask rectangle.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMaxChannels() {#getMaxChannels--}
```
public final int getMaxChannels()
```


Gets the max of channels count.

**Returns:**
int
### getPixelsDepth() {#getPixelsDepth--}
```
public final int getPixelsDepth()
```


Gets the pixels depth.

**Returns:**
int
### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Gets the channels rectangle.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getSheetMask() {#getSheetMask--}
```
public final ChannelInformation getSheetMask()
```


Gets the sheet mask.

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### getUserMask() {#getUserMask--}
```
public final ChannelInformation getUserMask()
```


Gets the user mask.

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
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




### saveData(StreamContainer streamContainer) {#saveData-com.aspose.psd.StreamContainer-}
```
public final void saveData(StreamContainer streamContainer)
```


Saves the resource to the specified stream container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container to save to. |

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

