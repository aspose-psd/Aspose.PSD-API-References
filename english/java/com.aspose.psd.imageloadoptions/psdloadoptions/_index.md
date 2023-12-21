---
title: PsdLoadOptions
second_title: Aspose.PSD for Java API Reference
description: Psd load options
type: docs
weight: 12
url: /java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

Psd load options
## Constructors

| Constructor | Description |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | Initializes a new instance of the [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) class. |
## Fields

| Field | Description |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | The custom font sources |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | Gets or sets whether to save with the rendered image, with or without a warp transform. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Gets the buffer size hint which is defined max allowed size for all internal buffers. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Gets the  Image  background  Color . |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Gets the data recovery mode. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Gets a value indicating whether [ignore after load]. |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | Gets or sets a value indicating whether [ignore alpha channel]. |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | Gets or sets a value indicating whether PSD text layer fixed width will be ignored on UpdateText operation execution. |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | Gets or sets a value indicating whether [load effects resource] (by default resource is not loaded). |
| [getProgressEventHandler()](#getProgressEventHandler--) | Gets the progress event handler. |
| [getReadOnlyMode()](#getReadOnlyMode--) | Gets or sets a value indicating whether [use read only mode]. |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | Gets or sets a value indicating whether [use disk for load effects resource] (by default used disk to load effects resource, but can be used memory if it is enought by setting this value to false). |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Gets a value indicating whether ICC profile conversion should be applied. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | This is part of the venture licensing pattern. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | Gets or sets whether to save with the rendered image, with or without a warp transform. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Sets the  Image  background  Color . |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Sets the data recovery mode. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Sets a value indicating whether [ignore after load]. |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | Gets or sets a value indicating whether [ignore alpha channel]. |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | Gets or sets a value indicating whether PSD text layer fixed width will be ignored on UpdateText operation execution. |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | Gets or sets a value indicating whether [load effects resource] (by default resource is not loaded). |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Gets or sets the memory MGR. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Sets the progress event handler. |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | Gets or sets a value indicating whether [use read only mode]. |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | Gets or sets a value indicating whether [use disk for load effects resource] (by default used disk to load effects resource, but can be used memory if it is enought by setting this value to false). |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Sets a value indicating whether ICC profile conversion should be applied. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | This is part of the venture licensing pattern. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


Initializes a new instance of the [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) class.

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
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


Gets or sets whether to save with the rendered image, with or without a warp transform.

Value:  true  render image with warp transformation  false .

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
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Gets a value indicating whether [ignore after load].

**Returns:**
boolean -  true  if [ignore after load]; otherwise,  false .
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


Gets or sets a value indicating whether [ignore alpha channel].

Value:  true  if [ignore alpha channel]; otherwise,  false .

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


Gets or sets a value indicating whether PSD text layer fixed width will be ignored on UpdateText operation execution.

Value:  true  if [ignore text layer width]; otherwise,  false .

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


Gets or sets a value indicating whether [load effects resource] (by default resource is not loaded). When set this option only supported effects will be rendered to final merged image.

Value:  true  if [load effects resource]; otherwise,  false .

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Gets the progress event handler.

Value: The progress event handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


Gets or sets a value indicating whether [use read only mode]. This is read-only mode, supported for identical compatibility with Adobe Photoshop. When this option is set, all changes applied for layers will not be saved to final image. All data is used from ImageData section, so it is identical to Photoshop. By default all loaded images are not identical to Adobe Photoshop compatible.

Value:  true  if [use photoshop compatibility mode]; otherwise,  false .

**Returns:**
boolean
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


Gets or sets a value indicating whether [use disk for load effects resource] (by default used disk to load effects resource, but can be used memory if it is enought by setting this value to false).

Value:  true  if [use disk for load effects resource]; otherwise,  false .

**Returns:**
boolean
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




### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


Gets or sets whether to save with the rendered image, with or without a warp transform.

Value:  true  render image with warp transformation  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Sets a value indicating whether [ignore after load].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if [ignore after load]; otherwise,  false . |

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


Gets or sets a value indicating whether [ignore alpha channel].

Value:  true  if [ignore alpha channel]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


Gets or sets a value indicating whether PSD text layer fixed width will be ignored on UpdateText operation execution.

Value:  true  if [ignore text layer width]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


Gets or sets a value indicating whether [load effects resource] (by default resource is not loaded). When set this option only supported effects will be rendered to final merged image.

Value:  true  if [load effects resource]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


Gets or sets a value indicating whether [use read only mode]. This is read-only mode, supported for identical compatibility with Adobe Photoshop. When this option is set, all changes applied for layers will not be saved to final image. All data is used from ImageData section, so it is identical to Photoshop. By default all loaded images are not identical to Adobe Photoshop compatible.

Value:  true  if [use photoshop compatibility mode]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


Gets or sets a value indicating whether [use disk for load effects resource] (by default used disk to load effects resource, but can be used memory if it is enought by setting this value to false).

Value:  true  if [use disk for load effects resource]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

