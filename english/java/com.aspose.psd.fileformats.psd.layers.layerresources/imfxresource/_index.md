---
title: ImfxResource
second_title: Aspose.PSD for Java API Reference
description: Imfx resource Multi-effects resource
type: docs
weight: 36
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/imfxresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.BaseFxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/basefxresource)
```
public final class ImfxResource extends BaseFxResource
```

Imfx resource (Multi-effects resource)
## Constructors

| Constructor | Description |
| --- | --- |
| [ImfxResource()](#ImfxResource--) | Initializes a new instance of the [ImfxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/imfxresource) class. |
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
| [addStructure_internalized(OSTypeStructure structure)](#addStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Adds the structure. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Checks the and set if resource is PSB specific. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findResourceForTest_internalized(int type)](#findResourceForTest-internalized-int-) | Finds the effect entity. |
| [generateDefaultResource_internalized()](#generateDefaultResource-internalized--) | Generates the default resource. |
| [getBlendingImageData_internalized()](#getBlendingImageData-internalized--) | Gets or sets the blending image data. |
| [getClass()](#getClass--) |  |
| [getDefaultMultiListStructure_internalized(int type)](#getDefaultMultiListStructure-internalized-int-) | Creates the new instance of [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) based on  type  with default effect structures. |
| [getDescriptorVersion()](#getDescriptorVersion--) | Gets the descriptor version. |
| [getEffectsBlendModes_internalized()](#getEffectsBlendModes-internalized--) | Gets or sets the effects blend modes. |
| [getEffectsBottomCoordinates_internalized()](#getEffectsBottomCoordinates-internalized--) | Gets or sets the effects bottom coordinates. |
| [getEffectsHeight_internalized()](#getEffectsHeight-internalized--) | Gets or sets the height of the effects. |
| [getEffectsLeftCoordinates_internalized()](#getEffectsLeftCoordinates-internalized--) | Gets or sets the effects left coordinates. |
| [getEffectsOpacities_internalized()](#getEffectsOpacities-internalized--) | Gets or sets the effects opacities. |
| [getEffectsRightCoordinates_internalized()](#getEffectsRightCoordinates-internalized--) | Gets or sets the effects right coordinates. |
| [getEffectsTopCoordinates_internalized()](#getEffectsTopCoordinates-internalized--) | Gets or sets the effects top coordinates. |
| [getEffectsWidth_internalized()](#getEffectsWidth-internalized--) | Gets or sets the width of the effects. |
| [getHeader_internalized()](#getHeader-internalized--) | Gets or sets the header. |
| [getImageData_internalized()](#getImageData-internalized--) | Gets or sets the image data. |
| [getKey()](#getKey--) | Gets the layer resource key. |
| [getLayerStyle_internalized()](#getLayerStyle-internalized--) | Gets or sets the layer style. |
| [getLayer_internalized()](#getLayer-internalized--) | Gets or sets the layer. |
| [getLength()](#getLength--) | Gets the layer resource length in bytes. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Gets the prefix length. |
| [getPsdVersion()](#getPsdVersion--) | Gets the minimal psd version required for layer resource. |
| [getRandData_internalized()](#getRandData-internalized--) | Gets or sets the rand data. |
| [getSignature()](#getSignature--) | Gets the layer resource signature. |
| [getStructureByName_internalized(String structureName)](#getStructureByName-internalized-java.lang.String-) | Gets the structure by name. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determines whether the resource is PSB specific. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Gets a value indicating whether this instance is resource PSB specific. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareForBlending_internalized(Layer layer)](#prepareForBlending-internalized-com.aspose.psd.fileformats.psd.layers.Layer-) | Prepares for blending. |
| [removeStructureByName_internalized(String structureName)](#removeStructureByName-internalized-java.lang.String-) | Removes the structure by name. |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Saves the resource to the specified stream container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Saves the custom resource header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Saves the header signature, identifier and length. |
| [setBlendingImageData_internalized(long[] value)](#setBlendingImageData-internalized-long---) | Gets or sets the blending image data. |
| [setEffectsBlendModes_internalized(long[] value)](#setEffectsBlendModes-internalized-long---) | Gets or sets the effects blend modes. |
| [setEffectsBottomCoordinates_internalized(int[] value)](#setEffectsBottomCoordinates-internalized-int---) | Gets or sets the effects bottom coordinates. |
| [setEffectsHeight_internalized(int[] value)](#setEffectsHeight-internalized-int---) | Gets or sets the height of the effects. |
| [setEffectsLeftCoordinates_internalized(int[] value)](#setEffectsLeftCoordinates-internalized-int---) | Gets or sets the effects left coordinates. |
| [setEffectsOpacities_internalized(byte[] value)](#setEffectsOpacities-internalized-byte---) | Gets or sets the effects opacities. |
| [setEffectsRightCoordinates_internalized(int[] value)](#setEffectsRightCoordinates-internalized-int---) | Gets or sets the effects right coordinates. |
| [setEffectsTopCoordinates_internalized(int[] value)](#setEffectsTopCoordinates-internalized-int---) | Gets or sets the effects top coordinates. |
| [setEffectsWidth_internalized(int[] value)](#setEffectsWidth-internalized-int---) | Gets or sets the width of the effects. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Gets or sets the header. |
| [setImageData_internalized(int[][] value)](#setImageData-internalized-int-----) | Gets or sets the image data. |
| [setLayerStyle_internalized(LayerStyleFX value)](#setLayerStyle-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-) | Gets or sets the layer style. |
| [setLayer_internalized(Layer value)](#setLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-) | Gets or sets the layer. |
| [setRandData_internalized(byte[] value)](#setRandData-internalized-byte---) | Gets or sets the rand data. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [update_internalized()](#update-internalized--) | Updates this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImfxResource() {#ImfxResource--}
```
public ImfxResource()
```


Initializes a new instance of the [ImfxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/imfxresource) class.

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

### addStructure_internalized(OSTypeStructure structure) {#addStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void addStructure_internalized(OSTypeStructure structure)
```


Adds the structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | The structure. |

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
### findResourceForTest_internalized(int type) {#findResourceForTest-internalized-int-}
```
public final IEffectsResource findResourceForTest_internalized(int type)
```


Finds the effect entity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The type. |

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.IEffectsResource - Returns the effect entity.
### generateDefaultResource_internalized() {#generateDefaultResource-internalized--}
```
public static ImfxResource generateDefaultResource_internalized()
```


Generates the default resource.

**Returns:**
[ImfxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/imfxresource) - Generated default [ImfxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/imfxresource)
### getBlendingImageData_internalized() {#getBlendingImageData-internalized--}
```
public final long[] getBlendingImageData_internalized()
```


Gets or sets the blending image data.

Value: The blending image data.

**Returns:**
long[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultMultiListStructure_internalized(int type) {#getDefaultMultiListStructure-internalized-int-}
```
public static ListStructure getDefaultMultiListStructure_internalized(int type)
```


Creates the new instance of [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) based on  type  with default effect structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The type of effect. |

**Returns:**
[ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) - The new instance of [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) based on  type  with default effect structures.
### getDescriptorVersion() {#getDescriptorVersion--}
```
public final int getDescriptorVersion()
```


Gets the descriptor version.

Value: The descriptor version.

**Returns:**
int
### getEffectsBlendModes_internalized() {#getEffectsBlendModes-internalized--}
```
public final long[] getEffectsBlendModes_internalized()
```


Gets or sets the effects blend modes.

Value: The effects blend modes.

**Returns:**
long[]
### getEffectsBottomCoordinates_internalized() {#getEffectsBottomCoordinates-internalized--}
```
public final int[] getEffectsBottomCoordinates_internalized()
```


Gets or sets the effects bottom coordinates.

Value: The effects bottom coordinates.

**Returns:**
int[]
### getEffectsHeight_internalized() {#getEffectsHeight-internalized--}
```
public final int[] getEffectsHeight_internalized()
```


Gets or sets the height of the effects.

Value: The height of the effects.

**Returns:**
int[]
### getEffectsLeftCoordinates_internalized() {#getEffectsLeftCoordinates-internalized--}
```
public final int[] getEffectsLeftCoordinates_internalized()
```


Gets or sets the effects left coordinates.

Value: The effects left coordinates.

**Returns:**
int[]
### getEffectsOpacities_internalized() {#getEffectsOpacities-internalized--}
```
public final byte[] getEffectsOpacities_internalized()
```


Gets or sets the effects opacities.

Value: The effects opacities.

**Returns:**
byte[]
### getEffectsRightCoordinates_internalized() {#getEffectsRightCoordinates-internalized--}
```
public final int[] getEffectsRightCoordinates_internalized()
```


Gets or sets the effects right coordinates.

Value: The effects right coordinates.

**Returns:**
int[]
### getEffectsTopCoordinates_internalized() {#getEffectsTopCoordinates-internalized--}
```
public final int[] getEffectsTopCoordinates_internalized()
```


Gets or sets the effects top coordinates.

Value: The effects top coordinates.

**Returns:**
int[]
### getEffectsWidth_internalized() {#getEffectsWidth-internalized--}
```
public final int[] getEffectsWidth_internalized()
```


Gets or sets the width of the effects.

Value: The width of the effects.

**Returns:**
int[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Gets or sets the header.

Value: The header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getImageData_internalized() {#getImageData-internalized--}
```
public final int[][] getImageData_internalized()
```


Gets or sets the image data.

Value: The image data.

**Returns:**
int[][]
### getKey() {#getKey--}
```
public final int getKey()
```


Gets the layer resource key.

**Returns:**
int
### getLayerStyle_internalized() {#getLayerStyle-internalized--}
```
public final LayerStyleFX getLayerStyle_internalized()
```


Gets or sets the layer style.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX
### getLayer_internalized() {#getLayer-internalized--}
```
public final Layer getLayer_internalized()
```


Gets or sets the layer.

Value: The layer.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
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
### getPsdVersion() {#getPsdVersion--}
```
public final int getPsdVersion()
```


Gets the minimal psd version required for layer resource. 0 indicates no restrictions.

**Returns:**
int
### getRandData_internalized() {#getRandData-internalized--}
```
public final byte[] getRandData_internalized()
```


Gets or sets the rand data.

Value: The rand data.

**Returns:**
byte[]
### getSignature() {#getSignature--}
```
public int getSignature()
```


Gets the layer resource signature.

**Returns:**
int
### getStructureByName_internalized(String structureName) {#getStructureByName-internalized-java.lang.String-}
```
public final OSTypeStructure getStructureByName_internalized(String structureName)
```


Gets the structure by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| structureName | java.lang.String | Name of the structure. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
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




### prepareForBlending_internalized(Layer layer) {#prepareForBlending-internalized-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void prepareForBlending_internalized(Layer layer)
```


Prepares for blending.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | The layer. |

### removeStructureByName_internalized(String structureName) {#removeStructureByName-internalized-java.lang.String-}
```
public final void removeStructureByName_internalized(String structureName)
```


Removes the structure by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| structureName | java.lang.String | Name of the structure. |

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

### setBlendingImageData_internalized(long[] value) {#setBlendingImageData-internalized-long---}
```
public final void setBlendingImageData_internalized(long[] value)
```


Gets or sets the blending image data.

Value: The blending image data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] |  |

### setEffectsBlendModes_internalized(long[] value) {#setEffectsBlendModes-internalized-long---}
```
public final void setEffectsBlendModes_internalized(long[] value)
```


Gets or sets the effects blend modes.

Value: The effects blend modes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] |  |

### setEffectsBottomCoordinates_internalized(int[] value) {#setEffectsBottomCoordinates-internalized-int---}
```
public final void setEffectsBottomCoordinates_internalized(int[] value)
```


Gets or sets the effects bottom coordinates.

Value: The effects bottom coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### setEffectsHeight_internalized(int[] value) {#setEffectsHeight-internalized-int---}
```
public final void setEffectsHeight_internalized(int[] value)
```


Gets or sets the height of the effects.

Value: The height of the effects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### setEffectsLeftCoordinates_internalized(int[] value) {#setEffectsLeftCoordinates-internalized-int---}
```
public final void setEffectsLeftCoordinates_internalized(int[] value)
```


Gets or sets the effects left coordinates.

Value: The effects left coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### setEffectsOpacities_internalized(byte[] value) {#setEffectsOpacities-internalized-byte---}
```
public final void setEffectsOpacities_internalized(byte[] value)
```


Gets or sets the effects opacities.

Value: The effects opacities.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setEffectsRightCoordinates_internalized(int[] value) {#setEffectsRightCoordinates-internalized-int---}
```
public final void setEffectsRightCoordinates_internalized(int[] value)
```


Gets or sets the effects right coordinates.

Value: The effects right coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### setEffectsTopCoordinates_internalized(int[] value) {#setEffectsTopCoordinates-internalized-int---}
```
public final void setEffectsTopCoordinates_internalized(int[] value)
```


Gets or sets the effects top coordinates.

Value: The effects top coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### setEffectsWidth_internalized(int[] value) {#setEffectsWidth-internalized-int---}
```
public final void setEffectsWidth_internalized(int[] value)
```


Gets or sets the width of the effects.

Value: The width of the effects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

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

### setImageData_internalized(int[][] value) {#setImageData-internalized-int-----}
```
public final void setImageData_internalized(int[][] value)
```


Gets or sets the image data.

Value: The image data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[][] |  |

### setLayerStyle_internalized(LayerStyleFX value) {#setLayerStyle-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-}
```
public final void setLayerStyle_internalized(LayerStyleFX value)
```


Gets or sets the layer style.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX |  |

### setLayer_internalized(Layer value) {#setLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void setLayer_internalized(Layer value)
```


Gets or sets the layer.

Value: The layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setRandData_internalized(byte[] value) {#setRandData-internalized-byte---}
```
public final void setRandData_internalized(byte[] value)
```


Gets or sets the rand data.

Value: The rand data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
### update_internalized() {#update-internalized--}
```
public final void update_internalized()
```


Updates this instance. TODO: Remove this method. Update should be automatic

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

