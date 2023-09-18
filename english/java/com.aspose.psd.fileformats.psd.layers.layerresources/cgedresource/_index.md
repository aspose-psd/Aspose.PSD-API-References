---
title: CgEdResource
second_title: Aspose.PSD for Java API Reference
description: Class CgEdResource.
type: docs
weight: 16
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class CgEdResource extends AdjustmentLayerResource
```

Class CgEdResource. Content Generator Extra Data (Photoshop CS5)
## Constructors

| Constructor | Description |
| --- | --- |
| [CgEdResource()](#CgEdResource--) | Initializes a new instance of the [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) class. |
## Fields

| Field | Description |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | The PSB header version |
| [PsbResourceSignature](#PsbResourceSignature) | The PSB-specific resource signature. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | The PSD header version |
| [ResourceSignature](#ResourceSignature) | The common resource signature. |
| [TypeToolKey](#TypeToolKey) | The type tool info key. |
## Methods

| Method | Description |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Checks the and set if resource is PSB specific. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAuto()](#getAuto--) | Gets or sets a value indicating whether this [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) is automatic. |
| [getBrightness()](#getBrightness--) | Gets or sets the brightness. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Gets or sets the contrast. |
| [getData()](#getData--) | Gets or sets the data. |
| [getHeader_internalized()](#getHeader-internalized--) | Gets or sets the header. |
| [getKey()](#getKey--) | Gets the layer resource key. |
| [getLabColor()](#getLabColor--) | Gets or sets a value indicating whether [lab color] is used. |
| [getLength()](#getLength--) | Gets the layer resource length in bytes. |
| [getMeanValueForBrightnessAndContrast()](#getMeanValueForBrightnessAndContrast--) | Gets or sets the mean value for brightness and contrast. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Gets the prefix length. |
| [getPropertyValueByTypeStructure_internalized(String structureName)](#getPropertyValueByTypeStructure-internalized-java.lang.String-) | Gets the property value by type structure. |
| [getPsdVersion()](#getPsdVersion--) | Gets the psd version. |
| [getSignature()](#getSignature--) | Gets the signature. |
| [getUseLegacy()](#getUseLegacy--) | Gets or sets a value indicating whether [use legacy]. |
| [getVersion()](#getVersion--) | Gets or sets the version. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determines whether the resource is PSB specific. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Gets a value indicating whether this instance is resource PSB specific. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Saves the resource to the specified stream container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Saves the custom resource header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Saves the header signature, identifier and length. |
| [setAuto(boolean value)](#setAuto-boolean-) | Gets or sets a value indicating whether this [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) is automatic. |
| [setBrightness(int value)](#setBrightness-int-) | Gets or sets the brightness. |
| [setContrast(int value)](#setContrast-int-) | Gets or sets the contrast. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Gets or sets the header. |
| [setLabColor(boolean value)](#setLabColor-boolean-) | Gets or sets a value indicating whether [lab color] is used. |
| [setMeanValueForBrightnessAndContrast(int value)](#setMeanValueForBrightnessAndContrast-int-) | Gets or sets the mean value for brightness and contrast. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Sets the property value by type structure. |
| [setUseLegacy(boolean value)](#setUseLegacy-boolean-) | Gets or sets a value indicating whether [use legacy]. |
| [setVersion(int value)](#setVersion-int-) | Gets or sets the version. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CgEdResource() {#CgEdResource--}
```
public CgEdResource()
```


Initializes a new instance of the [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) class. PSD format specification contains following description: 4 Descriptor Version( = 16) Variable Length Descriptor of extra data Suggestion: it may not be used in old versions of PS(Before CS5).

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
### getAuto() {#getAuto--}
```
public final boolean getAuto()
```


Gets or sets a value indicating whether this [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) is automatic.

Value:  true  if automatic; otherwise,  false .

**Returns:**
boolean
### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Gets or sets the brightness.

Value: The brightness.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public final int getContrast()
```


Gets or sets the contrast.

Value: The contrast.

**Returns:**
int
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
### getKey() {#getKey--}
```
public int getKey()
```


Gets the layer resource key.

**Returns:**
int
### getLabColor() {#getLabColor--}
```
public final boolean getLabColor()
```


Gets or sets a value indicating whether [lab color] is used.

Value:  true  if used [lab color]; otherwise,  false .

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


Gets the layer resource length in bytes.

**Returns:**
int
### getMeanValueForBrightnessAndContrast() {#getMeanValueForBrightnessAndContrast--}
```
public final int getMeanValueForBrightnessAndContrast()
```


Gets or sets the mean value for brightness and contrast.

Value: The mean value for brightness and contrast.

**Returns:**
int
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
### getPropertyValueByTypeStructure_internalized(String structureName) {#getPropertyValueByTypeStructure-internalized-java.lang.String-}
```
public final Object getPropertyValueByTypeStructure_internalized(String structureName)
```


Gets the property value by type structure. Used only for UnitTests.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| structureName | java.lang.String | Name of the structure. |

**Returns:**
java.lang.Object - OSType structure for easy unit-testing
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Gets the psd version.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Gets the signature.

**Returns:**
int
### getUseLegacy() {#getUseLegacy--}
```
public final boolean getUseLegacy()
```


Gets or sets a value indicating whether [use legacy].

Value:  true  if [use legacy]; otherwise,  false .

**Returns:**
boolean
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Gets or sets the version.

Value: The version.

**Returns:**
int
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

### setAuto(boolean value) {#setAuto-boolean-}
```
public final void setAuto(boolean value)
```


Gets or sets a value indicating whether this [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) is automatic.

Value:  true  if automatic; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Gets or sets the brightness.

Value: The brightness.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Gets or sets the contrast.

Value: The contrast.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

### setLabColor(boolean value) {#setLabColor-boolean-}
```
public final void setLabColor(boolean value)
```


Gets or sets a value indicating whether [lab color] is used.

Value:  true  if used [lab color]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setMeanValueForBrightnessAndContrast(int value) {#setMeanValueForBrightnessAndContrast-int-}
```
public final void setMeanValueForBrightnessAndContrast(int value)
```


Gets or sets the mean value for brightness and contrast.

Value: The mean value for brightness and contrast.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Sets the property value by type structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | The structure. |

### setUseLegacy(boolean value) {#setUseLegacy-boolean-}
```
public final void setUseLegacy(boolean value)
```


Gets or sets a value indicating whether [use legacy].

Value:  true  if [use legacy]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Gets or sets the version.

Value: The version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

