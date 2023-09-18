---
title: IPlacedLayerResource
second_title: Aspose.PSD for Java API Reference
description: Defines the IPlacedLayerResource interface that contains information about a placed layer in the PSD file.
type: docs
weight: 17
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

Defines the IPlacedLayerResource interface that contains information about a placed layer in the PSD file. Is is a markup interface used to designate PlLd, Sold and Sole resources in the Adobe\\ufffd Photoshop\\ufffd images. Is is used to support smart object layers in the Adobe\\ufffd Photoshop\\ufffd images.
## Methods

| Method | Description |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Gets or sets the anti alias policy of the placed layer in the PSD image. |
| [getBottom()](#getBottom--) | Gets or sets the bottom location of the placed layer in the PSD image. |
| [getBounds()](#getBounds--) | Gets or sets the bounds of the placed layer in the PSD file. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Gets or sets the measure unit of the horizontal mesh points. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
| [getItems()](#getItems--) | Gets or sets the warp items. |
| [getLeft()](#getLeft--) | Gets or sets the left location of the placed layer in the PSD file. |
| [getPageNumber()](#getPageNumber--) | Gets or sets the page number of the placed layer in the PSD file. |
| [getPerspective()](#getPerspective--) | Gets or sets the perspective value of the placed layer in the PSD file. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Gets or sets the perspective other value of the placed layer in the PSD file. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Gets or sets the type of the placed layer in the PSD file. |
| [getRight()](#getRight--) | Gets or sets the right location of the placed layer in the PSD file. |
| [getTop()](#getTop--) | Gets or sets the top location of the placed layer in the PSD image. |
| [getTotalPages()](#getTotalPages--) | Gets or sets the total pages of the placed layer in the PSD file. |
| [getTransformMatrix()](#getTransformMatrix--) | Gets or sets the transform matrix of the placed layer in the PSD file. |
| [getUOrder()](#getUOrder--) | Gets or sets the U order value of the placed layer in the PSD file. |
| [getUniqueId()](#getUniqueId--) | Gets or sets the global unique identifier of the or smart object placed layer in the PSD image. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Gets or sets the V order value of the placed layer in the PSD file. |
| [getValue()](#getValue--) | Gets or sets the warp value of the placed layer in the PSD image. |
| [getVersion()](#getVersion--) | Gets the version of the placed layer in the PSD file, usually 3-5. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Gets or sets the measure unit of the vertical mesh points. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
| [isCustom()](#isCustom--) | Gets or sets a value indicating whether this instance warp style is custom. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Gets or sets the anti alias policy of the placed layer in the PSD image. |
| [setBottom(double value)](#setBottom-double-) | Gets or sets the bottom location of the placed layer in the PSD image. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Gets or sets the bounds of the placed layer in the PSD file. |
| [setCustom(boolean value)](#setCustom-boolean-) | Gets or sets a value indicating whether this instance warp style is custom. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Gets or sets the measure unit of the horizontal mesh points. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Gets or sets the warp items. |
| [setLeft(double value)](#setLeft-double-) | Gets or sets the left location of the placed layer in the PSD file. |
| [setPageNumber(int value)](#setPageNumber-int-) | Gets or sets the page number of the placed layer in the PSD file. |
| [setPerspective(double value)](#setPerspective-double-) | Gets or sets the perspective value of the placed layer in the PSD file. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Gets or sets the perspective other value of the placed layer in the PSD file. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Gets or sets the type of the placed layer in the PSD file. |
| [setRight(double value)](#setRight-double-) | Gets or sets the right location of the placed layer in the PSD file. |
| [setTop(double value)](#setTop-double-) | Gets or sets the top location of the placed layer in the PSD image. |
| [setTotalPages(int value)](#setTotalPages-int-) | Gets or sets the total pages of the placed layer in the PSD file. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Gets or sets the transform matrix of the placed layer in the PSD file. |
| [setUOrder(int value)](#setUOrder-int-) | Gets or sets the U order value of the placed layer in the PSD file. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Gets or sets the global unique identifier of the or smart object placed layer in the PSD image. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Gets or sets the V order value of the placed layer in the PSD file. |
| [setValue(double value)](#setValue-double-) | Gets or sets the warp value of the placed layer in the PSD image. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Gets or sets the measure unit of the vertical mesh points. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


Gets or sets the anti alias policy of the placed layer in the PSD image.

Value: The anti alias policy of the placed layer.

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


Gets or sets the bottom location of the placed layer in the PSD image.

Value: The bottom location of the placed layer.

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Gets or sets the bounds of the placed layer in the PSD file.

Value: The placed layer bounds.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


Gets or sets the measure unit of the horizontal mesh points.

Value: The measure unit of the horizontal mesh points.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


Gets or sets the horizontal mesh points of the placed layer in the PSD file.

Value: The horizontal mesh points of the placed layer.

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


Gets or sets the warp items.

Value: The warp items.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


Gets or sets the left location of the placed layer in the PSD file.

Value: The left location of the placed layer.

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Gets or sets the page number of the placed layer in the PSD file.

Value: The page number of the placed layer.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


Gets or sets the perspective value of the placed layer in the PSD file.

Value: The perspective value of the placed layer.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


Gets or sets the perspective other value of the placed layer in the PSD file.

Value: The perspective other value of the placed layer.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


Gets or sets the type of the placed layer in the PSD file.

Value: The type of the placed layer.

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


Gets or sets the right location of the placed layer in the PSD file.

Value: The right location of the placed layer.

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


Gets or sets the top location of the placed layer in the PSD image.

Value: The top location of the placed layer.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


Gets or sets the total pages of the placed layer in the PSD file.

Value: The total pages of the placed layer.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


Gets or sets the transform matrix of the placed layer in the PSD file.

Value: The transform matrix of the placed layer.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


Gets or sets the U order value of the placed layer in the PSD file.

Value: The U order value of the placed layer.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


Gets or sets the global unique identifier of the or smart object placed layer in the PSD image.

Value: The unique identifier of the placed layer.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public abstract System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public abstract int getVOrder()
```


Gets or sets the V order value of the placed layer in the PSD file.

Value: The V order value of the placed layer.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


Gets or sets the warp value of the placed layer in the PSD image.

Value: The warp value of the placed layer.

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


Gets the version of the placed layer in the PSD file, usually 3-5.

Value: The placed or smart object layer version.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


Gets or sets the measure unit of the vertical mesh points.

Value: The measure unit of the vertical mesh points.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


Gets or sets the horizontal mesh points of the placed layer in the PSD file.

Value: The horizontal mesh points of the placed layer.

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Gets or sets a value indicating whether this instance warp style is custom. If true it contains mesh points. If set to false it erases mesh points.

Value:  true  if the placed or smart object layer resource has custom style; otherwise,  false .

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


Gets or sets the anti alias policy of the placed layer in the PSD image.

Value: The anti alias policy of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


Gets or sets the bottom location of the placed layer in the PSD image.

Value: The bottom location of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


Gets or sets the bounds of the placed layer in the PSD file.

Value: The placed layer bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


Gets or sets a value indicating whether this instance warp style is custom. If true it contains mesh points. If set to false it erases mesh points.

Value:  true  if the placed or smart object layer resource has custom style; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


Gets or sets the measure unit of the horizontal mesh points.

Value: The measure unit of the horizontal mesh points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


Gets or sets the horizontal mesh points of the placed layer in the PSD file.

Value: The horizontal mesh points of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


Gets or sets the warp items.

Value: The warp items.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


Gets or sets the left location of the placed layer in the PSD file.

Value: The left location of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


Gets or sets the page number of the placed layer in the PSD file.

Value: The page number of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


Gets or sets the perspective value of the placed layer in the PSD file.

Value: The perspective value of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


Gets or sets the perspective other value of the placed layer in the PSD file.

Value: The perspective other value of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


Gets or sets the type of the placed layer in the PSD file.

Value: The type of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


Gets or sets the right location of the placed layer in the PSD file.

Value: The right location of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


Gets or sets the top location of the placed layer in the PSD image.

Value: The top location of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


Gets or sets the total pages of the placed layer in the PSD file.

Value: The total pages of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


Gets or sets the transform matrix of the placed layer in the PSD file.

Value: The transform matrix of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


Gets or sets the U order value of the placed layer in the PSD file.

Value: The U order value of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


Gets or sets the global unique identifier of the or smart object placed layer in the PSD image.

Value: The unique identifier of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


Gets or sets the V order value of the placed layer in the PSD file.

Value: The V order value of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


Gets or sets the warp value of the placed layer in the PSD image.

Value: The warp value of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


Gets or sets the measure unit of the vertical mesh points.

Value: The measure unit of the vertical mesh points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


Gets or sets the horizontal mesh points of the placed layer in the PSD file.

Value: The horizontal mesh points of the placed layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double[] |  |

