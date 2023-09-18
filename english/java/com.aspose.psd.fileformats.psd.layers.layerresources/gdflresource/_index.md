---
title: GdFlResource
second_title: Aspose.PSD for Java API Reference
description: Class GdFlResource.
type: docs
weight: 31
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.FillLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/filllayerresource)
```
public class GdFlResource extends FillLayerResource
```

Class GdFlResource. This resource contains information about blending of clipped element.
## Constructors

| Constructor | Description |
| --- | --- |
| [GdFlResource()](#GdFlResource--) | Initializes a new instance of the [.GdFlResource](../../null/\#GdFlResource) class. |
## Fields

| Field | Description |
| --- | --- |
| [DefaultScale_internalized](#DefaultScale-internalized) | The default scale. |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | The PSB header version |
| [PsbResourceSignature](#PsbResourceSignature) | The PSB-specific resource signature. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | The PSD header version |
| [ResourceSignature](#ResourceSignature) | The common resource signature. |
| [TypeToolKey](#TypeToolKey) | The type tool info key. |
## Methods

| Method | Description |
| --- | --- |
| [addUnknownStructure_internalized(OSTypeStructure structure)](#addUnknownStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Adds the unknown structure. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Checks the and set if resource is PSB specific. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateDefaultControlPoints_internalized()](#generateDefaultControlPoints-internalized--) |  |
| [generateDefaultTransparencyPoints_internalized()](#generateDefaultTransparencyPoints-internalized--) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) |  |
| [getAngle()](#getAngle--) | Gets or sets the angle. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) |  |
| [getColorPoints()](#getColorPoints--) | Gets the color points. |
| [getDither()](#getDither--) |  |
| [getGradientInterval()](#getGradientInterval--) | Gets or sets the gradient interval. |
| [getGradientName()](#getGradientName--) | Gets or sets the name of the gradient. |
| [getGradientType()](#getGradientType--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Gets or sets the header. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Gets or sets the horizontal offset. |
| [getKey()](#getKey--) | Gets the layer resource key. |
| [getLength()](#getLength--) | Gets the layer resource length in bytes. |
| [getOffset_internalized()](#getOffset-internalized--) | Gets or sets the offset. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Gets the prefix length. |
| [getPsdVersion()](#getPsdVersion--) | Gets the minimal psd version required for layer resource. |
| [getReverse()](#getReverse--) |  |
| [getScale()](#getScale--) | Gets or sets the scale. |
| [getSignature()](#getSignature--) | Gets the layer resource signature. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Gets the transparency points. |
| [getVerticalOffset()](#getVerticalOffset--) | Gets or sets the vertical offset. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determines whether the resource is PSB specific. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Gets a value indicating whether this instance is resource PSB specific. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Saves the resource to the specified stream container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Saves the custom resource header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Saves the header signature, identifier and length. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) |  |
| [setAngle(double value)](#setAngle-double-) |  |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) |  |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) |  |
| [setDither(boolean value)](#setDither-boolean-) |  |
| [setGradientInterval(double value)](#setGradientInterval-double-) |  |
| [setGradientName(String value)](#setGradientName-java.lang.String-) |  |
| [setGradientType(int value)](#setGradientType-int-) |  |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Gets or sets the header. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) |  |
| [setOffset_internalized(OffsetEntity value)](#setOffset-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) |  |
| [setReverse(boolean value)](#setReverse-boolean-) |  |
| [setScale(int value)](#setScale-int-) |  |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) |  |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) |  |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GdFlResource() {#GdFlResource--}
```
public GdFlResource()
```


Initializes a new instance of the [.GdFlResource](../../null/\#GdFlResource) class.

### DefaultScale_internalized {#DefaultScale-internalized}
```
public static final int DefaultScale_internalized
```


The default scale.

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

### addUnknownStructure_internalized(OSTypeStructure structure) {#addUnknownStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public void addUnknownStructure_internalized(OSTypeStructure structure)
```


Adds the unknown structure.

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
### generateDefaultControlPoints_internalized() {#generateDefaultControlPoints-internalized--}
```
public static IGradientColorPoint[] generateDefaultControlPoints_internalized()
```




**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### generateDefaultTransparencyPoints_internalized() {#generateDefaultTransparencyPoints-internalized--}
```
public static IGradientTransparencyPoint[] generateDefaultTransparencyPoints_internalized()
```




**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getAlignWithLayer() {#getAlignWithLayer--}
```
public boolean getAlignWithLayer()
```




**Returns:**
boolean
### getAngle() {#getAngle--}
```
public double getAngle()
```


Gets or sets the angle.

The angle.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```




**Returns:**
[Color](../../com.aspose.psd/color)
### getColorPoints() {#getColorPoints--}
```
public IGradientColorPoint[] getColorPoints()
```


Gets the color points.

The color points.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getDither() {#getDither--}
```
public boolean getDither()
```




**Returns:**
boolean
### getGradientInterval() {#getGradientInterval--}
```
public double getGradientInterval()
```


Gets or sets the gradient interval.

The gradient interval.

**Returns:**
double
### getGradientName() {#getGradientName--}
```
public String getGradientName()
```


Gets or sets the name of the gradient.

The name of the gradient.

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public int getGradientType()
```




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
### getHorizontalOffset() {#getHorizontalOffset--}
```
public double getHorizontalOffset()
```


Gets or sets the horizontal offset.

The horizontal offset.

**Returns:**
double
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
### getOffset_internalized() {#getOffset-internalized--}
```
public OffsetEntity getOffset_internalized()
```


Gets or sets the offset.

The offset.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
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


Gets the minimal psd version required for layer resource. 0 indicates no restrictions.

**Returns:**
int
### getReverse() {#getReverse--}
```
public boolean getReverse()
```




**Returns:**
boolean
### getScale() {#getScale--}
```
public int getScale()
```


Gets or sets the scale.

The scale.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Gets the layer resource signature.

**Returns:**
int
### getTransparencyPoints() {#getTransparencyPoints--}
```
public IGradientTransparencyPoint[] getTransparencyPoints()
```


Gets the transparency points.

The transparency points.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getVerticalOffset() {#getVerticalOffset--}
```
public double getVerticalOffset()
```


Gets or sets the vertical offset.

The vertical offset.

**Returns:**
double
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

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public void setAlignWithLayer(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public void setColorPoints(IGradientColorPoint[] value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public void setDither(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setGradientInterval(double value) {#setGradientInterval-double-}
```
public void setGradientInterval(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public void setGradientName(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public void setGradientType(int value)
```




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

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public void setHorizontalOffset(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setOffset_internalized(OffsetEntity value) {#setOffset-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public void setOffset_internalized(OffsetEntity value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public void setReverse(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setScale(int value) {#setScale-int-}
```
public void setScale(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public void setTransparencyPoints(IGradientTransparencyPoint[] value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public void setVerticalOffset(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

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

