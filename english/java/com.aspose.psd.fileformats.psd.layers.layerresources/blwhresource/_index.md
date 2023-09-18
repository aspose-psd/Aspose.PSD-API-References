---
title: BlwhResource
second_title: Aspose.PSD for Java API Reference
description: BlwhResource class is a resource of Black and White Adjustment Layer.
type: docs
weight: 13
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlwhResource extends AdjustmentLayerResource
```

BlwhResource class is a resource of Black and White Adjustment Layer.
## Constructors

| Constructor | Description |
| --- | --- |
| [BlwhResource()](#BlwhResource--) | Initializes a new instance of the [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource) class. |
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
| [getBlackAndWhitePresetFileName()](#getBlackAndWhitePresetFileName--) | Gets or sets the black and white preset file name. |
| [getBlues()](#getBlues--) | Gets or sets the blues value. |
| [getBwPresetKind()](#getBwPresetKind--) | Gets or sets the black and white preset kind value. |
| [getClass()](#getClass--) |  |
| [getCyans()](#getCyans--) | Gets or sets the cyans value. |
| [getData()](#getData--) | Gets or sets the data. |
| [getGreens()](#getGreens--) | Gets or sets the greens value. |
| [getHeader_internalized()](#getHeader-internalized--) | Gets or sets the header. |
| [getKey()](#getKey--) | Gets the layer resource key. |
| [getLength()](#getLength--) | Gets the layer resource length in bytes. |
| [getMagentas()](#getMagentas--) | Gets or sets the magentas value. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Gets the prefix length. |
| [getPsdVersion()](#getPsdVersion--) | Gets the psd version. |
| [getReds()](#getReds--) | Gets or sets the reds value. |
| [getSignature()](#getSignature--) | Gets the signature. |
| [getTintColor()](#getTintColor--) | Gets the ARGB tint color. |
| [getTintColorBlue_internalized()](#getTintColorBlue-internalized--) | Gets or sets the Blue Tint Color double value. |
| [getTintColorGreen_internalized()](#getTintColorGreen-internalized--) | Gets or sets the Green Tint Color double value. |
| [getTintColorRed_internalized()](#getTintColorRed-internalized--) | Gets or sets the Red Tint Color double value. |
| [getUseTint()](#getUseTint--) | Gets or sets a value indicating whether [tint color] is used. |
| [getYellows()](#getYellows--) | Gets or sets the yellows value. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determines whether the resource is PSB specific. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Gets a value indicating whether this instance is resource PSB specific. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Saves the resource to the specified stream container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Saves the custom resource header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Saves the header signature, identifier and length. |
| [setBlackAndWhitePresetFileName(String value)](#setBlackAndWhitePresetFileName-java.lang.String-) | Gets or sets the black and white preset file name. |
| [setBlues(int value)](#setBlues-int-) | Gets or sets the blues value. |
| [setBwPresetKind(int value)](#setBwPresetKind-int-) | Gets or sets the black and white preset kind value. |
| [setCyans(int value)](#setCyans-int-) | Gets or sets the cyans value. |
| [setGreens(int value)](#setGreens-int-) | Gets or sets the greens value. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Gets or sets the header. |
| [setMagentas(int value)](#setMagentas-int-) | Gets or sets the magentas value. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Sets the property value by type structure. |
| [setReds(int value)](#setReds-int-) | Gets or sets the reds value. |
| [setTintColor(int value)](#setTintColor-int-) | Sets the tint color. |
| [setTintColorBlue_internalized(double value)](#setTintColorBlue-internalized-double-) | Gets or sets the Blue Tint Color double value. |
| [setTintColorGreen_internalized(double value)](#setTintColorGreen-internalized-double-) | Gets or sets the Green Tint Color double value. |
| [setTintColorRed_internalized(double value)](#setTintColorRed-internalized-double-) | Gets or sets the Red Tint Color double value. |
| [setUseTint(boolean value)](#setUseTint-boolean-) | Gets or sets a value indicating whether [tint color] is used. |
| [setYellows(int value)](#setYellows-int-) | Gets or sets the yellows value. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlwhResource() {#BlwhResource--}
```
public BlwhResource()
```


Initializes a new instance of the [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource) class.

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
### getBlackAndWhitePresetFileName() {#getBlackAndWhitePresetFileName--}
```
public final String getBlackAndWhitePresetFileName()
```


Gets or sets the black and white preset file name.

Value: The black and white preset file name.

**Returns:**
java.lang.String
### getBlues() {#getBlues--}
```
public final int getBlues()
```


Gets or sets the blues value.

Value: The blues value.

**Returns:**
int
### getBwPresetKind() {#getBwPresetKind--}
```
public final int getBwPresetKind()
```


Gets or sets the black and white preset kind value.

Value: The black and white preset kind value.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCyans() {#getCyans--}
```
public final int getCyans()
```


Gets or sets the cyans value.

Value: The cyans value.

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
### getGreens() {#getGreens--}
```
public final int getGreens()
```


Gets or sets the greens value.

Value: The greens value.

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
### getMagentas() {#getMagentas--}
```
public final int getMagentas()
```


Gets or sets the magentas value.

Value: The magentas value.

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
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Gets the psd version.

**Returns:**
int
### getReds() {#getReds--}
```
public final int getReds()
```


Gets or sets the reds value.

Value: The reds value.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Gets the signature.

**Returns:**
int
### getTintColor() {#getTintColor--}
```
public int getTintColor()
```


Gets the ARGB tint color.

**Returns:**
int - The ARGB tint color.
### getTintColorBlue_internalized() {#getTintColorBlue-internalized--}
```
public final double getTintColorBlue_internalized()
```


Gets or sets the Blue Tint Color double value.

Value: The Blue Tint Color double value.

**Returns:**
double
### getTintColorGreen_internalized() {#getTintColorGreen-internalized--}
```
public final double getTintColorGreen_internalized()
```


Gets or sets the Green Tint Color double value.

Value: The Green Tint Color double value.

**Returns:**
double
### getTintColorRed_internalized() {#getTintColorRed-internalized--}
```
public final double getTintColorRed_internalized()
```


Gets or sets the Red Tint Color double value.

Value: The Red Tint Color double value.

**Returns:**
double
### getUseTint() {#getUseTint--}
```
public final boolean getUseTint()
```


Gets or sets a value indicating whether [tint color] is used.

Value:  true  if used [tint color]; otherwise,  false .

**Returns:**
boolean
### getYellows() {#getYellows--}
```
public final int getYellows()
```


Gets or sets the yellows value.

Value: The yellows value.

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

### setBlackAndWhitePresetFileName(String value) {#setBlackAndWhitePresetFileName-java.lang.String-}
```
public final void setBlackAndWhitePresetFileName(String value)
```


Gets or sets the black and white preset file name.

Value: The black and white preset file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBlues(int value) {#setBlues-int-}
```
public final void setBlues(int value)
```


Gets or sets the blues value.

Value: The blues value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setBwPresetKind(int value) {#setBwPresetKind-int-}
```
public final void setBwPresetKind(int value)
```


Gets or sets the black and white preset kind value.

Value: The black and white preset kind value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCyans(int value) {#setCyans-int-}
```
public final void setCyans(int value)
```


Gets or sets the cyans value.

Value: The cyans value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setGreens(int value) {#setGreens-int-}
```
public final void setGreens(int value)
```


Gets or sets the greens value.

Value: The greens value.

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

### setMagentas(int value) {#setMagentas-int-}
```
public final void setMagentas(int value)
```


Gets or sets the magentas value.

Value: The magentas value.

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

### setReds(int value) {#setReds-int-}
```
public final void setReds(int value)
```


Gets or sets the reds value.

Value: The reds value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTintColor(int value) {#setTintColor-int-}
```
public void setTintColor(int value)
```


Sets the tint color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The value. |

### setTintColorBlue_internalized(double value) {#setTintColorBlue-internalized-double-}
```
public final void setTintColorBlue_internalized(double value)
```


Gets or sets the Blue Tint Color double value.

Value: The Blue Tint Color double value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setTintColorGreen_internalized(double value) {#setTintColorGreen-internalized-double-}
```
public final void setTintColorGreen_internalized(double value)
```


Gets or sets the Green Tint Color double value.

Value: The Green Tint Color double value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setTintColorRed_internalized(double value) {#setTintColorRed-internalized-double-}
```
public final void setTintColorRed_internalized(double value)
```


Gets or sets the Red Tint Color double value.

Value: The Red Tint Color double value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setUseTint(boolean value) {#setUseTint-boolean-}
```
public final void setUseTint(boolean value)
```


Gets or sets a value indicating whether [tint color] is used.

Value:  true  if used [tint color]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setYellows(int value) {#setYellows-int-}
```
public final void setYellows(int value)
```


Gets or sets the yellows value.

Value: The yellows value.

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

