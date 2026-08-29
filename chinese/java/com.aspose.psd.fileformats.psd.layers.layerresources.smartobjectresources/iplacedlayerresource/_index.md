---
title: "IPlacedLayerResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "定义 IPlacedLayerResource 接口，包含 PSD 文件中已放置图层的信息。"
type: docs
weight: 17
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

定义 IPlacedLayerResource 接口，该接口包含 PSD 文件中已放置图层的信息。它是用于在 Adobe\ufffd Photoshop\ufffd 图像中标识 PlLd、Sold 和 Sole 资源的标记接口。它用于在 Adobe\ufffd Photoshop\ufffd 图像中支持智能对象图层。
## Methods

| Method | 描述 |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | 获取或设置 PSD 图像中已放置图层的抗锯齿策略。 |
| [getBottom()](#getBottom--) | 获取或设置 PSD 图像中已放置图层的底部位置。 |
| [getBounds()](#getBounds--) | 获取或设置 PSD 文件中已放置图层的边界。 |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | 获取或设置水平网格点的测量单位。 |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
| [getItems()](#getItems--) | 获取或设置扭曲项。 |
| [getLeft()](#getLeft--) | 获取或设置 PSD 文件中已放置图层的左侧位置。 |
| [getPageNumber()](#getPageNumber--) | 获取或设置 PSD 文件中已放置图层的页码。 |
| [getPerspective()](#getPerspective--) | 获取或设置放置在 PSD 文件中的图层的透视值。 |
| [getPerspectiveOther()](#getPerspectiveOther--) | 获取或设置放置在 PSD 文件中的图层的其他透视值。 |
| [getPlacedLayerType()](#getPlacedLayerType--) | 获取或设置放置在 PSD 文件中的图层的类型。 |
| [getRight()](#getRight--) | 获取或设置放置在 PSD 文件中的图层的右侧位置。 |
| [getTop()](#getTop--) | 获取或设置放置在 PSD 图像中的图层的顶部位置。 |
| [getTotalPages()](#getTotalPages--) | 获取或设置放置在 PSD 文件中的图层的总页数。 |
| [getTransformMatrix()](#getTransformMatrix--) | 获取或设置放置在 PSD 文件中的图层的变换矩阵。 |
| [getUOrder()](#getUOrder--) | 获取或设置放置在 PSD 文件中的图层的 U 顺序值。 |
| [getUniqueId()](#getUniqueId--) | 获取或设置 PSD 图像中智能对象已放置图层的全局唯一标识符。 |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | 获取或设置放置在 PSD 文件中的图层的 V 顺序值。 |
| [getValue()](#getValue--) | 获取或设置放置在 PSD 图像中的图层的扭曲值。 |
| [getVersion()](#getVersion--) | 获取 PSD 文件中已放置图层的版本，通常为 3-5。 |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | 获取或设置垂直网格点的度量单位。 |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
| [isCustom()](#isCustom--) | 获取或设置一个值，指示此实例的扭曲样式是否为自定义。 |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | 获取或设置 PSD 图像中已放置图层的抗锯齿策略。 |
| [setBottom(double value)](#setBottom-double-) | 获取或设置 PSD 图像中已放置图层的底部位置。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | 获取或设置 PSD 文件中已放置图层的边界。 |
| [setCustom(boolean value)](#setCustom-boolean-) | 获取或设置一个值，指示此实例的扭曲样式是否为自定义。 |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | 获取或设置水平网格点的测量单位。 |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | 获取或设置扭曲项。 |
| [setLeft(double value)](#setLeft-double-) | 获取或设置 PSD 文件中已放置图层的左侧位置。 |
| [setPageNumber(int value)](#setPageNumber-int-) | 获取或设置 PSD 文件中已放置图层的页码。 |
| [setPerspective(double value)](#setPerspective-double-) | 获取或设置放置在 PSD 文件中的图层的透视值。 |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | 获取或设置放置在 PSD 文件中的图层的其他透视值。 |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | 获取或设置放置在 PSD 文件中的图层的类型。 |
| [setRight(double value)](#setRight-double-) | 获取或设置放置在 PSD 文件中的图层的右侧位置。 |
| [setTop(double value)](#setTop-double-) | 获取或设置放置在 PSD 图像中的图层的顶部位置。 |
| [setTotalPages(int value)](#setTotalPages-int-) | 获取或设置放置在 PSD 文件中的图层的总页数。 |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | 获取或设置放置在 PSD 文件中的图层的变换矩阵。 |
| [setUOrder(int value)](#setUOrder-int-) | 获取或设置放置在 PSD 文件中的图层的 U 顺序值。 |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | 获取或设置 PSD 图像中智能对象已放置图层的全局唯一标识符。 |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | 获取或设置放置在 PSD 文件中的图层的 V 顺序值。 |
| [setValue(double value)](#setValue-double-) | 获取或设置放置在 PSD 图像中的图层的扭曲值。 |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | 获取或设置垂直网格点的度量单位。 |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


获取或设置 PSD 图像中已放置图层的抗锯齿策略。

值：已放置图层的抗锯齿策略。

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


获取或设置 PSD 图像中已放置图层的底部位置。

值：已放置图层的底部位置。

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


获取或设置 PSD 文件中已放置图层的边界。

值：已放置图层的边界。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


获取或设置水平网格点的测量单位。

值：水平网格点的测量单位。

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


获取或设置 PSD 文件中已放置图层的水平网格点。

值：已放置图层的水平网格点。

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


获取或设置扭曲项。

值：扭曲项。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


获取或设置 PSD 文件中已放置图层的左侧位置。

值：已放置图层的左侧位置。

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


获取或设置 PSD 文件中已放置图层的页码。

值：已放置图层的页码。

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


获取或设置放置在 PSD 文件中的图层的透视值。

值：已放置图层的透视值。

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


获取或设置放置在 PSD 文件中的图层的其他透视值。

值：已放置图层的其他透视值。

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


获取或设置放置在 PSD 文件中的图层的类型。

值：已放置图层的类型。

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


获取或设置放置在 PSD 文件中的图层的右侧位置。

值：已放置图层的右侧位置。

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


获取或设置放置在 PSD 图像中的图层的顶部位置。

值：已放置图层的顶部位置。

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


获取或设置放置在 PSD 文件中的图层的总页数。

值：已放置图层的总页数。

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


获取或设置放置在 PSD 文件中的图层的变换矩阵。

值：已放置图层的变换矩阵。

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


获取或设置放置在 PSD 文件中的图层的 U 顺序值。

值：已放置图层的U顺序值。

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


获取或设置 PSD 图像中智能对象已放置图层的全局唯一标识符。

值：已放置图层的唯一标识符。

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


获取或设置放置在 PSD 文件中的图层的 V 顺序值。

值：已放置图层的V顺序值。

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


获取或设置放置在 PSD 图像中的图层的扭曲值。

值：已放置图层的扭曲值。

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


获取 PSD 文件中已放置图层的版本，通常为 3-5。

值：已放置或智能对象图层的版本。

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


获取或设置垂直网格点的度量单位。

值：垂直网格点的测量单位。

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


获取或设置 PSD 文件中已放置图层的水平网格点。

值：已放置图层的水平网格点。

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


获取或设置一个值，指示此实例的扭曲样式是否为自定义。如果为 true，则包含网格点。如果设置为 false，则擦除网格点。

值：如果已放置或智能对象图层资源具有自定义样式，则为 true；否则为 false。

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


获取或设置 PSD 图像中已放置图层的抗锯齿策略。

值：已放置图层的抗锯齿策略。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


获取或设置 PSD 图像中已放置图层的底部位置。

值：已放置图层的底部位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


获取或设置 PSD 文件中已放置图层的边界。

值：已放置图层的边界。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


获取或设置一个值，指示此实例的扭曲样式是否为自定义。如果为 true，则包含网格点。如果设置为 false，则擦除网格点。

值：如果已放置或智能对象图层资源具有自定义样式，则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


获取或设置水平网格点的测量单位。

值：水平网格点的测量单位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


获取或设置 PSD 文件中已放置图层的水平网格点。

值：已放置图层的水平网格点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


获取或设置扭曲项。

值：扭曲项。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


获取或设置 PSD 文件中已放置图层的左侧位置。

值：已放置图层的左侧位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


获取或设置 PSD 文件中已放置图层的页码。

值：已放置图层的页码。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


获取或设置放置在 PSD 文件中的图层的透视值。

值：已放置图层的透视值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


获取或设置放置在 PSD 文件中的图层的其他透视值。

值：已放置图层的其他透视值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


获取或设置放置在 PSD 文件中的图层的类型。

值：已放置图层的类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


获取或设置放置在 PSD 文件中的图层的右侧位置。

值：已放置图层的右侧位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


获取或设置放置在 PSD 图像中的图层的顶部位置。

值：已放置图层的顶部位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


获取或设置放置在 PSD 文件中的图层的总页数。

值：已放置图层的总页数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


获取或设置放置在 PSD 文件中的图层的变换矩阵。

值：已放置图层的变换矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


获取或设置放置在 PSD 文件中的图层的 U 顺序值。

值：已放置图层的U顺序值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


获取或设置 PSD 图像中智能对象已放置图层的全局唯一标识符。

值：已放置图层的唯一标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


获取或设置放置在 PSD 文件中的图层的 V 顺序值。

值：已放置图层的V顺序值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


获取或设置放置在 PSD 图像中的图层的扭曲值。

值：已放置图层的扭曲值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


获取或设置垂直网格点的度量单位。

值：垂直网格点的测量单位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


获取或设置 PSD 文件中已放置图层的水平网格点。

值：已放置图层的水平网格点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double[] |  |

