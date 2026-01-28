---
title: LmskResource
second_title: Aspose.PSD for Java API Reference
description: The LMsk resource.
type: docs
weight: 49
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class LmskResource extends LayerResource
```

The LMsk resource.

--------------------

This resource contains color space ID, which refers to a specific color space type, and 4 color components. Depending on ID, color components have different meanings. If the color space type does not require four values, the extra components are undefined and always written as zeros. Color components by color space types: RGB - the first three components are red, green, and blue. HSB - the first three components are hue, saturation, and brightness. CMYK- the four components are cyan, magenta, yellow, and black. Lab - the first three components are lightness, a chrominance, and b chrominance. Grayscale - the first component is the gray value, from 0...10000.
## Constructors

| Constructor | Description |
| --- | --- |
| [LmskResource()](#LmskResource--) | Initializes a new instance of the [LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource) class. |
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
| [create_internalized(byte[] data)](#create-internalized-byte---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorComponent1()](#getColorComponent1--) | Gets the color component 1. |
| [getColorComponent2()](#getColorComponent2--) | Gets the color component 2. |
| [getColorComponent3()](#getColorComponent3--) | Gets the color component 3. |
| [getColorComponent4()](#getColorComponent4--) | Gets the color component 4. |
| [getColorSpace()](#getColorSpace--) | Gets the color space. |
| [getFlag()](#getFlag--) | Gets the flag. |
| [getHeader_internalized()](#getHeader-internalized--) | Gets or sets the header. |
| [getKey()](#getKey--) | Gets the layer resource key. |
| [getLength()](#getLength--) | Gets the layer resource length in bytes. |
| [getOpacity()](#getOpacity--) | Gets the opacity. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Gets the prefix length. |
| [getPsdVersion()](#getPsdVersion--) | Gets the minimal psd version required for layer resource. |
| [getSignature()](#getSignature--) | Gets the layer resource signature. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determines whether the resource is PSB specific. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Gets a value indicating whether this instance is resource PSB specific. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Saves the resource to the specified stream container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Saves the custom resource header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Saves the header signature, identifier and length. |
| [setColorComponent1(int value)](#setColorComponent1-int-) | Gets the color component 1. |
| [setColorComponent2(int value)](#setColorComponent2-int-) | Gets the color component 2. |
| [setColorComponent3(int value)](#setColorComponent3-int-) | Gets the color component 3. |
| [setColorComponent4(int value)](#setColorComponent4-int-) | Gets the color component 4. |
| [setColorSpace(int value)](#setColorSpace-int-) | Gets the color space. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Gets or sets the header. |
| [setOpacity(short value)](#setOpacity-short-) | Gets the opacity. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LmskResource() {#LmskResource--}
```
public LmskResource()
```


Initializes a new instance of the [LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource) class.

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

### create_internalized(byte[] data) {#create-internalized-byte---}
```
public static LmskResource create_internalized(byte[] data)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] |  |

**Returns:**
[LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource)
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
### getColorComponent1() {#getColorComponent1--}
```
public final int getColorComponent1()
```


Gets the color component 1.

Value: The color component 1.

**Returns:**
int
### getColorComponent2() {#getColorComponent2--}
```
public final int getColorComponent2()
```


Gets the color component 2.

Value: The color component 2.

**Returns:**
int
### getColorComponent3() {#getColorComponent3--}
```
public final int getColorComponent3()
```


Gets the color component 3.

Value: The color component 3.

**Returns:**
int
### getColorComponent4() {#getColorComponent4--}
```
public final int getColorComponent4()
```


Gets the color component 4.

Value: The color component 4.

**Returns:**
int
### getColorSpace() {#getColorSpace--}
```
public final int getColorSpace()
```


Gets the color space.

Value: The color space.

**Returns:**
int
### getFlag() {#getFlag--}
```
public final byte getFlag()
```


Gets the flag.

Value: The flag.

**Returns:**
byte
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
### getOpacity() {#getOpacity--}
```
public final short getOpacity()
```


Gets the opacity.

Value: The opacity.

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
### getSignature() {#getSignature--}
```
public int getSignature()
```


Gets the layer resource signature.

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

### setColorComponent1(int value) {#setColorComponent1-int-}
```
public final void setColorComponent1(int value)
```


Gets the color component 1.

Value: The color component 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setColorComponent2(int value) {#setColorComponent2-int-}
```
public final void setColorComponent2(int value)
```


Gets the color component 2.

Value: The color component 2.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setColorComponent3(int value) {#setColorComponent3-int-}
```
public final void setColorComponent3(int value)
```


Gets the color component 3.

Value: The color component 3.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setColorComponent4(int value) {#setColorComponent4-int-}
```
public final void setColorComponent4(int value)
```


Gets the color component 4.

Value: The color component 4.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public final void setColorSpace(int value)
```


Gets the color space.

Value: The color space.

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

### setOpacity(short value) {#setOpacity-short-}
```
public final void setOpacity(short value)
```


Gets the opacity.

Value: The opacity.

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

