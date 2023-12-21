---
title: VstkResource
second_title: Aspose.PSD for Java API Reference
description: Resource class VstkResource.
type: docs
weight: 14
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class VstkResource extends LayerResource
```

Resource class VstkResource. Contains information about Vector Stroke Data. Resource should be initialized either by AssginItems method from resourcedata, either by assigning values to properties of the class.
## Constructors

| Constructor | Description |
| --- | --- |
| [VstkResource()](#VstkResource--) | Creates a new instance of the [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource) class. |
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
| [assginItems_internalized(System.Collections.Generic.List<OSTypeStructure> items)](#assginItems-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Assign items structures from Vstk resource. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Checks the and set if resource is PSB specific. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Gets or sets ClassID instance. |
| [getClassName_internalized()](#getClassName-internalized--) | Gets or sets class name. |
| [getFillEnabled()](#getFillEnabled--) | Gets or sets a value indicating whether Stroke fill enabled. |
| [getFillSettings()](#getFillSettings--) | Gets or sets Fill settings of the Stroke. |
| [getHeader_internalized()](#getHeader-internalized--) | Gets or sets the header. |
| [getKey()](#getKey--) | Gets the layer resource key. |
| [getLength()](#getLength--) | Gets the layer resource length in bytes. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Gets the prefix length. |
| [getPsdVersion()](#getPsdVersion--) | Gets the psd version. |
| [getSignature()](#getSignature--) | Gets the signature. |
| [getStrokeEnabled()](#getStrokeEnabled--) | Gets or sets a value indicating whether stroke effect enabled. |
| [getStrokeStyleBlendMode()](#getStrokeStyleBlendMode--) | Gets or sets Stroke Blend mode. |
| [getStrokeStyleContent()](#getStrokeStyleContent--) | Gets or sets Stroke entity. |
| [getStrokeStyleLineAlignment()](#getStrokeStyleLineAlignment--) | Gets or sets Stroke style line alignment. |
| [getStrokeStyleLineCapType()](#getStrokeStyleLineCapType--) | Gets or sets the type of the stroke style line cap. |
| [getStrokeStyleLineCapWidth()](#getStrokeStyleLineCapWidth--) | Gets or sets Stroke line cap width. |
| [getStrokeStyleLineDashOffset()](#getStrokeStyleLineDashOffset--) | Gets or sets the stroke style line dash offset. |
| [getStrokeStyleLineDashSet()](#getStrokeStyleLineDashSet--) | Gets or sets array of line dashes. |
| [getStrokeStyleLineJoinType()](#getStrokeStyleLineJoinType--) | Gets or sets Stroke style line join type. |
| [getStrokeStyleLineWidth()](#getStrokeStyleLineWidth--) | Gets or sets Stroke line width. |
| [getStrokeStyleMiterLimit()](#getStrokeStyleMiterLimit--) | Gets or sets the stroke style miter limit. |
| [getStrokeStyleOpacity()](#getStrokeStyleOpacity--) | Gets or sets Stroke stryle opacity (0-100%). |
| [getStrokeStyleResolution()](#getStrokeStyleResolution--) | Gets or sets Stroke style resolution. |
| [getStrokeStyleScaleLock()](#getStrokeStyleScaleLock--) | Gets or sets Stroke style scale lock. |
| [getStrokeStyleStrokeAdjust()](#getStrokeStyleStrokeAdjust--) | Gets or sets Stroke adjust. |
| [getStrokeStyleVersion()](#getStrokeStyleVersion--) | Gets or sets the stroke style version. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determines whether the resource is PSB specific. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Gets a value indicating whether this instance is resource PSB specific. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Saves the resource to the specified stream container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Saves the custom resource header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Saves the header signature, identifier and length. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Gets or sets ClassID instance. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Gets or sets class name. |
| [setFillEnabled(boolean value)](#setFillEnabled-boolean-) | Gets or sets a value indicating whether Stroke fill enabled. |
| [setFillSettings(IFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Gets or sets Fill settings of the Stroke. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Gets or sets the header. |
| [setStrokeEnabled(boolean value)](#setStrokeEnabled-boolean-) | Gets or sets a value indicating whether stroke effect enabled. |
| [setStrokeStyleBlendMode(long value)](#setStrokeStyleBlendMode-long-) | Gets or sets Stroke Blend mode. |
| [setStrokeStyleContent(DescriptorStructure value)](#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) | Gets or sets Stroke entity. |
| [setStrokeStyleLineAlignment(short value)](#setStrokeStyleLineAlignment-short-) | Gets or sets Stroke style line alignment. |
| [setStrokeStyleLineCapType(short value)](#setStrokeStyleLineCapType-short-) | Gets or sets the type of the stroke style line cap. |
| [setStrokeStyleLineCapWidth(double value)](#setStrokeStyleLineCapWidth-double-) | Gets or sets Stroke line cap width. |
| [setStrokeStyleLineDashOffset(int value)](#setStrokeStyleLineDashOffset-int-) | Gets or sets the stroke style line dash offset. |
| [setStrokeStyleLineDashSet(double[] value)](#setStrokeStyleLineDashSet-double---) | Gets or sets array of line dashes. |
| [setStrokeStyleLineJoinType(short value)](#setStrokeStyleLineJoinType-short-) | Gets or sets Stroke style line join type. |
| [setStrokeStyleLineWidth(double value)](#setStrokeStyleLineWidth-double-) | Gets or sets Stroke line width. |
| [setStrokeStyleMiterLimit(double value)](#setStrokeStyleMiterLimit-double-) | Gets or sets the stroke style miter limit. |
| [setStrokeStyleOpacity(int value)](#setStrokeStyleOpacity-int-) | Gets or sets Stroke stryle opacity (0-100%). |
| [setStrokeStyleResolution(double value)](#setStrokeStyleResolution-double-) | Gets or sets Stroke style resolution. |
| [setStrokeStyleScaleLock(boolean value)](#setStrokeStyleScaleLock-boolean-) | Gets or sets Stroke style scale lock. |
| [setStrokeStyleStrokeAdjust(boolean value)](#setStrokeStyleStrokeAdjust-boolean-) | Gets or sets Stroke adjust. |
| [setStrokeStyleVersion(int value)](#setStrokeStyleVersion-int-) | Gets or sets the stroke style version. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VstkResource() {#VstkResource--}
```
public VstkResource()
```


Creates a new instance of the [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource) class.

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

### assginItems_internalized(System.Collections.Generic.List<OSTypeStructure> items) {#assginItems-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public final void assginItems_internalized(System.Collections.Generic.List<OSTypeStructure> items)
```


