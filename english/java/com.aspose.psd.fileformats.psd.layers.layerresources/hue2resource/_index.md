---
title: Hue2Resource
second_title: Aspose.PSD for Java API Reference
description: Class Hue2Resource.
type: docs
weight: 34
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class Hue2Resource extends AdjustmentLayerResource
```

Class Hue2Resource. Resource of Exposure Adjustment Layer
## Constructors

| Constructor | Description |
| --- | --- |
| [Hue2Resource()](#Hue2Resource--) | Initializes a new instance of the [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) class. |
| [Hue2Resource(byte[] data)](#Hue2Resource-byte---) | Initializes a new instance of the [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) class. |
## Fields

| Field | Description |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | The PSB header version |
| [PsbResourceSignature](#PsbResourceSignature) | The PSB-specific resource signature. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | The PSD header version |
| [ResourceSignature](#ResourceSignature) | The common resource signature. |
| [TypeToolKey](#TypeToolKey) | The type tool info key. |
| [ventureLicense_internalized](#ventureLicense-internalized) | The venture license. |
## Methods

| Method | Description |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Checks the and set if resource is PSB specific. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorize()](#getColorize--) | Gets or sets a value indicating whether this [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) is colorize. |
| [getData()](#getData--) | Gets or sets the data. |
| [getHeader_internalized()](#getHeader-internalized--) | Gets or sets the header. |
| [getHue()](#getHue--) | Gets or sets the master hue. |
| [getKey()](#getKey--) | Gets the layer resource key. |
| [getLength()](#getLength--) | Gets the layer resource length in bytes. |
| [getLightness()](#getLightness--) | Gets or sets the master lightness. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Gets the prefix length. |
| [getPsdVersion()](#getPsdVersion--) | Gets the minimal psd version required for layer resource. |
| [getRanges()](#getRanges--) | Gets the ranges of Hue/Saturation Adjustment Layer. |
| [getSaturation()](#getSaturation--) | Gets or sets the master saturation. |
| [getSignature()](#getSignature--) | Gets the layer resource signature. |
| [getVersion()](#getVersion--) | Gets the version. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determines whether the resource is PSB specific. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Gets a value indicating whether this instance is resource PSB specific. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Saves the resource to the specified stream container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Saves the custom resource header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Saves the header signature, identifier and length. |
| [setColorize(boolean value)](#setColorize-boolean-) | Gets or sets a value indicating whether this [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) is colorize. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Gets or sets the header. |
| [setHue(short value)](#setHue-short-) | Gets or sets the master hue. |
| [setLightness(short value)](#setLightness-short-) | Gets or sets the master lightness. |
| [setRanges(ColorRangeHsl[] value)](#setRanges-com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl---) | Gets the ranges of Hue/Saturation Adjustment Layer. |
| [setSaturation(short value)](#setSaturation-short-) | Gets or sets the master saturation. |
| [setVersion(short value)](#setVersion-short-) | Gets the version. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hue2Resource() {#Hue2Resource--}
```
public Hue2Resource()
```


Initializes a new instance of the [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) class.

### Hue2Resource(byte[] data) {#Hue2Resource-byte---}
```
public Hue2Resource(byte[] data)
```


Initializes a new instance of the [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The data of the resource. |

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


The PSB header version

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


The PSB-specific resource signature.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


The PSD header version

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


The common resource signature.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


The type tool info key.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


The venture license.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Checks the and set if resource is PSB specific. Some resources are not recognized for now, but we have full list of PSB specific resources which changes their behaviour on save. So we need to check this in UnknownResource at least

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int | The key. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorize() {#getColorize--}
```
public final boolean getColorize()
```


Gets or sets a value indicating whether this [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) is colorize.

Value:  true  if colorize; otherwise,  false .

**Returns:**
boolean
### getData() {#getData--}
```
public final byte[] getData()
```


Gets or sets the data.

Value: The data.

**Returns:**
byte[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Gets or sets the header.

Value: The header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHue() {#getHue--}
```
public final short getHue()
```


Gets or sets the master hue.

Value: The master hue.

**Returns:**
short
### getKey() {#getKey--}
```
public final int getKey()
```


Gets the layer resource key.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Gets the layer resource length in bytes.

**Returns:**
int
### getLightness() {#getLightness--}
```
public final short getLightness()
```


Gets or sets the master lightness.

Value: The master lightness.

**Returns:**
short
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Gets the prefix length. Default value is 12 for 8BIM resources. and 16 for 8B64

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| psdVersion | int | The PSD version. |

**Returns:**
int - The Prefix Length.
### getPsdVersion() {#getPsdVersion--}
```
public final int getPsdVersion()
```


Gets the minimal psd version required for layer resource. 0 indicates no restrictions.

**Returns:**
int
### getRanges() {#getRanges--}
```
public final ColorRangeHsl[] getRanges()
```


Gets the ranges of Hue/Saturation Adjustment Layer. Ranges in PS can change names if range is changed, so we should work by index

Value: The ranges.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl[]
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


Gets or sets the master saturation.

Value: The master saturation.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


Gets the layer resource signature.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Gets the version. Default is 2

Value: The version.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Determines whether the resource is PSB specific.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int | The resource key. |

**Returns:**
boolean -  true  if the resource is PSB specific; otherwise,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Gets a value indicating whether this instance is resource PSB specific.

Value:  true  if this instance is resource PSB specific; otherwise,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Saves the resource to the specified stream container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container to save to. |
| psdVersion | int | The PSD version. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Saves the custom resource header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |
| signature | int | The signature. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Saves the header signature, identifier and length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |
| signature | int | The signature. |
| isLengthLong | boolean | if set to  true  length is long. |

### setColorize(boolean value) {#setColorize-boolean-}
```
public final void setColorize(boolean value)
```


Gets or sets a value indicating whether this [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) is colorize.

Value:  true  if colorize; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Gets or sets the header.

Value: The header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


Gets or sets the master hue.

Value: The master hue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


Gets or sets the master lightness.

Value: The master lightness.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setRanges(ColorRangeHsl[] value) {#setRanges-com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl---}
```
public void setRanges(ColorRangeHsl[] value)
```


Gets the ranges of Hue/Saturation Adjustment Layer. Ranges in PS can change names if range is changed, so we should work by index

Value: The ranges.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ColorRangeHsl\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


Gets or sets the master saturation.

Value: The master saturation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Gets the version. Default is 2

Value: The version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
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

