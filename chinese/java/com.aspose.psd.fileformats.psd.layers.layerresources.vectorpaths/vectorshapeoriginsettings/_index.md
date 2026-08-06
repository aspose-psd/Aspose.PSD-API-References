---
title: "VectorShapeOriginSettings"
second_title: "Aspose.PSD 的 Java API 参考"
description: "向量形状起始设置。"
type: docs
weight: 24
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings/
---

**Inheritance:**
java.lang.Object
```
public final class VectorShapeOriginSettings
```

向量形状起始设置。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)](#VectorShapeOriginSettings-boolean-int-) | 初始化一个新的 [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings) 类的实例。 |
| [VectorShapeOriginSettings()](#VectorShapeOriginSettings--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [KeyOriginIndex_internalized](#KeyOriginIndex-internalized) | 用于保存形状原点索引的描述符键。 |
| [KeyOriginRRectRadii_internalized](#KeyOriginRRectRadii-internalized) | 原点矩形半径描述符键 |
| [KeyOriginResolution_internalized](#KeyOriginResolution-internalized) | 原点分辨率描述符键 |
| [KeyOriginShapeBBox_internalized](#KeyOriginShapeBBox-internalized) | 原点形状边界框描述符键 |
| [KeyOriginType_internalized](#KeyOriginType-internalized) | 原点类型描述符键 |
| [KeyShapeInvalidated_internalized](#KeyShapeInvalidated-internalized) | 用于保存形状失效值的描述符键。 |
| [KnownKeys_internalized](#KnownKeys-internalized) | 已知属性键 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getId_internalized()](#getId-internalized--) | 获取唯一标识符。 |
| [getOriginBoxCorners()](#getOriginBoxCorners--) | 获取或设置原点框的角点。 |
| [getOriginIndex()](#getOriginIndex--) | 获取或设置原点形状索引。 |
| [getOriginRadiiRectangle()](#getOriginRadiiRectangle--) | 获取或设置原点半径矩形。 |
| [getOriginResolution()](#getOriginResolution--) | 获取或设置原点分辨率。 |
| [getOriginShapeBox()](#getOriginShapeBox--) | 获取或设置原点形状边界框。 |
| [getOriginType()](#getOriginType--) | 获取或设置原点的类型。 |
| [getTransform()](#getTransform--) | 获取或设置转换矩阵。 |
| [hasUnknownProperties_internalized()](#hasUnknownProperties-internalized--) | 获取或设置一个值，指示此实例是否具有未知属性。 |
| [hashCode()](#hashCode--) |  |
| [isChanged_internalized()](#isChanged-internalized--) | 获取或设置一个值，指示此实例是否已更改。 |
| [isOriginBoxCornersPresent()](#isOriginBoxCornersPresent--) | 获取一个值，指示此实例是否具有原点框角属性。 |
| [isOriginIndexPresent()](#isOriginIndexPresent--) | 获取一个值，指示此实例是否具有原点索引属性。 |
| [isOriginRadiiRectanglePresent()](#isOriginRadiiRectanglePresent--) | 获取一个值，指示此实例是否存在原点半径矩形。 |
| [isOriginResolutionPresent()](#isOriginResolutionPresent--) | 获取一个值，指示此实例是否具有原点分辨率属性。 |
| [isOriginShapeBBoxPresent()](#isOriginShapeBBoxPresent--) | 获取一个值，指示此实例是否具有矩形属性。 |
| [isOriginTypePresent()](#isOriginTypePresent--) | 获取一个值，指示此实例是否具有原点类型属性。 |
| [isPropertyPresent_internalized(String key)](#isPropertyPresent-internalized-java.lang.String-) | 确定是否存在具有指定键的属性。 |
| [isShapeInvalidated()](#isShapeInvalidated--) | 获取或设置一个值，指示形状是否已失效。 |
| [isShapeInvalidatedPresent()](#isShapeInvalidatedPresent--) | 获取一个值，指示此实例是否已设置形状失效属性。 |
| [isTransformPresent()](#isTransformPresent--) | 获取一个值，指示此实例是否具有变换属性。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChanged_internalized(boolean value)](#setChanged-internalized-boolean-) | 获取或设置一个值，指示此实例是否已更改。 |
| [setOriginBoxCorners(double[] value)](#setOriginBoxCorners-double---) | 获取或设置原点框的角点。 |
| [setOriginIndex(int value)](#setOriginIndex-int-) | 获取或设置原点形状索引。 |
| [setOriginRadiiRectangle(VectorShapeRadiiRectangle value)](#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-) | 获取或设置原点半径矩形。 |
| [setOriginResolution(double value)](#setOriginResolution-double-) | 获取或设置原点分辨率。 |
| [setOriginShapeBox(VectorShapeBoundingBox value)](#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-) | 获取或设置原点形状边界框。 |
| [setOriginType(int value)](#setOriginType-int-) | 获取或设置原点的类型。 |
| [setShapeInvalidated(boolean value)](#setShapeInvalidated-boolean-) | 获取或设置一个值，指示形状是否已失效。 |
| [setTransform(VectorShapeTransform value)](#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-) | 获取或设置转换矩阵。 |
| [setUnknownProperties_internalized(boolean value)](#setUnknownProperties-internalized-boolean-) | 获取或设置一个值，指示此实例是否具有未知属性。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex) {#VectorShapeOriginSettings-boolean-int-}
```
public VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)
```


初始化一个新的 [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings) 类的实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| isShapeInvalidated | boolean | 形状已失效的值。 |
| originIndex | int | 形状原点索引。 |

### VectorShapeOriginSettings() {#VectorShapeOriginSettings--}
```
public VectorShapeOriginSettings()
```


### KeyOriginIndex_internalized {#KeyOriginIndex-internalized}
```
public static final String KeyOriginIndex_internalized
```


用于保存形状原点索引的描述符键。

### KeyOriginRRectRadii_internalized {#KeyOriginRRectRadii-internalized}
```
public static final String KeyOriginRRectRadii_internalized
```


原点矩形半径描述符键

### KeyOriginResolution_internalized {#KeyOriginResolution-internalized}
```
public static final String KeyOriginResolution_internalized
```


原点分辨率描述符键

### KeyOriginShapeBBox_internalized {#KeyOriginShapeBBox-internalized}
```
public static final String KeyOriginShapeBBox_internalized
```


原点形状边界框描述符键

### KeyOriginType_internalized {#KeyOriginType-internalized}
```
public static final String KeyOriginType_internalized
```


原点类型描述符键

### KeyShapeInvalidated_internalized {#KeyShapeInvalidated-internalized}
```
public static final String KeyShapeInvalidated_internalized
```


用于保存形状失效值的描述符键。

### KnownKeys_internalized {#KnownKeys-internalized}
```
public static final String[] KnownKeys_internalized
```


已知属性键

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
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
### getId_internalized() {#getId-internalized--}
```
public final System.Guid getId_internalized()
```


获取唯一标识符。

值：唯一标识符。

**Returns:**
com.aspose.ms.System.Guid
### getOriginBoxCorners() {#getOriginBoxCorners--}
```
public final double[] getOriginBoxCorners()
```


获取或设置原点框的角点。

值：原点框角。

**Returns:**
double[]
### getOriginIndex() {#getOriginIndex--}
```
public final int getOriginIndex()
```


获取或设置原点形状索引。

**Returns:**
int
### getOriginRadiiRectangle() {#getOriginRadiiRectangle--}
```
public final VectorShapeRadiiRectangle getOriginRadiiRectangle()
```


获取或设置原点半径矩形。

值：原点半径矩形。

**Returns:**
[VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle)
### getOriginResolution() {#getOriginResolution--}
```
public final double getOriginResolution()
```


获取或设置原点分辨率。

值：原点分辨率。

**Returns:**
double
### getOriginShapeBox() {#getOriginShapeBox--}
```
public final VectorShapeBoundingBox getOriginShapeBox()
```


获取或设置原点形状边界框。

值：原点形状框。

**Returns:**
[VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox)
### getOriginType() {#getOriginType--}
```
public final int getOriginType()
```


获取或设置原点的类型。

值：原点的类型。

**Returns:**
int
### getTransform() {#getTransform--}
```
public final VectorShapeTransform getTransform()
```


获取或设置转换矩阵。

值：转换矩阵。

**Returns:**
[VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform)
### hasUnknownProperties_internalized() {#hasUnknownProperties-internalized--}
```
public final boolean hasUnknownProperties_internalized()
```


获取或设置一个值，指示此实例是否具有未知属性。

值：  true  如果此实例具有未知属性；否则，  false 。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isChanged_internalized() {#isChanged-internalized--}
```
public final boolean isChanged_internalized()
```


获取或设置一个值，指示此实例是否已更改。

值：  true  如果此实例已更改；否则，  false 。

**Returns:**
boolean
### isOriginBoxCornersPresent() {#isOriginBoxCornersPresent--}
```
public final boolean isOriginBoxCornersPresent()
```


获取一个值，指示此实例是否具有原点框角属性。

值：  true  如果此实例具有原点盒子角属性；否则，  false 。

**Returns:**
boolean
### isOriginIndexPresent() {#isOriginIndexPresent--}
```
public final boolean isOriginIndexPresent()
```


获取一个值，指示此实例是否具有原点索引属性。

值：  true  如果此实例具有原点索引属性；否则，  false 。

**Returns:**
boolean
### isOriginRadiiRectanglePresent() {#isOriginRadiiRectanglePresent--}
```
public final boolean isOriginRadiiRectanglePresent()
```


获取一个值，指示此实例是否存在原点半径矩形。

值：  true  如果此实例具有原点半径矩形属性；否则，  false 。

**Returns:**
boolean
### isOriginResolutionPresent() {#isOriginResolutionPresent--}
```
public final boolean isOriginResolutionPresent()
```


获取一个值，指示此实例是否具有原点分辨率属性。

值：  true  如果此实例具有原点分辨率属性；否则，  false 。

**Returns:**
boolean
### isOriginShapeBBoxPresent() {#isOriginShapeBBoxPresent--}
```
public final boolean isOriginShapeBBoxPresent()
```


获取一个值，指示此实例是否具有矩形属性。

值：  true  如果此实例具有原点形状矩形属性；否则，  false 。

**Returns:**
boolean
### isOriginTypePresent() {#isOriginTypePresent--}
```
public final boolean isOriginTypePresent()
```


获取一个值，指示此实例是否具有原点类型属性。

值：  true  如果此实例具有原点类型属性；否则，  false 。

**Returns:**
boolean
### isPropertyPresent_internalized(String key) {#isPropertyPresent-internalized-java.lang.String-}
```
public final boolean isPropertyPresent_internalized(String key)
```


确定是否存在具有指定键的属性。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | 属性键。 |

**Returns:**
布尔型 -  true  如果具有指定键的属性存在；否则，  false 。
### isShapeInvalidated() {#isShapeInvalidated--}
```
public final boolean isShapeInvalidated()
```


获取或设置一个值，指示形状是否已失效。

**Returns:**
boolean
### isShapeInvalidatedPresent() {#isShapeInvalidatedPresent--}
```
public final boolean isShapeInvalidatedPresent()
```


获取一个值，指示此实例是否已设置形状失效属性。

值：  true  如果此实例已设置形状失效属性；否则，  false 。

**Returns:**
boolean
### isTransformPresent() {#isTransformPresent--}
```
public final boolean isTransformPresent()
```


获取一个值，指示此实例是否具有变换属性。

值：  true  如果此实例具有变换属性；否则，  false 。

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




### setChanged_internalized(boolean value) {#setChanged-internalized-boolean-}
```
public final void setChanged_internalized(boolean value)
```


获取或设置一个值，指示此实例是否已更改。

值：  true  如果此实例已更改；否则，  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setOriginBoxCorners(double[] value) {#setOriginBoxCorners-double---}
```
public final void setOriginBoxCorners(double[] value)
```


获取或设置原点框的角点。

值：原点框角。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double[] |  |

### setOriginIndex(int value) {#setOriginIndex-int-}
```
public final void setOriginIndex(int value)
```


获取或设置原点形状索引。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setOriginRadiiRectangle(VectorShapeRadiiRectangle value) {#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-}
```
public final void setOriginRadiiRectangle(VectorShapeRadiiRectangle value)
```


获取或设置原点半径矩形。

值：原点半径矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle) |  |

### setOriginResolution(double value) {#setOriginResolution-double-}
```
public final void setOriginResolution(double value)
```


获取或设置原点分辨率。

值：原点分辨率。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setOriginShapeBox(VectorShapeBoundingBox value) {#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-}
```
public final void setOriginShapeBox(VectorShapeBoundingBox value)
```


获取或设置原点形状边界框。

值：原点形状框。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox) |  |

### setOriginType(int value) {#setOriginType-int-}
```
public final void setOriginType(int value)
```


获取或设置原点的类型。

值：原点的类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setShapeInvalidated(boolean value) {#setShapeInvalidated-boolean-}
```
public final void setShapeInvalidated(boolean value)
```


获取或设置一个值，指示形状是否已失效。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setTransform(VectorShapeTransform value) {#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-}
```
public final void setTransform(VectorShapeTransform value)
```


获取或设置转换矩阵。

值：转换矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform) |  |

### setUnknownProperties_internalized(boolean value) {#setUnknownProperties-internalized-boolean-}
```
public final void setUnknownProperties_internalized(boolean value)
```


获取或设置一个值，指示此实例是否具有未知属性。

值：  true  如果此实例具有未知属性；否则，  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