Assign items structures from Vstk resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| items | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

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
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Gets or sets ClassID instance.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Gets or sets class name.

**Returns:**
java.lang.String
### getFillEnabled() {#getFillEnabled--}
```
public final boolean getFillEnabled()
```


Gets or sets a value indicating whether Stroke fill enabled.

**Returns:**
boolean
### getFillSettings() {#getFillSettings--}
```
public final IFillSettings getFillSettings()
```


Gets or sets Fill settings of the Stroke.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
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
### getStrokeEnabled() {#getStrokeEnabled--}
```
public final boolean getStrokeEnabled()
```


Gets or sets a value indicating whether stroke effect enabled.

**Returns:**
boolean
### getStrokeStyleBlendMode() {#getStrokeStyleBlendMode--}
```
public final long getStrokeStyleBlendMode()
```


Gets or sets Stroke Blend mode.

**Returns:**
long
### getStrokeStyleContent() {#getStrokeStyleContent--}
```
public final DescriptorStructure getStrokeStyleContent()
```


Gets or sets Stroke entity. Property determines fill settings of the stroke.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### getStrokeStyleLineAlignment() {#getStrokeStyleLineAlignment--}
```
public final short getStrokeStyleLineAlignment()
```


Gets or sets Stroke style line alignment.

**Returns:**
short
### getStrokeStyleLineCapType() {#getStrokeStyleLineCapType--}
```
public final short getStrokeStyleLineCapType()
```


Gets or sets the type of the stroke style line cap.

Value: The type of the stroke style line cap.

**Returns:**
short
### getStrokeStyleLineCapWidth() {#getStrokeStyleLineCapWidth--}
```
public final double getStrokeStyleLineCapWidth()
```


Gets or sets Stroke line cap width.

**Returns:**
double
### getStrokeStyleLineDashOffset() {#getStrokeStyleLineDashOffset--}
```
public final int getStrokeStyleLineDashOffset()
```


Gets or sets the stroke style line dash offset.

Value: The stroke style line dash offset.

**Returns:**
int
### getStrokeStyleLineDashSet() {#getStrokeStyleLineDashSet--}
```
public final Double[] getStrokeStyleLineDashSet()
```


Gets or sets array of line dashes.

**Returns:**
java.lang.Double[]
### getStrokeStyleLineJoinType() {#getStrokeStyleLineJoinType--}
```
public final short getStrokeStyleLineJoinType()
```


Gets or sets Stroke style line join type.

**Returns:**
short
### getStrokeStyleLineWidth() {#getStrokeStyleLineWidth--}
```
public final double getStrokeStyleLineWidth()
```


Gets or sets Stroke line width.

**Returns:**
double
### getStrokeStyleMiterLimit() {#getStrokeStyleMiterLimit--}
```
public final double getStrokeStyleMiterLimit()
```


Gets or sets the stroke style miter limit.

