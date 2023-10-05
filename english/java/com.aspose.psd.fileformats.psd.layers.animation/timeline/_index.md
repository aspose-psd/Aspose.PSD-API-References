---
title: Timeline
second_title: Aspose.PSD for Java API Reference
description: The time line options model.
type: docs
weight: 14
url: /java/com.aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Inheritance:**
java.lang.Object
```
public final class Timeline
```

The time line options model.
## Constructors

| Constructor | Description |
| --- | --- |
| [Timeline()](#Timeline--) | Initializes a new instance of the [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) class. |
## Methods

| Method | Description |
| --- | --- |
| [applyTo_internalized(PsdImage psdImage)](#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-) | Apply current time line values to input  PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFSt()](#getAFSt--) | Gets or sets the AFSt value. |
| [getActiveFrameIndex()](#getActiveFrameIndex--) | Gets or sets the active frame index. |
| [getClass()](#getClass--) |  |
| [getFrame(int frameId)](#getFrame-int-) | Gets frame by id. |
| [getFrames()](#getFrames--) | Gets the list of frames. |
| [getFramesList()](#getFramesList--) | Gets the list of frames. |
| [getFsID()](#getFsID--) | Gets or sets the FsID value. |
| [getLoopesCount()](#getLoopesCount--) | Gets or sets the count of loops. |
| [getPsdImage()](#getPsdImage--) | Gets ot sets the  PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) of this [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(System.IO.Stream outputStream, ImageOptionsBase options)](#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-) | Saves the PsdImage's and Timeline data to the specified stream in the specified format according to save options. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Saves the PsdImage's and Timeline data to the specified file location in the specified format according to save options. |
| [setAFSt(int value)](#setAFSt-int-) | Gets or sets the AFSt value. |
| [setActiveFrameIndex_internalized(int value)](#setActiveFrameIndex-internalized-int-) | Gets or sets the active frame index. |
| [setFrames(Frame[] value)](#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---) | Gets the list of frames. |
| [setFsID(int value)](#setFsID-int-) | Gets or sets the FsID value. |
| [setLoopesCount(int value)](#setLoopesCount-int-) | Gets or sets the count of loops. |
| [setPsdImage(PsdImage value)](#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-) | Gets ot sets the  PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) of this [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
| [switchActiveFrame(int targetActiveFrameIndex)](#switchActiveFrame-int-) | Switches the active frame to targeted. |
| [toString()](#toString--) |  |
| [updateFrameFromPsdImage_internalized(int frameIndex)](#updateFrameFromPsdImage-internalized-int-) | Apply current time line values to input  PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timeline() {#Timeline--}
```
public Timeline()
```


Initializes a new instance of the [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) class.

### applyTo_internalized(PsdImage psdImage) {#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void applyTo_internalized(PsdImage psdImage)
```


Apply current time line values to input  PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| psdImage | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | The psd image. |

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
### getAFSt() {#getAFSt--}
```
public int getAFSt()
```


Gets or sets the AFSt value.

**Returns:**
int
### getActiveFrameIndex() {#getActiveFrameIndex--}
```
public int getActiveFrameIndex()
```


Gets or sets the active frame index.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFrame(int frameId) {#getFrame-int-}
```
public Frame getFrame(int frameId)
```


Gets frame by id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frameId | int | The frame id. |

**Returns:**
[Frame](../../com.aspose.psd.fileformats.psd.layers.animation/frame) - Returns the frame item or NULL if not exists.
### getFrames() {#getFrames--}
```
public Frame[] getFrames()
```


Gets the list of frames.

**Returns:**
com.aspose.psd.fileformats.psd.layers.animation.Frame[]
### getFramesList() {#getFramesList--}
```
public System.Collections.Generic.List<Frame> getFramesList()
```


Gets the list of frames.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.animation.Frame>
### getFsID() {#getFsID--}
```
public int getFsID()
```


Gets or sets the FsID value.

**Returns:**
int
### getLoopesCount() {#getLoopesCount--}
```
public int getLoopesCount()
```


Gets or sets the count of loops.

**Returns:**
int
### getPsdImage() {#getPsdImage--}
```
public PsdImage getPsdImage()
```


Gets ot sets the  PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) of this [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
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




### save(System.IO.Stream outputStream, ImageOptionsBase options) {#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-}
```
public void save(System.IO.Stream outputStream, ImageOptionsBase options)
```


Saves the PsdImage's and Timeline data to the specified stream in the specified format according to save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | com.aspose.ms.System.IO.Stream | The output stream. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The options. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Saves the PsdImage's and Timeline data to the specified file location in the specified format according to save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The options. |

### setAFSt(int value) {#setAFSt-int-}
```
public void setAFSt(int value)
```


Gets or sets the AFSt value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setActiveFrameIndex_internalized(int value) {#setActiveFrameIndex-internalized-int-}
```
public void setActiveFrameIndex_internalized(int value)
```


Gets or sets the active frame index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setFrames(Frame[] value) {#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---}
```
public void setFrames(Frame[] value)
```


Gets the list of frames.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Frame\[\]](../../com.aspose.psd.fileformats.psd.layers.animation/frame) |  |

### setFsID(int value) {#setFsID-int-}
```
public void setFsID(int value)
```


Gets or sets the FsID value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLoopesCount(int value) {#setLoopesCount-int-}
```
public void setLoopesCount(int value)
```


Gets or sets the count of loops.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPsdImage(PsdImage value) {#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void setPsdImage(PsdImage value)
```


Gets ot sets the  PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) of this [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) |  |

### switchActiveFrame(int targetActiveFrameIndex) {#switchActiveFrame-int-}
```
public void switchActiveFrame(int targetActiveFrameIndex)
```


Switches the active frame to targeted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetActiveFrameIndex | int | The target frame index. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFrameFromPsdImage_internalized(int frameIndex) {#updateFrameFromPsdImage-internalized-int-}
```
public void updateFrameFromPsdImage_internalized(int frameIndex)
```


Apply current time line values to input  PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frameIndex | int | The frame index to update layer States. |

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

