---
title: PhflResourceVersion2
second_title: Aspose.PSD for Java API Reference
description: Class PhflResource.
type: docs
weight: 61
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.PhflResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresource)
```
public class PhflResourceVersion2 extends PhflResource
```

Class PhflResource. Resource of Exposure Adjustment Layer 2 Version ( = 3 ) or ( = 2 ) 12 4 bytes each for XYZ color(Only in Version 3) 10 2 bytes color space followed by 4 \* 2 bytes color component(Only in Version 2) 4 Density 1 Preserve Luminosity
## Constructors

| Constructor | Description |
| --- | --- |
| [PhflResourceVersion2()](#PhflResourceVersion2--) | Initializes a new instance of the [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2) class. |
| [PhflResourceVersion2(byte[] data)](#PhflResourceVersion2-byte---) | Initializes a new instance of the [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2) class. |
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
| [getColorSpace()](#getColorSpace--) | Gets the color space. |
| [getComponentA()](#getComponentA--) | Gets or sets the A component of color |
| [getComponentB()](#getComponentB--) | Gets or sets the B component |
| [getComponentL()](#getComponentL--) | Gets or sets the L component of color |
| [getData()](#getData--) | Gets or sets the data. |
| [getDensity()](#getDensity--) | Gets or sets the density. |
| [getHeader_internalized()](#getHeader-internalized--) | Gets or sets the header. |
| [getKey()](#getKey--) | Gets the layer resource key. |
| [getLength()](#getLength--) | Gets the layer resource length in bytes. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Gets the prefix length. |
| [getPreserveLuminosity()](#getPreserveLuminosity--) | Gets or sets a value indicating whether [preserve luminosity]. |
| [getPsdVersion()](#getPsdVersion--) | Gets the psd version. |
| [getRgbColor()](#getRgbColor--) | Gets the color. |
| [getSignature()](#getSignature--) | Gets the signature. |
| [getVersion()](#getVersion--) | Gets the version. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determines whether the resource is PSB specific. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Gets a value indicating whether this instance is resource PSB specific. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Saves the resource to the specified stream container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Saves the custom resource header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Saves the header signature, identifier and length. |
| [setColorSpace(short value)](#setColorSpace-short-) | Gets the color space. |
| [setComponentA(short value)](#setComponentA-short-) | Gets or sets the A component of color |
| [setComponentB(short value)](#setComponentB-short-) | Gets or sets the B component |
| [setComponentL(short value)](#setComponentL-short-) | Gets or sets the L component of color |
| [setDensity(int value)](#setDensity-int-) | Gets or sets the density. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Gets or sets the header. |
| [setPreserveLuminosity(boolean value)](#setPreserveLuminosity-boolean-) | Gets or sets a value indicating whether [preserve luminosity]. |
| [setRgbColor(Color color)](#setRgbColor-com.aspose.psd.Color-) | Sets the RGB color. |
| [setVersion(short value)](#setVersion-short-) | Gets the version. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhflResourceVersion2() {#PhflResourceVersion2--}
```
public PhflResourceVersion2()
```


Initializes a new instance of the [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2) class.

### PhflResourceVersion2(byte[] data) {#PhflResourceVersion2-byte---}
```
public PhflResourceVersion2(byte[] data)
```


Initializes a new instance of the [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The data pf the resource. |

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
### getColorSpace() {#getColorSpace--}
```
public final short getColorSpace()
```


Gets the color space.

Value: The color space.

**Returns:**
short
### getComponentA() {#getComponentA--}
```
public final short getComponentA()
```


Gets or sets the A component of color

**Returns:**
short
### getComponentB() {#getComponentB--}
```
public final short getComponentB()
```


Gets or sets the B component

**Returns:**
short
### getComponentL() {#getComponentL--}
```
public final short getComponentL()
```


Gets or sets the L component of color

**Returns:**
short
### getData() {#getData--}
```
public final byte[] getData()
```


Gets or sets the data.

Value: The data.

**Returns:**
byte[]
### getDensity() {#getDensity--}
```
public final int getDensity()
```


Gets or sets the density.

Value: The density.

**Returns:**
int
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
### getLength() {#getLength--}
```
public int getLength()
```


Gets the layer resource length in bytes.

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
### getPreserveLuminosity() {#getPreserveLuminosity--}
```
public final boolean getPreserveLuminosity()
```


Gets or sets a value indicating whether [preserve luminosity].

Value:  true  if [preserve luminosity]; otherwise,  false .

**Returns:**
boolean
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Gets the psd version.

**Returns:**
int
### getRgbColor() {#getRgbColor--}
```
public Color getRgbColor()
```


Gets the color.

**Returns:**
[Color](../../com.aspose.psd/color) - The RGB color
### getSignature() {#getSignature--}
```
public int getSignature()
```


Gets the signature.

**Returns:**
int
### getVersion() {#getVersion--}
```
public short getVersion()
```


Gets the version.

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

### setColorSpace(short value) {#setColorSpace-short-}
```
public void setColorSpace(short value)
```


Gets the color space.

Value: The color space.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setComponentA(short value) {#setComponentA-short-}
```
public final void setComponentA(short value)
```


Gets or sets the A component of color

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setComponentB(short value) {#setComponentB-short-}
```
public final void setComponentB(short value)
```


Gets or sets the B component

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setComponentL(short value) {#setComponentL-short-}
```
public final void setComponentL(short value)
```


Gets or sets the L component of color

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setDensity(int value) {#setDensity-int-}
```
public final void setDensity(int value)
```


Gets or sets the density.

Value: The density.

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

### setPreserveLuminosity(boolean value) {#setPreserveLuminosity-boolean-}
```
public final void setPreserveLuminosity(boolean value)
```


Gets or sets a value indicating whether [preserve luminosity].

Value:  true  if [preserve luminosity]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRgbColor(Color color) {#setRgbColor-com.aspose.psd.Color-}
```
public void setRgbColor(Color color)
```


Sets the RGB color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | The color. |

### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Gets the version.

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