Value: The stroke style miter limit.

**Returns:**
double
### getStrokeStyleOpacity() {#getStrokeStyleOpacity--}
```
public final int getStrokeStyleOpacity()
```


Gets or sets Stroke stryle opacity (0-100%).

**Returns:**
int
### getStrokeStyleResolution() {#getStrokeStyleResolution--}
```
public final double getStrokeStyleResolution()
```


Gets or sets Stroke style resolution.

**Returns:**
double
### getStrokeStyleScaleLock() {#getStrokeStyleScaleLock--}
```
public final boolean getStrokeStyleScaleLock()
```


Gets or sets Stroke style scale lock.

**Returns:**
boolean
### getStrokeStyleStrokeAdjust() {#getStrokeStyleStrokeAdjust--}
```
public final boolean getStrokeStyleStrokeAdjust()
```


Gets or sets Stroke adjust.

**Returns:**
boolean
### getStrokeStyleVersion() {#getStrokeStyleVersion--}
```
public final int getStrokeStyleVersion()
```


Gets or sets the stroke style version.

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

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Gets or sets ClassID instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Gets or sets class name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFillEnabled(boolean value) {#setFillEnabled-boolean-}
```
public final void setFillEnabled(boolean value)
```


Gets or sets a value indicating whether Stroke fill enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFillSettings(IFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillSettings(IFillSettings value)
```


Gets or sets Fill settings of the Stroke.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

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

### setStrokeEnabled(boolean value) {#setStrokeEnabled-boolean-}
```
public final void setStrokeEnabled(boolean value)
```


Gets or sets a value indicating whether stroke effect enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setStrokeStyleBlendMode(long value) {#setStrokeStyleBlendMode-long-}
```
public final void setStrokeStyleBlendMode(long value)
```


Gets or sets Stroke Blend mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setStrokeStyleContent(DescriptorStructure value) {#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public final void setStrokeStyleContent(DescriptorStructure value)
```


Gets or sets Stroke entity. Property determines fill settings of the stroke.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

### setStrokeStyleLineAlignment(short value) {#setStrokeStyleLineAlignment-short-}
```
public final void setStrokeStyleLineAlignment(short value)
```


Gets or sets Stroke style line alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setStrokeStyleLineCapType(short value) {#setStrokeStyleLineCapType-short-}
```
public final void setStrokeStyleLineCapType(short value)
```


Gets or sets the type of the stroke style line cap.

Value: The type of the stroke style line cap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setStrokeStyleLineCapWidth(double value) {#setStrokeStyleLineCapWidth-double-}
```
public final void setStrokeStyleLineCapWidth(double value)
```


Gets or sets Stroke line cap width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setStrokeStyleLineDashOffset(int value) {#setStrokeStyleLineDashOffset-int-}
```
public final void setStrokeStyleLineDashOffset(int value)
```


Gets or sets the stroke style line dash offset.

Value: The stroke style line dash offset.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStrokeStyleLineDashSet(double[] value) {#setStrokeStyleLineDashSet-double---}
```
public final void setStrokeStyleLineDashSet(double[] value)
```


Gets or sets array of line dashes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double[] |  |

### setStrokeStyleLineJoinType(short value) {#setStrokeStyleLineJoinType-short-}
```
public final void setStrokeStyleLineJoinType(short value)
```


Gets or sets Stroke style line join type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setStrokeStyleLineWidth(double value) {#setStrokeStyleLineWidth-double-}
```
public final void setStrokeStyleLineWidth(double value)
```


Gets or sets Stroke line width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setStrokeStyleMiterLimit(double value) {#setStrokeStyleMiterLimit-double-}
```
public final void setStrokeStyleMiterLimit(double value)
```


Gets or sets the stroke style miter limit.

Value: The stroke style miter limit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setStrokeStyleOpacity(int value) {#setStrokeStyleOpacity-int-}
```
public final void setStrokeStyleOpacity(int value)
```


Gets or sets Stroke stryle opacity (0-100%).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStrokeStyleResolution(double value) {#setStrokeStyleResolution-double-}
```
public final void setStrokeStyleResolution(double value)
```


Gets or sets Stroke style resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setStrokeStyleScaleLock(boolean value) {#setStrokeStyleScaleLock-boolean-}
```
public final void setStrokeStyleScaleLock(boolean value)
```


Gets or sets Stroke style scale lock.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setStrokeStyleStrokeAdjust(boolean value) {#setStrokeStyleStrokeAdjust-boolean-}
```
public final void setStrokeStyleStrokeAdjust(boolean value)
```


Gets or sets Stroke adjust.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setStrokeStyleVersion(int value) {#setStrokeStyleVersion-int-}
```
public final void setStrokeStyleVersion(int value)
```


Gets or sets the stroke style version.

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

