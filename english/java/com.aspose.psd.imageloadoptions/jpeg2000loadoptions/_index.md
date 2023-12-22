---
title: Jpeg2000LoadOptions
second_title: Aspose.PSD for Java API Reference
description: JPEG2000 load options
type: docs
weight: 10
url: /java/com.aspose.psd.imageloadoptions/jpeg2000loadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class Jpeg2000LoadOptions extends LoadOptions
```

JPEG2000 load options
## Constructors

| Constructor | Description |
| --- | --- |
| [Jpeg2000LoadOptions()](#Jpeg2000LoadOptions--) | Initializes a new instance of the  Jpeg2000LoadOptions  class. |
## Fields

| Field | Description |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | The custom font sources |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Gets the buffer size hint which is defined max allowed size for all internal buffers. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Gets the  Image  background  Color . |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Gets the data recovery mode. |
| [getDefaultMaximumDecodingTime_internalized()](#getDefaultMaximumDecodingTime-internalized--) | Gets the default maximum decoding time. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Gets a value indicating whether [ignore after load]. |
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | Gets the maximum decoding time in seconds (this option can be used on very slow on memory machines to prevent hanging on process on very big images - resolution more than 5500x6500 pixels). |
| [getMaximumDecodingTimeForTile()](#getMaximumDecodingTimeForTile--) | Gets the maximum decoding time for tile. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Gets the progress event handler. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Gets a value indicating whether ICC profile conversion should be applied. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | This is part of the venture licensing pattern. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Sets the  Image  background  Color . |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Sets the data recovery mode. |
| [setDefaultMaximumDecodingTime_internalized(int value)](#setDefaultMaximumDecodingTime-internalized-int-) | Sets the default maximum decoding time. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Sets a value indicating whether [ignore after load]. |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | Sets the maximum decoding time in seconds (this option can be used on very slow on memory machines to prevent hanging on process on very big images - resolution more than 5500x6500 pixels). |
| [setMaximumDecodingTimeForTile(int value)](#setMaximumDecodingTimeForTile-int-) | Sets the maximum decoding time for tile. |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Gets or sets the memory MGR. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Sets the progress event handler. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Sets a value indicating whether ICC profile conversion should be applied. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | This is part of the venture licensing pattern. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Jpeg2000LoadOptions() {#Jpeg2000LoadOptions--}
```
public Jpeg2000LoadOptions()
```


Initializes a new instance of the  Jpeg2000LoadOptions  class.

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


The custom font sources

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
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Gets the buffer size hint which is defined max allowed size for all internal buffers.

Value: The buffer size hint, in megabytes. Non-positive value means no memory limitation for internal buffers

**Returns:**
int - the buffer size hint which is defined max allowed size for all internal buffers.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Gets the  Image  background  Color .

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

Typically the background color is set whenever pixel value cannot be recovered due to data corruption.
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Gets the data recovery mode.

**Returns:**
int - The data recovery mode.
### getDefaultMaximumDecodingTime_internalized() {#getDefaultMaximumDecodingTime-internalized--}
```
public static int getDefaultMaximumDecodingTime_internalized()
```


Gets the default maximum decoding time.

**Returns:**
int - The default maximum decoding time.
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Gets a value indicating whether [ignore after load].

**Returns:**
boolean -  true  if [ignore after load]; otherwise,  false .
### getMaximumDecodingTime() {#getMaximumDecodingTime--}
```
public int getMaximumDecodingTime()
```


Gets the maximum decoding time in seconds (this option can be used on very slow on memory machines to prevent hanging on process on very big images - resolution more than 5500x6500 pixels).

**Returns:**
int - The maximum decoding time.
### getMaximumDecodingTimeForTile() {#getMaximumDecodingTimeForTile--}
```
public final int getMaximumDecodingTimeForTile()
```


Gets the maximum decoding time for tile.

Value: The maximum decoding time for tile.

**Returns:**
int - the maximum decoding time for tile.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Gets the progress event handler.

Value: The progress event handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Gets a value indicating whether ICC profile conversion should be applied.

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


This is part of the venture licensing pattern. This value will be set by VentureLicenser if the venture passes us a LoadOptions object.

**Returns:**
java.lang.Object
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




### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Sets the buffer size hint which is defined max allowed size for all internal buffers.

Value: The buffer size hint, in megabytes. Non-positive value means no memory limitation for internal buffers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the buffer size hint which is defined max allowed size for all internal buffers. |

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


Sets the  Image  background  Color .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | The background color.

Typically the background color is set whenever pixel value cannot be recovered due to data corruption. |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Sets the data recovery mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The data recovery mode. |

### setDefaultMaximumDecodingTime_internalized(int value) {#setDefaultMaximumDecodingTime-internalized-int-}
```
public static void setDefaultMaximumDecodingTime_internalized(int value)
```


Sets the default maximum decoding time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The default maximum decoding time. |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Sets a value indicating whether [ignore after load].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if [ignore after load]; otherwise,  false . |

### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


Sets the maximum decoding time in seconds (this option can be used on very slow on memory machines to prevent hanging on process on very big images - resolution more than 5500x6500 pixels).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The maximum decoding time. |

### setMaximumDecodingTimeForTile(int value) {#setMaximumDecodingTimeForTile-int-}
```
public final void setMaximumDecodingTimeForTile(int value)
```


Sets the maximum decoding time for tile.

Value: The maximum decoding time for tile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the maximum decoding time for tile. |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


Gets or sets the memory MGR.

Value: The memory MGR.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Sets the progress event handler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | the progress event handler. |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Sets a value indicating whether ICC profile conversion should be applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


This is part of the venture licensing pattern. This value will be set by VentureLicenser if the venture passes us a LoadOptions object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

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

