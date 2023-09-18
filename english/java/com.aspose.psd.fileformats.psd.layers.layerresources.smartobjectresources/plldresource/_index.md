---
title: PlLdResource
second_title: Aspose.PSD for Java API Reference
description: Defines the PlLdResource class that contains information about a placed layer in the PSD file.
type: docs
weight: 10
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource)
```
public class PlLdResource extends PlacedResource
```

Defines the PlLdResource class that contains information about a placed layer in the PSD file. Is is used to support smart object layers in the Adobe® Photoshop® images. It was replaced by SoLdResource in the Adobe® Photoshop® CS3
## Constructors

| Constructor | Description |
| --- | --- |
| [PlLdResource()](#PlLdResource--) | Initializes a new instance of the [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) class. |
## Fields

| Field | Description |
| --- | --- |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | The custom envelope warp name |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | The default warp class name |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | The default warp class name |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | The expected warp descriptor version |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | The expected warp version |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | The horizontal identifier name |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | The mesh points key name |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | The orientation identifier name |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | The expected version value |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | The PSB header version |
| [PsbResourceSignature](#PsbResourceSignature) | The PSB-specific resource signature. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | The PSD header version |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | The rational point class identifier name |
| [ResourceSignature](#ResourceSignature) | The common resource signature. |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | The size of double |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | The size of int |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | The transform value count |
| [TypeToolKey](#TypeToolKey) | The type tool info key. |
| [TypeValue_internalized](#TypeValue-internalized) | The expected type value |
| [UOrderKey_internalized](#UOrderKey-internalized) | The u order key |
| [VOrderKey_internalized](#VOrderKey-internalized) | The v order key |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | The vertical identifier name |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | The warp custom name |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | The warp header length. |
| [WarpKey_internalized](#WarpKey-internalized) | The warp key. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | The warp none name |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | The warp perspective key |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | The warp perspective other |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | The warp rotate key |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | The warp style key |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | The warp value key |
| [ZeroChar_internalized](#ZeroChar-internalized) | The zero character. |
## Methods

| Method | Description |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | Asserts that the specified actual value equals to the expected value. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Checks the and set if resource is PSB specific. |
| [create_internalized(System.Guid uniqueId, boolean isCustom)](#create-internalized-com.aspose.ms.System.Guid-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Gets or sets the anti alias policy of the placed layer in the PSD image. |
| [getBottom()](#getBottom--) | Gets or sets the bottom location of the placed layer in the PSD image. |
| [getBounds()](#getBounds--) | Gets or sets the bounds of the placed layer in the PSD file. |
| [getClass()](#getClass--) |  |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Gets or sets the default unit type for assigned values such as Left, Top, Right, Bottom, TransformMatrix. |
| [getHeader_internalized()](#getHeader-internalized--) | Gets or sets the header. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Gets or sets the measure unit of the horizontal mesh points. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
| [getItems()](#getItems--) | Gets or sets the warp items. |
| [getKey()](#getKey--) | Gets the PlLd resource key. |
| [getLeft()](#getLeft--) | Gets or sets the left location of the placed layer in the PSD file. |
| [getLength()](#getLength--) | Gets the PlLd resource length in bytes. |
| [getPageNumber()](#getPageNumber--) | Gets or sets the page number of the placed layer in the PSD file. |
| [getPerspective()](#getPerspective--) | Gets or sets the perspective value of the placed layer in the PSD file. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Gets or sets the perspective other value of the placed layer in the PSD file. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Gets or sets the type of the placed layer in the PSD file. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Gets the prefix length. |
| [getPsdVersion()](#getPsdVersion--) | Gets the minimal psd version required for the PlLd resource. |
| [getRight()](#getRight--) | Gets or sets the right location of the placed layer in the PSD file. |
| [getSignature()](#getSignature--) | Gets the PlLd resource signature. |
| [getTop()](#getTop--) | Gets or sets the top location of the placed layer in the PSD image. |
| [getTotalPages()](#getTotalPages--) | Gets or sets the total pages of the placed layer in the PSD file. |
| [getTransformMatrix()](#getTransformMatrix--) | Gets or sets the transform matrix of the placed layer in the PSD file. |
| [getUOrder()](#getUOrder--) | Gets or sets the U order value of the placed layer in the PSD file. |
| [getUniqueId()](#getUniqueId--) | Gets or sets the global unique identifier of the placed layer in the PSD image. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Gets or sets the V order value of the placed layer in the PSD file. |
| [getValue()](#getValue--) | Gets or sets the warp value of the placed layer in the PSD image. |
| [getVersion()](#getVersion--) | Gets the version of the placed layer in the PSD file, usually 3. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Gets or sets the measure unit of the vertical mesh points. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | Gets or sets the class ID. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | Gets or sets the warp class name. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | Gets or sets the warp descriptor version. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | The warp items. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | Gets or sets the warp version. |
| [get_Item(String index)](#get-Item-java.lang.String-) | Gets the \{@link \#\#Aspose\#PSD\#FileFormats\#Psd\#Layers\#LayerResources\} at the specified index. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | Gets a value indicating whether this instance has bounds units. |
| [hashCode()](#hashCode--) |  |
| [initializeItems_internalized()](#initializeItems-internalized--) |  |
| [isCustom()](#isCustom--) | Gets or sets a value indicating whether this instance warp style is custom. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determines whether the resource is PSB specific. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Gets a value indicating whether this instance is resource PSB specific. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | Gets or sets a value indicating whether this instance rotate orientation is horizontal. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Saves the PlLD resource to the specified stream container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Saves the custom resource header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Saves the header signature, identifier and length. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Gets or sets the anti alias policy of the placed layer in the PSD image. |
| [setBottom(double value)](#setBottom-double-) | Gets or sets the bottom location of the placed layer in the PSD image. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Gets or sets the bounds of the placed layer in the PSD file. |
| [setCustom(boolean value)](#setCustom-boolean-) | Gets or sets a value indicating whether this instance warp style is custom. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Gets or sets the default unit type for assigned values such as Left, Top, Right, Bottom, TransformMatrix. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Gets or sets the header. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Gets or sets the measure unit of the horizontal mesh points. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Gets or sets the warp items. |
| [setLeft(double value)](#setLeft-double-) | Gets or sets the left location of the placed layer in the PSD file. |
| [setPageNumber(int value)](#setPageNumber-int-) | Gets or sets the page number of the placed layer in the PSD file. |
| [setPerspective(double value)](#setPerspective-double-) | Gets or sets the perspective value of the placed layer in the PSD file. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Gets or sets the perspective other value of the placed layer in the PSD file. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Gets or sets the type of the placed layer in the PSD file. |
| [setRight(double value)](#setRight-double-) | Gets or sets the right location of the placed layer in the PSD file. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | Gets or sets a value indicating whether this instance rotate orientation is horizontal. |
| [setTop(double value)](#setTop-double-) | Gets or sets the top location of the placed layer in the PSD image. |
| [setTotalPages(int value)](#setTotalPages-int-) | Gets or sets the total pages of the placed layer in the PSD file. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Gets or sets the transform matrix of the placed layer in the PSD file. |
| [setUOrder(int value)](#setUOrder-int-) | Gets or sets the U order value of the placed layer in the PSD file. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Gets or sets the global unique identifier of the placed layer in the PSD image. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Gets or sets the V order value of the placed layer in the PSD file. |
| [setValue(double value)](#setValue-double-) | Gets or sets the warp value of the placed layer in the PSD image. |
| [setVersion(int value)](#setVersion-int-) | Gets the version of the placed layer in the PSD file, usually 3. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Gets or sets the measure unit of the vertical mesh points. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Gets or sets the class ID. |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | Gets or sets the warp class name. |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | Gets or sets the warp descriptor version. |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | Gets or sets the warp version. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PlLdResource() {#PlLdResource--}
```
public PlLdResource()
```


Initializes a new instance of the [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) class. This default constructor is designed for using by PlLdResourceLoader. Use [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) for creating PlLdResource classes.

### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


The custom envelope warp name

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


The default warp class name

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


The default warp class name

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


The expected warp descriptor version

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


The expected warp version

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


The horizontal identifier name

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


The mesh points key name

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


The orientation identifier name

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


The expected version value

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

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


The rational point class identifier name

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


The common resource signature.

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


The size of double

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


The size of int

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


The transform value count

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


The type tool info key.

### TypeValue_internalized {#TypeValue-internalized}
```
public static final String TypeValue_internalized
```


The expected type value

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


The u order key

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


The v order key

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


The vertical identifier name

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


The warp custom name

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


The warp header length.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


The warp key. Also the default warp class name.

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


The warp none name

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


The warp perspective key

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


The warp perspective other

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


The warp rotate key

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


The warp style key

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


The warp value key

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


The zero character.

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


Asserts that the specified actual value equals to the expected value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| actualValue | java.lang.Object | The actual value. |
| expectedValue | java.lang.Object | The expected value. |
| message | java.lang.String | The message. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Checks the and set if resource is PSB specific. Some resources are not recognized for now, but we have full list of PSB specific resources which changes their behaviour on save. So we need to check this in UnknownResource at least

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int | The key. |

### create_internalized(System.Guid uniqueId, boolean isCustom) {#create-internalized-com.aspose.ms.System.Guid-boolean-}
```
public static PlLdResource create_internalized(System.Guid uniqueId, boolean isCustom)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid |  |
| isCustom | boolean |  |

**Returns:**
[PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource)
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
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


Gets or sets the anti alias policy of the placed layer in the PSD image.

Value: The anti alias policy of the placed layer.

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


Gets or sets the bottom location of the placed layer in the PSD image.

Value: The bottom location of the placed layer.

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Gets or sets the bounds of the placed layer in the PSD file.

Value: The placed layer bounds.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


Gets or sets the default unit type for assigned values such as Left, Top, Right, Bottom, TransformMatrix.

Value: The default measure unit type.

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
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


Gets or sets the measure unit of the horizontal mesh points.

Value: The measure unit of the horizontal mesh points.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


Gets or sets the horizontal mesh points of the placed layer in the PSD file.

Value: The horizontal mesh points of the placed layer.

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


Gets or sets the warp items.

Value: The warp items.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public int getKey()
```


Gets the PlLd resource key.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final double getLeft()
```


Gets or sets the left location of the placed layer in the PSD file.

Value: The left location of the placed layer.

**Returns:**
double
### getLength() {#getLength--}
```
public int getLength()
```


Gets the PlLd resource length in bytes.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Gets or sets the page number of the placed layer in the PSD file.

Value: The page number of the placed layer.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


Gets or sets the perspective value of the placed layer in the PSD file.

Value: The perspective value of the placed layer.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


Gets or sets the perspective other value of the placed layer in the PSD file.

Value: The perspective other value of the placed layer.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


Gets or sets the type of the placed layer in the PSD file.

Value: The type of the placed layer.

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


Gets the minimal psd version required for the PlLd resource. 0 indicates no restrictions.

**Returns:**
int
### getRight() {#getRight--}
```
public final double getRight()
```


Gets or sets the right location of the placed layer in the PSD file.

Value: The right location of the placed layer.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


Gets the PlLd resource signature.

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


Gets or sets the top location of the placed layer in the PSD image.

Value: The top location of the placed layer.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Gets or sets the total pages of the placed layer in the PSD file.

Value: The total pages of the placed layer.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


Gets or sets the transform matrix of the placed layer in the PSD file.

Value: The transform matrix of the placed layer.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


Gets or sets the U order value of the placed layer in the PSD file.

Value: The U order value of the placed layer.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


Gets or sets the global unique identifier of the placed layer in the PSD image.

Value: The unique identifier of the placed layer.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public final int getVOrder()
```


Gets or sets the V order value of the placed layer in the PSD file.

Value: The V order value of the placed layer.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Gets or sets the warp value of the placed layer in the PSD image.

Value: The warp value of the placed layer.

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Gets the version of the placed layer in the PSD file, usually 3.

Value: The placed layer version.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


Gets or sets the measure unit of the vertical mesh points.

Value: The measure unit of the vertical mesh points.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


Gets or sets the horizontal mesh points of the placed layer in the PSD file.

Value: The horizontal mesh points of the placed layer.

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


Gets or sets the class ID.

Value: The class ID.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


Gets or sets the warp class name.

Value: The warp class name.

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


Gets or sets the warp descriptor version.

Value: The warp descriptor version.

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


The warp items.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


Gets or sets the warp version.

Value: The warp version.

**Returns:**
int
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


Gets the \{@link \#\#Aspose\#PSD\#FileFormats\#Psd\#Layers\#LayerResources\} at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | java.lang.String | The key name. Value: The \{@link \#\#Aspose\#PSD\#FileFormats\#Psd\#Layers\#LayerResources\}. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found \{@link \#\#Aspose\#PSD\#FileFormats\#Psd\#Layers\#LayerResources\} instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


Gets a value indicating whether this instance has bounds units.

Value:  true  if this instance has bounds units; otherwise,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initializeItems_internalized() {#initializeItems-internalized--}
```
public void initializeItems_internalized()
```




### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


Gets or sets a value indicating whether this instance warp style is custom. If true it contains mesh points. If set to false it erases mesh points.

Value:  true  if the placed layer has custom style; otherwise,  false .

**Returns:**
boolean
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
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


Gets or sets a value indicating whether this instance rotate orientation is horizontal.

Value:  true  if the rotate orientation is horizontal; otherwise,  false .

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


Saves the PlLD resource to the specified stream container.

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

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


Gets or sets the anti alias policy of the placed layer in the PSD image.

Value: The anti alias policy of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Gets or sets the bottom location of the placed layer in the PSD image.

Value: The bottom location of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Gets or sets the bounds of the placed layer in the PSD file.

Value: The placed layer bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


Gets or sets a value indicating whether this instance warp style is custom. If true it contains mesh points. If set to false it erases mesh points.

Value:  true  if the placed layer has custom style; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


Gets or sets the default unit type for assigned values such as Left, Top, Right, Bottom, TransformMatrix.

Value: The default measure unit type.

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

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


Gets or sets the measure unit of the horizontal mesh points.

Value: The measure unit of the horizontal mesh points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


Gets or sets the horizontal mesh points of the placed layer in the PSD file.

Value: The horizontal mesh points of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


Gets or sets the warp items.

Value: The warp items.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Gets or sets the left location of the placed layer in the PSD file.

Value: The left location of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Gets or sets the page number of the placed layer in the PSD file.

Value: The page number of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


Gets or sets the perspective value of the placed layer in the PSD file.

Value: The perspective value of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


Gets or sets the perspective other value of the placed layer in the PSD file.

Value: The perspective other value of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


Gets or sets the type of the placed layer in the PSD file.

Value: The type of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Gets or sets the right location of the placed layer in the PSD file.

Value: The right location of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


Gets or sets a value indicating whether this instance rotate orientation is horizontal.

Value:  true  if the rotate orientation is horizontal; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Gets or sets the top location of the placed layer in the PSD image.

Value: The top location of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


Gets or sets the total pages of the placed layer in the PSD file.

Value: The total pages of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


Gets or sets the transform matrix of the placed layer in the PSD file.

Value: The transform matrix of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


Gets or sets the U order value of the placed layer in the PSD file.

Value: The U order value of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


Gets or sets the global unique identifier of the placed layer in the PSD image.

Value: The unique identifier of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


Gets or sets the V order value of the placed layer in the PSD file.

Value: The V order value of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Gets or sets the warp value of the placed layer in the PSD image.

Value: The warp value of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Gets the version of the placed layer in the PSD file, usually 3.

Value: The placed layer version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


Gets or sets the measure unit of the vertical mesh points.

Value: The measure unit of the vertical mesh points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


Gets or sets the horizontal mesh points of the placed layer in the PSD file.

Value: The horizontal mesh points of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


Gets or sets the class ID.

Value: The class ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


Gets or sets the warp class name.

Value: The warp class name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


Gets or sets the warp descriptor version.

Value: The warp descriptor version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


Gets or sets the warp version.

Value: The warp version.

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

