---
title: "WarpSettings"
second_title: "Aspose.PSD 的 Java API 参考"
description: "带扭曲的图层参数"
type: docs
weight: 11
url: /zh/java/com.aspose.psd.fileformats.psd.layers.warp/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

带扭曲的图层参数
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | 初始化 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) 类的新实例。 |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | 初始化 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [DefaultProcessingArea_internalized](#DefaultProcessingArea-internalized) | ProcessingArea 的默认值 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | 获取或设置扭曲图像的边界 |
| [getClass()](#getClass--) |  |
| [getMeshPoints()](#getMeshPoints--) | Photoshop 网格点 |
| [getProcessingArea()](#getProcessingArea--) | 获取或设置处理区域大小的值。 |
| [getRotate()](#getRotate--) | 获取或设置旋转值 |
| [getStyle()](#getStyle--) | 获取或设置扭曲的样式 |
| [getValue()](#getValue--) | 获取或设置扭曲的值 |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | 获取或设置 MeshPoints 中的用户更改 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | 获取或设置扭曲图像的边界 |
| [setMeshPoints(Point[] value)](#setMeshPoints-com.aspose.psd.Point---) | Photoshop 网格点 |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | 它返回来自资源向量的网格点 |
| [setProcessingArea(int value)](#setProcessingArea-int-) | 获取或设置处理区域大小的值。 |
| [setRotate(int value)](#setRotate-int-) | 获取或设置旋转值 |
| [setStyle(int value)](#setStyle-int-) | 获取或设置扭曲的样式 |
| [setValue(double value)](#setValue-double-) | 获取或设置扭曲的值 |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | 它将此扭曲参数保存到 PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | 它将此扭曲参数保存到 PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


初始化 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | 带有扭曲设置的 PS 项目 |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | 扭曲图像的边界 |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


初始化 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | 带有扭曲设置的资源 |

### DefaultProcessingArea_internalized {#DefaultProcessingArea-internalized}
```
public static final int DefaultProcessingArea_internalized
```


ProcessingArea 的默认值

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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


获取或设置扭曲图像的边界

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMeshPoints() {#getMeshPoints--}
```
public final Point[] getMeshPoints()
```


Photoshop 网格点

**Returns:**
com.aspose.psd.Point[]
### getProcessingArea() {#getProcessingArea--}
```
public final int getProcessingArea()
```


获取或设置处理区域大小的值。默认值为 10。范围为 [2;40]

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


获取或设置旋转值

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


获取或设置扭曲的样式

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


获取或设置扭曲的值

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefaultMeshPoints_internalized() {#isDefaultMeshPoints-internalized--}
```
public final boolean isDefaultMeshPoints_internalized()
```


获取或设置 MeshPoints 中的用户更改

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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


获取或设置扭曲图像的边界

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMeshPoints(Point[] value) {#setMeshPoints-com.aspose.psd.Point---}
```
public final void setMeshPoints(Point[] value)
```


Photoshop 网格点

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


它返回来自资源向量的网格点

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | 带有扭曲设置的资源 |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setProcessingArea(int value) {#setProcessingArea-int-}
```
public final void setProcessingArea(int value)
```


获取或设置处理区域大小的值。默认值为 10。范围为 [2;40]

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


获取或设置旋转值

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


获取或设置扭曲的样式

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


获取或设置扭曲的值

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


它将此扭曲参数保存到 PlacedResource

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | 带有扭曲设置的资源 |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - 来自此 WarpParams 的扭曲参数资源
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


它将此扭曲参数保存到 PlacedResource

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | 带有扭曲设置的资源 |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - Resource with warp params from this WarpParams
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

